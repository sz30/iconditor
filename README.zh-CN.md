Fonteditor Online Font Editor
==========

[English](./README.md) | [中文](./README.zh-CN.md)

使用`Fonteditor`在线编辑、转换、预览字体文件。

支持导入的字体格式有 ttf, woff, woff2, svg font, eot, otf等字体格式，支持ttf, woff, woff2等格式字体导出。

[线上地址](https://kekee000.github.io/fonteditor/)


![Fonteditor](./fonteditor-zh.jpg)

### 开发:

```
npm install && npm run dev
```

* `index.tpl`为入口模板文件，根据`index.tpl`生成`index.html`和`index-en.html`入口文件。
* jszip模块3.0 api有变动，若要升级，需要测试和修改导出zip模式

### 编译:

```
npm run build
```

### 测试:

```
npm run test
```

### DEMO:

```
npm run demo
```

### 相关项目

+ Fonteditor Core Lib: [fonteditor-core](https://github.com/kekee000/fonteditor-core)
+ fontmin: [fontmin](https://github.com/ecomfe/fontmin)

