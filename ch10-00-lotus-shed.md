# lotus-shed 命令行

lotus-shed 命令行是放置所有 lotus 工具的地方。

## 命令行

```
lotus-shed [global options] command [command options] [arguments...]
```

## 命令行选项

```
--help, -h     显示帮助 (默认：false)
--version, -v  打印版本 (默认：false)
```

## 子命令

```
base32
base16
bitfield
keyinfo          使用 lotus keyinfo 文件(钱包和 libp2p 主机密钥)
noncefix
bigint
stateroot-stats
import-car
commp-to-cid
fetch-params     获取验证参数
proofs
verifreg         与验证注册中心参与者交互
help, h          显示一个命令的命令或帮助列表
```

## 命令行退出状态

命令行的退出码如下：

- 0：执行成功
- 1：执行失败
