---
hide:
  - navigation
title: zlibrary 下载教程
---

## 太长不看版本

1. [打开搜索界面](https://search.zhelper.net/?[{%22name%22:%22zlib.app%22,%22url%22:%22https://api.zlib.app%22,%22type%22:%22full%22,%22sensitive%22:false,%22detail%22:false,%22download%22:%22https://d.zlib.app/download/%22}])
2. 搜索书籍，点击书籍名称，弹出窗口中点击下载。
3. 弹出以下页面，选择红框中任意一个按钮即可下载。

![](/pics/zlibapp.png) 


-------------------------------------------

## 说明

!!! warning

    **这些不是官方网站:** zlib.is,zlib.to,zlibrary.to,zlibrary.is,z-lib.is,z-lib.to

    如果您已向上述任何一个网站捐款，请致电银行要求退款，因为他们使用 stripe 进行处理


- 目前官方有 TGBOT、TOR/I2P、APP 三种渠道，其中 TGBOT 只能下载 50M 以下书籍，其他渠道没有限制。
- 民间，基于之前 Annas-archive 流出来的资源，涌现出一批离线版书库，资源同步到 22 年 10 月，一般需要通过 IPFS 下载。
- 此外，民间还有 zhelper 反编译 APP 得到的搜索/下载接口 zlib.app。此接口和 zlibrary 官方在线库同步，下载也是走 zlibrary 服务器。
- **推荐有能力的尽量走官方网站，其次 zlib.app 在线库，最后用离线库**


## 官方版，包括 TOR/APP/TGBOT 三种方式

### 官方使用教程一图流

![](./tor.png)

### 1. TGBOT /需🪜/需注册/限制下载量/最大50M

首先安装 TG：[下载地址](https://telegram.org/)（自备梯子）

然后浏览器打开：https://singlelogin.me/，注册或者登录之后，点击这个按钮就行了（登录之后才能看到）：

![](./tgbot.png)

50M 以下，每个账号限量 20 本每天。

目前最新地址：[https://t.me/zlib\_basic\_bot](https://t.me/zlib_basic_bot)

### 2. I2P/TOR /需🪜/需注册/限制下载量 

这种方法可以直接访问到原来的官网，就是速度稍微慢一点，然后需要额外下载专用浏览器，进行配置。关于这些浏览器的使用教程，请自行搜索。

#### TOR 

浏览器：http://torproject.netcologne.de/zh-CN/download/

网址（必须使用上面的浏览器打开）：http://bookszlibb74ugqojhzhg2a63w5i2atv5bqarulgczawnbmsb6s6qead.onion/

#### I2P 

浏览器：https://geti2p.net/en/download

网址（必须使用上面的浏览器打开）：http://kkd7tiqf5lv3olqfdnkw4znmmmmnjo2xqlxrp5ntthp6juowaiha.b32.i2p/

### 3. APP /需🪜/需注册/限制下载量/仅安卓 

**只有安卓可以用，比较稳定，推荐**

[下载地址](https://gofile.io/d/83fK5J)

打开之后直接登录，然后就像之前用网站一样了。

## 民间版 包括 在线库 和 离线库

关于在线库和离线库的区别，请参考

### 1. zlib.app 在线库

目前只有 [zlib.app](https://zlib.app/) 提供在线库。使用方法在本文档开头已经有说明。

> 据zlib.app 首页说明：“在 z-library 主网站被封之后，z-library 的安卓端 APP 仍能够正常使用。但国内用户，以及非安卓平台用户可能会感到不便。我们分析了 z-library 安卓安装包，得到了可用的 APP 接口，搭建了相应的中转服务，注册了一些公共账号，以方便更多人使用 z-library APP。”

### 2. 离线库 annas-archive/zlib-searcher/ylibrary 离线库 

这几个放一起是因为他们的书源是一致的。

#### Annas-archive

这是之前一个 zlib 备份项目，他们把 zlib 整站电子书直接爬了下来，存到了 IPFS 上。zlib 关了之后，他们做了个查询/下载界面，还是比较好用的，**而且可以显示封面**。如果可以打开，并且不排斥英文的话挺推荐。

网站地址：https://annas-archive.org/

里面的书籍可以通过 IPFS 下载/Libgen 下载（Libgen 是另外一个在线图书馆，和 zlib 有很多重合）。

#### zlib-searcher

这是把 **Annas-archive 数据库导出之后，另外做了个搜索+界面的开源项目**，可以自己部署。

Github 地址：https://github.com/zlib-searcher/zlib-searcher（已删库）

一个 DEMO：https://zlibsearch.1kbtool.com/

**注意：由于这是一个开源项目，所以有很多人用这个搭建了自己的 zlib-searcher，虽然网址不一样，但是里面的内容完全一致，就不全部放出来了。**

里面的书籍只能通过 IPFS 下载。

#### ylibrary 去中心化图书馆

 [ylibrary.org](https://ylibrary.org/)

基于上面 zlib-searcher 项目，添加了来自 superlib 的资源，中文书籍数量大大增加。推荐使用。


## 其他资源

另外的一些民间版本，书不全，用的比较少一点。

[https://clibrary.top/](https://clibrary.top/)

[https://bk.hallowlib.org/](https://bk.hallowlib.org/)

## Q&A

### 在线库和离线库的区别

在线库，顾名思义直接接入 zlib 官方的服务器，所有官方渠道，例如 APP 或者 TOR，均为在线库。民间版中 zlib.app 是通过破解官方APP的接口从而接入在线库。

离线库，一般指 2022 年 10 月，由 anna 从 zlibrary 爬取的书籍库。这一部分书籍的储存和下载不通过 zlib 官方服务器，不与官方库同步。书籍被储存在称为 IPFS 的去中心化文件系统中。

区别：在线库书更多，离线库的书籍只更新到 2022 年 10 月。使用离线库下载书籍，需要通过 IPFS，对于热门书籍比较快，对于冷门书籍比较慢甚至无法下载，在线库下载书籍需要通过 zlib 官方服务器，不管哪本书的速度都比较一致。通过在线库下载书籍需要消耗额度，离线库没有限制。目前民间版本一般都是离线库。

### 离线库都有哪些网站/服务

- 所有标记为 zlibsearch，或带有类似名称的服务。
- 所有下载连接中有 dweb、ipfs 字样的服务。

### 如何下载大于 50M 文件

TG 机器人无法下载 50M 以上文件。请参考其他方法下载，例如 TOR 和 APP。比较方便的方法是直接改用 [zhelper bot](https://t.me/+hYmPpuRHlb83ZTdh)。

### TOR 下载缓慢如何解决

换用 APP 或者机器人，如果确实要用 TOR，可以考虑以下方法

#### 加速 TOR 下载的教程

- TOR 书籍页面链接：http://bookszlibb74ugqojhzhg2a63w5i2atv5bqarulgczawnbmsb6s6qead.onion/book/11651373/1132ee
- 注意链接的特点：最后以 数字/字符串 的形式结尾。如 3511909/db1f53 或者 3511911/f37da4
- 然后，请访问 https://d.zlib.app/download/[替换成上一步的数字]/[替换成上一步的字符串] 即可
- 如果需要使用自己的额度，请使用 https://d.zlib.app/download/[替换成上一步的数字]/[替换成上一步的字符串]/[替换成remix_userid]/[替换成remix_userkey]

### 电脑和苹果设备如何使用 APP

法1：使用蓝叠等模拟器运行安卓APP。苹果和电脑没有官方APP。

法2：使用 zlib.app，一个从官方 APP 中破解出来的接口，和官方APP书库完全一致


### 点击下载无反应如何解决

一般 IPFS 下载冷门资源时会出现这种问题。

解决方法：

- 多试几个链接
- 换用在线库（官方渠道，APP/TGBOT等，或者 zlib.app）

### 格式不对、需要解压、有密码如何解决

大概率是在使用增强库时，下载到了 superlib（而不是 zlibrary）的书。这些书是另外一个图书馆的。请参考 https://ssdown.org 中的教程使用。