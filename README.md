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
