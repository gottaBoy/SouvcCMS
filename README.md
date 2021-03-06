# 欢迎使用SouvcCMS

**SouvcCMS**是一种使用java语言开发的博客平台，用户可以在支持Java和MySQL数据库的服务器上架设属于自己的网站，也可以把它当作一个内容管理系统(CMS)来使用。特点概述：
 
- **免费完整开源** ：基于MIT协议，源代码完全开源，无商业限制；
- **开发文档周全** ：开发环境，技术框架等介绍一应俱全，是工作学习好帮手；


##面向用户

个人开发者也可以使用SouvcCMS承接外包项目；
初学JAVA的同学可以下载源代码来进行学习交流；


##开发环境

建议开发者使用以下环境，这样避免版本带来的问题

* language：[Java](http://www.oracle.com/technetwork/java/index.html)
* IDE：[Eclipse](http://www.eclipse.org/)，[IntelliJ IDEA](http://www.jetbrains.com/idea/)
* JDK：[JDK 7](http://www.oracle.com/technetwork/cn/java/javase/downloads/jdk7-downloads-1880260.html)
* 数据库：[Mysql5.5](http://dev.mysql.com/downloads/)
* 数据库管理工具：[Navicat for MySQL](https://www.navicat.com/download/navicat-for-mysql)
* WEB服务器：[Tomcat 7](http://tomcat.apache.org/download-70.cgi)、[JBoss 6](http://jbossas.jboss.org/downloads)、[Jetty](https://github.com/eclipse/jetty.project) 等
* 版本管理工具：[Git](https://git-scm.com/download/)
* 代码托管平台：[Github](https://github.com/souvc/)
* Jar包管理：[Maven](http://maven.apache.org/)
* 操作系统：[Windows](https://www.microsoft.com/zh-cn/windows)、[Ubuntu](http://www.ubuntu.com/download) 等
* 编码方式：UTF-8



##技术框架

* 核心框架：[Spring Framework 4](http://projects.spring.io/spring-framework/)
* 安全框架：[Spring Security 4](http://projects.spring.io/spring-security/)
* 视图框架：Spring MVC 4
* 持久层框架：[Hibernate 4 ](http://hibernate.org/orm/)
* 数据库连接池：C3P0，或者[Alibaba Druid 1.0 ](https://github.com/alibaba/druid/)
* 日志管理：[SLF4J 1.7](http://www.slf4j.org/)、[Log4j2.x](http://logging.apache.org/log4j/2.x/)
* JS框架：[jQuery  1.x - 3.x ](https://jquery.com/)
* CSS框架：[Bootstrap 3](http://www.bootcss.com/)
* 文本编辑器： [Baidu Ueditor](http://ueditor.baidu.com/website/)


##开发工具一键下载


360网盘下载：https://yunpan.cn/c6kLee2Eyrhgx  访问密码 155c


##数据库表设计

说明：WordPress 是一个功能非常强大的博客系统，插件众多，易于扩充功能。安装和使用都非常方便。目前 WordPress 已经成为主流的 Blog 搭建平台。数据库表就是参照WordPress来进行设计的。

* souvc_cms_commentmeta：存储评论的元数据
* souvc_cms_comments：存储评论
* souvc_cms_links：存储友情链接（Blogroll）
* souvc_cms_options：存储WordPress系统选项和插件、主题配置
* souvc_cms_postmeta：存储文章（包括页面、上传文件、修订）的元数据
* souvc_cms_posts：存储文章（包括页面、上传文件、修订）
* souvc_cms_term_relationships：存储每个文章、链接和对应分类的关系
* souvc_cms_term_taxonomy：存储每个目录、标签所对应的分类
* souvc_cms_terms：存储每个目录、标签
* souvc_cms_usermeta：存储用户的元数据
* souvc_cms_users：存储用户

详细sql语句可以参照：https://github.com/souvc/SouvcCMS/blob/master/doc/db/souvccms.sql


##实体类生成工具

* 根据配置数据库信息，生成实体类。源码可以参照：https://github.com/mybatis/generator
* 本项目用的实体类生成工具，参照：https://github.com/souvc/SouvcCMS/tree/master/doc/tools/generator


##Maven学习教程

* [Windows环境下Apache Maven下载，安装与环境变量配置](http://www.souvc.com/?p=377)
* [Windows环境下命令行创建java项目](http://www.souvc.com/?p=382)
* [Maven命令行大全–按照字典顺序排序](http://www.souvc.com/?p=424)
* [Windows环境下用maven命令行创建javaweb项目](http://www.souvc.com/?p=397)
* [json-lib 的maven dependency找不到的解决方法](http://www.souvc.com/?p=1350)


##项目文件

项目目录结构

* com.souvc.cms.biz  
* com.souvc.cms.common.base
* com.souvc.cms.common.cache
* com.souvc.cms.controller
* com.souvc.cms.dao
* com.souvc.cms.entity   
* com.souvc.cms.security  



