最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计网关性能压测优化简单思路
简介：golang grpc metadata 元数据透传，metadata 传递 traceId、鉴权信息，全链路透传上下文信息。
 | 原文链接：http://zhishi.hlitpm.asia/blog/5306641.sHtML

原标题：golang gorm 批量插入性能调优
简介：环境变量不生效问题修复，排查环境变量加载顺序、作用域问题，修复环境变量读取不到的异常。
 | 原文链接：http://zhishi.hlitpm.asia/blog/8605483.sHtML

原标题：设计思考：防雪崩，系统过载保护架构设计
简介：安全组端口开放网络访问，调整服务器安全组规则，开放业务需要端口，恢复外部网络访问服务。
 | 原文链接：http://zhishi.hlitpm.asia/blog/3198615.sHtML

原标题：golang 系统设计降级策略开关配置方案
简介：golang gin 静态资源访问配置，Gin 配置静态资源目录，直接对外提供静态文件访问服务。
 | 原文链接：http://zhishi.hlitpm.asia/blog/0991392.sHtML

原标题：前端虚拟列表大数据渲染优化
简介：golang context.Background 与 TODO 区别，Background 主流程根上下文，TODO 不确定用哪个上下文时使用。
 | 原文链接：http://zhishi.hlitpm.asia/blog/5923974.sHtML

原标题：golang 系统信号信号量处理
简介：golang 结构体 json 序列化坑点，梳理 Go 结构体 JSON 序列化高频坑点，字段大小写、零值处理问题。
 | 原文链接：http://zhishi.hlitpm.asia/blog/1449134.sHtML

原标题：从零编写简易 CLI 命令行工具
简介：golang redis 过期键监听回调，监听 key 过期事件，过期触发业务逻辑，实现过期自动处理业务场景。
 | 原文链接：http://zhishi.hlitpm.asia/blog/4846315.sHtML

原标题：请求重试组件退避策略实现
简介：golang staticcheck 静态代码分析，staticcheck 深度静态检查，发现代码错误、性能问题、风格问题。
 | 原文链接：http://zhishi.hlitpm.asia/blog/2806962.sHtML

原标题：简易日志收集集中管理方案
简介：golang go 二进制安全 strip 减小体积，strip 剥离二进制调试符号，缩小程序二进制文件体积。
 | 原文链接：http://zhishi.hlitpm.asia/blog/5114899.sHtML

原标题：批量数据处理脚本编写技巧
简介：golang aes cbc gcm 模式加密对比，AES‑CBC AES‑GCM 模式加密解密，理解两种模式差异选型。
 | 原文链接：http://zhishi.hlitpm.asia/blog/3731374.sHtML

原标题：效率笔记：Makefile项目构建脚本编写实践
简介：接口压测定位系统性能瓶颈，使用压测工具对接口施压，观察指标，定位系统性能瓶颈点。
 | 原文链接：http://zhishi.hlitpm.asia/blog/9661864.sHtML

原标题：内存溢出问题现象识别排查
简介：golang http client 全局变量复用，http Client 不要每次请求新建，复用 Transport 提升性能。
 | 原文链接：http://zhishi.hlitpm.asia/blog/0107099.sHtML

原标题：优化实践：LRU本地缓存优化热点访问性能
简介：golang go 容器 heap 堆实现优先队列，实现 heap 接口，构建优先队列，任务优先级调度。
 | 原文链接：http://zhishi.hlitpm.asia/blog/9701206.sHtML

原标题：部署实践：服务器时间同步chrony配置
简介：golang go 单二进制文件静态编译交叉编译，交叉编译不同操作系统架构二进制文件，实现一次编译多平台运行。
 | 原文链接：http://zhishi.hlitpm.asia/blog/7907568.sHtML

原标题：方案对比：定时任务框架选型与架构对比
简介：WSL 文件权限访问异常修复，处理 WSL 环境文件权限错乱，调整权限配置，实现文件正常读写访问。
 | 原文链接：http://zhishi.hlitpm.asia/blog/2160383.sHtML

原标题：OpenAPI 自动接口文档生成
简介：golang init 函数合理使用边界，少用 init，优先显式调用初始化，便于控制初始化时机。
 | 原文链接：http://zhishi.hlitpm.asia/blog/6469361.sHtML

原标题：新手教程：Git撤销错误提交的几种常用方式
简介：golang os.Exit 退出程序注意 defer 不执行，os.Exit 会直接退出，不会执行 defer，优雅退出不要直接 os.Exit。
 | 原文链接：http://zhishi.hlitpm.asia/blog/7403248.sHtML

原标题：golang 系统设计分布式锁不同场景选型对比
简介：OAuth2 第三方登录服务搭建，搭建 OAuth2 服务，支持第三方账号登录，实现授权登录能力。
 | 原文链接：http://zhishi.hlitpm.asia/blog/5646487.sHtML

原标题：golang 系统设计配置中心核心能力梳理讲解
简介：分布式 ID 生成器高并发实现，实现高性能分布式 ID 生成器，适配高并发业务，生成全局唯一 ID。
 | 原文链接：http://zhishi.hlitpm.asia/blog/8462584.sHtML

原标题：前端静态缓存更新生效处理
简介：golang go http 服务器优雅关闭完整代码，http.Server Shutdown，等待现有请求处理完成关闭服务。
 | 原文链接：http://zhishi.hlitpm.asia/blog/6430872.sHtML

原标题：线上异常：线程池队列拒绝策略配置错误丢任务
简介：DNS TTL 配置域名切换生效，调整 DNS 解析 TTL，缩短缓存时间，域名变更后可以快速全网生效。
 | 原文链接：http://zhishi.hlitpm.asia/blog/0764968.sHtML

原标题：部署复盘：GitHubActions完整自动化配置
简介：golang 字符编码转换 go 处理，iconv‑go 做编码转换 gbk utf8 互转，处理老旧系统 gbk 编码数据。
 | 原文链接：http://zhishi.hlitpm.asia/blog/2387979.sHtML

原标题：预编译 SQL 防注入实现
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://zhishi.hlitpm.asia/blog/2663306.sHtML

原标题：Performance：JSON序列化性能优化实践
简介：golang gorm group by 分组统计，GORM 分组聚合统计，实现 count sum 等统计查询，快速完成统计业务。
 | 原文链接：http://zhishi.hlitpm.asia/blog/9134094.sHtML

原标题：零基础理解前后端简单交互流程
简介：前端虚拟列表大数据渲染优化，实现虚拟滚动列表，只渲染可视区域 DOM，上万条数据页面流畅渲染。
 | 原文链接：http://zhishi.hlitpm.asia/blog/6051091.sHtML

原标题：golang github actions 多平台构建
简介：golang tidb 数据库 go 项目适配，go 程序适配 tidb，兼容 mysql 协议，分布式数据库业务开发。
 | 原文链接：http://zhishi.hlitpm.asia/blog/4682883.sHtML

原标题：golang makefile 自动化构建脚本
简介：golang go‑zero 中间件鉴权限流，go‑zero 自定义中间件，实现鉴权、限流、日志打印通用能力。
 | 原文链接：http://zhishi.hlitpm.asia/blog/3475832.sHtML

原标题：开发复盘：大事务拆分优化业务性能实践
简介：日志敏感信息脱敏泄露防护，日志打印时自动脱敏手机号身份证，避免日志输出泄露用户隐私数据。
 | 原文链接：http://zhishi.hlitpm.asia/blog/9028867.sHtML

原标题：快速上手简单信号处理脚本编写
简介：golang http cookie jar 会话处理，客户端 cookie jar 自动管理 cookie，处理登录态会话。
 | 原文链接：http://zhishi.hlitpm.asia/blog/0775308.sHtML

原标题：golang mysql 时间类型选型避坑
简介：Redis 热点 key 拆分降低集群压力，拆分访问量极高的热点 Key，分散请求压力，避免 Redis 节点压力过高。
 | 原文链接：http://zhishi.hlitpm.asia/blog/5266728.sHtML

原标题：坑点：环境配置写死代码，上线忘记修改
简介：golang 自定义 pprof 扩展业务指标，扩展 pprof，输出业务自定义指标，结合性能数据分析业务状态。
 | 原文链接：http://zhishi.hlitpm.asia/blog/4201494.sHtML

原标题：golang 系统设计性能瓶颈定位完整方法论
简介：golang 延迟队列实现方案对比，时间轮、redis zset 实现延迟队列，处理延时执行业务。
 | 原文链接：http://zhishi.hlitpm.asia/blog/5321725.sHtML

原标题：实战项目：本地模拟磁盘IO高负载观察服务行为
简介：golang http body 必须关闭的重要性，无论成功失败必须关闭 request.Body，否则连接无法复用泄漏。
 | 原文链接：http://zhishi.hlitpm.asia/blog/4804757.sHtML

原标题：快速入门：API接口调试完整实操步骤
简介：Redis 热点 key 拆分降低集群压力，拆分访问量极高的热点 Key，分散请求压力，避免 Redis 节点压力过高。
 | 原文链接：http://zhishi.hlitpm.asia/blog/0276617.sHtML

原标题：express 中间件开发业务实践
简介：golang gin 中间件执行顺序讲解，理解 Gin 中间件注册顺序，区分前置后置逻辑，规避中间件顺序 bug。
 | 原文链接：http://zhishi.hlitpm.asia/blog/5403122.sHtML

原标题：golang 系统设计缓存降级开关快速切库实现
简介：文件句柄上限调整上传随机失败，调高系统文件句柄上限，解决高并发上传场景随机打开文件失败。
 | 原文链接：http://zhishi.hlitpm.asia/blog/4284271.sHtML

原标题：Performance：批量导入数据性能优化实践
简介：golang go 依赖漏洞检测 govulncheck，govulncheck 扫描依赖安全漏洞，发现项目供应链风险。
 | 原文链接：http://zhishi.hlitpm.asia/blog/0135603.sHtML

原标题：Performance：数据库join优化，大表join规避
简介：多实例部署 Session 共享方案，多服务实例部署场景，实现 Session 共享，保证用户登录状态跨实例生效。
 | 原文链接：http://zhishi.hlitpm.asia/blog/9325316.sHtML

原标题：快速入门ORM，实现简单数据库增删改查
简介：golang udp 服务端客户端开发示例，golang 实现 UDP 服务收发数据包，实现 udp 协议通信程序。
 | 原文链接：http://zhishi.hlitpm.asia/blog/1930741.sHtML

原标题：运维笔记：线上服务健康检查脚本编写
简介：golang bufio 缓冲读写性能优化，bufio 带缓冲读写，减少系统调用，提升文件网络 IO 性能。
 | 原文链接：http://zhishi.hlitpm.asia/blog/4881182.sHtML


二、踩坑排错｜Troubleshooting
原标题：安全笔记：文件下载接口路径校验安全
简介：golang cgo 性能开销避坑指南，cgo 调用开销，减少频繁 cgo 调用，规避 cgo 带来内存泄漏风险。
 | 原文链接：http://zhishi.hlitpm.asia/blog/9059179.sHtML

原标题：设计思考：分布式ID系统架构选型对比
简介：golang http 服务优雅关闭完整示例，接收终止信号，停止接收新请求，等待现有请求处理完毕后退出服务。
 | 原文链接：http://zhishi.hlitpm.asia/blog/0259421.sHtML

原标题：实践：实现Redis分布式锁完整可运行代码
简介：golang grpc 服务端流推送数据，服务端流式响应，服务端持续向客户端推送多条响应消息。
 | 原文链接：http://zhishi.hlitpm.asia/blog/0539547.sHtML

原标题：OpenSource：开源项目风险评估依赖安全检查
简介：golang context 上下文传参讲解，讲解 Context 使用场景，传递元数据、控制协程超时取消，规范协程控制。
 | 原文链接：http://zhishi.hlitpm.asia/blog/1320090.sHtML

原标题：golang go test 覆盖率统计实操
简介：golang GC 调优 GOGC 参数调整，调整 GOGC 阈值，控制 GC 触发时机，权衡内存占用与 CPU 开销。
 | 原文链接：http://zhishi.hlitpm.asia/blog/4508028.sHtML

原标题：golang 系统设计 json 解析性能优化实操
简介：golang os 主机名内核版本读取，os 读取主机名，内核信息，操作系统版本，获取运行环境信息。
 | 原文链接：http://zhishi.hlitpm.asia/blog/0386852.sHtML

原标题：golang redis bitmap 位图统计实现
简介：golang 错误栈捕获打印方案，捕获错误完整调用堆栈，线上日志输出堆栈，快速定位错误发生代码位置。
 | 原文链接：http://zhishi.hlitpm.asia/blog/3967910.sHtML

原标题：golang 系统设计排行榜几种实现
简介：golang go 模板执行错误捕获，捕获模板执行错误，防止模板错误直接返回空白页面。
 | 原文链接：http://zhishi.hlitpm.asia/blog/2186789.sHtML

原标题：新手教程：gitstash暂存工作区变更实操
简介：golang kitex 字节微服务框架入门，kitex 开发 rpc 微服务，代码生成，服务注册发现完整流程。
 | 原文链接：http://zhishi.hlitpm.asia/blog/7877495.sHtML

原标题：git cherry‑pick 规范操作防 bug
简介：缓存过期打散防止缓存雪崩，对缓存过期时间增加随机偏移，避免大量缓存同时失效引发缓存雪崩。
 | 原文链接：http://zhishi.hlitpm.asia/blog/2721945.sHtML

原标题：golang mysql json 字段查询使用
简介：eslint prettier 代码规范落地，配置 eslint 与 prettier，做代码检查格式化，统一前端团队代码风格。
 | 原文链接：http://zhishi.hlitpm.asia/blog/3756574.sHtML

原标题：golang 系统设计分布式锁超时业务防死锁处理
简介：golang go 程序运行时动态修改配置，运行时热加载配置结构体，原子更新保证并发读取安全。
 | 原文链接：http://zhishi.hlitpm.asia/blog/3912948.sHtML

原标题：golang 系统设计内部服务调用超时设置要点
简介：数据库死锁成因规避方案，讲解数据库死锁产生条件，给出业务层面规避手段，减少死锁事件发生。
 | 原文链接：http://zhishi.hlitpm.asia/blog/7617728.sHtML

原标题：golang mysql 联合索引最左匹配
简介：编译打包产物依赖分析解读，分析打包之后产物组成，理清运行依赖文件，排查打包后缺失文件问题。
 | 原文链接：http://zhishi.hlitpm.asia/blog/5942046.sHtML

原标题：pnpm 包管理工具实战避坑指南
简介：golang jaeger 链路追踪部署对接，jaeger 接收 opentelemetry 链路数据，可视化完整调用链路。
 | 原文链接：http://zhishi.hlitpm.asia/blog/6744045.sHtML

原标题：服务健康检查告警监控体系
简介：golang 消息队列 kafka 消费开发，Go 开发 Kafka 消费程序，消费消息执行业务，理解 Kafka 消费逻辑。
 | 原文链接：http://zhishi.hlitpm.asia/blog/1542502.sHtML

原标题：实战项目：多实例部署会话一致性验证实践
简介：golang 项目 makefile 脚本编写，编写 Makefile 脚本，封装编译、测试、构建命令，简化项目操作。
 | 原文链接：http://zhishi.hlitpm.asia/blog/6428343.sHtML

原标题：golang 系统设计传输加密 tls 配置要点
简介：golang GC 调优 GOGC 参数调整，调整 GOGC 阈值，控制 GC 触发时机，权衡内存占用与 CPU 开销。
 | 原文链接：http://zhishi.hlitpm.asia/blog/1649315.sHtML

原标题：golang es 聚合统计查询实现
简介：golang redis bitmap 位图业务实战，bitmap 做签到统计、用户状态标记，节省大量内存空间。
 | 原文链接：http://zhishi.hlitpm.asia/blog/1498595.sHtML

原标题：Issue：文件句柄耗尽，服务缓慢卡死复盘
简介：golang go mod graph 查看依赖关系，go mod graph 打印依赖树，定位间接依赖来源，解决版本冲突。
 | 原文链接：http://zhishi.hlitpm.asia/blog/9542209.sHtML

原标题：golang minio 预签名 url 临时访问
简介：nodejs 日志轮转生产环境配置，配置 Node 日志轮转切割，防止日志文件无限变大，适配生产环境。
 | 原文链接：http://zhishi.hlitpm.asia/blog/6988202.sHtML

原标题：Hands‑on：实现服务健康检查与自动报警demo
简介：分页逻辑错误数据漏查修复，修复分页查询逻辑漏洞，解决分页漏数据、重复返回数据等业务问题。
 | 原文链接：http://zhishi.hlitpm.asia/blog/8583093.sHtML

原标题：排错：容器OOM被杀死，日志看不到任何输出
简介：本地数据库开发环境搭建指南，讲解数据库安装配置、账号权限设置、连接测试，快速搭建用于开发调试的数据库实例。
 | 原文链接：http://zhishi.hlitpm.asia/blog/6241489.sHtML

原标题：golang 分布式锁 redis 实现
简介：golang go 代码覆盖率线上统计，单元测试覆盖率统计，找出未测试代码分支，提升测试质量。
 | 原文链接：http://zhishi.hlitpm.asia/blog/7929598.sHtML

原标题：golang mysql 悲观锁乐观锁实现
简介：golang grpc 客户端流上传数据，客户端流式请求，客户端分批上传数据到服务端，适合大文件传输。
 | 原文链接：http://zhishi.hlitpm.asia/blog/4168424.sHtML

原标题：Troubleshoot：跨域偶现失败难以复现问题
简介：依赖安装失败全方位排错，从网络、镜像源、权限、版本多角度，定位依赖安装失败，给出对应修复手段。
 | 原文链接：http://zhishi.hlitpm.asia/blog/7439578.sHtML

原标题：开源源码阅读拆解学习思路
简介：移动端适配 rem vw 方案对比，对比 rem 与 vw 移动端适配方案，分析优缺点，给出选型建议。
 | 原文链接：http://zhishi.hlitpm.asia/blog/3898644.sHtML

原标题：线上异常：缓存雪崩带来数据库压力瞬间飙升
简介：golang 数据库连接耗尽排查思路，监控连接池状态，定位连接未归还，解决连接耗尽报错。
 | 原文链接：http://zhishi.hlitpm.asia/blog/2641929.sHtML

原标题：eslint prettier 代码规范落地
简介：接口压测定位系统性能瓶颈，使用压测工具对接口施压，观察指标，定位系统性能瓶颈点。
 | 原文链接：http://zhishi.hlitpm.asia/blog/5332214.sHtML

原标题：Git 标签版本标记发布管理
简介：golang go get 升级降级依赖版本，go get 指定版本升级降级依赖包，管理第三方库版本。
 | 原文链接：http://zhishi.hlitpm.asia/blog/7161819.sHtML

原标题：系统文件描述符上限调大
简介：golang redis hyperloglog 基数统计，hyperloglog 统计 UV 基数，海量数据去重统计，极低内存开销。
 | 原文链接：http://zhishi.hlitpm.asia/blog/1022306.sHtML

原标题：golang 系统设计埋点数据上报方案
简介：配置与镜像分离防止信息泄露，业务配置不打包进镜像，外部挂载配置，避免密钥配置随镜像泄露。
 | 原文链接：http://zhishi.hlitpm.asia/blog/0108542.sHtML

原标题：golang 系统设计 rest 状态码合理使用指南
简介：golang go 并发模式 fan‑out fan‑in，fanout 分发任务 fanin 汇总结果，多协程并发处理任务。
 | 原文链接：http://zhishi.hlitpm.asia/blog/0751203.sHtML

原标题：入门实践：项目配置文件多环境管理方案
简介：gRPC 服务端客户端入门示例，搭建 gRPC 服务端与调用客户端，学习 protobuf 定义，掌握 RPC 基础开发流程。
 | 原文链接：http://zhishi.hlitpm.asia/blog/5999239.sHtML

原标题：开发记录：文件锁实现多进程互斥实践
简介：golang prometheus http 接口暴露指标，暴露 prometheus metrics 接口，输出业务运行指标，接入监控告警系统。
 | 原文链接：http://zhishi.hlitpm.asia/blog/6623371.sHtML

原标题：安全笔记：第三方SDK安全风险评估要点
简介：golang gin 路由分组权限管控，Gin 路由分组，不同分组绑定鉴权中间件，实现接口权限分组管控。
 | 原文链接：http://zhishi.hlitpm.asia/blog/4596585.sHtML

原标题：极简方式搭建个人技术文档站点
简介：慢查询分析索引调优数据库实战，抓取慢查询，分析执行计划，优化索引，解决数据库慢查询拖慢业务。
 | 原文链接：http://zhishi.hlitpm.asia/blog/5094761.sHtML

原标题：golang mysql 慢查询日志开启分析
简介：golang errgroup 协程组错误处理，errgroup 捕获协程错误，context 取消剩余协程，简化并发任务。
 | 原文链接：http://zhishi.hlitpm.asia/blog/7787688.sHtML

原标题：全局时间标准统一逻辑错乱修复
简介：Git 误删提交代码恢复找回，使用 Git reflog 工具找回被误删除提交记录，恢复误删除代码。
 | 原文链接：http://zhishi.hlitpm.asia/blog/5309014.sHtML

原标题：快速上手调试工具定位简单代码错误
简介：服务熔断防止故障级联传播，实现服务熔断逻辑，下游故障时快速失败，阻止故障向上游链式扩散。
 | 原文链接：http://zhishi.hlitpm.asia/blog/0653150.sHtML

三、实战开发｜Practice
原标题：golang 系统设计内部服务契约测试简单思路
简介：golang sql 注入风险规避要点，参数化查询杜绝 sql 注入，禁止字符串拼接 SQL 语句执行。
 | 原文链接：http://zhishi.hlitpm.asia/blog/9816170.sHtML

原标题：golang 工具函数库封装思路
简介：跨平台 uniapp 多端开发实操，uniapp 开发一套代码，编译多端，梳理多端差异处理与适配技巧。
 | 原文链接：http://zhishi.hlitpm.asia/blog/1905780.sHtML

原标题：golang gin 框架接口开发实战
简介：golang yaml 解析配置加载实操，Go 解析 YAML 配置文件，读取配置参数，驱动业务运行。
 | 原文链接：http://zhishi.hlitpm.asia/blog/3057085.sHtML

原标题：golang 系统设计死信队列 dlq 业务落地完整流程
简介：golang os 环境变量读取设置，os.Getenv os.Setenv os.Unsetenv 读写环境变量，环境变量多值处理。
 | 原文链接：http://zhishi.hlitpm.asia/blog/9621272.sHtML

原标题：golang mysql 行锁表锁场景区分
简介：golang jwt 令牌刷新逻辑实现，实现 JWT 双令牌机制，access 短期有效 refresh 刷新令牌，实现无感续期登录。
 | 原文链接：http://zhishi.hlitpm.asia/blog/0972246.sHtML

原标题：DevOps：GitLabCI完整流水线配置示例
简介：golang excel 生成导出高性能方案，excelize 流式生成 excel，百万行数据导出，规避内存溢出。
 | 原文链接：http://zhishi.hlitpm.asia/blog/5690014.sHtML

原标题：优化实践：序列化框架性能对比选型实践
简介：golang 布隆过滤器实现去重，Go 实现布隆过滤器，海量数据去重，节省内存开销，提升判断效率。
 | 原文链接：http://zhishi.hlitpm.asia/blog/9662934.sHtML

原标题：实战项目：WebSocket消息广播房间分组实践
简介：golang accept 错误循环崩溃处理，accept 返回系统错误，处理临时错误，避免死循环占满 CPU。
 | 原文链接：http://zhishi.hlitpm.asia/blog/8641466.sHtML

原标题：浏览器内存泄漏排查前端页面
简介：golang kafka 批量消费性能优化，开启批量拉取消息，调整批量大小，提升 kafka 消息消费吞吐量。
 | 原文链接：http://zhishi.hlitpm.asia/blog/3035908.sHtML

原标题：开发复盘：长轮询接口实现服务端消息推送
简介：程序预加载加快服务启动速度，把高频使用资源提前预加载，减少请求阶段初始化，加快服务启动。
 | 原文链接：http://zhishi.hlitpm.asia/blog/4096580.sHtML

原标题：Practice：实现熔断降级组件简单原型代码
简介：前端组件库按需加载性能优化，配置组件库按需引入，避免引入全部组件，减少打包产物体积。
 | 原文链接：http://zhishi.hlitpm.asia/blog/0161534.sHtML

原标题：golang 内存缓存简单实现方案
简介：golang 信号量 semaphore 并发限制，基于 semaphore 实现并发数量控制，保护数据库、第三方接口不被打满。
 | 原文链接：http://zhishi.hlitpm.asia/blog/2650274.sHtML

原标题：多环境配置中心灵活切换方案
简介：golang go 排序 sort 包自定义排序，sort 包实现自定义排序逻辑，对切片按业务规则排序。
 | 原文链接：http://zhishi.hlitpm.asia/blog/8632768.sHtML

原标题：短信服务封装失败自动重试
简介：golang validator 自定义校验规则，Gin Validator 自定义校验器，实现业务特殊参数校验逻辑。
 | 原文链接：http://zhishi.hlitpm.asia/blog/5064089.sHtML

原标题：从零搭建简单CLI命令行工具
简介：css 动画性能优化 GPU 加速，优化 CSS 动画，使用 GPU 加速属性，避免动画过程页面卡顿掉帧。
 | 原文链接：http://zhishi.hlitpm.asia/blog/1273119.sHtML

原标题：运维笔记：服务器故障排查常用命令清单
简介：nodejs 信号处理优雅关闭服务，监听系统信号，执行资源清理，实现 Node 服务优雅停机，拒绝粗暴杀死进程。
 | 原文链接：http://zhishi.hlitpm.asia/blog/0731857.sHtML

原标题：Practice：实现多数据源动态切换组件实践
简介：golang 反向代理 http 服务开发，手写简易 http 反向代理，转发请求，修改请求头响应头。
 | 原文链接：http://zhishi.hlitpm.asia/blog/8576611.sHtML

原标题：golang 系统设计 changelog 变更日志维护
简介：golang hertz http 框架快速上手，hertz 高性能 http 框架，路由中间件参数校验快速开发接口服务。
 | 原文链接：http://zhishi.hlitpm.asia/blog/1815969.sHtML

原标题：踩坑记录：端口被占用导致服务启动失败
简介：golang 性能压测 wr 工具实操指南，wr 压测工具对 Go 接口压测，观察 QPS 延迟，定位接口性能瓶颈。
 | 原文链接：http://zhishi.hlitpm.asia/blog/3061782.sHtML

原标题：CI 流水线构建失败日志排查
简介：MySQL 慢查询索引优化实战，抓取慢查询 SQL，分析执行计划，新增或者调整索引，提升 SQL 执行速度。
 | 原文链接：http://zhishi.hlitpm.asia/blog/2138873.sHtML

原标题：golang grpc protobuf 开发实操
简介：TLS 版本兼容 HTTPS 握手失败，兼容老旧 TLS 协议版本，修复部分客户端 HTTPS 握手失败无法访问。
 | 原文链接：http://zhishi.hlitpm.asia/blog/2829086.sHtML

原标题：golang 系统设计 tcp 粘包拆包处理方案实现
简介：golang sync/atomic 原子操作使用注意，理解原子操作内存顺序，规避原子操作错误使用带来 bug。
 | 原文链接：http://zhishi.hlitpm.asia/blog/7587559.sHtML

原标题：golang 系统设计 rest api 接口设计最佳实践
简介：golang go 代码覆盖率线上统计，单元测试覆盖率统计，找出未测试代码分支，提升测试质量。
 | 原文链接：http://zhishi.hlitpm.asia/blog/7989645.sHtML

原标题：快速入门消息队列基础概念模型
简介：golang 日志脱敏敏感字段过滤，日志打印自动脱敏敏感字段，避免日志输出手机号身份证泄露隐私。
 | 原文链接：http://zhishi.hlitpm.asia/blog/1828260.sHtML

原标题：golang 系统设计缓存空值防止缓存穿透实现
简介：项目语义化版本号规范管理，遵循语义化版本规范管理项目版本，明确主次版本变更含义。
 | 原文链接：http://zhishi.hlitpm.asia/blog/6468172.sHtML

原标题：实战：数据库explain执行计划分析实操演练
简介：golang http3 quic 客户端服务端示例，go 实现 http3 quic 服务端客户端，体验 quic 协议低延迟特性。
 | 原文链接：http://zhishi.hlitpm.asia/blog/7975224.sHtML

原标题：布隆过滤器数据高效去重实现
简介：golang redis pipeline 与 txpipeline 区别，区分普通管道与事务管道，根据业务场景选择合适批量执行方案。
 | 原文链接：http://zhishi.hlitpm.asia/blog/7355492.sHtML

原标题：HelloWorld：快速上手新项目最小可运行示例
简介：golang go 零停机升级实践要点，socket 继承，流量无损，旧连接处理完毕后旧进程退出。
 | 原文链接：http://zhishi.hlitpm.asia/blog/2463228.sHtML

原标题：golang 系统设计内部服务契约测试简单思路
简介：多实例部署 Session 共享方案，多服务实例部署场景，实现 Session 共享，保证用户登录状态跨实例生效。
 | 原文链接：http://zhishi.hlitpm.asia/blog/5429964.sHtML

原标题：golang 系统设计多租户数据隔离方案
简介：golang errgroup 协程组错误处理，errgroup 捕获协程错误，context 取消剩余协程，简化并发任务。
 | 原文链接：http://zhishi.hlitpm.asia/blog/9306965.sHtML

原标题：开发复盘：实现定时任务调度服务支持动态任务
简介：golang sync.Cond 条件变量使用，Cond 条件变量协程等待唤醒，复杂并发同步场景。
 | 原文链接：http://zhishi.hlitpm.asia/blog/0342870.sHtML

原标题：Git commit 钩子提交规范校验
简介：golang gif 图片帧处理操作，解析 gif 图片帧，压缩、拆分 gif 动图，处理动图业务。
 | 原文链接：http://zhishi.hlitpm.asia/blog/7791595.sHtML

原标题：性能笔记：避免频繁创建销毁对象GC优化
简介：golang uuid 生成多种版本实现，生成 uuid v1 v4，生成唯一标识，业务用于单据编号场景。
 | 原文链接：http://zhishi.hlitpm.asia/blog/6394288.sHtML

原标题：golang es 索引生命周期管理思路
简介：golang go 调度器 GMP 模型通俗讲解，拆解 GMP 模型，理解 goroutine M P 调度原理，看懂调度状态。
 | 原文链接：http://zhishi.hlitpm.asia/blog/4260623.sHtML

原标题：容器软链接文件权限修复
简介：预编译 SQL 防注入实现，使用预编译 SQL 方式，杜绝 SQL 注入风险，提升数据库访问层安全能力。
 | 原文链接：http://zhishi.hlitpm.asia/blog/2351895.sHtML

原标题：新手向：项目目录结构规范与含义解析
简介：nodejs 数据库连接池配置调优，调优 Node 数据库连接池参数，平衡性能与资源占用，避免连接耗尽。
 | 原文链接：http://zhishi.hlitpm.asia/blog/5320591.sHtML

原标题：golang 错误包装 errors.wrap 用法
简介：缓存穿透击穿雪崩全套防护，完整梳理缓存三大问题，落地全套防护策略，保障缓存层稳定运行。
 | 原文链接：http://zhishi.hlitpm.asia/blog/1857061.sHtML

原标题：Debug：并发场景下数据覆盖丢失问题定位
简介：RPC 接口字段增减兼容处理，RPC 接口新增删除字段做好向前兼容，老版本服务不会解析报错崩溃。
 | 原文链接：http://zhishi.hlitpm.asia/blog/0873683.sHtML

原标题：语义化版本依赖管理防错乱
简介：文件分片上传断点续传功能，实现文件分片上传，记录上传进度，支持断点续传大文件上传。
 | 原文链接：http://zhishi.hlitpm.asia/blog/1802644.sHtML

原标题：网关集成鉴权限流日志一体化
简介：golang 分布式锁 redis 实现，基于 Redis 实现 Go 分布式锁，解决多实例并发竞争资源问题。
 | 原文链接：http://zhishi.hlitpm.asia/blog/7815499.sHtML

四、架构设计｜Architecture
原标题：排错：DockerCompose依赖顺序启动顺序坑
简介：golang mock 单元测试编写技巧，单元测试 mock 外部依赖，隔离数据库网络，只测试业务逻辑本身。
 | 原文链接：http://zhishi.hlitpm.asia/blog/8980455.sHtML

原标题：golang 系统设计覆盖索引减少回表查询实现
简介：消息队列重复消费业务处理，实现消息消费幂等，处理重复投递消息，保证多次消费业务结果一致。
 | 原文链接：http://zhishi.hlitpm.asia/blog/7878618.sHtML

原标题：手写简易 ORM 理解对象映射
简介：Git 代码冲突正确处理方式，讲解冲突产生场景，演示冲突文件修改，正确合并代码，防止代码丢失。
 | 原文链接：http://zhishi.hlitpm.asia/blog/4375459.sHtML

原标题：golang 系统设计日志采样降低存储开销方案
简介：golang channel 通道并发处理，讲解 Channel 用法，协程之间通过通道传递数据，做并发同步控制。
 | 原文链接：http://zhishi.hlitpm.asia/blog/7256648.sHtML

原标题：避坑：定时任务重复执行带来业务脏数据
简介：golang mqtt 客户端 go 开发物联网，paho.mqtt.golang 实现 mqtt 客户端，物联网设备消息收发。
 | 原文链接：http://zhishi.hlitpm.asia/blog/7811431.sHtML

原标题：部署复盘：容器OOM问题完整排查流程
简介：golang 信号捕获程序退出处理，Go 捕获操作系统信号，做资源回收，控制程序退出流程。
 | 原文链接：http://zhishi.hlitpm.asia/blog/1631170.sHtML

原标题：golang 系统设计 hot‑reload 热重载 go 开发工具
简介：接口签名校验防篡改实现，实现请求签名验签逻辑，校验请求参数未被篡改，提升接口调用安全性。
 | 原文链接：http://zhishi.hlitpm.asia/blog/9838355.sHtML

原标题：golang 系统设计请求签名校验完整方案
简介：rebase 操作防止代码丢失，讲解 rebase 风险点，操作前做好备份，规避错误操作造成代码提交丢失。
 | 原文链接：http://zhishi.hlitpm.asia/blog/2689018.sHtML

原标题：golang 系统设计 jwt 安全使用避坑要点
简介：ORM 隐式慢查询问题规避，识别 ORM 框架隐式查询，避免循环查询数据库，减少不必要慢 SQL 产生。
 | 原文链接：http://zhishi.hlitpm.asia/blog/4078415.sHtML

原标题：设计思考：系统容量评估架构前期估算思路
简介：golang go 项目依赖冲突解决完整思路，定位冲突包，replace、exclude、升级降级解决版本冲突。
 | 原文链接：http://zhishi.hlitpm.asia/blog/5070329.sHtML

原标题：快速入门日志打印与日志分级基础用法
简介：重复提交幂等防护再次讲解，梳理前端重复点击、网络重试场景，落地接口幂等，杜绝重复业务。
 | 原文链接：http://zhishi.hlitpm.asia/blog/2779583.sHtML

原标题：golang 系统设计网关鉴权鉴权转发流程讲解
简介：golang docker 镜像构建最佳实践，Go 项目 Docker 镜像构建最佳实践，减小镜像体积，安全构建。
 | 原文链接：http://zhishi.hlitpm.asia/blog/4356462.sHtML

原标题：Hands‑on：简易代理服务器开发实践
简介：前端打包分包加载提速方案，前端打包做代码分包，拆分大 bundle，页面按需加载，提升首屏加载速度。
 | 原文链接：http://zhishi.hlitpm.asia/blog/6232833.sHtML

原标题：golang 系统设计数据库查询优化完整流程
简介：axios 二次封装请求拦截处理，对 axios 做二次封装，统一请求拦截响应拦截，处理错误、token 自动刷新。
 | 原文链接：http://zhishi.hlitpm.asia/blog/2255439.sHtML

原标题：移动端适配 rem vw 方案对比
简介：Git commit 钩子提交规范校验，配置 Git 提交钩子，提交代码自动校验提交信息格式，规范提交记录。
 | 原文链接：http://zhishi.hlitpm.asia/blog/7540791.sHtML

原标题：安全实践：生产环境禁止开启debug调试模式
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://zhishi.hlitpm.asia/blog/9425864.sHtML

原标题：开发复盘：大JSON解析分批处理避免内存溢出
简介：golang go 比较运算符可比较类型，哪些类型可以直接 == 比较，map slice 函数不可直接比较。
 | 原文链接：http://zhishi.hlitpm.asia/blog/9940015.sHtML

原标题：运维笔记：备份策略数据库定时备份脚本
简介：golang 数据库连接耗尽排查思路，监控连接池状态，定位连接未归还，解决连接耗尽报错。
 | 原文链接：http://zhishi.hlitpm.asia/blog/4389940.sHtML

?
