# 项目协作角色

| 角色 | 谁 | 职责 |
|------|-----|------|
| 游戏策划 | Cursor 侧策划 Agent（与产品负责人对话） | 玩法、版本规划、规格真源、验收标准、数值与系统取舍裁决 |
| 开发 + 美术执行 | Codex（及美术流程） | 技术实现、客户端/服务端、IAP、中英进包、美术生产与接入、可运行构建 |

## 远程仓库

- 当前 origin：https://github.com/Klansure/pigeon-game（已推送 main）  
- 目标地址：https://github.com/sleep-go/pigeon-game（仓库已存在；需 Collaborator 写权限或 `sleep-go` 凭据后再改 remote 推送）  
- **每次开工前**：先 `git pull` 同步，阅读近期变更与文档，再开始策划或开发协作。

## 文档真源

- 总策划：`docs/superpowers/specs/2026-10-31-saige-game-gdd-by-version.md`
- V1.0 玩法：`docs/superpowers/specs/2026-10-31-saige-v1.0-gameplay-spec.md`
- Codex 开工契约：`docs/handoff/CODEX_V1.0_KICKOFF_PROMPT.md`

## 规则

- 实现服从规格；改玩法须策划改文档后再动代码。
- V1.0 范围闸门见开工提示词「明确禁止」。
- 代码注释与 Git 提交说明使用中文。
- 协同以 GitHub 为准，避免基于过期本地副本决策。
