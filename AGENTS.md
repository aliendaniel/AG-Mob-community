# AGENTS.md

## Repository Purpose

This repository is the public community and support hub for AG Mob, the independent iPhone/iPad companion app for a user-owned OpenClaw Gateway.

AG Mob is developed and published by Chengling Hua as an independent individual developer. It is not affiliated with, endorsed by, or published by the OpenClaw project or its maintainers. Public docs must keep that relationship clear whenever OpenClaw compatibility is discussed.

This repository is not the private app source-code repository. Do not add mobile app source code, build files, signing assets, private roadmap details, setup codes, device tokens, production credentials, API keys, or internal service references here.

## Language Policy

- Default public docs should be English first.
- Chinese support must remain available through `docs/zh-CN/README.md` and bilingual helper text where useful.
- Keep public copy professional, concise, and friendly.
- Do not invent real URLs, emails, company names, or support commitments. If a public link is not ready, omit it until the real value is available.

## File Map

- Homepage: `README.md`
- Chinese homepage: `docs/zh-CN/README.md`
- Brand and screenshots: `docs/assets/`
- Issue forms: `.github/ISSUE_TEMPLATE/`
- Discussion category forms: `.github/DISCUSSION_TEMPLATE/`
- Pinned discussion seed drafts: `docs/community/seed-posts/`
- Moderation workflow: `docs/community/moderation-runbook.md`
- Manual GitHub UI checklist: `docs/community/manual-next-steps.md`

## Community Routing Rules

- Bug / reproducible failure -> GitHub Issues.
- Usage question / how-to -> Discussions / `Q&A`.
- Feature idea -> Discussions / `Ideas`.
- General community conversation -> Discussions / `General`.
- Release updates and product notices -> Discussions / `Announcements`.
- Casual chat / real-time help -> Discussions / `General` unless a public real-time channel is added later.
- Security or privacy vulnerability -> private email: `aliendaniel@hotmail.com`. Never public Issue or Discussion.

Chinese equivalents:

- Bug / 可复现故障：提交到 GitHub Issues。
- 使用问题：发到 Discussions 的 `Q&A` 分类。
- 功能想法：发到 Discussions 的 `Ideas` 分类。
- 普通交流：发到 Discussions 的 `General` 分类。
- 安全或隐私问题：只通过 `aliendaniel@hotmail.com` 私下报告。

## Updating Screenshots

Use real product screenshots from review or release builds when available. Store public-safe images in `docs/assets/screenshots/` with descriptive filenames. Do not include screenshots that expose private credentials, setup codes, user data, internal URLs that should not be public, or unreleased confidential features.

## Updating Release Notes

1. Use `docs/community/seed-posts/release-notes.md` as the structure.
2. Write for end users, not engineers.
3. Mention new features, improvements, fixes, and known issues.
4. Publish the final text in Discussions / `Announcements`.
5. Mirror important user-facing notes in both English and Chinese when possible.

## Updating Known Issues

1. Use `docs/community/seed-posts/known-issues.md`.
2. Include affected version, platform, impact, workaround, and fix status.
3. Avoid promising dates unless they are confirmed.
4. Link fixed issues back to release notes.

## Handling Feedback

1. Search existing Issues and Discussions before creating duplicates.
2. Ask for missing reproduction details before closing a bug as incomplete.
3. Move clear feature ideas to Discussions / `Ideas`.
4. Escalate security, privacy, account, payment, token, or credential issues to private email immediately.
