# lotus daemon

lotus daemon - 启动一个lotus守护进程

## 使用格式

```
lotus daemon command [command options] [arguments...]
```

## 命令行选项

```
  stop     停止运行lotus守护进程
  help, h  显示一个命令的命令或帮助列表
```

## 可用命令列表

```
   --api value              默认值：“1234”
   
   --genesis value          在第一个节点运行时使用的生成文件
   
   --bootstrap              默认值：true
   
   --import-chain value     在第一次运行时，从给定的文件或url加载链并进行验证
   
   --import-snapshot value  从给定的链导出文件或url导入链状态
   
   --halt-after-import      在从文件导入链之后暂停进程(默认:false)
   
   --pprof value            指定要写入cpu配置文件的文件名称
   
   --profile value          指定节点的类型
   
   --manage-fdlimit         管理打开文件限制(默认:true)
   
   --config value           指定要使用的配置文件路径
   
   --help, -h               显示帮助(默认:false)
   
   --version, -v            打印版本(默认:false)
```



