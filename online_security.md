# [fengyichang.github.io](fengyichang.github.io)

本文内容部分由多位[品葱](https://pincong.rocks)用户贡献，经[本人](yichangfeng.home.blog)搜集整理。持续更新中

目录
* [安全意识](#mindset)
* [安全技术](#techniques)
* [相关资源](#resources)

## 【安全意识】<a name="mindset"></a>

翻墙，掉脑袋的事，千万别嫌麻烦！为保障安全上网，你需要付出额外劳动、时间、金钱，也要牺牲一定用户体验，具体的代价跟你对安全等级的要求成正比。根据你在墙外的活动对朝廷造成的威胁等级，可分为以下三类：

1. 【无威胁】：如果你翻墙仅仅是为了浏览网站和获取信息，只要你不发言对当局基本上不构成任何威胁，这种行为一般没什么后果，运气实在不好最多罚款了事。
2. 【轻度威胁】：如果你在墙外留下批评政府或者反共言论，那就暴露了自己的政治倾向，除非你成为网红否则威胁仍然很轻，被逮到可能会被重罚、拘留、记录在案，可能会对你的未来产生不确定的影响。但这种发牢骚的行为不会被当局重点侦办，因此只要自己别太大意问题也不大。
3. 【重度威胁】：如果你的目的是爆料当局力图掩盖的事件、参与组织街头革命、推进民主进程、或已经具有较大影响力，那就对当局构成重度威胁，这时你就成了网警国安重点侦查、监控的对象，在侦查过程中他们可能不会打草惊蛇，而是放任你表演很久才动手抓人，这种后果可能就监禁、消失。如果你要干这类事情，不但要定期更换ID，而且要认真学习定期更新网络安全知识。

总之只要你想自由表达就不可避免的对朝廷造成2、3等级的威胁，因此请务必把自己练成‘编程随想’那样无法跟踪的高手，认真学习网络安全知识和技术，千万别怕麻烦。

另外，虞超先生就使用社交媒体时的安全意识，进行了[详细阐述](http://www.epochtimes.com/gb/16/5/2/n7795513.htm)
## 【安全技术】<a name="techniques"></a>

请自行判断所列技术，没有绝对的安全

1. 浏览网站时，能够暴露你身份的首先是IP地址，然后是浏览器指纹。英文好的请务必阅读[关于浏览器指纹的详细介绍](https://pixelprivacy.com/resources/browser-fingerprinting/)。 在未被墙的[AmIUnique](https://amiunique.org)测试自己的浏览器指纹是否能唯一，很可能你常用的浏览器如Chrome, Opera, Edge, IE等具有唯一的指纹。浏览器指纹能泄露你在墙内外不同网站上的活动，比如你在墙内网站A从事正常活动（但浏览器指纹被记录），然后你开了VPN访问墙外网站B，如果网站B是钓鱼网站将你的浏览器指纹发送回朝廷，那么尽管你在网站A、B采用了不同的用户名、注册邮箱、密码，而且通过VPN隐藏了自己的真实IP地址，当局仍然能够根据浏览器指纹确定网站B上你的活动。 因此最好就是采用编程随想的方式，见下文。
2. 编程随想似乎用的是双虚拟机（网卡）+ VPN + Tor; Tor+虚拟机，不装任何国产软件，[泡泡上有关tor的文章](https://pao-pao.net/article/1049)
3. 只使用Tor Browser用于翻墙浏览网站，注意保持其默认窗口大小，这会牺牲用户体验但能更好的保证你的浏览器特征不被识别
4. 操作系统，从U盘或者DVD启动的保护隐私的操作系统[https://tails.boum.org/](https://tails.boum.org/) 这种操作系统的所有内容都存储在电脑内存中，只要拔掉/关掉电源就一切消失，可以防止突然被当局抄家后泄露存储在硬盘的敏感资料，或者上网时电脑被植入木马
5. 弃vpn用ssr或v2(待考证)
6. 申请虚拟电话号码，如TextNow
7. 不用与墙内相同的网名，更不要用实名，更不要采用跟墙内账号相同或相近的密码
8. 不要发暴露身份信息的照片
9. 不要标注地址信息
10. 用境外邮箱: 推荐protonmail, 它不需要任何身份验证就能注册, 可以向普通邮箱发送邮件 https://protonmail.com/  注意, 你需要牢记密码, 因为没人可以帮你找回密码. 如果你的目的是注册网站，可以考虑 http://www.bccto.me  临时邮箱。一些安全邮件提供商 https://imgchr.com/i/F7CsJK 
11. 此外, 再推荐几个相对安全的应用; MEGA (https://mega.nz/)  是一个加密的云盘. Tor (https://www.torproject.org/)  是一个高度匿名的浏览器, 但是也可能会遇到蜜罐节点. WIRE (https://wire.com)  是一个开源的, 加密的聊天应用, 在网页上注册不需要电话号码. Telegram (https://telegram.org/)  是一个用户多, 功能全的聊天应用, 也具有加密功能, 但是加密聊天并不默认开启, 而且只能使用电话号码注册; 用加密聊天软件 unseen (https://unseen.is/)
12. 除此之外, 你的输入法也可能被用来监视你, 因此不推荐使用国产的输入法.

## 【相关资源】<a name="resources"></a>

### 隐私工具-加密安全对抗全球大规模监控 
https://cybermagicsec.github.io/privacytools-zh/

### 编程随想 翻墙技术专栏 
https://program-think.blogspot.com/

1. [“对抗专制、捍卫自由”的 N 种技术力量](https://program-think.blogspot.com/2015/08/Technology-and-Freedom.html) 
2. [如何防止黑客入侵(系列)](https://program-think.blogspot.com/2010/06/howto-prevent-hacker-attack-0.html) 
3. [如何保护隐私(系列)](https://program-think.blogspot.com/2013/06/privacy-protection-0.html) 
4. [如何隐藏你的踪迹，避免跨省追捕(系列)](https://program-think.blogspot.com/2010/04/howto-cover-your-tracks-0.html&nbsp;)
5. [扫盲操作系统虚拟机(系列)](https://program-think.blogspot.com/2012/10/system-vm-0.html) 
6. [TrueCrypt 的扫盲教程和高级教程](https://program-think.blogspot.com/2011/05/recommend-truecrypt.html#index) 
7. [文件加密的扫盲介绍](https://program-think.blogspot.com/2011/05/file-encryption-overview.html) 
8. [文件备份技巧：组合”虚拟加密盘”和”网盘”](https://program-think.blogspot.com/2013/07/online-backup-virtual-encrypted-disk.html)  
9. [扫盲文件完整性校验——关于散列值和数字签名](https://program-think.blogspot.com/2013/02/file-integrity-check.html)  
10. [社会工程学扫盲(系列)](https://program-think.blogspot.com/2009/05/social-engineering-0-overview.html)
