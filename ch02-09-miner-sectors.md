# miner sectors

`lotus-miner sectors` 与扇区存储进行交互。

## 命令行

```
lotus-miner sectors command [command options] [arguments...]
```

## 子命令

```
status             通过扇区的编号得到它的密封状态
list               扇区列表
refs               列出对扇区的引用
update-state       高级：手动更新扇区的状态，这可能有助于错误恢复
pledge             在扇区中存储随机数据
remove             强行移除一个扇区(警告：这意味着失去被移除扇区的算力和抵押)
mark-for-upgrade   标志着一个承诺能力的扇区将被一个交易的扇区取代
seal               手动开始密封扇区(用垃圾填充任何未使用的空间)
set-seal-delay     设定新扇区等待交易的时间，以分钟为单位
get-cc-collateral  获得承诺产能扇区所需的抵押
help, h            显示一个命令的命令或帮助列表
```
