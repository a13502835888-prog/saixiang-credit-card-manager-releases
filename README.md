# 赛向信用卡管家 · Windows 正式版下载

这个仓库仅用于分发经过审查的 Windows 客户端、更新清单和校验文件，不包含应用源码、账号凭证或用户账务。

- [v0.7.0 正式版发布](https://github.com/a13502835888-prog/saixiang-credit-card-manager-releases/releases/tag/production-v0.7.0)
- [下载正式便携包](https://github.com/a13502835888-prog/saixiang-credit-card-manager-releases/releases/download/production-v0.7.0/SaixiangCreditCardManager-production-0.7.0-x64.zip)
- [SHA-256 校验文件](https://github.com/a13502835888-prog/saixiang-credit-card-manager-releases/releases/download/production-v0.7.0/SHA256SUMS.txt)

已有带更新入口的客户端，请使用“帮助 → 检查更新”。v0.5.0 没有该入口，首次应使用另行交付的首次升级工具；以后原桌面快捷方式保持不变。不要把测试贷款包替换到正式目录。

正式更新通道为 `production-channel`，版本发布为 `production-v<版本>`。测试通道与正式通道相互隔离；v0.7.0 正式包没有开放贷款入口。程序更新不执行数据库迁移，不修改云端账务。

客户端下载依靠指定 GitHub HTTPS 源与 SHA-256 校验。这不是代码签名，也不提供签名级防篡改保证。
