# jooq-gencode-gradle
gradle 生成 jooq 代码

## step 1：
到jooq目录下，找到jooqdb.xml, 修改数据库连接、packageName等相关参数

## step 2:
执行以下命令生成jooq-code：

```
gradle -b jooq.gradle generate --debug -Ddb=userdb
```
