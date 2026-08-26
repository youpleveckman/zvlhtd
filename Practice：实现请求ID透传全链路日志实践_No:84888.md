最新前沿技术资讯

一、入门教程｜Getting Started
原标题：Practice：实现请求ID透传全链路日志实践
简介：golang init 函数合理使用边界，少用 init，优先显式调用初始化，便于控制初始化时机。
 | 原文链接：http://wiki.t786yd.asia/arts/825665.Doc

原标题：架构笔记：分布式事务方案对比与业务取舍
简介：请求重试组件退避策略实现，封装重试组件，实现指数退避策略，避免大量请求同时重试压垮下游。
 | 原文链接：http://wiki.t786yd.asia/arts/167033.Doc

原标题：golang 空接口 interface 使用技巧
简介：golang 分布式事务 seata go 客户端，seata‑go 实现分布式事务，保证跨库业务数据最终一致性。
 | 原文链接：http://wiki.t786yd.asia/arts/436764.Doc

原标题：golang 系统设计混沌测试简单场景模拟实现
简介：golang trace 链路追踪 opentelemetry，opentelemetry 实现链路追踪，生成 traceId spanId，完整记录调用链路。
 | 原文链接：http://wiki.t786yd.asia/arts/891010.Doc

原标题：golang mysql 分表自增 id 方案
简介：golang 限制 multipart 内存大小，设置 MaxMemory，大文件写入磁盘临时文件防止内存暴涨。
 | 原文链接：http://wiki.t786yd.asia/arts/808728.Doc

原标题：golang 系统设计密钥轮换安全实践思路
简介：golang 数据库 ORM 框架选型对比，gorm xorm sqlx 对比各 ORM 优缺点，根据业务场景选型。
 | 原文链接：http://wiki.t786yd.asia/arts/185658.Doc

原标题：golang kafka offset 提交策略
简介：HTTP 状态码请求头完整梳理，汇总常用 HTTP 状态码与请求头含义，帮助快速看懂网络请求，排查接口通信问题。
 | 原文链接：http://wiki.t786yd.asia/arts/855997.Doc

原标题：入门实践：简单图片上传预览本地demo
简介：golang go 包循环导入报错解决，A 导入 B B 导入 A，循环导入报错，重构代码拆分包消除循环依赖。
 | 原文链接：http://wiki.t786yd.asia/arts/495710.Doc

原标题：磁盘 inode 耗尽文件创建失败
简介：golang go 程序运行时动态修改配置，运行时热加载配置结构体，原子更新保证并发读取安全。
 | 原文链接：http://wiki.t786yd.asia/arts/159824.Doc

原标题：单元测试用例编写入门实操
简介：golang 日志按日期切割实现方案，实现日志文件按天切割，自动归档旧日志，防止单个日志文件过大。
 | 原文链接：http://wiki.t786yd.asia/arts/637201.Doc

原标题：Hands‑on：编写shell健康检查自动重启脚本
简介：golang net.Listener 包装自定义监听器，包装 Listener 做连接计数、连接拦截，扩展网络能力。
 | 原文链接：http://wiki.t786yd.asia/arts/340838.Doc

原标题：golang redis 发布订阅简单示例
简介：上传接口跨域配置特殊适配，针对文件上传接口，适配复杂请求，修复上传场景下跨域失效问题。
 | 原文链接：http://wiki.t786yd.asia/arts/038965.Doc

原标题：项目实践：数据库慢日志采集分析落地实践
简介：nodejs 接口限流防刷代码实现，Node 层实现接口限流，限制 IP 访问频次，防护接口被恶意高频调用。
 | 原文链接：http://wiki.t786yd.asia/arts/317997.Doc

原标题：开发记录：服务优雅关闭释放资源完整实现
简介：golang 分布式锁 redis 实现，基于 Redis 实现 Go 分布式锁，解决多实例并发竞争资源问题。
 | 原文链接：http://wiki.t786yd.asia/arts/151658.Doc

原标题：接口幂等性防重复请求实现
简介：golang ctx 传递规则不要存结构体，context 作为函数参数传递，禁止放入结构体字段存储。
 | 原文链接：http://wiki.t786yd.asia/arts/019718.Doc

原标题：排错：前端sourcemap错误线上无法定位报错
简介：golang 服务注册 etcd 简单示例，etcd 实现服务注册发现，微服务实例注册元数据，客户端发现节点。
 | 原文链接：http://wiki.t786yd.asia/arts/570449.Doc

原标题：数据库主从延迟业务兼容处理
简介：golang kitex 字节微服务框架入门，kitex 开发 rpc 微服务，代码生成，服务注册发现完整流程。
 | 原文链接：http://wiki.t786yd.asia/arts/303110.Doc

原标题：AI实践：大模型生成代码后审查与重构实践
简介：数值类型溢出错乱问题修复，选择合适数值存储类型，处理数值溢出，避免数据存储错乱结果异常。
 | 原文链接：http://wiki.t786yd.asia/arts/558795.Doc

原标题：内存溢出问题现象识别排查
简介：分布式事务最终一致性实现，基于可靠消息实现最终一致性，解决跨数据库跨服务业务数据一致性。
 | 原文链接：http://wiki.t786yd.asia/arts/721157.Doc

原标题：Security：接口鉴权越权漏洞检测与修复
简介：golang context.WithTimeout 超时上下文，WithTimeout 设置超时时间，超时自动 cancel 释放协程。
 | 原文链接：http://wiki.t786yd.asia/arts/270571.Doc

原标题：调优方案：消息队列消费速度优化处理堆积
简介：nodejs 多进程任务分发处理，多进程拆分处理 CPU 密集任务，主进程分发任务，利用多核提升处理速度。
 | 原文链接：http://wiki.t786yd.asia/arts/818814.Doc

原标题：快速入门消息队列基础概念模型
简介：业务接口幂等完整落地案例，完整业务场景幂等落地示例，覆盖表单提交、回调、重试各类场景。
 | 原文链接：http://wiki.t786yd.asia/arts/034965.Doc

原标题：实战项目：HTTPS本地自签名证书配置实践
简介：项目语义化版本号规范管理，遵循语义化版本规范管理项目版本，明确主次版本变更含义。
 | 原文链接：http://wiki.t786yd.asia/arts/094331.Doc

原标题：Git 误删提交代码恢复找回
简介：容器内存扩容 OOM 被杀死修复，调高容器内存限制，优化程序内存占用，避免程序被 OOM 终止。
 | 原文链接：http://wiki.t786yd.asia/arts/462192.Doc

原标题：golang 系统设计 pre‑commit 钩子本地代码校验
简介：全局时间标准统一逻辑错乱修复，全服务统一使用同一时间标准，不要混用本地时间 UTC，修复时间逻辑 bug。
 | 原文链接：http://wiki.t786yd.asia/arts/333250.Doc

原标题：Issue：日志输出包含敏感信息造成泄露风险
简介：golang 系统信号信号量处理，Go 处理系统各类信号，SIGINT、SIGTERM，实现程序可控退出。
 | 原文链接：http://wiki.t786yd.asia/arts/415436.Doc

原标题：golang redis 布隆过滤器安装使用
简介：YAML 配置文件语法快速上手，讲解 YAML 基础语法、缩进规则，编写项目配置文件，规避语法错误引发程序异常。
 | 原文链接：http://wiki.t786yd.asia/arts/563170.Doc

原标题：ORM 隐式慢查询问题规避
简介：golang go 比较运算符可比较类型，哪些类型可以直接 == 比较，map slice 函数不可直接比较。
 | 原文链接：http://wiki.t786yd.asia/arts/491425.Doc

原标题：golang 数据库连接泄露排查
简介：golang 优雅处理 http 重定向逻辑，自定义控制 http 重定向跳转次数，防止无限重定向死循环。
 | 原文链接：http://wiki.t786yd.asia/arts/099692.Doc

原标题：方案对比：轮询长轮询WebSocket推送架构选型
简介：开发代理服务网络限制解决，搭建本地代理服务，解决开发环境网络访问受限，实现外部接口正常调用。
 | 原文链接：http://wiki.t786yd.asia/arts/798372.Doc

原标题：OAuth2 第三方登录服务搭建
简介：golang hertz http 框架快速上手，hertz 高性能 http 框架，路由中间件参数校验快速开发接口服务。
 | 原文链接：http://wiki.t786yd.asia/arts/323723.Doc

原标题：程序日志分级输出规范实践
简介：golang 灰度发布流量权重路由实现，根据权重切分流量，部分流量访问新版本服务，实现灰度发布。
 | 原文链接：http://wiki.t786yd.asia/arts/300053.Doc

原标题：架构复盘：服务灰度发布架构设计与流量切分
简介：前端打包分包加载提速方案，前端打包做代码分包，拆分大 bundle，页面按需加载，提升首屏加载速度。
 | 原文链接：http://wiki.t786yd.asia/arts/644963.Doc

原标题：架构笔记：批量任务系统架构防重复、断点续跑
简介：golang contract 契约测试微服务，微服务契约测试，保证接口变更不破坏调用方，提前发现兼容性问题。
 | 原文链接：http://wiki.t786yd.asia/arts/773516.Doc

原标题：效率笔记：Git高级命令日常开发高频使用汇总
简介：golang cobra 命令行参数配置绑定，cobra 绑定配置文件环境变量命令行参数，多源配置合并。
 | 原文链接：http://wiki.t786yd.asia/arts/832415.Doc

原标题：开发记录：实现完整用户登录鉴权业务模块
简介：golang jwt 令牌刷新逻辑实现，实现 JWT 双令牌机制，access 短期有效 refresh 刷新令牌，实现无感续期登录。
 | 原文链接：http://wiki.t786yd.asia/arts/461381.Doc

原标题：golang 优雅处理数据库事务
简介：nodejs 内存溢出问题排查修复，Node.js 程序 OOM 排查流程，定位内存泄露，调整内存限制修复崩溃。
 | 原文链接：http://wiki.t786yd.asia/arts/186015.Doc

原标题：OpenSource：开源项目风险评估依赖安全检查
简介：golang go 程序容器资源 requests limits，设置容器 cpu 内存配额，防止实例抢占集群资源，稳定调度。
 | 原文链接：http://wiki.t786yd.asia/arts/444216.Doc

原标题：golang 系统设计蓝绿发布滚动发布对比
简介：HTTPS 证书过期更新操作，检测 HTTPS 证书到期，更新证书文件，恢复 HTTPS 服务正常访问。
 | 原文链接：http://wiki.t786yd.asia/arts/020145.Doc

原标题：部署实践：多实例服务部署无状态改造
简介：不必要字符转义关闭业务异常，关闭多余自动转义逻辑，防止业务数据被错误转义，破坏原始数据。
 | 原文链接：http://wiki.t786yd.asia/arts/363048.Doc


二、踩坑排错｜Troubleshooting
原标题：架构复盘：数据库主从架构设计与延迟应对方案
简介：golang go 变量逃逸场景汇总，切片、指针、返回局部变量引发逃逸，变量分配到堆影响 GC。
 | 原文链接：http://wiki.t786yd.asia/arts/165205.Doc

原标题：方案对比：几种分布式限流算法架构适用性
简介：不必要字符转义关闭业务异常，关闭多余自动转义逻辑，防止业务数据被错误转义，破坏原始数据。
 | 原文链接：http://wiki.t786yd.asia/arts/382070.Doc

原标题：golang 系统设计集成测试环境准备清理实操
简介：golang 自定义 pprof 扩展业务指标，扩展 pprof，输出业务自定义指标，结合性能数据分析业务状态。
 | 原文链接：http://wiki.t786yd.asia/arts/462880.Doc

原标题：运维笔记：服务器故障排查常用命令清单
简介：golang tcp keepalive 参数程序配置，go 程序设置 tcp keepalive，操作系统 tcp 保活参数，清理僵死连接。
 | 原文链接：http://wiki.t786yd.asia/arts/800008.Doc

原标题：时间精度统一业务判断修复
简介：DNS TTL 配置域名切换生效，调整 DNS 解析 TTL，缩短缓存时间，域名变更后可以快速全网生效。
 | 原文链接：http://wiki.t786yd.asia/arts/610519.Doc

原标题：排错：多实例部署session共享失效登录失效
简介：golang go 项目依赖冲突解决完整思路，定位冲突包，replace、exclude、升级降级解决版本冲突。
 | 原文链接：http://wiki.t786yd.asia/arts/308322.Doc

原标题：golang 单元测试 table‑driven
简介：进程线程并发基础概念讲解，区分进程与线程，讲解调度逻辑，理解并发执行原理，为高并发业务开发打基础。
 | 原文链接：http://wiki.t786yd.asia/arts/208857.Doc

原标题：空指针异常判空容错处理
简介：golang 反向代理 http 服务开发，手写简易 http 反向代理，转发请求，修改请求头响应头。
 | 原文链接：http://wiki.t786yd.asia/arts/674984.Doc

原标题：系统时间同步定时任务偏移
简介：pnpm 包管理工具实战避坑指南，使用 pnpm 管理项目依赖，梳理常见坑点，充分利用 pnpm 优势。
 | 原文链接：http://wiki.t786yd.asia/arts/295199.Doc

原标题：golang redis pipeline 原子性说明
简介：golang 分布式唯一 id 多种方案对比，雪花、redis、uuid 对比各方案优缺点，指导业务选型使用。
 | 原文链接：http://wiki.t786yd.asia/arts/425111.Doc

原标题：新手指南：虚拟机WSL开发环境入门配置
简介：限流窗口绕过漏洞修复方案，修复限流时间窗口漏洞，避免攻击者绕过限流规则，保障接口防护有效。
 | 原文链接：http://wiki.t786yd.asia/arts/312751.Doc

原标题：golang 系统设计缓存优化落地实操指南
简介：golang go mod graph 查看依赖关系，go mod graph 打印依赖树，定位间接依赖来源，解决版本冲突。
 | 原文链接：http://wiki.t786yd.asia/arts/430470.Doc

原标题：性能复盘：系统上下文切换过高性能下降调优
简介：golang grpc 拦截器开发鉴权日志，开发 grpc 服务端拦截器，统一做鉴权、日志打印、异常捕获处理。
 | 原文链接：http://wiki.t786yd.asia/arts/208546.Doc

原标题：部署复盘：服务启动顺序依赖处理方案
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://wiki.t786yd.asia/arts/207195.Doc

原标题：实践：多配置文件合并加载组件实现
简介：golang https 客户端跳过证书校验，开发测试环境跳过 tls 证书校验，仅用于内网测试禁止生产使用。
 | 原文链接：http://wiki.t786yd.asia/arts/652916.Doc

原标题：入门实践：简易导出导入文件功能实现
简介：TCP 长连接参数优化 TIME_WAIT，调整 TCP 内核参数，优化长连接，减少大量 TIME_WAIT 连接占用资源。
 | 原文链接：http://wiki.t786yd.asia/arts/860822.Doc

原标题：快速入门WebSocket，实现简易双向通信demo
简介：接口幂等性防重复请求实现，实现接口幂等逻辑，避免重复提交请求产生多条脏数据，保障业务数据安全。
 | 原文链接：http://wiki.t786yd.asia/arts/317402.Doc

原标题：坑点：依赖缓存未更新，旧代码持续运行
简介：golang 定时任务任务持久化存储，定时任务持久化到数据库，服务重启任务不丢失，动态管理任务。
 | 原文链接：http://wiki.t786yd.asia/arts/091913.Doc

原标题：架构笔记：数据库读写分离架构数据不一致应对
简介：golang go‑zero 中间件鉴权限流，go‑zero 自定义中间件，实现鉴权、限流、日志打印通用能力。
 | 原文链接：http://wiki.t786yd.asia/arts/087853.Doc

原标题：golang docker 部署 kafka 本地调试
简介：golang 延迟队列实现方案对比，时间轮、redis zset 实现延迟队列，处理延时执行业务。
 | 原文链接：http://wiki.t786yd.asia/arts/612442.Doc

原标题：开发记录：表单参数校验统一中间件实现
简介：golang go 项目安全检查漏洞扫描，扫描 go 项目依赖漏洞，代码安全审计，规避安全风险。
 | 原文链接：http://wiki.t786yd.asia/arts/063914.Doc

原标题：调优方案：Web服务内核socket参数调优
简介：Nginx 缓冲区调优大文件上传，调大 Nginx 请求缓冲区，支持客户端上传大体积文件，避免上传被截断。
 | 原文链接：http://wiki.t786yd.asia/arts/984603.Doc

原标题：golang 系统设计大文件上传架构
简介：golang 进程信号捕获 SIGUSR 自定义信号，捕获用户自定义信号，实现线上不重启触发调试、日志切换。
 | 原文链接：http://wiki.t786yd.asia/arts/667058.Doc

原标题：轻量 API 后端接口服务快速开发
简介：golang gorm 软删除实现逻辑，Gorm 开启软删除，删除数据仅标记，数据保留可恢复，满足业务数据留存。
 | 原文链接：http://wiki.t786yd.asia/arts/034715.Doc

原标题：架构复盘：数据库索引架构设计原则与边界
简介：文件读写与异常捕获代码示例，演示文件读取写入操作，增加异常捕获逻辑，规避文件不存在、权限不足导致崩溃。
 | 原文链接：http://wiki.t786yd.asia/arts/902871.Doc

原标题：前端下载导出文件功能实现
简介：golang 表格驱动测试完整示例，表格驱动多组输入输出，批量执行测试用例，减少重复代码。
 | 原文链接：http://wiki.t786yd.asia/arts/756676.Doc

原标题：golang docker 运行 etcd 本地测试
简介：golang html 模板渲染简单示例，Go HTML 模板渲染，服务端渲染页面，填充数据输出 HTML 页面。
 | 原文链接：http://wiki.t786yd.asia/arts/876786.Doc

原标题：性能复盘：接口响应从800ms优化到50ms全过程
简介：环境变量不生效问题修复，排查环境变量加载顺序、作用域问题，修复环境变量读取不到的异常。
 | 原文链接：http://wiki.t786yd.asia/arts/598932.Doc

原标题：快速入门GraphQL基础查询语法示例
简介：golang 异步任务队列 worker 池开发，任务入数据库或 redis，worker 池消费执行，异步处理耗时业务。
 | 原文链接：http://wiki.t786yd.asia/arts/951259.Doc

原标题：golang docker volume 数据持久化
简介：golang socket 文件描述符继承重启，父进程传递 listener fd 给子进程，实现 go 程序零停机热重启。
 | 原文链接：http://wiki.t786yd.asia/arts/728739.Doc

原标题：golang 系统设计 grpc proto 接口设计原则
简介：golang go 信号处理优雅重启实现，USR2 触发程序重启，不关闭监听 socket 实现零停机升级。
 | 原文链接：http://wiki.t786yd.asia/arts/383691.Doc

原标题：golang mysql 连接泄漏检测方法
简介：Redis 热点 key 拆分降低集群压力，拆分访问量极高的热点 Key，分散请求压力，避免 Redis 节点压力过高。
 | 原文链接：http://wiki.t786yd.asia/arts/232590.Doc

原标题：开发记录：分布式ID生成器实现与压力测试
简介：golang net.Conn 包装自定义连接，包装 net.Conn，统计读写字节，日志打印，超时控制。
 | 原文链接：http://wiki.t786yd.asia/arts/966334.Doc

原标题：golang 系统设计 rest http 方法使用原则
简介：golang 日志按日期切割实现方案，实现日志文件按天切割，自动归档旧日志，防止单个日志文件过大。
 | 原文链接：http://wiki.t786yd.asia/arts/445066.Doc

原标题：磁盘占满服务不可用清理方案
简介：Git 仓库瘦身加快克隆下载速度，清理 Git 仓库历史大文件，缩减仓库体积，提升克隆拉取仓库速度。
 | 原文链接：http://wiki.t786yd.asia/arts/736886.Doc

原标题：Git 分支管理多人协作实战教程
简介：SourceMap 生成线上报错定位，项目打包生成 SourceMap 文件，线上报错可以还原源码，快速定位报错位置。
 | 原文链接：http://wiki.t786yd.asia/arts/414989.Doc

原标题：golang docker 部署 mongodb 开发环境
简介：DNS 解析异常第三方调用故障，排查 DNS 解析故障，修复域名解析，恢复第三方接口网络调用。
 | 原文链接：http://wiki.t786yd.asia/arts/347848.Doc

原标题：nodejs 多进程任务分发处理
简介：golang go‑zero 中间件鉴权限流，go‑zero 自定义中间件，实现鉴权、限流、日志打印通用能力。
 | 原文链接：http://wiki.t786yd.asia/arts/704720.Doc

原标题：方案对比：几种任务队列架构选型优缺点
简介：golang websocket 服务端开发，Go 实现 WebSocket 服务端，处理连接、消息收发，实现长连接服务。
 | 原文链接：http://wiki.t786yd.asia/arts/787130.Doc

原标题：Shell 脚本自动化命令编写
简介：golang prometheus client 业务埋点实操，prometheus client‑go 业务埋点，计数器、仪表盘、直方图指标开发。
 | 原文链接：http://wiki.t786yd.asia/arts/480130.Doc

三、实战开发｜Practice
原标题：nestjs 拦截器过滤器管道实战
简介：ICMP 放通网络丢包问题修复，放开 ICMP 协议，解决 MTU 问题导致网络丢包，修复网络不稳定现象。
 | 原文链接：http://wiki.t786yd.asia/arts/303065.Doc

原标题：Practice：简易限流器分布式版本Redis实现
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://wiki.t786yd.asia/arts/670782.Doc

原标题：实战项目：搭建本地Mock服务快速开发联调
简介：golang 错误静默忽略风险规避，禁止空忽略错误，必须处理或者明确注释为什么忽略错误。
 | 原文链接：http://wiki.t786yd.asia/arts/163475.Doc

原标题：golang 系统设计线程协程泄露定位方法
简介：项目依赖安全扫描漏洞防范，扫描项目第三方依赖包，修复存在安全漏洞依赖，防范供应链攻击。
 | 原文链接：http://wiki.t786yd.asia/arts/943404.Doc

原标题：运维笔记：服务器定时任务运维脚本编写
简介：golang 表格驱动测试完整示例，表格驱动多组输入输出，批量执行测试用例，减少重复代码。
 | 原文链接：http://wiki.t786yd.asia/arts/162854.Doc

原标题：golang kafka 监控指标简单梳理
简介：JWT 工具封装令牌刷新过期，封装 JWT 工具类，实现令牌生成、校验、过期刷新整套令牌管理逻辑。
 | 原文链接：http://wiki.t786yd.asia/arts/609351.Doc

原标题：分页逻辑错误数据漏查修复
简介：golang sort 搜索查找切片元素，sort.Search 二分查找有序切片，快速定位元素索引位置。
 | 原文链接：http://wiki.t786yd.asia/arts/254290.Doc

原标题：golang 系统设计定时任务动态启停配置方案
简介：代理 HTTPS 证书访问异常处理，配置代理根证书，解决代理环境 HTTPS 证书校验失败无法访问外网。
 | 原文链接：http://wiki.t786yd.asia/arts/223306.Doc

原标题：安全笔记：Git仓库密钥硬编码泄露处理方案
简介：golang minio 私有对象存储开发，minio s3 对象存储，bucket 管理，文件上传下载权限设置。
 | 原文链接：http://wiki.t786yd.asia/arts/324040.Doc

原标题：golang http 服务性能优化调参
简介：golang redis 事务 multi exec 使用，Redis 事务 multi exec 实现批量命令原子执行，理解 redis 事务隔离特性。
 | 原文链接：http://wiki.t786yd.asia/arts/464806.Doc

原标题：golang minio 对象存储接口开发
简介：golang ip 限流黑名单实现方案，基于 IP 做限流与黑名单，拦截恶意 IP 访问，保护接口服务。
 | 原文链接：http://wiki.t786yd.asia/arts/169911.Doc

原标题：golang 系统设计结构化日志字段规范约定
简介：golang context 取消传播机制，父 ctx 取消，所有派生子 context 全部被取消，理解上下文传播。
 | 原文链接：http://wiki.t786yd.asia/arts/182128.Doc

原标题：前端大文件分片上传完整方案
简介：golang benchmark 参数‑bench‑mem 统计内存分配，benchmark 开启内存统计，观察内存分配次数大小。
 | 原文链接：http://wiki.t786yd.asia/arts/753926.Doc

原标题：Performance：数据库分表解决单表过大性能衰减
简介：golang 进程信号捕获 SIGUSR 自定义信号，捕获用户自定义信号，实现线上不重启触发调试、日志切换。
 | 原文链接：http://wiki.t786yd.asia/arts/869635.Doc

原标题：Security：SSRF服务端请求伪造漏洞防御
简介：golang 大文件 HTTP 流式上传接收，服务端流式接收上传文件，不全部加载内存，防止大文件 OOM 崩溃。
 | 原文链接：http://wiki.t786yd.asia/arts/686483.Doc

原标题：排错：静态资源CDN缓存未刷新旧资源持续返回
简介：文件批量导入导出功能实现，开发批量导入导出接口，处理大量文件数据，完成业务数据批量迁移与导出。
 | 原文链接：http://wiki.t786yd.asia/arts/193384.Doc

原标题：golang docker volume 数据持久化
简介：golang docker compose 开发环境 go 服务，docker compose 编排 go 服务与中间件，本地一键拉起整套开发环境。
 | 原文链接：http://wiki.t786yd.asia/arts/156992.Doc

原标题：架构复盘：RPC框架架构超时重试设计要点
简介：golang 配置文件多格式兼容加载，同时支持 yaml toml json 多种格式配置文件，灵活适配不同部署环境。
 | 原文链接：http://wiki.t786yd.asia/arts/200877.Doc

原标题：nodejs 消息队列消费服务开发
简介：开发代理服务网络限制解决，搭建本地代理服务，解决开发环境网络访问受限，实现外部接口正常调用。
 | 原文链接：http://wiki.t786yd.asia/arts/853698.Doc

原标题：vue3 组合式 API 业务开发实战
简介：跨域偶现失败配置修复，解决跨域问题时而复现时而正常，定位配置漏配、请求头异常等隐性问题。
 | 原文链接：http://wiki.t786yd.asia/arts/529877.Doc

原标题：实践：Git工作流主干开发团队协作实践
简介：rebase 操作防止代码丢失，讲解 rebase 风险点，操作前做好备份，规避错误操作造成代码提交丢失。
 | 原文链接：http://wiki.t786yd.asia/arts/963526.Doc

原标题：golang redis 缓存预热实现思路
简介：golang pdf 生成 go 服务端生成 pdf，服务端动态生成 pdf 报表文件，直接输出下载给到前端。
 | 原文链接：http://wiki.t786yd.asia/arts/387927.Doc

原标题：golang k8s configmap secret 配置
简介：golang mongodb go 驱动实操教程，mongo‑go‑driver 操作 mongodb，文档增删改查聚合查询。
 | 原文链接：http://wiki.t786yd.asia/arts/422428.Doc

原标题：系统时间同步定时任务偏移
简介：Git 分支管理多人协作实战教程，详解分支创建、合并、冲突处理，适配团队开发场景，规范多人协同代码工作流。
 | 原文链接：http://wiki.t786yd.asia/arts/505074.Doc

原标题：实践：代码提交前自动格式化校验配置实践
简介：文件句柄上限调整上传随机失败，调高系统文件句柄上限，解决高并发上传场景随机打开文件失败。
 | 原文链接：http://wiki.t786yd.asia/arts/942014.Doc

原标题：Troubleshooting：防火墙安全组拦截访问请求
简介：express 请求参数校验处理，接入参数校验库，校验入参，拦截非法参数，提前拦截错误请求。
 | 原文链接：http://wiki.t786yd.asia/arts/055523.Doc

原标题：Performance：长连接管理优化减少连接重建开销
简介：HTTP 状态码请求头完整梳理，汇总常用 HTTP 状态码与请求头含义，帮助快速看懂网络请求，排查接口通信问题。
 | 原文链接：http://wiki.t786yd.asia/arts/098595.Doc

原标题：分布式锁失效问题排查修复
简介：golang 后端节点健康检查机制实现，定时探测后端节点状态，自动剔除故障节点，保障转发可用。
 | 原文链接：http://wiki.t786yd.asia/arts/221739.Doc

原标题：Troubleshooting：k8s镜像拉取失败镜像仓库网络问题
简介：golang 消息死信处理业务逻辑，Go 实现死信队列逻辑，消费失败消息转入死信，不阻塞正常消息队列。
 | 原文链接：http://wiki.t786yd.asia/arts/816646.Doc

原标题：golang 系统设计 mq 消息积压解决方案
简介：golang go 程序权限最小化运行，容器内使用普通用户运行程序，拒绝 root 运行提升安全等级。
 | 原文链接：http://wiki.t786yd.asia/arts/032815.Doc

原标题：浮点计算精度错误处理方案
简介：文件监控服务自动重启开发，监控项目文件变更，代码修改自动重启服务，提升本地开发调试效率。
 | 原文链接：http://wiki.t786yd.asia/arts/251412.Doc

原标题：golang kafka 死信队列业务落地
简介：golang 分库分表 id 路由规则设计，分库分表 id 路由算法，id 映射库表，数据均匀打散避免热点分片。
 | 原文链接：http://wiki.t786yd.asia/arts/949866.Doc

原标题：数据库分表存储大表优化方案
简介：Git 混乱提交历史清理方法，针对杂乱的提交记录，使用 Git 工具整理，清理无效提交，还原整洁版本历史。
 | 原文链接：http://wiki.t786yd.asia/arts/783456.Doc

原标题：golang 系统设计单元测试 mock 外部依赖技巧
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://wiki.t786yd.asia/arts/531752.Doc

原标题：项目实践：消息队列消息确认机制业务实践
简介：golang kafka 消费者位移管理，理解 kafka offset，手动提交位移，保证消息消费至少一次语义。
 | 原文链接：http://wiki.t786yd.asia/arts/521559.Doc

原标题：ServiceWorker 缓存页面更新清理
简介：全局时间标准统一逻辑错乱修复，全服务统一使用同一时间标准，不要混用本地时间 UTC，修复时间逻辑 bug。
 | 原文链接：http://wiki.t786yd.asia/arts/738561.Doc

原标题：CI 构建缓存加速编译速度
简介：接口请求重试容错机制实现，封装请求重试逻辑，遇到临时网络故障自动重试，提升第三方调用稳定性。
 | 原文链接：http://wiki.t786yd.asia/arts/901924.Doc

原标题：安全实践：生产环境禁止开启debug调试模式
简介：golang elasticsearch 客户端 golang 实操，es 客户端文档增删改查，条件搜索聚合统计对接搜索引擎。
 | 原文链接：http://wiki.t786yd.asia/arts/070401.Doc

原标题：零基础理解缓存基础原理与简单使用
简介：golang nats jetstream 持久消息队列，nats jetstream 持久化消息，保证消息不丢失，实现可靠消费。
 | 原文链接：http://wiki.t786yd.asia/arts/529574.Doc

原标题：Troubleshooting：防火墙安全组拦截访问请求
简介：golang json 自定义 MarshalJSON UnmarshalJSON，自定义 json 序列化反序列化逻辑，处理特殊格式字段。
 | 原文链接：http://wiki.t786yd.asia/arts/841898.Doc

四、架构设计｜Architecture
原标题：golang docker 网络模式桥接 host
简介：golang sftp 文件上传下载操作，sftp 协议远程文件上传下载，实现服务器之间文件传输功能。
 | 原文链接：http://wiki.t786yd.asia/arts/420750.Doc

原标题：记一次升级操作系统内核引发服务不稳定
简介：golang 程序崩溃 core dump 生成调试，开启 core dump，程序崩溃生成转储文件，事后分析崩溃原因。
 | 原文链接：http://wiki.t786yd.asia/arts/593730.Doc

原标题：golang 系统设计无锁编程思路简单示例
简介：golang go 锁竞争导致 CPU 飙升，识别锁竞争场景，减少锁粒度，优化并发逻辑降低 CPU 开销。
 | 原文链接：http://wiki.t786yd.asia/arts/790144.Doc

原标题：进程线程并发基础概念讲解
简介：golang fasthttp 服务开发完整示例，fasthttp 搭建 http 服务，路由、参数读取、响应返回完整业务。
 | 原文链接：http://wiki.t786yd.asia/arts/006812.Doc

原标题：排错：打包后资源路径，开发生产行为不一致
简介：golang 跨平台系统差异处理方案，处理 windows linux mac 路径、信号、文件权限差异，代码跨平台兼容。
 | 原文链接：http://wiki.t786yd.asia/arts/881423.Doc

原标题：部署实践：服务器防火墙安全组配置实践
简介：golang mongodb go 驱动实操教程，mongo‑go‑driver 操作 mongodb，文档增删改查聚合查询。
 | 原文链接：http://wiki.t786yd.asia/arts/472875.Doc

原标题：Architecture：静态资源分发CDN整体架构思路
简介：golang go 爬虫 robots 协议遵守，解析 robots.txt 规则，控制爬虫抓取范围，合规采集网页数据。
 | 原文链接：http://wiki.t786yd.asia/arts/611064.Doc

原标题：golang 系统设计消息大小限制业务处理方案
简介：golang 接口返回统一封装工具，封装 Go 接口统一返回工具，标准化成功失败返回结构体。
 | 原文链接：http://wiki.t786yd.asia/arts/931889.Doc

原标题：golang 接口请求日志记录中间件
简介：golang 数据库连接池参数调优详解，最大连接空闲连接最大生命周期，结合业务合理配置避免资源浪费。
 | 原文链接：http://wiki.t786yd.asia/arts/962797.Doc

原标题：golang 系统设计 rest http 方法使用原则
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://wiki.t786yd.asia/arts/150179.Doc

原标题：开发记录：文件锁实现多进程互斥实践
简介：golang gorm 事务手动回滚提交，手动控制事务流程，业务异常主动回滚，保障数据操作原子性。
 | 原文链接：http://wiki.t786yd.asia/arts/682211.Doc

原标题：坑点：缓存穿透，大量无效请求打穿数据库
简介：nodejs 进程间通信 IPC 实操，演示 Node.js 主进程子进程 IPC 通信，进程之间传递消息数据。
 | 原文链接：http://wiki.t786yd.asia/arts/994298.Doc

原标题：踩坑记录：CPU亲和配置不合理多核心负载不均
简介：集成测试业务流程编写示例，编写业务流程集成测试，覆盖完整业务链路，验证模块之间协同工作是否正常。
 | 原文链接：http://wiki.t786yd.asia/arts/300144.Doc

原标题：golang 系统设计 git 钩子自动化校验实现
简介：JSON XML 数据解析处理示例，演示两种格式数据解析与序列化，增加异常捕获，处理格式错乱导致解析失败。
 | 原文链接：http://wiki.t786yd.asia/arts/335478.Doc

原标题：golang 系统设计逻辑删除物理删除选型对比
简介：SDK 版本兼容线上崩溃修复，处理 SDK 版本升级之后线上崩溃，定位 API 变更，做版本兼容适配改造。
 | 原文链接：http://wiki.t786yd.asia/arts/375981.Doc

原标题：Architecture：BFF后端聚合层架构适用场景
简介：golang go 单二进制文件静态编译交叉编译，交叉编译不同操作系统架构二进制文件，实现一次编译多平台运行。
 | 原文链接：http://wiki.t786yd.asia/arts/118025.Doc

原标题：配置外部化线上部署防错误
简介：前端错误监控上报系统搭建，搭建前端错误监控，捕获页面 JS 错误，上报后端，快速发现线上页面 bug。
 | 原文链接：http://wiki.t786yd.asia/arts/706168.Doc

原标题：WebSocket 聊天室实时通讯开发
简介：golang go 信号处理优雅重启实现，USR2 触发程序重启，不关闭监听 socket 实现零停机升级。
 | 原文链接：http://wiki.t786yd.asia/arts/057547.Doc

?
