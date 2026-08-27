最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计 websocket 协议原理梳理
简介：服务熔断防止故障级联传播，实现服务熔断逻辑，下游故障时快速失败，阻止故障向上游链式扩散。
 | 原文链接：http://book.rfpysii.asia/blog/6505555.sHtMl

原标题：golang 系统设计分库分表本地测试调试技巧
简介：golang go select 多路等待 channel，select 等待多个 channel，default 非阻塞，超时等待 channel。
 | 原文链接：http://book.rfpysii.asia/blog/0720960.sHtMl

原标题：golang 系统设计线上问题复现思路简单讲解
简介：golang 日志按日期切割实现方案，实现日志文件按天切割，自动归档旧日志，防止单个日志文件过大。
 | 原文链接：http://book.rfpysii.asia/blog/6909167.sHtMl

原标题：Performance：数据库join优化，大表join规避
简介：数据库死锁成因规避方案，讲解数据库死锁产生条件，给出业务层面规避手段，减少死锁事件发生。
 | 原文链接：http://book.rfpysii.asia/blog/3367541.sHtMl

原标题：部署实践：多实例服务部署无状态改造
简介：全局时间标准统一逻辑错乱修复，全服务统一使用同一时间标准，不要混用本地时间 UTC，修复时间逻辑 bug。
 | 原文链接：http://book.rfpysii.asia/blog/7249546.sHtMl

原标题：Hands‑on：手写简单消息队列理解存储模型
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://book.rfpysii.asia/blog/2722736.sHtMl

原标题：移动端适配 rem vw 方案对比
简介：golang sync.Mutex 互斥锁正确模式，互斥锁 defer Unlock，锁粒度控制，避免锁范围过大。
 | 原文链接：http://book.rfpysii.asia/blog/0463436.sHtMl

原标题：Debug：网关超时时间小于后端接口超时设置
简介：golang 读写分离 gorm 实现主从切换，gorm 配置主库写入从库查询，读写分离分担数据库查询压力。
 | 原文链接：http://book.rfpysii.asia/blog/5354608.sHtMl

原标题：效率笔记：调试网络请求curl命令高级用法
简介：golang os 主机名内核版本读取，os 读取主机名，内核信息，操作系统版本，获取运行环境信息。
 | 原文链接：http://book.rfpysii.asia/blog/4127899.sHtMl

原标题：分布式 ID 全局唯一生成方案
简介：大事务拆分防止连接池耗尽，将执行时间很长的大事务拆分为小事务，减少事务占用连接时长。
 | 原文链接：http://book.rfpysii.asia/blog/3359718.sHtMl

原标题：rebase 操作防止代码丢失
简介：golang 优雅处理 http 超时设置，Go HTTP 请求设置各类超时，防止请求无限阻塞，保护协程与连接。
 | 原文链接：http://book.rfpysii.asia/blog/0365114.sHtMl

原标题：golang 系统设计分布式配置中心思路
简介：golang 内存缓存简单实现方案，Go 实现进程内简易内存缓存，本地缓存热点数据，减少远程调用。
 | 原文链接：http://book.rfpysii.asia/blog/8545071.sHtMl

原标题：排错：打包后资源路径，开发生产行为不一致
简介：css 动画性能优化 GPU 加速，优化 CSS 动画，使用 GPU 加速属性，避免动画过程页面卡顿掉帧。
 | 原文链接：http://book.rfpysii.asia/blog/9592145.sHtMl

原标题：新手向：看懂项目README的正确阅读姿势
简介：golang excel 生成导出高性能方案，excelize 流式生成 excel，百万行数据导出，规避内存溢出。
 | 原文链接：http://book.rfpysii.asia/blog/9927265.sHtMl

原标题：接口签名验签完整安全方案
简介：极简方式搭建个人技术文档站点，使用轻量化工具快速部署文档站点，支持 markdown 编写，实现知识沉淀与对外分享。
 | 原文链接：http://book.rfpysii.asia/blog/7777294.sHtMl

原标题：排错：容器OOM被杀死，日志看不到任何输出
简介：K8s 镜像拉取网络故障修复，排查 K8s 集群镜像拉取网络问题，配置镜像源，恢复镜像正常拉取。
 | 原文链接：http://book.rfpysii.asia/blog/7964842.sHtMl

原标题：golang redis 布隆过滤器安装使用
简介：接口幂等性防重复请求实现，实现接口幂等逻辑，避免重复提交请求产生多条脏数据，保障业务数据安全。
 | 原文链接：http://book.rfpysii.asia/blog/0308663.sHtMl

原标题：踩坑：消息队列消息堆积，消费者处理能力不足
简介：WebSocket 双向通信 demo 开发，搭建简易 WebSocket 服务，实现客户端服务端双向消息推送，理解实时通信原理。
 | 原文链接：http://book.rfpysii.asia/blog/7442562.sHtMl

原标题：性能笔记：线程池参数调优任务队列策略
简介：新手参与开源社区贡献指南，介绍开源社区基础规则，讲解阅读 issue、提交 PR 流程，指导开发者参与开源贡献。
 | 原文链接：http://book.rfpysii.asia/blog/8979622.sHtMl

原标题：golang redis lua 脚本开发调试
简介：开发代理服务网络限制解决，搭建本地代理服务，解决开发环境网络访问受限，实现外部接口正常调用。
 | 原文链接：http://book.rfpysii.asia/blog/5847986.sHtMl

原标题：方案对比：缓存更新策略Cache‑Aside读写模式
简介：golang rabbitmq go 客户端生产消费，streadway/amqp 实现 rabbitmq 生产者消费者，队列交换机绑定。
 | 原文链接：http://book.rfpysii.asia/blog/7460698.sHtMl

原标题：DevOps：多环境镜像标签版本管理规范
简介：全局异常处理器接口返回统一，接入全局异常捕获，拦截业务全部异常，对外输出统一格式返回值。
 | 原文链接：http://book.rfpysii.asia/blog/2009968.sHtMl

原标题：Practice：模拟第三方接口超时服务降级验证
简介：nodejs 内存溢出问题排查修复，Node.js 程序 OOM 排查流程，定位内存泄露，调整内存限制修复崩溃。
 | 原文链接：http://book.rfpysii.asia/blog/5904164.sHtMl

原标题：部署实践：HTTPS证书自动续期配置实践
简介：golang excel 简单读写操作示例，Go 实现 Excel 简单读写，业务数据导出 Excel 报表。
 | 原文链接：http://book.rfpysii.asia/blog/9831855.sHtMl

原标题：避坑：ORM框架隐式查询产生大量慢SQL
简介：golang http3 quic 客户端服务端示例，go 实现 http3 quic 服务端客户端，体验 quic 协议低延迟特性。
 | 原文链接：http://book.rfpysii.asia/blog/6898931.sHtMl

原标题：golang http 代理客户端配置
简介：移动端适配 rem vw 方案对比，对比 rem 与 vw 移动端适配方案，分析优缺点，给出选型建议。
 | 原文链接：http://book.rfpysii.asia/blog/0368681.sHtMl

原标题：golang 系统设计 http3 quic 简单原理了解
简介：golang go ring 环形容器循环队列，ring 环形链表实现循环队列，环形缓冲区业务场景。
 | 原文链接：http://book.rfpysii.asia/blog/7639415.sHtMl

原标题：golang 系统设计数据库迁移工具 go‑migrate 实操
简介：golang 重试退避机制代码实现，Go 实现请求重试与指数退避，处理临时故障，提升调用稳定性。
 | 原文链接：http://book.rfpysii.asia/blog/2526431.sHtMl

原标题：OpenSource：开源项目README高质量编写指南
简介：golang context 上下文传参讲解，讲解 Context 使用场景，传递元数据、控制协程超时取消，规范协程控制。
 | 原文链接：http://book.rfpysii.asia/blog/2263789.sHtMl

原标题：golang mysql 存储过程简单使用
简介：限流窗口绕过漏洞修复方案，修复限流时间窗口漏洞，避免攻击者绕过限流规则，保障接口防护有效。
 | 原文链接：http://book.rfpysii.asia/blog/1518541.sHtMl

原标题：架构复盘：分表扩容架构平滑迁移思路
简介：golang context.WithTimeout 超时上下文，WithTimeout 设置超时时间，超时自动 cancel 释放协程。
 | 原文链接：http://book.rfpysii.asia/blog/1403219.sHtMl

原标题：开源实践：开源Issue沟通技巧如何有效提Bug
简介：后端登录鉴权模块完整开发，实现完整登录模块，包含账号校验、令牌发放、接口鉴权整套能力。
 | 原文链接：http://book.rfpysii.asia/blog/5159154.sHtMl

原标题：架构复盘：数据库主从架构设计与延迟应对方案
简介：文件读写与异常捕获代码示例，演示文件读取写入操作，增加异常捕获逻辑，规避文件不存在、权限不足导致崩溃。
 | 原文链接：http://book.rfpysii.asia/blog/3635183.sHtMl

原标题：设计思考：大促系统架构压测改造整体思路
简介：golang go‑pg postgres 客户端实操，go‑pg 操作 PostgreSQL 数据库，CRUD 关联查询业务开发。
 | 原文链接：http://book.rfpysii.asia/blog/2427619.sHtMl

原标题：golang 系统设计消息消费 offset 管理策略
简介：eslint prettier 代码规范落地，配置 eslint 与 prettier，做代码检查格式化，统一前端团队代码风格。
 | 原文链接：http://book.rfpysii.asia/blog/2608256.sHtMl

原标题：实战项目：实现分布式任务调度最小原型
简介：前端防抖节流高频事件处理，封装防抖节流工具，处理滚动、输入框输入等高频触发事件减少执行次数。
 | 原文链接：http://book.rfpysii.asia/blog/3826446.sHtMl

原标题：调优方案：MySQL缓冲池参数性能调优实践
简介：service‑worker 离线缓存实践，使用 ServiceWorker 实现静态资源离线缓存，弱网环境页面依然可访问。
 | 原文链接：http://book.rfpysii.asia/blog/4073739.sHtMl

原标题：Hands‑on：本地模拟分布式锁失效场景测试
简介：nestjs 权限守卫鉴权实现方案，使用 Nest 守卫实现接口鉴权，角色权限控制，拦截未授权接口访问。
 | 原文链接：http://book.rfpysii.asia/blog/8139599.sHtMl

原标题：nodejs 项目 pm2 部署运维指南
简介：数据库主从延迟业务兼容处理，业务适配主从复制延迟，避免读取从库拿到还未同步完成旧数据。
 | 原文链接：http://book.rfpysii.asia/blog/1283946.sHtMl

原标题：前端组件库按需加载性能优化
简介：全平台系统环境变量配置，汇总多操作系统环境变量配置方法，统一项目读取逻辑，适配不同运行平台。
 | 原文链接：http://book.rfpysii.asia/blog/9562678.sHtMl


二、踩坑排错｜Troubleshooting
原标题：golang redis 事务 multi exec 使用
简介：任务执行锁防止并发重复调度，增加任务执行锁，多实例环境，防止同一个定时任务并发多次运行。
 | 原文链接：http://book.rfpysii.asia/blog/1115331.sHtMl

原标题：golang 系统设计测试环境预发环境生产环境隔离
简介：golang contract 契约测试微服务，微服务契约测试，保证接口变更不破坏调用方，提前发现兼容性问题。
 | 原文链接：http://book.rfpysii.asia/blog/9592636.sHtMl

原标题：golang mysql 事务回滚异常处理
简介：文件描述符优化进程卡死修复，及时关闭文件句柄，控制打开文件数量，解决文件句柄耗尽进程卡死。
 | 原文链接：http://book.rfpysii.asia/blog/7762778.sHtMl

原标题：Troubleshooting：防火墙安全组拦截访问请求
简介：CI 构建缓存加速编译速度，开启 CI 流水线依赖缓存，复用上一次构建依赖包，缩短流水线构建耗时。
 | 原文链接：http://book.rfpysii.asia/blog/0047940.sHtMl

原标题：代码格式化工具团队统一风格
简介：golang io.Copy 流式拷贝数据，io.Copy 拷贝 reader 到 writer，不用加载全部数据到内存。
 | 原文链接：http://book.rfpysii.asia/blog/0052864.sHtMl

原标题：Hands‑on：简易压缩中间件gzip实现实践
简介：缓存穿透防护保护数据库，实现缓存穿透防护手段，拦截不存在的数据查询，避免请求直接打穿数据库。
 | 原文链接：http://book.rfpysii.asia/blog/8826436.sHtMl

原标题：一次数据库死锁现场分析与解决方案记录
简介：golang go 优雅处理信号丢失场景，处理信号丢失、信号被忽略，保障程序可以正常接收终止信号。
 | 原文链接：http://book.rfpysii.asia/blog/8189132.sHtMl

原标题：golang docker 部署 mongodb 开发环境
简介：开发测试生产多环境配置区分，讲解三套环境配置分离思路，配置文件隔离，防止开发配置泄露到生产环境。
 | 原文链接：http://book.rfpysii.asia/blog/5146472.sHtMl

原标题：安全笔记：Git仓库密钥硬编码泄露处理方案
简介：golang kitex 字节微服务框架入门，kitex 开发 rpc 微服务，代码生成，服务注册发现完整流程。
 | 原文链接：http://book.rfpysii.asia/blog/2515292.sHtMl

原标题：性能复盘：消息队列大量小消息性能问题优化
简介：golang os 环境变量读取设置，os.Getenv os.Setenv os.Unsetenv 读写环境变量，环境变量多值处理。
 | 原文链接：http://book.rfpysii.asia/blog/9207747.sHtMl

原标题：golang kafka 消息顺序性保证方案
简介：CI/CD 流水线自动构建部署落地，搭建完整 CI/CD 流水线，代码提交自动构建、测试、部署到目标环境。
 | 原文链接：http://book.rfpysii.asia/blog/2684216.sHtMl

原标题：开发复盘：超时参数统一治理线上服务实践
简介：日志驱动异常日志不输出修复，排查日志驱动配置，修复日志写入配置，恢复程序正常日志输出。
 | 原文链接：http://book.rfpysii.asia/blog/2589803.sHtMl

原标题：内存广播本地进程消息通知
简介：golang mqtt 客户端 go 开发物联网，paho.mqtt.golang 实现 mqtt 客户端，物联网设备消息收发。
 | 原文链接：http://book.rfpysii.asia/blog/9335238.sHtMl

原标题：设计思考：系统容量评估架构前期估算思路
简介：golang 字符串处理常用技巧汇总，字符串拼接、分割、替换、类型转换实操，规避字符串高频错误。
 | 原文链接：http://book.rfpysii.asia/blog/5584416.sHtMl

原标题：踩坑：分布式事务状态不一致数据两边不一致
简介：golang go 错误包装 fmt.Errorf % w，使用 % w 包装错误，支持 errors.Is errors.As 判断错误类型。
 | 原文链接：http://book.rfpysii.asia/blog/1584239.sHtMl

原标题：方案设计：分布式分页查询架构难点处理
简介：golang bytes.Buffer 字节缓冲区使用，bytes.Buffer 字节内存缓冲区，拼接字节，避免频繁内存分配。
 | 原文链接：http://book.rfpysii.asia/blog/7965357.sHtMl

原标题：跨平台换行符统一异常修复
简介：golang 网卡 ip 读取网络信息获取，程序读取本机网卡 IP，多网卡环境筛选业务使用 IP 地址。
 | 原文链接：http://book.rfpysii.asia/blog/7062050.sHtMl

原标题：开发复盘：大数据量分页避免offset性能问题
简介：时间同步修复令牌提前过期，服务器时间不同步导致 JWT 令牌提前过期，同步系统时间解决异常。
 | 原文链接：http://book.rfpysii.asia/blog/6208052.sHtMl

原标题：golang 系统设计链路查询定位慢请求实操技巧
简介：golang tcp 四次挥手 go 程序行为，理解 tcp 四次挥手，处理连接关闭、重置、RST 包异常场景。
 | 原文链接：http://book.rfpysii.asia/blog/4119174.sHtMl

原标题：golang mock 单元测试编写技巧
简介：内存泄漏定位分析完整流程，分享内存泄漏排查步骤，定位没有释放的对象，解决内存持续上涨问题。
 | 原文链接：http://book.rfpysii.asia/blog/0322407.sHtMl

原标题：golang 数据库慢查询监控实现
简介：前端打包产物体积压缩优化，多手段压缩前端打包产物，移除无用代码，压缩资源，提升页面加载速度。
 | 原文链接：http://book.rfpysii.asia/blog/8708891.sHtMl

原标题：排错：多实例部署session共享失效登录失效
简介：灰度发布策略服务平滑升级，实现灰度发布逻辑，流量逐步切到新版本，出现问题快速回滚旧版本。
 | 原文链接：http://book.rfpysii.asia/blog/6965833.sHtMl

原标题：golang redis 事务 multi exec 使用
简介：golang 命令行彩色输出终端，终端彩色文字输出，进度条交互，优化命令行工具用户体验。
 | 原文链接：http://book.rfpysii.asia/blog/6570396.sHtMl

原标题：服务健康检查告警监控体系
简介：golang grpc metadata 元数据透传，metadata 传递 traceId、鉴权信息，全链路透传上下文信息。
 | 原文链接：http://book.rfpysii.asia/blog/1968228.sHtMl

原标题：golang mysql innodb 事务隔离级别
简介：灰度发布策略服务平滑升级，实现灰度发布逻辑，流量逐步切到新版本，出现问题快速回滚旧版本。
 | 原文链接：http://book.rfpysii.asia/blog/5626372.sHtMl

原标题：golang 系统设计 gob msgpack 序列化对比
简介：golang html 模板防 xss 自动转义，理解 go html/template 自动转义，防止 XSS 攻击，处理不需要转义场景。
 | 原文链接：http://book.rfpysii.asia/blog/9369691.sHtMl

原标题：golang 系统设计配置中心核心能力梳理讲解
简介：golang regexp 正则捕获分组提取数据，正则捕获分组提取子匹配内容，拿到需要业务字段。
 | 原文链接：http://book.rfpysii.asia/blog/0785990.sHtMl

原标题：golang 系统设计埋点数据上报方案
简介：JSON XML 数据解析处理示例，演示两种格式数据解析与序列化，增加异常捕获，处理格式错乱导致解析失败。
 | 原文链接：http://book.rfpysii.asia/blog/5191524.sHtMl

原标题：避坑：ORM框架隐式查询产生大量慢SQL
简介：Redis 热点 key 拆分降低集群压力，拆分访问量极高的热点 Key，分散请求压力，避免 Redis 节点压力过高。
 | 原文链接：http://book.rfpysii.asia/blog/1788956.sHtMl

原标题：golang 系统设计服务优雅停机完整流程
简介：JWT 工具封装令牌刷新过期，封装 JWT 工具类，实现令牌生成、校验、过期刷新整套令牌管理逻辑。
 | 原文链接：http://book.rfpysii.asia/blog/2142887.sHtMl

原标题：架构笔记：数据库读写分离架构数据不一致应对
简介：golang 时间戳秒毫秒纳秒转换，Unix UnixMilli UnixNano 互相转换，区分单位避免时间逻辑 bug。
 | 原文链接：http://book.rfpysii.asia/blog/7715614.sHtMl

原标题：WSL 内存上限限制防止资源耗尽
简介：golang 集成测试测试数据库回滚，集成测试结束自动回滚数据库，不污染测试环境数据。
 | 原文链接：http://book.rfpysii.asia/blog/8010556.sHtMl

原标题：实践：大文件分片上传后端完整实现思路
简介：TCP 长连接参数优化 TIME_WAIT，调整 TCP 内核参数，优化长连接，减少大量 TIME_WAIT 连接占用资源。
 | 原文链接：http://book.rfpysii.asia/blog/3922165.sHtMl

原标题：Troubleshoot：异步异常未捕获，进程悄无声息退出
简介：golang go test 单元测试命令参数详解，gotest 参数覆盖率，指定测试用例，跳过测试，单元测试命令实操。
 | 原文链接：http://book.rfpysii.asia/blog/9822471.sHtMl

原标题：性能笔记：DNS缓存优化减少域名解析开销
简介：golang net.Listener 包装自定义监听器，包装 Listener 做连接计数、连接拦截，扩展网络能力。
 | 原文链接：http://book.rfpysii.asia/blog/5637605.sHtMl

原标题：Troubleshooting：防火墙安全组拦截访问请求
简介：golang grafana 面板 go 业务指标可视化，prometheus 指标对接 grafana，配置监控面板可视化业务状态。
 | 原文链接：http://book.rfpysii.asia/blog/1053195.sHtMl

原标题：全局时间标准统一逻辑错乱修复
简介：nodejs 脚手架工具开发完整教程，从零开发 Node 命令行脚手架，实现项目模板生成，理解 CLI 开发。
 | 原文链接：http://book.rfpysii.asia/blog/2822882.sHtMl

原标题：新手指南：项目本地编译输出产物解析
简介：vue pinia 状态管理实战教程，Pinia 完整实战示例，实现状态定义修改，模块拆分替代 Vuex。
 | 原文链接：http://book.rfpysii.asia/blog/9437319.sHtMl

原标题：排错：反向代理后获取真实IP全部变成内网IP
简介：golang rsa 签名验签 pem 证书加载，加载 pem 格式密钥证书，rsa 签名与验签完整业务实现。
 | 原文链接：http://book.rfpysii.asia/blog/8165231.sHtMl

原标题：golang 系统设计分布式锁红锁优缺点梳理
简介：超大数据集分页性能优化方案，对比不同分页方案，针对海量数据集做分页性能优化，解决越翻越慢。
 | 原文链接：http://book.rfpysii.asia/blog/2696605.sHtMl

三、实战开发｜Practice
原标题：golang k8s 滚动更新回滚策略
简介：golang 容器时区设置镜像构建处理，镜像内部设置正确时区，解决容器时间与宿主机不一致。
 | 原文链接：http://book.rfpysii.asia/blog/2277832.sHtMl

原标题：安全笔记：请求头伪造IP漏洞防护
简介：golang 自定义 pprof 扩展业务指标，扩展 pprof，输出业务自定义指标，结合性能数据分析业务状态。
 | 原文链接：http://book.rfpysii.asia/blog/3261653.sHtMl

原标题：golang docker compose 完整语法
简介：限流规则误拦截正常请求修复，修正限流规则阈值，避免合法用户被限流拦截，兼顾防护与可用性。
 | 原文链接：http://book.rfpysii.asia/blog/0110449.sHtMl

原标题：Hands‑on：编写GitLabCI配置自动测试部署
简介：golang viper 多源配置管理实操，viper 读取配置文件环境变量命令行参数，多源配置优先级管理。
 | 原文链接：http://book.rfpysii.asia/blog/7286612.sHtMl

原标题：新手指南：看懂开源项目的Issue与PR
简介：golang sqlx 原生 SQL 代码简化，sqlx 简化原生 SQL 结果映射结构体，兼顾性能与开发效率。
 | 原文链接：http://book.rfpysii.asia/blog/1993034.sHtMl

原标题：golang 集成测试启动测试数据库
简介：HTTPS 证书过期更新操作，检测 HTTPS 证书到期，更新证书文件，恢复 HTTPS 服务正常访问。
 | 原文链接：http://book.rfpysii.asia/blog/0473203.sHtMl

原标题：golang 优雅关闭 grpc 服务示例
简介：文件描述符优化进程卡死修复，及时关闭文件句柄，控制打开文件数量，解决文件句柄耗尽进程卡死。
 | 原文链接：http://book.rfpysii.asia/blog/1975275.sHtMl

原标题：环境变量不生效问题修复
简介：golang 单元测试 mock http 请求，mock HTTP 外部接口，单元测试不依赖外部网络，保证用例稳定运行。
 | 原文链接：http://book.rfpysii.asia/blog/3025526.sHtMl

原标题：内网 DNS 不稳定随机报错排查
简介：golang 接口限流中间件开发，Gin 开发限流中间件，接口层实现访问频率限制，防护接口流量。
 | 原文链接：http://book.rfpysii.asia/blog/4992006.sHtMl

原标题：golang 参数校验业务接口处理
简介：golang e2e 端到端测试 go 接口，编写 e2e 测试，完整模拟用户请求，校验整套业务链路正确性。
 | 原文链接：http://book.rfpysii.asia/blog/9833417.sHtMl

原标题：预编译 SQL 防注入实现
简介：golang go url url.Values 参数编码，url.Values 构建 url 查询参数，自动处理参数 url 编码。
 | 原文链接：http://book.rfpysii.asia/blog/3835880.sHtMl

原标题：动态定时任务业务调度实现
简介：golang go 服务蓝绿发布实践思路，蓝绿两套实例，流量一键切换，回滚快速降低发布风险。
 | 原文链接：http://book.rfpysii.asia/blog/0060293.sHtMl

原标题：golang 系统设计开源项目贡献指南 contributing
简介：golang embed 目录读取文件列表，embed 嵌入整个目录，读取目录下全部文件，做静态资源服务。
 | 原文链接：http://book.rfpysii.asia/blog/6322104.sHtMl

原标题：部署复盘：配置不要硬编码进镜像最佳实践
简介：golang 系统资源限制读取 cpu 内存，读取系统容器 cpu 内存限制，程序适配容器资源配额做业务调优。
 | 原文链接：http://book.rfpysii.asia/blog/8647711.sHtMl

原标题：OOMKilled 容器被杀完整排查
简介：数值 key 浮点匹配异常规避，避免浮点数作为 Redis 等存储的 key，防止精度问题引发 key 匹配失败。
 | 原文链接：http://book.rfpysii.asia/blog/4677966.sHtMl

原标题：设计思考：分布式会话架构选型对比
简介：CI/CD 流水线自动构建部署落地，搭建完整 CI/CD 流水线，代码提交自动构建、测试、部署到目标环境。
 | 原文链接：http://book.rfpysii.asia/blog/8638459.sHtMl

原标题：golang rate‑limiter 限流组件
简介：图片上传预览格式大小处理，实现图片上传接口，校验文件格式、大小，完成上传后预览处理。
 | 原文链接：http://book.rfpysii.asia/blog/6134567.sHtMl

原标题：Debug：HTTPS握手失败TLS版本兼容问题
简介：nodejs 信号处理优雅关闭服务，监听系统信号，执行资源清理，实现 Node 服务优雅停机，拒绝粗暴杀死进程。
 | 原文链接：http://book.rfpysii.asia/blog/3359659.sHtMl

原标题：项目实践：数据库慢日志采集分析落地实践
简介：golang 异步任务队列 worker 池开发，任务入数据库或 redis，worker 池消费执行，异步处理耗时业务。
 | 原文链接：http://book.rfpysii.asia/blog/4037586.sHtMl

原标题：golang 互斥锁读写锁并发安全
简介：golang grpc 服务端流推送数据，服务端流式响应，服务端持续向客户端推送多条响应消息。
 | 原文链接：http://book.rfpysii.asia/blog/3193229.sHtMl

原标题：golang gin 路由分组权限管控
简介：golang context.WithTimeout 超时上下文，WithTimeout 设置超时时间，超时自动 cancel 释放协程。
 | 原文链接：http://book.rfpysii.asia/blog/4555391.sHtMl

原标题：开发复盘：分布式会话共享多种方案实践
简介：golang go 模板缓存预编译模板，预编译 html 模板，程序启动加载，避免每次请求解析模板损耗性能。
 | 原文链接：http://book.rfpysii.asia/blog/4349861.sHtMl

原标题：入门实践：简单的请求封装与异常捕获
简介：golang 雪花 id 重复问题排查，排查雪花算法 ID 重复问题，时钟回拨、机器 ID 冲突，给出修复方案。
 | 原文链接：http://book.rfpysii.asia/blog/4523254.sHtMl

原标题：Cookie Session 会话状态管理
简介：golang go 优雅处理信号丢失场景，处理信号丢失、信号被忽略，保障程序可以正常接收终止信号。
 | 原文链接：http://book.rfpysii.asia/blog/4148313.sHtMl

原标题：golang ci 流水线单元测试集成测试
简介：前端骨架屏提升页面体验，实现页面骨架屏，数据未加载完成展示占位，优化页面白屏感知体验。
 | 原文链接：http://book.rfpysii.asia/blog/4773119.sHtMl

原标题：golang 系统设计监控大盘故障快速定位思路
简介：多线程线程安全脏数据规避，梳理多线程共享变量，做好同步控制，避免并发修改产生脏数据。
 | 原文链接：http://book.rfpysii.asia/blog/2211727.sHtMl

原标题：实战：数据库索引设计，复合索引最佳实践
简介：GitHub 项目提交推送完整流程讲解，从仓库初始化到提交推送远程仓库，梳理全流程细节，避开新手高频错误。
 | 原文链接：http://book.rfpysii.asia/blog/6149991.sHtMl

原标题：Redis 内存淘汰策略数据防丢失
简介：上传接口跨域配置特殊适配，针对文件上传接口，适配复杂请求，修复上传场景下跨域失效问题。
 | 原文链接：http://book.rfpysii.asia/blog/5394000.sHtMl

原标题：Troubleshooting：Nginx缓冲区过小大文件上传失败
简介：eslint prettier 代码规范落地，配置 eslint 与 prettier，做代码检查格式化，统一前端团队代码风格。
 | 原文链接：http://book.rfpysii.asia/blog/8706832.sHtMl

原标题：踩坑：Docker容器内时区不一致引发的时间BUG
简介：golang httptest 模拟外部 http 服务，httptest.NewServer 模拟第三方 http 服务，单元测试 mock 外部接口。
 | 原文链接：http://book.rfpysii.asia/blog/7260500.sHtMl

原标题：golang 系统设计索引设计通用方法论汇总
简介：golang snowflake 时钟回拨解决方案，雪花算法处理时钟回拨，防止生成重复 ID，保证 ID 全局唯一。
 | 原文链接：http://book.rfpysii.asia/blog/3651317.sHtMl

原标题：golang 系统设计覆盖索引减少回表查询实现
简介：golang csv 读写批量数据处理，Go 读写 CSV 文件，批量导入导出业务数据，处理 CSV 格式解析。
 | 原文链接：http://book.rfpysii.asia/blog/7021224.sHtMl

原标题：从零学习简单分页逻辑实现思路
简介：golang redis list 队列简易消息队列，利用 Redis List 实现简易队列，完成任务入队消费基础能力。
 | 原文链接：http://book.rfpysii.asia/blog/8081071.sHtMl

原标题：调优方案：消息队列消费速度优化处理堆积
简介：nodejs 数据库连接池配置调优，调优 Node 数据库连接池参数，平衡性能与资源占用，避免连接耗尽。
 | 原文链接：http://book.rfpysii.asia/blog/9016953.sHtMl

原标题：入门实践：简易进度条CLI工具实现demo
简介：golang tcp_NODELAY 关闭延迟发送，设置 tcp_NODELAY，关闭 Nagle 算法，降低小包请求延迟。
 | 原文链接：http://book.rfpysii.asia/blog/6789732.sHtMl

原标题：TCP 长连接参数优化 TIME_WAIT
简介：golang context.WithTimeout 超时上下文，WithTimeout 设置超时时间，超时自动 cancel 释放协程。
 | 原文链接：http://book.rfpysii.asia/blog/1252983.sHtMl

原标题：golang 错误处理最佳实践汇总
简介：golang 消息队列 kafka 消费开发，Go 开发 Kafka 消费程序，消费消息执行业务，理解 Kafka 消费逻辑。
 | 原文链接：http://book.rfpysii.asia/blog/7898153.sHtMl

原标题：golang grpc protobuf 开发实操
简介：接口限流逻辑简单模拟实现，编写简易限流逻辑，限制接口访问频次，保护服务，避免短时间大量请求压垮系统。
 | 原文链接：http://book.rfpysii.asia/blog/2504623.sHtMl

原标题：golang docker compose 本地开发最佳实践
简介：golang 数据库 ORM 框架选型对比，gorm xorm sqlx 对比各 ORM 优缺点，根据业务场景选型。
 | 原文链接：http://book.rfpysii.asia/blog/2631803.sHtMl

原标题：golang 系统设计缓存优化落地实操指南
简介：项目构建脚本编译打包解析，解读项目构建脚本，理清编译、压缩、资源复制流程，理解打包后产物如何生成。
 | 原文链接：http://book.rfpysii.asia/blog/4297600.sHtMl

四、架构设计｜Architecture
原标题：golang 系统设计无锁编程思路简单示例
简介：golang 漏桶算法实现接口限流，漏桶算法控制请求流出速率，平滑突发流量，削平流量峰值。
 | 原文链接：http://book.rfpysii.asia/blog/9827878.sHtMl

原标题：golang 系统设计异步化改造业务流程思路
简介：golang strings.Builder 字符串高效拼接，strings.Builder 做字符串拼接，比 += 性能更高，减少内存拷贝。
 | 原文链接：http://book.rfpysii.asia/blog/2057052.sHtMl

原标题：AI实践：大模型生成测试用例实践与校验
简介：golang json number 数字不转 float64，使用 json.Number 保留原始数字字符串，防止大数字精度丢失。
 | 原文链接：http://book.rfpysii.asia/blog/1695822.sHtMl

原标题：Hands‑on：简易请求转发代理中间件实现
简介：golang 速率限制令牌桶实现，Go 实现令牌桶限流算法，可复用限流器，控制业务调用速率。
 | 原文链接：http://book.rfpysii.asia/blog/8567943.sHtMl

原标题：golang 系统设计异步化改造业务流程思路
简介：OpenAPI 自动接口文档生成，集成 OpenAPI 工具，自动扫描代码生成接口文档，减少文档维护成本。
 | 原文链接：http://book.rfpysii.asia/blog/2463980.sHtMl

原标题：设计思考：系统容量评估架构前期估算思路
简介：rebase 操作防止代码丢失，讲解 rebase 风险点，操作前做好备份，规避错误操作造成代码提交丢失。
 | 原文链接：http://book.rfpysii.asia/blog/0903594.sHtMl

原标题：golang redis stream 消息队列实践
简介：MySQL 慢查询索引优化实战，抓取慢查询 SQL，分析执行计划，新增或者调整索引，提升 SQL 执行速度。
 | 原文链接：http://book.rfpysii.asia/blog/8592643.sHtMl

原标题：golang 系统设计本地缓存与分布式缓存
简介：golang 处理连接被重置 reset 错误，识别 connection reset by peer，对端关闭连接异常处理逻辑。
 | 原文链接：http://book.rfpysii.asia/blog/8204385.sHtMl

原标题：入门实践：本地简单代理服务搭建
简介：内存溢出问题现象识别排查，识别内存溢出现象，梳理排查方向，定位内存持续上涨引发服务崩溃问题。
 | 原文链接：http://book.rfpysii.asia/blog/6418629.sHtMl

原标题：DevOps：制品仓库管理二进制产物版本
简介：golang go 泛型约束与类型集合，泛型 type set 约束，限制泛型支持类型，写出安全泛型代码。
 | 原文链接：http://book.rfpysii.asia/blog/6224197.sHtMl

原标题：golang 系统设计延迟消息实现几种方案对比
简介：golang go race 竞态检测工具，‑race 检测数据竞争，编译运行检测并发读写数据竞争 bug。
 | 原文链接：http://book.rfpysii.asia/blog/9267238.sHtMl

原标题：golang 系统设计防爬虫简单策略
简介：Docker 网络模式容器互通设置，选择合适 Docker 网络模式，实现容器之间网络互相访问通信。
 | 原文链接：http://book.rfpysii.asia/blog/9890265.sHtMl

原标题：Practice：JWT工具封装，刷新令牌完整逻辑
简介：golang nacos go 客户端配置服务发现，nacos‑go 对接 nacos，配置管理、微服务注册发现。
 | 原文链接：http://book.rfpysii.asia/blog/4764286.sHtMl

原标题：Architecture：服务注册发现架构原理与选型
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://book.rfpysii.asia/blog/4088897.sHtMl

原标题：性能复盘：GC停顿过长业务卡顿优化记录
简介：golang 时间轮算法实现延时调度，手写简易时间轮，高并发大量延时任务，降低轮询 CPU 消耗。
 | 原文链接：http://book.rfpysii.asia/blog/9290430.sHtMl

原标题：golang 系统设计缓存更新策略 cache aside 讲解
简介：日志输出规范防止磁盘爆满，控制日志输出量，配置日志切割轮转，避免日志文件无限增长占满磁盘。
 | 原文链接：http://book.rfpysii.asia/blog/2457751.sHtMl

原标题：Debug：多线程共享可变变量产生脏数据
简介：golang redis lua 脚本原子操作，使用 Lua 脚本实现原子逻辑，减少网络往返，保障多命令原子执行。
 | 原文链接：http://book.rfpysii.asia/blog/9593159.sHtMl

原标题：golang 系统设计代码评审高效沟通原则思路
简介：数值类型溢出错乱问题修复，选择合适数值存储类型，处理数值溢出，避免数据存储错乱结果异常。
 | 原文链接：http://book.rfpysii.asia/blog/5318856.sHtMl

?
