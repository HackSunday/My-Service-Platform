# Invoker Platform

## prototype design

### Invoker Platform (IP) Server

- 心跳检测 感知服务生死
- 网络拓扑 
- 服务注册
- 写入服务依赖到IP client（服务状态改变时、每隔一段时间）
- 服务隔离
- 服务的禁用/开启

### Invoker Platform (IP) Client

- 注册服务到IP Server
- 同步依赖的服务到IP Server
- 封装服务调用
- 记录服务调用情况
- 同步调用到注册中心
