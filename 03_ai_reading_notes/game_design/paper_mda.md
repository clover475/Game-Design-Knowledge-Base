---
title: MDA - Mechanics, Dynamics, Aesthetics
type: reading_note
topic: game_design / mechanics
source_url: https://users.cs.northwestern.edu/~hunicke/MDA.pdf
local_path: 03_ai_reading_notes/game_design/paper_mda.md
added_by: codex
added_date: 2026-06-30
status: indexed
priority: A
related_projects: all
tags: [mda, mechanics, dynamics, aesthetics, framework]
---

# 这份资料讲什么

MDA 是一个游戏设计和分析框架，把游戏拆成 Mechanics、Dynamics、Aesthetics 三层：设计者从机制出发，玩家从体验出发。它适合用来检查“我设计的规则是否真的导向我想要的玩家体验”。

# 对游戏策划初学者最重要的概念

- Mechanics：规则、数据、算法、操作、资源、系统约束。
- Dynamics：玩家与系统互动后产生的行为模式。
- Aesthetics：玩家实际获得的情感和体验，例如探索、挑战、表达、幻想、社交、发现。

# 如何转化成玩家动作

先写玩家能做什么，再问这些动作是否会产生目标体验。例如“收集碎片、交换线索、解锁路径”可以导向探索、发现和选择压力。

# 如何转化成游戏机制

用目标体验反推机制：想要“记忆被覆盖的不安感”，可以设计记忆槽、覆盖规则、回溯限制、冲突线索和不可逆选择。

# 如何转化成关卡设计

关卡要承载动态：路径分叉、门槛、锁钥、回环、视线遮挡、空间记忆点，都应该服务玩家行为模式。

# 如何转化成叙事设计

叙事不是只写剧情，而是让机制制造叙事动态。例如选择、后果、隐藏信息和延迟反馈可以让玩家自己生成故事。

# 如何转化成美术需求

美术需求应服务体验目标：如果目标是荒诞和记忆错位，视觉可以使用错帧、局部溶解、重复空间、年代物件错置。

# 如何转化成开发需求

开发需求应写清规则、状态、触发条件、反馈、失败条件和可调参数。

# 对文化叙事类游戏有什么启发

文化资料不要只作为图鉴，而要变成玩家动作和系统反馈。例如“文物碎片”可以变成收集、修复、误读、交换、献祭、解锁路线的机制。

# 可用于当前项目的地方

- 犍陀罗文化游戏：把文化知识转成探索、修复、路径解锁和 NPC 解释冲突。
- 高考后人生模拟器：把选择和后果系统化，形成多结局动态。
- AI NPC / RAG 系统：用资料检索支撑 NPC 的知识、记忆和反馈。

