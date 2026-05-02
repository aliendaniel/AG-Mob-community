# Moderation Runbook / 社区运营 Runbook

Use this guide for routine GitHub Issues, Discussions, pinned posts, and bilingual support.

## Bug Triage

1. Check whether the report includes device, app version, OS version, Gateway connection type, reproduction steps, expected result, and actual result.
2. If details are missing, ask for the missing information and keep the `triage` label.
3. If the report is reproducible or high impact, add relevant labels such as `bug`, `iPhone`, `iPad`, `gateway`, `needs-info`, or `known-issue`.
4. If the impact is broad, add it to the Known Issues pinned post.
5. After a fix ships, comment with the fixed version and close the issue.

## When To Move A Discussion To An Issue

- The post describes a reproducible bug.
- The user has clear steps, device details, and impact.
- Maintainers need to track fix status.

After creating the Issue, link it back from the original Discussion.

## When To Close As Duplicate

- Another Issue or Discussion already tracks the same problem.
- The new post does not add a new platform, reproduction path, or impact detail.

Close politely and link to the canonical thread.

## When To Answer In Q&A

- The user asks how to connect, scan setup code, approve a device, use chats, manage tasks, search, settings, permissions, offline recovery, or notifications.
- The topic does not require engineering fix tracking.
- Mark the clearest reply as the answer when resolved.

If the same question repeats often, update README, SUPPORT, or the Start Here pinned post.

## When To Escalate To Security Email

Immediately redirect to `aliendaniel@hotmail.com` when a post involves:

- Security vulnerability, permission bypass, data leakage, or abuse path
- Setup codes, device tokens, API keys, private logs, account data, or other sensitive information
- A public post that already exposed sensitive data

Public replies should stay minimal and avoid vulnerability details.

## Weekly Maintenance Checklist

- Review new Issues and add labels.
- Ask for missing bug details.
- Close duplicates with links.
- Review Q&A and mark accepted answers.
- Review Ideas and summarize recurring requests.
- Update Known Issues status.
- Publish or refresh Release Notes.
- Confirm public contact details and screenshots are still current.
- Check that important posts include English first and Chinese where useful.

---

## 中文摘要

- Bug：先检查设备、版本、系统、连接方式、复现步骤、期望结果和实际结果。
- Discussion 转 Issue：当问题可复现且需要跟踪修复状态时。
- 重复问题：关闭时贴出主线程链接。
- Q&A：用于连接、扫码、审批、会话、任务、搜索、设置、权限、离线恢复和通知等使用问题。
- 安全问题：立即引导到 `aliendaniel@hotmail.com`，公开回复不要讨论漏洞细节。
