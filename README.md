zabbix-book
===========

zabbix monitor file    
本项目是《Zabbix分布式监控系统运维》一书的附录部分，本书目录如下：

第一部分Zabbix基础
=
第一章，监控系统简介    
   1.1为何需要监控系统     
   1.2监控系统的实现 
   1.3监控系统的开源软件现状 
   1.4监控系统的原理探究    
第二章，Zabbix简介    
   2.1 Zabbix的客户    
   2.2 使用Zabbix的准备    
   2.3 Zabbix为何物	    
   2.4 选择Zabbix的理由	    
   2.5 Zabbix的架构	    
   2.6 zabbix运行流程	    
   2.7 Zabbix功能特性	    
第三章，安装部署	    
   3.1 安装环境概述	    
   3.2 zabbix_server服务端的安装	    
   3.3 zabbix-agent客户端的安装	    
   3.4 snmp监控方式的安装配置	    
   3.5 Windows上安装zabbix-agent	    
   3.6 其他平台的安装	    
   3.7 zabbix_get的使用	    
   3.8 zabbix术语（命令）相关	    
   3.9 Zabbix-server对数据的存储	    
   3.10 Zabbix init脚本解释	    
   3.11服务的高可用	    
   3.12关于安全的考虑	    
   3.13 禁用zabbix的重新安装	    
第四章，快速配置使用	    
   4.1配置流程	    
   4.2主机组的添加	    
   4.3模板的添加	    
   4.4添加主机	    
   4.5 Graphs的配置	    
   4.6 screen的配置	    
   4.7 Slide shows的配置	    
   4.8 zatree的使用	    
   4.9 map的配置	    
   4.10 WEB监控	    
   4.11 IT服务	    
   4.12报表	    
   4.13资产管理	    
第五章，深入配置使用	    
   5.1 Items的添加	    
   5.2 Items key的添加	    
   5.3 ITEMS的类型	    
   5.4宏的配置	    
   5.5维护时间	    
   5.6事件确认	    
   5.7数据的导入导出配置	    
第六章 ，告警的配置	    
   6.1 告警的概述	    
   6.2Trigger的配置	    
   6.3添加 Actions	    
   6.4邮件告警配置实例	    
   6.4.2创建用户	    
   6.5自定义脚本告警	    
   6.6邮件告警脚本的配置实例	    
   6.7告警升级的机制	    
   6.8告警配置故障排查	    
   
第二部分，zabbix中级部分	    
=
第七章，监控方式剖析	    
   7.1 Zabbix支持的监控方式	    
   7.2 Zabbix监控方式的逻辑	    
   7.3 agent监控方式	    
   7.4 Trapper监控方式	    
   7.5 SNMP监控方式	    
   7.6 IPMI监控方式	    
   7.7 JMX监控方式	    
   7.8命令执行	    
第八章，分布式监控	    
   8.1代理架构	    
   8.2节点架构	    
   8.3主动模式和被动模式	    
第九章，Zabbix与自动化运维	    
   9.1监控自动化	    
   9.2网络发现	    
   9.3主动方式的自动注册	    
   9.4 low level discovery	    
   9.5 Zabbix在自动化运维工具的使用	    
第十章，使用的经验技巧	    
   10.1如何有效的设置监控告警	    
   10.2监控项的使用技巧	    
   10.3触发器的使用技巧	    
   10.4触发器配置	    
   10.5谷歌浏览器告警插件	    
   10.6数据图断图的原因	    
第十一章，监控案例	    
   11.1监控tcp连接数	    
   11.2监控nginx	    
   11.3监控php-fpm	    
   11.4监控tomcat，weblogic	    
   11.5监控mysql	    
   11.6监控dell服务器	    
   11.7监控Cisco路由器	    
   11.8监控VMware	    
   11.9 hadoop监控	    
   11.10 更多监控	    
   
第三部分Zabbix高级部分
=
第十二章，性能优化	    
   12.1Zabbix的性能优化的概述	    
   12.2Zabbix的性能优化的依据	    
   12.3配置文件的参数优化	    
   12.4 Zabbix的架构优化	    
   12.5 Zabbix的items中工作模式以及Trigger的优化	    
   12.6 Zabbix的数据库优化	    
   12.7其他方面的	    
第十三章，Zabbix API的使用	    
   13.1 Zabbix API简介	    
   13.2什么是json-rpc	    
   12.3Zabbix API的使用流程	    
   13.4第三方zabbixAPI模块	    
第十四章，使用Zabbix协议	    
   14.1 Zabbix sender协议	    
第十五章，定制Zabbix安装包	    
   15.1为什么需要定制安装包	    
   15.2如何定制安装包	    
第十六章，大型分布式监控案例	    
   16.1监控系统构建的概述	    
   16.2监控环境架构图	    
   16.3架构实现的过程	    
   16.4业务相关的配置	    
   16.5其他需求   
   
第四部分 附录	    
=
第十七章，源码安装及相关配置	    
   17.1安装zabbix-server	    
   17.2 Zabbix-agent的安装	    
   17.3 关于zabbix的升级	    
