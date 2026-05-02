# AGENTS.md

## 仓库定位

这个仓库是 AG Mob 的公开社区与支持中心，用于运营 App Store 上架后的用户沟通、问题收集、功能建议、公告、已知问题和版本更新。

这个仓库不是私有源码仓库。不要在这里添加 App 源码、构建配置、商店素材、密钥、内部接口、私有路线图或任何无法公开的信息。

## 文件位置

- Issue 表单：`.github/ISSUE_TEMPLATE/`
- Discussion 分类表单：`.github/DISCUSSION_TEMPLATE/`
- 置顶帖草稿：`docs/community/seed-posts/`
- 社区运营流程：`docs/community/moderation-runbook.md`
- 手动配置清单：`docs/community/manual-next-steps.md`

## 社区分流规则

- Bug / 可复现故障：提交到 GitHub Issues。
- 使用问题 / How-to：发到 GitHub Discussions 的 `Q&A` 分类。
- 功能想法 / Feature idea：发到 GitHub Discussions 的 `Ideas` 分类。
- 普通交流 / 社区话题：发到 GitHub Discussions 的 `General` 分类。
- 实时帮助 / 轻松聊天：引导到 Discord：`DISCORD_INVITE_URL`。
- 安全漏洞 / 隐私风险：只通过 `SECURITY_EMAIL` 私下报告，不要发布公开 Issue 或 Discussion。

## 后续 Codex 维护规则

后续维护这个仓库时，请优先保持内容短、清晰、面向最终用户。不要把这里扩展成源码协作仓库。

更新版本说明时：

1. 使用 `docs/community/seed-posts/release-notes.md` 的结构准备发布内容。
2. 面向用户描述变化，避免内部实现细节。
3. 如果需要同步公开信息，将内容复制到 `Announcements` 分类的版本更新帖。

更新已知问题时：

1. 使用 `docs/community/seed-posts/known-issues.md` 的结构记录问题、临时方案和修复状态。
2. 每个问题都写清影响版本、影响平台、状态和替代方案。
3. 已修复的问题在发布说明中关闭循环，并在已知问题帖中标记为已修复。

处理用户反馈时：

1. 先搜索是否已有重复 Issue 或 Discussion。
2. 缺少复现信息的 Bug 先补充提问，不要急着关闭。
3. 安全、隐私、账号、支付相关敏感内容立即引导到私密邮箱。
