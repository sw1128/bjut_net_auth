# 【电脑端】北京工业大学（BJUT）校园网自动/一键认证软件

Github图片加载慢的话可以转到：[博客](https://zwhyzzz.top/bjut-net-auth/)

上次开发完手机端的一件认证APP之后，有同学问有没有电脑端的，其实本人觉得电脑比手机要方便很多，因为现在的浏览器都有记住账号密码的功能，只要打开页面点几下鼠标就可以了。但既然有人提出来了，那就不妨有时间的时候尝试一下，还可以提升一下代码水平。觉得能给你带来方便的就用，觉得觉得鸡肋多余的就别用，非常简单。

因此本项目40%为了满足那位同学的要求，60%用于自我学习。

`小插曲：今天突然接到电话（具体不方便透露），我得知不久的以后两个认证将合并成一个，这可能意味着“一键认证”的软件的实用性又降低了，但这是个好事，毕竟不管是我去做这件事还是学校去做这件事，方便大家的使用才是最终目的。并且只要有同学在用我的软件，我就会一直完善和维护下去。`

OK，废话不多说，进入正文 👇

## 🚩 请务必看完介绍再下载，尤其是 [隐私声明](#yssm)，下载链接在最后。 

## ✨ 关于软件

　　据我所知，北工大的校园网认证有两种。

　　拿中蓝宿舍举例：

- 如果电脑网线连的是墙上的网口，那么只会出现蓝色的认证页面。

![](https://zwhy-1310134253.cos.ap-beijing.myqcloud.com/blue.png)

- 如果电脑网线连的是光猫的LAN口，或者不用网线直接连光猫的WIFI信号，那么就需要认证完下方红色的页面之后再认证蓝色的页面。
  
![](https://zwhy-1310134253.cos.ap-beijing.myqcloud.com/red.png)

本软件可以可以帮你省下认证的这点时间。

## 🎄 软件功能

✅  自动检测是否连接到校园网并自动认证

<img src="https://zwhy-1310134253.cos.ap-beijing.myqcloud.com/bjut_auth1.gif" width="80%" height="80%" />

✅  兼容两种认证的类型

✅  一切交互或通知都使用原生的Windows通知弹窗，看着很舒服有没有

![](https://zwhy-1310134253.cos.ap-beijing.myqcloud.com/bjut_auth2.jpg)

✅  快捷查看流量使用情况

<img src="https://zwhy-1310134253.cos.ap-beijing.myqcloud.com/bjut_auth3.gif" width="80%" height="80%" />

✅  可以设置或取消开机自启动

<img src="https://zwhy-1310134253.cos.ap-beijing.myqcloud.com/bjut_auth4.gif" width="80%" height="80%" />

## <span id="yssm">📢 隐私声明</span>

本软件不会收集任何信息，一切数据皆存储在设备本地。

由于代码调用了Windows系统的Toast通知、设置开机自启动会读写注册表，如果杀毒软件提示风险属于误报，请放心使用。

本人用研究生延毕做担保，本软件绝对无毒无害！

同时，为防止有人对代码进行修改、植入后门以窃取账号信息，将不对代码进行开源。

腾讯哈勃分析结果：

![](https://zwhy-1310134253.cos.ap-beijing.myqcloud.com/habo.jpg)

360木马云查杀结果：

![](https://zwhy-1310134253.cos.ap-beijing.myqcloud.com/bjut_auth6.png)

## 🔔 使用方法

### 首次使用

- 第一次打开软件时，会有输入账号密码的提示，输入完后会生成一个配置文件，以后无需再输入。

<img src="https://zwhy-1310134253.cos.ap-beijing.myqcloud.com/bjut_auth5.png" width="80%" height="80%" />

　　一般来说，这一步做完就不用再管了。

### 开机自启动

- 如果设置为开机自启动，那么每次开机后都会自动检测是否连接到校园网并自动认证。（推荐）

- 如果没有设置开机自启动，那么每次打开软件后都会自动检测是否连接到校园网并自动认证。

### 手动认证

- 如果自动认证失败了（例如改了密码），可以在软件右键菜单中点击“一键认证”进行手动认证，认证成功后会更新配置。

### 其他也没啥了，可以自行体会

## 🆘 注意事项

　　本软件是基于.NET Framework 4.6.1框架开发的，其他设备运行有可能存在兼容等问题，若遇到相关问题可以添加我的微信反馈。

<img src="https://zwhy-1310134253.cos.ap-beijing.myqcloud.com/wx_code.jpg" width="40%" height="40%" />

## 📥 下载地址

https://wwuw.lanzouj.com/iuXoK0zoecwd

## ⭐ 额外说明

　　如果你觉得有用，麻烦给个star吧⭐如果你在使用的过程中遇到了什么问题，或者有什么建议，欢迎点击软件右键菜单中的“联系作者”按钮加我为好友，同时也欢迎各路大佬交流学习！
