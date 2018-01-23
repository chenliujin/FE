
- 登陆/登出
- 动态侧边栏
- 软键盘
- 分辨率
- 桌面最大化
- 隐藏最小化和关闭按钮


# Electron
Electron is a framework for building cross-platform desktop applications with web technology.

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






# 参考文献
- [win环境，构建 electron+vue demo的准备工作](https://newsn.net/say/electron-vue-demo-win-prepare.html)
- [electron-vue-admin](https://github.com/PanJiaChen/electron-vue-admin)
