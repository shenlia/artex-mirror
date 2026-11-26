# ARTEX 发布产物（镜像）

本目录存放上游 **v0.3.31** 的官方发布二进制，原样搬运，未做任何修改。

- 上游仓库：https://github.com/RuoJi6/ARTEX
- 上游发布页：https://github.com/RuoJi6/ARTEX/releases/tag/v0.3.31
- 发布日期：2026-11-23
- 许可证：AGPL-3.0（见仓库根目录 `LICENSE`）

## 文件

| 文件 | 平台 | 大小 |
| --- | --- | --- |
| `artex-0.3.31-linux-amd64.zip` | Linux x86_64 | 15.5 MB |
| `artex-0.3.31-linux-arm64.zip` | Linux ARM64 | 14.5 MB |
| `artex-0.3.31-darwin-amd64.zip` | macOS Intel | 15.7 MB |
| `artex-0.3.31-darwin-arm64.zip` | macOS Apple Silicon | 15.0 MB |
| `artex-0.3.31-windows-amd64.zip` | Windows x86_64 | 15.8 MB |
| `SHA256SUMS` | 校验和（上游原文件） | 479 B |

## 校验

```bash
cd releases/v0.3.31
sha256sum -c SHA256SUMS      # Linux
shasum -a 256 -c SHA256SUMS  # macOS
```

## 官方容器镜像

```
docker pull ruoji6/artex:v0.3.31
docker pull ruoji6/artex:latest
```

支持 linux/amd64 与 linux/arm64，Docker 自动按宿主架构选择。

---

本仓库是 `RuoJi6/ARTEX` 的完整 Git 镜像（全部分支与标签），仅作备份与加速分发用途；代码著作权归原作者所有，遵循 AGPL-3.0。
