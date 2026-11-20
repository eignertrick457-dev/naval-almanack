# naval-almanack

> 把《纳瓦尔宝典》蒸馏成 AI Agent Skill：财富、职业、副业、学习与人生决策的可执行判断清单。

## 这是什么

一个将纳瓦尔·拉维坎特（Naval Ravikant）关于财富与幸福的核心思维模型——寻求财富而非金钱或地位、专长 × 责任 × 杠杆、无需许可的杠杆、玩长期游戏、判断力优先于勤奋、幸福是可习得的技能——提炼为可执行判断清单的 Agent Skill。

**边界说明：**本 Skill 处理的是"人生结构层"决策，不处理交易下单、择时、仓位等"执行层"交易问题——后者请使用交易规则类 Skill（如 livermore-trading-rules）。

## 模块速览

| 模块 | 条目 | 用途 |
|------|------|------|
| 核心原则 | 9 条 | 底层世界观：资产 vs 出卖时间、四种杠杆、专长、判断力、长期游戏 |
| 财富创造判断清单 | 9 项过检 | 评估一个赚钱想法 / 项目 / 机会 |
| 职业与副业决策清单 | 四问 + 五检 + 退出信号 | 评估职业去留、副业是否启动 |
| 学习与阅读原则 | 7 条 | 配置学习时间与读书方式 |
| 幸福核心框架 | 8 条 | 欲望管理、健康优先级、当下、环境设计 |
| 反模式 | 10 条表格 | 纳瓦尔最反对的做法，命中即否决 |
| 适用边界 | — | 明确适用场景与拒绝接单的交易执行类问题 |

## 安装使用

**方式一：Agent Skills 目录**（适用于 Claude Code 等支持 skills 约定的框架）

```bash
git clone https://github.com/eignertrick457-dev/naval-almanack.git
mkdir -p ~/.claude/skills
cp -r naval-almanack ~/.claude/skills/
```

**方式二：**任意支持 SKILL.md frontmatter 的 Agent 框架——将本目录放入技能根目录，Agent 按 frontmatter 的 name + description 自动触发。

**方式三：**当规则文件直接使用——把 SKILL.md 全文粘贴为系统提示词 / 项目规则（如 .cursorrules、AGENTS.md 引用内容），适用于任何 LLM。

触发示例：用户问"要不要辞职做自媒体""这个副业值得做吗""该学什么技能""如何不做一辈子打工人""最近很焦虑怎么调整"时，Agent 自动加载本 Skill 并按模块输出对照结论。

## 来源

书籍：《纳瓦尔宝典：财富与幸福指南》（The Almanack of Naval Ravikant），埃里克·乔根森（Eric Jorgenson）整理，集结 Naval Ravikant 的推文、访谈与播客言论；原书有官方免费电子版（nav.almanack / "The Almanack of Naval Ravikant" 官网下载）。

本仓库为方法论改写提炼，无原文摘录；数值类内容（如副业零收入期 6–24 个月、转型窗口 3–12 个月）为经验默认值，需按个人情况校准。

## 免责声明

本 Skill 仅作决策框架参考，不构成投资、职业或心理专业建议。

> AI生成
