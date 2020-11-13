# lotus chain

lotus chain - 与 filecoin 区块链交互

## 使用格式

```
lotus chain command [command options] [arguments...]
```

## 可用命令

```
   head             打印链头
   
   getblock         获取一个块并打印它的详细信息
   
   read-obj         读取对象的原始字节
   
   delete-obj       从链块存储中删除一个对象
   
   stat-obj         收集objs的大小和ipld连接数
   
   getmessage       通过cid获得并打印message
   
   sethead          手动设置本地节点头tipset，（警告：通常仅用于恢复）
   
   list, love       查看链的一部分
   
   get              通过路径获取链DAG节点
   
   bisect           为事件将链一分为二（bisect：一分为二，二等分）
   
   export           将链导出到“car File”
   
   slash-consensus  报告共识错误（consensus：共识，一致）
   
   gas-price        估计gas价格
   
   inspect-usage    检查给定“tipset”的块空间使用情况
   
   decode           解码各种类型
   
   help, h          显示命令列表或一个命令的帮助
```

