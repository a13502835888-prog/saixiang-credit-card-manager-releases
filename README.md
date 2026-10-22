# 赛向信用卡管家 · Windows 正式版下载

这个仓库仅用于分发经过审查的 Windows 客户端、更新清单和校验文件，不包含应用源码、账号凭证或用户账务。

- [V11（v0.11.0）正式版发布](https://github.com/a13502835888-prog/saixiang-credit-card-manager-releases/releases/tag/production-v0.11.0)
- [下载正式便携包](https://github.com/a13502835888-prog/saixiang-credit-card-manager-releases/releases/download/production-v0.11.0/SaixiangCreditCardManager-production-0.11.0-x64.zip)
- [SHA-256 校验文件](https://github.com/a13502835888-prog/saixiang-credit-card-manager-releases/releases/download/production-v0.11.0/SHA256SUMS.txt)

已有带更新入口的客户端，请使用“帮助 → 检查更新”。v0.5.0 没有该入口，v0.7.0 的检查更新存在跳转兼容问题，v0.7.1 的大包下载时限较短；这些版本均请使用另行交付的 v0.7.2 首次升级工具；以后原桌面快捷方式保持不变。不要把测试贷款包替换到正式目录。

正式更新通道为 `production-channel`，版本发布为 `production-v<版本>`。测试通道与正式通道相互隔离；v0.9.0 正式包保留贷款及信用卡功能，并新增“设置 → 导出我的账本”，只导出当前账号16类业务资料；JSON不等于数据库或账号灾备。程序更新不执行数据库迁移，不修改云端账务。

客户端下载依靠指定 GitHub HTTPS 源与 SHA-256 校验。这不是代码签名，也不提供签名级防篡改保证。

Windows v0.9.1 修复窗口获焦只读刷新/离线状态导致的更新误拦截，真实未完成操作仍受保护。

Windows v0.10.0 根据同卡至少3期实际账单识别唯一还款日规则并预填建议；保存前仍须核对银行实际最后还款日。

Windows v0.10.1 修复 Electron 将 app.asar 误当目录导致的更新准备失败；失败时显示具体阶段和安全诊断代码，不记录账号、凭证或账务。

Windows v0.10.2 建卡无需填写固定还款日，未登记时显示“待银行账单确认”；旧卡日期和账务保持，实际日期继续按银行账单核对。
