# AlphaPilot

AlphaPilot 是 AlphaPilotHQ 团队发布正式版本与收集反馈的集中站点。所有公开发行版都可以在 GitHub Release 页面获取，问题追踪也统一放在 Issues 中，方便团队与社区协作。

## 快速开始
1. 克隆仓库并切换到目标标签，例如 `git clone https://github.com/AlphaPilotHQ/AlphaPilotHQ.git` 后执行 `git checkout v1.6.0`。
2. 下载对应发行包，或参考 `Asset/` 目录中的随版本发布的资源。
3. 若需提交问题，在 `Issues` 中按照模板描述环境与复现步骤，避免重复（DRY 原则确保信息集中在单一位置）。

## 发布结构
- Release 页面保留所有版本的变更说明与二进制附件。
- `Asset/` 目录维护各版本通用素材，按需引用以保持模块内聚（符合单一职责原则）。
- 标签（如 `v1.6.0`）代表冻结的稳定快照，便于复现及部署。

## 社区与支持
- 官方网站提供文档、下载与公告：[AlphaPilot 官网](https://www.alphapilot.tech/home)。
- 欢迎加入 [Telegram 社群](https://t.me/AlphaPilotClub) 与其他用户交流经验。
- 如需反馈敏感问题，可通过 Issues 设为私密或联系维护者，遵循最小接触面（Demeter 法则）仅暴露必要信息。

## 贡献指南
1. Fork 仓库并基于最新标签创建分支，使用 PR 提交变更。
2. 在自测后附上操作步骤和预期行为说明，保证审阅者能快速验证。
3. 保持文档、脚本与资源的职责划分清晰，避免一处修改影响不相关模块（遵守 SOLID 中的 OCP 与 ISP）。

## 反馈渠道
- GitHub Issues：功能需求、缺陷报告与一般讨论。
- Release 评论：针对具体发行版本的建议或问答。
- 社区活动：关注官方公告，参与线上活动以获取最新动态。

