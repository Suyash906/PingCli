# PingCli
CLI app to send ICMP packet to hostname

### Use command like this
```
    1. go run main.go pinger mail.google.com
    2. go run main.go pinger 127.0.0.1
```
### Sample Output
```
2020/04/19 23:16:20 Ping 127.0.0.1 (127.0.0.1): RTT : 53.237µs

2020/04/19 23:16:22 Ping 127.0.0.1 (127.0.0.1): RTT : 176.998µs

...
```

### Refernece
1. https://gist.github.com/lmas/c13d1c9de3b2224f9c26435eb56e6ef3