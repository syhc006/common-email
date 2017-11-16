# common-email

> 之前一直在做邮件系统，涉及到很多模块，在这里提供发邮件和下载邮件核心介绍
> 由于涉及隐私问题，我是以demo方式提供出来的，不过不影响核心功能和介绍


## 发送邮件功能点
 1. smtp协议发送邮件
 2. 支持可切换ssl非ssl方式
 3. 支持velocity渲染模板发送邮件
 4. 支持切换代理发送邮件
## 下载邮件功能点
 5. 支持imap协议，下载未读邮件，并设置邮件已读
 6. 支持pop3协议，根据业务需求下载邮件
 7. 支持切换ssl非ssl方式
 8. 支持下载附件和邮件内容中的图片
 9. 支持解析附件内容

## Email收发POP3/IMAP/SMTP常用端口

> POP3： 默认端口为：110 （如勾选ssl安全链接，端口号为995）
> SMTP： 默认端口为：25 （如勾选ssl安全链接，端口号为994）
> IMAP： 默认端口为：143 （如勾选ssl安全链接，端口号为993）


## 邮箱配置说明

> 无论用哪一个提供商的邮箱，都要先去开启你使用的服务，
> [开启腾讯邮箱方式](https://jingyan.baidu.com/article/4f7d5712b1ac7c1a201927da.html)、[开启163邮箱方式](https://jingyan.baidu.com/article/4f7d5712d3451a1a201927b1.html)



## 发送邮件和下载邮件坑及问题总结(仅供参考)
[链接地址](http://blog.csdn.net/zhouhao1256/article/details/78543430)

## 工程地址
[common-email](https://github.com/zhou1hang/common-email)



