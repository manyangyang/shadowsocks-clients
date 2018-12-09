# shadowsocks-clients（各shadowsocks客户端安装）
抽空搭了个shadowsocks. 现在要用的话，需要在各个端安装对应的client。但是由于某些原因,百度、知乎等可能都搜不到有效资料，安装客户端时会遇到一些问题。
以下是各个平台的使用方法。跟我申请端口密码等配置(现在不再配了，满了，人多了怕速度慢)。主要拿到的配置有：

```
ip: xxx.xx.xx.xxx
port: xxxx
password:  xxxxxx
signType: rc4-md5
```


加密方式选rc4-md5是因为它性能相对较好。iOS客户端只手动配置这几个就可以。

## iOS
iOS端好用的socks代理客户端推荐SuperRocket-SSR，app store搜“SuperRocket”下载即可（收费￥6.00）。

<img src="https://upload-images.jianshu.io/upload_images/574394-ebf2dc85e586d9c1.jpeg" width = 30% height = 30% alt="SuperRocket-SSR" div align=center/>

下载完成后，手动配置拿到的参数。

<img src="https://upload-images.jianshu.io/upload_images/574394-bfdc84fabfa5965f.jpeg" width = 30% height = 30% alt="手动添加配置界面" div align=center />

配置完成后，。首页点击连接就可以了。大部分not found app都可以用。
## Android
下载链接：[下载shadowsocks-android](https://github.com/shadowsocks/shadowsocks-android/releases). 如果不知道自己该下哪个，下载universal的版本就行。
如果这个下不动，可以到百度网盘下载.
链接: [shadowsocks安卓客户端](https://pan.baidu.com/s/1wvhvEx78HpP0Bh0lbtCGxw) 
提取码: `f19s` 

<img src="https://upload-images.jianshu.io/upload_images/574394-f7a354166dd0d7cf.jpeg" width = 30% height = 30% alt="简单设置下" div align=center/>

## Mac OS端
Mac端找了好久的客户端，终于在gayhub找到一个凑合能用(下)的，为了防止原仓库删掉，专门fork了一份，地址：[ShadowSocksX](https://github.com/manyangyang/ShadowSocksX)。

<img src="https://upload-images.jianshu.io/upload_images/574394-bfe70220b1cebd2d.png" width = 50% height = 50% alt="各电脑客户端" div align=center/>

windows的那个exe我没试，只试了Mac的app，可以用。
要是没有git的同学，可以直接下载，点击dmg文件，下载就行。

<img src="https://upload-images.jianshu.io/upload_images/574394-d34d80e45faa721e.png" width = 50% height = 50% alt="点击下载" div align=center/>

安装完成后，打开app，填写之前拿的配置，填好就行。

<img src="https://upload-images.jianshu.io/upload_images/574394-1b54fa4268da6b29.png" width = 50% height = 50% alt="简单配置" div align=center/>

配置完成后，在顶部菜单栏点击“打开shadowsocks”，模式建议选择“自动代理模式”，服务器选择刚才配好的代理就行。

<img src="https://upload-images.jianshu.io/upload_images/574394-34ee9bbfe6b3fc74.png" width = 50% height = 50% alt="启动客户端" div align=center/>

启动后就可以了。看东西基本秒开的（高清视频可能会缓冲下）。
## Windows端
windows客户端也在上面那个连接里（[ShadowSocksX](https://github.com/manyangyang/ShadowSocksX)）。下载exe文件安装，配置步骤和Mac端的类似。我没试。
windows还有个：[ShadowSocksX-windows-release](https://github.com/shadowsocks/shadowsocks-windows/releases)，但是下不动。
