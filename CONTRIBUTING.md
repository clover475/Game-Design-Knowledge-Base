# CONTRIBUTING

本知识库的贡献目标是：让资料可追踪、可复用、可被 AI 调用，而不是只把链接或文件堆进仓库。

## 新增资料流程

1. 把新资料放入 `00_inbox_pending/`，或先记录 URL。
2. 在 `resources_index.md` 新增一条 metadata 记录。
3. 判断资料类型：`book` / `paper` / `article` / `repo` / `gdd` / `postmortem` / `tool` / `visual_ref` / `prompt` / `project_note` / `open_source_project`。
4. 移入对应目录，或保留外链并写明没有本地文件。
5. 写一句“为什么值得收录”。
6. 如果是 A 级资料，创建 AI 阅读笔记。
7. 如果有可复用方法，拆成设计卡片。
8. 如果能服务项目，链接到 `06_project_use/` 对应项目。
9. 更新 `update_log.md`。

## 命名规范

- 文件名使用英文或拼音，避免过长。
- Markdown 文件统一使用 `.md`。
- 每个文件开头带 metadata。
- 推荐格式：
  - `book_the_art_of_game_design.md`
  - `paper_mda.md`
  - `mechanic_memory_overlap.md`
  - `level_spatial_loop.md`
  - `case_bioshock_gdd.md`
  - `prompt_book_to_design_cards.md`

## Metadata 必填字段

```yaml
---
title:
type:
topic:
source_url:
local_path:
added_by:
added_date:
status:
priority:
related_projects:
tags:
---
```

## 状态定义

- `inbox`: 已收集，未整理。
- `indexed`: 已进入总索引。
- `summarized`: 已生成 AI 阅读笔记。
- `carded`: 已拆成设计卡片。
- `applied`: 已用于具体项目。

## GitHub 提交建议

- 一次提交只做一类事情：新增资料、补笔记、补卡片、更新项目调用。
- 不提交大型原始文件，除非明确确认版权和仓库容量。
- 不确定版权的资料只记录书名、来源、购买/获取方式和自己的摘要。

