# anheirium-dns-record

Anheirium WireGuard 内网 DNS 记录仓库。

## 使用方式

CoreDNS 从 Latest Release 拉取 `anhery.db` 和 `version.json`。

## 更新流程

1. 修改 `anhery.db` 和 `version.json`（更新 serial）
2. 推送到 main 分支
3. 创建新 Release，附带这两个文件
