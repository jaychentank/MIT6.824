# mit6.824
课程主页：http://nil.csail.mit.edu/6.824/2022/index.html

lab1：基于单机多进程的MapReduce，独立完成了对txt文本单词数的统计。

路径：src/mr/

lab2：实现了具有选举、心跳、同步、快照、持久化机制的Raft集群，在面对断电重启，网络分区等异常情况下仍能保持可用性。

lab3：基于Lab2，构建了一个键值数据库服务，能在大量的客户端并发请求Put, Append和Get操作时能保持线性一致性。

路径：src/kvraft/ + src/raft/

lab4：基于Lab2，构建了一个分布式的，拥有分片功能的，当组离开或者组加入能保证负载均衡的，能够根据配置同步迁移数据的键值数据库服务。

额外的challenge：challenge1 要求及时清理不再属于本组的数据，challenge2 不仅要求分片迁移时不影响未迁移分片的读写服务，还要求不同地分片数据能够独立迁移。

路径：src/shardctrler(lab 4A) + src/shardkv(lab4B)

[这里](https://github.com/jaychentank/Notes/blob/main/%E5%88%86%E5%B8%83%E5%BC%8F%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0.md)用于记录项目中遇到的困难和坑点。
