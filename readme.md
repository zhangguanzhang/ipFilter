# 给网络组同事写的防火墙session日志过滤的cli

```
git clone xxxx $GOPATH/ipFilter
go build main.go
```
```
>main.exe
filter info

Usage:
  filter [flags]

Examples:

main.exe fw.log -n 10

Flags:
  -h, --help            help for filter
  -n, --number uint32   result line number (default 3)
```