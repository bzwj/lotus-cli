# miner storage

`lotus-miner storage` - 管理扇区存储manage sector storage

## 使用格式：

```shell
lotus-miner storage command [command options] [arguments...]
```

## 描述：

*扇区可以跨许多文件系统路径存储。 这些命令提供了管理矿工将用于长期存储扇区以进行验证的存储（称为“存储”）的方式，以及在通过密封管道移动时如何存储扇区的存储（称为“密封”）。*

## 可选命令：

```shell
   attach   附加本地存储路径
   list     列出本地存储路径
   find     在存储系统中查找扇区
   cleanup  触发清理动作
   help, h  显示命令列表或一个命令的帮助
```

## 命令行选项：

```shell
   --help, -h     显示帮助 (default: false)
   --version, -v  打印版本号 (default: false)
```

