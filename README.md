![gh_17810254f3db_258](https://github.com/user-attachments/assets/898458bb-c3e1-44e8-9de6-70d7653492c3)

**郑重声明：项目经过本地测试，确保可以运行。由于精力有限，不提供调试服务。项目仅供学习和毕业设计参考~**

#### 1.项目介绍

技术栈+工具：SpringBoot + JSP + MySQL + Maven + IDEA2022

系统角色：管理员、普通用户

系统功能：管理员（影片类别管理、影片管理、影院管理、放映管理、订单管理、票房管理、系统管理、留言管理等）、普通用户/门户（注册登录、电影信息、在线订票、我的订单、充值等）

#### 2.项目部署

- 创建数据库，导入项目中的sql

- 打开IDEA，导入项目shoupiao

- 根据本地数据库环境，修改数据库的连接信息 src/main/resources/application.properties 16-19行

- 启动项目，运行 http://localhost:8080/dingpiao 普通用户账号/密码：18657571688/123456 

- 管理web http://localhost:8080/dingpiao/admin/login.jsp  管理员账号/密码： admin/admin
