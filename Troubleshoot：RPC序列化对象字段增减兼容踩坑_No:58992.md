最新前沿技术资讯

一、入门教程｜Getting Started
原标题：Troubleshoot：RPC序列化对象字段增减兼容踩坑
简介：golang redis scan 遍历 key 避免阻塞，使用 scan 迭代遍历 redis 键，不用 keys 命令，防止阻塞 redis 服务。
 | 原文链接：http://book.gay65g.asia/blog/164500.Doc

原标题：开发记录：批量接口请求并发控制实践
简介：golang jwt 令牌刷新逻辑实现，实现 JWT 双令牌机制，access 短期有效 refresh 刷新令牌，实现无感续期登录。
 | 原文链接：http://book.gay65g.asia/blog/672134.Doc

原标题：golang 系统设计缓存预热缓存降级实现
简介：golang etcd key 监听变更 watch 机制，watch 监听 etcd 键变化，配置变更实时感知，实现配置热更新。
 | 原文链接：http://book.gay65g.asia/blog/345141.Doc

原标题：实践：Git工作流主干开发团队协作实践
简介：容器资源限制防止宿主机过载，设置容器 CPU 内存资源上限，避免单个容器耗尽宿主机全部硬件资源。
 | 原文链接：http://book.gay65g.asia/blog/974721.Doc

原标题：golang 系统设计代码评审关注点 checklist 清单
简介：golang 错误静默忽略风险规避，禁止空忽略错误，必须处理或者明确注释为什么忽略错误。
 | 原文链接：http://book.gay65g.asia/blog/687943.Doc

原标题：golang 系统设计会话共享多实例部署
简介：golang http body 必须关闭的重要性，无论成功失败必须关闭 request.Body，否则连接无法复用泄漏。
 | 原文链接：http://book.gay65g.asia/blog/286111.Doc

原标题：golang 系统设计内部服务调用超时设置要点
简介：后端大文件分片上传接口开发，开发后端分片上传接口，接收分片，合并分片完成大文件存储。
 | 原文链接：http://book.gay65g.asia/blog/503203.Doc

原标题：坑点：gitrebase操作失误，代码提交丢失
简介：跨域偶现失败配置修复，解决跨域问题时而复现时而正常，定位配置漏配、请求头异常等隐性问题。
 | 原文链接：http://book.gay65g.asia/blog/863080.Doc

原标题：OpenSource：开源项目贡献者协作流程规范
简介：WebSocket 聊天室实时通讯开发，基于 WebSocket 搭建简易聊天室，实现多人消息广播实时聊天效果。
 | 原文链接：http://book.gay65g.asia/blog/301317.Doc

原标题：编译打包产物依赖分析解读
简介：Dockerfile 编写容器打包实战，讲解 Dockerfile 指令含义，编写镜像构建脚本，将本地项目打包成可分发容器镜像。
 | 原文链接：http://book.gay65g.asia/blog/027095.Doc

原标题：golang 系统设计分布式配置中心思路
简介：极简 API 网关路由转发实现，开发极简网关服务，完成请求路由转发，理解网关基础实现原理。
 | 原文链接：http://book.gay65g.asia/blog/435048.Doc

原标题：Issue：系统fd快速上涨进程慢慢卡死
简介：分布式任务调度集群原型开发，开发简易分布式调度原型，集群多节点运行，保证任务只执行一次。
 | 原文链接：http://book.gay65g.asia/blog/659447.Doc

原标题：golang 消息队列 kafka 消费开发
简介：golang go 程序运行时动态修改配置，运行时热加载配置结构体，原子更新保证并发读取安全。
 | 原文链接：http://book.gay65g.asia/blog/947998.Doc

原标题：golang 系统设计压力测试性能测试执行流程
简介：vite 项目配置与构建提速技巧，讲解 vite 配置优化手段，提升开发热更新速度与生产构建打包效率。
 | 原文链接：http://book.gay65g.asia/blog/509530.Doc

原标题：Security：文件上传漏洞攻击面完整防护方案
简介：golang 子进程执行命令标准流处理，exec.Command 执行外部命令，处理 stdout stderr，防止缓冲区阻塞卡死。
 | 原文链接：http://book.gay65g.asia/blog/429490.Doc

原标题：入门实践：简单数据脱敏处理示例
简介：容器软链接文件权限修复，修复容器内软链接文件权限，让程序能够正常读取软链接指向的文件。
 | 原文链接：http://book.gay65g.asia/blog/048773.Doc

原标题：golang redis bitmap 位图统计实现
简介：缓存穿透防护保护数据库，实现缓存穿透防护手段，拦截不存在的数据查询，避免请求直接打穿数据库。
 | 原文链接：http://book.gay65g.asia/blog/101110.Doc

原标题：安全实践：容器最小化镜像减少攻击面
简介：代码格式化工具团队统一风格，接入格式化工具，统一全团队代码书写风格，减少格式类 git 冲突。
 | 原文链接：http://book.gay65g.asia/blog/501718.Doc

原标题：nodejs 中间件模式原理剖析
简介：golang os.Signal 信号监听完整示例，signal.Notify 监听信号，缓冲 channel 防止信号丢失。
 | 原文链接：http://book.gay65g.asia/blog/466531.Doc

原标题：踩坑：Docker容器内时区不一致引发的时间BUG
简介：gitignore 文件编写过滤规则，讲解 gitignore 语法，编写过滤配置，忽略缓存、编译产物、密钥文件，保持仓库整洁。
 | 原文链接：http://book.gay65g.asia/blog/167045.Doc

原标题：golang 系统设计容量评估简单方法论
简介：golang 分页查询封装通用工具，封装 Go 通用分页工具，统一处理分页参数，简化业务分页接口开发。
 | 原文链接：http://book.gay65g.asia/blog/940554.Doc

原标题：golang jwt 鉴权中间件完整示例
简介：游标分页大数据查询性能提升，使用游标分页替代偏移分页，解决大数据 offset 分页性能越来越差问题。
 | 原文链接：http://book.gay65g.asia/blog/001120.Doc

原标题：golang 系统设计 http3 quic 简单原理了解
简介：文件读写与异常捕获代码示例，演示文件读取写入操作，增加异常捕获逻辑，规避文件不存在、权限不足导致崩溃。
 | 原文链接：http://book.gay65g.asia/blog/600607.Doc

原标题：Debug：DNS缓存TTL设置不当服务切换无法生效
简介：golang go mod why 查询依赖引入原因，go mod why 查询为什么引入某个包，理清依赖来源。
 | 原文链接：http://book.gay65g.asia/blog/081189.Doc

原标题：Troubleshooting：Nginx缓冲区过小大文件上传失败
简介：golang systemd 信号与优雅退出配合，systemd 停止服务发送 SIGTERM，go 程序捕获信号优雅关闭。
 | 原文链接：http://book.gay65g.asia/blog/661465.Doc

原标题：架构笔记：数据库连接池架构参数调优思路
简介：包管理器依赖冲突解决方案，分析依赖冲突产生根源，提供版本调整、锁定依赖等手段，解决项目依赖报错问题。
 | 原文链接：http://book.gay65g.asia/blog/653272.Doc

原标题：golang 系统设计 rest 资源命名规范汇总
简介：golang http MaxHeaderBytes 限制请求头，设置 http 最大请求头大小，防止超大 header 攻击。
 | 原文链接：http://book.gay65g.asia/blog/140200.Doc

原标题：golang 系统设计敏感数据加密存储方案
简介：nestjs 拦截器过滤器管道实战，实操 Nest 拦截器、异常过滤器、管道校验，处理请求与响应统一逻辑。
 | 原文链接：http://book.gay65g.asia/blog/949549.Doc

原标题：项目实践：多租户数据隔离三种方案实操对比
简介：golang go 防止路径穿越攻击，文件操作校验路径，拒绝../ 路径穿越，禁止访问系统任意文件。
 | 原文链接：http://book.gay65g.asia/blog/788138.Doc

原标题：golang 系统设计主键 id 选型雪花自增对比
简介：前端工程化 webpack 打包优化，针对 webpack 项目做打包调优，分包、压缩、Tree‑Shaking，缩减包体积。
 | 原文链接：http://book.gay65g.asia/blog/070544.Doc

原标题：DevOps：Docker镜像安全扫描集成CI流程
简介：golang 负载均衡轮询加权轮询实现，手写负载均衡算法，轮询、加权轮询分发请求到后端节点。
 | 原文链接：http://book.gay65g.asia/blog/763255.Doc

原标题：零基础理解会话、Cookie、Session基础
简介：golang etcd key 监听变更 watch 机制，watch 监听 etcd 键变化，配置变更实时感知，实现配置热更新。
 | 原文链接：http://book.gay65g.asia/blog/973345.Doc

原标题：性能复盘：热点key导致RedisCPU飙升优化
简介：golang 优雅处理 http 重定向逻辑，自定义控制 http 重定向跳转次数，防止无限重定向死循环。
 | 原文链接：http://book.gay65g.asia/blog/077391.Doc

原标题：项目实践：接口压测，逐步加压观察系统表现
简介：文件监控服务自动重启开发，监控项目文件变更，代码修改自动重启服务，提升本地开发调试效率。
 | 原文链接：http://book.gay65g.asia/blog/886747.Doc

原标题：golang mysql 连接泄漏检测方法
简介：golang go ring 环形容器循环队列，ring 环形链表实现循环队列，环形缓冲区业务场景。
 | 原文链接：http://book.gay65g.asia/blog/577616.Doc

原标题：容器软链接文件权限修复
简介：golang nilnil interface 陷阱复现，interface 包含类型不为 nil 值为 nil，判 ==nil 返回 false 经典坑。
 | 原文链接：http://book.gay65g.asia/blog/345519.Doc

原标题：性能笔记：DNS缓存优化减少域名解析开销
简介：前端打包产物体积压缩优化，多手段压缩前端打包产物，移除无用代码，压缩资源，提升页面加载速度。
 | 原文链接：http://book.gay65g.asia/blog/960651.Doc

原标题：新手向：Mac/Windows开发环境差异踩坑
简介：golang 文件句柄耗尽排查处理，统计进程打开文件句柄，找到未关闭文件，修复句柄泄漏问题。
 | 原文链接：http://book.gay65g.asia/blog/289275.Doc

原标题：开发测试生产多环境配置区分
简介：golang 日志级别动态调整热更新，不用重启程序动态修改日志输出级别，线上调试排查问题十分方便。
 | 原文链接：http://book.gay65g.asia/blog/645144.Doc

原标题：golang 系统设计开源项目安全漏洞处理流程
简介：golang oss 签名 URL 临时访问，生成 oss 临时签名 url，限时访问私有文件，保障文件访问安全可控。
 | 原文链接：http://book.gay65g.asia/blog/347047.Doc


二、踩坑排错｜Troubleshooting
原标题：golang redis 集群 hash 槽讲解
简介：golang 模糊测试 go fuzz 基础编写，Fuzz 测试函数，自动生成随机输入，发现代码崩溃 panic。
 | 原文链接：http://book.gay65g.asia/blog/551630.Doc

原标题：git stash 代码暂存切换分支
简介：批量数据处理脚本编写技巧，编写脚本批量处理大量业务数据，循环处理、分批执行，提升数据处理效率。
 | 原文链接：http://book.gay65g.asia/blog/045390.Doc

原标题：JSON XML 数据解析处理示例
简介：消息消费重试次数限制防爆炸，限制消息最大重试次数，防止失败消息无限重试造成消息爆炸堆积。
 | 原文链接：http://book.gay65g.asia/blog/078016.Doc

原标题：golang 系统设计内部服务熔断降级配置思路
简介：golang 响应 body 流式返回大数据，http 流式输出数据，边生成边返回，无需在内存组装完整返回结果。
 | 原文链接：http://book.gay65g.asia/blog/569408.Doc

原标题：记一次本地运行正常，线上环境报错诡异问题
简介：golang tcp_NODELAY 关闭延迟发送，设置 tcp_NODELAY，关闭 Nagle 算法，降低小包请求延迟。
 | 原文链接：http://book.gay65g.asia/blog/381519.Doc

原标题：golang 系统设计故障定位排查通用步骤方法论
简介：golang time 时间格式化避坑，Go 时间格式化参考时间牢记，处理时间解析格式化，解决时间输出错乱。
 | 原文链接：http://book.gay65g.asia/blog/188868.Doc

原标题：golang ci 流水线代码质量扫描集成
简介：golang go 版本管理 go install 安装工具，go install 安装指定版本 go 工具，管理本地 go 工具版本。
 | 原文链接：http://book.gay65g.asia/blog/164790.Doc

原标题：golang 系统设计 docker compose 本地开发环境搭建
简介：axios 二次封装请求拦截处理，对 axios 做二次封装，统一请求拦截响应拦截，处理错误、token 自动刷新。
 | 原文链接：http://book.gay65g.asia/blog/914119.Doc

原标题：容器资源限制防止宿主机过载
简介：golang go get 升级降级依赖版本，go get 指定版本升级降级依赖包，管理第三方库版本。
 | 原文链接：http://book.gay65g.asia/blog/173243.Doc

原标题：golang 系统设计 tcp 粘包拆包处理方案实现
简介：golang nats jetstream 持久消息队列，nats jetstream 持久化消息，保证消息不丢失，实现可靠消费。
 | 原文链接：http://book.gay65g.asia/blog/606242.Doc

原标题：Nginx 透传真实客户端 IP 配置
简介：golang grpc 拦截器开发鉴权日志，开发 grpc 服务端拦截器，统一做鉴权、日志打印、异常捕获处理。
 | 原文链接：http://book.gay65g.asia/blog/673027.Doc

原标题：开发复盘：数据库批量更新优化性能实践
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://book.gay65g.asia/blog/272138.Doc

原标题：配置外部化线上部署防错误
简介：WSL 文件权限访问异常修复，处理 WSL 环境文件权限错乱，调整权限配置，实现文件正常读写访问。
 | 原文链接：http://book.gay65g.asia/blog/128244.Doc

原标题：Hands‑on：本地模拟分布式锁失效场景测试
简介：从零编写简易 CLI 命令行工具，通过实战案例实现基础命令交互，理解命令行程序执行逻辑，产出可运行小工具。
 | 原文链接：http://book.gay65g.asia/blog/170772.Doc

原标题：前端图片懒加载性能优化
简介：golang goreleaser 自动版本发布打包，goreleaser 自动化打包发布，生成多平台二进制归档文件。
 | 原文链接：http://book.gay65g.asia/blog/924512.Doc

原标题：动态定时任务业务调度实现
简介：golang http 中间件洋葱模型原理，理解 go http 中间件洋葱模型，请求响应流转顺序，编写自定义中间件。
 | 原文链接：http://book.gay65g.asia/blog/812912.Doc

原标题：实战项目：编写Dockerfile多阶段构建减小镜像体积
简介：nodejs 进程间通信 IPC 实操，演示 Node.js 主进程子进程 IPC 通信，进程之间传递消息数据。
 | 原文链接：http://book.gay65g.asia/blog/481140.Doc

原标题：Security：Web常见安全漏洞原理与修复清单
简介：磁盘 inode 耗尽文件创建失败，排查磁盘 inode 占用，清理大量小文件，恢复文件创建能力。
 | 原文链接：http://book.gay65g.asia/blog/358806.Doc

原标题：golang docker 部署 mysql 注意事项
简介：golang channel 作为函数参数方向，声明 channel 入参方向，只读 channel 只写 channel 提升代码约束。
 | 原文链接：http://book.gay65g.asia/blog/527376.Doc

原标题：记一次分库分表路由计算错误数据写入错误分片
简介：golang go cover 覆盖率报告生成，go test‑cover 生成测试覆盖率，html 可视化查看未覆盖代码行。
 | 原文链接：http://book.gay65g.asia/blog/081414.Doc

原标题：语义化版本依赖管理防错乱
简介：service‑worker 离线缓存实践，使用 ServiceWorker 实现静态资源离线缓存，弱网环境页面依然可访问。
 | 原文链接：http://book.gay65g.asia/blog/599615.Doc

原标题：Practice：实现请求重试组件支持退避策略
简介：数据库索引重建提升查询速度，针对碎片化索引，重建数据库索引，恢复 SQL 查询执行性能。
 | 原文链接：http://book.gay65g.asia/blog/941849.Doc

原标题：Troubleshoot：DNS解析异常导致第三方调用失败
简介：批量数据处理脚本编写技巧，编写脚本批量处理大量业务数据，循环处理、分批执行，提升数据处理效率。
 | 原文链接：http://book.gay65g.asia/blog/599987.Doc

原标题：golang 时间时区处理避坑指南
简介：golang time 时间格式化参考时间牢记，2006‑01‑02T15:04:05Z07:00，掌握 go 时间格式化关键点。
 | 原文链接：http://book.gay65g.asia/blog/540088.Doc

原标题：本地运行正常线上报错排查
简介：文件分片上传断点续传功能，实现文件分片上传，记录上传进度，支持断点续传大文件上传。
 | 原文链接：http://book.gay65g.asia/blog/193262.Doc

原标题：Docker 多阶段构建镜像瘦身
简介：golang 多协程任务池并发控制，实现协程任务池，控制并发协程数量，防止无限制创建 goroutine。
 | 原文链接：http://book.gay65g.asia/blog/011104.Doc

原标题：golang 系统设计滑动窗口限流代码示例
简介：RPC 报文大小上限调优大请求，调大 RPC 框架报文最大限制，支持传输大体积请求报文不被截断。
 | 原文链接：http://book.gay65g.asia/blog/647764.Doc

原标题：Issue：本地数据库与线上数据库排序规则差异
简介：golang 数据库连接耗尽排查思路，监控连接池状态，定位连接未归还，解决连接耗尽报错。
 | 原文链接：http://book.gay65g.asia/blog/852360.Doc

原标题：golang 系统设计架构图绘图工具选型对比
简介：浏览器本地存储安全使用技巧，讲解 localStorage、sessionStorage 使用边界，规避 XSS 泄露存储数据。
 | 原文链接：http://book.gay65g.asia/blog/305549.Doc

原标题：文件编码统一随机乱码修复
简介：从零编写简易 CLI 命令行工具，通过实战案例实现基础命令交互，理解命令行程序执行逻辑，产出可运行小工具。
 | 原文链接：http://book.gay65g.asia/blog/041598.Doc

原标题：golang mysql 长连接短连接对比
简介：golang json number 数字不转 float64，使用 json.Number 保留原始数字字符串，防止大数字精度丢失。
 | 原文链接：http://book.gay65g.asia/blog/166620.Doc

原标题：golang 优雅处理系统信号 SIGINT
简介：golang trace 工具采集 go 程序执行轨迹，go trace 采集程序完整调度轨迹，分析协程调度阻塞问题。
 | 原文链接：http://book.gay65g.asia/blog/019544.Doc

原标题：踩坑：大报文传输，RPC消息超过大小限制
简介：golang time 时间格式化避坑，Go 时间格式化参考时间牢记，处理时间解析格式化，解决时间输出错乱。
 | 原文链接：http://book.gay65g.asia/blog/181147.Doc

原标题：缓存过期打散防止缓存雪崩
简介：端口占用访问失败排查方案，讲解端口占用排查命令，定位占用进程，释放端口，解决服务启动端口被占用报错。
 | 原文链接：http://book.gay65g.asia/blog/604584.Doc

原标题：golang jaeger 链路追踪 go 接入
简介：golang tidb 数据库 go 项目适配，go 程序适配 tidb，兼容 mysql 协议，分布式数据库业务开发。
 | 原文链接：http://book.gay65g.asia/blog/871104.Doc

原标题：golang 系统设计技术文档维护更新最佳实践
简介：golang 程序崩溃 core dump 生成调试，开启 core dump，程序崩溃生成转储文件，事后分析崩溃原因。
 | 原文链接：http://book.gay65g.asia/blog/293125.Doc

原标题：Hands‑on：简易消息推送服务开发实践
简介：golang clickhouse go 客户端数据写入，clickhouse‑go 客户端写入查询，海量时序数据分析业务。
 | 原文链接：http://book.gay65g.asia/blog/602883.Doc

原标题：线上异常：缓存雪崩带来数据库压力瞬间飙升
简介：golang grpc 客户端拦截器封装，grpc 客户端拦截器实现请求统一签名、重试、链路信息透传。
 | 原文链接：http://book.gay65g.asia/blog/861197.Doc

原标题：Security：Web常见安全漏洞原理与修复清单
简介：vue3 组合式 API 业务开发实战，Vue3 组合式 API 业务实战示例，拆分业务逻辑组合复用，提升代码组织。
 | 原文链接：http://book.gay65g.asia/blog/567794.Doc

原标题：golang 系统设计第三方接口调用封装思路
简介：golang time.After 内存泄漏场景，for 循环使用 time.After 会创建大量 timer，造成内存泄漏。
 | 原文链接：http://book.gay65g.asia/blog/586388.Doc

三、实战开发｜Practice
原标题：golang 系统设计链路追踪架构简单讲解
简介：golang 容器健康检查接口开发，Go 开发 HTTP 健康接口，供容器编排工具探测实例存活状态。
 | 原文链接：http://book.gay65g.asia/blog/176270.Doc

原标题：golang 系统设计缓存空值防止缓存穿透实现
简介：新手参与开源社区贡献指南，介绍开源社区基础规则，讲解阅读 issue、提交 PR 流程，指导开发者参与开源贡献。
 | 原文链接：http://book.gay65g.asia/blog/290948.Doc

原标题：实践：前后端分离项目登录状态保持完整方案
简介：golang go 排序 sort 包自定义排序，sort 包实现自定义排序逻辑，对切片按业务规则排序。
 | 原文链接：http://book.gay65g.asia/blog/689118.Doc

原标题：golang 系统设计消息 partition 数量设置思路
简介：后端分页查询逻辑代码实现，编写后端分页接口，处理页码、每页条数参数，优化大数据量查询返回结果。
 | 原文链接：http://book.gay65g.asia/blog/508451.Doc

原标题：Architecture：配置中心架构，动态配置设计思路
简介：消息队列消费堆积扩容处理，消息大量堆积时，扩容消费实例，优化消费逻辑，加快消息处理速度。
 | 原文链接：http://book.gay65g.asia/blog/341085.Doc

原标题：golang 系统设计开源版本发布 changelog 维护
简介：golang go 程序守护进程实现思路，go 程序不做 daemon 化，依靠 systemd pm2 k8s 实现进程守护。
 | 原文链接：http://book.gay65g.asia/blog/399810.Doc

原标题：请求工具封装统一异常处理
简介：ORM 隐式慢查询问题规避，识别 ORM 框架隐式查询，避免循环查询数据库，减少不必要慢 SQL 产生。
 | 原文链接：http://book.gay65g.asia/blog/568679.Doc

原标题：golang 系统设计代码仓库权限管理方案
简介：golang lru 缓存淘汰算法编写，手写 LRU 缓存淘汰算法，实现本地缓存，淘汰最久未使用数据。
 | 原文链接：http://book.gay65g.asia/blog/089927.Doc

原标题：golang docker 镜像安全扫描漏洞
简介：任务执行锁防止并发重复调度，增加任务执行锁，多实例环境，防止同一个定时任务并发多次运行。
 | 原文链接：http://book.gay65g.asia/blog/189161.Doc

原标题：避坑：CookieSecure属性造成测试环境登录失败
简介：golang word 文档生成处理 go 方案，go 生成 word 文档报表，填充文本表格，输出 docx 文件。
 | 原文链接：http://book.gay65g.asia/blog/048213.Doc

原标题：golang redis 大 key 识别处理方案
简介：golang 错误静默忽略风险规避，禁止空忽略错误，必须处理或者明确注释为什么忽略错误。
 | 原文链接：http://book.gay65g.asia/blog/178917.Doc

原标题：方案对比：单体、微服务、模块化单体取舍
简介：golang mysql 慢查询日志程序采集解析，程序读取解析 mysql 慢查询日志，统计慢 SQL 做监控告警。
 | 原文链接：http://book.gay65g.asia/blog/856493.Doc

原标题：git cherry‑pick 规范操作防 bug
简介：css 动画性能优化 GPU 加速，优化 CSS 动画，使用 GPU 加速属性，避免动画过程页面卡顿掉帧。
 | 原文链接：http://book.gay65g.asia/blog/464518.Doc

原标题：新手指南：读懂项目构建脚本作用
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：http://book.gay65g.asia/blog/523352.Doc

原标题：Practice：实现文件监控自动重启开发服务工具
简介：TCP 心跳检测清理僵死连接，开启 TCP 心跳机制，自动清理僵死无效连接，释放连接资源。
 | 原文链接：http://book.gay65g.asia/blog/427948.Doc

原标题：golang 系统设计大表结构变更不停机方案
简介：限流规则误拦截正常请求修复，修正限流规则阈值，避免合法用户被限流拦截，兼顾防护与可用性。
 | 原文链接：http://book.gay65g.asia/blog/531280.Doc

原标题：方案对比：同步调用vs异步消息业务选型
简介：golang clickhouse go 客户端数据写入，clickhouse‑go 客户端写入查询，海量时序数据分析业务。
 | 原文链接：http://book.gay65g.asia/blog/503830.Doc

原标题：从零搭建简单CLI命令行工具
简介：golang go 终端 pty 伪终端操作，pty 启动子进程，模拟终端交互，实现交互式命令调用。
 | 原文链接：http://book.gay65g.asia/blog/269018.Doc

原标题：实战：Redis过期回调实现业务事件通知实践
简介：golang goroutine 池任务调度，实现 goroutine 池，复用协程，频繁任务场景减少协程创建销毁开销。
 | 原文链接：http://book.gay65g.asia/blog/156541.Doc

原标题：记一次升级操作系统内核引发服务不稳定
简介：golang go‑fuzz 模糊测试开发，go fuzz 模糊测试，自动构造异常输入，发现代码隐藏 bug。
 | 原文链接：http://book.gay65g.asia/blog/088396.Doc

原标题：Security：Web常见安全漏洞原理与修复清单
简介：前端图片懒加载性能优化，实现图片懒加载，页面可视区域才加载图片，减少页面初始网络请求。
 | 原文链接：http://book.gay65g.asia/blog/891435.Doc

原标题：方案设计：统一错误处理架构全链路方案
简介：golang go‑zero 配置中心热更新，go‑zero 对接 etcd 配置中心，配置热更新无需重启服务。
 | 原文链接：http://book.gay65g.asia/blog/452761.Doc

原标题：数据库读写分离性能优化
简介：golang 高并发下锁优化减少竞争，减小锁粒度，读写锁替换互斥锁，无锁编程降低锁竞争开销。
 | 原文链接：http://book.gay65g.asia/blog/804850.Doc

原标题：service‑worker 离线缓存实践
简介：代码模块化组件化拆分思路，讲解代码拆分原则，将大业务拆分为独立模块组件，提升代码复用与维护能力。
 | 原文链接：http://book.gay65g.asia/blog/621864.Doc

原标题：golang redis 热点 key 业务规避
简介：Spring 事务传播机制配置生效，理解事务传播行为，正确配置，修复事务不生效、事务失效的业务 bug。
 | 原文链接：http://book.gay65g.asia/blog/741877.Doc

原标题：golang mysql 联合索引最左匹配
简介：golang http3 quic 客户端服务端示例，go 实现 http3 quic 服务端客户端，体验 quic 协议低延迟特性。
 | 原文链接：http://book.gay65g.asia/blog/871329.Doc

原标题：架构复盘：业务系统中如何合理使用分库分表
简介：nodejs 内存溢出问题排查修复，Node.js 程序 OOM 排查流程，定位内存泄露，调整内存限制修复崩溃。
 | 原文链接：http://book.gay65g.asia/blog/189961.Doc

原标题：安全复盘：Redis未授权访问漏洞防护
简介：nodejs 进程间通信 IPC 实操，演示 Node.js 主进程子进程 IPC 通信，进程之间传递消息数据。
 | 原文链接：http://book.gay65g.asia/blog/522393.Doc

原标题：Practice：实现接口签名、验签完整示例代码
简介：防火墙 IP 白名单回调接口放行，配置防火墙白名单，放行第三方回调服务器 IP，接收回调请求正常。
 | 原文链接：http://book.gay65g.asia/blog/788875.Doc

原标题：Architecture：静态资源分发CDN整体架构思路
简介：eslint prettier 代码规范落地，配置 eslint 与 prettier，做代码检查格式化，统一前端团队代码风格。
 | 原文链接：http://book.gay65g.asia/blog/463216.Doc

原标题：pnpm 包管理工具实战避坑指南
简介：重复提交幂等防护再次讲解，梳理前端重复点击、网络重试场景，落地接口幂等，杜绝重复业务。
 | 原文链接：http://book.gay65g.asia/blog/465798.Doc

原标题：运维笔记：服务器定时任务运维脚本编写
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://book.gay65g.asia/blog/451361.Doc

原标题：Issue：文件编码混合GBKUTF‑8乱码随机出现
简介：golang 重试退避机制代码实现，Go 实现请求重试与指数退避，处理临时故障，提升调用稳定性。
 | 原文链接：http://book.gay65g.asia/blog/644955.Doc

原标题：记一次升级操作系统内核引发服务不稳定
简介：golang defer panic 异常处理，理解 defer 延迟执行，panic 恐慌捕获，实现函数资源释放异常保护。
 | 原文链接：http://book.gay65g.asia/blog/493610.Doc

原标题：nodejs 数据库连接池配置调优
简介：golang 日志按日期切割实现方案，实现日志文件按天切割，自动归档旧日志，防止单个日志文件过大。
 | 原文链接：http://book.gay65g.asia/blog/294046.Doc

原标题：JWT 令牌过期异常处理
简介：golang csv 读写批量数据处理，Go 读写 CSV 文件，批量导入导出业务数据，处理 CSV 格式解析。
 | 原文链接：http://book.gay65g.asia/blog/783472.Doc

原标题：golang mysql 行锁表锁场景区分
简介：模拟登录鉴权权限判断示例，实现简易登录流程，会话状态维护，完成接口权限校验，理解身份鉴权基础逻辑。
 | 原文链接：http://book.gay65g.asia/blog/314824.Doc

原标题：Troubleshooting：防火墙安全组拦截访问请求
简介：golang go‑zero 框架项目快速搭建，go‑zero 脚手架生成微服务项目，api rpc 服务快速开发。
 | 原文链接：http://book.gay65g.asia/blog/308878.Doc

原标题：golang 系统设计分布式任务调度
简介：gRPC 服务端客户端入门示例，搭建 gRPC 服务端与调用客户端，学习 protobuf 定义，掌握 RPC 基础开发流程。
 | 原文链接：http://book.gay65g.asia/blog/015518.Doc

原标题：golang cron 定时任务防并发执行
简介：日志敏感信息脱敏泄露防护，日志打印时自动脱敏手机号身份证，避免日志输出泄露用户隐私数据。
 | 原文链接：http://book.gay65g.asia/blog/040430.Doc

四、架构设计｜Architecture
原标题：快速入门OpenAPI文档生成基础实践
简介：前端水印防信息泄露实现，实现网页水印功能，页面叠加用户信息水印，防止页面截图信息外泄。
 | 原文链接：http://book.gay65g.asia/blog/798164.Doc

原标题：golang 系统设计 hot‑reload 热重载 go 开发工具
简介：golang go 初始化顺序包变量 init 函数，包级变量初始化，init 执行顺序，理解包加载执行流程。
 | 原文链接：http://book.gay65g.asia/blog/052332.Doc

原标题：缓存过期策略优化防业务故障
简介：golang go http 静态文件禁止目录遍历，http.FileServer 防止../ 路径穿越，了解底层安全实现。
 | 原文链接：http://book.gay65g.asia/blog/191527.Doc

原标题：Hands‑on：简易代理服务器开发实践
简介：静态博客部署 GitHub Pages 教程，将静态博客项目部署至 GitHub Pages，完成线上访问，快速搭建个人技术博客站点。
 | 原文链接：http://book.gay65g.asia/blog/128439.Doc

原标题：调优方案：容器CPU内存参数压测后调优
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://book.gay65g.asia/blog/471153.Doc

原标题：快速入门异步编程基础模型
简介：golang 互斥锁读写锁并发安全，互斥锁读写锁实操，保护共享变量，解决多协程并发读写数据竞争。
 | 原文链接：http://book.gay65g.asia/blog/829886.Doc

原标题：看懂报错日志快速定位问题
简介：golang http MaxHeaderBytes 限制请求头，设置 http 最大请求头大小，防止超大 header 攻击。
 | 原文链接：http://book.gay65g.asia/blog/055052.Doc

原标题：安全组端口开放网络访问
简介：Git LFS 大文件推送失败解决，配置 Git LFS，处理仓库大文件，解决大文件推送报错推送失败。
 | 原文链接：http://book.gay65g.asia/blog/745154.Doc

原标题：快速入门gRPC基础概念与简单示例
简介：golang context.WithValue 传递元数据，WithValue 只传 traceId 鉴权元数据，不要传业务大对象。
 | 原文链接：http://book.gay65g.asia/blog/670225.Doc

原标题：方案设计：统一ID生成服务架构对比雪花算法
简介：golang go json 序列化自定义字段，json 标签控制字段名称、忽略字段、omitempty 空值忽略。
 | 原文链接：http://book.gay65g.asia/blog/674599.Doc

原标题：限流窗口绕过漏洞修复方案
简介：golang go 信号处理优雅重启实现，USR2 触发程序重启，不关闭监听 socket 实现零停机升级。
 | 原文链接：http://book.gay65g.asia/blog/237904.Doc

原标题：nodejs 项目 pm2 部署运维指南
简介：内网 DNS 不稳定随机报错排查，定位内网 DNS 抖动问题，配置备选 DNS，解决偶现域名解析失败。
 | 原文链接：http://book.gay65g.asia/blog/003219.Doc

原标题：性能笔记：RPC超时参数优化防止级联阻塞
简介：vite 项目配置与构建提速技巧，讲解 vite 配置优化手段，提升开发热更新速度与生产构建打包效率。
 | 原文链接：http://book.gay65g.asia/blog/159897.Doc

原标题：Troubleshoot：批量导入数据，事务过大回滚日志暴涨
简介：golang 本地消息表实现最终一致性，本地消息表 + 定时任务轮询，可靠消息实现分布式事务。
 | 原文链接：http://book.gay65g.asia/blog/204289.Doc

原标题：Issue：本地可以访问，容器内部网络不通
简介：进程线程并发基础概念讲解，区分进程与线程，讲解调度逻辑，理解并发执行原理，为高并发业务开发打基础。
 | 原文链接：http://book.gay65g.asia/blog/015416.Doc

原标题：golang context 上下文传参讲解
简介：OAuth2 第三方登录服务搭建，搭建 OAuth2 服务，支持第三方账号登录，实现授权登录能力。
 | 原文链接：http://book.gay65g.asia/blog/350305.Doc

原标题：golang 错误处理最佳实践汇总
简介：程序性能指标 CPU 内存监控，讲解基础性能指标含义，简单实现监控采集，初步定位程序运行性能瓶颈。
 | 原文链接：http://book.gay65g.asia/blog/026134.Doc

原标题：Practice：实现限流之后友好业务返回处理
简介：文件编码统一随机乱码修复，统一项目全部文件读写编码，消除随机中文乱码，保证文本处理稳定。
 | 原文链接：http://book.gay65g.asia/blog/563846.Doc

?
