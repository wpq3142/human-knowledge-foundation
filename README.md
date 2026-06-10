# Human Knowledge Foundation Project (人类知识地基计划)

English | [简体中文](README_zh.md)

[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

## Introduction

Welcome to the **Human Knowledge Foundation Project**.

The true source of this project is a months-long, 100,000+ word intellectual marathon on **"The Nature of Intelligence."** The "Human Knowledge Foundation Project" you see here is the first engineering product that naturally landed once that inquiry was pushed to its conclusion. **"The Nature of Intelligence" is the core and the source; the "Human Knowledge Foundation Project" is the fruit it bears.**

> **🧭 Start here: [Origin Story: From "The Nature of Intelligence" to "The Human Knowledge Foundation"](docs/philosophical_background/00_项目缘起_从智能的本质到知识地基.md)** (currently in Chinese)
>
> It lays out the full context: why intelligence is "efficiency," why knowledge is an edifice built on a foundation of "implicit assumptions," and why "systematically mining those foundations" becomes something that *had* to be done. **Reading this source first, then the engineering and data that follow, is the right way to understand this project.**

So, on the engineering level, what does this project actually do?

This project is dedicated to utilizing artificial intelligence to systematically and programmatically map the "fundamental assumptions" and "implicit assumptions" that support the grand edifice of human scientific and mathematical knowledge—exploring a new paradigm of scientific discovery: shifting from "accidental exploration by geniuses" to "systematic mining assisted by AI," and ultimately transforming implicit pre-existing knowledge into a computable, verifiable network of atomic concepts.

> **⚠️ Reader's Guide: A Gold-Miner's Mindset**  
> The intellectual source of this project is a deeply intuitive, personal exploration—like a "scout squad" sent out before the regular scientific army arrives; it inevitably contains areas that are not fully rigorous.  
> Therefore, whether reading the philosophical origins or participating in future mining work, we advocate a **"gold-miner's mindset"**—do not read this with the strict expectations of a textbook. Instead, act like a miner searching for glowing objects in a pile of rubble, keenly capturing those valuable sparks of cognition, and then refining and validating them using scientific engineering methods.

## The Intellectual Core at a Glance (One-Paragraph Why)

If we compress the logical chain of the "Origin Story" into a single line:

> **The essence of intelligence is "efficiency"** (building and using models under resource constraints) → **knowledge is an edifice built on a foundation of L0–L4 "implicit assumptions"** → **the essence of a scientific revolution is "conflict-driven reconstruction" when the foundation cracks** → **and the essence of "understanding" is "decoupling" coupled phenomena into independent variables and premises** → **therefore, systematically reverse-engineering and decoupling the implicit assumptions of human knowledge turns "scientific discovery" from an accidental stroke of genius into an engineerable "foundation mining" operation.**

The full unfolding of this chain lives in the [Origin Story](docs/philosophical_background/00_项目缘起_从智能的本质到知识地基.md) and the entire [`docs/philosophical_background/`](docs/philosophical_background/README.md) directory.

## Repository Structure

```text
human-knowledge-foundation/
├── README.md                  # Project homepage & navigation (English)
├── README_zh.md               # Project homepage & navigation (Chinese)
├── WHITEPAPER_FRAMEWORK.md    # Whitepaper framework (English)
├── WHITEPAPER_FRAMEWORK_zh.md # Whitepaper framework (Chinese)
├── RECRUITMENT.md             # Recruitment notice (English)
├── RECRUITMENT_zh.md          # Recruitment notice (Chinese)
├── SPONSORSHIP_PROPOSAL.md    # Sponsorship proposal (English)
├── SPONSORSHIP_PROPOSAL_zh.md # Sponsorship proposal (Chinese)
├── LICENSE                    # Open-source license (CC BY-SA 4.0)
├── CONTRIBUTING.md            # Contribution guidelines (WIP)
├── CODE_OF_CONDUCT.md         # Community code of conduct (WIP)
│
├── docs/                      # Core theory & documentation
│   ├── philosophical_background/ # [THE CORE] The Nature of Intelligence — the source of it all
│   │   ├── README.md                                  # Core reading guide (start here)
│   │   ├── 00_项目缘起_从智能的本质到知识地基.md        # Origin story: the "why" (ZH)
│   │   ├── 01_智能的本质_最终精要.md                   # The full synthesis (ZH)
│   │   ├── 02_理解的新定义_解耦与因果.md               # Understanding = decoupling (ZH)
│   │   └── 03_体验是价值权重_痛苦快乐不是玄学.md         # Experience is not mysticism (ZH)
│   ├── methodology/           # Methodology: probe systems, assumption layers, evidence gates
│   ├── similar_projects.md    # Analysis of similar projects & frontiers (e.g., PIEVO)
│   └── taxonomy/              # Domain taxonomy & concept classification
│
├── data/                      # Core data output area
│   ├── L0_sensory_instincts/  # Level 0: Sensory & instinct assumptions
│   ├── L1_basic_logic/        # Level 1: Basic logical assumptions
│   ├── L2_mathematics/        # Level 2: Mathematical axiom systems
│   ├── L3_natural_sciences/   # Level 3: Natural science implicit assumptions (Physics, Chemistry, etc.)
│   │   └── physics/
│   │       └── KFA-L3-PHYS-001_牛顿第一定律.md # First assumption card sample (ZH)
│   │
│   └── templates/             # Templates & specifications for assumption cards
│
├── scripts/                   # Automation toolchain
│   ├── extraction_agents/     # Agent scripts for multi-LLM concurrent extraction
│   └── validation_tools/      # Format validation & logical check tools
│
└── community/                 # Community interaction & records
    ├── meeting_notes/         # Discussion & meeting notes
    └── contributors.md        # Contributor acknowledgment list
```

## Core Philosophy

* **Objective Demystification**: Utilizing a multi-vendor LLM (Multi-LLM) objective debate mechanism to strip away anthropocentrism and single-model biases.
* **Assumptions as Bedrocks**: All complex edifices of knowledge are built on unprovable axioms and implicit assumptions. Finding these assumptions is the key to paradigm shifts.
* **Open-Source Collaboration**: Believing in the power of combining collective human wisdom with machine intelligence, making the most solid foundations of knowledge open for everyone to review.

## Getting Started

1. **Read the core first**: Start with the [`docs/philosophical_background/`](docs/philosophical_background/README.md) directory to understand *why this project was bound to emerge*. This is what truly determines how you judge its value. (Core essays are currently in Chinese.)
2. Read the [Whitepaper Framework (WHITEPAPER_FRAMEWORK.md)](WHITEPAPER_FRAMEWORK.md) to understand the full picture and methodology of the project.
3. Check the [Recruitment Notice (RECRUITMENT.md)](RECRUITMENT.md) to see how you can contribute.
4. Fork this repository and start extracting your first "Assumption Card"!

## Contributing

We warmly welcome all thinkers, programmers, and domain experts to join us! Whether submitting an issue to discuss theory, refining automation scripts, or helping review the rigor of a physical assumption, every contribution you make strengthens the foundation of human knowledge.

*(Detailed contribution guidelines will be available soon.)*
