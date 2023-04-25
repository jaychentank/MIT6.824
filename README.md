# mit6.824
lab1：基于单机多进程的MapReduce，独立完成了对txt文本单词数的统计

路径：mit6.824/src/mr/coordinator.go + rpc.go + worker.go

lab2:实现了具有选举、心跳、同步、快照、持久化机制的Raft集群，在面对断电重启，网络分区等异常情况下仍能保持可用性

路径：mit6.824/src/kvraft/client.go + common.go + server.go

mit6.824/src/raft/raft.go + util.go + persister.go

（lab3是基于lab2的，由于时间原因是写了一点点就上传了）