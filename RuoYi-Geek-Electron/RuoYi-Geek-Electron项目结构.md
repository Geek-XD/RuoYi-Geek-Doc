
# RuoYi-Geek-Electron项目结构

```bash
├── build                         //编译后的文件
├── dist                          //发布版本
├── node_modules                  //Node.js 依赖包
├── out                           //编译输出
│   ├── main                        //主进程
│   ├── preload                     //预加载
│   └── renderer                    //渲染进程
├── resources                     //资源
├── src                           //源代码(ts)
│   ├── main                        //主进程
│   │   ├── annotation                // 注解
│   │   │   ├── BindMapping.ts          //绑定映射
│   │   │   └── WorkerRunner.ts         //工作线程运行器
│   │   └── utils                   //工具函数
│   │   └── window                  //窗口相关
│   │   │   ├── BaseWindow.ts         //基础窗口
│   │   │   └── IndexWindow.ts        //主窗口
│   │   └── index.ts                // 入口
│   ├── preload                     //预加载
│   └── renderer                    //渲染进程


```
