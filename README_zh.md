# Human Knowledge Foundation Project (人类知识地基计划)

[English](README.md) | 简体中文

[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

## 项目简介 (Introduction)

欢迎来到**人类知识地基计划**。

这个项目真正的源头，是一场关于「**智能的本质**」的、长达十余万字的极限思辨。而你现在看到的「人类知识地基计划」，是这场思辨推演到尽头后，自然落地的第一个工程产物。**「智能的本质」是内核与源头，「人类知识地基计划」是它结出的果实。**

> **🧭 建议从这一篇开始读：[《项目缘起：从「智能的本质」到「人类知识地基」》](docs/philosophical_background/00_项目缘起_从智能的本质到知识地基.md)**
>
> 它把这个项目的来龙去脉讲透：智能为什么是「效率」、知识为什么是一座建在「隐含假设」地基上的大厦、以及为什么"系统性地挖掘这些地基"会成为一件必然要做的事。**先读懂这条源头，再看后面的工程与数据，才是理解这个项目的正确方式。**

那么，落到工程上，这个项目具体在做什么？

本项目致力于利用人工智能技术，系统化、工程化地梳理支撑全人类自然科学与数学知识大厦的“基本假设”和“隐含假设”，探索科学发现的新范式——从“天才的偶然探险”转向“AI 辅助的系统化采矿”，最终把隐性的前置知识变成一张可计算、可验证的原子概念网络。

> **⚠️ 读者指南：淘金者心态**  
> 本项目的思想源头，是一场带有个人探索色彩的直觉思辨，就像是科学正规军到来前派出的“前哨小分队”，难免存在不够严密之处。
> 因此，无论是阅读思想起源，还是参与未来的采矿工作，我们都倡导一种**“淘金者心态”**——不要抱着阅读教科书般严苛的心态来求全责备，而应像在杂物堆中翻找发光物品一样，敏锐地捕捉那些有价值的认知火花，并用科学工程的方法将其提纯验证。

## 思想内核一览：智能的本质（One-Paragraph Why）

如果只用一段话概括「项目缘起」的逻辑链条，它是这样一条线：

> **智能的本质是「效率」**（在资源受限下构建并利用模型）→ **知识是一座建在 L0–L4「隐含假设」地基上的大厦** → **科学革命的本质，是地基出现裂缝时的「冲突驱动、地基重构」** → **而「理解」的本质，就是把耦合在一起的现象「解耦」成独立的变量与前提** → **所以，系统性地逆向挖掘、解耦人类知识的隐含假设，就等于把"科学发现"从偶然的天才探险，改造成可工程化的「地基采矿」。**

这条链子的完整展开，见 [《项目缘起》](docs/philosophical_background/00_项目缘起_从智能的本质到知识地基.md) 与整个 [`docs/philosophical_background/`](docs/philosophical_background/README.md) 目录。

## 目录结构 (Repository Structure)

```text
human-knowledge-foundation/
├── README.md                  # 项目主页与导航 (英文版)
├── README_zh.md               # 项目主页与导航 (中文版)
├── WHITEPAPER_FRAMEWORK.md    # 项目白皮书框架 (英文版)
├── WHITEPAPER_FRAMEWORK_zh.md # 项目白皮书框架 (中文版)
├── RECRUITMENT.md             # 寻人启事与招募文案 (英文版)
├── RECRUITMENT_zh.md          # 寻人启事与招募文案 (中文版)
├── SPONSORSHIP_PROPOSAL.md    # 开放研究赞助说明 (英文版)
├── SPONSORSHIP_PROPOSAL_zh.md # 开放研究赞助说明 (中文版)
├── LICENSE                    # 开源协议 (建议采用 CC BY-SA 4.0)
├── CONTRIBUTING.md            # 贡献指南 (WIP)
├── CODE_OF_CONDUCT.md         # 社区行为准则 (WIP)
│
├── docs/                      # 核心理论与文档
│   ├── philosophical_background/ # 【项目内核】智能的本质 —— 一切的源头
│   │   ├── README.md                                  # 内核导览（建议从这里进）
│   │   ├── 00_项目缘起_从智能的本质到知识地基.md        # 把“为什么要做”讲透
│   │   ├── 01_智能的本质_最终精要.md                   # 十余万字思辨的结晶
│   │   ├── 02_理解的新定义_解耦与因果.md               # 理解=解耦（最新拼图）
│   │   └── 03_体验是价值权重_痛苦快乐不是玄学.md         # 体验也不是玄学
│   ├── methodology/           # 方法论：探针系统、假设分层、证据闸门
│   ├── similar_projects.md    # 类似项目与学术前沿（如 PIEVO）梳理
│   └── taxonomy/              # 知识大类与概念分类法
│
├── data/                      # 核心数据产出区
│   ├── L0_sensory_instincts/  # L0级：感官与本能假设
│   ├── L1_basic_logic/        # L1级：基础逻辑假设
│   ├── L2_mathematics/        # L2级：数学公理体系
│   ├── L3_natural_sciences/   # L3级：自然科学隐含假设 (分物理、化学等)
│   │   └── physics/
│   │       └── KFA-L3-PHYS-001_牛顿第一定律.md # 首张假设卡片样例
│   │
│   └── templates/             # 假设卡片模板与规范
│
├── scripts/                   # 自动化工具链
│   ├── extraction_agents/     # 用于多模型并发提问和提取的 Agent 脚本
│   └── validation_tools/      # 格式校验与逻辑回查工具
│
└── community/                 # 社区互动与记录
    ├── meeting_notes/         # 讨论与会议记录
    └── contributors.md        # 贡献者致谢名单
```

## 核心理念 (Core Philosophy)

* **客观祛魅**：采用多厂商大模型（Multi-LLM）客观辩论机制，剥离人类中心主义与单一模型的偏差。
* **假设即基石**：所有复杂的知识大厦皆建立在不可证的公理和隐含假设之上。找到假设，即找到范式跃迁的钥匙。
* **开源共建**：相信群体智慧与机器智能的结合，让最坚固的地基开放给所有人审阅。

## 快速开始 (Getting Started)

1. **先读内核**：从 [《项目缘起：从「智能的本质」到「人类知识地基」》](docs/philosophical_background/00_项目缘起_从智能的本质到知识地基.md) 开始，理解这个项目"为什么必然会出现"。这是真正决定你如何判断它价值的一篇。
2. 阅读 [白皮书框架 (WHITEPAPER_FRAMEWORK_zh.md)](WHITEPAPER_FRAMEWORK_zh.md) 了解项目的全景图和方法论。
3. 查阅 [招募文案 (RECRUITMENT_zh.md)](RECRUITMENT_zh.md) 查看你能如何贡献力量。
4. Fork 本仓库，开始你的第一张“假设卡片”提取！

## 参与贡献 (Contributing)

我们极度欢迎所有的思想者、程序员和领域专家加入！无论是提交 Issue 讨论理论、完善自动化脚本，还是协助审查某条物理假设的严谨性，你的每一次提交都在加固人类知识的地基。

（详细的贡献流程文档即将上线，敬请期待。）
