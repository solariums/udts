

# PostgreSQL

UDTS支持PostgreSQL作为数据传输源/目标。

## PostgreSQL填写表单

| 参数名   | 说明                                                         |
| -------- | ------------------------------------------------------------ |
| 地址类型       | 提供内网地址，外网地址，专线地址三种方式，内网地址需要填写VPC和子网信息，外网地址支持ip和域名两种 |
| 数据库名 | PostgreSQL数据库名称|                                         |
| 端口     | PostgreSQL连接端口                                                |
| 用户名   | PostgreSQL连接用户名                                              |
| 密码     | PostgreSQL数据库对应用户密码                                      |
| 表名     | PostgreSQL传输表名，若不填，系统默认为整库迁移                    |


