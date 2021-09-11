# sky-mall

## 部署 nacos
> 进入目录， `sky-mall-compose`
1. 启动 MySQL，`docker-compose up -d mysql` 
2. 导入表结构，`nacos/data.sql`
3. 启动 nacos, `docker-compose up -d nacos`
4. 查看日志， `docker-compose logs nacos`
5. 访问 http://localhost:8848/nacos/, 用户名和密码均是 nacos