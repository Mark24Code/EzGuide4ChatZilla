#IRC客户端ChatZilla简明向导
##### 作者：Mark24
##### 邮箱：mark.zhangyoung@qq.com
##### 时间：2015.08.05
![git_logo](http://ww1.sinaimg.cn/mw690/44894cbbgw1eus4od5flfj20kw0h2mzd.jpg)


##IRC客户端ChatZilla简明向导

IRC似乎在国内不怎么流行，自己也是一个新人，把自己简单的探索步骤记录下来，给别人一个快速入门。

IRC需要一些命令 

这里不谈领命行，只给一个入口，感兴趣的同学自行探索

下面直接上干货，5分钟，让你接入V2EX的IRC频道

## IRC是什么？

IRC是Internet Relay Chat 的英文缩写，中文一般称为互联网中继聊天。它是由芬兰人Jarkko Oikarinen于1988年首创的一种网络聊天协议。

简单的说是一种分布式的QQ，服务器分散在全球各地，知道一个服务器节点，还有一个频道名，便可以接入一个房间 

可以一起讨论，也支持ssh等，也可以单独在两人之间建立起连接

小巧，及时性，速度快，几乎无延时，就是它的有点

IRC的客户端非常之多

[维基百科](https://zh.wikipedia.org/wiki/IRC)上列举如下：


* mIRC被认为是Windows操作系统下最受欢迎，应用最广的IRC客户端软件。
* ChatZilla是Mozilla浏览器下的IRC客户端程序，基于JavaScript和XUL语言编写的。
* Opera浏览器有内置的IRC客户端软件。
* Pidgin支持IRC网络。
* XChat跨平台IRC客户端软件
* HydraIRC是GPL授权对应Windows系统的IRC客户端软件
* KVIrc是一款注重图形的GPL授权IRC客户端软件，基于Qt。
* Irssi 类UNIX系统下CLI界面的IRC客户端，常常与Screen一起搭配使用。
* Colloquy是Mac OS X下的免费IRC客户端，界面设计友好，还有Console可以监控背后针对每个频道执行所有IRC命令。
* WeeChat也是一款类UNIX系统下的CLI界面的IRC客户端。
* QuasselIRC是一款多平台下IRC客户端。
* HexChat支持Windows、Linux、OSX平台，并且开放源代码。
* LimeChat由日本人开发多平台IRC客户端软件。

好啦，估计没耐心的人，看到这里已经头大了。这么多怎么选，其实列在这里方便网友查找。大同小异反正。 

鉴于浏览器随处可见，开发者人员必备，这里介绍Firefox上面的 ChatZilla,比较小巧，开启方便。
跨平台，依赖于Firefox好过于，依赖于客户端，不同机器上，登录Firefox帐号同步之后，会自动安装ChatZilla，比较方便。

我们就敲定了，介绍ChatZilla

好啦，下面开始，手把手教你接入V2EX!

##接入V2EX频道

1.下载最新版本的Firefox

目前，笔者写到这里，Firefox的最新版本是39.0

2.打开浏览器，如图点击 三道线，“更多”标志

![1](http://ww2.sinaimg.cn/mw690/44894cbbgw1eus464049rj210z0opadb.jpg)

3.弹出菜单选择 “附加组建”

![2](http://ww1.sinaimg.cn/mw690/44894cbbgw1eus464euj6j20zk0m8dlj.jpg)

4.进入附加组建页面，关注右上角，插件搜索，输入<strong>ChatZilla</strong>,然后回车，搜索

![3](http://ww4.sinaimg.cn/mw690/44894cbbgw1eus469t24aj20zk0m84qp.jpg)

5.搜索结果出来后，别急，慢慢往下拉网页，找到 更多搜索结果,经验之谈，后面你就知道为什么了

![4](http://ww4.sinaimg.cn/mw690/44894cbbgw1eus46d6zesj20zk0m87wh.jpg)

6.出现的新页面比较好看，反复看看，如图，我们需要这两个插件，点击安装把，每安装一个，要重启浏览器一次，耐心点~

![5](http://ww3.sinaimg.cn/mw690/44894cbbgw1eus46eguyuj20zk0m8ak9.jpg)

<strong style="color: red;">什么?!!你总是下载不了插件??</strong> 恭喜你，中奖了！！

不过没关系，笔者准备了一个备份： 

链接: http://pan.baidu.com/s/1gdGpXdx 密码: bamp

安装方法：

* 打开Firefox

* 挨个把后缀名是xpi的文件，拖放到浏览器中，对，就是页面上，稍等一会，跳出安装提示

7.如果出现安装完成，你的图标出现在了浏览器菜单栏上，一个<strong>CZ</strong> logo，可以跳到第8步 

如果没有图标，对Firefox不熟悉的同学，看下面的图，尝试把图标，拖到菜单栏中 

![6](http://ww1.sinaimg.cn/mw690/44894cbbgw1eus46fmlzej20zk0m8n2y.jpg)

![7](http://ww4.sinaimg.cn/mw690/44894cbbgw1eus46k48yhj20zk0m8k40.jpg)

8.现在可以点击<strong>CZ</strong> logo启动，ChatZilla客户端了

![8](http://ww4.sinaimg.cn/mw690/44894cbbgw1eus46qphnfj20zk0m8gpp.jpg)

9.客户端开启之后，就是如何找到V2EX频道 

看App的菜单栏，找到IRC选项，找到<strong>进入频道</strong>

![9](http://ww2.sinaimg.cn/mw690/44894cbbgw1eus483lo7cj20zk0m8ah2.jpg)

10.进入频道设置页面，如图操作 

1. 网络：下拉菜单，选择f<strong>freenode</strong> 网络节点服务器

2. 频道: 手动输入 <strong>v2ex</strong>，大小写都会变成小写 

3. 加入：点击这个按钮，下面的搜索很迟钝，不管有没有结果，直接加入好了

![10](http://ww2.sinaimg.cn/mw690/44894cbbgw1eus484dkhij20zk0m8af3.jpg)

11.下面网络没有问题，应该就加成功了，可以看到V友了，输入框中，可以直接发送内容，也可以发送命令

命令以`/`开头，可以试试 `/info` 

`/command`会列出所有可以输入的指令

[参考指南](http://chatzilla.hacksrus.com/faq/)自己猛戳

![11](http://ww2.sinaimg.cn/mw690/44894cbbgw1eus487lftxj20zk0m878j.jpg)

12.支持的表情

![16](http://ww3.sinaimg.cn/mw690/44894cbbgw1eus60bub0gj20sn06bgn7.jpg)


##关于技巧和设置

###更改自己的昵称

![12](http://ww1.sinaimg.cn/mw690/44894cbbgw1eus488j5p0j20zk0m8gqf.jpg)

###常驻V2EX

每个聊天的页面都有一个标签，如图所示，右击标签，可以设置<strong>启动时打开</strong>

这样子永远找到 V2EX，免去搜索烦恼

![13](http://ww1.sinaimg.cn/mw690/44894cbbgw1eus4895yk2j20zk0m8aft.jpg)

###设置通知提醒，等等

![14](http://ww1.sinaimg.cn/mw690/44894cbbgw1eus48a8vk0j20zk0m8dko.jpg)

![15](http://ww1.sinaimg.cn/mw690/44894cbbgw1eus48b376oj20zk0m8wj9.jpg)


<hr>
资源声明:图片来自于互联网  
版权声明:自由转载-非商用-非衍生-保持署名（创意共享3.0许可证）

<hr>
###反馈

可以在issue中反馈，欢迎交流，共同进步

<hr>
###赞助

如果你觉得本文章质量不错，读后收获很大，不妨小额赞助我一下，让我有“动力”继续致力于高质量文章和教程

天气都37摄氏度+了
不妨，请作者喝瓶汽水吧 ^0^


![zhifubao](http://ww1.sinaimg.cn/mw690/44894cbbgw1euiwofemusj20dt0dijsy.jpg)


