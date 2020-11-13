# miner init - 矿工初始化

`lotus-miner init` 对 Lotus 矿工仓库进行初始化。

## 命令行

```
lotus-miner init [command options] [arguments...]
```

## 命令行选项

```
--actor value                指定已经创建的矿工 actor 的地址
--create-worker-key          创建单独的工作者密钥 (默认为 false)
--worker value, -w value     要使用的工作者密钥 (覆盖 --create-worker-key)
--owner value, -o value      要使用的所有者密钥
--sector-size value          指定要使用的扇区大小 (默认为 "512MiB")
--pre-sealed-sectors value   指定一组预先密封的扇区，以便作为一个初始矿工启动
--pre-sealed-metadata value  指定预密封扇区的元数据文件
--nosync                     不检查全节点同步状态 (默认为 false)
--symlink-imported-sectors   尝试符号链接到预先密封的扇区，而不是将它们复制到适当的位置 (默认为 false)
--no-local-storage           不要对扇区存储使用矿工仓库 (默认为 false)
--gas-price value            在AttoFIL中为初始化消息设置 GAS 价格，单位 AttoFIL (默认为 "0")
--help, -h                   显示帮助 (默认为 false)
```
