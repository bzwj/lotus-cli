# lotus msig

lotus - msig 与一个多重签名钱包相互作用

## 使用格式

```
lotus msig command [command options] [arguments...]
```

## 命令行选项

```
   --confidence value  等待证明的块数（默认值：5）
   
   --help, -h          显示帮助
   
   --version, -v       打印当前版本号
```

## 可用命令

```
   create             创建一个新的多签钱包
   
   inspect            检验一个多签钱包
   
   approve            批准一个多重签名消息
   
   vested             获取两个epochs之间归属于msig的金额
   
   propose-threshold  建议在帐户上设置不同的签名阈值
   
   help, h            显示命令列表或一个命令的帮助
```

### propose：

```
   propose            提出一个多重签名事务
   
   propose-remove     建议移除一个签名者
```

### add：

```
   add-propose        建议添加签名者
   
   add-approve        批准消息以添加签名者
   
   add-cancel         取消添加签名者的消息
```

### swap：

```
   swap-propose       建议交换签名者

   swap-approve       批准交换签名者消息

   swap-cancel        取消交换签名者消息
```

### lock：

```
   lock-propose       建议锁定一些余额
   
   lock-approve       批准锁定余额消息
   
   lock-cancel        取消锁定余额消息
```

