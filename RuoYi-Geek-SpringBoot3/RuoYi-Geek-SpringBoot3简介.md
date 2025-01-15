RuoYi-Geek-SpringBoot3 是基于Spring Boot 3 和 RuoYi-Geek 框架开发的开源项目，旨在提供一个高效、灵活、易用的后台管理系统解决方案。它结合了 RuoYi 的优秀特性和 Spring Boot 3 的新功能，适合快速开发企业级应用。

# 平台简介

本平台是一套全部开源的快速开发平台，毫无保留给个人及企业免费使用。

* 前端采用Vue3、Element Plus。
* 后端采用Spring Boot3、Spring Security、Redis & Jwt。
* 权限认证使用Jwt，支持多终端认证系统。
* 支持加载动态权限菜单，多方式轻松权限控制。
* 高效率开发，使用代码生成器可以一键生成前后端代码。
* 多数据源与分库分表默认集成
* 所有非基本模块可随意插拔，让开发更加简单高效
* 提供了多个工具模块助力开发，如：在线接口模块、mybatis-jpa模块
* 提供了多个常见业务模块简化开发，如：第三方认证模块、支付模块
* 提供了多个常见的服务模块集成开发，如：websocket模块、minio模块
* 特别鸣谢：[element](https://gitee.com/link?target=https%3A%2F%2Fgithub.com%2FElemeFE%2Felement)，[vue-element-admin](https://gitee.com/link?target=https%3A%2F%2Fgithub.com%2FPanJiaChen%2Fvue-element-admin)，[eladmin-web](https://gitee.com/link?target=https%3A%2F%2Fgithub.com%2Felunez%2Feladmin-web)。
* 阿里云折扣场：[点我进入](https://gitee.com/link?target=http%3A%2F%2Faly.ruoyi.vip)，腾讯云秒杀场：[点我进入](https://gitee.com/link?target=http%3A%2F%2Ftxy.ruoyi.vip)
* 阿里云优惠券：[点我领取](https://gitee.com/link?target=https%3A%2F%2Fwww.aliyun.com%2Fminisite%2Fgoods%3FuserCode%3Dbrki8iof%26share_source%3Dcopy_link)，腾讯云优惠券：[点我领取](https://gitee.com/link?target=https%3A%2F%2Fcloud.tencent.com%2Fredirect.php%3Fredirect%3D1025%26cps_key%3D198c8df2ed259157187173bc7f4f32fd%26from%3Dconsole)

# 主要特性

**核心：模块化架构设计，支持各个模块的快速安拆，对第三方认证、第三方支付模块设计了基础的规范和基础模块。**

1. **Spring Boot 3 支持** ：

* 基于 Spring Boot 3 开发，充分利用其新特性和性能优化。
* 支持 Java 17 及以上版本。
* 改用SpringBoot3+java17的更新的技术栈并改掉所有的弃用的方法。

2. **RuoYi-Geek 框架** ：

* 继承了 RuoYi 的模块化设计，便于扩展和维护。
* 提供丰富的后台管理功能，如用户管理、角色管理、权限管理等。

   3. **前后端分离** ：

* 前端采用 Vue、Element Plus，后端提供 Spring Boot3、Spring Security、Redis & Jwt，便于前后端独立开发和部署。

4. **安全性** ：

* 集成 Spring Security，提供完善的权限控制和认证机制。
* 支持 JWT 等现代认证方式。

5. **数据库支持** ：

* 支持多种数据库，如 MySQL、Oracle 等。
* 集成 MyBatis-Plus，简化数据库操作。

6. **代码生成器** ：

* 升级了代码生成器（配合本项目的vue3版本才可用），使关联表生成更加简单。

# 适用场景

* **企业级后台管理系统** ：适用于需要复杂权限管理和多模块集成的企业应用。
* **快速开发平台** ：适合需要快速搭建原型的项目，减少开发周期。
* **学习与教学** ：适合学习和研究 Spring Boot 3 和 RuoYi 框架的开发者。
