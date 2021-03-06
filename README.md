# Toolbox
易迅工具盒子，一款致力于零散功能整合以提高工作效率的工具

<br />

## 现有功能
 - 执行命令行
 - 单文件 JS、CSS 压缩
 - 字符串生成二维码
 - 文件 base64

<br />

## 使用说明

###### 由于应用程序大小的问题，项目仅释放出源码，大家可以自行打包对应平台的应用程序。  
:sparkles: **使用及打包前请先执行 `npm install`，安装项目依赖的 NPM 模块**  

<br />

### 运行盒子

盒子是基于 Electron 制作，所以请确保您已安装 [Electron](electron.atom.io)。  
[如何使用 Electron ?](https://github.com/YIXUNFE/blog/issues/62)  

安装好 Electron 后，执行如下命令可以运行盒子：  
```
electron path/to/toolbox
```

<br />

### 打包应用程序

推荐使用 `electron-packager` 模块实现打包应用程序。  
[如何打包?](https://github.com/YIXUNFE/blog/issues/62)  

`electron-packager` 会自动为您打包**全平台**应用程序。  
:sparkles: **应用打包完成后，需要将 `yixunfe_toolbox.config` 配置文件放在应用程序**同级目录**下以便程序能够加载配置。**  

<br />

## 功能说明

### 构建任务

新建任务后，盒子会保存任务方便您日后使用。 [任务配置与使用？](https://github.com/YIXUNFE/blog/issues/67)  

除了一般的构建任务，盒子也可以执行任意的命令行命令，比如`ping`，`start` 等。（操作系统支持的话）  
###### 项目中已经配置了一个示例任务。  

<br />

### 文件压缩

支持将 js、css 文件内容进行压缩并在界面提供复制按钮。

-----------------

## Thanks

<br />



