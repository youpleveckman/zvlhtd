最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang docker compose 完整语法
简介：golang jwt 令牌刷新逻辑实现，实现 JWT 双令牌机制，access 短期有效 refresh 刷新令牌，实现无感续期登录。
 | 原文链接：http://wiki.c1992c.asia/arts/411950.Doc

原标题：golang 系统设计压力测试性能测试执行流程
简介：golang 大内存分配 GC 抖动规避，避免瞬时大量对象创建，分批处理，防止 GC 抖动业务抖动。
 | 原文链接：http://wiki.c1992c.asia/arts/462106.Doc

原标题：新手指南：本地防火墙端口访问失败排查
简介：golang cgo 性能开销避坑指南，cgo 调用开销，减少频繁 cgo 调用，规避 cgo 带来内存泄漏风险。
 | 原文链接：http://wiki.c1992c.asia/arts/291377.Doc

原标题：API 大版本不兼容平滑迁移
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://wiki.c1992c.asia/arts/969009.Doc

原标题：踩坑记录：CPU亲和配置不合理多核心负载不均
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://wiki.c1992c.asia/arts/889101.Doc

原标题：golang kafka 生产者参数调优
简介：分布式 ID 全局唯一生成方案，讲解分布式 ID 生成思路，实现全局唯一 ID，满足分布式系统主键生成需求。
 | 原文链接：http://wiki.c1992c.asia/arts/371356.Doc

原标题：日志驱动异常日志不输出修复
简介：golang go 线上故障排查完整流程，CPU 高、内存上涨、接口超时、goroutine 泄露一套排查处理流程。
 | 原文链接：http://wiki.c1992c.asia/arts/015445.Doc

原标题：安全笔记：CSP内容安全策略配置实践
简介：开源项目构建失败排查步骤，梳理构建报错排查流程，从依赖、网络、权限、脚本多角度定位项目构建失败原因。
 | 原文链接：http://wiki.c1992c.asia/arts/307639.Doc

原标题：golang 系统设计锁优化减少竞争提升吞吐
简介：DNS TTL 配置域名切换生效，调整 DNS 解析 TTL，缩短缓存时间，域名变更后可以快速全网生效。
 | 原文链接：http://wiki.c1992c.asia/arts/834107.Doc

原标题：设计思考：系统容量评估架构前期估算思路
简介：golang 分布式追踪全链路日志打印，日志打印 traceId，各个服务日志可串联，排查跨服务调用问题。
 | 原文链接：http://wiki.c1992c.asia/arts/371659.Doc

原标题：性能笔记：线程池参数调优任务队列策略
简介：golang systemd 信号与优雅退出配合，systemd 停止服务发送 SIGTERM，go 程序捕获信号优雅关闭。
 | 原文链接：http://wiki.c1992c.asia/arts/126551.Doc

原标题：开发记录：JWT过期刷新滑动过期实现实践
简介：golang gorm 原生 SQL 执行处理，复杂场景执行原生 SQL，处理返回结果集，兼顾性能与灵活性。
 | 原文链接：http://wiki.c1992c.asia/arts/297985.Doc

原标题：从零搭建本地开发环境完整教程
简介：golang sync/atomic 原子操作使用注意，理解原子操作内存顺序，规避原子操作错误使用带来 bug。
 | 原文链接：http://wiki.c1992c.asia/arts/820840.Doc

原标题：大事务拆分防止连接池耗尽
简介：golang atomic 原子操作整数，atomic 加减比较交换，无锁更新整型变量，简单计数器场景。
 | 原文链接：http://wiki.c1992c.asia/arts/090693.Doc

原标题：坑点：npm/pip全局版本与项目本地版本冲突
简介：golang select 随机分支执行特性，多个 channel 就绪 select 随机选择，理解 select 行为特性。
 | 原文链接：http://wiki.c1992c.asia/arts/124981.Doc

原标题：golang 系统设计线上故障排查完整流程
简介：golang 分库分表简单路由实现，简易分表路由逻辑实现，根据分片 key 计算分片位置，数据路由写入。
 | 原文链接：http://wiki.c1992c.asia/arts/785221.Doc

原标题：开发复盘：大JSON解析分批处理避免内存溢出
简介：golang http 服务并发连接数限制，自定义 listener 统计连接数量，限制最大并发连接数保护服务。
 | 原文链接：http://wiki.c1992c.asia/arts/633829.Doc

原标题：开发测试生产多环境配置区分
简介：golang http body 必须关闭的重要性，无论成功失败必须关闭 request.Body，否则连接无法复用泄漏。
 | 原文链接：http://wiki.c1992c.asia/arts/417960.Doc

原标题：golang 单元测试 table‑driven
简介：数据库连接及时关闭连接泄漏，确保数据库连接使用完毕释放归还连接池，杜绝连接泄漏耗尽连接。
 | 原文链接：http://wiki.c1992c.asia/arts/028962.Doc

原标题：安全实践：SQL注入产生场景与完整防御手段
简介：golang os 环境变量读取设置，os.Getenv os.Setenv os.Unsetenv 读写环境变量，环境变量多值处理。
 | 原文链接：http://wiki.c1992c.asia/arts/696849.Doc

原标题：SourceMap 生成线上报错定位
简介：golang mongodb go 驱动实操教程，mongo‑go‑driver 操作 mongodb，文档增删改查聚合查询。
 | 原文链接：http://wiki.c1992c.asia/arts/260962.Doc

原标题：入门实战：搭建简易静态网页项目
简介：Git 子模块更新代码不全修复，正确更新 Git 子模块，拉取子模块完整代码，解决子模块目录为空问题。
 | 原文链接：http://wiki.c1992c.asia/arts/960292.Doc

原标题：排错：CI缓存策略错误，每次全量重新构建
简介：golang sync.Pool 对象池复用对象，sync.Pool 复用临时对象，减少内存分配，降低 GC 频率提升性能。
 | 原文链接：http://wiki.c1992c.asia/arts/244336.Doc

原标题：踩坑记录：文件描述符不足，上传功能随机失败
简介：SourceMap 生成线上报错定位，项目打包生成 SourceMap 文件，线上报错可以还原源码，快速定位报错位置。
 | 原文链接：http://wiki.c1992c.asia/arts/230129.Doc

原标题：坑点：Docker资源限制未设置导致宿主机卡死
简介：数据库死锁成因规避方案，讲解数据库死锁产生条件，给出业务层面规避手段，减少死锁事件发生。
 | 原文链接：http://wiki.c1992c.asia/arts/501362.Doc

原标题：Security：文件路径穿越漏洞完整防护
简介：系统字符集统一乱码修复，统一数据库、程序、操作系统字符集，解决中文乱码显示异常问题。
 | 原文链接：http://wiki.c1992c.asia/arts/276815.Doc

原标题：ORM 框架数据库增删改查实操
简介：CI 构建缓存加速编译速度，开启 CI 流水线依赖缓存，复用上一次构建依赖包，缩短流水线构建耗时。
 | 原文链接：http://wiki.c1992c.asia/arts/533907.Doc

原标题：golang git 提交信息规范校验
简介：调试工具断点调试变量查看技巧，演示断点设置、变量监视、调用栈查看，借助调试工具高效排查业务逻辑错误。
 | 原文链接：http://wiki.c1992c.asia/arts/964617.Doc

原标题：优化实践：内存池思想减少频繁分配释放
简介：golang 僵尸进程处理 go 程序，正确等待子进程退出，避免产生僵尸进程，占用系统进程表。
 | 原文链接：http://wiki.c1992c.asia/arts/020811.Doc

原标题：安全复盘：OAuth2授权流程安全坑点汇总
简介：新手参与开源社区贡献指南，介绍开源社区基础规则，讲解阅读 issue、提交 PR 流程，指导开发者参与开源贡献。
 | 原文链接：http://wiki.c1992c.asia/arts/418179.Doc

原标题：新手教程：gitstash暂存工作区变更实操
简介：golang recover 捕获 panic 使用边界，recover 只在 defer 内部生效，协程内部必须捕获本协程 panic。
 | 原文链接：http://wiki.c1992c.asia/arts/930945.Doc

原标题：golang 系统设计数据脱敏架构实现
简介：golang rate 令牌桶限流器源码理解，拆解令牌桶限流核心逻辑，理解令牌生成消耗，掌握限流底层原理。
 | 原文链接：http://wiki.c1992c.asia/arts/445007.Doc

原标题：nodejs 接口限流防刷代码实现
简介：golang grpc keepalive 保活配置，grpc keepalive 参数调优，检测断开僵死连接，释放无效连接资源。
 | 原文链接：http://wiki.c1992c.asia/arts/573603.Doc

原标题：DNS 解析异常第三方调用故障
简介：golang go‑zero rpc 微服务开发，go‑zero 定义 proto，生成 rpc 服务代码，实现微服务调用。
 | 原文链接：http://wiki.c1992c.asia/arts/293658.Doc

原标题：golang 系统设计故障定位排查通用步骤方法论
简介：磁盘 inode 耗尽文件创建失败，排查磁盘 inode 占用，清理大量小文件，恢复文件创建能力。
 | 原文链接：http://wiki.c1992c.asia/arts/379063.Doc

原标题：CI 流水线构建失败日志排查
简介：golang elasticsearch 客户端 golang 实操，es 客户端文档增删改查，条件搜索聚合统计对接搜索引擎。
 | 原文链接：http://wiki.c1992c.asia/arts/673339.Doc

原标题：效率笔记：终端开发工具提升日常调试效率
简介：golang contract 契约测试微服务，微服务契约测试，保证接口变更不破坏调用方，提前发现兼容性问题。
 | 原文链接：http://wiki.c1992c.asia/arts/755255.Doc

原标题：限流窗口绕过漏洞修复方案
简介：golang go 运行时获取编译信息，程序内部读取编译时间 git 版本，接口输出程序版本信息。
 | 原文链接：http://wiki.c1992c.asia/arts/525645.Doc

原标题：TCP 长连接参数优化 TIME_WAIT
简介：golang 自定义 pprof 扩展业务指标，扩展 pprof，输出业务自定义指标，结合性能数据分析业务状态。
 | 原文链接：http://wiki.c1992c.asia/arts/705287.Doc

原标题：SSH 密钥配置 GitHub 免密登录
简介：新手快速上手 Git 版本控制实操指南，讲解 Git 基础概念与常用命令，结合实操案例，帮助零基础用户掌握版本控制核心能力。
 | 原文链接：http://wiki.c1992c.asia/arts/856584.Doc


二、踩坑排错｜Troubleshooting
原标题：零基础理解版本控制核心概念与工作流
简介：Nginx 缓冲区调优大文件上传，调大 Nginx 请求缓冲区，支持客户端上传大体积文件，避免上传被截断。
 | 原文链接：http://wiki.c1992c.asia/arts/726860.Doc

原标题：开发复盘：百万数据批量导入数据库优化方案
简介：golang grpc 负载均衡客户端实现，grpc 客户端负载均衡，轮询随机权重，分发请求到多个服务实例。
 | 原文链接：http://wiki.c1992c.asia/arts/857112.Doc

原标题：golang minio 分片上传断点续传
简介：golang 项目目录分层规范设计，Go 后端项目目录分层规范，按领域分层，提高项目可读性可维护性。
 | 原文链接：http://wiki.c1992c.asia/arts/078530.Doc

原标题：golang 系统设计数据库索引设计方法论
简介：golang http3 quic 客户端服务端示例，go 实现 http3 quic 服务端客户端，体验 quic 协议低延迟特性。
 | 原文链接：http://wiki.c1992c.asia/arts/660327.Doc

原标题：golang 系统设计 e2e 端到端测试简单落地思路
简介：gRPC 服务端客户端入门示例，搭建 gRPC 服务端与调用客户端，学习 protobuf 定义，掌握 RPC 基础开发流程。
 | 原文链接：http://wiki.c1992c.asia/arts/423432.Doc

原标题：调优方案：Docker容器内核参数性能调优
简介：golang 配置热更新不重启服务，实现配置热加载，监听配置变更，更新内存配置，无需重启服务实例。
 | 原文链接：http://wiki.c1992c.asia/arts/104103.Doc

原标题：快速入门容器基础概念，理解镜像与容器
简介：golang redis pipeline 与 txpipeline 区别，区分普通管道与事务管道，根据业务场景选择合适批量执行方案。
 | 原文链接：http://wiki.c1992c.asia/arts/271877.Doc

原标题：golang redis 持久化 RDB AOF 对比
简介：golang http 中间件洋葱模型原理，理解 go http 中间件洋葱模型，请求响应流转顺序，编写自定义中间件。
 | 原文链接：http://wiki.c1992c.asia/arts/451122.Doc

原标题：开发记录：业务错误告警邮件通知组件实践
简介：golang 配置中心 apollo go 客户端，apollo go sdk 读取配置，配置变更自动热更新无需重启服务。
 | 原文链接：http://wiki.c1992c.asia/arts/112348.Doc

原标题：排错：内网域名解析不稳定导致服务随机报错
简介：文件监控服务自动重启开发，监控项目文件变更，代码修改自动重启服务，提升本地开发调试效率。
 | 原文链接：http://wiki.c1992c.asia/arts/095878.Doc

原标题：git rebase 整理提交历史实操
简介：golang 延迟队列实现方案对比，时间轮、redis zset 实现延迟队列，处理延时执行业务。
 | 原文链接：http://wiki.c1992c.asia/arts/023566.Doc

原标题：DevOps：私有镜像仓库搭建与权限管控
简介：内存广播本地进程消息通知，实现进程内内存消息广播，进程内部模块之间事件通知解耦。
 | 原文链接：http://wiki.c1992c.asia/arts/718377.Doc

原标题：golang 内存 pprof 定位内存泄漏
简介：golang icmp ping 程序实现，go 实现 ping 工具发送 icmp 报文，检测网络连通性。
 | 原文链接：http://wiki.c1992c.asia/arts/719036.Doc

原标题：golang 系统设计 http3 quic 简单原理了解
简介：golang context 超时取消实战案例，使用 context 控制协程、http 请求超时，自动终止超时任务，避免协程无限阻塞。
 | 原文链接：http://wiki.c1992c.asia/arts/384635.Doc

原标题：golang 系统设计时间字段选型 datetime timestamp
简介：GET POST 接口请求参数处理，讲解两种请求方式参数传递区别，演示参数接收、解析、校验，适配不同接口调用场景。
 | 原文链接：http://wiki.c1992c.asia/arts/967283.Doc

原标题：Shell 运维脚本服务器效率提升
简介：服务器时钟同步任务错乱修复，配置服务器 NTP 时间同步，保证集群所有机器时间保持一致。
 | 原文链接：http://wiki.c1992c.asia/arts/457475.Doc

原标题：OpenSource：开源项目许可证License选型指南
简介：golang prometheus 指标埋点开发，业务埋点计数器、仪表盘、直方图，对接 prometheus 采集监控指标。
 | 原文链接：http://wiki.c1992c.asia/arts/907363.Doc

原标题：Troubleshoot：磁盘打满导致服务全部不可用
简介：Redis 热点 key 拆分降低集群压力，拆分访问量极高的热点 Key，分散请求压力，避免 Redis 节点压力过高。
 | 原文链接：http://wiki.c1992c.asia/arts/934977.Doc

原标题：golang 系统设计单元测试表驱动测试 table‑driven
简介：golang mongodb 索引优化慢查询处理，mongodb 创建索引，分析慢查询，优化聚合查询执行性能。
 | 原文链接：http://wiki.c1992c.asia/arts/826181.Doc

原标题：开发复盘：海量日志轮转清理脚本实践
简介：golang html 模板渲染简单示例，Go HTML 模板渲染，服务端渲染页面，填充数据输出 HTML 页面。
 | 原文链接：http://wiki.c1992c.asia/arts/094629.Doc

原标题：golang traceId spanId 传递方案
简介：golang wasm 浏览器 js 交互，go wasm 与 js 互相调用，浏览器端 go 程序操作 dom 调用 js 函数。
 | 原文链接：http://wiki.c1992c.asia/arts/615425.Doc

原标题：方案设计：统一错误处理架构全链路方案
简介：网关超时时间调优后端等待，调大网关向后端转发请求超时时间，给后端业务充足处理时间。
 | 原文链接：http://wiki.c1992c.asia/arts/264358.Doc

原标题：线上故障：热点Key打满RedisCPU节点过载
简介：golang lru 缓存淘汰算法编写，手写 LRU 缓存淘汰算法，实现本地缓存，淘汰最久未使用数据。
 | 原文链接：http://wiki.c1992c.asia/arts/568788.Doc

原标题：CI 持续集成自动构建流程
简介：golang gzip 压缩 http 响应，服务端开启 gzip 压缩，减小接口响应体积，降低网络传输耗时。
 | 原文链接：http://wiki.c1992c.asia/arts/387755.Doc

原标题：golang 系统设计 cpu 瓶颈定位优化方案
简介：golang redis 过期时间处理技巧，设置 key 过期，监控过期事件，基于过期特性实现业务缓存逻辑。
 | 原文链接：http://wiki.c1992c.asia/arts/123689.Doc

原标题：手写简易 ORM 理解对象映射
简介：Git 误删提交代码恢复找回，使用 Git reflog 工具找回被误删除提交记录，恢复误删除代码。
 | 原文链接：http://wiki.c1992c.asia/arts/432684.Doc

原标题：golang 系统设计分布式锁红锁优缺点梳理
简介：端口占用访问失败排查方案，讲解端口占用排查命令，定位占用进程，释放端口，解决服务启动端口被占用报错。
 | 原文链接：http://wiki.c1992c.asia/arts/560738.Doc

原标题：记一次第三方回调IP变动未更新防火墙拦截
简介：golang context.Background 与 TODO 区别，Background 主流程根上下文，TODO 不确定用哪个上下文时使用。
 | 原文链接：http://wiki.c1992c.asia/arts/746084.Doc

原标题：golang 系统设计 protobuf 枚举类型规范写法
简介：golang go 服务日志输出 journald，systemd journald 接收程序 stdout 日志，统一管理服务日志。
 | 原文链接：http://wiki.c1992c.asia/arts/411714.Doc

原标题：Performance：数据库join优化，大表join规避
简介：限流规则误拦截正常请求修复，修正限流规则阈值，避免合法用户被限流拦截，兼顾防护与可用性。
 | 原文链接：http://wiki.c1992c.asia/arts/079358.Doc

原标题：Performance：缓存策略优化，降低数据库压力
简介：golang io.LimitReader 限制读取字节数，LimitReader 限制最大读取，防止读取超大数据。
 | 原文链接：http://wiki.c1992c.asia/arts/456615.Doc

原标题：golang 系统设计 cpu 高占用排查步骤
简介：golang tcp_NODELAY 关闭延迟发送，设置 tcp_NODELAY，关闭 Nagle 算法，降低小包请求延迟。
 | 原文链接：http://wiki.c1992c.asia/arts/636699.Doc

原标题：golang 系统设计字符串拼接性能优化技巧
简介：golang http 重定向策略自定义，CheckRedirect 自定义重定向逻辑，限制重定向次数，防止死循环。
 | 原文链接：http://wiki.c1992c.asia/arts/271982.Doc

原标题：golang 系统设计 go netpoll 多路复用简单理解
简介：golang gorm 预加载关联查询优化，GORM 预加载关联数据，避免 N+1 查询问题，提升数据库查询性能。
 | 原文链接：http://wiki.c1992c.asia/arts/555685.Doc

原标题：CI 流水线超时时间延长配置
简介：golang go 程序守护进程实现思路，go 程序不做 daemon 化，依靠 systemd pm2 k8s 实现进程守护。
 | 原文链接：http://wiki.c1992c.asia/arts/271737.Doc

原标题：golang 系统设计网关性能压测优化简单思路
简介：跨库查询性能优化处理，减少跨库关联查询，做数据冗余或者中间表，规避跨库查询性能低下。
 | 原文链接：http://wiki.c1992c.asia/arts/041588.Doc

原标题：实战项目：GitHubAction自动测试构建实践
简介：golang http client 全局变量复用，http Client 不要每次请求新建，复用 Transport 提升性能。
 | 原文链接：http://wiki.c1992c.asia/arts/318199.Doc

原标题：开发复盘：消息队列消息顺序性业务落地实践
简介：Mock 接口服务快速搭建实操，搭建模拟后端接口，自定义返回数据、延迟响应，前端开发阶段无需依赖真实后端服务。
 | 原文链接：http://wiki.c1992c.asia/arts/796369.Doc

原标题：golang 系统设计消息 key 选择保证顺序性方案
简介：批量异步处理系统业务落地，构建批量异步处理系统，把耗时业务异步化，提升接口响应速度。
 | 原文链接：http://wiki.c1992c.asia/arts/507906.Doc

原标题：接口压测定位系统性能瓶颈
简介：开源项目构建失败排查步骤，梳理构建报错排查流程，从依赖、网络、权限、脚本多角度定位项目构建失败原因。
 | 原文链接：http://wiki.c1992c.asia/arts/767000.Doc

三、实战开发｜Practice
原标题：golang mock 单元测试编写技巧
简介：react hooks 常见陷阱避坑指南，梳理 React Hooks 高频踩坑点，依赖数组、闭包陷阱，写出稳定组件。
 | 原文链接：http://wiki.c1992c.asia/arts/969552.Doc

原标题：Troubleshooting：数据库主从延迟带来查询数据不一致
简介：golang 漏桶算法实现接口限流，漏桶算法控制请求流出速率，平滑突发流量，削平流量峰值。
 | 原文链接：http://wiki.c1992c.asia/arts/186202.Doc

原标题：架构复盘：服务灰度发布架构设计与流量切分
简介：golang 优雅处理数据库事务，Go 数据库事务封装，正确处理事务提交回滚，保证业务数据一致性。
 | 原文链接：http://wiki.c1992c.asia/arts/499944.Doc

原标题：从零学习基础的接口请求与参数处理
简介：golang errgroup 协程组错误处理，errgroup 捕获协程错误，context 取消剩余协程，简化并发任务。
 | 原文链接：http://wiki.c1992c.asia/arts/152277.Doc

原标题：Hands‑on：简易图片压缩处理服务demo
简介：前端国际化多语言方案落地，搭建前端多语言国际化方案，切换语言，页面文本自动切换对应语种。
 | 原文链接：http://wiki.c1992c.asia/arts/758570.Doc

原标题：golang 系统设计压测指标确定与分析
简介：Docker 多阶段构建镜像瘦身，使用 Docker 多阶段构建，剔除编译阶段依赖，产出体积更小运行镜像。
 | 原文链接：http://wiki.c1992c.asia/arts/041340.Doc

原标题：golang mysql 悲观锁乐观锁实现
简介：编译打包产物依赖分析解读，分析打包之后产物组成，理清运行依赖文件，排查打包后缺失文件问题。
 | 原文链接：http://wiki.c1992c.asia/arts/277760.Doc

原标题：实战：Redis管道批量操作性能优化实践
简介：golang csv 百万级数据导入数据库，流式读取 csv 分批写入数据库，避免一次性加载全部数据。
 | 原文链接：http://wiki.c1992c.asia/arts/537430.Doc

原标题：golang 系统设计分表分页排序业务实现难点
简介：TLS 版本兼容 HTTPS 握手失败，兼容老旧 TLS 协议版本，修复部分客户端 HTTPS 握手失败无法访问。
 | 原文链接：http://wiki.c1992c.asia/arts/482124.Doc

原标题：复盘总结：技术选型对比文档模板实践
简介：golang redis pipeline 与 txpipeline 区别，区分普通管道与事务管道，根据业务场景选择合适批量执行方案。
 | 原文链接：http://wiki.c1992c.asia/arts/200175.Doc

原标题：项目实践：数据库慢日志采集分析落地实践
简介：golang net.Conn 包装自定义连接，包装 net.Conn，统计读写字节，日志打印，超时控制。
 | 原文链接：http://wiki.c1992c.asia/arts/523678.Doc

原标题：golang kafka 同步异步消费对比
简介：golang go mod graph 可视化依赖图，可视化 go 依赖关系，直观看到包之间依赖，定位冲突。
 | 原文链接：http://wiki.c1992c.asia/arts/609923.Doc

原标题：golang es 批量 bulk 操作性能调优
简介：golang net.Listener 包装自定义监听器，包装 Listener 做连接计数、连接拦截，扩展网络能力。
 | 原文链接：http://wiki.c1992c.asia/arts/752661.Doc

原标题：golang mysql 防止 sql 注入实践
简介：环境变量不生效问题修复，排查环境变量加载顺序、作用域问题，修复环境变量读取不到的异常。
 | 原文链接：http://wiki.c1992c.asia/arts/252775.Doc

原标题：golang mysql 时间类型选型避坑
简介：Docker 容器入门镜像实操教程，介绍 Docker 基础概念，演示镜像拉取、容器启停，帮助新手建立容器化开发认知。
 | 原文链接：http://wiki.c1992c.asia/arts/904285.Doc

原标题：golang mysql 连接泄漏检测方法
简介：前端虚拟列表大数据渲染优化，实现虚拟滚动列表，只渲染可视区域 DOM，上万条数据页面流畅渲染。
 | 原文链接：http://wiki.c1992c.asia/arts/306294.Doc

原标题：磁盘占满服务不可用清理方案
简介：golang 接口限流中间件开发，Gin 开发限流中间件，接口层实现访问频率限制，防护接口流量。
 | 原文链接：http://wiki.c1992c.asia/arts/646705.Doc

原标题：golang 配置文件多环境加载
简介：golang prometheus client 业务埋点实操，prometheus client‑go 业务埋点，计数器、仪表盘、直方图指标开发。
 | 原文链接：http://wiki.c1992c.asia/arts/210726.Doc

原标题：Hands‑on：简易的事件订阅发布组件开发实践
简介：golang 数据库慢查询监控实现，Go 封装 SQL 执行监控，记录慢 SQL，上报日志，发现数据库性能问题。
 | 原文链接：http://wiki.c1992c.asia/arts/531461.Doc

原标题：安全实践：容器最小化镜像减少攻击面
简介：提交第一个开源 PR 完整流程，Fork 项目、修改代码、提交 Pull Request，讲解 PR 规范，提升合并通过率。
 | 原文链接：http://wiki.c1992c.asia/arts/622982.Doc

原标题：安全实践：SQL注入产生场景与完整防御手段
简介：golang gin 路由动态注册实现方案，根据配置动态注册接口路由，无需硬编码路由，适配动态业务模块。
 | 原文链接：http://wiki.c1992c.asia/arts/909506.Doc

原标题：golang 系统设计回调签名校验防伪造实现
简介：golang 数据库慢查询监控实现，Go 封装 SQL 执行监控，记录慢 SQL，上报日志，发现数据库性能问题。
 | 原文链接：http://wiki.c1992c.asia/arts/561279.Doc

原标题：golang 系统设计缓存预热脚本编写实操
简介：Git 分支切换合并删除完整操作，实操分支全生命周期操作，包含切换、合并、删除，熟悉日常开发分支处理流程。
 | 原文链接：http://wiki.c1992c.asia/arts/236822.Doc

原标题：nodejs http 服务性能调优实战
简介：nestjs 权限守卫鉴权实现方案，使用 Nest 守卫实现接口鉴权，角色权限控制，拦截未授权接口访问。
 | 原文链接：http://wiki.c1992c.asia/arts/892215.Doc

原标题：新手指南：读懂项目构建脚本作用
简介：极简 API 网关路由转发实现，开发极简网关服务，完成请求路由转发，理解网关基础实现原理。
 | 原文链接：http://wiki.c1992c.asia/arts/196024.Doc

原标题：Security：反序列化漏洞风险识别与规避
简介：Shell 脚本自动化命令编写，讲解 Shell 基础语法，编写自动化脚本，完成批量执行、文件处理，解放重复手工操作。
 | 原文链接：http://wiki.c1992c.asia/arts/556379.Doc

原标题：从零学习简单分页逻辑实现思路
简介：golang go 程序 CPU 占用高定位步骤，pprof 定位热点函数，分析 CPU 高占用，优化耗时代码逻辑。
 | 原文链接：http://wiki.c1992c.asia/arts/054937.Doc

原标题：golang k8s liveness readiness 探针
简介：文件描述符优化进程卡死修复，及时关闭文件句柄，控制打开文件数量，解决文件句柄耗尽进程卡死。
 | 原文链接：http://wiki.c1992c.asia/arts/378049.Doc

原标题：项目实践：定时任务防重复执行落地实践
简介：接口签名校验防篡改实现，实现请求签名验签逻辑，校验请求参数未被篡改，提升接口调用安全性。
 | 原文链接：http://wiki.c1992c.asia/arts/950696.Doc

原标题：golang 系统设计 rest 分页排序过滤参数规范
简介：从零编写简易 CLI 命令行工具，通过实战案例实现基础命令交互，理解命令行程序执行逻辑，产出可运行小工具。
 | 原文链接：http://wiki.c1992c.asia/arts/275568.Doc

原标题：运维笔记：系统文件句柄数调整生产配置
简介：golang go 信号处理优雅重启实现，USR2 触发程序重启，不关闭监听 socket 实现零停机升级。
 | 原文链接：http://wiki.c1992c.asia/arts/907634.Doc

原标题：Architecture：API网关核心能力与组件拆分
简介：nodejs 脚手架工具开发完整教程，从零开发 Node 命令行脚手架，实现项目模板生成，理解 CLI 开发。
 | 原文链接：http://wiki.c1992c.asia/arts/818338.Doc

原标题：项目实践：搭建个人API网关最小实现版本
简介：golang gitlab ci go 项目流水线编写，gitlab ci 流水线执行单元测试、静态检查、构建推送镜像。
 | 原文链接：http://wiki.c1992c.asia/arts/571216.Doc

原标题：golang 系统设计基准测试 benchmark 编写
简介：极简方式搭建个人技术文档站点，使用轻量化工具快速部署文档站点，支持 markdown 编写，实现知识沉淀与对外分享。
 | 原文链接：http://wiki.c1992c.asia/arts/026841.Doc

原标题：效率笔记：GitWorkflow团队协作规范模板
简介：大文件导出内存溢出防护，流式处理大文件导出，边读边写，不把全部数据加载内存，规避 OOM。
 | 原文链接：http://wiki.c1992c.asia/arts/129860.Doc

原标题：golang 系统设计架构图绘制规范简单建议
简介：前端下载导出文件功能实现，前端实现文件流下载导出，处理异常，适配浏览器不同下载行为。
 | 原文链接：http://wiki.c1992c.asia/arts/539572.Doc

原标题：golang mysql 慢查询日志开启分析
简介：文件读写与异常捕获代码示例，演示文件读取写入操作，增加异常捕获逻辑，规避文件不存在、权限不足导致崩溃。
 | 原文链接：http://wiki.c1992c.asia/arts/026478.Doc

原标题：从零学习简单分布式ID生成思路
简介：nodejs 中间件模式原理剖析，拆解 Node 中间件设计模式，理解请求逐层处理流转的底层原理。
 | 原文链接：http://wiki.c1992c.asia/arts/084987.Doc

原标题：Performance：大事务拆分，减少锁持有时间
简介：内存溢出问题现象识别排查，识别内存溢出现象，梳理排查方向，定位内存持续上涨引发服务崩溃问题。
 | 原文链接：http://wiki.c1992c.asia/arts/233524.Doc

原标题：Troubleshoot：MySQL字符集utf8非utf8mb4emoji报错
简介：golang nats jetstream 持久消息队列，nats jetstream 持久化消息，保证消息不丢失，实现可靠消费。
 | 原文链接：http://wiki.c1992c.asia/arts/526011.Doc

四、架构设计｜Architecture
原标题：Practice：实现接口签名、验签完整示例代码
简介：多实例部署 Session 共享方案，多服务实例部署场景，实现 Session 共享，保证用户登录状态跨实例生效。
 | 原文链接：http://wiki.c1992c.asia/arts/175223.Doc

原标题：Issue：文件句柄耗尽，服务缓慢卡死复盘
简介：nodejs 消息队列消费服务开发，Node 开发消息队列消费端，监听队列消息执行业务逻辑，异步解耦业务。
 | 原文链接：http://wiki.c1992c.asia/arts/254155.Doc

原标题：依赖安装失败全方位排错
简介：golang docker compose 开发环境 go 服务，docker compose 编排 go 服务与中间件，本地一键拉起整套开发环境。
 | 原文链接：http://wiki.c1992c.asia/arts/447610.Doc

原标题：线上异常：布隆过滤器误判造成业务逻辑异常
简介：静态博客部署 GitHub Pages 教程，将静态博客项目部署至 GitHub Pages，完成线上访问，快速搭建个人技术博客站点。
 | 原文链接：http://wiki.c1992c.asia/arts/971266.Doc

原标题：Dockerfile 编写容器打包实战
简介：golang grpc 负载均衡客户端实现，grpc 客户端负载均衡，轮询随机权重，分发请求到多个服务实例。
 | 原文链接：http://wiki.c1992c.asia/arts/462069.Doc

原标题：坑点：gitreset误删本地代码恢复方案
简介：新手参与开源社区贡献指南，介绍开源社区基础规则，讲解阅读 issue、提交 PR 流程，指导开发者参与开源贡献。
 | 原文链接：http://wiki.c1992c.asia/arts/890929.Doc

原标题：golang 系统设计内存瓶颈定位优化思路
简介：golang 单元测试 table‑driven，表格驱动单元测试写法，批量输入多组测试用例，简化单元测试代码。
 | 原文链接：http://wiki.c1992c.asia/arts/133039.Doc

原标题：方案对比：几种任务队列架构选型优缺点
简介：golang embed 目录读取文件列表，embed 嵌入整个目录，读取目录下全部文件，做静态资源服务。
 | 原文链接：http://wiki.c1992c.asia/arts/105600.Doc

原标题：多环境配置中心灵活切换方案
简介：golang trace 链路追踪 opentelemetry，opentelemetry 实现链路追踪，生成 traceId spanId，完整记录调用链路。
 | 原文链接：http://wiki.c1992c.asia/arts/699037.Doc

原标题：全局时间标准统一逻辑错乱修复
简介：golang atomic.Value 存储任意类型数据，atomic.Value 安全存储读取任意类型，配置热更新常用。
 | 原文链接：http://wiki.c1992c.asia/arts/492957.Doc

原标题：复盘总结：技术选型对比文档模板实践
简介：异步编程 Promise 执行流程解析，拆解异步执行顺序，理解回调与 Promise 差异，理清异步场景下代码执行逻辑。
 | 原文链接：http://wiki.c1992c.asia/arts/231952.Doc

原标题：golang 系统设计告警渠道钉钉邮件企业微信集成
简介：磁盘占满服务不可用清理方案，定位磁盘占用大文件，清理日志、缓存文件，恢复磁盘可用空间。
 | 原文链接：http://wiki.c1992c.asia/arts/827282.Doc

原标题：零基础理解幂等性基础概念与场景
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：http://wiki.c1992c.asia/arts/450962.Doc

原标题：后端分页查询逻辑代码实现
简介：程序信号中断退出处理逻辑，捕获系统中断信号，执行资源释放、关闭连接，实现程序优雅退出。
 | 原文链接：http://wiki.c1992c.asia/arts/553795.Doc

原标题：golang 系统设计分库分表本地测试调试技巧
简介：nodejs 接口限流防刷代码实现，Node 层实现接口限流，限制 IP 访问频次，防护接口被恶意高频调用。
 | 原文链接：http://wiki.c1992c.asia/arts/295808.Doc

原标题：前端打包分包加载提速方案
简介：手写简易 RPC 服务通信原型，手写极简 RPC 原型，理解服务注册、网络传输、方法调用底层逻辑。
 | 原文链接：http://wiki.c1992c.asia/arts/315206.Doc

原标题：极简 API 网关路由转发实现
简介：golang kafka 同步异步消费对比，对比 Kafka 同步消费异步消费，分析优缺点，业务选型参考。
 | 原文链接：http://wiki.c1992c.asia/arts/155579.Doc

原标题：开发记录：表单文件类型校验后端安全校验实践
简介：golang 性能压测 wr 工具实操指南，wr 压测工具对 Go 接口压测，观察 QPS 延迟，定位接口性能瓶颈。
 | 原文链接：http://wiki.c1992c.asia/arts/266252.Doc

?
