# lotus client

lotus client - 做交易，存储数据，检索数据

## 使用格式

```
lotus client command [command options] [arguments...]
```

## 命令行选项

```
help, h  显示一个命令的命令或帮助列表
```



## 可用命令

### data：

```
	 import  导入数据
     drop    移除import数据
     local   列出本地导入的数据
```

### retrieval:

```
	 find      在网络中查找数据
     retrieve  从网络检索数据
```

### storage:

```
     deal        与一个矿工初始化存储交易
     query-ask   找一个矿工的需求
     list-deals  列出存储市场交易
     get-deal    打印详细交易信息
     list-asks   列出所有可以接单的矿工
```

### util:

```
	 commP             计算出块文件的 piece-cid (commP)
     generate-car      从输出生成一个 car file
     info              打印存储市场的客户端信息
     list-transfers    列出正在进行中的的交易数据传输
     restart-transfer  强制重启停止的数据传输
```



