# mk56
Go容器化微服务系统实战
Go容器化微服务系统实战
[![下载地址](https://img.mukewang.com/szimg/5fc9e83d08971d8705340300.jpg "下载地址")](https://51xueit.vip "下载地址")
[下载地址](https://51xueit.vip "下载地址")
### 第1章 课程介绍与学习指南 

#### 课程的介绍、学习路线与指南，如何更好的学习本课程
1-1 本课的go微服务有什么不同？ (05:34)


### 第2章 Go微服务介绍与容器化入门 

#### 课程从微服务入门开始，本章讲解go-micro的transport通讯层grpc原理。以及grpc数据的传输序列化和反序列化protobuf的原理
2-1 微服务基础介绍 (19:17)

2-2 微服务必备技能Docker 入门介绍 (18:48)

2-3 go-micro基础之 grpc proto (20:29)

2-4 go-micro 组件架构及通讯原理 (12:28)

2-5 go-micro 入门案例验证 (14:41)

2-6 go-micro 入门案例编写 (14:19)

2-7 【讨论题】35岁+是继续干技术还是转管理？


### 第3章 微服务模块开发 

#### 以业务最简单的用户模块为例，串联go module、gorm等知识，理解如何将模块开发并封装为镜像。同时讲解如何配置代理获得何老师一样的项目仓库。
3-1 micro new 和项目目录创建 (11:18)

3-2 go mod 私有化设置 和 gorm 说明 (07:16)

3-3 编写proto并自动生成代码 (11:16)

3-4 domain对数据库和模型进行操作 (19:38)

3-5 编写Handel要暴露的服务 (16:23)

3-6 go-micro开发流程梳理 (08:20)

3-7 dockerfile 打包 user 功能 (11:57)

3-8 章节小结 (02:16)


### 第4章 注册配置中心实现

#### 介绍go-micro中的Consul组件实现注册中心和配置中心的基本原理。完成分类模块基本功能开发，利用Docker快速安装Consul，介绍实际工作中的使用经验，并将其接入项目。
4-1 注册中心的基本介绍 (14:13)

4-2 注册中心的安装 (05:23)

4-3 分类模块目录结构生成 (08:36)

4-4 编写对外暴露的服务 (19:33)

4-5 数据库进行交互 (14:18)

4-6 编写Handler (33:21)

4-7 配置中心/注册中心的使用 (11:49)

4-8 完善Consule配置 (20:13)

4-9 微服务课程小结 (06:22)

4-10 开发起一个计划总是遥遥无期，它总被一些非技术性的原因阻挠


### 第5章 链路追踪观望台

#### 介绍go-micro中的Jaeger组件原理和作用，开发商品模块并打包部署。为项目集成链路追踪功能，完成链路观测台
5-1 jaeger 原理 (17:54)

5-2 商品领域 proto编写 (17:14)

5-3 商品领域 模型编写 (11:52)

5-4 商品领域repository 开发 (13:04)

5-5 商品领域 service开发 (03:02)

5-6 商品领域 handler开发 (16:08)

5-7 商品领域 链路追踪使用 (43:51)

5-8 链路追踪小结 (03:25)


### 第6章 熔断，限流，负载均衡

#### 熔断，限流，负载均衡是微服务保稳三剑客，而电商中的购物车模块需要稳定的服务来保证准确性，本章介绍hystrix-go组件原理和作用，介绍限流问题的代码包 uber/ratelimit的基本使用
6-1 熔断器作用和原理 (13:05)

6-2 限流的作用和原理 (04:22)

6-3 负载均衡作用和原理 (03:33)

6-4 微服务API网关 (06:01)

6-5 server端 proto 文件编写 (15:02)

6-6 service 端 model 开发 (02:18)

6-7 server端 repository 开发 (13:02)

6-8 server端口service开发 (04:10)

6-9 common 独立使用 (04:59)

6-10 server端 handler开发 (13:53)

6-11 server 端 添加限流 (16:56)

6-12 购物车API层 添加熔断 (16:36)

6-13 购物车API层 添加负载均衡 (18:49)

6-14 API 网关及熔断看板使用 (09:34)

6-15 【讨论】我不理解我的上司整天在干什么，但是我觉得他在瞎忙活

6-16 章节总结 (04:50)


### 第7章 性能监控能力完善

#### 微服务Go化，一般都是因为在意性能，所以性能监控非常重要，尤其是订单模块。本章开发订单模块的同时，使用Docker快速完成promethues+grafana安装，并接入项目中，完成性能监控台
7-1 监控系统prometheus基本介绍 (16:58)

7-2 docker-compose 基础介绍 (09:23)

7-3 docker-compose 具体使用的例子 (13:26)

7-4 订单领域 proto 开发 (16:07)

7-5 订单领域 model 开发 (05:52)

7-6 订单领域 repository 开发 (12:52)

7-7 订单领域 service 开发 (03:59)

7-8 微服务handler 代码编写 (15:33)

7-9 订单main.go 添加 prometheus 监控 (23:03)

7-10 监控系统可视化 (20:34)

7-11 监控系统建立章节总结 (04:52)


### 第8章 服务级观测台完成

#### 通过zap 工具进行日志记录，统一收集到日志中心ELK中。再统一配置，将前面的链路追踪、负载均衡、监控日志等全部集成在一起，完成服务级观测台
8-1 日志系统ELK 架构介绍 (07:52)

8-2 Filebeat 工作原理及注意事项 (06:54)

8-3 Logstash 工作原理 (05:05)

8-4 docker-compose 配置安装 ELK (25:03)

8-5 国际支付 PayPal 账户和沙盒环境指南 (08:50)

8-6 日志zap 封装 (09:15)

8-7 支付服务端 Proto 开发 (11:45)

8-8 支付信息 handler 开发 (14:41)

8-9 支付服务端 main.go 文件开发 (22:10)

8-10 FileBeat 下载和使用说明 (04:08)

8-11 支付API proto 开发 (05:01)

8-12 国际支付PayPal handler 退款业务开发（上） (13:37)

8-13 国际支付PayPal handler 退款业务开发（下） (10:02)

8-14 支付PayPal main.go 开发及效果展示（上） (12:12)

8-15 支付PayPal main.go 开发及效果展示（下） (12:52)

8-16 幂等性介绍 (04:12)

8-17 Kibana日志可视化展示 (16:41)

8-18 该如何应对截止日期和从属关系的压

8-19 本章小结 (03:35)


### 第9章 项目部署，完成闭环

#### 至此，项目已可视化，还差部署即可完成闭环。本章重点讲解如何进行快速部署。讲解K8s的整体架构，基础组件及使用。提供阿里云镜像，只用脚本就可以安装。最后帮助大家完成前后端联调，画下完美句号
9-1 k8s 基础入门及架构介绍 (11:52)

9-2 k8s api server 架构及创建应用原理 (08:36)

9-3 k8s 不同种类controller 作用讲解 (05:00)

9-4 k8s 安装-阿里云创建ECS (07:16)

9-5 k8s 安装 服务器基础安装 (13:39)

9-6 k8s 安装初始化Master 节点 (06:54)

9-7 k8s node 节点加入集群 (03:39)

9-8 kompose 介绍和说明 (05:41)

9-9 kubectl 常用命令讲解 (04:25)

9-10 有太多东西没学没有足够的时间心里很焦虑怎么办


[下载地址](https://51xueit.vip "下载地址")
