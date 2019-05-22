# MyRocks_zh_doc
MyRocks 文档翻译

## 目录

### 概览
      [构建步骤](一、概览/0.构建步骤.md)
      [MyRocks入门](一、概览/1.MyRocks入门.md)
      [如何报告错误并寻求帮助](一、概览/2.如何报告错误并寻求帮助.md)
      [MyRocks优于InnoDB](一、概览/3.MyRocks优于InnoDB.md)
      [MyRocks限制](一、概览/4.MyRocks限制.md)
      [新MySQL MyRrocks引擎变量参数](一、概览/5.新MySQL MyRrocks引擎变量参数.md)
      [MyRocks编码约定](一、概览/6.MyRocks编码约定.md)

### 事务

      [行锁](二、事务\1.行锁.md)
      [事务隔离级别](二、事务\2.事务隔离级别.md)
      [崩溃修复](二、事务\3.崩溃修复.md)
      [配置slave节点崩溃安全修复](二、事务\4.配置slave节点崩溃安全修复.md)
      [配置master节点崩溃安全修复](二、事务\5.配置master节点崩溃安全修复.md)

### 备份

      [使用mysqldump工具逻辑备份](三、备份\1.使用mysqldump工具逻辑备份.md)
      [使用myrocks_hotbackup工具物理备份](三、备份\2.使用myrocks_hotbackup工具物理备份.md)

### 性能调优

      [my.cnf配置参数设置](四、性能调优/1.my.cnf配置参数设置.md)
      [数据导入](四、性能调优/2.数据导入.md)
      [结构设计](四、性能调优/3.结构设计.md)
      [更快的delete删除操作](四、性能调优/4.更快的delete删除操作.md)
      [生存时间TTL](四、性能调优/5.生存时间TTL.md)
      [Read Free Replication特性](四、性能调优/6.Read Free Replication特性.md)
      [分区表列族](四、性能调优/7.分区表列族.md)
      [手动压缩](四、性能调优/8.手动压缩.md)

### 监控

      [Show Engine Status查看引擎状态](五、监控\1.Show Engine Status查看引擎状态.md)
      [MyRocks新引擎返回码](五、监控\2.MyRocks新引擎返回码.md)
      [Information Schema状态](五、监控\3.Information Schema状态.md)     

### 迁移

      [从InnoDB引擎迁移到MyRocks引擎](六、迁移\1.从InnoDB引擎迁移到MyRocks引擎.md)
      [从官方MySQL 5.6复制到Facebook MySQL 5.6](六、迁移\2.从官方MySQL 5.6复制到Facebook MySQL 5.6.md)

### 内部结构
      [MyRocks数据字典格式](七、内部结构\1.MyRocks数据字典格式.md)
      [MyRocks记录格式](七、内部结构\2.MyRocks记录格式.md)
      [MyRocks优化器统计信息](七、内部结构\3.MyRocks优化器统计信息.md)

#### 原文出自

      [FaceBook MyRocks Wiki](https://github.com/facebook/mysql-5.6/wiki)

