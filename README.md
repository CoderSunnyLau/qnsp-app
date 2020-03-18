#文档

---

###发布配置

1. xxx；
2. xxx。


###项目配置

- pages.json 文件中的 pages 页面有改动时，需要复制一份到 static/pages.json，因为在uniapp编译时，会把根目录的 pages.json 文件修改掉。而 static 里的文件则不会被修改。pages.json 文件里的 pages 的每一项需要填写 name 属性，name 不可重复。通过 this.$page[name] 可在程序中的获取到该页面的路径信息，方便跳转时填写路径。
- 本项目图标库地址为 [图标库地址]()。图标库下载后，把 iconfont.ttf 文件放到 xxx 文件夹中。另外，复制 iconfont.css 文件中图标css的部分到 xxx/iconfont.css 中。


###注意事项

- 用 textarea 组件编辑的内容，在展示的时候，请使用<text></text>来展示，因为<view></view>展示的内容不支持换行。

### 使用工具，库，插件
- 1. [xx.js](https://github.com/xx) xx