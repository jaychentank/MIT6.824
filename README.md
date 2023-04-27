# mit6.824
课程主页：http://nil.csail.mit.edu/6.824/2022/index.html

lab1：基于单机多进程的MapReduce，独立完成了对txt文本单词数的统计

路径：mit6.824/src/mr/

lab2:实现了具有选举、心跳、同步、快照、持久化机制的Raft集群，在面对断电重启，网络分区等异常情况下仍能保持可用性

lab3:基于raft底层实现容错的键值服务，该服务维护一个简单的键值对数据库，在大量客户端并发请求Put、Append和Get操作时仍能满足线性一致性

路径：mit6.824/src/kvraft/ + mit6.824/src/raft/



[这里](https://github.com/jaychentank/Notes/blob/main/%E5%88%86%E5%B8%83%E5%BC%8F%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0.md)用于记录项目中遇到的困难和坑点。
