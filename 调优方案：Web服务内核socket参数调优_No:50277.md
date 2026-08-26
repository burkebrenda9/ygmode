最新前沿技术资讯

一、入门教程｜Getting Started
原标题：调优方案：Web服务内核socket参数调优
简介：RPC 接口字段增减兼容处理，RPC 接口新增删除字段做好向前兼容，老版本服务不会解析报错崩溃。
 | 原文链接：http://wiki.mljc3b.asia/arts/481885.Doc

原标题：golang 系统设计内部服务熔断降级配置思路
简介：静态博客部署 GitHub Pages 教程，将静态博客项目部署至 GitHub Pages，完成线上访问，快速搭建个人技术博客站点。
 | 原文链接：http://wiki.mljc3b.asia/arts/680266.Doc

原标题：开发记录：搭建CI/CD流水线自动构建部署项目
简介：golang go work 多模块本地开发，go work 多模块本地同时开发，本地模块互相引用，无需推送仓库。
 | 原文链接：http://wiki.mljc3b.asia/arts/596175.Doc

原标题：数值类型溢出错乱问题修复
简介：golang time.After 内存泄漏场景，for 循环使用 time.After 会创建大量 timer，造成内存泄漏。
 | 原文链接：http://wiki.mljc3b.asia/arts/206906.Doc

原标题：golang 系统设计代码评审 checklist 清单
简介：golang go‑zero 缓存自动击穿防护，go‑zero 缓存组件自带缓存击穿防护，减少缓存层故障。
 | 原文链接：http://wiki.mljc3b.asia/arts/852745.Doc

原标题：golang docker 部署 es 本地开发
简介：golang 换行符统一处理，文本文件读写统一换行符，规避不同系统换行符带来解析异常。
 | 原文链接：http://wiki.mljc3b.asia/arts/936777.Doc

原标题：用户敏感数据脱敏代码实现
简介：死信队列处理消息阻塞业务，配置死信队列，处理消费失败消息，避免失败消息阻塞整个队列业务。
 | 原文链接：http://wiki.mljc3b.asia/arts/711581.Doc

原标题：golang 系统设计缓存热点 key 问题业务规避
简介：golang 大文件读取内存优化，Go 流式读取大文件，分块处理，避免大文件一次性加载全部到内存。
 | 原文链接：http://wiki.mljc3b.asia/arts/306096.Doc

原标题：开发复盘：消息队列消息顺序性业务落地实践
简介：golang 响应 body 流式返回大数据，http 流式输出数据，边生成边返回，无需在内存组装完整返回结果。
 | 原文链接：http://wiki.mljc3b.asia/arts/789981.Doc

原标题：golang redis 发布订阅简单示例
简介：服务熔断防止故障级联传播，实现服务熔断逻辑，下游故障时快速失败，阻止故障向上游链式扩散。
 | 原文链接：http://wiki.mljc3b.asia/arts/092288.Doc

原标题：golang 系统设计 rest 分页排序过滤参数规范
简介：golang 僵尸进程处理 go 程序，正确等待子进程退出，避免产生僵尸进程，占用系统进程表。
 | 原文链接：http://wiki.mljc3b.asia/arts/074503.Doc

原标题：golang 系统设计内网外网服务隔离方案
简介：golang 工具函数库封装思路，Go 通用工具库封装思路，错误处理、类型转换，业务项目复用工具代码。
 | 原文链接：http://wiki.mljc3b.asia/arts/802022.Doc

原标题：DevOps：容器网络模式选型与坑点总结
简介：golang go 死锁检测工具，静态检查、运行检测，发现 channel 锁导致死锁问题。
 | 原文链接：http://wiki.mljc3b.asia/arts/758322.Doc

原标题：golang 系统设计数据库索引设计方法论
简介：golang 日志按日期切割实现方案，实现日志文件按天切割，自动归档旧日志，防止单个日志文件过大。
 | 原文链接：http://wiki.mljc3b.asia/arts/272082.Doc

原标题：golang 系统设计日志本地打印线上关闭调试信息
简介：golang http client 连接池调优，调优 Go HTTP Client 连接池参数，复用 TCP 连接，减少连接创建开销。
 | 原文链接：http://wiki.mljc3b.asia/arts/960725.Doc

原标题：Debug：消息队列死信队列堆积无人处理业务阻塞
简介：数值 key 浮点匹配异常规避，避免浮点数作为 Redis 等存储的 key，防止精度问题引发 key 匹配失败。
 | 原文链接：http://wiki.mljc3b.asia/arts/126244.Doc

原标题：踩坑记录：数值溢出造成业务ID错乱异常
简介：多线程线程安全脏数据规避，梳理多线程共享变量，做好同步控制，避免并发修改产生脏数据。
 | 原文链接：http://wiki.mljc3b.asia/arts/488293.Doc

原标题：方案设计：批量大数据导出系统架构拆解
简介：golang gin 路由动态注册实现方案，根据配置动态注册接口路由，无需硬编码路由，适配动态业务模块。
 | 原文链接：http://wiki.mljc3b.asia/arts/614471.Doc

原标题：golang 系统设计 mq 消息丢失完整防护
简介：golang go yaml 解析自定义类型，yaml 自定义序列化，时间、特殊类型自定义解析逻辑。
 | 原文链接：http://wiki.mljc3b.asia/arts/126444.Doc

原标题：golang 分布式上下文传递方案
简介：golang tcp_NODELAY 关闭延迟发送，设置 tcp_NODELAY，关闭 Nagle 算法，降低小包请求延迟。
 | 原文链接：http://wiki.mljc3b.asia/arts/269519.Doc

原标题：业务接口幂等完整落地案例
简介：golang gorm 子查询嵌套查询写法，Gorm 实现子查询、嵌套查询，复杂条件查询简化代码编写。
 | 原文链接：http://wiki.mljc3b.asia/arts/640549.Doc

原标题：坑点：缓存穿透，大量无效请求打穿数据库
简介：调试工具断点调试变量查看技巧，演示断点设置、变量监视、调用栈查看，借助调试工具高效排查业务逻辑错误。
 | 原文链接：http://wiki.mljc3b.asia/arts/895911.Doc

原标题：集成测试业务流程编写示例
简介：前端骨架屏提升页面体验，实现页面骨架屏，数据未加载完成展示占位，优化页面白屏感知体验。
 | 原文链接：http://wiki.mljc3b.asia/arts/092404.Doc

原标题：集成测试业务流程编写示例
简介：golang k8s go 服务 yaml 资源编写，k8s 部署 go 应用 deployment service，健康检查资源限制配置。
 | 原文链接：http://wiki.mljc3b.asia/arts/892677.Doc

原标题：Security：限流防爬虫防恶意攻击防护体系
简介：批量数据处理脚本编写技巧，编写脚本批量处理大量业务数据，循环处理、分批执行，提升数据处理效率。
 | 原文链接：http://wiki.mljc3b.asia/arts/497951.Doc

原标题：运维笔记：系统监控指标大盘搭建实操
简介：css 变量主题切换方案实现，使用 CSS 变量实现网页主题切换，多套主题样式快速切换无需大量 CSS。
 | 原文链接：http://wiki.mljc3b.asia/arts/641581.Doc

原标题：快速上手单元测试，写出第一个测试用例
简介：golang go 锁竞争导致 CPU 飙升，识别锁竞争场景，减少锁粒度，优化并发逻辑降低 CPU 开销。
 | 原文链接：http://wiki.mljc3b.asia/arts/566614.Doc

原标题：项目实践：多环境配置管理组件设计与实现
简介：单元测试用例编写入门实操，讲解测试用例设计思路，演示基础单元测试代码，提升代码健壮性，提前发现逻辑 bug。
 | 原文链接：http://wiki.mljc3b.asia/arts/994014.Doc

原标题：golang kafka offset 提交策略
简介：TCP 长连接参数优化 TIME_WAIT，调整 TCP 内核参数，优化长连接，减少大量 TIME_WAIT 连接占用资源。
 | 原文链接：http://wiki.mljc3b.asia/arts/013143.Doc

原标题：从零搭建简单CLI命令行工具
简介：golang strings.Builder 字符串高效拼接，strings.Builder 做字符串拼接，比 += 性能更高，减少内存拷贝。
 | 原文链接：http://wiki.mljc3b.asia/arts/993262.Doc

原标题：golang kafka 消息丢失重复消费
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://wiki.mljc3b.asia/arts/742322.Doc

原标题：运维笔记：服务器日志轮转logrotate配置
简介：golang redis stream 消息队列实战，redis stream 实现可靠消息队列，消费组、ack 确认，消息不丢失。
 | 原文链接：http://wiki.mljc3b.asia/arts/050326.Doc

原标题：复盘总结：分布式系统常见坑点汇总清单
简介：接口幂等性防重复请求实现，实现接口幂等逻辑，避免重复提交请求产生多条脏数据，保障业务数据安全。
 | 原文链接：http://wiki.mljc3b.asia/arts/923381.Doc

原标题：golang 系统设计无锁编程思路简单示例
简介：service‑worker 离线缓存实践，使用 ServiceWorker 实现静态资源离线缓存，弱网环境页面依然可访问。
 | 原文链接：http://wiki.mljc3b.asia/arts/275062.Doc

原标题：golang 系统设计内存复用 sync.pool 使用
简介：大事务拆分防止连接池耗尽，将执行时间很长的大事务拆分为小事务，减少事务占用连接时长。
 | 原文链接：http://wiki.mljc3b.asia/arts/455417.Doc

原标题：DevOps：GitLabCI完整流水线配置示例
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://wiki.mljc3b.asia/arts/963108.Doc

原标题：Troubleshoot：MySQL字符集utf8非utf8mb4emoji报错
简介：golang hertz 反向代理与负载均衡，hertz 实现反向代理，内置负载均衡，快速搭建网关类服务。
 | 原文链接：http://wiki.mljc3b.asia/arts/506141.Doc

原标题：对象存储上传下载权限实操
简介：多实例部署 Session 共享方案，多服务实例部署场景，实现 Session 共享，保证用户登录状态跨实例生效。
 | 原文链接：http://wiki.mljc3b.asia/arts/002038.Doc

原标题：线上故障：Redis内存淘汰策略错误数据丢失
简介：JWT 令牌过期异常处理，捕获 JWT 过期、篡改异常，编写业务处理逻辑，引导用户重新获取令牌。
 | 原文链接：http://wiki.mljc3b.asia/arts/458714.Doc

原标题：记一次限流组件误配置把正常用户拦截
简介：缓存过期打散防止缓存雪崩，对缓存过期时间增加随机偏移，避免大量缓存同时失效引发缓存雪崩。
 | 原文链接：http://wiki.mljc3b.asia/arts/206957.Doc


二、踩坑排错｜Troubleshooting
原标题：坑点：限流计数器重置时机错误，绕过限流规则
简介：react 状态管理方案选型对比，对比 Redux、Zustand 等 React 状态管理库，分析适用业务场景辅助选型。
 | 原文链接：http://wiki.mljc3b.asia/arts/674476.Doc

原标题：实战：Nginx配置静态站点、反向代理、负载均衡
简介：golang http 服务并发连接数限制，自定义 listener 统计连接数量，限制最大并发连接数保护服务。
 | 原文链接：http://wiki.mljc3b.asia/arts/650049.Doc

原标题：效率笔记：批量处理文本命令行工具实战案例
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://wiki.mljc3b.asia/arts/203951.Doc

原标题：极简方式搭建个人技术文档站点
简介：磁盘占满服务不可用清理方案，定位磁盘占用大文件，清理日志、缓存文件，恢复磁盘可用空间。
 | 原文链接：http://wiki.mljc3b.asia/arts/898139.Doc

原标题：golang 系统设计高可用服务架构梳理
简介：golang gin 静态资源访问配置，Gin 配置静态资源目录，直接对外提供静态文件访问服务。
 | 原文链接：http://wiki.mljc3b.asia/arts/059906.Doc

原标题：零基础理解会话、Cookie、Session基础
简介：golang ip 限流黑名单实现方案，基于 IP 做限流与黑名单，拦截恶意 IP 访问，保护接口服务。
 | 原文链接：http://wiki.mljc3b.asia/arts/759689.Doc

原标题：特殊输入字符过滤解析防护
简介：分布式事务最终一致性实现，基于可靠消息实现最终一致性，解决跨数据库跨服务业务数据一致性。
 | 原文链接：http://wiki.mljc3b.asia/arts/647761.Doc

原标题：DevOps：制品仓库管理二进制产物版本
简介：无用对象回收抑制内存上涨，优化对象生命周期，及时释放不再使用对象，抑制内存持续不断增长。
 | 原文链接：http://wiki.mljc3b.asia/arts/443510.Doc

原标题：golang 系统设计代码评审高效沟通原则思路
简介：灰度发布策略服务平滑升级，实现灰度发布逻辑，流量逐步切到新版本，出现问题快速回滚旧版本。
 | 原文链接：http://wiki.mljc3b.asia/arts/964415.Doc

原标题：WebSocket 聊天室实时通讯开发
简介：golang fasthttp 客户端连接池调优，fasthttp 客户端连接池配置，复用连接提升请求性能。
 | 原文链接：http://wiki.mljc3b.asia/arts/440882.Doc

原标题：golang 日志 zap 结构化日志实践
简介：golang go‑zero rpc 微服务开发，go‑zero 定义 proto，生成 rpc 服务代码，实现微服务调用。
 | 原文链接：http://wiki.mljc3b.asia/arts/506709.Doc

原标题：golang 系统设计故障复盘模板 postmortem 参考
简介：golang redis 锁超时业务处理，Redis 分布式锁超时问题处理，锁续期逻辑，防止业务未完成锁提前释放。
 | 原文链接：http://wiki.mljc3b.asia/arts/712694.Doc

原标题：Issue复现：内存泄漏定位完整复盘记录
简介：数据库分表路由写入分片修正，修复分表路由逻辑，保证数据写入正确分片，不会出现数据丢失错乱。
 | 原文链接：http://wiki.mljc3b.asia/arts/509733.Doc

原标题：Security：Web常见安全漏洞原理与修复清单
简介：golang 大内存分配 GC 抖动规避，避免瞬时大量对象创建，分批处理，防止 GC 抖动业务抖动。
 | 原文链接：http://wiki.mljc3b.asia/arts/668801.Doc

原标题：Troubleshooting：K8sPodOOMKilled完整排查流程
简介：异步任务堆积消费能力优化，处理消息任务堆积问题，提升消费处理速度，恢复队列正常处理水位。
 | 原文链接：http://wiki.mljc3b.asia/arts/411057.Doc

原标题：灰度发布策略服务平滑升级
简介：本地简易配置中心动态管理，搭建轻量本地配置中心，业务动态读取配置，修改配置不重启服务。
 | 原文链接：http://wiki.mljc3b.asia/arts/805088.Doc

原标题：布隆过滤器数据高效去重实现
简介：golang websocket 服务端开发，Go 实现 WebSocket 服务端，处理连接、消息收发，实现长连接服务。
 | 原文链接：http://wiki.mljc3b.asia/arts/581749.Doc

原标题：分布式事务最终一致性实现
简介：服务器时钟同步任务错乱修复，配置服务器 NTP 时间同步，保证集群所有机器时间保持一致。
 | 原文链接：http://wiki.mljc3b.asia/arts/572314.Doc

原标题：Debug：时间回拨，定时任务调度逻辑错乱
简介：golang go 第三方库选型评估要点，评估库活跃度维护情况、性能、依赖数量，选择合适开源库。
 | 原文链接：http://wiki.mljc3b.asia/arts/322001.Doc

原标题：golang 系统设计网络 io 模型 epoll 原理讲解
简介：golang 限流器熔断降级组合使用，限流熔断降级组合架构，流量防护完整方案，保障服务稳定性。
 | 原文链接：http://wiki.mljc3b.asia/arts/124553.Doc

原标题：调优方案：JVM内存参数优化，降低GC频率
简介：数据库分表存储大表优化方案，对超大数据表做分表，拆分数据，降低单表数据量提升查询性能。
 | 原文链接：http://wiki.mljc3b.asia/arts/203364.Doc

原标题：OpenSource：如何高效阅读大型开源项目源码
简介：前端组件库按需加载性能优化，配置组件库按需引入，避免引入全部组件，减少打包产物体积。
 | 原文链接：http://wiki.mljc3b.asia/arts/271585.Doc

原标题：开发记录：批量接口请求并发控制实践
简介：后端分页查询逻辑代码实现，编写后端分页接口，处理页码、每页条数参数，优化大数据量查询返回结果。
 | 原文链接：http://wiki.mljc3b.asia/arts/194294.Doc

原标题：golang gin 框架接口开发实战
简介：pnpm 包管理工具实战避坑指南，使用 pnpm 管理项目依赖，梳理常见坑点，充分利用 pnpm 优势。
 | 原文链接：http://wiki.mljc3b.asia/arts/677667.Doc

原标题：实践：OpenAPI自动生成接口文档完整实践
简介：golang 日志按日期切割实现方案，实现日志文件按天切割，自动归档旧日志，防止单个日志文件过大。
 | 原文链接：http://wiki.mljc3b.asia/arts/971593.Doc

原标题：Debug日志：生产环境偶发空指针异常排查
简介：nodejs 中间件模式原理剖析，拆解 Node 中间件设计模式，理解请求逐层处理流转的底层原理。
 | 原文链接：http://wiki.mljc3b.asia/arts/814061.Doc

原标题：WebSocket 断线重连稳定优化
简介：golang go‑pg postgres 客户端实操，go‑pg 操作 PostgreSQL 数据库，CRUD 关联查询业务开发。
 | 原文链接：http://wiki.mljc3b.asia/arts/899221.Doc

原标题：部署复盘：配置热更新不用重启服务方案
简介：git stash 代码暂存切换分支，使用 stash 暂存未提交代码，切换其他分支处理紧急任务，再恢复原有工作进度。
 | 原文链接：http://wiki.mljc3b.asia/arts/438561.Doc

原标题：性能笔记：TCP参数内核调优服务高并发场景
简介：golang excel 生成导出高性能方案，excelize 流式生成 excel，百万行数据导出，规避内存溢出。
 | 原文链接：http://wiki.mljc3b.asia/arts/314369.Doc

原标题：入门实践：简单数据脱敏处理示例
简介：golang alertmanager 告警配置实践，alertmanager 配置告警路由，告警发送邮件钉钉，异常及时通知运维。
 | 原文链接：http://wiki.mljc3b.asia/arts/488276.Doc

原标题：项目目录结构规范化最佳实践
简介：golang gin 框架接口开发实战，Gin 框架搭建 HTTP 服务，开发增删改查接口，快速完成后端接口开发。
 | 原文链接：http://wiki.mljc3b.asia/arts/788027.Doc

原标题：内存广播本地进程消息通知
简介：线程调度优化减少上下文切换，优化线程数量，减少线程频繁切换，降低 CPU 上下文切换开销。
 | 原文链接：http://wiki.mljc3b.asia/arts/679437.Doc

原标题：实践：数据库备份脚本自动化编写实践
简介：多实例部署 Session 共享方案，多服务实例部署场景，实现 Session 共享，保证用户登录状态跨实例生效。
 | 原文链接：http://wiki.mljc3b.asia/arts/766193.Doc

原标题：运维笔记：服务器日志轮转logrotate配置
简介：golang kafka 消费者组重平衡避坑，规避消费者组频繁 rebalance，减少消费抖动，保障消息消费稳定性。
 | 原文链接：http://wiki.mljc3b.asia/arts/265237.Doc

原标题：golang 系统设计逻辑删除物理删除选型对比
简介：golang embed 目录读取文件列表，embed 嵌入整个目录，读取目录下全部文件，做静态资源服务。
 | 原文链接：http://wiki.mljc3b.asia/arts/269704.Doc

原标题：golang 分布式锁防死锁处理
简介：TLS 版本兼容 HTTPS 握手失败，兼容老旧 TLS 协议版本，修复部分客户端 HTTPS 握手失败无法访问。
 | 原文链接：http://wiki.mljc3b.asia/arts/755403.Doc

原标题：前端组件库按需加载性能优化
简介：golang go 依赖漏洞检测 govulncheck，govulncheck 扫描依赖安全漏洞，发现项目供应链风险。
 | 原文链接：http://wiki.mljc3b.asia/arts/345060.Doc

原标题：Debug日志：生产环境偶发空指针异常排查
简介：golang 服务注册 etcd 简单示例，etcd 实现服务注册发现，微服务实例注册元数据，客户端发现节点。
 | 原文链接：http://wiki.mljc3b.asia/arts/263729.Doc

原标题：数据库主从延迟业务兼容处理
简介：golang math 包常用数学函数，绝对值取整平方根三角函数，业务数学计算工具。
 | 原文链接：http://wiki.mljc3b.asia/arts/035579.Doc

原标题：golang 系统设计主干开发 trunk‑based 讲解
简介：安全组端口开放网络访问，调整服务器安全组规则，开放业务需要端口，恢复外部网络访问服务。
 | 原文链接：http://wiki.mljc3b.asia/arts/648457.Doc

三、实战开发｜Practice
原标题：golang 日志 zap 结构化日志实践
简介：golang go‑zero 配置中心热更新，go‑zero 对接 etcd 配置中心，配置热更新无需重启服务。
 | 原文链接：http://wiki.mljc3b.asia/arts/852210.Doc

原标题：golang 系统设计批量处理优化业务性能
简介：golang 命令行彩色输出终端，终端彩色文字输出，进度条交互，优化命令行工具用户体验。
 | 原文链接：http://wiki.mljc3b.asia/arts/771661.Doc

原标题：golang 系统设计埋点数据上报方案
简介：接口限流逻辑简单模拟实现，编写简易限流逻辑，限制接口访问频次，保护服务，避免短时间大量请求压垮系统。
 | 原文链接：http://wiki.mljc3b.asia/arts/455495.Doc

原标题：golang 系统设计 rest http 方法使用原则
简介：限流规则误拦截正常请求修复，修正限流规则阈值，避免合法用户被限流拦截，兼顾防护与可用性。
 | 原文链接：http://wiki.mljc3b.asia/arts/841815.Doc

原标题：golang redis 缓存雪崩完整处理
简介：golang go regexp 正则预编译，regexp.MustCompile 预编译正则，不要循环内部编译正则，节省 CPU。
 | 原文链接：http://wiki.mljc3b.asia/arts/206245.Doc

原标题：golang k8s 日志收集 efk 简单架构
简介：golang socket 文件描述符继承重启，父进程传递 listener fd 给子进程，实现 go 程序零停机热重启。
 | 原文链接：http://wiki.mljc3b.asia/arts/013511.Doc

原标题：axios 二次封装请求拦截处理
简介：golang 自定义 pprof 扩展业务指标，扩展 pprof，输出业务自定义指标，结合性能数据分析业务状态。
 | 原文链接：http://wiki.mljc3b.asia/arts/749837.Doc

原标题：golang 系统设计 mq 消息丢失完整防护
简介：golang bufio.Scanner 按行读取大文件，Scanner 逐行读取文本文件，处理超大日志 csv。
 | 原文链接：http://wiki.mljc3b.asia/arts/719213.Doc

原标题：记一次第三方SDK版本兼容引发线上故障
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://wiki.mljc3b.asia/arts/820601.Doc

原标题：线上异常：接口偶发超时，完整定位过程记录
简介：golang gorm 原生 SQL 执行处理，复杂场景执行原生 SQL，处理返回结果集，兼顾性能与灵活性。
 | 原文链接：http://wiki.mljc3b.asia/arts/260243.Doc

原标题：golang 系统设计 gob msgpack 序列化对比
简介：golang go math 大数高精度计算，math/big 处理超大整数、高精度浮点数，金额大数运算。
 | 原文链接：http://wiki.mljc3b.asia/arts/412466.Doc

原标题：开源实践：开源Issue沟通技巧如何有效提Bug
简介：golang dns 自定义解析器实现，自定义 dns 解析，指定 dns 服务器，控制域名解析逻辑，适配内网环境。
 | 原文链接：http://wiki.mljc3b.asia/arts/677119.Doc

原标题：golang traceId spanId 传递方案
简介：限流规则误拦截正常请求修复，修正限流规则阈值，避免合法用户被限流拦截，兼顾防护与可用性。
 | 原文链接：http://wiki.mljc3b.asia/arts/563102.Doc

原标题：排错：内网域名解析不稳定导致服务随机报错
简介：K8s 镜像拉取网络故障修复，排查 K8s 集群镜像拉取网络问题，配置镜像源，恢复镜像正常拉取。
 | 原文链接：http://wiki.mljc3b.asia/arts/860465.Doc

原标题：golang 系统设计海量数据分页查询
简介：Cookie 跨环境登录配置调整，调整 Cookie 域、Secure 属性，适配开发测试生产环境，修复登录失效。
 | 原文链接：http://wiki.mljc3b.asia/arts/997277.Doc

原标题：golang mongodb 分页性能优化技巧
简介：业务错误码体系设计方案，设计项目统一错误码，区分不同业务异常，标准化错误返回，便于前端识别处理。
 | 原文链接：http://wiki.mljc3b.asia/arts/640576.Doc

原标题：设计思考：系统幂等性整体架构层面保障
简介：golang 滑动窗口限流算法 go 实现，滑动窗口限流，解决固定窗口临界流量突增漏洞，限流更精准。
 | 原文链接：http://wiki.mljc3b.asia/arts/706412.Doc

原标题：项目实践：Docker镜像安全扫描本地实操
简介：端口占用释放资源重启服务，查找占用端口进程，结束占用进程，释放端口，让服务能够正常启动监听。
 | 原文链接：http://wiki.mljc3b.asia/arts/634805.Doc

原标题：项目实践：灰度发布简易方案落地实践
简介：golang 模糊测试 go fuzz 基础编写，Fuzz 测试函数，自动生成随机输入，发现代码崩溃 panic。
 | 原文链接：http://wiki.mljc3b.asia/arts/927321.Doc

原标题：HelloShell：入门常用shell脚本编写
简介：golang tcp 连接泄露排查定位，netstat 查看连接状态，找出未正常关闭连接，定位连接泄漏代码。
 | 原文链接：http://wiki.mljc3b.asia/arts/440760.Doc

原标题：Debug：序列化反序列化版本不一致解析失败
简介：golang redis scan 遍历 key 避免阻塞，使用 scan 迭代遍历 redis 键，不用 keys 命令，防止阻塞 redis 服务。
 | 原文链接：http://wiki.mljc3b.asia/arts/312656.Doc

原标题：golang k8s job 一次性任务执行
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：http://wiki.mljc3b.asia/arts/237871.Doc

原标题：golang redis stream 消息队列实践
简介：golang excel 大文件读取流式解析，流式读取大 excel 文件，逐行解析数据，不加载全部内容进内存。
 | 原文链接：http://wiki.mljc3b.asia/arts/564069.Doc

原标题：golang jaeger 链路追踪 go 接入
简介：golang go 错误包装 fmt.Errorf % w，使用 % w 包装错误，支持 errors.Is errors.As 判断错误类型。
 | 原文链接：http://wiki.mljc3b.asia/arts/755142.Doc

原标题：golang nginx 反向代理 go 服务配置
简介：静态博客部署 GitHub Pages 教程，将静态博客项目部署至 GitHub Pages，完成线上访问，快速搭建个人技术博客站点。
 | 原文链接：http://wiki.mljc3b.asia/arts/957932.Doc

原标题：golang 系统设计代码评审关注点 checklist 清单
简介：golang testify testify 断言库使用，testify assert require 断言，简化单元测试断言代码。
 | 原文链接：http://wiki.mljc3b.asia/arts/986974.Doc

原标题：Practice：模拟第三方接口超时服务降级验证
简介：golang 集成测试测试数据库回滚，集成测试结束自动回滚数据库，不污染测试环境数据。
 | 原文链接：http://wiki.mljc3b.asia/arts/237095.Doc

原标题：入门实践：本地简单代理服务搭建
简介：golang go 接口定义原则小接口，go 小接口设计原则，接口尽量小，只定义必要方法，提升代码灵活性。
 | 原文链接：http://wiki.mljc3b.asia/arts/394908.Doc

原标题：Issue复现：内存泄漏定位完整复盘记录
简介：golang net/http/httptest 服务端模拟，httptest.NewRecorder 记录 handler 响应，校验返回状态码 body。
 | 原文链接：http://wiki.mljc3b.asia/arts/141728.Doc

原标题：golang mysql 存储过程简单使用
简介：golang go 错误包装 fmt.Errorf % w，使用 % w 包装错误，支持 errors.Is errors.As 判断错误类型。
 | 原文链接：http://wiki.mljc3b.asia/arts/444429.Doc

原标题：调优方案：JVM内存参数优化，降低GC频率
简介：Docker 多阶段构建镜像瘦身，使用 Docker 多阶段构建，剔除编译阶段依赖，产出体积更小运行镜像。
 | 原文链接：http://wiki.mljc3b.asia/arts/856087.Doc

原标题：安全笔记：GitHubAction密钥安全管理
简介：服务熔断防止故障级联传播，实现服务熔断逻辑，下游故障时快速失败，阻止故障向上游链式扩散。
 | 原文链接：http://wiki.mljc3b.asia/arts/825269.Doc

原标题：Docker 容器入门镜像实操教程
简介：大文件导出内存溢出防护，流式处理大文件导出，边读边写，不把全部数据加载内存，规避 OOM。
 | 原文链接：http://wiki.mljc3b.asia/arts/933886.Doc

原标题：架构笔记：缓存雪崩缓存击穿架构防护方案
简介：golang 反向代理 http 服务开发，手写简易 http 反向代理，转发请求，修改请求头响应头。
 | 原文链接：http://wiki.mljc3b.asia/arts/044332.Doc

原标题：踩坑：重试逻辑未做幂等，重复生成业务数据
简介：golang testing.TB Helper 标记辅助函数，t.Helper 标记辅助函数，报错打印真实调用位置。
 | 原文链接：http://wiki.mljc3b.asia/arts/047997.Doc

原标题：坑点：gitreset误删本地代码恢复方案
简介：golang base64 编码解码实操，Go Base64 编码解码示例，处理业务场景 Base64 格式数据转换。
 | 原文链接：http://wiki.mljc3b.asia/arts/530830.Doc

原标题：实战项目：搭建私有Docker镜像仓库本地实践
简介：golang context 取消传播机制，父 ctx 取消，所有派生子 context 全部被取消，理解上下文传播。
 | 原文链接：http://wiki.mljc3b.asia/arts/302725.Doc

原标题：方案对比：轮询长轮询WebSocket推送架构选型
简介：端口占用访问失败排查方案，讲解端口占用排查命令，定位占用进程，释放端口，解决服务启动端口被占用报错。
 | 原文链接：http://wiki.mljc3b.asia/arts/256105.Doc

原标题：开源实践：开源Issue沟通技巧如何有效提Bug
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：http://wiki.mljc3b.asia/arts/896763.Doc

原标题：golang 系统设计海量数据分页查询
简介：短信服务封装失败自动重试，封装短信发送组件，处理发送失败自动重试，兼容多短信服务商。
 | 原文链接：http://wiki.mljc3b.asia/arts/331479.Doc

四、架构设计｜Architecture
原标题：新手指南：如何读懂开源项目报错日志
简介：golang 自定义 pprof 扩展业务指标，扩展 pprof，输出业务自定义指标，结合性能数据分析业务状态。
 | 原文链接：http://wiki.mljc3b.asia/arts/158782.Doc

原标题：部署实践：Nginx高可用配置方案实践
简介：前端静态缓存更新生效处理，修改静态资源版本标识，处理浏览器强缓存，让更新资源生效。
 | 原文链接：http://wiki.mljc3b.asia/arts/960429.Doc

原标题：性能笔记：DNS缓存优化减少域名解析开销
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://wiki.mljc3b.asia/arts/609942.Doc

原标题：Redis 热点 key 拆分降低集群压力
简介：golang grpc keepalive 保活配置，grpc keepalive 参数调优，检测断开僵死连接，释放无效连接资源。
 | 原文链接：http://wiki.mljc3b.asia/arts/805272.Doc

原标题：Troubleshooting：k8s镜像拉取失败镜像仓库网络问题
简介：文件描述符优化进程卡死修复，及时关闭文件句柄，控制打开文件数量，解决文件句柄耗尽进程卡死。
 | 原文链接：http://wiki.mljc3b.asia/arts/527038.Doc

原标题：golang 系统设计 mq 消息顺序性保证思路
简介：golang viper 多源配置管理实操，viper 读取配置文件环境变量命令行参数，多源配置优先级管理。
 | 原文链接：http://wiki.mljc3b.asia/arts/741005.Doc

原标题：golang 系统设计配置多环境本地开发适配方案
简介：HTTPS 证书过期更新操作，检测 HTTPS 证书到期，更新证书文件，恢复 HTTPS 服务正常访问。
 | 原文链接：http://wiki.mljc3b.asia/arts/357986.Doc

原标题：架构笔记：WebSocket大规模连接服务架构
简介：golang sync.WaitGroup 协程等待控制，WaitGroup 控制一组协程等待全部执行完成，完成批量协程任务调度。
 | 原文链接：http://wiki.mljc3b.asia/arts/328433.Doc

原标题：golang 系统设计接口返回格式统一规范
简介：文件分片上传断点续传功能，实现文件分片上传，记录上传进度，支持断点续传大文件上传。
 | 原文链接：http://wiki.mljc3b.asia/arts/453949.Doc

原标题：golang 系统设计 api 文档 swagger redoc 落地
简介：重复提交幂等防护再次讲解，梳理前端重复点击、网络重试场景，落地接口幂等，杜绝重复业务。
 | 原文链接：http://wiki.mljc3b.asia/arts/157293.Doc

原标题：项目实践：OpenTelemetry链路追踪本地部署实践
简介：golang 雪花算法 workId 自动获取，自动获取机器 workId，不用手动配置，简化分布式 id 部署。
 | 原文链接：http://wiki.mljc3b.asia/arts/471953.Doc

原标题：Debug：表单自动转义特殊字符业务逻辑出错
简介：golang go 程序权限最小化运行，容器内使用普通用户运行程序，拒绝 root 运行提升安全等级。
 | 原文链接：http://wiki.mljc3b.asia/arts/044094.Doc

原标题：golang 系统设计分表扩容数据平滑迁移思路
简介：golang gin 参数绑定 query form json，掌握 Gin 多种参数绑定方式，适配不同请求格式参数读取。
 | 原文链接：http://wiki.mljc3b.asia/arts/088084.Doc

原标题：golang 系统设计接口幂等架构设计
简介：golang 信号捕获程序退出处理，Go 捕获操作系统信号，做资源回收，控制程序退出流程。
 | 原文链接：http://wiki.mljc3b.asia/arts/930680.Doc

原标题：操作系统内核版本适配服务
简介：golang go url url.Values 参数编码，url.Values 构建 url 查询参数，自动处理参数 url 编码。
 | 原文链接：http://wiki.mljc3b.asia/arts/622806.Doc

原标题：nodejs 进程间通信 IPC 实操
简介：golang kafka 消费者位移管理，理解 kafka offset，手动提交位移，保证消息消费至少一次语义。
 | 原文链接：http://wiki.mljc3b.asia/arts/607657.Doc

原标题：golang 系统设计压测指标 qps rt 错误率讲解
简介：golang go cover 覆盖率报告生成，go test‑cover 生成测试覆盖率，html 可视化查看未覆盖代码行。
 | 原文链接：http://wiki.mljc3b.asia/arts/412390.Doc

原标题：Performance：长连接管理优化减少连接重建开销
简介：Docker Compose 一键搭建本地栈，使用 Compose 编排多个容器，一键拉起全套开发依赖服务。
 | 原文链接：http://wiki.mljc3b.asia/arts/107834.Doc

?
