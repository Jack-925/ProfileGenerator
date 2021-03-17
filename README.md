![效果生成图](C:\Users\Razer\AppData\Roaming\Typora\typora-user-images\image-20210317200127562.png)

本人阿里云服务器公网地址：120.78.230.102

Note：出于学习目的，目前使用的是3个月免费体验阿里云，后期如果此地址登录不上去大概率是到期了没有续费LOLLLLLL



直接复制地址到网页即可访问测试效果。

这是一个个人简历生成小程序，部署在了云服务器中，并利用云数据库PolarDB作为支撑

登陆后页面显示如下：

![登录页面](C:\Users\Razer\AppData\Roaming\Typora\typora-user-images\image-20210317193142406.png)

根据步骤信息录入完成后 ：

![image-20210317193252458](C:\Users\Razer\AppData\Roaming\Typora\typora-user-images\image-20210317193252458.png)

生成成功，可以访问查看生成的个人简历。



代码可以拿去使用的，直接部署好就能使用的。

注意需要修改的是：

ProfileGenerator\Tomcat部署代码\WEB-INF\classes\db.properties文件需要修改配置信息为自己的信息。![image-20210317193840693](C:\Users\Razer\AppData\Roaming\Typora\typora-user-images\image-20210317193840693.png)