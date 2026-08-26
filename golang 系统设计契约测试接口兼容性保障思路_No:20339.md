最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计契约测试接口兼容性保障思路
简介：golang 日志 zap 结构化日志实践，接入 Zap 结构化日志库，打印结构化日志，方便日志检索解析。
 | 原文链接：http://wiki.x06jfh.asia/arts/111438.Doc

原标题：nodejs http 服务性能调优实战
简介：golang race 检测器性能开销，race 检测器有性能损耗，只用于测试环境，禁止生产开启 race。
 | 原文链接：http://wiki.x06jfh.asia/arts/041026.Doc

原标题：集成测试业务流程编写示例
简介：golang pprof 线上采集性能数据，线上环境采集 pprof 性能样本，不用停机，分析线上性能问题。
 | 原文链接：http://wiki.x06jfh.asia/arts/126682.Doc

原标题：限流组件计数器令牌桶模式实现
简介：上传接口跨域配置特殊适配，针对文件上传接口，适配复杂请求，修复上传场景下跨域失效问题。
 | 原文链接：http://wiki.x06jfh.asia/arts/103658.Doc

原标题：性能笔记：RPC超时参数优化防止级联阻塞
简介：分布式事务最终一致性实现，基于可靠消息实现最终一致性，解决跨数据库跨服务业务数据一致性。
 | 原文链接：http://wiki.x06jfh.asia/arts/783808.Doc

原标题：golang 系统设计 tcc 事务简单原理业务示例
简介：版本升级服务启动失败处理，版本更新之后服务无法启动，对比新旧版本配置、依赖差异，完成故障修复。
 | 原文链接：http://wiki.x06jfh.asia/arts/499885.Doc

原标题：golang 系统设计告警分级 p0‑p3 定义处理流程
简介：golang 路径处理 filepath 包规范写法，使用 filepath 处理路径拼接分割，自动适配操作系统路径分隔符。
 | 原文链接：http://wiki.x06jfh.asia/arts/125478.Doc

原标题：JWT 令牌过期异常处理
简介：golang tar gz 压缩解压处理，tar.gz 归档压缩解压，服务端日志备份、文件打包场景使用。
 | 原文链接：http://wiki.x06jfh.asia/arts/312336.Doc

原标题：设计思考：业务埋点架构日志埋点设计原则
简介：HTTPS 证书过期更新操作，检测 HTTPS 证书到期，更新证书文件，恢复 HTTPS 服务正常访问。
 | 原文链接：http://wiki.x06jfh.asia/arts/578065.Doc

原标题：架构复盘：容器资源隔离架构CPU内存限制设计
简介：golang 处理连接被重置 reset 错误，识别 connection reset by peer，对端关闭连接异常处理逻辑。
 | 原文链接：http://wiki.x06jfh.asia/arts/150084.Doc

原标题：golang 系统设计配置敏感信息加密存储方案
简介：空指针异常判空容错处理，讲解空指针产生场景，规范判空逻辑，增加容错，避免空指针直接造成程序崩溃。
 | 原文链接：http://wiki.x06jfh.asia/arts/331752.Doc

原标题：golang docker 镜像安全扫描漏洞
简介：golang gorm 软删除实现逻辑，Gorm 开启软删除，删除数据仅标记，数据保留可恢复，满足业务数据留存。
 | 原文链接：http://wiki.x06jfh.asia/arts/505800.Doc

原标题：Practice：实现数据库连接池简易模拟实现
简介：golang http 文件下载断点续传服务，服务端实现断点续传，支持大文件分段下载，提升大文件下载稳定性。
 | 原文链接：http://wiki.x06jfh.asia/arts/698031.Doc

原标题：调优方案：MySQL缓冲池参数性能调优实践
简介：golang rsa 签名验签 pem 证书加载，加载 pem 格式密钥证书，rsa 签名与验签完整业务实现。
 | 原文链接：http://wiki.x06jfh.asia/arts/632311.Doc

原标题：Git LFS 大文件推送失败解决
简介：golang redis 过期时间处理技巧，设置 key 过期，监控过期事件，基于过期特性实现业务缓存逻辑。
 | 原文链接：http://wiki.x06jfh.asia/arts/583267.Doc

原标题：golang 系统设计数据库扩容几种方式
简介：golang embed 目录读取文件列表，embed 嵌入整个目录，读取目录下全部文件，做静态资源服务。
 | 原文链接：http://wiki.x06jfh.asia/arts/904282.Doc

原标题：golang 系统设计内存复用 sync.pool 使用
简介：golang 消息死信处理业务逻辑，Go 实现死信队列逻辑，消费失败消息转入死信，不阻塞正常消息队列。
 | 原文链接：http://wiki.x06jfh.asia/arts/237288.Doc

原标题：golang 系统设计线上故障排查完整流程
简介：golang http cookie jar 会话处理，客户端 cookie jar 自动管理 cookie，处理登录态会话。
 | 原文链接：http://wiki.x06jfh.asia/arts/459207.Doc

原标题：golang 系统设计测试环境预发环境生产环境隔离
简介：golang wasm 性能优化与内存管理，wasm 内存分配释放，减少内存拷贝，优化浏览器端性能。
 | 原文链接：http://wiki.x06jfh.asia/arts/514637.Doc

原标题：CI 流水线超时时间延长配置
简介：golang 限流熔断放在代理层实践，代理层统一限流熔断，对后端服务做流量保护。
 | 原文链接：http://wiki.x06jfh.asia/arts/528312.Doc

原标题：部署实践：内网开发环境代理配置实践
简介：golang 错误栈捕获打印方案，捕获错误完整调用堆栈，线上日志输出堆栈，快速定位错误发生代码位置。
 | 原文链接：http://wiki.x06jfh.asia/arts/830333.Doc

原标题：安全笔记：CORS跨域配置错误安全风险
简介：golang hmac 签名生成校验示例，hmac 生成消息签名，做接口请求签名，校验数据不被篡改。
 | 原文链接：http://wiki.x06jfh.asia/arts/200296.Doc

原标题：golang 系统设计错误码体系完整设计
简介：nodejs 内存溢出问题排查修复，Node.js 程序 OOM 排查流程，定位内存泄露，调整内存限制修复崩溃。
 | 原文链接：http://wiki.x06jfh.asia/arts/085103.Doc

原标题：nodejs 集成测试业务流程编写
简介：golang 容器时区设置镜像构建处理，镜像内部设置正确时区，解决容器时间与宿主机不一致。
 | 原文链接：http://wiki.x06jfh.asia/arts/352709.Doc

原标题：golang 系统设计分表扩容数据平滑迁移思路
简介：YAML 配置文件语法快速上手，讲解 YAML 基础语法、缩进规则，编写项目配置文件，规避语法错误引发程序异常。
 | 原文链接：http://wiki.x06jfh.asia/arts/475445.Doc

原标题：golang viper 配置热更新实操
简介：golang ctx 关闭之后资源释放，context 取消后，监听 Done ()，释放 goroutine 网络 IO 资源。
 | 原文链接：http://wiki.x06jfh.asia/arts/163015.Doc

原标题：零基础理解数据库事务基础ACID概念
简介：CLI 工具进度条交互效果开发，在命令行工具增加进度条展示，直观反馈任务执行进度，优化命令行体验。
 | 原文链接：http://wiki.x06jfh.asia/arts/437051.Doc

原标题：golang docker 基础命令实操汇总
简介：Git 代码冲突正确处理方式，讲解冲突产生场景，演示冲突文件修改，正确合并代码，防止代码丢失。
 | 原文链接：http://wiki.x06jfh.asia/arts/414006.Doc

原标题：golang 系统设计 protobuf json 性能对比
简介：golang go 运行时获取编译信息，程序内部读取编译时间 git 版本，接口输出程序版本信息。
 | 原文链接：http://wiki.x06jfh.asia/arts/111060.Doc

原标题：golang 系统设计接口返回格式统一规范
简介：git cherry‑pick 规范操作防 bug，规范 cherry‑pick 使用流程，处理冲突，避免错误引入不兼容代码。
 | 原文链接：http://wiki.x06jfh.asia/arts/716295.Doc

原标题：实践：API接口文档自动导出离线文档实践
简介：本地运行正常线上报错排查，对比本地与线上环境差异，从配置、系统版本、文件权限定位线上独有的 bug。
 | 原文链接：http://wiki.x06jfh.asia/arts/634314.Doc

原标题：golang redis 缓存更新策略讲解
简介：Fork 开源项目同步上游代码，Fork 开源仓库之后，配置上游源，同步官方最新代码，保持代码版本对齐。
 | 原文链接：http://wiki.x06jfh.asia/arts/864168.Doc

原标题：服务健康检查监控接口开发
简介：golang 数据库分表策略按时间分片，按时间维度分表，历史数据拆分，单表数据量控制保证查询性能。
 | 原文链接：http://wiki.x06jfh.asia/arts/874599.Doc

原标题：golang k8s hpa 水平 pod 自动扩缩容
简介：golang 配置热更新不重启服务，实现配置热加载，监听配置变更，更新内存配置，无需重启服务实例。
 | 原文链接：http://wiki.x06jfh.asia/arts/160415.Doc

原标题：架构复盘：供应链安全架构依赖包风险治理
简介：golang consul 服务发现简单示例，对接 Consul 实现服务注册发现，微服务实例自动感知。
 | 原文链接：http://wiki.x06jfh.asia/arts/596027.Doc

原标题：golang 系统设计消息重试次数间隔策略设置
简介：Docker 网络模式容器互通设置，选择合适 Docker 网络模式，实现容器之间网络互相访问通信。
 | 原文链接：http://wiki.x06jfh.asia/arts/718145.Doc

原标题：项目实践：MySQL读写分离本地模拟实践
简介：golang 数据库连接池泄露检测逻辑，监控连接池状态，检测连接长时间未归还，告警连接泄漏问题。
 | 原文链接：http://wiki.x06jfh.asia/arts/538812.Doc

原标题：Security：业务操作审计日志安全留存
简介：golang cobra 命令行参数配置绑定，cobra 绑定配置文件环境变量命令行参数，多源配置合并。
 | 原文链接：http://wiki.x06jfh.asia/arts/743981.Doc

原标题：Security：限流防爬虫防恶意攻击防护体系
简介：golang go mod tidy 依赖清理，go mod tidy 自动增删依赖，整理 go.mod go.sum 文件。
 | 原文链接：http://wiki.x06jfh.asia/arts/900739.Doc

原标题：实战：基于内存实现简单消息广播组件
简介：golang go 值传递引用传递理解，go 全部为值传递，指针本质拷贝指针值，理清参数传递行为。
 | 原文链接：http://wiki.x06jfh.asia/arts/823676.Doc


二、踩坑排错｜Troubleshooting
原标题：Troubleshooting：Redis大key引发集群卡顿
简介：后端分页查询逻辑代码实现，编写后端分页接口，处理页码、每页条数参数，优化大数据量查询返回结果。
 | 原文链接：http://wiki.x06jfh.asia/arts/691570.Doc

原标题：新手教程：配置SSH‑Key免密访问GitHub
简介：golang docker 多阶段构建 go 镜像，Go 项目 Docker 多阶段构建，编译与运行阶段分离，大幅度缩减最终镜像体积，提升镜像分发效率。
 | 原文链接：http://wiki.x06jfh.asia/arts/289559.Doc

原标题：golang 系统设计创建更新时间自动维护方案
简介：系统文件描述符上限调大，调高操作系统文件描述符上限，解决高并发场景打开文件报错。
 | 原文链接：http://wiki.x06jfh.asia/arts/326980.Doc

原标题：看懂报错日志快速定位问题
简介：golang 路径处理 filepath 包规范写法，使用 filepath 处理路径拼接分割，自动适配操作系统路径分隔符。
 | 原文链接：http://wiki.x06jfh.asia/arts/931701.Doc

原标题：golang 系统设计读写分离架构示例
简介：请求重试组件退避策略实现，封装重试组件，实现指数退避策略，避免大量请求同时重试压垮下游。
 | 原文链接：http://wiki.x06jfh.asia/arts/997261.Doc

原标题：golang 系统设计定时任务执行超时中断防护
简介：golang sqlx 原生 SQL 代码简化，sqlx 简化原生 SQL 结果映射结构体，兼顾性能与开发效率。
 | 原文链接：http://wiki.x06jfh.asia/arts/945172.Doc

原标题：Practice：实现业务唯一流水号生成组件实践
简介：后端分页查询逻辑代码实现，编写后端分页接口，处理页码、每页条数参数，优化大数据量查询返回结果。
 | 原文链接：http://wiki.x06jfh.asia/arts/496563.Doc

原标题：golang 系统设计指标聚合计算存储选型对比
简介：nodejs 数据库连接池配置调优，调优 Node 数据库连接池参数，平衡性能与资源占用，避免连接耗尽。
 | 原文链接：http://wiki.x06jfh.asia/arts/569071.Doc

原标题：快速入门GraphQL基础查询语法示例
简介：批量异步处理系统业务落地，构建批量异步处理系统，把耗时业务异步化，提升接口响应速度。
 | 原文链接：http://wiki.x06jfh.asia/arts/317692.Doc

原标题：golang 系统设计本地缓存过期淘汰策略选型
简介：golang gif 图片帧处理操作，解析 gif 图片帧，压缩、拆分 gif 动图，处理动图业务。
 | 原文链接：http://wiki.x06jfh.asia/arts/023392.Doc

原标题：Issue：防火墙拦截ICMP，MTU问题网络丢包
简介：golang embed 目录读取文件列表，embed 嵌入整个目录，读取目录下全部文件，做静态资源服务。
 | 原文链接：http://wiki.x06jfh.asia/arts/706722.Doc

原标题：方案设计：异步解耦业务架构边界识别
简介：多实例部署 Session 共享方案，多服务实例部署场景，实现 Session 共享，保证用户登录状态跨实例生效。
 | 原文链接：http://wiki.x06jfh.asia/arts/283596.Doc

原标题：DevOps：私有镜像仓库搭建与权限管控
简介：golang 日志输出 stdout 标准输出规范，容器环境日志输出到 stdout，由容器平台统一采集日志文件。
 | 原文链接：http://wiki.x06jfh.asia/arts/601427.Doc

原标题：坑点：Docker资源限制未设置导致宿主机卡死
简介：golang gin 参数绑定 query form json，掌握 Gin 多种参数绑定方式，适配不同请求格式参数读取。
 | 原文链接：http://wiki.x06jfh.asia/arts/192576.Doc

原标题：架构复盘：供应链安全架构依赖包风险治理
简介：golang accept 错误循环崩溃处理，accept 返回系统错误，处理临时错误，避免死循环占满 CPU。
 | 原文链接：http://wiki.x06jfh.asia/arts/798438.Doc

原标题：golang minio 预签名 url 临时访问
简介：golang base64 编码解码实操，Go Base64 编码解码示例，处理业务场景 Base64 格式数据转换。
 | 原文链接：http://wiki.x06jfh.asia/arts/495542.Doc

原标题：golang 系统设计日志采样降低存储开销方案
简介：Git 分支管理多人协作实战教程，详解分支创建、合并、冲突处理，适配团队开发场景，规范多人协同代码工作流。
 | 原文链接：http://wiki.x06jfh.asia/arts/715246.Doc

原标题：排错：静态资源CDN缓存未刷新旧资源持续返回
简介：golang go 服务压测前后性能对比，压测记录 QPS 延迟，优化前后对比，验证优化效果。
 | 原文链接：http://wiki.x06jfh.asia/arts/612512.Doc

原标题：golang kafka 批量发送消费优化
简介：golang gitlab ci go 项目流水线编写，gitlab ci 流水线执行单元测试、静态检查、构建推送镜像。
 | 原文链接：http://wiki.x06jfh.asia/arts/981876.Doc

原标题：golang redis 位图用户签到统计
简介：文件句柄上限调整上传随机失败，调高系统文件句柄上限，解决高并发上传场景随机打开文件失败。
 | 原文链接：http://wiki.x06jfh.asia/arts/195211.Doc

原标题：golang 系统设计 grpc http2 多路复用讲解
简介：golang context 超时取消实战案例，使用 context 控制协程、http 请求超时，自动终止超时任务，避免协程无限阻塞。
 | 原文链接：http://wiki.x06jfh.asia/arts/927919.Doc

原标题：快速上手简单性能监控指标查看
简介：浏览器内存泄漏排查前端页面，梳理前端页面内存泄漏场景，讲解排查手段，修复页面内存持续上涨。
 | 原文链接：http://wiki.x06jfh.asia/arts/978866.Doc

原标题：golang github actions 完整工作流示例
简介：golang io.Reader io.Writer 接口理解，io 读写接口，各类数据源统一抽象，适配 io 复制函数。
 | 原文链接：http://wiki.x06jfh.asia/arts/352272.Doc

原标题：golang 系统设计 protobuf oneof 类型业务场景
简介：golang gin 参数绑定 query form json，掌握 Gin 多种参数绑定方式，适配不同请求格式参数读取。
 | 原文链接：http://wiki.x06jfh.asia/arts/826941.Doc

原标题：golang 系统设计 pr 评审合并完整流程
简介：golang os/exec 安全执行外部命令，规避命令注入漏洞，参数分离，禁止拼接命令字符串执行。
 | 原文链接：http://wiki.x06jfh.asia/arts/575082.Doc

原标题：Hands‑on：代码生成器，一键生成CRUD模板
简介：golang 设置 net.Conn 读写超时，每次读写设置超时，防止连接永久阻塞挂起不返回。
 | 原文链接：http://wiki.x06jfh.asia/arts/216646.Doc

原标题：性能笔记：线程池参数调优任务队列策略
简介：golang context.WithCancel 手动取消上下文，WithCancel 生成可取消 ctx，手动调用 cancel 触发取消。
 | 原文链接：http://wiki.x06jfh.asia/arts/559468.Doc

原标题：快速入门gRPC基础概念与简单示例
简介：业务错误码完整落地实践，落地完整业务错误码，枚举全部业务异常，统一返回，配套文档说明。
 | 原文链接：http://wiki.x06jfh.asia/arts/115155.Doc

原标题：特殊输入字符过滤解析防护
简介：golang go 并发模式 fan‑out fan‑in，fanout 分发任务 fanin 汇总结果，多协程并发处理任务。
 | 原文链接：http://wiki.x06jfh.asia/arts/150987.Doc

原标题：Troubleshoot：异步异常未捕获，进程悄无声息退出
简介：golang go select 多路等待 channel，select 等待多个 channel，default 非阻塞，超时等待 channel。
 | 原文链接：http://wiki.x06jfh.asia/arts/083281.Doc

原标题：Git 子模块更新代码不全修复
简介：golang benchmark 减少测试干扰，benchmark 执行循环 b.N，避免循环内部做非被测逻辑干扰结果。
 | 原文链接：http://wiki.x06jfh.asia/arts/371593.Doc

原标题：golang gorm 批量插入性能调优
简介：monorepo 项目多包管理最佳实践，monorepo 仓库管理多子包，统一版本管理，处理包之间互相依赖。
 | 原文链接：http://wiki.x06jfh.asia/arts/597596.Doc

原标题：开发复盘：避免大报文导致服务OOM优化实践
简介：Git commit 钩子提交规范校验，配置 Git 提交钩子，提交代码自动校验提交信息格式，规范提交记录。
 | 原文链接：http://wiki.x06jfh.asia/arts/382110.Doc

原标题：数据库连接池参数调优
简介：golang 负载均衡轮询加权轮询实现，手写负载均衡算法，轮询、加权轮询分发请求到后端节点。
 | 原文链接：http://wiki.x06jfh.asia/arts/180956.Doc

原标题：Hands‑on：简易压缩中间件gzip实现实践
简介：系统文件描述符上限调大，调高操作系统文件描述符上限，解决高并发场景打开文件报错。
 | 原文链接：http://wiki.x06jfh.asia/arts/456590.Doc

原标题：文件批量导入导出功能实现
简介：业务错误码体系设计方案，设计项目统一错误码，区分不同业务异常，标准化错误返回，便于前端识别处理。
 | 原文链接：http://wiki.x06jfh.asia/arts/790328.Doc

原标题：Practice：模拟缓存雪崩缓存击穿验证防护策略
简介：golang wasm 浏览器 js 交互，go wasm 与 js 互相调用，浏览器端 go 程序操作 dom 调用 js 函数。
 | 原文链接：http://wiki.x06jfh.asia/arts/957920.Doc

原标题：零基础理解依赖管理与包管理器
简介：golang os 环境变量读取设置，os.Getenv os.Setenv os.Unsetenv 读写环境变量，环境变量多值处理。
 | 原文链接：http://wiki.x06jfh.asia/arts/271878.Doc

原标题：nodejs 全局异常捕获进程防护
简介：golang kafka 批量消费性能优化，开启批量拉取消息，调整批量大小，提升 kafka 消息消费吞吐量。
 | 原文链接：http://wiki.x06jfh.asia/arts/978941.Doc

原标题：安全笔记：文件下载接口路径校验安全
简介：移动端适配 rem vw 方案对比，对比 rem 与 vw 移动端适配方案，分析优缺点，给出选型建议。
 | 原文链接：http://wiki.x06jfh.asia/arts/619237.Doc

三、实战开发｜Practice
原标题：序列化版本不一致解析失败
简介：golang 分页查询封装通用工具，封装 Go 通用分页工具，统一处理分页参数，简化业务分页接口开发。
 | 原文链接：http://wiki.x06jfh.asia/arts/333905.Doc

原标题：golang minio 预签名 url 临时访问
简介：golang 开发环境快速搭建指南，快速完成 Golang 开发环境配置，工具链安装，环境变量设置，准备开发。
 | 原文链接：http://wiki.x06jfh.asia/arts/932479.Doc

原标题：golang 系统设计灰度发布实现思路
简介：golang jwt 鉴权中间件完整示例，Gin JWT 鉴权中间件，令牌校验，解析用户信息，接口鉴权拦截。
 | 原文链接：http://wiki.x06jfh.asia/arts/672320.Doc

原标题：部署复盘：配置不要硬编码进镜像最佳实践
简介：golang go 变量逃逸场景汇总，切片、指针、返回局部变量引发逃逸，变量分配到堆影响 GC。
 | 原文链接：http://wiki.x06jfh.asia/arts/035199.Doc

原标题：开发记录：敏感数据加密存储解密业务实践
简介：golang netlink 系统信息获取，netlink 获取系统网络信息，网卡地址，内核网络状态读取。
 | 原文链接：http://wiki.x06jfh.asia/arts/900360.Doc

原标题：全局时间标准统一逻辑错乱修复
简介：代理 HTTPS 证书访问异常处理，配置代理根证书，解决代理环境 HTTPS 证书校验失败无法访问外网。
 | 原文链接：http://wiki.x06jfh.asia/arts/549116.Doc

原标题：golang 简单爬虫请求防封禁
简介：SourceMap 生成线上报错定位，项目打包生成 SourceMap 文件，线上报错可以还原源码，快速定位报错位置。
 | 原文链接：http://wiki.x06jfh.asia/arts/743227.Doc

原标题：golang 系统设计读写分离延迟业务兼容
简介：golang 速率限制令牌桶实现，Go 实现令牌桶限流算法，可复用限流器，控制业务调用速率。
 | 原文链接：http://wiki.x06jfh.asia/arts/534849.Doc

原标题：项目目录结构规范化最佳实践
简介：golang go 种子初始化 rand 随机，rand 初始化种子，不初始化会固定序列，理解随机数种子行为。
 | 原文链接：http://wiki.x06jfh.asia/arts/418004.Doc

原标题：实践：消息队列死信处理业务落地实践
简介：时间精度统一业务判断修复，统一业务使用时间戳精度，毫秒秒区分清楚，修复时间判断逻辑错误。
 | 原文链接：http://wiki.x06jfh.asia/arts/987128.Doc

原标题：安全笔记：文件下载接口路径校验安全
简介：golang io.MultiReader MultiWriter 拼接流，多个 reader 拼接，多 writer 同时写入一份数据。
 | 原文链接：http://wiki.x06jfh.asia/arts/538431.Doc

原标题：新手教程：Gittag版本标签打标签实操
简介：程序预加载加快服务启动速度，把高频使用资源提前预加载，减少请求阶段初始化，加快服务启动。
 | 原文链接：http://wiki.x06jfh.asia/arts/850753.Doc

原标题：Hands‑on：简易导出PDF后端生成demo实践
简介：golang 分表跨表 join 查询处理方案，分表后跨分片关联查询解决方案，业务层聚合代替数据库 join。
 | 原文链接：http://wiki.x06jfh.asia/arts/827593.Doc

原标题：限流组件计数器令牌桶模式实现
简介：golang mock 单元测试编写技巧，单元测试 mock 外部依赖，隔离数据库网络，只测试业务逻辑本身。
 | 原文链接：http://wiki.x06jfh.asia/arts/174402.Doc

原标题：调优方案：消息批量消费提升MQ处理吞吐量
简介：golang go json 序列化自定义字段，json 标签控制字段名称、忽略字段、omitempty 空值忽略。
 | 原文链接：http://wiki.x06jfh.asia/arts/903683.Doc

原标题：跨平台 uniapp 多端开发实操
简介：vite 插件开发自定义构建逻辑，开发自定义 vite 插件，介入构建生命周期，实现项目个性化构建逻辑。
 | 原文链接：http://wiki.x06jfh.asia/arts/852659.Doc

原标题：golang md5 sha 加密工具实现
简介：golang 制品镜像版本号规范管理，镜像版本号结合 git commit，明确每个镜像对应代码版本便于追溯。
 | 原文链接：http://wiki.x06jfh.asia/arts/945142.Doc

原标题：golang 系统设计接口频率限制业务落地
简介：短信服务封装失败自动重试，封装短信发送组件，处理发送失败自动重试，兼容多短信服务商。
 | 原文链接：http://wiki.x06jfh.asia/arts/502527.Doc

原标题：项目实践：MySQL读写分离本地模拟实践
简介：pnpm 包管理工具实战避坑指南，使用 pnpm 管理项目依赖，梳理常见坑点，充分利用 pnpm 优势。
 | 原文链接：http://wiki.x06jfh.asia/arts/417924.Doc

原标题：Architecture：灰度、蓝绿、金丝雀发布架构对比
简介：golang contract 契约测试微服务，微服务契约测试，保证接口变更不破坏调用方，提前发现兼容性问题。
 | 原文链接：http://wiki.x06jfh.asia/arts/236253.Doc

原标题：golang 系统设计链路数据存储选型对比讲解
简介：golang 多协程任务池并发控制，实现协程任务池，控制并发协程数量，防止无限制创建 goroutine。
 | 原文链接：http://wiki.x06jfh.asia/arts/329818.Doc

原标题：主干开发团队代码合并策略
简介：前端打包分包加载提速方案，前端打包做代码分包，拆分大 bundle，页面按需加载，提升首屏加载速度。
 | 原文链接：http://wiki.x06jfh.asia/arts/853438.Doc

原标题：golang docker 镜像体积优化技巧
简介：golang 日志按日期切割实现方案，实现日志文件按天切割，自动归档旧日志，防止单个日志文件过大。
 | 原文链接：http://wiki.x06jfh.asia/arts/019113.Doc

原标题：golang docker compose 完整语法
简介：golang kitex 中间件与元数据传递，kitex 自定义中间件，透传 traceId 鉴权元数据，统一处理请求。
 | 原文链接：http://wiki.x06jfh.asia/arts/172650.Doc

原标题：Redis 热点 key 拆分降低集群压力
简介：服务启动依赖顺序配置正确，配置服务启动依赖关系，保证依赖服务就绪之后再启动当前业务服务。
 | 原文链接：http://wiki.x06jfh.asia/arts/965461.Doc

原标题：Hands‑on：简易反向代理中间件实现
简介：golang 分页查询封装通用工具，封装 Go 通用分页工具，统一处理分页参数，简化业务分页接口开发。
 | 原文链接：http://wiki.x06jfh.asia/arts/800216.Doc

原标题：性能笔记：磁盘IO过高业务优化手段
简介：模拟登录鉴权权限判断示例，实现简易登录流程，会话状态维护，完成接口权限校验，理解身份鉴权基础逻辑。
 | 原文链接：http://wiki.x06jfh.asia/arts/896802.Doc

原标题：golang 系统设计压测指标确定与分析
简介：时间精度统一业务判断修复，统一业务使用时间戳精度，毫秒秒区分清楚，修复时间判断逻辑错误。
 | 原文链接：http://wiki.x06jfh.asia/arts/017065.Doc

原标题：业务幂等键设计防重复逻辑
简介：Git 分支切换合并删除完整操作，实操分支全生命周期操作，包含切换、合并、删除，熟悉日常开发分支处理流程。
 | 原文链接：http://wiki.x06jfh.asia/arts/086739.Doc

原标题：golang 系统设计定时任务执行超时中断防护
简介：golang nacos go 客户端配置服务发现，nacos‑go 对接 nacos，配置管理、微服务注册发现。
 | 原文链接：http://wiki.x06jfh.asia/arts/614710.Doc

原标题：HelloShell：入门常用shell脚本编写
简介：CI 流水线构建失败日志排查，阅读 CI 流水线输出日志，定位构建脚本、依赖、环境导致流水线失败问题。
 | 原文链接：http://wiki.x06jfh.asia/arts/670149.Doc

原标题：golang k8s 滚动更新回滚策略
简介：golang 内存缓存简单实现方案，Go 实现进程内简易内存缓存，本地缓存热点数据，减少远程调用。
 | 原文链接：http://wiki.x06jfh.asia/arts/235091.Doc

原标题：golang 系统设计消息消费 offset 管理策略
简介：golang kafka 消费者位移管理，理解 kafka offset，手动提交位移，保证消息消费至少一次语义。
 | 原文链接：http://wiki.x06jfh.asia/arts/260923.Doc

原标题：新手教程：本地环境变量配置全流程
简介：golang 钉钉企业微信告警消息推送，go 调用企业微信钉钉接口，推送告警通知、业务消息。
 | 原文链接：http://wiki.x06jfh.asia/arts/334635.Doc

原标题：golang 系统设计 rest 状态码合理使用指南
简介：golang 多协程任务池并发控制，实现协程任务池，控制并发协程数量，防止无限制创建 goroutine。
 | 原文链接：http://wiki.x06jfh.asia/arts/052065.Doc

原标题：golang mysql 长连接短连接对比
简介：包管理器依赖缓存清理，清理本地依赖缓存，解决缓存旧包引发问题，拉取最新版本依赖包。
 | 原文链接：http://wiki.x06jfh.asia/arts/899871.Doc

原标题：golang 配置热更新不重启服务
简介：Redis 分布式锁高并发安全实现，基于 Redis 实现分布式锁，处理锁过期、续期，保障集群并发安全。
 | 原文链接：http://wiki.x06jfh.asia/arts/815982.Doc

原标题：golang 系统设计 go netpoll 多路复用简单理解
简介：golang go 项目 CI github actions 配置，github actions 实现 go 项目 ci，自动测试、代码检查、编译打包镜像。
 | 原文链接：http://wiki.x06jfh.asia/arts/056479.Doc

原标题：项目实践：消息队列消息堆积模拟处理实践
简介：消息队列重复消费业务处理，实现消息消费幂等，处理重复投递消息，保证多次消费业务结果一致。
 | 原文链接：http://wiki.x06jfh.asia/arts/690093.Doc

原标题：golang 信号量控制并发数量
简介：前端国际化多语言方案落地，搭建前端多语言国际化方案，切换语言，页面文本自动切换对应语种。
 | 原文链接：http://wiki.x06jfh.asia/arts/308957.Doc

四、架构设计｜Architecture
原标题：实战：搭建日志收集分析简易完整演示环境
简介：代码模块化组件化拆分思路，讲解代码拆分原则，将大业务拆分为独立模块组件，提升代码复用与维护能力。
 | 原文链接：http://wiki.x06jfh.asia/arts/654580.Doc

原标题：运维笔记：备份策略数据库定时备份脚本
简介：golang bufio 缓冲读写性能优化，bufio 带缓冲读写，减少系统调用，提升文件网络 IO 性能。
 | 原文链接：http://wiki.x06jfh.asia/arts/442753.Doc

原标题：golang 系统设计请求签名校验完整方案
简介：css 动画性能优化 GPU 加速，优化 CSS 动画，使用 GPU 加速属性，避免动画过程页面卡顿掉帧。
 | 原文链接：http://wiki.x06jfh.asia/arts/321216.Doc

原标题：设计思考：容器化业务应用架构改造要点
简介：golang validator 自定义校验规则，Gin Validator 自定义校验器，实现业务特殊参数校验逻辑。
 | 原文链接：http://wiki.x06jfh.asia/arts/699809.Doc

原标题：golang docker compose 完整语法
简介：JSON XML 数据解析处理示例，演示两种格式数据解析与序列化，增加异常捕获，处理格式错乱导致解析失败。
 | 原文链接：http://wiki.x06jfh.asia/arts/205549.Doc

原标题：复盘总结：系统压测报告模板与分析思路
简介：golang sqlx 原生 SQL 代码简化，sqlx 简化原生 SQL 结果映射结构体，兼顾性能与开发效率。
 | 原文链接：http://wiki.x06jfh.asia/arts/320097.Doc

原标题：golang 系统设计短链接服务实现思路
简介：css 动画性能优化 GPU 加速，优化 CSS 动画，使用 GPU 加速属性，避免动画过程页面卡顿掉帧。
 | 原文链接：http://wiki.x06jfh.asia/arts/670719.Doc

原标题：golang 系统设计容器镜像安全加固要点
简介：vue3 组合式 API 业务开发实战，Vue3 组合式 API 业务实战示例，拆分业务逻辑组合复用，提升代码组织。
 | 原文链接：http://wiki.x06jfh.asia/arts/153009.Doc

原标题：开发记录：跨域中间件完整配置与边界处理
简介：golang go 初始化顺序包变量 init 函数，包级变量初始化，init 执行顺序，理解包加载执行流程。
 | 原文链接：http://wiki.x06jfh.asia/arts/330545.Doc

原标题：HelloTest：理解集成测试基础编写思路
简介：CPU 亲和性配置负载均衡调度，配置进程 CPU 亲和，均衡利用多核 CPU，优化程序调度性能。
 | 原文链接：http://wiki.x06jfh.asia/arts/563179.Doc

原标题：Troubleshooting：K8sPodOOMKilled完整排查流程
简介：接口幂等性防重复请求实现，实现接口幂等逻辑，避免重复提交请求产生多条脏数据，保障业务数据安全。
 | 原文链接：http://wiki.x06jfh.asia/arts/052185.Doc

原标题：golang html 模板渲染简单示例
简介：golang atomic.Value 存储任意类型数据，atomic.Value 安全存储读取任意类型，配置热更新常用。
 | 原文链接：http://wiki.x06jfh.asia/arts/634748.Doc

原标题：Debug：HTTPS握手失败TLS版本兼容问题
简介：golang io.Copy 流式拷贝数据，io.Copy 拷贝 reader 到 writer，不用加载全部数据到内存。
 | 原文链接：http://wiki.x06jfh.asia/arts/304994.Doc

原标题：golang 系统设计内网外网服务隔离方案
简介：WebSocket 断线重连稳定优化，增加 WebSocket 断线自动重连逻辑，处理网络抖动，维持长连接稳定。
 | 原文链接：http://wiki.x06jfh.asia/arts/320331.Doc

原标题：golang 系统设计日志脱敏防止信息泄露
简介：golang grpc 错误状态码标准化，grpc 标准化错误返回，定义业务错误码，客户端解析处理业务异常。
 | 原文链接：http://wiki.x06jfh.asia/arts/537097.Doc

原标题：golang redis bitmap 位图统计实现
简介：Git 子模块更新代码不全修复，正确更新 Git 子模块，拉取子模块完整代码，解决子模块目录为空问题。
 | 原文链接：http://wiki.x06jfh.asia/arts/816475.Doc

原标题：布隆过滤器误判问题修正
简介：golang mongodb 索引优化慢查询处理，mongodb 创建索引，分析慢查询，优化聚合查询执行性能。
 | 原文链接：http://wiki.x06jfh.asia/arts/347489.Doc

原标题：调优方案：消息批量消费提升MQ处理吞吐量
简介：CI 持续集成自动构建流程，讲解 CI 基础概念，配置流水线实现代码提交后自动构建、测试，提升交付自动化。
 | 原文链接：http://wiki.x06jfh.asia/arts/531002.Doc

?
