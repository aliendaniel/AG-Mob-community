# Manual Next Steps / 手动配置清单

以下任务需要在 GitHub UI 或发布渠道中手动完成。

## 占位符替换

- 将 `DISCORD_INVITE_URL` 替换为真实 Discord 邀请链接。
- 将 `SUPPORT_EMAIL` 替换为真实支持邮箱。
- 将 `SECURITY_EMAIL` 替换为真实安全邮箱。
- 将 `APPSTORE_URL` 替换为真实 App Store 地址。
- 将 `TESTFLIGHT_URL` 替换为真实 TestFlight 地址；如果不公开 TestFlight，可以删除相关行。

## GitHub Discussions

- 确认 Discussions 已启用。
- 确认分类名称完全为 `Announcements`、`Q&A`、`Ideas`、`General`。
- 确认分类 slug 与模板文件匹配：`announcements.yml`、`ideas.yml`。
- 把 `docs/community/seed-posts/start-here.md` 复制成第一个置顶帖。
- 把 `docs/community/seed-posts/known-issues.md` 复制成已知问题置顶帖。
- 把 `docs/community/seed-posts/release-notes.md` 用作每个版本的发布模板。

## GitHub Issues

- 打开 Issue chooser，确认 Bug 表单和 Feature Request 表单可见。
- 确认空白 Issue 已关闭。
- 确认 Discord 和 Security contact links 能跳转到正确位置。
- 确认 `bug`、`feature`、`triage` 标签存在，颜色和描述清晰。
- 根据需要新增 `needs-info`、`duplicate`、`iOS`、`Android`、`known-issue` 标签。

## 发布前检查

- README 中的快速入口可以正常打开。
- SECURITY 明确要求不要公开安全问题。
- SUPPORT 中的渠道分流和邮箱正确。
- CODE_OF_CONDUCT 足够清晰，并能覆盖垃圾信息、攻击性内容和敏感信息处理。
- 置顶帖内容已经去掉模板占位文字或改成当前真实状态。
