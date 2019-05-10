当我们的服务器，无法通过软件的方式提升并发响应的时候，有两种解决方案

1. 升级服务器主机，这种方法，我们称之为向上扩展，scale up
2. 增加服务器数量，分散请求，我们称之为向外扩展，scale out，组合多台主机，完成一个任务，这一个任务是可以被分割成多个小任务的大人物。

集合在一起的一组同类设备（同类事物），就是人们所谓的集群（cluster），在这里，我们的集群主要用于将任务分割后，将任务分散处理的，所以我们通常称之为负载均衡集群（load balancing cluster）

来此同一个用户的多次请求，可能会被分配到不同该服务器上，导致数据不能同步，两种解决方案！

数据都存储在一个共享存储设备中，所有服务器都能访问，读写！

 