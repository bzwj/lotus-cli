# lotus send

```
lotus send - Send funds between accounts
lotus send -在帐户之间发送资金
用法：lotus send [command options] [targetAddress] [amount]
```

## 使用格式

```
lotus send [command options] [targetAddress] [amount]
```

## 可用命令列表

```
   --from value         可选地指定要从中发送资金的帐户
   
   --gas-premium value  指定AttoFIL中使用的gas价格(默认为“0”)
   
   --gas-feecap value   指定AttoFIL中使用的gas费用上限(默认为“0”)
   
   --gas-limit value    指定gas限制(默认值:0)
   
   --nonce value        指定要使用的nonce(默认值:-1)
   
   --method value       指定要调用的方法(默认值:0)
   
   --params-json value  以json格式指定调用参数
   
   --params-hex value   用十六进制指定调用参数
   
   --help, -h           显示帮助(默认:false)
```

