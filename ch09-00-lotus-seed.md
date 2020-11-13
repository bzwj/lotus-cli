# lotus-seed 命令行

lotus-seed 命令行是用于密封创世矿工扇区。

## 命令行

```
lotus-seed [global options] command [command options] [arguments...]
```

## 命令行选项

```
--sector-dir value  (默认："~/.genesis-sectors")
--help, -h          显示帮助 (默认：false)
--version, -v       打印版本 (默认：false)
```

## 子命令

```
genesis
pre-seal
aggregate-manifests  将一组预封清单聚合到单个文件中
help, h              显示一个命令的命令或帮助列表
```

## 命令行退出状态

命令行的退出码如下：

- 0：执行成功
- 1：执行失败
