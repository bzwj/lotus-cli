# seed pre-seal - 预密封

`seed pre-seal` 对矿工的扇区进行预密封。

## 命令行

```
lotus-seed pre-seal [command options] [arguments...]
```

## 命令行选项

```
--miner-addr value       指定你的矿工的未来地址 (默认为 "t01000")
--sector-size value      指定要预封的扇区大小 (默认为 "2KiB")
--ticket-preimage value  为密封随机性设置预镜像标签 (默认为 "lotus is fire")
--num-sectors value      选择要预封的扇区数 (默认: 1)
--sector-offset value    开始密封时跳过多少个扇区id (默认: 0)
--key value              (可选)用于签名/所有者/工作者地址的密钥
--fake-sectors           (默认为 false)
--help, -h               显示帮助 (默认为 false)
```
