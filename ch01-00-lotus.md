# lotus 命令行

lotus 命令行是 Filecoin 去中心化存储网络客户端。

## 命令行

```
lotus [global options] command [command options] [arguments...]
```

## 命令行选项

```
--help, -h     显示帮助 (默认：false)
--version, -v  打印版本 (默认：false)
```

## 基本子命令

```
send    在账户间发送资金
wallet  管理钱包
client  制作交易，存储数据，检索数据
msig    与多签钱包交互
paych   管理支付渠道
```

## 开发者子命令

```
auth          管理 RPC 权限
mpool         管理消息池
state         与 filecoin 链状态交互并查询
chain         与 filecoin 区块链交互
log           管理日志
wait-api      等待 lotus api 上线
fetch-params  获取验证参数
```

## 网络子命令

```
net   管理 P2P 网络
sync  检查链同步器或与之交互
```

## 本地仓库路径

lotus 使用本地文件系统中的仓库存储内容。默认情况下，本地仓库位于 `~/.lotus`。你可以设置 LOTUS_PATH 环境变量来定义本地仓库的位置：

```
export LOTUS_PATH=/path/to/lotusrepo
```

## 命令行退出状态

命令行的退出码如下：

- 0：执行成功
- 1：执行失败
