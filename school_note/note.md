# CCNA command

router 指令

* user 到 root

```bash
enable
```
or

```bash
en
```

* 要做任何設定都要進入 configure terminal

```bash
configure terminal
```
or

```bash
config t
```

設定 IP：

* 先指定 interface

```bash
int <interface>
```

```bash
ip addr <ip> <mask>
```

help

```bash
ip address ?
```

取消先前指令的設定

```bash
no <command>
```

設定 password

```bash
enable secret <password>
```

設定 line console password

```bash
line console 0
password <password>
login
```

列出目前設定

```bash
sh running
```


列

https://github.com/sipponkrisna/cisco_eSIM_router_configuration/blob/master/router%20configuration%20codes.txt