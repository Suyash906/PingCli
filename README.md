### Packages Used
```
    1. github.com/spf13/cobra
    2. github.com/mitchellh/go-homedir
    3. github.com/spf13/viper
    4. golang.org/x/net/icmp
    5. golang.org/x/net/ipv4
```

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
1. https://github.com/golang/net/tree/d3edc9973b7eb1fb302b0ff2c62357091cea9a30/icmp
