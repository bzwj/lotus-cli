# lotus paych

 lotus paych - 管理支付渠道

## 使用格式

```
lotus paych command [command options] [arguments...]
```

## 可用命令

```
   add-funds          将资金添加到fromAddress和toAddress之间的支付通道中。如果不存在则创建支付通道。
   
   list               列出所有本地已注册的支付渠道
   
   voucher            与支付渠道凭证互动
   
   settle             结算付款渠道（settle：解决；结清）
   
   status             显示出站付款渠道的状态
   
   status-by-from-to  通过发件人/收件人地址显示一个活跃的对外支付渠道的状态
   
   collect            为支付渠道收集资金
   
   help, h            显示一个命令的命令或帮助列表
```

