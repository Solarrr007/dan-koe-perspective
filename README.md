<div align="center">

# Dan Koe.skill

> *"You don't need a niche, you need a point of view."*

[![OpenAI Codex](https://img.shields.io/badge/OpenAI%20Codex-Skill-black)](https://openai.com/codex/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Research](https://img.shields.io/badge/Research-12%20Sources-blue)](#研究来源)
[![Dan Koe](https://img.shields.io/badge/Dan%20Koe-Creator%20OS-blueviolet)](#核心主题)
[![Runnable](https://img.shields.io/badge/Perspective-Runnable-orange)](#使用方式)
[![AgentSkills](https://img.shields.io/badge/AgentSkills-Standard-green)](https://agentskills.io/)

<br>

**把 Dan Koe 的写作、个人品牌、AI 杠杆和一人公司思维，蒸馏成一个可直接调用的 Codex Skill。**

<br>

不是语气模仿，也不是金句复读。<br>
这是一个基于公开资料调研、结构化提炼后的可运行视角 Skill。<br>
你可以直接用它来分析内容定位、个人品牌、一人公司和人生路径。

[安装](#安装方式) · [怎么用](#使用方式) · [包含什么](#这个-skill-包含什么) · [研究来源](#研究来源)

<br>

**其他语言 / Other Languages:** [English](README_EN.md)

</div>

---

`dan-koe-perspective` 是一个本地 Codex Skill。它把 Dan Koe 关于个人品牌、写作、AI 杠杆、一人公司、人生设计的核心判断方式，整理成一个能直接参与对话和分析的思维操作系统。

## 这是什么

`dan-koe-perspective` 是一个本地 Codex Skill，激活后会用 Dan Koe 的公开思想框架来回答问题，重点覆盖：

- 个人品牌与内容定位
- 写作与 point of view
- 一人公司与数字杠杆
- AI 工作流与 taste
- 人生路径、身份设计与长期成长

它更像一个“Dan Koe 视角的思维顾问”，而不是一个只会复读金句的聊天机器人。

## 适合谁

如果你在做这些事，这个 Skill 会很适合：

- 做内容，但不知道自己的差异化到底是什么
- 想做个人品牌或一人公司
- 想把写作、产品、AI 工具串成一个系统
- 对 Dan Koe 的框架有兴趣，但不想只学到表层表达
- 想用另一种视角重新审视职业、成长和自由度

## 这个 Skill 包含什么

这个仓库目前包含：

- 1 个可直接触发的主 Skill
- 5 个核心心智模型
- 8 条决策启发式
- Dan Koe 的表达 DNA
- 1 套回答工作流（Agentic Protocol）
- 6 份 research notes，方便继续迭代和审查

研究结构包括：

- `01-writings.md`：著作与长文
- `02-conversations.md`：播客与视频表达
- `03-expression-dna.md`：语言风格与表达模式
- `04-external-views.md`：外部评价与争议
- `05-decisions.md`：关键决策与转向
- `06-timeline.md`：人物时间线与最新动态

## 它和普通“角色扮演”有什么不同

很多人物类 AI 项目，最后做成的是“语气模仿器”。

这个项目更关心的是：

- Dan Koe 是怎么判断问题的
- 他会优先看什么变量
- 他怎样把身份、写作、产品、AI、人生设计串起来
- 他在哪些问题上会很笃定，在哪些问题上应该保留边界

换句话说，这个 Skill 的目标不是复述 Dan Koe 说过的话，而是尽可能还原他会如何分析一个问题。

## 核心主题

这个 Skill 重点提炼了 Dan Koe 的这些母题：

- Point of view 比 niche 更重要
- 默认人生脚本需要被主动打破
- Specialized generalism 比静态专长更有未来
- Productize your mind，而不是只卖时间
- AI 会压低生产门槛，但 taste 仍然稀缺

## 安装方式

把这个仓库放到你的 Codex skills 目录下：

```powershell
Copy-Item -Recurse .\dan-koe-perspective C:\Users\<YourUser>\.codex\skills\
```

或者直接克隆到：

```text
~/.codex/skills/dan-koe-perspective
```

然后重启 Codex，让 Skill 被重新加载。

## 使用方式

安装并重启后，可以直接这样触发：

```text
用 Dan Koe 的视角帮我分析我的内容定位
Dan Koe 会怎么看我的一人公司路线
我兴趣很多，怎么像 Dan Koe 说的那样把自己变成 niche
Dan Koe 会怎么判断 AI 应该帮我做什么
切换到 Dan Koe 模式，帮我拆一下个人品牌策略
```

## 示例问题

你可以拿这些问题测试效果：

- “我做了很多内容，但始终没有辨识度，问题出在哪？”
- “如果我想做个人品牌，应该先做内容还是先做产品？”
- “我到底该继续上班，还是开始尝试一人公司？”
- “AI 时代里，什么能力还值得自己慢慢练？”
- “我写了很多，但没有形成自己的 point of view，怎么办？”

## 仓库结构

```text
dan-koe-perspective/
├── README.md
├── README_EN.md
├── SKILL.md
├── agents/
│   └── openai.yaml
└── references/
    └── research/
        ├── 01-writings.md
        ├── 02-conversations.md
        ├── 03-expression-dna.md
        ├── 04-external-views.md
        ├── 05-decisions.md
        └── 06-timeline.md
```

## 研究来源

主要基于这些公开来源提炼：

- Dan Koe 官网
- Dan Koe 的文章与 newsletter
- The Koe Cast
- 公开视频与转录
- LinkedIn 长文
- Eden 相关公开页面
- 外部观察与评论文章

完整来源清单可见 [SKILL.md](./SKILL.md) 和 `references/research/`。

## 为什么做这个项目

很多人学 Dan Koe，最后学到的是几句很好传播的话。

比如：

- “You don’t need a niche, you need a point of view.”
- “Productize your mind.”
- “Taste is the new intelligence.”

但真正有价值的，不是把这些话记住，而是把这些话背后的判断结构提炼出来。

这个项目想做的，就是把 Dan Koe 的“思维方式”做成一个可反复调用的本地 Skill。

## 局限性

这个项目有几个明确边界：

- 它基于公开资料提炼，不代表 Dan Koe 本人
- 它更适合作为思维辅助，不适合作为绝对权威
- 它擅长创作者商业、写作、AI 杠杆和人生设计，不替代行业专家判断
- 对实时事实问题，仍然应该优先查最新信息

## License

建议你根据最终上传方式自行补充许可证。

如果你希望别人自由修改和分发，MIT 是一个简单直接的选择。

## Credits

- Dan Koe：公开思想来源
- Nuwa-style distillation workflow：人物视角提炼方法参考
- Codex：Skill 结构化生成与实现
