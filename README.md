SendEmail
=========

实现webpower平台的接口

1.定时增量或全量的上传用户数据到平台并记录上传结果到本地数据库
2.生成DMA平台需要的四个CSV文件，并定时上传FTP服务器
3.定时在FTP服务器上拉取平台的回传文件，并解析到本地数据库
4.系统自检，发现问题后自动发送邮件到管理员邮箱
5.根据用户收藏或购买过的商品实现个性化自动推送邮件的发送
