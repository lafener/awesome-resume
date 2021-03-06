---

# 联系方式

- Email：hang@srhang.me
- QQ/微信：285104010

---

# 个人信息

 - 杭建/男/1987 
 - 工学硕士/西安电子科技大学/计算机学院/计算机系统结构
 - 工学学士/西安电子科技大学/计算机学院/网络工程
 - 工作年限：2年
 - 微博：@[飒然Hang](http://weibo.com/superhj1987)
 - 技术博客：[http://srhang.me/blog](http://srhang.me/blog)
 - Github: [http://github.com/superhj1987](http://github.com/superhj1987)

---

# 工作经历

- 随身云(北京)信息技术有限公司 （ 2014年11月 ~ 至今 ）

	**服务端技术负责人**：负责公司的服务端技术管理工作，包括架构设计、难点解决、代码review、技术培训等，重构了服务端技术框架，搭建了公司的git、maven、jekens、sonar等基础开发设施，此外主持了公司的大数据平台的开发工作。
	
- 网易杭州研究院 （ 2013年4月 ~ 2014年11月 ）

	**高级软件开发工程师**： 服务端开发：公共基础平台技术、业务部门技术支撑。	

# 项目经验

## 随身云(北京)信息技术有限公司

### 基础平台

针对整个公司，设计了micro service的架构。将基础服务抽离出来，做到低耦合，以便于维护升级。

- cas: 单点登录系统

- eservice: 基础服务中心：App认证、管理；CAS用户认证、管理；

- suishen-dao: 借鉴my-batis实现的dao框架，基于spring，实现了dao层的操作，包括事务管理以及cache操作。no xml配置，依赖于注解。

### Peacock

随身云内容投放系统，包括自有广告、第三方广告等的投放。对于存储、高并发有着较高的要求。

### SSY-DMP

随身云Data mining platform，包括统计和数据挖掘等功能。

- 统计模块采用flume+kafka+storm+hbase的架构，辅以redis（去重等处理）。
- 数据挖掘模块（未开始）


### [中华万年历](http://www.zhwnl.cn)

此项目是公司的主要项目，拥有1.5亿用户，日活跃人数在100万左右。本人review了其关键代码，并做了一些架构重新设计。具体参与了V6的卡片管理以及社区系统的设计与开发。


### [美历](http://meili.me) 

此项目是一个女性经期管理社交APP，用户已达50万，并不断增长中。具体参与了V4版本的架构设计以及帖子广场的算法设计以及实现。


### [洋蜜美食汇](http://www.yangmi.com)

此项目是公司的电商项目，面向吃货。针对此系统，设计了ark电商系统：商品中心、交易中心、售后中心以及后台系统。这几个系统间通过esb总线通信，完成电商功能。

 
## 网易杭州研究院

### 网易云计算NLB 

NLB，即NetEase Load Balance-网易弹性负载均衡。为网易云计算项目提供动态负载均衡支持。技术选型：c语言(agent)、node(server)、python(脚本)、pomelo(通讯框架)。

项目主要开发者，参与项目需求、架构设计。主要负责七层负载均衡以及代理端设计实现，部分服务端开发工作、部分脚本开发工作。


### [易信公众平台](http://plus.yixin.im)

易信公众平台是易信的主要功能之一，为用户提供公众帐号服务。整个系统采用Spring+DAO+DDB+NDIR架构设计。现已上线，为易信公众帐号以及用户提供公众平台服务。

项目主要开发工程师，完成系统用户管理、实时消息、高级功能、群发消息、通用发码、应用平台oauth认证等主要功能模块的开发以及多个第三方公众帐号的开发工作，并参与整体架构设计、部署等。


### 运维监控平台-交换机监控系统

网易杭研的运维平台主要功能之一，采集网易杭州机房内部几百台交换机的数据，绘制成图表，供服务器维护人员使用。现已上线运行，提供服务。

全权负责，包括技术选型、前后端开发，部署以及维护。实现了主从互备从而保证系统的高可用（通过心跳保证监控采集守护进程存活）。


## 学生期间项目

### 嗨翻校园（原掌上校园）

嗨翻校园（原掌上校园）是一款定位于校园生活服务的移动APP，全方位覆盖校园的各类生活服务。基于Android平台，服务端采用LAMP架构。目前处于上线运营状态，服务于西安电子科技大学在校学生。

项目负责人，完成产品的需求分析、系统设计，并具体完成服务端信息抓取、接口开发以及客户端部分功能模块。

### [狠狠推](http://www.henhentui.com)

狠狠推是立志于在信息爆炸时代，为用户过滤，推荐对他来说最重要的信息的服务。此项目入选2011腾讯学生孵化项目并在QQ labs进行展示。在2012盛大云计算开发&创意大赛中获得最佳技术、最佳移动应用、最佳用户体验三项大奖。现已正式上线运营，并引起了很多资本的关注，如创新工场、盛大创新院等。雷锋网、动点科技等科技博客给予过报道。服务端采用Java、PHP语言，LAMP架构。

团队技术负责人，负责产品的技术选型、系统架构，并具体完成Web端的设计开发、服务端信息抓取、部分API接口的开发工作。

### [陕西省专业技术人员继续教育学习平台](http://www.sxjxjy.gov.cn)

为陕西省人社厅建立的“专业技术人员”继续教育学习支撑和管理平台。包括学习平台、教学管理平台、管理系统三大部分。基于SSH+ExtJs架构。现已上线运行，为全陕西省30个继续教育基地、上千单位以及130万专业技术人员服务。

项目开发组长，负责搭建系统整体架构、技术选型、核心模块的编写以及系统的部署、维护等。并具体实现了学习平台和教学管理平台的几个模块功能。

### 综合网络管理系统XNMS

项目来自于：装备科技网络安全预警和控制系统研究与开发，实现综合网络管理系统。包括网络管理五大功能模型，涵盖传统计算机网络、物联网、移动网络等。使用了Java、C/C++语言以及snmp++、agent++、agentX++、GTK+等技术。

项目开发组长，负责项目的需求分析、整体设计、进度控制等。具体设计完成了Linux下的内网安全管理系统以及移动终端设备管理系统。

---

# 开源项目和作品

## 开源项目

 - [java-develop-practice](https://github.com/superhj1987/java-develop-practice): Java开发相关技术的总结
 - [spring-remoting-thrift](https://github.com/superhj1987/spring-remoting-thrift):Spring remoting thrift support
 - [spring-mvc-model-attribute-alias](https://github.com/superhj1987/spring-mvc-model-attribute-alias) : 针对spring mvc的model attribute不支持别名的解决方案。
 - [nginx_cookbook](https://github.com/superhj1987/nginx_cookbook): 学习nginx源代码的学习笔记以及一些实践代码
 - [netty-study](https://github.com/superhj1987/netty-study):netty源代码学习笔记以及实践代码
 - [awesome-tpool](https://github.com/superhj1987/awesome-tpool) : c实现的基于posix的线程池
 - [awesome-queue](https://github.com/superhj1987/awesome-queue): c实现的队列源码
 - [picclipper](https://github.com/Suishenyun/picclipper): android上的截图软件，特殊之处在于可以进行多边形截图。
 - [awesome-identicon](https://github.com/superhj1987/awesome-identicon): java实现的identicon（像素头像）
 - [useful-scripts](https://github.com/oldratlee/useful-scripts): 一些实用的shell脚本，本人贡献了一些服务端监控shell脚本
 
## 技术文章

- [Spring mvc的controller传递HttpServletResponse参数的一点事](http://www.srhang.me/blog/2014/12/09/spring-mvc-httpservletresponse/)
- [ShellShock这点事](http://www.srhang.me/blog/2014/09/29/shell-shock/) 
- [Nginx负载均衡](http://www.srhang.me/blog/2014/08/27/nginx-loabbalance/)
- [谈谈系统架构这个东西](http://srhang.iteye.com/blog/2076025)

---

# 技能清单

以下均为我熟练使用的技能

- 开发语言：Java/C/Node/PHP/Python/Shell
- 开发框架：Spring/Spring mvc/MyBatis/Struts/Netty
- 前端框架：Jquery/ExtJs/BootStrap
- 数据库相关：MySQL/Redis/Oracle
- 版本管理、文档和自动化部署工具：Svn/Git/Jira/Jenkins
- 单元测试：Junit
- 分布式技术：Storm/Hbase
- 消息队列：Kafka/RabbitMQ
