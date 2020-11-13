# lotus-seal-worker 命令行

lotus-seal-worker 命令行是远程存储矿工工作者。

## 命令行

```
lotus-seal-worker [global options] command [command options] [arguments...]
```

## 命令行选项

```
--workerrepo value    (默认: "~/.lotusworker") [$WORKER_PATH]
--storagerepo value   (默认: "~/.lotusstorage") [$LOTUS_STORAGE_PATH]
--enable-gpu-proving  允许使用 GPU 进行挖矿操作 (默认: true)
--help, -h            显示帮助 (默认：false)
--version, -v         打印版本 (默认：false)
```

## 子命令

```
run      启动 lotus 工作者
help, h  显示一个命令的命令或帮助列表
```

## 本地仓库路径

lotus-seal-worker 使用本地文件系统中的仓库存储内容。默认情况下，本地仓库位于 `~/.lotusworker`。你可以设置 WORKER_PATH 环境变量来定义本地仓库的位置：

```
export WORKER_PATH=/path/to/lotusworkerrepo
```

## 命令行退出状态

命令行的退出码如下：

- 0：执行成功
- 1：执行失败
