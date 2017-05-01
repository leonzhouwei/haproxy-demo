# 运行环境

----
## HAProxy
占用端口号为 23306

----
## 2 个 MySQL 兼容的数据库实例
- 一个实例是货真价实的 MySQL，占用端口号为 3306
- 另一个实例是 [tidb](https://github.com/pingcap/tidb/blob/master/docs/QUICKSTART.md)，占用端口号为 4000

----
## 通过 haproxy 访问 MySQL 实例的命令
mysql -h 127.0.0.1 -P 23306 -u root
