1. ./install.sh
2. 配置 iOS shortcut https://www.icloud.com/shortcuts/8281c014a3ad46fc9c76037732fa3c35 
3. lfn --help 自己研究怎么做

## 时区

`lfn` 默认使用 `Asia/Shanghai`，以保持现有 `UTC+8` 行为兼容。

如果你在其他时区，可以通过环境变量覆盖：

```sh
export LIFE_NOTE_TZ=Asia/Tokyo
```

`LIFE_NOTE_TZ` 需要是有效的 IANA 时区名称，例如 `Asia/Shanghai`、`Asia/Tokyo`。
