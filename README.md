# mp-unpack

基于electron-vue开发的微信小程序自助解包客户端  
> 方便没有技术基础的同学轻松进行小程序的反编译

#### 为什么使用electron来做

上手方便、可跨平台

#### 前置准备：利用模拟器获取小程序包

1.通过电脑安装模拟器(如夜神)，安装微信、文件管理器
2.微信打开要反编译的小程序
3.打开文件管理器，路径：data/data/com.tencent.mm/MicroMsg/4c5fb997e38800c7d70bb22d56d7e756/appbrand/pkg

注意：4c5fb997e38800c7d70bb22d56d7e756这个每个人的应该都不一样，pkg下格式为wxapkg即是小程序包，压缩后弄到桌面上，拖到反编译文件里就自动编译了，编译后导出，解压后即是小程序源码。



#### 运行截图  

Mac  
<img src="mp-unpack.png" alt="mac解包截图" width="420" />  

Windows  

<img src="mp-unpack-win.png" alt="windows解包截图" width="420" />

#### 如何使用

To clone and run this repository you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](https://www.npmjs.com/)) installed on your computer. From your command line:

``` bash
git clone https://github.com/xiaoqi888/mp-unpack.git

cd mp-unpack

npm install && cd tool/ && npm install 

npm run dev
```
  
