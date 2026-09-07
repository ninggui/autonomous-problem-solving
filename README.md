# 自主问题解决

![GitHub stars](https://img.shields.io/github/stars/ninggui/autonomous-problem-solving)
![License](https://img.shields.io/github/license/ninggui/autonomous-problem-solving)
[![SkillHub](https://img.shields.io/badge/SkillHub-在线安装-blue)](https://skillhub.cn/skills/autonomous-problem-solving)

遭遇问题时先搜索再执行，失败后分析原因，只在确需用户介入时才回传。

## 这是什么

一个可复用的 AI Agent 技能（Skill），来自真实业务场景沉淀，含完整执行流程、避坑清单与验证步骤。

## 快速使用

将本仓库放入 Agent 技能目录后，用对应触发词调用（见 SKILL.md），Agent 会自动加载并执行完整流程。

## 核心能力

| 能力 | 说明 |
|------|------|
| 先搜索再执行 |
| 失败根因分析 |
| SkillHub 现成方案优先 |

## 使用方式（安装）

- **Hermes**: 放入 `skills/` 目录
- **Claude**: 放入 `~/.claude/skills/`
- **其他 Agent**: 按对应 SKILL.md 格式放入技能目录
- **SkillHub 一键安装**: https://skillhub.cn/skills/autonomous-problem-solving

## 优势

- 减少无谓的用户打扰
- 沉淀"失败→修复"经验闭环
- 适合夜间/无人值守任务

## 内容结构

- `SKILL.md` — 核心技能定义（触发条件、执行流程、避坑清单）
- `references/` — 可选参考文件

## 许可

MIT
