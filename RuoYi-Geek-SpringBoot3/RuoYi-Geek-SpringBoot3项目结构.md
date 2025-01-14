本项目是基于 Spring Boot 的后台管理系统，对若依（RuoYi）框架进行完善升级，它具有模块化设计，灵活的系统配置和权限管理等功能。以下是一个典型的框架目录结构示例：

```
ruoyi-geek-project/
├── ruoyi-admin                    # 后台管理模块
│   ├── src
│   │   ├── main
│   │      ├── java               # Java源代码
│   │      │   └── com/ruoyi      # 主要包路径
│   │      │       ├── web
│   │      │       │   │──controller   #响应输入，处理请求
│   │      │       │   │── core        #基础服务
│   │      │       ├── RuoYiApplication.java   # 启动类
│   │      │       ├── RuoYiServletInitializer.java     # Servlet容器
│   │      │  
│   │      └── resources           # 资源文件
│   │          ├── application-auth.yml            # app配置
│   │          ├── application-druid.yml           # 主数据源配置
│   │          ├── application-pay.yml             # 支付宝配置
│   │          └── application.yml    # 开发环境配置
│   └── pom.xml                     # Maven依赖管理
├── ruoyi-framework                 # 系统框架模块
│   ├── src
│   │   ├── main
│   │      ├── aspectj               #数据处理 
│   │      │── config                #基础配置
│   │      │── datasource            #数据源配置
│   │      │── interceptor           #拦截器
│   │      │── manager               #业务逻辑管理层
│   │      │──security               #应用安全验证
│   │      └── web                   # 交互配置
│   └── pom.xml                     # Maven依赖管理
├── ruoyi-middleware                 # 中间件配置模块 
│   
├── ruoyi-models                    # 数据模型配置
│
├── ruoyi-pay                       # 支付接口配置
│
├── ruoyi-plugins                   # 扩展功能
│
├── ruoyi-system                    # 系统管理模块
│   ├── src
│   │   ├── main
│   │   │   ├── java               # 框架相关的Java源码
│   │   │   └── resources          # 框架相关的资源文件
│   └── pom.xml                     # Maven依赖管理
└── sql                             # 数据库脚本目录
```
