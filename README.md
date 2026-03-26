# openclaw-workspace

这是大钧哥在 OpenClaw 里的工作区仓库，用来保存身份设定、用户偏好、记忆文件和日常维护记录。

## 主要文件

- `IDENTITY.md`：助手的身份设定
- `USER.md`：用户信息与偏好
- `MEMORY.md`：长期记忆
- `MEMORY_RULES.md`：记忆维护规则
- `memory/YYYY-MM-DD.md`：每日记录
- `SOUL.md`：助手的行为风格与原则
- `AGENTS.md`：工作区约定
- `TOOLS.md`：本地工具和环境备注
- `HEARTBEAT.md`：心跳检查说明

## 用途

这个仓库主要用于：

- 记录大钧哥的长期与短期记忆
- 保存和追踪工作区内的重要变更
- 让配置、习惯和文档可以通过 GitHub 留档

## Git 说明

当前仓库已连接到 GitHub，并在运行中的 OpenClaw Docker 环境内配置了 Git 凭证缓存，因此后续常规提交与推送可以由助手直接完成。

## 隐私提醒

仓库中不应提交敏感运行时数据、凭证或本地缓存。
目前 `.gitignore` 已忽略常见本地文件，例如：

- `.openclaw/`
- `.env`
- `*.log`
- `node_modules/`

如果后续增加了新的敏感文件，也应及时加入 `.gitignore`。
