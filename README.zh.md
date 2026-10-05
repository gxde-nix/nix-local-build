# GXDE-NIX本地构建脚本
此脚本用于本地构建Nix包。

## 用法
```
用法: build-nix [选项] [目标]

从本地目录构建Nix包。

选项:
  -L, --log       构建时打印日志
      --rebuild   重新构建以检查可复现性
      --cleanup   清理产物
  -h, --help      打印帮助

目标:
  一个.nix文件或者flake installable，例如.#package。
  默认在当前目录查找。
```

## 许可证
(C) 2026 CharOfString.

`build-nix`以[MIT](https://spdx.org/licenses/MIT.html) 或 (如果您想要) [GPL-1.0-or-later](https://spdx.org/licenses/GPL-1.0-or-later.html)协议获得许可。
