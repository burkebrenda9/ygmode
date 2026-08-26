最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计架构图绘图工具选型对比
简介：TCP 长连接参数优化 TIME_WAIT，调整 TCP 内核参数，优化长连接，减少大量 TIME_WAIT 连接占用资源。
 | 原文链接：http://book.n70dwu.asia/blog/747143.Doc

原标题：golang consul 服务发现简单示例
简介：包管理器依赖缓存清理，清理本地依赖缓存，解决缓存旧包引发问题，拉取最新版本依赖包。
 | 原文链接：http://book.n70dwu.asia/blog/003293.Doc

原标题：API 大版本不兼容平滑迁移
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://book.n70dwu.asia/blog/401231.Doc

原标题：安全复盘：Nginx配置不当带来的安全风险
简介：服务熔断防止故障级联传播，实现服务熔断逻辑，下游故障时快速失败，阻止故障向上游链式扩散。
 | 原文链接：http://book.n70dwu.asia/blog/290269.Doc

原标题：golang 项目 docker compose 本地调试
简介：布隆过滤器误判问题修正，调整布隆过滤器参数，降低误判概率，保证业务去重逻辑准确。
 | 原文链接：http://book.n70dwu.asia/blog/828627.Doc

原标题：golang 系统设计第三方接口调用封装思路
简介：定时任务重复执行分布式锁，使用分布式锁控制定时任务，保证集群环境定时任务只会执行一次。
 | 原文链接：http://book.n70dwu.asia/blog/070408.Doc

原标题：golang minio 存储桶权限管控配置
简介：golang http cookie jar 会话处理，客户端 cookie jar 自动管理 cookie，处理登录态会话。
 | 原文链接：http://book.n70dwu.asia/blog/212758.Doc

原标题：方案对比：同步调用vs异步消息业务选型
简介：golang cgo 性能开销避坑指南，cgo 调用开销，减少频繁 cgo 调用，规避 cgo 带来内存泄漏风险。
 | 原文链接：http://book.n70dwu.asia/blog/029353.Doc

原标题：架构笔记：数据脱敏架构接入层与存储层方案
简介：golang rate‑limiter 限流组件，封装通用 Go 限流组件，支持多算法，业务接口直接复用调用。
 | 原文链接：http://book.n70dwu.asia/blog/998914.Doc

原标题：golang 系统设计 hot‑reload 热重载 go 开发工具
简介：golang 消息队列 kafka 消费开发，Go 开发 Kafka 消费程序，消费消息执行业务，理解 Kafka 消费逻辑。
 | 原文链接：http://book.n70dwu.asia/blog/265252.Doc

原标题：安全复盘：日志打印敏感信息泄露治理
简介：golang 定时任务 cron 使用指南，Go 使用 Cron 库实现定时任务，配置 corn 表达式调度业务任务。
 | 原文链接：http://book.n70dwu.asia/blog/282585.Doc

原标题：golang mysql json 字段查询使用
简介：golang go time 时区数据库内置，go 内置时区数据库，不用系统时区文件，容器时区不依赖系统。
 | 原文链接：http://book.n70dwu.asia/blog/772976.Doc

原标题：express 请求参数校验处理
简介：时间精度统一业务判断修复，统一业务使用时间戳精度，毫秒秒区分清楚，修复时间判断逻辑错误。
 | 原文链接：http://book.n70dwu.asia/blog/830399.Doc

原标题：实战项目：编写Dockerfile多阶段构建减小镜像体积
简介：golang go 程序 CPU 占用高定位步骤，pprof 定位热点函数，分析 CPU 高占用，优化耗时代码逻辑。
 | 原文链接：http://book.n70dwu.asia/blog/023342.Doc

原标题：架构复盘：数据库主从架构设计与延迟应对方案
简介：nestjs 框架模块化项目搭建，从零搭建 NestJS 项目，模块化拆分业务，搭建规范后端项目骨架。
 | 原文链接：http://book.n70dwu.asia/blog/280585.Doc

原标题：数据库死锁成因规避方案
简介：golang html 模板防 xss 自动转义，理解 go html/template 自动转义，防止 XSS 攻击，处理不需要转义场景。
 | 原文链接：http://book.n70dwu.asia/blog/684706.Doc

原标题：部署复盘：静态资源版本哈希缓存策略
简介：golang 负载均衡轮询加权轮询实现，手写负载均衡算法，轮询、加权轮询分发请求到后端节点。
 | 原文链接：http://book.n70dwu.asia/blog/631711.Doc

原标题：golang 系统设计第三方接口 mock 单元测试
简介：golang time 时间格式化避坑，Go 时间格式化参考时间牢记，处理时间解析格式化，解决时间输出错乱。
 | 原文链接：http://book.n70dwu.asia/blog/061944.Doc

原标题：Troubleshooting：数据库主从延迟带来查询数据不一致
简介：monorepo 项目多包管理最佳实践，monorepo 仓库管理多子包，统一版本管理，处理包之间互相依赖。
 | 原文链接：http://book.n70dwu.asia/blog/684172.Doc

原标题：golang 系统设计数据库慢请求排查流程
简介：程序预加载加快服务启动速度，把高频使用资源提前预加载，减少请求阶段初始化，加快服务启动。
 | 原文链接：http://book.n70dwu.asia/blog/519149.Doc

原标题：golang 雪花 id 重复问题排查
简介：golang 大文件读取内存优化，Go 流式读取大文件，分块处理，避免大文件一次性加载全部到内存。
 | 原文链接：http://book.n70dwu.asia/blog/633326.Doc

原标题：新手向：开源项目本地构建失败通用排查步骤
简介：静态资源 404 路径打包修复，修复打包后静态资源访问 404，调整资源输出路径，保证资源正常加载。
 | 原文链接：http://book.n70dwu.asia/blog/059853.Doc

原标题：零基础理解数据库事务基础ACID概念
简介：golang io.Copy 流式拷贝数据，io.Copy 拷贝 reader 到 writer，不用加载全部数据到内存。
 | 原文链接：http://book.n70dwu.asia/blog/139898.Doc

原标题：安全复盘：消息队列未授权访问安全加固
简介：eslint prettier 代码规范落地，配置 eslint 与 prettier，做代码检查格式化，统一前端团队代码风格。
 | 原文链接：http://book.n70dwu.asia/blog/398330.Doc

原标题：golang 大文件 http 下载服务
简介：日志驱动异常日志不输出修复，排查日志驱动配置，修复日志写入配置，恢复程序正常日志输出。
 | 原文链接：http://book.n70dwu.asia/blog/163192.Doc

原标题：golang es 更新文档注意版本冲突
简介：静态站点自动部署发布方案，配置流水线，代码更新自动构建静态站点并且部署上线，简化发布。
 | 原文链接：http://book.n70dwu.asia/blog/229992.Doc

原标题：性能复盘：系统上下文切换过高性能下降调优
简介：golang go http 服务器优雅关闭完整代码，http.Server Shutdown，等待现有请求处理完成关闭服务。
 | 原文链接：http://book.n70dwu.asia/blog/111553.Doc

原标题：golang 系统设计分布式事务业务选型决策思路
简介：JWT 工具封装令牌刷新过期，封装 JWT 工具类，实现令牌生成、校验、过期刷新整套令牌管理逻辑。
 | 原文链接：http://book.n70dwu.asia/blog/412552.Doc

原标题：本地运行正常线上报错排查
简介：golang hertz 性能优化参数调优，hertz 连接池、缓冲区参数调优，最大化接口吞吐性能。
 | 原文链接：http://book.n70dwu.asia/blog/944306.Doc

原标题：排错：CI缓存策略错误，每次全量重新构建
简介：golang etcd key 监听变更 watch 机制，watch 监听 etcd 键变化，配置变更实时感知，实现配置热更新。
 | 原文链接：http://book.n70dwu.asia/blog/159652.Doc

原标题：从零搭建简单的健康检查接口示例
简介：golang goroutine 泄露常见场景汇总，channel 阻塞、context 忘记取消，导致协程无法退出发生泄露。
 | 原文链接：http://book.n70dwu.asia/blog/935321.Doc

原标题：golang 时间时区处理避坑指南
简介：golang 系统信号信号量处理，Go 处理系统各类信号，SIGINT、SIGTERM，实现程序可控退出。
 | 原文链接：http://book.n70dwu.asia/blog/937679.Doc

原标题：部署复盘：GitHubActions完整自动化配置
简介：批量异步处理系统业务落地，构建批量异步处理系统，把耗时业务异步化，提升接口响应速度。
 | 原文链接：http://book.n70dwu.asia/blog/444205.Doc

原标题：nodejs 定时任务生产环境避坑
简介：程序性能指标 CPU 内存监控，讲解基础性能指标含义，简单实现监控采集，初步定位程序运行性能瓶颈。
 | 原文链接：http://book.n70dwu.asia/blog/444992.Doc

原标题：golang 系统设计本地缓存过期淘汰策略选型
简介：golang 微服务网关简易实现，http 反向代理、路由匹配、鉴权限流，理解网关核心原理。
 | 原文链接：http://book.n70dwu.asia/blog/539483.Doc

原标题：Performance：大事务拆分，减少锁持有时间
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://book.n70dwu.asia/blog/585330.Doc

原标题：前端骨架屏提升页面体验
简介：分布式 ID 生成器高并发实现，实现高性能分布式 ID 生成器，适配高并发业务，生成全局唯一 ID。
 | 原文链接：http://book.n70dwu.asia/blog/880184.Doc

原标题：时间精度统一业务判断修复
简介：网关集成鉴权限流日志一体化，在网关层整合鉴权、限流、请求日志，统一对入口请求做管控处理。
 | 原文链接：http://book.n70dwu.asia/blog/639071.Doc

原标题：HelloGitHubPages：部署你的第一个静态博客
简介：数据库分表存储大表优化方案，对超大数据表做分表，拆分数据，降低单表数据量提升查询性能。
 | 原文链接：http://book.n70dwu.asia/blog/053372.Doc

原标题：Troubleshooting：数据库索引失效，查询性能暴跌
简介：百万数据 Excel 导出内存优化，优化大 Excel 导出逻辑，流式输出，避免一次性加载全部数据造成 OOM。
 | 原文链接：http://book.n70dwu.asia/blog/720495.Doc


二、踩坑排错｜Troubleshooting
原标题：CPU 亲和性配置负载均衡调度
简介：请求工具封装统一异常处理，对网络请求做二次封装，统一捕获各类请求异常，标准化接口返回格式。
 | 原文链接：http://book.n70dwu.asia/blog/495604.Doc

原标题：golang dockerfile 多阶段构建详解
简介：golang go 程序版本号内置编译注入，编译时注入 git commit 版本号，程序运行输出版本便于排查。
 | 原文链接：http://book.n70dwu.asia/blog/115831.Doc

原标题：快速上手搭建简易内网测试服务
简介：异步编程 Promise 执行流程解析，拆解异步执行顺序，理解回调与 Promise 差异，理清异步场景下代码执行逻辑。
 | 原文链接：http://book.n70dwu.asia/blog/193443.Doc

原标题：golang 系统设计配置本地缓存降级策略方案
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://book.n70dwu.asia/blog/660784.Doc

原标题：golang websocket 消息广播实现
简介：golang 互斥锁读写锁并发安全，互斥锁读写锁实操，保护共享变量，解决多协程并发读写数据竞争。
 | 原文链接：http://book.n70dwu.asia/blog/481405.Doc

原标题：开发复盘：搭建文件上传服务支持分片断点续传
简介：golang redis hyperloglog 基数统计，hyperloglog 统计 UV 基数，海量数据去重统计，极低内存开销。
 | 原文链接：http://book.n70dwu.asia/blog/771307.Doc

原标题：golang defer panic 异常处理
简介：golang gorm 预加载关联查询优化，GORM 预加载关联数据，避免 N+1 查询问题，提升数据库查询性能。
 | 原文链接：http://book.n70dwu.asia/blog/410685.Doc

原标题：golang 系统设计告警风暴抑制方案实现
简介：golang netlink 系统信息获取，netlink 获取系统网络信息，网卡地址，内核网络状态读取。
 | 原文链接：http://book.n70dwu.asia/blog/377393.Doc

原标题：复盘总结：分布式系统常见坑点汇总清单
简介：golang atomic 原子操作整数，atomic 加减比较交换，无锁更新整型变量，简单计数器场景。
 | 原文链接：http://book.n70dwu.asia/blog/147608.Doc

原标题：golang redis 地理位置 geo 使用
简介：golang go 服务蓝绿发布实践思路，蓝绿两套实例，流量一键切换，回滚快速降低发布风险。
 | 原文链接：http://book.n70dwu.asia/blog/234106.Doc

原标题：代码格式化工具团队统一风格
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：http://book.n70dwu.asia/blog/854230.Doc

原标题：golang 系统设计高可用服务架构梳理
简介：前后端会话登录状态持久化，实现登录状态持久存储，重启服务登录状态不丢失，保障会话稳定性。
 | 原文链接：http://book.n70dwu.asia/blog/575518.Doc

原标题：线上异常：缓存雪崩带来数据库压力瞬间飙升
简介：golang go mod exclude 排除依赖版本，exclude 排除有问题依赖版本，规避有 bug 的第三方包。
 | 原文链接：http://book.n70dwu.asia/blog/304668.Doc

原标题：golang dockerfile 多阶段构建详解
简介：全量回归测试提升代码质量，搭建全量回归测试集，版本发布执行回归测试，避免迭代引入旧 bug。
 | 原文链接：http://book.n70dwu.asia/blog/015705.Doc

原标题：golang 系统设计单元测试编写原则最佳实践
简介：golang redis stream 消息队列实战，redis stream 实现可靠消息队列，消费组、ack 确认，消息不丢失。
 | 原文链接：http://book.n70dwu.asia/blog/297720.Doc

原标题：golang 系统设计接口向前兼容改造实操
简介：golang 分布式锁防死锁实现要点，锁超时、续期、锁持有者校验，避免锁死锁，保障分布式锁可靠性。
 | 原文链接：http://book.n70dwu.asia/blog/342804.Doc

原标题：线上故障：Redis内存淘汰策略错误数据丢失
简介：vite 项目配置与构建提速技巧，讲解 vite 配置优化手段，提升开发热更新速度与生产构建打包效率。
 | 原文链接：http://book.n70dwu.asia/blog/589674.Doc

原标题：开发记录：敏感数据加密存储解密业务实践
简介：golang csv 百万级数据导入数据库，流式读取 csv 分批写入数据库，避免一次性加载全部数据。
 | 原文链接：http://book.n70dwu.asia/blog/114772.Doc

原标题：文件读写与异常捕获代码示例
简介：Docker 网络模式容器互通设置，选择合适 Docker 网络模式，实现容器之间网络互相访问通信。
 | 原文链接：http://book.n70dwu.asia/blog/771157.Doc

原标题：﻿【GettingStarted】从零搭建本地开发环境完整指南
简介：golang socket 文件描述符继承重启，父进程传递 listener fd 给子进程，实现 go 程序零停机热重启。
 | 原文链接：http://book.n70dwu.asia/blog/211600.Doc

原标题：Hands‑on：简易事件驱动架构原型开发
简介：内网测试服务搭建团队调试，配置本地服务内网可访问，团队成员能够访问调试，方便前后端联调与内部演示。
 | 原文链接：http://book.n70dwu.asia/blog/787170.Doc

原标题：Hands‑on：简易代理服务器开发实践
简介：项目目录结构规范化最佳实践，梳理源码、配置、静态资源目录划分，规范项目布局，提升代码可读性和可维护性。
 | 原文链接：http://book.n70dwu.asia/blog/920666.Doc

原标题：坑点：环境配置写死代码，上线忘记修改
简介：GitHub 项目提交推送完整流程讲解，从仓库初始化到提交推送远程仓库，梳理全流程细节，避开新手高频错误。
 | 原文链接：http://book.n70dwu.asia/blog/598625.Doc

原标题：分布式任务调度集群原型开发
简介：golang sync.Cond 条件变量使用，Cond 条件变量协程等待唤醒，复杂并发同步场景。
 | 原文链接：http://book.n70dwu.asia/blog/096711.Doc

原标题：开发记录：JWT过期刷新滑动过期实现实践
简介：时间同步修复令牌提前过期，服务器时间不同步导致 JWT 令牌提前过期，同步系统时间解决异常。
 | 原文链接：http://book.n70dwu.asia/blog/070632.Doc

原标题：业务错误码体系设计方案
简介：golang 异步任务队列 worker 池开发，任务入数据库或 redis，worker 池消费执行，异步处理耗时业务。
 | 原文链接：http://book.n70dwu.asia/blog/495651.Doc

原标题：golang 系统设计压测指标确定与分析
简介：golang 限制 multipart 内存大小，设置 MaxMemory，大文件写入磁盘临时文件防止内存暴涨。
 | 原文链接：http://book.n70dwu.asia/blog/064549.Doc

原标题：效率笔记：Makefile项目构建脚本编写实践
简介：golang smtp 邮件发送完整示例，调用 smtp 服务发送文本与 html 格式邮件，实现邮件通知能力。
 | 原文链接：http://book.n70dwu.asia/blog/397612.Doc

原标题：调优方案：服务实例扩容，水平扩展性能
简介：接口请求重试容错机制实现，封装请求重试逻辑，遇到临时网络故障自动重试，提升第三方调用稳定性。
 | 原文链接：http://book.n70dwu.asia/blog/903245.Doc

原标题：Performance：缓存策略优化，降低数据库压力
简介：Mock 接口服务快速搭建实操，搭建模拟后端接口，自定义返回数据、延迟响应，前端开发阶段无需依赖真实后端服务。
 | 原文链接：http://book.n70dwu.asia/blog/892113.Doc

原标题：Shell 运维脚本服务器效率提升
简介：css 变量主题切换方案实现，使用 CSS 变量实现网页主题切换，多套主题样式快速切换无需大量 CSS。
 | 原文链接：http://book.n70dwu.asia/blog/965884.Doc

原标题：新手教程：本地环境变量配置全流程
简介：浏览器内存泄漏排查前端页面，梳理前端页面内存泄漏场景，讲解排查手段，修复页面内存持续上涨。
 | 原文链接：http://book.n70dwu.asia/blog/972209.Doc

原标题：Troubleshooting：数据库索引失效，查询性能暴跌
简介：golang trace 可视化分析协程阻塞，使用 trace 网页 UI，定位协程阻塞、系统调用阻塞、锁等待。
 | 原文链接：http://book.n70dwu.asia/blog/272524.Doc

原标题：golang 系统设计故障应急响应完整流程梳理
简介：golang time 时间比较 Before After Equal，时间比较不要直接减，使用内置方法判断时间先后。
 | 原文链接：http://book.n70dwu.asia/blog/129560.Doc

原标题：服务熔断防止故障级联传播
简介：golang http 文件下载断点续传服务，服务端实现断点续传，支持大文件分段下载，提升大文件下载稳定性。
 | 原文链接：http://book.n70dwu.asia/blog/009659.Doc

原标题：golang 系统设计消息堆积排查扩容完整步骤
简介：图片上传预览格式大小处理，实现图片上传接口，校验文件格式、大小，完成上传后预览处理。
 | 原文链接：http://book.n70dwu.asia/blog/455160.Doc

原标题：Nginx 透传真实客户端 IP 配置
简介：golang 模板函数自定义拓展，自定义 template 模板函数，在 html 模板调用自定义逻辑处理数据。
 | 原文链接：http://book.n70dwu.asia/blog/934160.Doc

原标题：设计思考：分布式系统时钟同步带来的架构问题
简介：Dockerfile 编写容器打包实战，讲解 Dockerfile 指令含义，编写镜像构建脚本，将本地项目打包成可分发容器镜像。
 | 原文链接：http://book.n70dwu.asia/blog/642785.Doc

原标题：golang 系统设计日志系统架构思路
简介：项目脚手架模板生成工具，搭建项目模板脚手架，一键生成标准化项目骨架，减少重复初始化工作。
 | 原文链接：http://book.n70dwu.asia/blog/252808.Doc

原标题：Hands‑on：本地模拟分布式锁失效场景测试
简介：golang gitlab ci go 项目流水线编写，gitlab ci 流水线执行单元测试、静态检查、构建推送镜像。
 | 原文链接：http://book.n70dwu.asia/blog/644232.Doc

三、实战开发｜Practice
原标题：开发复盘：异步消息解耦业务流程落地实践
简介：用户敏感数据脱敏代码实现，编写数据脱敏工具，对手机号、身份证做脱敏处理，防止敏感信息直接泄露。
 | 原文链接：http://book.n70dwu.asia/blog/941515.Doc

原标题：部署实践：容器优雅停机配置处理信号
简介：golang elasticsearch 客户端 golang 实操，es 客户端文档增删改查，条件搜索聚合统计对接搜索引擎。
 | 原文链接：http://book.n70dwu.asia/blog/037020.Doc

原标题：开发复盘：超时参数统一治理线上服务实践
简介：golang go mod graph 查看依赖关系，go mod graph 打印依赖树，定位间接依赖来源，解决版本冲突。
 | 原文链接：http://book.n70dwu.asia/blog/932242.Doc

原标题：Debug：时间回拨，定时任务调度逻辑错乱
简介：手写简易 MQ 理解消息存储消费，手写极简消息队列 Demo，理解消息存储、投递、消费完整流程。
 | 原文链接：http://book.n70dwu.asia/blog/884100.Doc

原标题：零基础理解版本控制核心概念与工作流
简介：nodejs jwt 登录鉴权完整示例，Node 实现 JWT 登录鉴权，登录签发令牌，接口校验令牌身份。
 | 原文链接：http://book.n70dwu.asia/blog/702012.Doc

原标题：Troubleshoot：跨库关联查询，性能急剧恶化
简介：百万数据 Excel 导出内存优化，优化大 Excel 导出逻辑，流式输出，避免一次性加载全部数据造成 OOM。
 | 原文链接：http://book.n70dwu.asia/blog/204405.Doc

原标题：新手向：Mac/Windows开发环境差异踩坑
简介：服务健康检查告警监控体系，搭建健康检查加告警体系，服务异常及时推送告警通知运维人员。
 | 原文链接：http://book.n70dwu.asia/blog/539634.Doc

原标题：方案对比：RPC、HTTP、gRPC场景选型分析
简介：提交第一个开源 PR 完整流程，Fork 项目、修改代码、提交 Pull Request，讲解 PR 规范，提升合并通过率。
 | 原文链接：http://book.n70dwu.asia/blog/409961.Doc

原标题：Git 代码冲突正确处理方式
简介：golang 分布式事务 seata go 客户端，seata‑go 实现分布式事务，保证跨库业务数据最终一致性。
 | 原文链接：http://book.n70dwu.asia/blog/695367.Doc

原标题：golang 系统设计大流量削峰处理方案
简介：golang 分布式 ID 雪花算法实现，Go 实现雪花算法，生成分布式全局唯一 ID，适配分库分表主键。
 | 原文链接：http://book.n70dwu.asia/blog/070660.Doc

原标题：golang 系统设计内部服务契约测试简单思路
简介：golang 协程泄露问题排查方法，识别 Go 协程泄露现象，分析泄露场景，给出排查定位协程泄露手段。
 | 原文链接：http://book.n70dwu.asia/blog/356963.Doc

原标题：Spring 事务传播机制配置生效
简介：golang go http 静态文件禁止目录遍历，http.FileServer 防止../ 路径穿越，了解底层安全实现。
 | 原文链接：http://book.n70dwu.asia/blog/291683.Doc

原标题：golang redis 集群 hash 槽讲解
简介：异步编程 Promise 执行流程解析，拆解异步执行顺序，理解回调与 Promise 差异，理清异步场景下代码执行逻辑。
 | 原文链接：http://book.n70dwu.asia/blog/109001.Doc

原标题：golang 系统设计数据库死锁分析规避
简介：nodejs 消息队列消费服务开发，Node 开发消息队列消费端，监听队列消息执行业务逻辑，异步解耦业务。
 | 原文链接：http://book.n70dwu.asia/blog/160052.Doc

原标题：golang 系统设计数据库扩容几种方式
简介：golang gin 框架接口开发实战，Gin 框架搭建 HTTP 服务，开发增删改查接口，快速完成后端接口开发。
 | 原文链接：http://book.n70dwu.asia/blog/490894.Doc

原标题：Hands‑on：实现服务健康检查与自动报警demo
简介：单元测试用例编写入门实操，讲解测试用例设计思路，演示基础单元测试代码，提升代码健壮性，提前发现逻辑 bug。
 | 原文链接：http://book.n70dwu.asia/blog/323522.Doc

原标题：从零搭建简单的健康检查接口示例
简介：前端 pdf 预览渲染方案对比，对比前端 PDF 预览库，分析性能、兼容性，给出业务选型参考。
 | 原文链接：http://book.n70dwu.asia/blog/758422.Doc

原标题：实战项目：搭建私有Docker镜像仓库本地实践
简介：前端权限路由动态生成实现，根据后端返回权限，动态生成前端路由菜单，实现页面权限控制。
 | 原文链接：http://book.n70dwu.asia/blog/633674.Doc

原标题：开源实践：Fork上游项目，持续同步更新代码
简介：golang trace 可视化分析协程阻塞，使用 trace 网页 UI，定位协程阻塞、系统调用阻塞、锁等待。
 | 原文链接：http://book.n70dwu.asia/blog/632115.Doc

原标题：golang mongodb 事务多文档使用
简介：golang 故障演练服务模拟超时报错，程序模拟接口超时、报错，做混沌测试验证熔断降级有效性。
 | 原文链接：http://book.n70dwu.asia/blog/703257.Doc

原标题：golang 系统设计布隆过滤器拦截不存在 key
简介：golang rate‑limiter 限流组件，封装通用 Go 限流组件，支持多算法，业务接口直接复用调用。
 | 原文链接：http://book.n70dwu.asia/blog/608420.Doc

原标题：避坑：CookieSecure属性造成测试环境登录失败
简介：golang redis zset 实现延时任务队列，zset 存储任务到期时间，轮询到期任务执行，简易延迟队列。
 | 原文链接：http://book.n70dwu.asia/blog/729629.Doc

原标题：golang 系统设计数据库查询优化完整流程
简介：时间精度统一业务判断修复，统一业务使用时间戳精度，毫秒秒区分清楚，修复时间判断逻辑错误。
 | 原文链接：http://book.n70dwu.asia/blog/043763.Doc

原标题：golang 系统设计数据库扩容几种方式
简介：golang 链路追踪简易实现方案，简易链路追踪实现，传递 traceId，记录调用链路，方便排查慢调用。
 | 原文链接：http://book.n70dwu.asia/blog/542255.Doc

原标题：开发记录：批量接口请求并发控制实践
简介：golang go 程序容器资源 requests limits，设置容器 cpu 内存配额，防止实例抢占集群资源，稳定调度。
 | 原文链接：http://book.n70dwu.asia/blog/767966.Doc

原标题：golang 系统设计依赖版本升级风险评估
简介：CLI 批量处理工具文件操作开发，开发命令行批量工具，实现批量文件处理，提升重复文件处理效率。
 | 原文链接：http://book.n70dwu.asia/blog/712412.Doc

原标题：golang docker compose 本地开发最佳实践
简介：内存溢出问题现象识别排查，识别内存溢出现象，梳理排查方向，定位内存持续上涨引发服务崩溃问题。
 | 原文链接：http://book.n70dwu.asia/blog/916007.Doc

原标题：内网 DNS 不稳定随机报错排查
简介：golang makefile 多平台编译脚本，makefile 一键交叉编译多平台二进制，打包镜像，执行测试。
 | 原文链接：http://book.n70dwu.asia/blog/708591.Doc

原标题：golang 系统设计线上 ddl 变更安全执行思路
简介：后端大文件分片上传接口开发，开发后端分片上传接口，接收分片，合并分片完成大文件存储。
 | 原文链接：http://book.n70dwu.asia/blog/917152.Doc

原标题：golang docker 容器资源限制设置
简介：golang proto 默认值坑点梳理，梳理 Protobuf 默认值坑，零值字段区分未赋值，避免业务逻辑错误。
 | 原文链接：http://book.n70dwu.asia/blog/293692.Doc

原标题：Spring 事务传播机制配置生效
简介：golang net.Conn 包装自定义连接，包装 net.Conn，统计读写字节，日志打印，超时控制。
 | 原文链接：http://book.n70dwu.asia/blog/425501.Doc

原标题：golang websocket 服务端开发
简介：golang go‑fuzz 模糊测试开发，go fuzz 模糊测试，自动构造异常输入，发现代码隐藏 bug。
 | 原文链接：http://book.n70dwu.asia/blog/177717.Doc

原标题：Hands‑on：简易请求转发代理中间件实现
简介：分布式 ID 全局唯一生成方案，讲解分布式 ID 生成思路，实现全局唯一 ID，满足分布式系统主键生成需求。
 | 原文链接：http://book.n70dwu.asia/blog/776221.Doc

原标题：golang 系统设计读写穿透更新缓存几种方案
简介：跨库查询性能优化处理，减少跨库关联查询，做数据冗余或者中间表，规避跨库查询性能低下。
 | 原文链接：http://book.n70dwu.asia/blog/736282.Doc

原标题：Shell 运维脚本服务器效率提升
简介：golang go 变量逃逸场景汇总，切片、指针、返回局部变量引发逃逸，变量分配到堆影响 GC。
 | 原文链接：http://book.n70dwu.asia/blog/383612.Doc

原标题：WebSocket 断线重连稳定优化
简介：网关集成鉴权限流日志一体化，在网关层整合鉴权、限流、请求日志，统一对入口请求做管控处理。
 | 原文链接：http://book.n70dwu.asia/blog/028305.Doc

原标题：golang 系统设计本地缓存过期淘汰策略选型
简介：包管理器依赖缓存清理，清理本地依赖缓存，解决缓存旧包引发问题，拉取最新版本依赖包。
 | 原文链接：http://book.n70dwu.asia/blog/008141.Doc

原标题：效率笔记：GitWorkflow团队协作规范模板
简介：nodejs 全局异常捕获进程防护，捕获未捕获异常与 Promise 拒绝，尽量保护进程不因为异常直接退出。
 | 原文链接：http://book.n70dwu.asia/blog/385258.Doc

原标题：排错：静态资源404，打包路径配置错误
简介：新手参与开源社区贡献指南，介绍开源社区基础规则，讲解阅读 issue、提交 PR 流程，指导开发者参与开源贡献。
 | 原文链接：http://book.n70dwu.asia/blog/341844.Doc

原标题：golang 系统设计配置多环境隔离方案落地
简介：Nginx 请求头大小上限调整，修改 Nginx 配置，调大请求头允许最大大小，避免大 Header 请求被拒绝。
 | 原文链接：http://book.n70dwu.asia/blog/876501.Doc

四、架构设计｜Architecture
原标题：架构笔记：任务调度系统架构设计与可靠性
简介：golang bytes.Buffer 字节缓冲区使用，bytes.Buffer 字节内存缓冲区，拼接字节，避免频繁内存分配。
 | 原文链接：http://book.n70dwu.asia/blog/811463.Doc

原标题：安全笔记：JWT安全风险，签名泄露过期控制
简介：golang 程序崩溃 core dump 生成调试，开启 core dump，程序崩溃生成转储文件，事后分析崩溃原因。
 | 原文链接：http://book.n70dwu.asia/blog/622348.Doc

原标题：实践：消息队列死信处理业务落地实践
简介：golang http client 连接池调优，调优 Go HTTP Client 连接池参数，复用 TCP 连接，减少连接创建开销。
 | 原文链接：http://book.n70dwu.asia/blog/145815.Doc

原标题：golang 系统设计代码仓库权限管理方案
简介：golang gin 静态资源访问配置，Gin 配置静态资源目录，直接对外提供静态文件访问服务。
 | 原文链接：http://book.n70dwu.asia/blog/452287.Doc

原标题：Hands‑on：手写简易ORM框架理解底层原理
简介：日志切割配置防止日志丢失，配置日志切割轮转策略，日志按大小时间切割，防止日志文件丢失。
 | 原文链接：http://book.n70dwu.asia/blog/559368.Doc

原标题：golang 系统设计日志级别业务使用原则梳理
简介：golang go 爬虫 html 解析 goquery，goquery 解析 html 文档，css 选择器提取网页内容，实现网页数据抓取。
 | 原文链接：http://book.n70dwu.asia/blog/328117.Doc

原标题：golang 系统设计网关请求日志 traceId 透传实现
简介：数据库事务 ACID 原理讲解，拆解事务四大特性，理解事务隔离、原子性，明白事务如何保障数据安全。
 | 原文链接：http://book.n70dwu.asia/blog/033038.Doc

原标题：实践：API接口文档自动导出离线文档实践
简介：WebSocket 双向通信 demo 开发，搭建简易 WebSocket 服务，实现客户端服务端双向消息推送，理解实时通信原理。
 | 原文链接：http://book.n70dwu.asia/blog/763870.Doc

原标题：项目实践：灰度发布简易方案落地实践
简介：golang os 主机名内核版本读取，os 读取主机名，内核信息，操作系统版本，获取运行环境信息。
 | 原文链接：http://book.n70dwu.asia/blog/427483.Doc

原标题：golang k8s 节点污点容忍度配置
简介：开源项目构建失败排查步骤，梳理构建报错排查流程，从依赖、网络、权限、脚本多角度定位项目构建失败原因。
 | 原文链接：http://book.n70dwu.asia/blog/996525.Doc

原标题：golang redis 批量 pipeline 实践
简介：nestjs 框架模块化项目搭建，从零搭建 NestJS 项目，模块化拆分业务，搭建规范后端项目骨架。
 | 原文链接：http://book.n70dwu.asia/blog/150784.Doc

原标题：Issue：Docker网络模式选择错误容器互通失败
简介：DNS 解析异常第三方调用故障，排查 DNS 解析故障，修复域名解析，恢复第三方接口网络调用。
 | 原文链接：http://book.n70dwu.asia/blog/477834.Doc

原标题：golang mysql 慢查询日志开启分析
简介：golang 读写分离 gorm 实现主从切换，gorm 配置主库写入从库查询，读写分离分担数据库查询压力。
 | 原文链接：http://book.n70dwu.asia/blog/022084.Doc

原标题：排坑：Git提交历史混乱，如何清理错误提交
简介：OOMKilled 容器被杀完整排查，排查容器被 OOM 终止完整流程，区分程序内存泄露和容器内存限制过小。
 | 原文链接：http://book.n70dwu.asia/blog/556995.Doc

原标题：golang 系统设计缓存降级开关快速切库实现
简介：golang go 符号表与调试信息取舍，区分生产环境调试符号取舍，平衡镜像体积与故障排查能力。
 | 原文链接：http://book.n70dwu.asia/blog/357892.Doc

原标题：消息消费重试次数限制防爆炸
简介：OOMKilled 容器被杀完整排查，排查容器被 OOM 终止完整流程，区分程序内存泄露和容器内存限制过小。
 | 原文链接：http://book.n70dwu.asia/blog/786926.Doc

原标题：安全笔记：JWT安全风险，签名泄露过期控制
简介：golang k8s informer 机制原理理解，informer 监听 k8s 资源变更，本地缓存，减少 apiserver 压力。
 | 原文链接：http://book.n70dwu.asia/blog/593970.Doc

原标题：golang mysql 批量导入数据实操
简介：golang redis pipeline 批量操作，使用 Redis Pipeline 批量执行多条命令，减少网络往返，提升批量操作性能。
 | 原文链接：http://book.n70dwu.asia/blog/882873.Doc

?
