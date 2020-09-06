# gin-grpc-demo
- 这是从下面网址学的例子 仅用来个人测试学习
- https://blog.csdn.net/u013474436/article/details/87863833

# How to run
- run grpc server
```
$ go run grpc/server.go
```
- run gin server
```
$ go run gin/main.go
```
- use curl command to test it
```
$ curl -v 'http://localhost:8052/rest/n/thinkerou'
```

# result
- 启动grpc-server 监听tcp:50051
![Image](https://raw.githubusercontent.com/purevirtual/gin-rpc-demo/master/assets/images/1.png)
- 启动gin-server http:8052
![Image](https://raw.githubusercontent.com/purevirtual/gin-rpc-demo/master/assets/images/2.png)
- 使用curl作为client 通过访问gin来间接调用grp-server
![Image](https://raw.githubusercontent.com/purevirtual/gin-rpc-demo/master/assets/images/3.png)