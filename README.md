# go-redis

一个简洁的Golang Redis访问库.

仅支持单机模式, 如果需要集群, 请使用twemproxy overlord实现集群

使用方式参考 `redis_test.go` 文件

支持超时设置, 防止出现b站的那个坑, 就是专线断了, 然后全部堵死
