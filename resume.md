# 个人信息
- 夏正月/本科/男/1994 
- 湘潭大学/2016届/5年工作经验
- blog： [https://russxia.com](https://russxia.com)
- 求职意向：Java开发工程师

---

# 联系方式
- 邮箱：xzy199400@foxmail.com
- 手机：13776598417

---

# 技能
---
- 熟悉Java集合、多线程、JUC、反射、锁等
- 了解JVM内存模型，类加载机制，常见的GC算法
- 熟悉Spring、Mybatis、Spring Boot、Spring Cloud、Dubbo等技术栈
- 熟悉MySQL、Redis等主流数据库

---

# 工作经历

## 杭州大搜车-24车团队（2019.1 - 2021.4）

### 主要项目

+ 悠享车服-车主服务(微信小程序)：接入第三方权益，通过商品购买、积分兑换等功能兑换权益
  + 和第三方平台对接权益
  + 整合第三方权益，提供会员卡的购买、会员权益的发放、订单及相关流水
  + 提供商品限时购功能，包括SPU、SKU功能
  + 任务积分系统，提供积分兑换功能
+ 抖聊(微信小程序)：基于抖音开放平台实现的一个聊天、车商跟进工具
  + 对接抖音开放平台，基于抖音的私信和推送功能实现聊天功能
  + 使用公司自研的延时队列工具(基于Redis的zset)，实现定时群发功能
  + 整合抖音中的意向用户、粉丝用户，方便用户及时跟进客户
+ 弹车金项目(APP)：弹车金通过活动是发放给C端用户的一种奖励。这个奖励可用于用户购车还了每期月租后的返现。目的是促进用户留存和在活动期间的下单意向
  + 设计预算池、弹车金活动、弹车金的发放、弹车金的使用等功能
  + 使用Sentinel对Dubbo接口进行限流
  + 使用Redis分布式锁做并发控制，使用MySQL乐观锁防止超发

### 其他项目

+ 天猫商品发布工具(后台管理工具)：对接淘宝开放平台，提供天猫商品发布工具，提升运营效率
+ 24车管家(微信小程序)：针对女性车主用户，提供管家式一对一服务，获取流量
+ 宝马二手车投放项目(支付宝小程序)：和宝马合作的一次引导二手车车主回流到宝马经销商门店的项目。用户通过留资、上传行驶证领取一张可以到指定宝马门店做免费机油保养的券
+ 汽车福利社(支付宝小程序)：和支付宝合作的投放落地页，提供打卡签到领奖品功能，引导用户留咨、导流到大搜车天猫旗舰店

### 主要工作

+ 负责项目的需求评审设计，技术框架选型，以及部分功能设计。

  搭建技术框架主要由：SpringBoot + Mybatis + Spring Cache + Redis + RocketMQ + Dubbo构成
+ 帮助项目组内同学排查问题，review代码
+ 负责对应应用线上服务稳定性和性能优化



## 杭州美图美妆（2018.3 — 2018.11）

### 红包项目(普通红包、会员红包、满返红包等)

**项目描述** : 从零开始搭建红包项目，实现红包相关功能
**工作内容** :

+ 分层红包结构，解构成：预算控制、红包活动(领取门槛+玩法规则)、红包领取、红包使用(对接交易+红包流水)四大模块
+ 使用Redis作为缓存和分布式锁
+ 使用Sharding-JDBC做红包和红包流水的分表
+ 排查线上问题，优化GC问题


## 卖好车(杭州一骑轻尘)（2016.8 — 2018.3）

**项目描述** : 这是一个服务于供应商和经销商的 App 业务，产品名称:卖好车。主要包含交易、金融、仓储、物流等四条业务线。本人主要负责的是交易以及平台运营的相关业务。交易业务主要包含车源、寻车、惠拼车、担保交易、秒车库(打通仓储、物流、金融的一个产品)等相关业务。

**工作内容** :
+ 负责普通寻车、竞价寻车等业务的支持和开发
+ 秒车库、车源等相关业务的开发和支持 
+ 相关需求和接口有对象的文档产出 
+ 为相关功能提供后台系统管理功能