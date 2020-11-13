# lotus-miner storage-deals

lotus-miner storage-deals - 管理存储协议和相关配置

## 使用格式

```
lotus-miner storage-deals command [command options] [arguments...]
```

## 可用命令

```
   import-data        手动导入交易数据
   
   list               列出该矿工的所有交易
   
   selection          为存储交易提案配置接受标准
   
   set-ask            配置矿工的请求
   
   get-ask            打印矿工的请求
   
   set-blocklist      设置矿工的“blocklisted”块CIDs列表
   
   get-blocklist      列出矿工块“CID blocklist”的内容
   
   reset-blocklist    从矿工的“CID blocklist”中删除所有记录
   
   set-seal-duration  设置预期的时间(以分钟记)，您希望密封扇区花费的时间。在此期限前开始的交易将被拒绝。
   
   help, h            显示命令列表或一个命令的帮助
```

