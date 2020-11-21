# miner net

`lotus-miner net` - 管理P2P网络

## 使用格式

```sh
lotus-miner net command [command options] [arguments...]
```

## 可选命令

```sh
   peers         打印peers
   connect       连接到一个peer
   listen        列出监听地址
   id            获取节点身份
   findpeer      查找给定peerID的地址
   scores        打印peers的pubsub分数
   reachability  从互联网上打印有关可达性(reachability)的信息
   bandwidth     打印带宽使用情况信息
   block         管理网络连接选通规则
   help, h       显示命令列表或一个命令的帮助
```

## 命令行选项：

```shell
   --help, -h     显示帮助 (default: false)
   --version, -v  打印版本号 (default: false)
```

