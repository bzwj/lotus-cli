# bench sealing - 基准测试密封

`bench sealing` 对 Lotus 的密封进行基准测试。

## 命令行

```
bench sealing [command options] [arguments...]
```

## 命令行选项

```
--storage-dir value                       存储长期扇区的存储目录的路径 (默认为 "~/.lotus-bench")
--sector-size value                       扇区的字节大小，即32GiB (默认为 "512MiB")
--no-gpu                                  在基准测试运行时禁用 gpu 使用 (默认为 false)
--miner-addr value                        传递矿机地址(只有在使用现有扇区构建器时才需要)(默认为 "t01000")
--benchmark-existing-sectorbuilder value  传递一个目录以在现有的扇区构建器上运行提交计时
--json-out                                输出json格式的结果 (默认为 false)
--skip-commit2                            跳过基准测试的 commit2 (snark)部分 (默认为 false)
--skip-unseal                             跳过基准测试的解封部分 (默认为 false)
--save-commit2-input value                将 commit2 输入保存到一个文件中
--num-sectors value                       (默认为 1)
--parallel value                          (默认为 1)
--help, -h                                显示帮助 (默认为 false)
```
