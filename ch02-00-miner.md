# lotus-storage-miner 命令行

lotus-storage-miner 命令行是 Filecoin 去中心化存储网络存储矿工。

## 命令行

```
lotus-storage-miner [global options] command [command options] [arguments...]
```

## 命令行选项

```
--storagerepo value  (默认: "~/.lotusstorage") [$LOTUS_STORAGE_PATH]
--help, -h           显示帮助 (默认：false)
--version, -v        打印版本 (默认：false)
```

## 基本子命令

```
actor            操作矿工参与者
storage-deals    管理存储交易和相关配置
retrieval-deals  管理检索交易和相关配置
info             打印存储矿工信息
init             初始化 lotus 存储矿工仓库
rewards          管理挖矿奖励
run              启动一个 lotus 存储矿工进程
stop             停止运行的 lotus 存储矿工
sectors          与扇区存储交互
storage          管理扇区存储
workers          与工作者互动
proving          证明信息视图
version          打印版本
help, h          显示一个命令的命令或帮助列表
```

## chain：

```
actor  操作矿机的actor
info   打印miner的信息
```

## developer:

```
auth          管理 RPC 权限
log           管理日志
wait-api      等待 lotus api 上线
fetch-params  获取验证参数
```

## market：

```
storage-deals    管理存储交易和相关配置
retrieval-deals  管理检索交易和相关配置
data-transfers   管理数据传输
```

## network:

```
net   管理 P2P 网络
```

## retrieval：

```
pieces  与piecestore交互
```

## storage：

```
sectors  与扇区店互动
proving  证明信息视图
storage  管理扇区存储
sealing  与密封管道相互作用
```

## 全局选项

 

```
--actor value, -a value
	：指定要检查状态的其他actor(只读)
	
--color
	:默认：false
	
--miner-repo value, --storagerepo value  
	：指定矿机回购路径。flag(storagerepo)和env(LOTUS_STORAGE_PATH)是不支持的，将很快删除(默认为“~/.lotusminer”)[$LOTUS_MINER_PATH， $LOTUS_STORAGE_PATH]


```



## 本地仓库路径

lotus-storage-miner 使用本地文件系统中的仓库存储内容。默认情况下，本地仓库位于 `~/.lotusstorage`。你可以设置 LOTUS_STORAGE_PATH 环境变量来定义本地仓库的位置：

```
export LOTUS_STORAGE_PATH=/path/to/lotusstoragerepo
```

## 命令行退出状态

命令行的退出码如下：

- 0：执行成功
- 1：执行失败
