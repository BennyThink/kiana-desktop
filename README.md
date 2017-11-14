kiana-desktop
# kiana插件桌面版

使用Electron构建

## 运行方法 ##

### 二进制 ###
Windows下载解压缩后运行`kiana-desktop.exe`, Linux运行`./kiana-desktop`. macOS 俺不知道。
* [Windows x86](https://github.com/BennyThink/kiana-desktop/raw/master/dist/kiana-desktop-win32-ia32)
* [Windows x64](https://github.com/BennyThink/kiana-desktop/raw/master/dist/kiana-desktop-linux-x64.7z)
* [Linux x64](https://github.com/BennyThink/kiana-desktop/raw/master/dist/kiana-desktop-linux-x64.7z)
* [macOS](https://github.com/BennyThink/kiana-desktop/raw/master/dist/kiana-desktop-darwin-x64.7z)

### 手动运行 ###
或者使用npm安装electron，然后一下二选其一：
* 在应用目录打开命令行，输入`electron .`
* 在命令行输入`electron`,启动一个Electron窗口，并把`main.js`拖入窗口中。

## 打包命令 ##
使用`electron-packager`模块

`npm run-script package`

设置淘宝npm mirror

`export ELECTRON_MIRROR=https://npm.taobao.org/mirrors/electron/`
