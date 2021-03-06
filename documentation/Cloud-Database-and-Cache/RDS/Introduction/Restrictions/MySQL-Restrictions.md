# 限制说明
## 最大连接数限制
### MySQL
|实例规格|最大连接数|
|---|---|
|1核 1GB|300|
|1核 2GB|600|
|1核 4GB|1200|
|2核 8GB|2000|
|4核 16GB|4000|
|8核 32GB|8000|
|16核 64GB|16000|

### MySQL 只读实例
|实例规格|最大连接数|
|---|---|
|1核 1GB|300|
|1核 2GB|600|
|1核 4GB|1200|
|2核 8GB|2000|
|4核 16GB|4000|
|8核 32GB|8000|
|16核 64GB|16000|

## 功能限制
### 缩容操作
* 现在不支持实例的缩容。

### 数据库版本升级
* 现在不支持数据库版本的升级。例如 MySQL 5.6 升级到 MySQL 5.7。

### 实例恢复
* 针对已经删除的实例，不支持恢复。

### 创建实例
* 针对单地域的实例数是有限制的，一个地域默认最多支持 5 个实例，如果有更多实例需求，请提交工单。
