---
title: Memory Distortion Visual Effect
type: design_card
card_type: visual
topic: visual / technical_implementation
source: project needs
added_by: codex
added_date: 2026-06-30
status: indexed
priority: B
related_projects: culture_narrative_future
tags: [shader, distortion, glitch, memory]
---

# 一句话定义

用画面错帧、溶解、局部扭曲、颜色偏移表现记忆被修改或现实不稳定。

# 适用场景

记忆覆盖、时间回滚、隐藏路径出现、NPC 说法冲突、关键道具变化。

# 美术需求

- 需要正常状态、轻微异常、强异常三档视觉。
- 避免纯粹炫技，效果必须对应具体系统事件。
- 参考方向：旧照片褪色、CRT 错位、局部马赛克、年代材质残影。

# 开发需求

需要 shader 参数：强度、范围、持续时间、颜色偏移、遮罩区域、触发事件。

