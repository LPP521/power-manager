# power-manager
机房服务器通过idrac接口控制所有服务器的开关机（后端代码）

# 依赖
使用python3.6开发 使用bottle这个web框架

第三方库依赖：
* bottle
* pymysql
* setproctitle
* urllib3
* python-dracclient

后端需要连接数据库 只需要提供必须的几个表字段就可以了 
必须的字段看配置文件这部分的配置
