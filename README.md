# RuoYi-Geek-Doc

## 仓库简介

该仓库专门存放GEEK-XD生态各类框架如：RuoYi-Geek-SpringBoot3、RuoYi-Geek-Vue3、RuoYi-Geek-App、RuoYi-Geek-Electron的文档

## GEEK-XD生态介绍

原版的RuoYi-Vue与RuoYi-App是基于SpringBoot2+Vue2打造的企业级开发框架，得到了广大开发者的喜爱和积极反馈。但随着技术的迭代进步，SpringBoot3与Vue3逐渐进入开发者的视野。为了满足开发者对于新技术的追求，RuoYi官方文档提供了SpringBoot2至SpringBoot3的升级方法。与此同时，社区也涌现出了RuoYi-Vue3、RuoYi-App-Vue3的版本，展现了开发者社区对于技术升级的热情与努力。

然而，在升级的过程中，官方的方法为了兼顾Java1.8的特性与一些老旧的方法，未完全拥抱SpringBoot3与Java17的全部特性。而社区中的RuoYi-Vue3、RuoYi-App-Vue3版本由于出自不同的团队之手，兼容性及整合性上存在些许不足。更为关键的是，尽管这些版本支持TypeScript，但缺乏与之相匹配的tsconfig.json配置文件，这使得在主流编辑器如VSCode中，TypeScript的语法提示环境并未达到最佳状态。

鉴于此，RuoYi-Geek生态应运而生。它旨在为广大开发者提供一个既保留原版本核心特性，又整合社区版优点的全新解决方案。在RuoYi-Geek中，我们深入调研了企业开发中常用的RuoYi扩展，并直接在框架中集成，确保开发者能够快速上手，高效开发。同时，我们采用了最新的SpringBoot3+Vue3技术栈，彻底移除了为了兼容Java1.8而保留的老旧方法。更为重要的是，我们为TypeScript开发环境加入了常用的tsconfig.json配置，使得开发者在VSCode等编辑器中能够获得更为舒适、便捷的语法提示体验。

除此之外，我们还会为这个框架和它的小伙伴们注入更多超实用的工具，无论是日常开发还是企业级项目，都能轻松应对！想象一下，某个瞬间你可能会因为我们的一个小工具而效率爆表，简直像是开了外挂一样！我们真心希望这个框架能成为你的得力助手，让你的工作不再那么“苦逼”，变得更加有趣、高效、舒适。XD==😄  \\(@^0^@)/

RuoYi-Geek不仅仅是一个简单的升级版本，更是对于RuoYi生态的一次全面优化与整合。我们相信，通过RuoYi-Geek，开发者将能够更为高效、愉悦地开发出优秀的企业级应用。

## 框架介绍

### RuoYi-Geek-SpringBoot3

本框架为基于SpringBoot3+Vue3前后端分离的Java快速开发框架。

本框架为我们生态后端的Springboot 3版本。配合若依极客生态的Vue3版本，该版本在支付模块和第三方登录模块方面进行了基础设计工作，并针对代码生成器进行了显著增强，现在支持字段级别的关联表操作。此外，新增了在线接口开发模块，该模块允许用户通过在线方式使用mybatis来修改接口。其他功能模块也正在持续更新和完善中。

### RuoYi-Geek-Vue3

本框架为基于SpringBoot3+Vue3前后端分离的Java快速开发框架。

本框架为我们生态前端的Vue3版本。目前新增了threejs支持，并配合若依极客生态框架后端的Springboot 3版本，该版本在支付模块和第三方登录模块方面进行了基础设计工作，并针对代码生成器进行了显著增强，现在支持字段级别的关联表操作。此外，我们新增了在线接口开发模块，该模块允许用户通过在线方式使用mybatis来修改接口。其他功能模块也正在持续更新和完善中。

### RuoYi-Geek-App

若依极客生态App版本是 RuoYi-App 框架的基础上进行了二次开发，采用了 Uniapp 结合 Vue3 的技术栈。它同时支持 JavaScript 和 TypeScript 开发，并且兼容 CSS、SCSS 以及 Less 样式语言。为了优化性能，我们已经对代码进行了初步的分包处理。此外，我们集成了 uview-plus、uchart和相关的模板供大家参考和使用。

### RuoYi-Geek-Electron

RuoYi-Geek-Electron旨在为RuoYi-Geek-SpringBoot3与RuoYi-Geek-Vue3搭建一个舒适的窗口应用环境，并用装饰器简化开发。目前正在完善中。。。。。。。
