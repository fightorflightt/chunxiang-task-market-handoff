# 零工任务市场开发交付包

版本 v0.2 · 低保真 · 2026-10-13

本交付包按雇主、零工、平台三方组织，包含可点击原型、页面需求说明、统一业务规则和验收用例。

## 在线评审

[打开完整开发交付包](https://fightorflightt.github.io/chunxiang-task-market-handoff/)

- [低保真原型](https://fightorflightt.github.io/chunxiang-task-market-handoff/#prototype/E01)
- [页面需求说明](https://fightorflightt.github.io/chunxiang-task-market-handoff/#spec/E01)
- [统一业务规则](https://fightorflightt.github.io/chunxiang-task-market-handoff/#rules)
- [验收用例](https://fightorflightt.github.io/chunxiang-task-market-handoff/#tests)

## 内容

- 15 个低保真页面，黑白灰线框。
- 15 份页面说明，包含入口、展示字段、前置条件、操作结果与异常处理。
- 12 条共用业务规则，以及任务、订单、酬金与提现状态。
- 22 个验收场景；页面、规则、用例编号相互关联。
- 8 项待确认决策。

## 文档

- [页面需求说明](page-requirements.md)
- [统一业务规则](business-rules.md)
- [验收用例](acceptance-cases.md)
- [待确认事项](review-decisions.md)
- [验证记录](VALIDATION.md)
- [离线交付包](task-market-developer-handoff-v0.2.zip)

## 原型边界

原型仅模拟交互，不连接真实账户、支付或订单服务。金额、期限、费用及账户均为演示值，不代表最终产品规则。生产系统仍需按验收用例验证。

## 离线使用

下载交付包并解压，打开 task-market-handoff/dist/index.html 即可，无需联网。演示进度保存在本机浏览器，可以重置。

## 部署

使用 GitHub Pages，从 main 分支根目录发布；.nojekyll 保留原始静态文件，不配置自定义域名。
