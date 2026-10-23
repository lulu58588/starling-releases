# 星鸣 Starling · 发布仓库

这个仓库只放**发布产物**：桌面版（macOS / Windows / Linux）与纯终端版的安装包。

- 打 tag 会在 [lulu58588/starling](https://github.com/lulu58588/starling) 触发 `release.yml`，
  它用 `repository_dispatch` 派发到这里构建、签名、公证并发布，产物落在本仓库的 Releases。
- 同一个 Release 会被复制回主仓库的 Releases 页，方便从两处下载。
- 自动更新与更新源只读本仓库。

签名的密钥（macOS Developer ID 证书、Apple 公证凭据）只存在这里，不进主仓库。
