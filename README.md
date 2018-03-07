# javaWeb--网上宠物商城（毕业设计）
开发语言 jsp+mysql+html
开发环境 eclipse+tomcat8.0+mysql数据库
展示图片 ：https://github.com/RAOE/java-----/blob/master/show.png
实现功能

       1.顾客,登陆注册，修改个人资料，宠物信息查询，宠物信息分类查询
       (1).狗狗类 (2).猫猫类 (3).宠物周边
       
       2.可以将喜欢的宠物加入购物车，并结算，查看订单，确认收货，评价订单，用户帮助，积分等
       
       3.后台系统开发，管理员，管理员登陆，管理员注册，查看顾客信息，可以修改顾客信息，修改宠物信息，发布宠物信息，查看订单并且确认收货，对用户进行评价
       
       4.宠物论坛，可以在论坛里发布喜欢的狗狗，可以选择匿名发布信息。
       
      使用说明
      1.在navicat里运行pets.sql脚本 文件创建数据库
      2.在dhcp数据库连接池里将mysql账号密码修改为你自己的
      3.配置tomcat服务器 添加到工程中
      4.运行项目 localhost:8080/PetsFront为项目的首页
      5.其他问题可以留言问我
            
      整个项目耗时1周
      
       待解决问题：
       
       1/ 在图片上传的时候 由于每一次上传都会清空servlet的缓冲区，将原生的tmp文件给覆盖 导致无法上传文件，所以采用了url的方式来保存商品图片
       ,以后会考虑采用七牛云+ueditor的方式上传文件
       
       2/ 在密码登陆的时候 没有采用MD5的方式来保存密码 。等等一系列 大家都可以去优化 做的更好
       
       3.后台管理员账号密码都是admin
      
       4.商品页面做的不是很美，希望可以做的更好
       
       喜欢的话别忘了给个star哦~

