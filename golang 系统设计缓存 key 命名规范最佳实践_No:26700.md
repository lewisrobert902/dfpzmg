最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计缓存 key 命名规范最佳实践
简介：golang kitex 中间件与元数据传递，kitex 自定义中间件，透传 traceId 鉴权元数据，统一处理请求。
 | 原文链接：http://wiki.rzgou0.asia/arts/19721465.html

原标题：容器软链接文件权限修复
简介：提交第一个开源 PR 完整流程，Fork 项目、修改代码、提交 Pull Request，讲解 PR 规范，提升合并通过率。
 | 原文链接：http://wiki.rzgou0.asia/arts/47548704.html

原标题：Issue：日志输出包含敏感信息造成泄露风险
简介：rebase 操作防止代码丢失，讲解 rebase 风险点，操作前做好备份，规避错误操作造成代码提交丢失。
 | 原文链接：http://wiki.rzgou0.asia/arts/52263897.html

原标题：golang 系统设计唯一索引业务使用场景
简介：golang channel 作为函数参数方向，声明 channel 入参方向，只读 channel 只写 channel 提升代码约束。
 | 原文链接：http://wiki.rzgou0.asia/arts/64704600.html

原标题：nodejs 信号处理优雅关闭服务
简介：golang 消息死信处理业务逻辑，Go 实现死信队列逻辑，消费失败消息转入死信，不阻塞正常消息队列。
 | 原文链接：http://wiki.rzgou0.asia/arts/87511043.html

原标题：golang redis 分布式锁 redisson 思路
简介：API 大版本不兼容平滑迁移，API 版本迭代不兼容旧接口，设计平滑迁移方案，逐步完成版本切换。
 | 原文链接：http://wiki.rzgou0.asia/arts/01882796.html

原标题：缓存过期打散防止缓存雪崩
简介：golang 表格驱动测试完整示例，表格驱动多组输入输出，批量执行测试用例，减少重复代码。
 | 原文链接：http://wiki.rzgou0.asia/arts/35942094.html

原标题：Practice：实现请求body重复读取中间件实践
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://wiki.rzgou0.asia/arts/19116895.html

原标题：一次JWT令牌过期时间异常问题复盘
简介：缓存过期打散防止缓存雪崩，对缓存过期时间增加随机偏移，避免大量缓存同时失效引发缓存雪崩。
 | 原文链接：http://wiki.rzgou0.asia/arts/52638649.html

原标题：golang lru 缓存淘汰算法编写
简介：golang go 随机数安全与非安全，math/rand 伪随机与 crypto/rand 密码学安全随机，区分业务场景。
 | 原文链接：http://wiki.rzgou0.asia/arts/18336642.html

原标题：接口签名验签完整安全方案
简介：序列化版本不一致解析失败，保证序列化对象版本对齐，修复版本不匹配导致对象反序列化失败。
 | 原文链接：http://wiki.rzgou0.asia/arts/86252321.html

原标题：golang consul 服务发现简单示例
简介：golang 数据库连接耗尽排查思路，监控连接池状态，定位连接未归还，解决连接耗尽报错。
 | 原文链接：http://wiki.rzgou0.asia/arts/93350629.html

原标题：文件描述符优化进程卡死修复
简介：DNS TTL 配置域名切换生效，调整 DNS 解析 TTL，缩短缓存时间，域名变更后可以快速全网生效。
 | 原文链接：http://wiki.rzgou0.asia/arts/05294507.html

原标题：Issue：防火墙拦截ICMP，MTU问题网络丢包
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：http://wiki.rzgou0.asia/arts/55476341.html

原标题：golang 数据库批量更新性能优化
简介：TLS 版本兼容 HTTPS 握手失败，兼容老旧 TLS 协议版本，修复部分客户端 HTTPS 握手失败无法访问。
 | 原文链接：http://wiki.rzgou0.asia/arts/59078143.html

原标题：坑点：缓存穿透，大量无效请求打穿数据库
简介：golang 数据库连接泄露排查，定位 Go 数据库连接泄露，连接没有归还池，导致连接耗尽报错。
 | 原文链接：http://wiki.rzgou0.asia/arts/77231970.html

原标题：golang websocket 消息广播实现
简介：golang errgroup 协程组错误处理，errgroup 捕获协程错误，context 取消剩余协程，简化并发任务。
 | 原文链接：http://wiki.rzgou0.asia/arts/89321556.html

原标题：动态定时任务业务调度实现
简介：nodejs 单元测试 jest 实操教程，Jest 单元测试实操，编写测试用例，mock 依赖，验证业务逻辑正确性。
 | 原文链接：http://wiki.rzgou0.asia/arts/60478826.html

原标题：nestjs 拦截器过滤器管道实战
简介：跨域偶现失败配置修复，解决跨域问题时而复现时而正常，定位配置漏配、请求头异常等隐性问题。
 | 原文链接：http://wiki.rzgou0.asia/arts/63771853.html

原标题：入门实践：简易导出导入文件功能实现
简介：service‑worker 离线缓存实践，使用 ServiceWorker 实现静态资源离线缓存，弱网环境页面依然可访问。
 | 原文链接：http://wiki.rzgou0.asia/arts/38720869.html

原标题：golang pprof 线上采集性能数据
简介：golang go 错误包装 fmt.Errorf % w，使用 % w 包装错误，支持 errors.Is errors.As 判断错误类型。
 | 原文链接：http://wiki.rzgou0.asia/arts/00750545.html

原标题：golang redis 缓存预热实现思路
简介：端口占用访问失败排查方案，讲解端口占用排查命令，定位占用进程，释放端口，解决服务启动端口被占用报错。
 | 原文链接：http://wiki.rzgou0.asia/arts/28436770.html

原标题：实践：代码提交前自动格式化校验配置实践
简介：接口幂等性防重复请求实现，实现接口幂等逻辑，避免重复提交请求产生多条脏数据，保障业务数据安全。
 | 原文链接：http://wiki.rzgou0.asia/arts/99736078.html

原标题：golang 系统设计分表扩容数据平滑迁移思路
简介：Nginx 缓冲区调优大文件上传，调大 Nginx 请求缓冲区，支持客户端上传大体积文件，避免上传被截断。
 | 原文链接：http://wiki.rzgou0.asia/arts/32900783.html

原标题：坑点：gitpull冲突处理不当造成代码丢失
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://wiki.rzgou0.asia/arts/10277963.html

原标题：架构笔记：海量日志处理架构选型与实践
简介：golang redis pipeline 批量操作，使用 Redis Pipeline 批量执行多条命令，减少网络往返，提升批量操作性能。
 | 原文链接：http://wiki.rzgou0.asia/arts/32148827.html

原标题：移动端适配 rem vw 方案对比
简介：异步任务堆积消费能力优化，处理消息任务堆积问题，提升消费处理速度，恢复队列正常处理水位。
 | 原文链接：http://wiki.rzgou0.asia/arts/01285365.html

原标题：数值 key 浮点匹配异常规避
简介：nodejs http 服务性能调优实战，调优 Node HTTP 服务内核参数，连接复用，提升接口并发处理能力。
 | 原文链接：http://wiki.rzgou0.asia/arts/72736064.html

原标题：Hands‑on：简易连接池原型实现理解原理
简介：超大数据集分页性能优化方案，对比不同分页方案，针对海量数据集做分页性能优化，解决越翻越慢。
 | 原文链接：http://wiki.rzgou0.asia/arts/52528011.html

原标题：golang etcd 分布式锁实现原理
简介：golang k8s go 服务 yaml 资源编写，k8s 部署 go 应用 deployment service，健康检查资源限制配置。
 | 原文链接：http://wiki.rzgou0.asia/arts/96179584.html

原标题：golang gitlab runner 部署与注册实操
简介：golang go 模板缓存预编译模板，预编译 html 模板，程序启动加载，避免每次请求解析模板损耗性能。
 | 原文链接：http://wiki.rzgou0.asia/arts/25700399.html

原标题：golang 分布式 ID 雪花算法实现
简介：golang 跨平台系统差异处理方案，处理 windows linux mac 路径、信号、文件权限差异，代码跨平台兼容。
 | 原文链接：http://wiki.rzgou0.asia/arts/99396398.html

原标题：nodejs redis 缓存业务实战
简介：读懂开源项目 README 实用技巧，教你快速解析开源项目说明文档，提取安装、运行、配置关键信息，快速上手项目。
 | 原文链接：http://wiki.rzgou0.asia/arts/81380029.html

原标题：Troubleshoot：磁盘打满导致服务全部不可用
简介：golang etcd key 监听变更 watch 机制，watch 监听 etcd 键变化，配置变更实时感知，实现配置热更新。
 | 原文链接：http://wiki.rzgou0.asia/arts/58473214.html

原标题：golang 系统设计排行榜几种实现
简介：golang 容器内读取 k8s 配置 configmap，程序读取 k8s configmap 配置，配置与镜像分离便于运维。
 | 原文链接：http://wiki.rzgou0.asia/arts/66584268.html

原标题：实战项目：搭建本地Mock服务快速开发联调
简介：golang go 整洁架构代码组织实践，整洁架构依赖向内，解耦业务逻辑与外部基础设施。
 | 原文链接：http://wiki.rzgou0.asia/arts/97263101.html

原标题：golang 系统设计技术债务识别登记治理思路
简介：golang 单例模式实现几种方式，Go 单例模式多种实现对比，sync.Once 等方式，实现全局唯一实例。
 | 原文链接：http://wiki.rzgou0.asia/arts/01741915.html

原标题：golang 系统设计 rest http 方法使用原则
简介：ORM 隐式慢查询问题规避，识别 ORM 框架隐式查询，避免循环查询数据库，减少不必要慢 SQL 产生。
 | 原文链接：http://wiki.rzgou0.asia/arts/45692999.html

原标题：消息队列消费堆积扩容处理
简介：系统时间同步定时任务偏移，同步服务器系统时间，防止时间偏移，避免定时任务执行时间错乱。
 | 原文链接：http://wiki.rzgou0.asia/arts/69451776.html

原标题：部署复盘：蓝绿发布实现零停机业务更新
简介：golang go decimal 定点小数金额计算，decimal 库处理金额，规避 float64 精度丢失，财务计算。
 | 原文链接：http://wiki.rzgou0.asia/arts/49237903.html


二、踩坑排错｜Troubleshooting
原标题：数值 key 浮点匹配异常规避
简介：golang gin 框架接口开发实战，Gin 框架搭建 HTTP 服务，开发增删改查接口，快速完成后端接口开发。
 | 原文链接：http://wiki.rzgou0.asia/arts/01504374.html

原标题：从零搭建简单定时任务demo
简介：golang cgo 性能开销避坑指南，cgo 调用开销，减少频繁 cgo 调用，规避 cgo 带来内存泄漏风险。
 | 原文链接：http://wiki.rzgou0.asia/arts/12625049.html

原标题：golang 系统设计消息体序列化选型对比
简介：缓存基础原理与简单代码实现，讲解缓存设计思路，编写简易缓存逻辑，减少重复计算与重复请求，提升程序响应速度。
 | 原文链接：http://wiki.rzgou0.asia/arts/53114554.html

原标题：复盘总结：分布式系统常见坑点汇总清单
简介：golang 配置热更新不重启服务，实现配置热加载，监听配置变更，更新内存配置，无需重启服务实例。
 | 原文链接：http://wiki.rzgou0.asia/arts/24214270.html

原标题：golang 系统设计 go netpoll 多路复用简单理解
简介：golang go 初始化顺序包变量 init 函数，包级变量初始化，init 执行顺序，理解包加载执行流程。
 | 原文链接：http://wiki.rzgou0.asia/arts/57023422.html

原标题：踩坑：大事务引发数据库连接池耗尽
简介：golang 集成测试测试数据库回滚，集成测试结束自动回滚数据库，不污染测试环境数据。
 | 原文链接：http://wiki.rzgou0.asia/arts/29234745.html

原标题：设计思考：缓存分层架构设计与失效处理策略
简介：golang 静态文件服务搭建教程，Go 搭建静态文件服务，托管静态资源，实现文件直接对外访问。
 | 原文链接：http://wiki.rzgou0.asia/arts/82219155.html

原标题：golang 系统设计多级缓存更新策略
简介：全局本地依赖隔离冲突规避，区分全局依赖与项目本地依赖，隔离环境，防止全局包干扰项目运行。
 | 原文链接：http://wiki.rzgou0.asia/arts/66551548.html

原标题：灰度发布策略服务平滑升级
简介：golang 系统 IO 阻塞 goroutine 场景，理解系统调用阻塞 M，P 会调度其他 M，掌握 go 调度行为。
 | 原文链接：http://wiki.rzgou0.asia/arts/86011774.html

原标题：golang docker 部署 mongodb 开发环境
简介：golang 图片处理 go 图片裁剪压缩，golang 图像处理库，图片缩放裁剪水印，服务端图片处理。
 | 原文链接：http://wiki.rzgou0.asia/arts/87446322.html

原标题：golang 系统设计 go netpoll 多路复用简单理解
简介：ORM 隐式慢查询问题规避，识别 ORM 框架隐式查询，避免循环查询数据库，减少不必要慢 SQL 产生。
 | 原文链接：http://wiki.rzgou0.asia/arts/34423172.html

原标题：部署复盘：金丝雀发布流量切分实操方案
简介：golang 项目目录分层规范设计，Go 后端项目目录分层规范，按领域分层，提高项目可读性可维护性。
 | 原文链接：http://wiki.rzgou0.asia/arts/16923416.html

原标题：效率笔记：调试网络请求curl命令高级用法
简介：pnpm 包管理工具实战避坑指南，使用 pnpm 管理项目依赖，梳理常见坑点，充分利用 pnpm 优势。
 | 原文链接：http://wiki.rzgou0.asia/arts/76986167.html

原标题：踩坑记录：端口被占用导致服务启动失败
简介：热更新开发环境配置教程，配置代码热重载，修改代码无需重启服务立即生效，大幅提升本地开发调试效率。
 | 原文链接：http://wiki.rzgou0.asia/arts/14190321.html

原标题：性能笔记：TCP参数内核调优服务高并发场景
简介：golang influxdb 时序数据库读写操作，influxdb 存储时序指标，业务指标监控数据存取。
 | 原文链接：http://wiki.rzgou0.asia/arts/49871200.html

原标题：方案对比：本地缓存vs分布式缓存架构取舍
简介：nodejs 跨域中间件配置细节，Express 跨域中间件配置细节，处理预检请求，修复偶现跨域失效。
 | 原文链接：http://wiki.rzgou0.asia/arts/97028358.html

原标题：golang 系统设计分表跨表 join 业务处理方案
简介：Fork 开源项目同步上游代码，Fork 开源仓库之后，配置上游源，同步官方最新代码，保持代码版本对齐。
 | 原文链接：http://wiki.rzgou0.asia/arts/56071821.html

原标题：Practice：模拟网络抖动验证服务容错能力
简介：golang contract 契约测试微服务，微服务契约测试，保证接口变更不破坏调用方，提前发现兼容性问题。
 | 原文链接：http://wiki.rzgou0.asia/arts/40410938.html

原标题：方案设计：统一错误处理架构全链路方案
简介：golang grpc protobuf 开发实操，Go gRPC 开发，编写 Protobuf 定义，服务端客户端完整示例。
 | 原文链接：http://wiki.rzgou0.asia/arts/61425028.html

原标题：ORM 框架数据库增删改查实操
简介：golang docker compose 开发环境 go 服务，docker compose 编排 go 服务与中间件，本地一键拉起整套开发环境。
 | 原文链接：http://wiki.rzgou0.asia/arts/68459097.html

原标题：golang k8s 监控 prometheus 部署
简介：golang 结构体零值可用性原则，go 结构体尽量做到零值可用，不用初始化直接使用提升易用性。
 | 原文链接：http://wiki.rzgou0.asia/arts/62473816.html

原标题：设计思考：API网关和BFF职责边界划分
简介：golang tcp 四次挥手 go 程序行为，理解 tcp 四次挥手，处理连接关闭、重置、RST 包异常场景。
 | 原文链接：http://wiki.rzgou0.asia/arts/52858886.html

原标题：安全实践：敏感信息加密存储传输完整方案
简介：golang 日志级别动态调整热更新，不用重启程序动态修改日志输出级别，线上调试排查问题十分方便。
 | 原文链接：http://wiki.rzgou0.asia/arts/12534207.html

原标题：golang prometheus 告警规则编写
简介：数据库索引重建提升查询速度，针对碎片化索引，重建数据库索引，恢复 SQL 查询执行性能。
 | 原文链接：http://wiki.rzgou0.asia/arts/46319866.html

原标题：Debug：表单提交特殊字符造成接口解析失败
简介：golang redis stream 消息队列实战，redis stream 实现可靠消息队列，消费组、ack 确认，消息不丢失。
 | 原文链接：http://wiki.rzgou0.asia/arts/88694766.html

原标题：golang docker 部署 es 本地开发
简介：磁盘 inode 耗尽文件创建失败，排查磁盘 inode 占用，清理大量小文件，恢复文件创建能力。
 | 原文链接：http://wiki.rzgou0.asia/arts/97418752.html

原标题：排错：HTTPS证书过期导致接口调用失败
简介：golang go 泛型约束与类型集合，泛型 type set 约束，限制泛型支持类型，写出安全泛型代码。
 | 原文链接：http://wiki.rzgou0.asia/arts/36752836.html

原标题：排错：反向代理后获取真实IP全部变成内网IP
简介：项目构建脚本编译打包解析，解读项目构建脚本，理清编译、压缩、资源复制流程，理解打包后产物如何生成。
 | 原文链接：http://wiki.rzgou0.asia/arts/44448763.html

原标题：设计思考：分布式系统时钟同步带来的架构问题
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://wiki.rzgou0.asia/arts/23210251.html

原标题：新手教程：Git撤销错误提交的几种常用方式
简介：hosts 配置本地回环访问修复，修改 hosts 配置，修复 127.0.0.1 解析异常，本地服务访问失败问题。
 | 原文链接：http://wiki.rzgou0.asia/arts/79945443.html

原标题：架构复盘：服务灰度发布架构设计与流量切分
简介：golang go 比较运算符可比较类型，哪些类型可以直接 == 比较，map slice 函数不可直接比较。
 | 原文链接：http://wiki.rzgou0.asia/arts/64464509.html

原标题：坑点：限流计数器重置时机错误，绕过限流规则
简介：API 接口调试与异常处理实战，覆盖接口请求、参数组装、错误捕获，提供调试思路，高效定位接口返回异常问题。
 | 原文链接：http://wiki.rzgou0.asia/arts/39963252.html

原标题：golang 系统设计消息大小限制业务处理方案
简介：golang bufio 缓冲读写性能优化，bufio 带缓冲读写，减少系统调用，提升文件网络 IO 性能。
 | 原文链接：http://wiki.rzgou0.asia/arts/82326792.html

原标题：RPC 报文大小上限调优大请求
简介：nestjs 全局返回格式统一处理，Nest 全局拦截器统一包装接口返回数据，对外输出标准化响应格式。
 | 原文链接：http://wiki.rzgou0.asia/arts/59755897.html

原标题：方案设计：异步解耦业务架构边界识别
简介：CLI 工具进度条交互效果开发，在命令行工具增加进度条展示，直观反馈任务执行进度，优化命令行体验。
 | 原文链接：http://wiki.rzgou0.asia/arts/14009319.html

原标题：golang 系统设计分布式锁超时业务防死锁处理
简介：golang 日志 zap 结构化日志实践，接入 Zap 结构化日志库，打印结构化日志，方便日志检索解析。
 | 原文链接：http://wiki.rzgou0.asia/arts/70922263.html

原标题：架构复盘：消息队列在业务系统中边界与最佳实践
简介：Git 代码冲突正确处理方式，讲解冲突产生场景，演示冲突文件修改，正确合并代码，防止代码丢失。
 | 原文链接：http://wiki.rzgou0.asia/arts/31294037.html

原标题：架构笔记：海量消息堆积架构处理能力设计
简介：golang k8s secret 敏感配置加载，加载 k8s secret 存储密钥密码，敏感信息不存放配置文件。
 | 原文链接：http://wiki.rzgou0.asia/arts/83641631.html

原标题：GraphQL 接口查询优化实操
简介：golang uuid 生成多种版本实现，生成 uuid v1 v4，生成唯一标识，业务用于单据编号场景。
 | 原文链接：http://wiki.rzgou0.asia/arts/68207356.html

原标题：DNS TTL 配置域名切换生效
简介：系统字符集统一乱码修复，统一数据库、程序、操作系统字符集，解决中文乱码显示异常问题。
 | 原文链接：http://wiki.rzgou0.asia/arts/97450492.html

三、实战开发｜Practice
原标题：golang mysql 慢查询日志开启分析
简介：全平台系统环境变量配置，汇总多操作系统环境变量配置方法，统一项目读取逻辑，适配不同运行平台。
 | 原文链接：http://wiki.rzgou0.asia/arts/89290229.html

原标题：golang 系统设计事务消息 rocketmq 简单原理
简介：DNS 解析异常第三方调用故障，排查 DNS 解析故障，修复域名解析，恢复第三方接口网络调用。
 | 原文链接：http://wiki.rzgou0.asia/arts/94088506.html

原标题：环境变量不生效问题修复
简介：数据库索引重建提升查询速度，针对碎片化索引，重建数据库索引，恢复 SQL 查询执行性能。
 | 原文链接：http://wiki.rzgou0.asia/arts/86619384.html

原标题：从零学习简单分页逻辑实现思路
简介：分布式锁失效问题排查修复，分析分布式锁失效场景，修复锁超时、续期问题，保证锁逻辑可靠。
 | 原文链接：http://wiki.rzgou0.asia/arts/13927229.html

原标题：设计思考：大促系统架构压测改造整体思路
简介：golang 压缩 zip 文件生成解压，golang 实现 zip 压缩打包，解压 zip 归档文件，处理批量文件归档。
 | 原文链接：http://wiki.rzgou0.asia/arts/81996236.html

原标题：golang 系统设计防重复提交实现
简介：golang io.LimitReader 限制读取字节数，LimitReader 限制最大读取，防止读取超大数据。
 | 原文链接：http://wiki.rzgou0.asia/arts/05572050.html

原标题：golang 系统设计容器镜像安全加固要点
简介：golang bufio 缓冲读写性能优化，bufio 带缓冲读写，减少系统调用，提升文件网络 IO 性能。
 | 原文链接：http://wiki.rzgou0.asia/arts/51752767.html

原标题：golang 集成测试启动测试数据库
简介：golang go 无锁并发编程技巧，原子操作 sync/atomic，简单场景替换锁，提升并发性能。
 | 原文链接：http://wiki.rzgou0.asia/arts/35463272.html

原标题：Shell 运维脚本服务器效率提升
简介：golang 项目 go mod 依赖管理，Go Mod 管理项目依赖，下载、升级、清理依赖，解决依赖版本管理。
 | 原文链接：http://wiki.rzgou0.asia/arts/05574279.html

原标题：golang docker 基础命令实操汇总
简介：Shell 运维脚本服务器效率提升，编写常用运维 Shell 脚本，自动化服务器运维操作，减少手工重复工作。
 | 原文链接：http://wiki.rzgou0.asia/arts/75786424.html

原标题：golang 系统设计配置敏感信息加密存储方案
简介：golang go 程序权限最小化运行，容器内使用普通用户运行程序，拒绝 root 运行提升安全等级。
 | 原文链接：http://wiki.rzgou0.asia/arts/27022020.html

原标题：Hands‑on：简易代理服务器开发实践
简介：webpack chunk 分包策略详解，讲解 webpack chunk 分包策略，拆分第三方包与业务代码，优化缓存复用。
 | 原文链接：http://wiki.rzgou0.asia/arts/46556091.html

原标题：Practice：从零实现轻量后端接口服务完整实践
简介：golang os.Exit 退出程序注意 defer 不执行，os.Exit 会直接退出，不会执行 defer，优雅退出不要直接 os.Exit。
 | 原文链接：http://wiki.rzgou0.asia/arts/01757109.html

原标题：golang github actions 多平台构建
简介：golang staticcheck 静态代码分析，staticcheck 深度静态检查，发现代码错误、性能问题、风格问题。
 | 原文链接：http://wiki.rzgou0.asia/arts/24089725.html

原标题：golang ci 流水线单元测试集成测试
简介：golang rate‑limiter 限流组件，封装通用 Go 限流组件，支持多算法，业务接口直接复用调用。
 | 原文链接：http://wiki.rzgou0.asia/arts/19547320.html

原标题：golang 信号捕获程序退出处理
简介：golang net/url 路径拼接处理，url.ParseRequestURI 处理请求 url，正确拼接 url 路径避免拼接错误。
 | 原文链接：http://wiki.rzgou0.asia/arts/08767192.html

原标题：图片上传预览格式大小处理
简介：golang go‑zero 分布式锁组件使用，go‑zero 内置 redis 分布式锁，业务直接调用实现并发控制。
 | 原文链接：http://wiki.rzgou0.asia/arts/54755022.html

原标题：缓存穿透击穿雪崩全套防护
简介：golang CPU 绑定亲和性设置 go 程序，设置进程 CPU 亲和绑定核心，减少 CPU 调度开销，提升计算性能。
 | 原文链接：http://wiki.rzgou0.asia/arts/56945277.html

原标题：AI实践：大模型生成测试用例实践与校验
简介：文件描述符优化进程卡死修复，及时关闭文件句柄，控制打开文件数量，解决文件句柄耗尽进程卡死。
 | 原文链接：http://wiki.rzgou0.asia/arts/75886492.html

原标题：部署实践：服务器防火墙安全组配置实践
简介：golang http 代理客户端配置，Go HTTP Client 配置代理，通过代理服务器发起网络请求。
 | 原文链接：http://wiki.rzgou0.asia/arts/82052543.html

原标题：golang 跨域处理中间件编写
简介：空指针异常判空容错处理，讲解空指针产生场景，规范判空逻辑，增加容错，避免空指针直接造成程序崩溃。
 | 原文链接：http://wiki.rzgou0.asia/arts/40955358.html

原标题：开发记录：JWT过期刷新滑动过期实现实践
简介：golang go work 多模块本地开发，go work 多模块本地同时开发，本地模块互相引用，无需推送仓库。
 | 原文链接：http://wiki.rzgou0.asia/arts/04570414.html

原标题：分页逻辑错误数据漏查修复
简介：golang go math 大数高精度计算，math/big 处理超大整数、高精度浮点数，金额大数运算。
 | 原文链接：http://wiki.rzgou0.asia/arts/74486014.html

原标题：vue3 组合式 API 业务开发实战
简介：灰度发布策略服务平滑升级，实现灰度发布逻辑，流量逐步切到新版本，出现问题快速回滚旧版本。
 | 原文链接：http://wiki.rzgou0.asia/arts/47632670.html

原标题：Cookie Session 会话状态管理
简介：golang context.WithValue 传递元数据，WithValue 只传 traceId 鉴权元数据，不要传业务大对象。
 | 原文链接：http://wiki.rzgou0.asia/arts/37636940.html

原标题：效率笔记：VSCode插件集合后端前端开发效率
简介：前端虚拟列表大数据渲染优化，实现虚拟滚动列表，只渲染可视区域 DOM，上万条数据页面流畅渲染。
 | 原文链接：http://wiki.rzgou0.asia/arts/66181131.html

原标题：golang 系统设计网关错误重试超时处理策略
简介：golang time 时间格式化避坑，Go 时间格式化参考时间牢记，处理时间解析格式化，解决时间输出错乱。
 | 原文链接：http://wiki.rzgou0.asia/arts/89125263.html

原标题：golang http grpc 全链路埋点示例
简介：golang 日志按日期切割实现方案，实现日志文件按天切割，自动归档旧日志，防止单个日志文件过大。
 | 原文链接：http://wiki.rzgou0.asia/arts/56671829.html

原标题：安全笔记：CORS跨域配置错误安全风险
简介：时间同步修复令牌提前过期，服务器时间不同步导致 JWT 令牌提前过期，同步系统时间解决异常。
 | 原文链接：http://wiki.rzgou0.asia/arts/63776045.html

原标题：golang 协程 panic 捕获防止崩溃
简介：静态站点自动部署发布方案，配置流水线，代码更新自动构建静态站点并且部署上线，简化发布。
 | 原文链接：http://wiki.rzgou0.asia/arts/58347818.html

原标题：golang kafka 生产者参数调优
简介：golang go 爬虫请求速率控制，爬虫限频、代理轮换，设置 UA，防止爬虫被目标站点封禁 IP。
 | 原文链接：http://wiki.rzgou0.asia/arts/55044587.html

原标题：Security：反序列化漏洞风险识别与规避
简介：golang 限流熔断放在代理层实践，代理层统一限流熔断，对后端服务做流量保护。
 | 原文链接：http://wiki.rzgou0.asia/arts/71568596.html

原标题：数据库连接池参数调优
简介：进程线程并发基础概念讲解，区分进程与线程，讲解调度逻辑，理解并发执行原理，为高并发业务开发打基础。
 | 原文链接：http://wiki.rzgou0.asia/arts/15032538.html

原标题：golang 系统设计主干开发 trunk‑based 讲解
简介：golang go‑zero 框架项目快速搭建，go‑zero 脚手架生成微服务项目，api rpc 服务快速开发。
 | 原文链接：http://wiki.rzgou0.asia/arts/59188480.html

原标题：golang mongodb 分页性能优化技巧
简介：golang net.Listener 包装自定义监听器，包装 Listener 做连接计数、连接拦截，扩展网络能力。
 | 原文链接：http://wiki.rzgou0.asia/arts/74932567.html

原标题：nodejs 接口限流防刷代码实现
简介：golang panic 崩溃日志完整收集，捕获所有 panic，打印堆栈，记录日志，方便定位崩溃根源。
 | 原文链接：http://wiki.rzgou0.asia/arts/41821820.html

原标题：Git 标签版本标记发布管理
简介：服务健康检查告警监控体系，搭建健康检查加告警体系，服务异常及时推送告警通知运维人员。
 | 原文链接：http://wiki.rzgou0.asia/arts/36155485.html

原标题：开发复盘：内存缓存LRU淘汰策略实现实践
简介：golang excel 大文件读取流式解析，流式读取大 excel 文件，逐行解析数据，不加载全部内容进内存。
 | 原文链接：http://wiki.rzgou0.asia/arts/12672430.html

原标题：新手避坑：第一次提交GitHub项目完整流程
简介：golang accept 错误循环崩溃处理，accept 返回系统错误，处理临时错误，避免死循环占满 CPU。
 | 原文链接：http://wiki.rzgou0.asia/arts/65985702.html

原标题：Troubleshooting：代理环境下证书校验失败HTTPS报错
简介：golang go 应用内存使用优化手段，减少对象分配，复用对象，降低 GC 压力，减少 GC 停顿时间。
 | 原文链接：http://wiki.rzgou0.asia/arts/84941626.html

四、架构设计｜Architecture
原标题：Dockerfile 编写容器打包实战
简介：golang 数据库分表策略按时间分片，按时间维度分表，历史数据拆分，单表数据量控制保证查询性能。
 | 原文链接：http://wiki.rzgou0.asia/arts/20917289.html

原标题：大事务拆分防止连接池耗尽
简介：golang go‑zero 分布式锁组件使用，go‑zero 内置 redis 分布式锁，业务直接调用实现并发控制。
 | 原文链接：http://wiki.rzgou0.asia/arts/75133589.html

原标题：golang 工具函数库封装思路
简介：golang 消息队列中间件选型对比，kafka redis‑stream rabbitmq，对比吞吐量可靠性选型参考。
 | 原文链接：http://wiki.rzgou0.asia/arts/00528593.html

原标题：GraphQL 接口查询优化实操
简介：golang 系统信号信号量处理，Go 处理系统各类信号，SIGINT、SIGTERM，实现程序可控退出。
 | 原文链接：http://wiki.rzgou0.asia/arts/42347118.html

原标题：Issue：本地可以访问，容器内部网络不通
简介：golang url 参数编码处理方案，Go URL 参数编码解码，处理特殊字符，避免 URL 参数错乱。
 | 原文链接：http://wiki.rzgou0.asia/arts/22881614.html

原标题：golang goroutine 池任务调度
简介：golang cgroup 读取容器资源限制，go 程序读取 cgroup，获取容器 cpu 内存限额，适配容器环境。
 | 原文链接：http://wiki.rzgou0.asia/arts/09169236.html

原标题：golang mysql 存储过程简单使用
简介：css 动画性能优化 GPU 加速，优化 CSS 动画，使用 GPU 加速属性，避免动画过程页面卡顿掉帧。
 | 原文链接：http://wiki.rzgou0.asia/arts/05000782.html

原标题：golang 结构体 json 序列化坑点
简介：golang gorm 原生 SQL 执行处理，复杂场景执行原生 SQL，处理返回结果集，兼顾性能与灵活性。
 | 原文链接：http://wiki.rzgou0.asia/arts/88346701.html

原标题：限流组件计数器令牌桶模式实现
简介：git rebase 整理提交历史实操，使用 rebase 整理杂乱提交记录，将多条提交合并，保持 git 提交历史干净线性。
 | 原文链接：http://wiki.rzgou0.asia/arts/08643718.html

原标题：golang 系统设计服务优雅停机完整流程
简介：golang dns 自定义解析器实现，自定义 dns 解析，指定 dns 服务器，控制域名解析逻辑，适配内网环境。
 | 原文链接：http://wiki.rzgou0.asia/arts/34966364.html

原标题：入门实践：项目配置文件多环境管理方案
简介：golang context.WithCancel 手动取消上下文，WithCancel 生成可取消 ctx，手动调用 cancel 触发取消。
 | 原文链接：http://wiki.rzgou0.asia/arts/07252455.html

原标题：入门实践：简单重试逻辑封装实现
简介：golang redis hash 结构业务实战，使用 Redis Hash 存储对象数据，适合对象字段频繁更新业务场景。
 | 原文链接：http://wiki.rzgou0.asia/arts/84632300.html

原标题：坑点：Git仓库过大，clone速度极慢解决方案
简介：前端组件库按需加载性能优化，配置组件库按需引入，避免引入全部组件，减少打包产物体积。
 | 原文链接：http://wiki.rzgou0.asia/arts/57951499.html

原标题：golang 系统设计缓存更新策略 cache aside 讲解
简介：golang http 客户端连接泄漏排查，http client 未读取响应体导致连接无法复用，解决连接泄漏耗尽连接池。
 | 原文链接：http://wiki.rzgou0.asia/arts/55306778.html

原标题：golang 系统设计线上日志快速检索技巧
简介：OAuth2 第三方登录服务搭建，搭建 OAuth2 服务，支持第三方账号登录，实现授权登录能力。
 | 原文链接：http://wiki.rzgou0.asia/arts/70598560.html

原标题：DevOps：多环境镜像标签版本管理规范
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://wiki.rzgou0.asia/arts/41041411.html

原标题：超大数据集分页性能优化方案
简介：全局异常处理器接口返回统一，接入全局异常捕获，拦截业务全部异常，对外输出统一格式返回值。
 | 原文链接：http://wiki.rzgou0.asia/arts/69277482.html

原标题：golang 系统设计线上问题复现思路简单讲解
简介：golang go‑zero 框架项目快速搭建，go‑zero 脚手架生成微服务项目，api rpc 服务快速开发。
 | 原文链接：http://wiki.rzgou0.asia/arts/36498990.html

原标题：Git 混乱提交历史清理方法
简介：golang go get 升级降级依赖版本，go get 指定版本升级降级依赖包，管理第三方库版本。
 | 原文链接：http://wiki.rzgou0.asia/arts/25011428.html

原标题：golang 系统设计内部服务契约测试简单思路
简介：全局异常处理器接口返回统一，接入全局异常捕获，拦截业务全部异常，对外输出统一格式返回值。
 | 原文链接：http://wiki.rzgou0.asia/arts/77331996.html

原标题：大文件导出内存溢出防护
简介：echarts 大数据渲染性能调优，大数据量 ECharts 图表调优，数据采样、分片渲染，解决图表卡顿。
 | 原文链接：http://wiki.rzgou0.asia/arts/73428188.html

原标题：复盘总结：接口重构兼容旧版本改造复盘
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://wiki.rzgou0.asia/arts/93299337.html

原标题：golang 系统设计 rest 错误返回格式统一规范
简介：容器资源限制防止宿主机过载，设置容器 CPU 内存资源上限，避免单个容器耗尽宿主机全部硬件资源。
 | 原文链接：http://wiki.rzgou0.asia/arts/00609063.html

原标题：golang k8s secret 加密敏感信息
简介：golang go 线上故障排查完整流程，CPU 高、内存上涨、接口超时、goroutine 泄露一套排查处理流程。
 | 原文链接：http://wiki.rzgou0.asia/arts/29296635.html

原标题：golang toml 配置文件解析教程
简介：golang go mod graph 可视化依赖图，可视化 go 依赖关系，直观看到包之间依赖，定位冲突。
 | 原文链接：http://wiki.rzgou0.asia/arts/44676146.html

原标题：golang context 上下文传参讲解
简介：golang 内存 pprof 定位内存泄漏，pprof 分析内存快照，定位内存泄露对象，解决 Go 程序内存持续上涨。
 | 原文链接：http://wiki.rzgou0.asia/arts/66881549.html

原标题：golang redis bitmap 位图统计实现
简介：golang go yaml 解析自定义类型，yaml 自定义序列化，时间、特殊类型自定义解析逻辑。
 | 原文链接：http://wiki.rzgou0.asia/arts/00984521.html

原标题：Hands‑on：代码生成器，一键生成CRUD模板
简介：golang sftp 文件上传下载操作，sftp 协议远程文件上传下载，实现服务器之间文件传输功能。
 | 原文链接：http://wiki.rzgou0.asia/arts/41933412.html

原标题：golang 系统设计采样策略降低链路存储开销
简介：golang go mod graph 可视化依赖图，可视化 go 依赖关系，直观看到包之间依赖，定位冲突。
 | 原文链接：http://wiki.rzgou0.asia/arts/48371829.html

原标题：记一次分布式锁失效引发的数据错乱问题
简介：JSON XML 数据解析处理示例，演示两种格式数据解析与序列化，增加异常捕获，处理格式错乱导致解析失败。
 | 原文链接：http://wiki.rzgou0.asia/arts/73709847.html

原标题：golang 系统设计消息堆积排查扩容完整步骤
简介：内存广播本地进程消息通知，实现进程内内存消息广播，进程内部模块之间事件通知解耦。
 | 原文链接：http://wiki.rzgou0.asia/arts/34269964.html

原标题：golang docker 部署 mongodb 开发环境
简介：golang go 并发模式 errgroup 使用，errgroup 结合 context，协程组，任意协程出错整体取消任务。
 | 原文链接：http://wiki.rzgou0.asia/arts/51603374.html

原标题：golang 系统设计监控大盘故障快速定位思路
简介：golang go 初始化顺序包变量 init 函数，包级变量初始化，init 执行顺序，理解包加载执行流程。
 | 原文链接：http://wiki.rzgou0.asia/arts/25484489.html

原标题：快速入门Nginx基础配置，反向代理示例
简介：WSL 文件权限访问异常修复，处理 WSL 环境文件权限错乱，调整权限配置，实现文件正常读写访问。
 | 原文链接：http://wiki.rzgou0.asia/arts/81004452.html

原标题：手写简易 ORM 理解对象映射
简介：内存溢出问题现象识别排查，识别内存溢出现象，梳理排查方向，定位内存持续上涨引发服务崩溃问题。
 | 原文链接：http://wiki.rzgou0.asia/arts/21032381.html

原标题：golang 系统设计接口超时设计原则梳理
简介：golang interface {} 类型断言类型转换，类型断言 ok 模式，避免断言失败触发 panic。
 | 原文链接：http://wiki.rzgou0.asia/arts/27048341.html

原标题：golang 内存缓存简单实现方案
简介：golang go 模板执行错误捕获，捕获模板执行错误，防止模板错误直接返回空白页面。
 | 原文链接：http://wiki.rzgou0.asia/arts/57933566.html

原标题：记一次本地运行正常，线上环境报错诡异问题
简介：项目目录结构规范化最佳实践，梳理源码、配置、静态资源目录划分，规范项目布局，提升代码可读性和可维护性。
 | 原文链接：http://wiki.rzgou0.asia/arts/16675646.html

原标题：golang redis pipeline 原子性说明
简介：golang gif 图片帧处理操作，解析 gif 图片帧，压缩、拆分 gif 动图，处理动图业务。
 | 原文链接：http://wiki.rzgou0.asia/arts/07859961.html

原标题：开源实践：开源项目本地调试构建排坑经验
简介：慢查询分析索引调优数据库实战，抓取慢查询，分析执行计划，优化索引，解决数据库慢查询拖慢业务。
 | 原文链接：http://wiki.rzgou0.asia/arts/07292262.html

五、文体娱乐
原标题：golang 系统设计分表跨表 join 业务处理方案
简介：golang k8s informer 机制原理理解，informer 监听 k8s 资源变更，本地缓存，减少 apiserver 压力。
 | 原文链接：http://wiki.rzgou0.asia/arts/30551599.html

原标题：文件编码统一随机乱码修复
简介：golang redis geo 地理位置存储查询，Redis GEO 存储经纬度，查询附近点位，实现附近人业务功能。
 | 原文链接：http://wiki.rzgou0.asia/arts/85384413.html

原标题：golang 系统设计 json 解析性能优化实操
简介：golang 系统信号信号量处理，Go 处理系统各类信号，SIGINT、SIGTERM，实现程序可控退出。
 | 原文链接：http://wiki.rzgou0.asia/arts/99439975.html

原标题：golang 系统设计 go benchmark 性能测试实操
简介：golang go json 序列化自定义字段，json 标签控制字段名称、忽略字段、omitempty 空值忽略。
 | 原文链接：http://wiki.rzgou0.asia/arts/43824549.html

原标题：golang 消息队列 kafka 消费开发
简介：golang 后端节点健康检查机制实现，定时探测后端节点状态，自动剔除故障节点，保障转发可用。
 | 原文链接：http://wiki.rzgou0.asia/arts/40402855.html

原标题：Git 子模块更新代码不全修复
简介：golang 数据库 ORM 框架选型对比，gorm xorm sqlx 对比各 ORM 优缺点，根据业务场景选型。
 | 原文链接：http://wiki.rzgou0.asia/arts/71893464.html

原标题：对象存储上传下载权限实操
简介：golang go mod graph 可视化依赖图，可视化 go 依赖关系，直观看到包之间依赖，定位冲突。
 | 原文链接：http://wiki.rzgou0.asia/arts/23359569.html

原标题：golang 系统设计技术债务识别登记治理思路
简介：golang 容器时区设置镜像构建处理，镜像内部设置正确时区，解决容器时间与宿主机不一致。
 | 原文链接：http://wiki.rzgou0.asia/arts/89508128.html

原标题：性能笔记：压测如何定位真实系统瓶颈
简介：nodejs 流处理大文件不占内存，使用 Node.js 流处理超大文件，边读边写，不需要全部加载进内存。
 | 原文链接：http://wiki.rzgou0.asia/arts/67012438.html

原标题：Architecture：大文件上传下载系统架构设计
简介：golang go 运行时获取编译信息，程序内部读取编译时间 git 版本，接口输出程序版本信息。
 | 原文链接：http://wiki.rzgou0.asia/arts/83831432.html

原标题：项目实践：消息队列消息堆积模拟处理实践
简介：golang 僵尸进程处理 go 程序，正确等待子进程退出，避免产生僵尸进程，占用系统进程表。
 | 原文链接：http://wiki.rzgou0.asia/arts/74785085.html

原标题：golang 系统设计 mq 消息顺序性保证思路
简介：golang 数据库连接池泄露检测逻辑，监控连接池状态，检测连接长时间未归还，告警连接泄漏问题。
 | 原文链接：http://wiki.rzgou0.asia/arts/13911256.html

原标题：调优方案：消息批量消费提升MQ处理吞吐量
简介：开发代理服务网络限制解决，搭建本地代理服务，解决开发环境网络访问受限，实现外部接口正常调用。
 | 原文链接：http://wiki.rzgou0.asia/arts/25275152.html

原标题：Debug：消息队列死信队列堆积无人处理业务阻塞
简介：golang alertmanager 告警配置实践，alertmanager 配置告警路由，告警发送邮件钉钉，异常及时通知运维。
 | 原文链接：http://wiki.rzgou0.asia/arts/20601347.html

原标题：开源实践：开源Issue沟通技巧如何有效提Bug
简介：静态资源 404 路径打包修复，修复打包后静态资源访问 404，调整资源输出路径，保证资源正常加载。
 | 原文链接：http://wiki.rzgou0.asia/arts/13385754.html

原标题：项目实践：OpenTelemetry链路追踪本地部署实践
简介：nodejs 跨域中间件配置细节，Express 跨域中间件配置细节，处理预检请求，修复偶现跨域失效。
 | 原文链接：http://wiki.rzgou0.asia/arts/08823209.html

原标题：文件读写与异常捕获代码示例
简介：配置与镜像分离防止信息泄露，业务配置不打包进镜像，外部挂载配置，避免密钥配置随镜像泄露。
 | 原文链接：http://wiki.rzgou0.asia/arts/08882065.html

原标题：从零学习简单分布式ID生成思路
简介：CI 流水线超时时间延长配置，调大 CI 任务超时阈值，解决构建任务耗时较长被流水线强制终止。
 | 原文链接：http://wiki.rzgou0.asia/arts/94199566.html

原标题：golang mongodb 索引优化查询速度
简介：golang channel 缓冲无缓冲区别，缓冲 channel 与无缓冲 channel，底层行为差异业务选型参考。
 | 原文链接：http://wiki.rzgou0.asia/arts/16542028.html

原标题：golang 项目 makefile 脚本编写
简介：MySQL 慢查询索引优化实战，抓取慢查询 SQL，分析执行计划，新增或者调整索引，提升 SQL 执行速度。
 | 原文链接：http://wiki.rzgou0.asia/arts/31682422.html

原标题：线上故障：消息队列重复消费业务处理异常
简介：CI 持续集成自动构建流程，讲解 CI 基础概念，配置流水线实现代码提交后自动构建、测试，提升交付自动化。
 | 原文链接：http://wiki.rzgou0.asia/arts/75829359.html

原标题：实战项目：容器资源限制配置压力测试实践
简介：本地运行正常线上报错排查，对比本地与线上环境差异，从配置、系统版本、文件权限定位线上独有的 bug。
 | 原文链接：http://wiki.rzgou0.asia/arts/27156866.html

原标题：Performance：避免循环查询N+1问题完整优化
简介：GitHub Markdown 文档语法汇总，整理 Markdown 常用语法，编写仓库 README、文档，提升开源项目文档排版质量。
 | 原文链接：http://wiki.rzgou0.asia/arts/63749343.html

原标题：golang 系统设计网关 websocket 转发配置要点
简介：golang go proxy 私有代理配置，配置 go proxy 私有代理，加速依赖下载，内网环境构建项目。
 | 原文链接：http://wiki.rzgou0.asia/arts/23907680.html

原标题：golang docker 私有仓库搭建使用
简介：golang fuzz corpus 语料库使用，fuzz 语料存储历史输入，回归测试，持续复现曾经触发 bug 输入。
 | 原文链接：http://wiki.rzgou0.asia/arts/82756532.html

原标题：一次JWT令牌过期时间异常问题复盘
简介：golang go race 竞态检测工具，‑race 检测数据竞争，编译运行检测并发读写数据竞争 bug。
 | 原文链接：http://wiki.rzgou0.asia/arts/67359839.html

原标题：跨平台 uniapp 多端开发实操
简介：日志敏感信息脱敏泄露防护，日志打印时自动脱敏手机号身份证，避免日志输出泄露用户隐私数据。
 | 原文链接：http://wiki.rzgou0.asia/arts/58642835.html

原标题：入门实战：搭建简易静态网页项目
简介：开发代理服务网络限制解决，搭建本地代理服务，解决开发环境网络访问受限，实现外部接口正常调用。
 | 原文链接：http://wiki.rzgou0.asia/arts/38498189.html

原标题：前端打包分包加载提速方案
简介：业务幂等键设计防重复逻辑，讲解幂等键设计思路，选择合适业务字段作为幂等标识，实现可靠防重复。
 | 原文链接：http://wiki.rzgou0.asia/arts/92140474.html

原标题：golang 系统设计 jmeter 简单压测脚本编写
简介：golang gorm 批量插入性能调优，GORM 批量插入优化，调整批次大小，提升大量数据插入数据库速度。
 | 原文链接：http://wiki.rzgou0.asia/arts/37916088.html

原标题：GC 垃圾回收优化降低 CPU 占用
简介：CORS 跨域问题多种解决方案，对比 CORS、代理等不同跨域方案优缺点，根据业务场景选择合适的跨域处理方式。
 | 原文链接：http://wiki.rzgou0.asia/arts/60995693.html

原标题：nodejs jwt 登录鉴权完整示例
简介：golang gorm group by 分组统计，GORM 分组聚合统计，实现 count sum 等统计查询，快速完成统计业务。
 | 原文链接：http://wiki.rzgou0.asia/arts/72960275.html

原标题：线上故障：第三方接口超时未设置熔断雪崩
简介：简易日志收集集中管理方案，搭建轻量日志收集方案，把多服务日志汇总，集中检索查看日志信息。
 | 原文链接：http://wiki.rzgou0.asia/arts/99125493.html

原标题：golang 重试退避机制代码实现
简介：golang hertz 反向代理与负载均衡，hertz 实现反向代理，内置负载均衡，快速搭建网关类服务。
 | 原文链接：http://wiki.rzgou0.asia/arts/97311979.html

原标题：开发记录：长连接连接管理自动清理僵死连接
简介：golang 微服务网关简易实现，http 反向代理、路由匹配、鉴权限流，理解网关核心原理。
 | 原文链接：http://wiki.rzgou0.asia/arts/31452850.html

原标题：Architecture：安全防护架构XSSCSRFSQL注入防御
简介：golang redis scan 遍历 key 避免阻塞，使用 scan 迭代遍历 redis 键，不用 keys 命令，防止阻塞 redis 服务。
 | 原文链接：http://wiki.rzgou0.asia/arts/56975391.html

原标题：极简 API 网关路由转发实现
简介：Docker 容器时区错误修复方案，修复 Docker 容器内部时区偏差，解决容器内时间不对引发业务逻辑异常。
 | 原文链接：http://wiki.rzgou0.asia/arts/08537375.html

原标题：golang http 服务性能优化调参
简介：正则表达式文本处理实战案例，结合业务场景演示正则匹配、提取、替换，处理手机号、邮箱等各类文本校验需求。
 | 原文链接：http://wiki.rzgou0.asia/arts/13612685.html

原标题：实战：基于内存实现简单消息广播组件
简介：golang gin 框架接口开发实战，Gin 框架搭建 HTTP 服务，开发增删改查接口，快速完成后端接口开发。
 | 原文链接：http://wiki.rzgou0.asia/arts/67794912.html

原标题：golang 系统设计消息体序列化选型对比
简介：golang docker 多阶段构建 go 镜像，Go 项目 Docker 多阶段构建，编译与运行阶段分离，大幅度缩减最终镜像体积，提升镜像分发效率。
 | 原文链接：http://wiki.rzgou0.asia/arts/06212793.html

五、性能优化｜Performance
仓库链接：
https://github.com/garrettjoy2/soaxuk/commit/9ae6b9bf710ae45765721d0a43e617b2650b8648

https://github.com/garciacindy6770/fidydu/commit/2df2a80c0ce474a4910a968d7ac7c686181efd78

https://github.com/piercekevin7/xvuwgj/commit/8716d83bd79a296c2cbdfe742e29d782f6c4f824

https://github.com/nixonscott3145/mooyvl/commit/4fd410301b1e665c42fa2e9e8b5856d86782b951

https://github.com/lopezmatthew5/gnmqar/commit/818e1294e8098333883c468451021e617087b502

https://github.com/lewisrobert902/dfpzmg/commit/e77d90c7875a49d303b12bc013a2e7b7c0db36b8

https://github.com/adamsgregory05/wlqkoi/commit/34e37a5bbfe6a4682006848acd66c0809591c0e4

https://github.com/vargasgary779/xgzyue/commit/9d114a3908c29b16f7244112b0f65e9cd0b1a6e9

https://github.com/reyesvicki427/tfxinp/commit/29604ac4ed41b35fe5a7f30a37faa3de4525bb8a

https://github.com/carrbrian51/fsxudt/commit/07f39da4211779b77e2d33bb0020ec9e8fc634f5

https://github.com/campbellgwendolyn04/rcbwlz/commit/f0d57e13ddb1044f93fb4e0f5f9c3db01ffdac73

https://github.com/kelleymichele2/busbxm/commit/b0b58e1a2d71070cc1a54b4c4d5fb9c445a4a8cd

https://github.com/hamptontiffany427/azlwfb/commit/1ac01f5bed7d0587bdfb1e3c8ff2c00595812fd5

https://github.com/griffineric92/dokwsr/commit/960af9dff192121be01b6a611f48e3c2379ccf92


六、安全｜Security
代码仓库：
https://github.com/mckinneyhannah5539/vpbrak/commit/421ade15cc47a23a2ab8147e299d26ed6003b081

https://github.com/dyerwendy576/yrwibx/commit/3eba0944ddbc303302c17144e1ab62689356c86f

https://github.com/williamslynn4829/scpzcl/commit/8fa1c759f9185bb1d8115fb19351cc9ae79373e6

https://github.com/monroealexis97/ghcmqg/commit/09543cdeb35a48396904acf14e29c6bc1b80f0c7

https://github.com/brewerchristopher8044/utrvqg/commit/72a40f57ac1dd968c26c17426efc6367b6426690

https://github.com/gutierrezcindy3/vamoqy/commit/4ad7bebaf8781cdb3ec23eb26aef21f55d3c3202

https://github.com/browntonya78/nackic/commit/4cf5b2f4cc4091873cad734c7e03b9865027f6d3

https://github.com/allencassandra0463/cvnbsx/commit/7117a25ca751604c7c5b4d5b9177bc984bbab00e

https://github.com/nixonscott3145/mooyvl/commit/ffcf4f4c5d6f8aacd78521d01ba1ee1f5d99bdc0

https://github.com/thomaseileen4/tfblzb/commit/520eb0f57c133fc280b00ee034ceb39dbb9808ae

https://github.com/garrettjoy2/soaxuk/commit/f1e8a9308542adea0d4abd27b11e134c9d67a1c8

https://github.com/popekimberly6070/gcndud/commit/6005f186cc2df8404471b1f45d2640b6d3c8cdd5

https://github.com/lewisrobert902/dfpzmg/commit/c9ccdd873ce8f2f5afd3337eef36a5c9cec0cde7

https://github.com/reyesvicki427/tfxinp/commit/07002f7c1f5548e33fd1b66cfe3da263dd39627b


七、DevOps｜运维部署
参考资料[1]：https://github.com/ballardbarbara3001/bhmqof/commit/73425ee7cc5b035cb5a55a10ff39faf91aeaeb91

参考资料[2]：https://github.com/carrbrian51/fsxudt/commit/f3b8315a4bdd3f399bcc019edfce5ddd81bbd921

参考资料[3]：https://github.com/campbellgwendolyn04/rcbwlz/commit/8168b71d4b08ba8e8137f11fb41b4e81cb6a8af1

参考资料[4]：https://github.com/browntheodore81/scjnsj/commit/6d48639c1ed5f03d449501402b41a26968179cb1

参考资料[5]：https://github.com/haynesbrittany91/atftev/commit/aea7af8ccbcd306bcec92bcdc7eeb4b7d1d548c7


八、开源、效率、AI、总结复盘
开源资料：https://github.com/stonejonathan67/pmzikz/commit/2d122c9d228a222261b9f60d752387b0ee0fb820

开源资料：https://github.com/griffineric92/dokwsr/commit/8d9d01a770fbe133698d0a2afa927137d691a1d8

开源资料：https://github.com/williamslynn4829/scpzcl/commit/6df2402de7cfef0315b078f529fb8244aeefd1a3

开源资料：https://github.com/monroealexis97/ghcmqg/commit/503e9ed567c50a3bf663a4c59f719483a6a8f3bb

开源资料：https://github.com/woodnatalie531/wsunre/commit/9095a9b29cfeab05f1f697852d3e0aa02bcea2f3

开源资料：https://github.com/browntonya78/nackic/commit/2d5a81a04dd99e0ac79562e4e20194238cd8b3f4

开源资料：https://github.com/garciacindy6770/fidydu/commit/8b6f5d08ac3cde0f4971dfaf0c2413201479829e

开源资料：https://github.com/wardgregory26/talhxt/commit/92755cfce9857ced82b65388d8395e007194d72c

开源资料：https://github.com/lewisrobert902/dfpzmg/commit/db7dbd4cfcf64be1069ca6ec7f11dca1f09ef6c3


*数据更新时间：2026年08月23日04时44分51秒(UTC+8)*
*数据采集自，GitHub README、Issues、Blog、技术文档、项目 Wiki，包含：教程、踩坑、实战、架构、性能、部署、排错、最佳实践、复盘、迁移、重构、安全、运维、前端、后端、云原生、AI、效率工具。*
