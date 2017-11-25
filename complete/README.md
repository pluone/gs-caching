说明：  
这是spring cache的官方demo，官方使用的缓存方案是ConcurrentHashMap
这里缓存实现替代为redis

启动项目之前需要在本机启动redis docker
具体方法为:
- 从docker加速地址拉取redis镜像  
`docker pull registry.docker-cn.com/library/redis`  
- 启动docker redis容器  
`docker run --name redis -p 6379:6379 -d redis`
- 最后执行docker ps查看redis启动状态