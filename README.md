1. # OA

   #### 项目介绍

   基于 springboot+myvatis_+ mvc + activiti+quarts+quartz 写的一个办公企业管理系统 OA

   #### 软件架构

   springboot+myvatis_+ mvc + activiti+quarts+quartz

   #### 说明

   ##### 功能：

   用户模块 日志模块 考勤模块 工作流模块 请假 岗位 会议申请 菜单 。。。 定时任务月末统计考勤状况 等功能

   前端页面出致于：若依管理系统（https://github.com/WuJunJie521/RuoYiu）

   ##### 在线体验

   管理员 账号：admin 密码：admin

   领导角色演示账号/密码：manager、123456

   员工角色演示账号密码：employee /123456
   作者的微信：JJHHao有问题联系。
 

   截图：

   4.3.1 个人办公模块的实现
       登陆的用户的个人办公模块会有由日程管理，个人便签，通讯录，请假记录模块。其中普通员工有对日程的查看，个人便签的增删改查，通讯录的查看，请假的查看功能。经理和boss有对日程，个人便签，通讯录，请假的增删改查功能。如图10所示。
         ![Image1](https://github.com/HardshipDreamNice/OA/blob/master/sql/img/1.png)
   4.3.2 会议管理模块的实现
          会议管理模块只有权限高的boss和经理才能看到，有会议室管理，会议管理，和预约管理三个模块，实现了会议室的预约，会议管理，和预约管理的增删改查功能，如图11所示。
     ![Image2](https://github.com/HardshipDreamNice/OA/blob/master/sql/img/2.png)
   4.3.3 系统管理模块的实现
          系统管理模块只有权限最高的boss和经理才能操作，有员工管理，部门管理，角色管理，菜单管理，岗位管理，公告管理，和工作时间管理。实现了上面管理相对应的增删改查操作，如图12所示。
     ![Image3](https://github.com/HardshipDreamNice/OA/blob/master/sql/img/3.png)
   4.3.4 流程审批模块的实现
        该模块实现了需要进行审批的记录的查看和审批记录的对应的增删改查功能，如图13所示。
         ![Image4](https://github.com/HardshipDreamNice/OA/blob/master/sql/img/4.png)
   图13 流程审批系统界面图
   
   4.3.5 考勤管理模块的实现
          该模块实现了对考勤记录的查看和统计的功能，分别实现了相对应的增删改查的功能，如图14所示。
      ![Image5](https://github.com/HardshipDreamNice/OA/blob/master/sql/img/5.png)
       
   图14考勤管理系统界面图
   
   4.3.6 文件管理模块的实现
          该模块实现使用ftp作为服务器实现了对相应的文件，图片等的上传功能，上传后的文件会放在ftp服务器中，并且对相应的上传文件实现了对应的正删改查操作，如图15所示。
         ![Image6](/sql/img/6.png)
     图15 文件管理系统界面图

  
