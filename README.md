# 君见项目库

本机全部项目的分类索引。每个项目一页，含简介、技术栈、体积、状态与仓库地址。

> 由本机目录扫描生成，最后更新：2026-10-29

## 分类总览

| 分类 | 项目 | 一句话 | 状态 |
|---|---|---|---|
| QQ 机器人 | [qq-ai-bot（修仙 / 君见）](qqbot/qq-ai-bot.md) | QQ 群 AI 自动回复主体工程。被 @ 或叫到名字时带群聊上下文回复，内含… | ✅ 现役 |
|  | [君见 二次开发整合包](qqbot/junjian-devkit.md) | 同一工程的导出快照（2026-10-28），附带 README_二次开发整合… | 📦 快照 |
|  | [君见 融合前备份](qqbot/junjian-backup.md) | 2026-10-24 合并前的完整备份，用于对照与回滚（bot.py 1.1… | 📦 快照 |
|  | [NapCat 部署](qqbot/napcat.md) | QQ NT 注入式 OneBot v11 服务端，当前账号 23658690… | 📄 文档/工具 |
| 客户端与 UI | [君见 App UI 重做交接（完整版）](ui/junjian-ui-handoff.md) | UI 整体重做的交接文档：接口清单、资源清单、指令清单、PWA/APK 约束… | 📄 文档/工具 |
|  | [君见 App UI 重做交接（精简版）](ui/junjian-ui-handoff-lite.md) | 上一份的轻量版本，只保留核心清单。… | 📄 文档/工具 |
| 本地服务与工具 | [Antigravity 本地 API 接入](tools/antigravity-api.md) | 把 Antigravity Tools 的本地 OpenAI/Anthrop… | 📄 文档/工具 |
|  | [Codex 线路修复](tools/codex-fix.md) | chatgpt.com 的 CONNECT 代理转发脚本（强制解析到可用 I… | 📄 文档/工具 |
|  | [微信自动回复](tools/wechat-autoreply.md) | 用 Python 驱动 PC 微信客户端，收到消息后按规则自动回复。… | 📄 文档/工具 |
|  | [课表提醒面板（新能源2603）](tools/timetable-reminder.md) | PowerShell WinForms 面板 + 计划任务：课表提醒、到点提… | 📄 文档/工具 |
| 方案存档 | [仙剑商店 · 基岩版方案](archive/xianjian-shop.md) | 把 51 条商店命令写进网易我的世界基岩版存档：用 .mcstructure… | 📄 文档/工具 |
|  | [Claude 记忆库](archive/claude-memory.md) | Claude Code 的长期记忆目录：偏好、环境、项目笔记、日志（已通过 … | 📄 文档/工具 |

## 目录结构

```
docs/
  qqbot/qq-ai-bot.md      qq-ai-bot（修仙 / 君见）
  qqbot/junjian-devkit.md      君见 二次开发整合包
  qqbot/junjian-backup.md      君见 融合前备份
  qqbot/napcat.md      NapCat 部署
  ui/junjian-ui-handoff.md      君见 App UI 重做交接（完整版）
  ui/junjian-ui-handoff-lite.md      君见 App UI 重做交接（精简版）
  tools/antigravity-api.md      Antigravity 本地 API 接入
  tools/codex-fix.md      Codex 线路修复
  tools/wechat-autoreply.md      微信自动回复
  tools/timetable-reminder.md      课表提醒面板（新能源2603）
  archive/xianjian-shop.md      仙剑商店 · 基岩版方案
  archive/claude-memory.md      Claude 记忆库
```

## 仓库一览

| 仓库 | 说明 |
|---|---|
| [junjian-project-hub](https://github.com/作者/junjian-project-hub) | 本目录站（私有） |
| [xiuxian](https://github.com/作者/xiuxian) | qq-ai-bot 主仓库（私有），本地历史在 `desktop-upgrade-20261029` 分支 |
| [junjian-devkit](https://github.com/作者/junjian-devkit) | 二次开发整合包快照 |
| [junjian-ui-handoff](https://github.com/作者/junjian-ui-handoff) | UI 重做交接（完整） |
| [junjian-ui-handoff-lite](https://github.com/作者/junjian-ui-handoff-lite) | UI 重做交接（精简） |
| [antigravity-api](https://github.com/作者/antigravity-api) | Antigravity 本地 API 接入 |
| [codex-fix](https://github.com/作者/codex-fix) | Codex TLS 修复脚本 |
| [wechat-autoreply](https://github.com/作者/wechat-autoreply) | 微信自动回复 |
| [xianjian-shop](https://github.com/作者/xianjian-shop) | 仙剑商店方案存档 |
