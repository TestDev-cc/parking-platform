# 基于Java+Vue+SpringBoot-打造的智慧停车场-毕设项目功能介绍

![登陆界面](https://www.skywalking.pro/download/images/parking-platform/WX20231011-144536@2x.png  "登陆界面.png")

![功能示意图](https://www.skywalking.pro/download/images/parking-platform/WechatIMG794.jpg  "功能示意图.png")

####  **联系作者** 

![联系作者](https://skywalking-web.oss-cn-chengdu.aliyuncs.com/main-platform-fengfeiyezi.png)

 **这是作者的微信二维码，如需本项目源代码，可扫码或者VX:cyddhao联系作者。**  

![微信二维码-1](https://skywalking-web.oss-cn-chengdu.aliyuncs.com/fengfeiyezi-QR-code.png?x-oss-process=image/resize,p_50 "微信二维码-1.png")

![主页](https://www.skywalking.pro/download/images/parking-platform/WX20231012-093945@2x.png   "主页.png")

**系统功能持续更新中。。。**
#### 介绍
 **这是一个基于SpringBoot2.X VUE2.6 ElementUI MyBatisPlus Java1.8 实现的智慧停车场系统，系统主要分为后台和前端，前端主要是H5页面形式，后台则为管理系统形式，后台系统具备的功能有系统管理、权限管理、停车位管理管理、H5轮播图管理、停车场信息管理、车辆信息管理管理功能、车辆活动信息功能、识别记录功能、车辆识别记录功能等多个功能。H5端则具备模拟识别车牌的功能，该项目代码清晰，注释完整，文档齐全，适合作为毕业设计以及个人学习。** 
 
 #### 后台管理系统功能点
|功能点   | 描述  | 备注   |
| :------------: | :------------: | :------------: |
|  权限管理 | 管理系统具备的菜单和按钮权限  | 不同用户登陆系统，功能不同 |
|  系统用户管理 | 管理系统的各种用户  | 属于RBAC权限一部分  |
|  系统角色管理 | 管理系统的各种角色（进行权限控制）  | 属于RBAC权限一部分  |
|  停车位管理 | 管理停车位管理管理  | 停车位信息维护功能也包含在这里面  |
|  H5轮播图管理 | 管理系统H5端轮播图 | 包含维护系统H5端轮播图功能  |
|  停车场信息管理 | 管理停车场信息 | 包含管理停车场信息功能  |
|  车辆信息管理 | 管理车辆信息 | 记录车辆是否登记  |
|  车辆信息管理 | 管理车辆信息 | 记录车辆是否登记  |
|  车辆信息管理 | 管理车辆信息 | 记录车辆是否登记  |
|  车辆活动信息管理 | 车辆活动信息维护、识别车牌 | 记录车辆出库和入库信息  |

 #### H5、小程序端功能点
|功能点   | 描述  | 备注   |
| :------------: | :------------: | :------------: |
|  车牌识别 | 模拟车牌识别功能  | 提交车牌信息，可进行识别 |

#### 项目所用技术
|技术点   | 描述  | 备注   |
| :------------: | :------------: | :------------: |
|  SpringBoot2.X | 先进的Spring集成框架  | 集成了最新版  |
| VUE2.6  |  前端交互框架 |   |
| ElementUI 2.x |  饿了么出品的前端UI框架 |   |
| ANTD |  阿里出品的图表框架  | 好用且好看  |
| MyBatisPlus | 基于MyBatis封装的ORM框架  |方便查询   |
| Shiro1.5.0 | 经典而好用的权限框架  |  |
| uniapp | 移动端开发框架  |  |
| uview | 高颜值的移动端UI框架  |  |
| Java1.8 | 最常用的Java版本  |使用了Java8新特性  |
| RBAC权限模型|纯动态的菜单权限设计，可控制权限到按钮级别  |纯动态的菜单权限设计  |

#### 清晰的注释
**项目的每个类和方法，都具备清晰的注释，适合阅读，注释如下图：**

**1. 类注释**

![类注释](https://www.skywalking.pro/download/images/meta/WX20230206-092916@2x.png "类注释")

**2. 数据库字段注释注释**

![类注释](https://www.skywalking.pro/download/images/meta/WX20230206-093511@2x.png "类注释")

#### 项目特有优势
1. 清晰的注释，每个方法，类，字段，都具备中文注释。
2. 部署方便，作者编写了一键启动的脚本，可以让Java后端完美运行在主流服务器上。
3. 代码符合行业规范，变量，类，命名简洁优雅。
4. 应用多种市面上的先进技术，方便学习和开发。
5. 具备完整的项目文档和技术文档，方便二次开发。
6. 具备前后端代码生成器，一键生成VUE以及Java后端代码。 
#### 它适合做什么？
1. 适合作为高校毕业设计。
2. 适合作为初学者学习使用。
3. 如果场景适合，可以作为商业使用。
### 联系作者
#### 微信号: cyddhao
#### 管理系统后端演示地址:
```
登录地址: https://www.skywalking.pro/parking-platform
登录账号: admin
登录密码: 123456
```

**若演示程序不可用，可翻到文末扫码联系作者微信或者留言**

### 软件架构说明
该项目采用市面上比较流程的前后端分离架构，以SpringBoot技术栈为后端，以VUE为前端，采用优雅简洁漂亮的UI框架。系统采用前端发起请求，后端处理业务的方式进行交互，相对于传统的JSP，freemarker等技术有较大区别以及先进性。同时在权限控制方面有独到的创新，实现了VUE自定义指令，以控制系统权限到每一个系统按钮。是非常适合作为毕业设计以及学习的系统。
#### 前端技术
1. ElementUI
2. 页面,按钮级别权限控制。
3. 多个组件封装，调用方便。
4. Antv图表组件。
5. WebPack
6. ES6
7. 多环境打包。
8. VUE路由，过滤器，自定义指令。
9. 代码简洁，符合编码规范。
#### 后端技术
1. SpringBoot2.x
2. Shiro权限框架
3. Redis6.X最新版
4. MyBatis注解版
5. MySQL6.7
6. 分模块开发，自定义启动脚本，JVM调优
7. 多环境,前后端完全分离。
8. 代码生成器。
9. orika传输对象映射器。

### 系统技术文档
**为了让读者更好地理解系统技术原理，功能实现方法，故特地准备了系统技术文档，里面包含系统所使用的主要技术框架，运行说明，系统表设计，模块设计等。**
#### 系统技术文档截图

![系统技术文档截图-01](https://www.skywalking.pro/download/images/parking-platform/WX20231012-095455@2x.png  "系统技术文档截图-01.png")

![系统技术文档截图-02](https://www.skywalking.pro/download/images/parking-platform/WX20231012-095540@2x.png  "系统技术文档截图-02.png")


### 项目代码展示

#### 系统VUE代码截图展示

![管理系统VUE代码截图展示](https://www.skywalking.pro/download/images/parking-platform/WX20231012-095652@2x.png "系统VUE代码截图展示.png")

#### 系统后端Java代码截图展示

![管理系统后端Java代码截图展示](https://www.skywalking.pro/download/images/parking-platform/WX20231012-095730@2x.png "管理系统后端Java代码截图展示.png")

#### 数据库表结构展示

![数据库表结构展示](https://www.skywalking.pro/download/images/parking-platform/WX20231012-095816@2x.png "数据库表结构展示.png")

### 系统截图展示
#### 系统登陆
- 登陆界面

![登陆界面](https://www.skywalking.pro/download/images/parking-platform/WX20231011-144536@2x.png "登陆界面.png")

#### 系统管理模块
- 系统主页

![主页](https://skywalking.pro/download/images/parking-platform/WX20231012-093945%402x.png "主页.png")

- 菜单管理

![菜单管理](https://www.skywalking.pro/download/images/parking-platform/WX20231012-101928@2x.png  "菜单管理.png")

![菜单编辑](https://www.skywalking.pro/download/images/parking-platform/WX20231012-102027@2x.png "菜单编辑.png")

- 角色管理

![角色管理](https://www.skywalking.pro/download/images/parking-platform/WX20231012-102148@2x.png "角色管理.png")

![角色编辑](https://www.skywalking.pro/download/images/parking-platform/WX20231012-102306@2x.png  "角色编辑.png")

![角色新增](https://www.skywalking.pro/download/images/parking-platform/WX20231012-102224@2x.png "角色新增.png")

- 系统用户管理

![系统用户列表](https://www.skywalking.pro/download/images/parking-platform/WX20231012-102350@2x.png "系统用户列表.png")

![系统用户编辑](https://www.skywalking.pro/download/images/parking-platform/WX20231012-102517@2x.png "系统用户编辑.png")

#### 系统监控模块

- 系统日志

![系统日志模块-01](https://www.skywalking.pro/download/images/parking-platform/WX20231012-104302@2x.png "系统日志模块-01.png")

![H5轮播图模块-02](https://www.skywalking.pro/download/images/parking-platform/WX20231012-104504@2x.png "H5轮播图模块-02.png")

#### H5端模块

- 首页

![首页](https://www.skywalking.pro/download/images/parking-platform/WX20231012-110956@2x.png "首页")

- 提交识别

![提交识别](https://www.skywalking.pro/download/images/parking-platform/WX20231012-110956@2x.png "提交识别")

![提交识别](https://www.skywalking.pro/download/images/parking-platform/WX20231012-111154@2x.png "提交识别")

![提交识别](https://www.skywalking.pro/download/images/parking-platform/WX20231012-111244@2x.png "提交识别")

- 识别结果

![识别结果](https://www.skywalking.pro/download/images/parking-platform/WX20231012-111315@2x.png "识别结果")

#### 系统业务模块

- H5轮播图模块

![H5轮播图模块-01](https://www.skywalking.pro/download/images/parking-platform/WX20231012-104302@2x.png "H5轮播图模块-01.png")

![H5轮播图模块-02](https://www.skywalking.pro/download/images/parking-platform/WX20231012-104504@2x.png "H5轮播图模块-02.png")

- 停车场信息管理模块

![停车场信息列表](https://www.skywalking.pro/download/images/parking-platform/WX20231012-104749@2x.png "停车场信息列表.png")

![停车场信息新增](https://www.skywalking.pro/download/images/parking-platform/WX20231012-104819@2x.png "停车场信息新增.png")

- 停车位信息模块

![停车位信息列表](https://www.skywalking.pro/download/images/parking-platform/WX20231012-104916@2x.png "停车位信息列表.png")

![停车位信息新增](https://www.skywalking.pro/download/images/parking-platform/WX20231012-105031@2x.png "停车位信息新增.png")

- 车辆信息模块

![车辆信息列表](https://www.skywalking.pro/download/images/parking-platform/WX20231012-105101@2x.png "车辆信息列表.png")

![车辆信息新增](https://www.skywalking.pro/download/images/parking-platform/WX20231012-105156@2x.png "车辆信息新增.png")

- 车辆活动信息模块

![车辆活动信息列表](https://www.skywalking.pro/download/images/parking-platform/WX20231012-105237@2x.png "车辆活动信息列表.png")

![模拟开闸](https://www.skywalking.pro/download/images/parking-platform/WX20231012-105400@2x.png  "模拟开闸.png")

- 识别记录模块

![识别记录列表](https://www.skywalking.pro/download/images/parking-platform/WX20231012-105457@2x.png "识别记录列表.png")

![提交识别](https://www.skywalking.pro/download/images/parking-platform/WX20231012-105528@2x.png  "提交识别.png")

![识别结果](https://www.skywalking.pro/download/images/parking-platform/WX20231012-105710@2x.png   "识别结果.png")

#### 后台系统功能模块概要
+ 系统登陆
+ 系统主页
  - 系统主页折线图统计
    * 系统主页折线图统计
    + 系统模块导航
    - 系统访问数统计
+ 系统管理
  - 系统用户管理
    * 系统用户条件查询
    + 系统用户修改
    - 系统用户删除
  - 系统用户新增
  - 系统菜单管理
    * 系统菜单条件查询
    + 系统菜单修改(可级联修改)
    - 系统菜单删除
  - 系统菜单新增
  - 系统角色管理
    * 系统角色条件查询
    + 系统角色修改
    - 系统角色删除
  - 系统角色新增
  - 系统字典管理
    * 系统字典条件查询
    + 系统字典修改
    - 系统字典删除
  - 系统字典新增
+ 系统监控
  - 在线用户管理
    * 在线用户条件查询
    + 在线用户踢出
  - 系统日志管理
    * 系统日志条件查询
    + 系统日志分析
  + 系统访问IP分析
+ H5轮播图管理
  - H5轮播图界面
    * H5轮播图条件查询
    + H5轮播图新增
	+ H5轮播图删除
	+ H5轮播图修改
+ 停车场信息管理
  - 停车场信息界面
    * 停车场信息条件查询
    + 停车场信息新增
	+ 停车场信息删除
	+ 停车场信息修改
+ 停车位信息管理
  - 停车位信息界面
    * 停车位信息条件查询
    + 停车位信息新增
	+ 停车位信息删除
	+ 停车位信息修改
+ 车辆信息管理
  - 车辆信息界面
    * 车辆信息条件查询
    + 车辆信息新增
	+ 车辆信息删除
	+ 车辆信息修改
+ 车辆活动信息管理
  - 车辆活动信息界面
    * 车辆活动信息条件查询
    + 车辆活动信息新增
	+ 车辆活动信息删除
	+ 车辆活动信息修改
+ 识别记录信息管理
  - 车辆活动信息界面
    * 识别记录信息条件查询
    + 提交识别功能
	+ 识别记录信息删除
	+ 识别记录信息修改


#### 演示地址
```
登录地址: https://www.skywalking.pro/parking-platform
登录账号: admin
登录密码: 123456
```
若演示地址不可用，可扫码联系作者微信或者留言

####  **联系作者** 

 **这是作者的微信二维码，如需本项目源代码，可扫码或者VX:cyddhao联系作者。**  

![联系作者](https://skywalking-web.oss-cn-chengdu.aliyuncs.com/main-platform-fengfeiyezi.png)

#### 安装教程

#### 后端安装方法

```
1.  mvn clean package
2.  tar -zxvf parking-platform-api.tar.gz (解压tar包)
3.  cd parking-platform-api
5.  sh /sbin/startup.sh dev
```
#### 前端安装方法

```
1.  yarn install (安装node_moudle)
2.  yarn start (启动)
3.  yarn build:pro (构建生产包)
```
