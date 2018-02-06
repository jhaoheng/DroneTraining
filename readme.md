# slideshow

https://www.slideshare.net/jhaohenghu/use-drone-to-cicd

# coverage.out

> coverage.out 檔案內容

```
mode: set
_/Users/maxhu/Documents/github/DroneTraining/go-example/main.go:7.13,9.2 1 1
_/Users/maxhu/Documents/github/DroneTraining/go-example/main.go:11.12,13.2 1 1
```

# troubshooting

- 伺服器出現 : `drone-server_1  | INFO: 2018/02/05 09:07:58 grpc: Server.processUnaryRPC failed to write status stream error: code = Canceled desc = "context canceled"`
  - 檢查 ip 與 port 是否 server 有被限制
