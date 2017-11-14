kiana-desktop
# kiana插件桌面版

使用Electron构建

## 运行方法 ##

### 二进制 ###
在release下下载对应的二进制
### 手动运行 ###
或者使用npm安装electron，然后一下二选其一：
* 在应用目录打开命令行，输入electron .
* 在命令行输入electron,启动一个Electron窗口，并把mian.js拖入窗口中。

## 打包命令 ##
使用`electron-packager`模块

`npm run-script package`

设置淘宝npm mirror

`export ELECTRON_MIRROR=https://npm.taobao.org/mirrors/electron/`