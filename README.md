# jc-spring-boot
  某电商微服务框架模板v1
  
# 技术选型
## 框架(微服务)
+ spring boot 1.5.7
+ apache dubbo 2.5.6
+ zookeeper 3.4.5
+ mybatis + pagehelper + tk.mapper 持久化框架 + 管理系统分页 + 通用mapper(去xml)
## 日志+埋点+结构化数据存储
 MongoDB
## 缓存,消峰
 redis

# 技术设计要点
+ 数据库设计统一模板
  - 逻辑删除 创建/修改人&时间 分布式乐观锁 商户/APP数据水平拆分
+ 架构设计
  - 业务开发不关心数据库统一模板设计,架构在业务层(service层)为其赋值
  - json框架使用fastjson
  - 工具包统一使用apache-lang3







