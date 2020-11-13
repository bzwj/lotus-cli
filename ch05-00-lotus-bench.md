# lotus-bench 命令行

lotus-bench 命令行是在您的硬件上对 lotus 进行性能基准测试。

## 命令行

```
bench [global options] command [command options] [arguments...]
```

## 命令行选项

```
--help, -h     显示帮助 (默认：false)
--version, -v  打印版本 (默认：false)
```

## 子命令

```
prove    证明计算的基准测试
sealing
import   链导入和验证的基准测试
help, h  显示一个命令的命令或帮助列表
```

## 命令行退出状态

命令行的退出码如下：

- 0：执行成功
- 1：执行失败
