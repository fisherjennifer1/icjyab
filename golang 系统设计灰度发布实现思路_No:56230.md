最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计灰度发布实现思路
简介：golang net.Listener 包装自定义监听器，包装 Listener 做连接计数、连接拦截，扩展网络能力。
 | 原文链接：http://book.9p2k8h.asia/blog/246761.Doc

原标题：时间同步修复令牌提前过期
简介：golang https 客户端跳过证书校验，开发测试环境跳过 tls 证书校验，仅用于内网测试禁止生产使用。
 | 原文链接：http://book.9p2k8h.asia/blog/615443.Doc

原标题：快速入门对象存储基础使用场景
简介：express 中间件开发业务实践，开发 Express 自定义中间件，拦截请求，实现鉴权、日志记录等通用逻辑。
 | 原文链接：http://book.9p2k8h.asia/blog/010065.Doc

原标题：架构复盘：RPC框架架构超时重试设计要点
简介：golang http client Transport 参数调优，Transport 最大连接空闲连接，TLS 配置，http 客户端调优。
 | 原文链接：http://book.9p2k8h.asia/blog/204224.Doc

原标题：性能笔记：HTTP连接复用性能优化实践
简介：golang 异步任务队列 worker 池开发，任务入数据库或 redis，worker 池消费执行，异步处理耗时业务。
 | 原文链接：http://book.9p2k8h.asia/blog/372483.Doc

原标题：ICMP 放通网络丢包问题修复
简介：golang context 包标准用法规范，context 传递请求元数据、超时、取消，函数第一个参数传入 ctx。
 | 原文链接：http://book.9p2k8h.asia/blog/480684.Doc

原标题：方案设计：异步解耦业务架构边界识别
简介：消息消费重试次数限制防爆炸，限制消息最大重试次数，防止失败消息无限重试造成消息爆炸堆积。
 | 原文链接：http://book.9p2k8h.asia/blog/423525.Doc

原标题：新手指南：项目本地编译输出产物解析
简介：端口占用访问失败排查方案，讲解端口占用排查命令，定位占用进程，释放端口，解决服务启动端口被占用报错。
 | 原文链接：http://book.9p2k8h.asia/blog/663795.Doc

原标题：配置外部化线上部署防错误
简介：读懂开源项目 README 实用技巧，教你快速解析开源项目说明文档，提取安装、运行、配置关键信息，快速上手项目。
 | 原文链接：http://book.9p2k8h.asia/blog/453814.Doc

原标题：golang redis 网络超时参数调优
简介：golang gin 参数绑定 query form json，掌握 Gin 多种参数绑定方式，适配不同请求格式参数读取。
 | 原文链接：http://book.9p2k8h.asia/blog/419557.Doc

原标题：新手教程：gitrebase基础使用与风险提示
简介：golang go 爬虫 robots 协议遵守，解析 robots.txt 规则，控制爬虫抓取范围，合规采集网页数据。
 | 原文链接：http://book.9p2k8h.asia/blog/341762.Doc

原标题：方案对比：轮询长轮询WebSocket推送架构选型
简介：golang excel 大文件读取流式解析，流式读取大 excel 文件，逐行解析数据，不加载全部内容进内存。
 | 原文链接：http://book.9p2k8h.asia/blog/077495.Doc

原标题：排错：静态资源CDN缓存未刷新旧资源持续返回
简介：golang go 调用动态链接库 so 文件，go 加载 so 动态库调用函数，复用编译好的 C 动态库。
 | 原文链接：http://book.9p2k8h.asia/blog/373970.Doc

原标题：踩坑记录：浮点精度错误造成业务计算错误
简介：golang uuid 生成多种版本实现，生成 uuid v1 v4，生成唯一标识，业务用于单据编号场景。
 | 原文链接：http://book.9p2k8h.asia/blog/055863.Doc

原标题：安全实践：容器最小化镜像减少攻击面
简介：golang go 优雅处理信号丢失场景，处理信号丢失、信号被忽略，保障程序可以正常接收终止信号。
 | 原文链接：http://book.9p2k8h.asia/blog/668395.Doc

原标题：OpenSource：如何高效阅读大型开源项目源码
简介：代理 HTTPS 证书访问异常处理，配置代理根证书，解决代理环境 HTTPS 证书校验失败无法访问外网。
 | 原文链接：http://book.9p2k8h.asia/blog/711984.Doc

原标题：Issue：Nginxkeepalive参数不合理大量TIME_WAIT
简介：golang go time 时区数据库内置，go 内置时区数据库，不用系统时区文件，容器时区不依赖系统。
 | 原文链接：http://book.9p2k8h.asia/blog/534729.Doc

原标题：零基础理解跨域问题产生原因与基础方案
简介：golang 命令行交互 cobra 开发 cli，cobra 库开发功能完善命令行工具，子命令参数标志解析。
 | 原文链接：http://book.9p2k8h.asia/blog/318007.Doc

原标题：坑点：Git工作区换行符CRLF/LF跨平台坑
简介：golang redis lua 脚本原子操作，使用 Lua 脚本实现原子逻辑，减少网络往返，保障多命令原子执行。
 | 原文链接：http://book.9p2k8h.asia/blog/433355.Doc

原标题：磁盘占满服务不可用清理方案
简介：数值 key 浮点匹配异常规避，避免浮点数作为 Redis 等存储的 key，防止精度问题引发 key 匹配失败。
 | 原文链接：http://book.9p2k8h.asia/blog/101047.Doc

原标题：golang 系统设计缓存 key 淘汰雪崩防护思路
简介：nodejs 集成测试业务流程编写，编写 Node 集成测试，调用真实接口，验证完整业务链路执行结果。
 | 原文链接：http://book.9p2k8h.asia/blog/534363.Doc

原标题：DevOps：容器网络模式选型与坑点总结
简介：golang 优雅处理数据库事务，Go 数据库事务封装，正确处理事务提交回滚，保证业务数据一致性。
 | 原文链接：http://book.9p2k8h.asia/blog/526818.Doc

原标题：Issue：WSL2内存持续暴涨不自动释放
简介：golang go time 时区数据库内置，go 内置时区数据库，不用系统时区文件，容器时区不依赖系统。
 | 原文链接：http://book.9p2k8h.asia/blog/518885.Doc

原标题：golang 系统设计创建更新时间自动维护方案
简介：golang go 锁竞争导致 CPU 飙升，识别锁竞争场景，减少锁粒度，优化并发逻辑降低 CPU 开销。
 | 原文链接：http://book.9p2k8h.asia/blog/711406.Doc

原标题：Issue：操作系统最大打开文件数限制导致报错
简介：重复提交幂等防护再次讲解，梳理前端重复点击、网络重试场景，落地接口幂等，杜绝重复业务。
 | 原文链接：http://book.9p2k8h.asia/blog/045503.Doc

原标题：golang 系统设计 lru 缓存算法实现思路
简介：数据库 utf8mb4 支持 emoji 存储，数据库字段设置 utf8mb4 字符集，完整支持 emoji 表情存储入库。
 | 原文链接：http://book.9p2k8h.asia/blog/301143.Doc

原标题：架构笔记：批量任务系统架构防重复、断点续跑
简介：TLS 版本兼容 HTTPS 握手失败，兼容老旧 TLS 协议版本，修复部分客户端 HTTPS 握手失败无法访问。
 | 原文链接：http://book.9p2k8h.asia/blog/719649.Doc

原标题：golang redis 地理位置 geo 使用
简介：golang testing.TB Helper 标记辅助函数，t.Helper 标记辅助函数，报错打印真实调用位置。
 | 原文链接：http://book.9p2k8h.asia/blog/340336.Doc

原标题：golang 系统设计缓存降级开关快速切库实现
简介：nodejs 全局异常捕获进程防护，捕获未捕获异常与 Promise 拒绝，尽量保护进程不因为异常直接退出。
 | 原文链接：http://book.9p2k8h.asia/blog/637688.Doc

原标题：golang docker 部署 mongodb 开发环境
简介：golang 图片处理 go 图片裁剪压缩，golang 图像处理库，图片缩放裁剪水印，服务端图片处理。
 | 原文链接：http://book.9p2k8h.asia/blog/604697.Doc

原标题：Performance：后端接口性能优化完整分析流程
简介：系统字符集统一乱码修复，统一数据库、程序、操作系统字符集，解决中文乱码显示异常问题。
 | 原文链接：http://book.9p2k8h.asia/blog/370399.Doc

原标题：golang github actions 发布 release 包
简介：golang 字符编码转换 go 处理，iconv‑go 做编码转换 gbk utf8 互转，处理老旧系统 gbk 编码数据。
 | 原文链接：http://book.9p2k8h.asia/blog/555440.Doc

原标题：golang redis 过期策略内存淘汰
简介：golang 错误静默忽略风险规避，禁止空忽略错误，必须处理或者明确注释为什么忽略错误。
 | 原文链接：http://book.9p2k8h.asia/blog/648102.Doc

原标题：golang minio 预签名 url 临时访问
简介：golang sync.Map 高并发 map 使用场景，sync.Map 适用场景，读写实操，对比普通 map 加锁性能差异。
 | 原文链接：http://book.9p2k8h.asia/blog/314426.Doc

原标题：Git 标签版本标记发布管理
简介：golang 命令行交互 cobra 开发 cli，cobra 库开发功能完善命令行工具，子命令参数标志解析。
 | 原文链接：http://book.9p2k8h.asia/blog/772510.Doc

原标题：性能笔记：HTTP连接复用性能优化实践
简介：golang go math 大数高精度计算，math/big 处理超大整数、高精度浮点数，金额大数运算。
 | 原文链接：http://book.9p2k8h.asia/blog/550474.Doc

原标题：golang 系统设计接口防刷 ip 限流实现
简介：golang 定时任务 cron 使用指南，Go 使用 Cron 库实现定时任务，配置 corn 表达式调度业务任务。
 | 原文链接：http://book.9p2k8h.asia/blog/382328.Doc

原标题：golang 配置文件多环境加载
简介：定时任务周期调度 demo 开发，实现简单定时调度程序，按时间周期执行业务逻辑，理解定时任务运行机制。
 | 原文链接：http://book.9p2k8h.asia/blog/000016.Doc

原标题：golang gitlab ci 配置自动构建镜像
简介：golang 分表跨表 join 查询处理方案，分表后跨分片关联查询解决方案，业务层聚合代替数据库 join。
 | 原文链接：http://book.9p2k8h.asia/blog/655557.Doc

原标题：Troubleshooting：数据库主从延迟带来查询数据不一致
简介：golang ioutil 已废弃替换方案，ioutil 废弃之后替换为 os io 包函数，更新旧项目代码。
 | 原文链接：http://book.9p2k8h.asia/blog/200244.Doc


二、踩坑排错｜Troubleshooting
原标题：golang 系统设计技术债务识别登记治理思路
简介：golang gorm 子查询嵌套查询写法，Gorm 实现子查询、嵌套查询，复杂条件查询简化代码编写。
 | 原文链接：http://book.9p2k8h.asia/blog/677055.Doc

原标题：数据库事务 ACID 原理讲解
简介：超大数据集分页性能优化方案，对比不同分页方案，针对海量数据集做分页性能优化，解决越翻越慢。
 | 原文链接：http://book.9p2k8h.asia/blog/103385.Doc

原标题：golang mysql 时间类型选型避坑
简介：网络读取超时设置连接挂起防护，设置网络读取超时时间，防止请求无限挂起不返回，占用连接资源。
 | 原文链接：http://book.9p2k8h.asia/blog/383131.Doc

原标题：踩坑：重试逻辑未做幂等，重复生成业务数据
简介：hosts 配置本地回环访问修复，修改 hosts 配置，修复 127.0.0.1 解析异常，本地服务访问失败问题。
 | 原文链接：http://book.9p2k8h.asia/blog/396913.Doc

原标题：优化实践：Redis性能调优，避免大key热key
简介：WSL 文件权限访问异常修复，处理 WSL 环境文件权限错乱，调整权限配置，实现文件正常读写访问。
 | 原文链接：http://book.9p2k8h.asia/blog/724788.Doc

原标题：golang 系统设计链路追踪架构简单讲解
简介：golang 信号捕获程序退出处理，Go 捕获操作系统信号，做资源回收，控制程序退出流程。
 | 原文链接：http://book.9p2k8h.asia/blog/420301.Doc

原标题：记一次分布式锁失效引发的数据错乱问题
简介：JWT 工具封装令牌刷新过期，封装 JWT 工具类，实现令牌生成、校验、过期刷新整套令牌管理逻辑。
 | 原文链接：http://book.9p2k8h.asia/blog/782151.Doc

原标题：golang 系统设计 ci 流水线安全管控思路
简介：golang go 项目依赖冲突解决完整思路，定位冲突包，replace、exclude、升级降级解决版本冲突。
 | 原文链接：http://book.9p2k8h.asia/blog/014070.Doc

原标题：golang 大文件 http 下载服务
简介：golang go json 序列化自定义字段，json 标签控制字段名称、忽略字段、omitempty 空值忽略。
 | 原文链接：http://book.9p2k8h.asia/blog/642828.Doc

原标题：排错：容器OOM被杀死，日志看不到任何输出
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://book.9p2k8h.asia/blog/304986.Doc

原标题：Practice：实现请求大小限制中间件防护大报文
简介：golang redis bitmap 位图业务实战，bitmap 做签到统计、用户状态标记，节省大量内存空间。
 | 原文链接：http://book.9p2k8h.asia/blog/973810.Doc

原标题：坑点：gitrebase操作失误，代码提交丢失
简介：golang http.Server 配置参数详解，ReadTimeout WriteTimeout IdleTimeout，全方位防护慢请求攻击。
 | 原文链接：http://book.9p2k8h.asia/blog/411697.Doc

原标题：golang 系统设计集成测试环境准备清理实操
简介：golang 限流熔断放在代理层实践，代理层统一限流熔断，对后端服务做流量保护。
 | 原文链接：http://book.9p2k8h.asia/blog/717121.Doc

原标题：golang 系统设计网络超时故障排查思路
简介：golang 跨平台系统差异处理方案，处理 windows linux mac 路径、信号、文件权限差异，代码跨平台兼容。
 | 原文链接：http://book.9p2k8h.asia/blog/266145.Doc

原标题：Mock 接口服务快速搭建实操
简介：代码模块化组件化拆分思路，讲解代码拆分原则，将大业务拆分为独立模块组件，提升代码复用与维护能力。
 | 原文链接：http://book.9p2k8h.asia/blog/153876.Doc

原标题：入门实践：简易导出导入文件功能实现
简介：跨平台换行符统一异常修复，统一代码文件换行符，解决不同操作系统换行符不一致带来脚本执行异常。
 | 原文链接：http://book.9p2k8h.asia/blog/990442.Doc

原标题：golang 系统设计 git 工作流本地开发提交流程
简介：WebSocket 双向通信 demo 开发，搭建简易 WebSocket 服务，实现客户端服务端双向消息推送，理解实时通信原理。
 | 原文链接：http://book.9p2k8h.asia/blog/718796.Doc

原标题：实践：数据库回滚点业务调试实践
简介：golang 静态编译缩小镜像体积，Go 程序静态编译，不依赖系统库，产出单二进制文件，缩小镜像。
 | 原文链接：http://book.9p2k8h.asia/blog/563743.Doc

原标题：后端大文件分片上传接口开发
简介：golang context 包标准用法规范，context 传递请求元数据、超时、取消，函数第一个参数传入 ctx。
 | 原文链接：http://book.9p2k8h.asia/blog/348106.Doc

原标题：项目实践：搭建个人API网关最小实现版本
简介：多实例部署 Session 共享方案，多服务实例部署场景，实现 Session 共享，保证用户登录状态跨实例生效。
 | 原文链接：http://book.9p2k8h.asia/blog/297298.Doc

原标题：golang mysql 存储过程简单使用
简介：golang tcp 连接泄露排查定位，netstat 查看连接状态，找出未正常关闭连接，定位连接泄漏代码。
 | 原文链接：http://book.9p2k8h.asia/blog/474751.Doc

原标题：Practice：实现数据库连接池简易模拟实现
简介：golang go 爬虫请求速率控制，爬虫限频、代理轮换，设置 UA，防止爬虫被目标站点封禁 IP。
 | 原文链接：http://book.9p2k8h.asia/blog/637312.Doc

原标题：零基础理解JSON、XML数据格式处理
简介：golang os 文件目录操作大全，文件创建删除重命名，目录遍历，文件信息读取，完成各类文件系统操作。
 | 原文链接：http://book.9p2k8h.asia/blog/121048.Doc

原标题：golang 系统设计容器健康检查设计思路
简介：全局本地依赖隔离冲突规避，区分全局依赖与项目本地依赖，隔离环境，防止全局包干扰项目运行。
 | 原文链接：http://book.9p2k8h.asia/blog/078006.Doc

原标题：Cookie 跨环境登录配置调整
简介：golang go 程序抢占调度理解，理解 go 抢占式调度原理，长循环阻塞调度，造成协程调度延迟。
 | 原文链接：http://book.9p2k8h.asia/blog/100628.Doc

原标题：避坑：版本升级之后项目直接无法启动
简介：任务执行锁防止并发重复调度，增加任务执行锁，多实例环境，防止同一个定时任务并发多次运行。
 | 原文链接：http://book.9p2k8h.asia/blog/488005.Doc

原标题：限流窗口绕过漏洞修复方案
简介：golang go 应用内存使用优化手段，减少对象分配，复用对象，降低 GC 压力，减少 GC 停顿时间。
 | 原文链接：http://book.9p2k8h.asia/blog/520704.Doc

原标题：业务错误码体系设计方案
简介：golang 设置 net.Conn 读写超时，每次读写设置超时，防止连接永久阻塞挂起不返回。
 | 原文链接：http://book.9p2k8h.asia/blog/819483.Doc

原标题：入门实践：实现简单文件读写功能
简介：本地运行正常线上报错排查，对比本地与线上环境差异，从配置、系统版本、文件权限定位线上独有的 bug。
 | 原文链接：http://book.9p2k8h.asia/blog/660984.Doc

原标题：架构笔记：海量消息堆积架构处理能力设计
简介：手写简易 ORM 理解对象映射，手写极简 ORM 示例，理解对象与数据库表字段映射底层原理。
 | 原文链接：http://book.9p2k8h.asia/blog/415440.Doc

原标题：Troubleshooting：Redis大key引发集群卡顿
简介：golang 优雅处理 http 重定向逻辑，自定义控制 http 重定向跳转次数，防止无限重定向死循环。
 | 原文链接：http://book.9p2k8h.asia/blog/057584.Doc

原标题：golang 速率限制令牌桶实现
简介：golang gin 获取客户端真实 IP，多层代理场景正确拿到用户真实访问 IP，避免拿到网关代理内网地址。
 | 原文链接：http://book.9p2k8h.asia/blog/787192.Doc

原标题：golang 系统设计配置热更新不重启服务实现
简介：K8s 镜像拉取网络故障修复，排查 K8s 集群镜像拉取网络问题，配置镜像源，恢复镜像正常拉取。
 | 原文链接：http://book.9p2k8h.asia/blog/748026.Doc

原标题：golang 系统设计压测工具 wrk 使用实操
简介：JSON XML 数据解析处理示例，演示两种格式数据解析与序列化，增加异常捕获，处理格式错乱导致解析失败。
 | 原文链接：http://book.9p2k8h.asia/blog/930583.Doc

原标题：golang 分库分表简单路由实现
简介：golang prometheus client 业务埋点实操，prometheus client‑go 业务埋点，计数器、仪表盘、直方图指标开发。
 | 原文链接：http://book.9p2k8h.asia/blog/441357.Doc

原标题：golang grafana 监控面板简单配置
简介：全局异常处理器接口返回统一，接入全局异常捕获，拦截业务全部异常，对外输出统一格式返回值。
 | 原文链接：http://book.9p2k8h.asia/blog/012797.Doc

原标题：定时任务重复执行分布式锁
简介：golang 定时任务任务持久化存储，定时任务持久化到数据库，服务重启任务不丢失，动态管理任务。
 | 原文链接：http://book.9p2k8h.asia/blog/741795.Doc

原标题：golang 系统设计 api 接口兼容性设计原则
简介：nodejs 信号处理优雅关闭服务，监听系统信号，执行资源清理，实现 Node 服务优雅停机，拒绝粗暴杀死进程。
 | 原文链接：http://book.9p2k8h.asia/blog/118559.Doc

原标题：Troubleshooting：依赖安装失败完整排查清单
简介：golang 半关闭 tcp 连接 shutdown，tcp 连接 shutdown 半关闭，单向关闭读或者写，理解 tcp 关闭流程。
 | 原文链接：http://book.9p2k8h.asia/blog/281768.Doc

原标题：golang redis 发布订阅简单示例
简介：golang mime 类型检测文件，mime 识别文件 mime 类型，设置 http 响应 Content‑Type。
 | 原文链接：http://book.9p2k8h.asia/blog/494836.Doc

三、实战开发｜Practice
原标题：Git commit 钩子提交规范校验
简介：golang os 文件目录操作大全，文件创建删除重命名，目录遍历，文件信息读取，完成各类文件系统操作。
 | 原文链接：http://book.9p2k8h.asia/blog/925620.Doc

原标题：部署复盘：容器资源限制CPU内存配置实践
简介：golang os 文件目录操作大全，文件创建删除重命名，目录遍历，文件信息读取，完成各类文件系统操作。
 | 原文链接：http://book.9p2k8h.asia/blog/182238.Doc

原标题：golang 系统设计分布式事务几种方案优缺点
简介：缓存基础原理与简单代码实现，讲解缓存设计思路，编写简易缓存逻辑，减少重复计算与重复请求，提升程序响应速度。
 | 原文链接：http://book.9p2k8h.asia/blog/153963.Doc

原标题：内存广播本地进程消息通知
简介：golang trace 工具采集 go 程序执行轨迹，go trace 采集程序完整调度轨迹，分析协程调度阻塞问题。
 | 原文链接：http://book.9p2k8h.asia/blog/445151.Doc

原标题：golang zap 日志按日期切割方案
简介：golang go 调用动态链接库 so 文件，go 加载 so 动态库调用函数，复用编译好的 C 动态库。
 | 原文链接：http://book.9p2k8h.asia/blog/263155.Doc

原标题：实践：API接口文档自动导出离线文档实践
简介：golang benchmark 减少测试干扰，benchmark 执行循环 b.N，避免循环内部做非被测逻辑干扰结果。
 | 原文链接：http://book.9p2k8h.asia/blog/911364.Doc

原标题：golang mysql 慢查询日志开启分析
简介：项目脚手架模板生成工具，搭建项目模板脚手架，一键生成标准化项目骨架，减少重复初始化工作。
 | 原文链接：http://book.9p2k8h.asia/blog/744290.Doc

原标题：nodejs http 服务性能调优实战
简介：Git 误提交撤销回退实操教程，演示多种撤销提交方式，区分已经推送远程和本地未提交场景，处理误提交代码。
 | 原文链接：http://book.9p2k8h.asia/blog/833985.Doc

原标题：Practice：实现请求body重复读取中间件实践
简介：golang mongodb 索引优化慢查询处理，mongodb 创建索引，分析慢查询，优化聚合查询执行性能。
 | 原文链接：http://book.9p2k8h.asia/blog/603147.Doc

原标题：vue3 组合式 API 业务开发实战
简介：golang go‑pg postgres 客户端实操，go‑pg 操作 PostgreSQL 数据库，CRUD 关联查询业务开发。
 | 原文链接：http://book.9p2k8h.asia/blog/225053.Doc

原标题：记一次第三方回调IP变动未更新防火墙拦截
简介：异步任务堆积消费能力优化，处理消息任务堆积问题，提升消费处理速度，恢复队列正常处理水位。
 | 原文链接：http://book.9p2k8h.asia/blog/041473.Doc

原标题：实践：分布式事务本地模拟验证实践
简介：golang go 爬虫 robots 协议遵守，解析 robots.txt 规则，控制爬虫抓取范围，合规采集网页数据。
 | 原文链接：http://book.9p2k8h.asia/blog/148385.Doc

原标题：项目目录结构规范化最佳实践
简介：WSL 搭建 Windows Linux 开发环境，配置 WSL 环境，在 Windows 系统使用 Linux 工具链，适配 Linux 开发项目。
 | 原文链接：http://book.9p2k8h.asia/blog/785540.Doc

原标题：golang k8s secret 加密敏感信息
简介：数据库分表存储大表优化方案，对超大数据表做分表，拆分数据，降低单表数据量提升查询性能。
 | 原文链接：http://book.9p2k8h.asia/blog/045222.Doc

原标题：防火墙 IP 白名单回调接口放行
简介：golang go http 服务器优雅关闭完整代码，http.Server Shutdown，等待现有请求处理完成关闭服务。
 | 原文链接：http://book.9p2k8h.asia/blog/490541.Doc

原标题：Hands‑on：简易布隆过滤器实现与测试验证
简介：golang smtp 邮件发送完整示例，调用 smtp 服务发送文本与 html 格式邮件，实现邮件通知能力。
 | 原文链接：http://book.9p2k8h.asia/blog/996110.Doc

原标题：golang 系统设计开源项目维护简单经验分享
简介：pnpm 包管理工具实战避坑指南，使用 pnpm 管理项目依赖，梳理常见坑点，充分利用 pnpm 优势。
 | 原文链接：http://book.9p2k8h.asia/blog/644874.Doc

原标题：实战项目：WebSocket消息广播房间分组实践
简介：golang feishu 飞书机器人消息发送，调用飞书 webhook 机器人，发送文本卡片消息，实现业务告警通知。
 | 原文链接：http://book.9p2k8h.asia/blog/244722.Doc

原标题：Nginx 透传真实客户端 IP 配置
简介：golang interface {} 类型断言类型转换，类型断言 ok 模式，避免断言失败触发 panic。
 | 原文链接：http://book.9p2k8h.asia/blog/267645.Doc

原标题：部署复盘：静态站点部署CDN完整流程
简介：Fork 开源项目同步上游代码，Fork 开源仓库之后，配置上游源，同步官方最新代码，保持代码版本对齐。
 | 原文链接：http://book.9p2k8h.asia/blog/318629.Doc

原标题：golang 系统设计告警分级 p0‑p3 定义处理流程
简介：前端虚拟列表大数据渲染优化，实现虚拟滚动列表，只渲染可视区域 DOM，上万条数据页面流畅渲染。
 | 原文链接：http://book.9p2k8h.asia/blog/227227.Doc

原标题：golang prometheus 告警规则编写
简介：网络读取超时设置连接挂起防护，设置网络读取超时时间，防止请求无限挂起不返回，占用连接资源。
 | 原文链接：http://book.9p2k8h.asia/blog/558414.Doc

原标题：快速上手单元测试，写出第一个测试用例
简介：golang 分表跨表 join 查询处理方案，分表后跨分片关联查询解决方案，业务层聚合代替数据库 join。
 | 原文链接：http://book.9p2k8h.asia/blog/369570.Doc

原标题：线上接口超时故障排查思路
简介：golang io.MultiReader MultiWriter 拼接流，多个 reader 拼接，多 writer 同时写入一份数据。
 | 原文链接：http://book.9p2k8h.asia/blog/292333.Doc

原标题：git stash 代码暂存切换分支
简介：HTTP 状态码请求头完整梳理，汇总常用 HTTP 状态码与请求头含义，帮助快速看懂网络请求，排查接口通信问题。
 | 原文链接：http://book.9p2k8h.asia/blog/902664.Doc

原标题：效率笔记：GitWorkflow团队协作规范模板
简介：golang grpc 负载均衡客户端实现，grpc 客户端负载均衡，轮询随机权重，分发请求到多个服务实例。
 | 原文链接：http://book.9p2k8h.asia/blog/676951.Doc

原标题：实战项目：CLI批量文件处理工具开发全过程
简介：golang excel 简单读写操作示例，Go 实现 Excel 简单读写，业务数据导出 Excel 报表。
 | 原文链接：http://book.9p2k8h.asia/blog/713502.Doc

原标题：golang consul 健康检查服务注册
简介：golang context.WithCancel 手动取消上下文，WithCancel 生成可取消 ctx，手动调用 cancel 触发取消。
 | 原文链接：http://book.9p2k8h.asia/blog/340368.Doc

原标题：golang 系统设计容器镜像安全加固要点
简介：golang hertz 反向代理与负载均衡，hertz 实现反向代理，内置负载均衡，快速搭建网关类服务。
 | 原文链接：http://book.9p2k8h.asia/blog/902737.Doc

原标题：从零搭建简单的健康检查接口示例
简介：golang 分布式 ID 雪花算法实现，Go 实现雪花算法，生成分布式全局唯一 ID，适配分库分表主键。
 | 原文链接：http://book.9p2k8h.asia/blog/682766.Doc

原标题：极简 API 网关路由转发实现
简介：golang gzip 压缩 http 响应，服务端开启 gzip 压缩，减小接口响应体积，降低网络传输耗时。
 | 原文链接：http://book.9p2k8h.asia/blog/728842.Doc

原标题：Hands‑on：手写简单RPC框架基础通信版本
简介：golang fuzz corpus 语料库使用，fuzz 语料存储历史输入，回归测试，持续复现曾经触发 bug 输入。
 | 原文链接：http://book.9p2k8h.asia/blog/193116.Doc

原标题：Practice：手写简易限流组件，计数器、令牌桶实现
简介：axios 二次封装请求拦截处理，对 axios 做二次封装，统一请求拦截响应拦截，处理错误、token 自动刷新。
 | 原文链接：http://book.9p2k8h.asia/blog/002181.Doc

原标题：golang minio 分片上传断点续传
简介：Mock 接口服务快速搭建实操，搭建模拟后端接口，自定义返回数据、延迟响应，前端开发阶段无需依赖真实后端服务。
 | 原文链接：http://book.9p2k8h.asia/blog/700293.Doc

原标题：golang 系统设计定时任务分片执行分布式思路
简介：golang k8s 客户端 client‑go 简单示例，client‑go 操作 k8s 资源，增删改查 pod deployment 等资源对象。
 | 原文链接：http://book.9p2k8h.asia/blog/707321.Doc

原标题：golang 系统设计链路追踪架构简单讲解
简介：golang 数据库连接泄露排查，定位 Go 数据库连接泄露，连接没有归还池，导致连接耗尽报错。
 | 原文链接：http://book.9p2k8h.asia/blog/076233.Doc

原标题：Practice：模拟热点key，验证缓存防护策略
简介：golang 日志 zap 结构化日志实践，接入 Zap 结构化日志库，打印结构化日志，方便日志检索解析。
 | 原文链接：http://book.9p2k8h.asia/blog/259222.Doc

原标题：golang 系统设计 git 钩子自动化校验实现
简介：项目依赖安全扫描漏洞防范，扫描项目第三方依赖包，修复存在安全漏洞依赖，防范供应链攻击。
 | 原文链接：http://book.9p2k8h.asia/blog/133585.Doc

原标题：新手教程：Git撤销错误提交的几种常用方式
简介：golang 大内存分配 GC 抖动规避，避免瞬时大量对象创建，分批处理，防止 GC 抖动业务抖动。
 | 原文链接：http://book.9p2k8h.asia/blog/967767.Doc

原标题：Hands‑on：简易的事件订阅发布组件开发实践
简介：前端打包分包加载提速方案，前端打包做代码分包，拆分大 bundle，页面按需加载，提升首屏加载速度。
 | 原文链接：http://book.9p2k8h.asia/blog/199201.Doc

四、架构设计｜Architecture
原标题：golang 系统设计 jwt 安全使用避坑要点
简介：golang go mod graph 可视化依赖图，可视化 go 依赖关系，直观看到包之间依赖，定位冲突。
 | 原文链接：http://book.9p2k8h.asia/blog/895502.Doc

原标题：效率笔记：批量处理文本命令行工具实战案例
简介：golang benchmark 参数‑bench‑mem 统计内存分配，benchmark 开启内存统计，观察内存分配次数大小。
 | 原文链接：http://book.9p2k8h.asia/blog/610410.Doc

原标题：架构笔记：多数据源架构设计事务处理难点
简介：golang sync.Pool 对象池复用对象，sync.Pool 复用临时对象，减少内存分配，降低 GC 频率提升性能。
 | 原文链接：http://book.9p2k8h.asia/blog/139425.Doc

原标题：方案对比：几种分布式限流算法架构适用性
简介：数据库索引重建提升查询速度，针对碎片化索引，重建数据库索引，恢复 SQL 查询执行性能。
 | 原文链接：http://book.9p2k8h.asia/blog/455530.Doc

原标题：golang 系统设计日志架构采集存储检索完整链路
简介：golang 集成测试测试数据库回滚，集成测试结束自动回滚数据库，不污染测试环境数据。
 | 原文链接：http://book.9p2k8h.asia/blog/364756.Doc

原标题：golang 系统设计 grpc http2 多路复用讲解
简介：golang go 测试文件命名规范，_test.go 测试文件，TestXxx 单元测试函数命名规范。
 | 原文链接：http://book.9p2k8h.asia/blog/851781.Doc

原标题：开发记录：批量接口请求并发控制实践
简介：API 接口调试与异常处理实战，覆盖接口请求、参数组装、错误捕获，提供调试思路，高效定位接口返回异常问题。
 | 原文链接：http://book.9p2k8h.asia/blog/841169.Doc

原标题：性能笔记：RPC超时参数优化防止级联阻塞
简介：golang grpc 负载均衡客户端实现，grpc 客户端负载均衡，轮询随机权重，分发请求到多个服务实例。
 | 原文链接：http://book.9p2k8h.asia/blog/888853.Doc

原标题：golang redis 分布式计数器开发
简介：golang http.Server 配置参数详解，ReadTimeout WriteTimeout IdleTimeout，全方位防护慢请求攻击。
 | 原文链接：http://book.9p2k8h.asia/blog/092749.Doc

原标题：golang 系统设计代码评审高效沟通原则思路
简介：后端登录鉴权模块完整开发，实现完整登录模块，包含账号校验、令牌发放、接口鉴权整套能力。
 | 原文链接：http://book.9p2k8h.asia/blog/858049.Doc

原标题：代码模块化组件化拆分思路
简介：golang trace 链路追踪 opentelemetry，opentelemetry 实现链路追踪，生成 traceId spanId，完整记录调用链路。
 | 原文链接：http://book.9p2k8h.asia/blog/612243.Doc

原标题：跨平台换行符统一异常修复
简介：golang jwt jwk 公钥验证令牌，使用 jwk 公钥校验 jwt，非对称方式签发校验令牌，提升安全性。
 | 原文链接：http://book.9p2k8h.asia/blog/932068.Doc

原标题：架构复盘：RPC框架架构超时重试设计要点
简介：golang go 自定义错误类型实现，自定义 error 结构体，携带错误码、堆栈信息，统一业务错误。
 | 原文链接：http://book.9p2k8h.asia/blog/090812.Doc

原标题：浮点计算精度错误处理方案
简介：golang 速率限制令牌桶实现，Go 实现令牌桶限流算法，可复用限流器，控制业务调用速率。
 | 原文链接：http://book.9p2k8h.asia/blog/558959.Doc

原标题：Hands‑on：实现WebSocket聊天室完整前后端demo
简介：golang 正则表达式 Go 实操案例，正则匹配提取替换，处理手机号邮箱校验，规避正则回溯 CPU 暴涨。
 | 原文链接：http://book.9p2k8h.asia/blog/330356.Doc

原标题：golang etcd 租约 lease 过期机制
简介：golang cpu pprof 性能分析实操，使用 pprof 采集 CPU 性能数据，定位 CPU 高占用函数，做性能优化。
 | 原文链接：http://book.9p2k8h.asia/blog/608434.Doc

原标题：golang 系统设计开源 pr 评审合并流程实操
简介：golang go‑zero 监控指标埋点，go‑zero 内置 metrics 监控，上报业务指标对接监控平台。
 | 原文链接：http://book.9p2k8h.asia/blog/793093.Doc

原标题：Hands‑on：本地模拟分布式锁失效场景测试
简介：golang loki 日志收集 go 服务集成，日志输出适配 loki，标签携带 traceId，日志集中检索排查问题。
 | 原文链接：http://book.9p2k8h.asia/blog/042886.Doc

?
