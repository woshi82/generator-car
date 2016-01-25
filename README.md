# generator-car 

[![NPM](https://nodei.co/npm/generator-car.png)](https://nodei.co/npm/generator-car/)


## 安装

```
npm i -g yo bower generator-car
npm i -g fis-prepackager-i18n fis-prepackager-browserify
```

## 使用

### 生成项目

```
mkdir my-project
cd my-project
yo car
```

### 生成页面文件

```
yo car:view <viewName>
```

其中 `viewName` 为页面名

### 定义配置

```
yo car:config <configKey> [configValue]
```

其中 `configKey` 为配置名，`configValue` 为配置值。


### 生成组件文件

```
yo car:cmp new <componentName>
```

或者可以简写为

```
yo car:cmp n <componentName>
```

### 安装组件

```
yo car:cmp install <componentName>
```

或者可以简写为

```
yo car:cmp i <componentName>
```

### 生成国际化配置文件

```
yo car:i18n <language>
```

其中 `language` 为语言名称，如 `en`，`ru` 等


### 查看当前工具版本

```
yo car:v
```

## License

MIT
