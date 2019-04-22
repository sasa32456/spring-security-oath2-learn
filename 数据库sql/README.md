# 数据库设计
官方https://github.com/spring-projects/spring-security-oauth/blob/master/spring-security-oauth2/src/test/resources/schema.sql

由于我们使用的是 MySQL 数据库，默认建表语句中主键为 VARCHAR(256)，这超过了最大的主键长度，请手动修改为 128，并用 BLOB 替换语句中的 LONGVARBINARY 类型

此处mysql_后面是数据库名
