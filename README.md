# 由来

前段时间偶然看到了赵大佬写的[Z-File](https://github.com/zhaojun1998/zfile),使用了一段时间之后，发现真的是一个特别方便的一个搭建下载站的程序。由于大佬没有去做命令行下的安装和升级的脚本，所以我就自己写了一个一键安装与管理脚本。(目前只支持linux下的一键安装)

## 代码功能

* 安装Z-File运行环境
* 安装Z-File
* 卸载Z-File
* 更新Z-File为最新版本
* 安装旧版Z-File
* 启动、停止、重启

## 使用教程

```
wget -P ~ https://raw.githubusercontent.com/iwayen/zfile-cli/master/zfile.sh && chmod +x zfile.sh && ./zfile.sh
```

# Z-File项目介绍

## Z-File

此项目是一个在线文件目录的程序, 支持各种对象存储和本地存储, 使用定位是个人放常用工具下载, 或做公共的文件库. 不会向多账户方向开发.

前端基于 [h5ai](https://larsjung.de/h5ai/) 的原有功能使用 Vue 重新开发了一遍. 后端采用 SpringBoot, 数据库采用内嵌数据库.

预览地址: [https://zfile.jun6.net](https://zfile.jun6.net)

文档地址: [http://docs.zhaojun.im/zfile](http://docs.zhaojun.im/zfile)

## 系统特色

* 内存缓存 (免安装)
* 内存数据库 (免安装)
* 个性化配置
* 自定义目录的 readme 说明文件
* 自定义 JS, CSS
* 文件夹密码
* 支持在线浏览文本文件, 视频, 图片, 音乐. (支持 FLV 和 HLS)
* 文件/目录二维码
* 缓存动态开启, ~~缓存自动刷新 (v2.2 及以前版本支持)~~
* ~~全局搜索 (v2.2 及以前版本支持)~~
* 同时挂载多个存储策略
* 支持 阿里云 OSS, FTP, 华为云 OBS, 本地存储, MINIO, OneDrive 国际/家庭/个人版, OneDrive 世纪互联版, 七牛云 KODO, 腾讯云 COS, 又拍云 USS.
