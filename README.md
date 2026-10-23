# 哎呀记账 · Aiya Ledger

哎呀，记一笔就好。无需注册的个人记账工具，记录收支、管理账户、查看日历、预算与统计。以下说明适用 1.4.0；实际可下载版本以 App Store 为准。

A little note. A clearer day. Personal bookkeeping without an app account. This documentation describes version 1.4.0; the App Store determines the version currently available.

## 技术支持 / Support

- 开发者：duhaley（个人开发者 / individual developer）
- 支持与隐私邮箱 / Support and privacy: **924323178@qq.com**

如需帮助，请通过邮箱联系，或在 [Issues](https://gitcode.com/duhaley/aiyalegder/issues) 描述问题。请提供应用版本、设备型号、系统版本、操作步骤及错误提示。截图请遮挡私人资料。请勿发送密码、Apple 验证码、完整银行卡号或完整账本。公开 Issue 中的内容可被其他人看到。

For help, email us or open an Issue with your app version, device, OS version, steps and error message. Redact personal information. Never send passwords, Apple verification codes, full card numbers or complete ledgers. Issues are public.

## 常见问题 / FAQ

### 如何备份和恢复？ / Backups and restoration

进入「设置 → 数据管理」，导出 JSON 完整备份，或在「云端备份」手动保存到自己的 iCloud Drive / HTTPS WebDAV 文件夹。恢复前核对文件与预览，确认后会替换当前账本。CSV 用于表格查看；完整恢复请保留 JSON。云备份不是实时账本同步。

Open Settings > Data management to export a complete JSON backup or manually use your own iCloud Drive / HTTPS WebDAV folder. Check the backup and preview before confirming restoration, which replaces the current ledger. CSV is for spreadsheet use; keep JSON for full restoration. Cloud backup is not real-time ledger sync.

### iCloud 等待上传或下载？ / Pending iCloud transfer

确认已登录 Apple 账户并开启 iCloud Drive，检查网络和 iCloud 空间，再刷新历史。等待上传不代表云备份已完成。请保留本地 JSON 副本，不要在没有可用备份时卸载应用。

Check your Apple account, iCloud Drive, connection and available cloud storage, then refresh history. A pending upload is not a completed backup. Keep local JSON copies and avoid uninstalling without a usable backup.

### 如何恢复 Pro？ / Restore Pro purchases

使用购买时的 Apple 账户，进入「设置 → 哎呀 Pro → 恢复购买」。Pro 是非消耗型一次买断，无自动续费；本次新增工具包含在原购买中。恢复账本不会授予购买权益，权益由 Apple 已验证交易确认。若无法连接商店，请联网后重试。退款由 Apple 处理。

Use the Apple account that purchased Pro, then open Settings > Aiya Pro > Restore Purchases. Pro is a non-consumable one-time purchase with no automatic renewal. New tools are included for existing buyers. Restoring a ledger does not grant Pro; Apple verifies ownership. Retry with a connection if the store is unavailable. Apple handles refunds.

### Pro 包含什么？ / What does Pro include?

七项工具：**分类与标签、消费复盘、自动分类规则、储蓄目标、分类预算、周期账单、进阶报表**。分类有 42 款统一尺寸的内置图标与配色；标签可跨分类使用。规则整理本机输入或导入记录，不读取短信或自动抓取其他应用。周期账单由用户确认后入账，本地提醒需另行允许通知。储蓄目标只作规划记录，不自动转移资金。

Seven tools: **custom categories and tags, spending reviews, classification rules, savings goals, category budgets, recurring bills and advanced reports**. Choose 42 category icons and colors, and use tags across categories. Rules process local input/imports, not SMS or other apps. Bills require confirmation; reminders require notification permission. Goals are planning records and do not move real funds.

基础记账、总预算、基础统计、收支日历、基础桌面小组件和 Watch 伴侣功能、导入导出、备份恢复、主题和常用模板继续免费。可在「设置 → 体验示例账本」体验全部七项 Pro；示例在独立内存空间运行，退出丢弃，不改动真实账本或购买状态。

Core bookkeeping, overall budget, basic statistics, money calendar, basic widgets/Watch companion, import/export, backups, themes and templates remain free. Settings > Explore a sample ledger offers all seven Pro tools in an isolated, temporary session without changing your real ledger or purchase status.

### Apple Watch 如何同步？ / Apple Watch sync

使用与 iPhone 配对的手表，打开手机与手表应用，保持系统连接可用。在「设置 → 设备与桌面 → Apple Watch」查看连接。手表显示最近同步的收支与预算，可快速记账并选择账户、分类和标签。Pro 用户可查看复盘和储蓄目标摘要，编辑在手机完成。

Use the companion on your paired Apple Watch and open both apps with a working system connection. Settings > Devices & widgets > Apple Watch shows connection information. The watch displays recently synced totals and budgets, supports quick entries, accounts, categories and tags, and gives Pro buyers read-only review/goal summaries. Edit plans on iPhone.

待同步记录会保留，直到手机校验并保存后确认。请先同步再卸载，不要靠反复记同一笔来重试。隐藏金额后，新同步快照不含汇总、复盘或目标金额。手表不发起付款、不提供独立云备份或购买。

Pending entries remain until iPhone validates and saves them. Sync before uninstalling and avoid entering duplicates to retry. New hidden-amount snapshots omit summary/review/goal amounts. The watch does not make payments or offer independent cloud backups or purchasing.

### 币种与数据保护 / Currencies and data protection

支持 14 种币种，按账户币种分开统计，不自动换汇，不支持跨币种转账。总览右上应用图标下方的币种标识可打开币种管理。

Fourteen currencies are kept separate by account, without conversion or cross-currency transfers. Open currency preferences using the currency badge below the app logo on Overview.

账本和导出文件没有应用级加密，隐藏金额只遮挡界面。请保护设备并妥善保管备份。导入账单在本机解析，不连接银行或索取支付密码。

Ledger and exported files are not encrypted by the app. Hiding amounts only masks the display. Protect your device and backups. Statements are parsed locally, with no bank connection or payment-password request.

## 隐私政策 / Privacy policy

- [简体中文政策全文](https://raw.gitcode.com/duhaley/aiyalegder/raw/main/privacy-policy-zh.txt)
- [English privacy policy](https://raw.gitcode.com/duhaley/aiyalegder/raw/main/privacy-policy-en.txt)

此仓库用于支持与隐私政策，不要求上传或公开个人账本。This repository provides support and privacy information; you do not need to publish your ledger.
