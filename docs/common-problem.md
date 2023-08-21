# 常见问题

## 网络相关

### [如何连接校内WiFi](https://wku.kf5.com/hc/kb/article/1571383/?lang=zh_cn)

### WKU的网络为什么总提示我登录?

你有可能打开了 随机硬件地址 / 随机设备MAC / 私有无线局域网地址,  只需要进入到WiFi设置, 找到相关的开关关掉就可以了  

[学校官方HelpDesk的指南](https://wku.kf5.com/hc/kb/article/1424509/)

如果你好奇这项技术可以看这个[柴知道的科普视频](https://www.bilibili.com/video/BV1gt411L7DV/?share_source=copy_web&vd_source=00f5e74c5395223be70e39d15664e474) 

另外, 你鉴于WKU网络仅允许3台设备自动登录, 因此你需要清空OpenAuth列表来保证你不会被限制. 步骤为:   

1. 浏览器地址栏输入: <a href="http://10.0.0.6/" title="注意不要使用中文标点" target="_blank">10.0.0.6</a>  如果不能打开请使用<a href="http://login.wku.edu.cn/" title="注意不要使用中文标点" target="_blank">login.wku.edu.cn</a>  
2. 如果你已经登录请点击右上角的Login   
3. 输入学号和密码, 但是**不要点Log in**  
4. 点击 OpenAuth, 点击每一个delete  
5. 在你的每台设备上重新连接WKU的网络  

如果你有**多于3台设备**需要连接网络, 常见的办法是绑定常用的设备为自动登录, 剩下的在浏览器中保存账号密码登录.   
或者可以通过手机WiFi热点或路由器(目前学校内支持路由器的宿舍网络仅有中国移动的宽带业务)连接网络. 但是此类网络并不能提供全球互联网.

## 选课相关

### 中方课的界面文字为什么是英文的?

这是因为WKU Campus默认选项为英文, 你可以在界面右上角 Sign Out, 然后在登录界面, 切换为English, 再切换为中文, 然后登录, 这样系统就会显示为中文了


## 美肯相关


### [关于Okta的相关说明](https://wku.kf5.com/hc/kb/article/1590491/)

### 怎么让我能在更多设备上获得Canvas的登录验证码?

1. 登录[账户设置界面](https://sso.kean.edu/enduser/settings)
2. 往下滑找到额外验证的地方
3. 添加Google Authenticator方式
4. 下载Google Authenticator APP(安卓手机需要有谷歌服务)
5. 如果需要添加更多设备在Google Authenticator里面转移账户就可以多设备使用了
6. 再次登录Kean的时候就可以选择是Okta验证或者Google Authenticator验证了

## 邮件相关

### [如何使用温肯和美肯邮箱](https://wku.kf5.com/hc/kb/article/1410376/)

### [如何转发美肯邮件到温肯邮箱](https://wku.kf5.com/hc/kb/article/1416410/)

### [如何在苹果手机/PAD上设置WKU邮箱](https://wku.kf5.com/hc/kb/article/1570726/)

### [如何在安卓手机上设置WKU邮箱](https://wku.kf5.com/hc/kb/article/1416408/)

### [如何转发温肯邮件到美肯邮箱](https://wku.kf5.com/hc/kb/article/1097265/)

### [如何修改温肯邮箱密码](https://wku.kf5.com/hc/kb/article/1622492/)


---

因温肯官方HelpDesk和第三方也写过此类Q&A, 故已有回答仅做索引