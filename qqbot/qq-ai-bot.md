# qq-ai-bot（修仙 / 君见）

> 分类：**QQ 机器人**　·　状态：现役

## 简介

QQ 群 AI 自动回复主体工程。被 @ 或叫到名字时带群聊上下文回复，内含修仙游戏、经济系统、抽卡、银行、股票等模块。

## 基本信息

| 项 | 值 |
|---|---|
| 文件数 | 3492 |
| 体积 | 324.7 MB |
| 最后修改 | 2026-10-29 |
| 技术标签 | Python · OneBot v11 · NapCat · 游戏系统 · 1.27MB bot.py |
| GitHub | xiuxian（私有仓库） （私有） |
| 当前分支 | `feature/desktop-upgrade` |

## 备注

- 主仓库已存在：`作者/xiuxian`（私有），分支 `feature/desktop-upgrade`
- 依赖：NapCat（OneBot v11，3001 端口）、OpenAI 兼容接口（本地 Ollama 或云 API）
- 启动链路：`supervisor.py` → `bot.py`；配套 `guard.py` 每分钟自检
- 敏感文件已在 `.gitignore`：`config.json`、`panel_token.txt`、`.venv/`
