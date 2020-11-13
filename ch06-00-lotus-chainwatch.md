# lotus-chainwatch 命令行

lotus-chainwatch 命令行是链监测工具。

## 命令行

```
chainwatch [global options] command [command options] [arguments...]
```

## 命令行选项

```
--repo value   (默认："~/.lotus") [$LOTUS_PATH]
--db value     [$LOTUS_DB]
--help, -h     显示帮助 (默认：false)
--version, -v  打印版本 (默认：false)
```

## 子命令

```
run      启动 lotus chainwatch
dot      生成点图
help, h  显示一个命令的命令或帮助列表
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
