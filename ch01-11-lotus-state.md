# lotus state

lotus state -与filecoin链状态进行交互并查询

## 使用格式

```
lotus state command [command options] [arguments...]
```

## 命令行选项

```
   --tipset value  指定ipset所调用的方法(用逗号隔开的 cids 数组)
   
   --help, -h      
   
   --version, -v   
```



## 可用命令

```
   power               查询网络或矿机功率
   
   sectors             查询矿机的扇区集（sector：扇区）
   
   active-sectors      查询矿机的活动扇区集
   
   list-actors         列出网络中的所有参与者
   
   list-miners         列出网络中的所有矿工
   
   circulating-supply  获取当前Filecoin的准确循环供应
   
   sector              获取矿机扇区信息
   
   get-actor           打印“Actor”信息
   
   lookup              查找相配的 ID 地址
   
   replay              重播特定消息
   
   sector-size         查找矿机扇区规模
   
   read-state          查看以 JSON 格式显示的Actors状态
   
   list-messages       列出符合给定条件的链条上的消息
   
   compute-state       执行状态计算
   
   call                在本地 actor 上调用方法
   
   get-deal            查看链上交易信息
   
   wait-msg            等待消息出现在链上
   
   search-msg          搜索以查看消息是否已出现在链上
   
   miner-info          检索矿工信息
   
   market              检查存储市场Actor（参与者）
   
   exec-trace          获取给定消息的执行跟踪
   
   help, h             显示命令列表或一个命令的帮助
```

