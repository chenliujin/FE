# Electron
Electron is a framework for building cross-platform desktop applications with web technology.








- 双向数据绑定




- 登陆/登出
- 动态侧边栏
- 软键盘
- 分辨率
- 桌面最大化
- 隐藏最小化和关闭按钮




# browser-window
- 窗口默认最大化
- resizable Boolean (可选) - 窗口是否可以改变尺寸. 默认值为 true. 
- movable Boolean (可选) - 窗口是否可以移动. 在 Linux 中无效. 默认值为 true. 
- minimizable Boolean (可选) - 窗口是否可以最小化. 在 Linux 中无效. 默认值为 true. 
- maximizable Boolean (可选) - 窗口是否可以最大化动. 在 Linux 中无效. 默认值为 true. 
- closable Boolean (可选) - 窗口是否可以关闭. 在 Linux 中无效. 默认值为 true.
- alwaysOnTop Boolean (可选) -窗口是否永远在别的窗口的上面. 默认值为false.
- fullscreen Boolean (可选) - 窗口是否可以全屏. 当设置为 false 时，在 macOS 上全屏的按钮将被隐藏或禁用. 默认值为 false.


# 环境搭建
- [node:8.9.3](http://nodejs.cn/download/)

# 以管理员身份运行 cmd
```
$ npm config set registry https://registry.npm.taobao.org/
$ npm config set electron_mirror http://npm.taobao.org/mirrors/electron/
```

# 安装 vue-cli
```
$ npm install -g vue-cli
```

# 安装 yarn
```
$ npm install -g yarn
```

# 重点，安装windows-build-tools
```
$ npm install --global --production windows-build-tools
```



# Demo
- https://github.com/sohelamin/electron-vue-boilerplate

```
$ npm run build
$ npm run package-osx | npm run package-win
```


# Docs
- [BrowserWindow](https://electronjs.org/docs/api/browser-window)




# 参考文献
- [Electron 文档](https://electronjs.org/docs/api)
- [electron-vue 官方文档](https://simulatedgreg.gitbooks.io/electron-vue/content/cn/)
- [win环境，构建 electron+vue demo的准备工作](https://newsn.net/say/electron-vue-demo-win-prepare.html)
- [electron-vue-admin](https://github.com/PanJiaChen/electron-vue-admin)

