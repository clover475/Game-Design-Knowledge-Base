---
title: Memory Overlap
type: design_card
card_type: mechanic
topic: mechanics / narrative
source: MDA + project needs
added_by: codex
added_date: 2026-06-30
status: indexed
priority: A
related_projects: culture_narrative_future / ai_npc_rag
tags: [memory, choice, narrative_system]
---

# 一句话定义

玩家的新选择会覆盖、污染或重写旧记忆，从而改变可见线索、NPC 态度或路径。

# 适用场景

文化叙事、心理叙事、AI NPC 记忆系统、探索解谜。

# 玩家动作

收集记忆、选择保留或覆盖、向 NPC 讲述版本、回到旧地点验证变化。

# 系统规则

- 每个关键事件生成一条记忆记录。
- 记忆有可信度、来源、时间、情绪标签。
- 新记忆与旧记忆冲突时，触发覆盖、并存或分裂。

# 反馈方式

UI 文本变化、NPC 话术变化、场景物件错位、音效断裂、画面错帧。

# 开发需求

需要记忆数据结构、冲突检测、状态覆盖规则、存档字段、可视化调试面板。

# 风险

如果反馈不清晰，玩家会以为是 bug。必须明确哪些变化是系统设计。

# 可迁移到当前项目的方式

用于 AI NPC / RAG 系统时，可把资料来源、NPC 记忆和玩家输入统一成可检索知识记录。

