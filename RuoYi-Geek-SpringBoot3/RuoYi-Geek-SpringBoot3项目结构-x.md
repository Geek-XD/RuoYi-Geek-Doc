<<<<<<< HEAD

# RuoYi-Geek-SpringBoot3项目结构

```bash
├──    ruoyi-admin                        // 管理后台模块
│   ├── src/main
│   │   ├── java/com/ruoyi                    //项目的 Java 源代码
│   │   │   └── web                           // Web 相关的 Java 类
│   │   │   ├── RuoYiApplication.java         //应用程序主类，用于启动应用程序。
│   │   │   └── RuoYiServletInitializer.java  //Servlet 初始化类
│   │   └── resources                         //资源文件
│   └── target                                //输出目录
│   └── pom.xml                               //配置文件
├──   ruoyi-auth                          //认证模块
│   ├── ruoyi-auth-common                     // 通用模块或库
│   ├── ruoyi-auth-starter                    // 启动器
│   ├── ruoyi-oauth-justauth                  // OAuth 认证和授权
│   ├── ruoyi-oauth-wx                        //微信认证和授权。
│   ├── ruoyi-tfa-email                       // 邮件双因素认证
│   ├── ruoyi-tfa-phone                       // 手机双因素认证
│   └── pom.xml                               //配置文件
├── ruoyi-common                          //公共模块
│   ├── src/main/java/com/ruoyi/common
│   │   ├── annotation                        // 自定义注解
│   │   ├── config                            // 配置类
│   │   ├── constant                          // 常量类
│   │   ├── core                              // 核心业务逻辑类
│   │   ├── enums                             // 缓存枚举类。
│   │   ├── exception                         // 异常处理类。
│   │   ├── filter                            // 过滤器类。
│   │   ├── service                           // 服务层接口和实现类。
│   │   ├── utils                             // 工具类。
│   │   └── xss                               // 与跨站脚本（XSS）防护相关的类。
├── ruoyi-framework                       //框架模块
│   ├── src/main/java/com/ruoyi/framework
│   │   ├── aspectj                           //AOP切面
│   │   ├── config                            // 配置类
│   │   ├── datasource                        // 数据源配置
│   │   ├── interceptor                       // 拦截器
│   │   ├── manager                           // 管理器
│   │   ├── security                          // 安全配置
│   │   └── web                               //  Web 相关配置
│   ├── generated-sources                     // 注解处理器生成的源代码文件
│   ├── generated-test-sources                // 测试注解处理器生成的源代码文件
├── ruoyi-middleware                      //中间件模块
│   ├── ruoyi-middleware-minio                //  MinIO存储服务
│   ├── ruoyi-middleware-rabbitmq             // 与RabbitMQ消息队列服务
│   ├── ruoyi-middleware-redis                // Redis缓存服务
│   └── ruoyi-middleware-starter              // 中间件启动器
├── ruoyi-models                          //模型模块
│   ├── ruoyi-generator                       // 代码生成器
│   ├── ruoyi-models-starter                  // 模型启动器
│   ├── ruoyi-online                          // 在线模块
│   ├── ruoyi-quartz                          // 定时任务
├── ruoyi-pay                             //支付模块
│   ├── ruoyi-pay-alipay                      // 支付宝支付
│   ├── ruoyi-pay-common                      // 通用支付组件
│   ├── ruoyi-pay-sqb                         // SQB 支付
│   ├── ruoyi-pay-starter                     // pay启动器
│   ├── ruoyi-pay-wx                          // 微信支付
└── ruoyi-plugins                         //插件模块
│   ├── ruoyi-alibaba-oss                     // 阿里云 OSS 存储
│   ├── ruoyi-atomikos                        // Atomikos事务管理
│   ├── ruoyi-ehcache                         // Ehcache 缓存
│   ├── ruoyi-mybatis-interceptor             // MyBatis 拦截
│   ├── ruoyi-mybatis-jpa                     // MyBatis 和 JPA 集成
│   ├── ruoyi-mybatis-plus                    //  MyBatis Plus 扩展
│   ├── ruoyi-netty                           // Netty 网络编程
│   ├── ruoyi-plugins-starter                 // 插件启动器
│   ├── ruoyi-websocket                       //  WebSocket支持
├── ruoyi-system                          //系统模块
├── sql                                   //SQL脚本目录
│   ├── auth.sql                              //数据库认证SQL 脚本。
│   ├── create_database.sql                   // 创建数据库 SQL 脚本。
│   ├── gen.sql                               // 生成相关数据SQL 脚本。
│   ├── online.sql                            // 在线服务相关SQL 脚本。
│   ├── pay.sql                               // 支付相关的 SQL 脚本。
│   ├── quartz.sql                            // Quartz 定时任务相关的 SQL 脚本。
│   └── ry_20230223.sql                       // 系统初始数据 SQL 脚本。
```
