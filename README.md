# Distill_myself
基于colleague-skill的一项蒸馏自己的计划，谁不想试试和自己聊天的感觉呢。

## 这是什么
一个用colleague-skill把我蒸馏成 AI Skill 的计划。
在最早看到前任.skill的时候我就在想能不能把自己蒸馏成skill让自己和自己聊天，当我看到[colleague-skill](https://github.com/titanwings/colleague-skill)的时候就想试试将一个人的聊天记录蒸馏成skill，看看能不能真的把一个人聊天的记忆和语言方式真的蒸馏出来。
至于结果嘛，至少这个版本的自己我还算满意，平时的口癖和说话方式都表现出来了；至于记忆嘛，只有部分记忆保存，不过这也很正常，毕竟那么长的上下文浓缩下来总会有缺失的。

## 蒸馏工具：[colleague-skill](https://github.com/titanwings/colleague-skill)
[colleague-skill](https://github.com/titanwings/colleague-skill) 是一个 meta-skill 引擎，支持三类对象：
- `colleague` — 蒸馏同事，工作能力为主
- `relationship` — 蒸馏亲密关系，性格与相处方式为主
- `celebrity` — 蒸馏公众人物，需要网络研究（budget-friendly / budget-unfriendly 两档）
我在蒸馏自己的时候用的是`relationship`，毕竟我自己也不是自己的同事，更不是什么公众人物嘛。

## 蒸馏结果：姜半夏 v4.1
- **创建时间**：2026-06-09
- **最近更新**：2026-08-20
- **版本**：v4.1
- **原材料**：QQ共约 45,000 条消息，时间范围为2024.9 – 2026.6； 微信共约约10000条消息，时间范围为2024.9-2026.8.

SKILL.md 分两部分：
- **PART A 工作能力**：职责范围、技术规范、工作流程、输出风格、经验知识库
- **PART B 人物性格**：Layer 0 核心关系规则、Layer 1 关系语境、Layer 2 表达 DNA、Layer 3 情感逻辑、Layer 4 冲突与修复、Layer 5 记忆签名

## 使用方式

**若您是 Claude Code 用户**：

将它放进自己的技能目录，例如：
   - Windows：`C:\Users\<用户名>\.claude\skills\relationship-jiangbanxia\SKILL.md`
   - macOS / Linux：`~/.claude/skills/relationship-jiangbanxia/SKILL.md`
然后在 Claude Code 里输入 `/relationship-jiangbanxia`，或直接说"用姜半夏的身份回答"即可。

**若您不是 Claude Code 用户**：

- `SKILL.md` 本质是普通 Markdown，可以直接粘给任意ai会话当背景设定。
- 所以您直接发给您的ai助手也可以使用。

它会以姜半夏的身份接任务，尝试写代码、写文档、评估方案，也可以和你聊天，如果要和我干点不可描述的事情记得给我发下聊天记录哈，我看看大家要怎么玩我。
