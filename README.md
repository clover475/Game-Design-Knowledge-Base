# Game Design Knowledge Base

这是一个用于学习、协作和 AI 调用的游戏设计知识库。它既是本地 Obsidian Vault，也是 GitHub 协作仓库。目标不是收藏资料，而是把资料转化为可检索、可复用、可服务项目的游戏设计系统。

## 适用目标

- 从零学习游戏设计、机制设计、关卡设计、叙事设计、视觉设计和游戏开发基础。
- 与学习搭子共同维护资料、笔记、设计卡片、案例拆解和 prompt。
- 在和 AI 对话时快速提供高质量上下文。
- 支持文化叙事类游戏、探索类游戏、线上线下联动游戏、AI NPC / RAG 游戏内容系统的策划与实现。

## 目录结构

```text
00_inbox_pending/                 临时收集区，所有未整理资料先放这里
01_raw_sources/                   原始资料区：书籍、论文、网页、GDD、postmortem、视觉参考、开源项目
02_indexes/                       场景索引和专题索引
03_ai_reading_notes/              AI 阅读笔记
04_design_cards/                  可复用设计卡片
05_case_studies/                  GDD、postmortem、开源项目、成熟游戏案例拆解
06_project_use/                   当前和未来项目的调用区
07_prompts/                       Prompt 模板
08_collaboration/                 协作规则、标签系统、review queue
09_learning_paths/                学习路径
resources_index.md                全局资料总表
priority_reading_list.md          优先阅读路线
CONTRIBUTING.md                   贡献流程
update_log.md                     更新记录
metadata_template.md              Metadata 模板
review_queue.md                   待判断事项
```

## AI 如何使用这个知识库

- 快速问答：读取 `resources_index.md`，再读取相关 `03_ai_reading_notes/` 笔记。
- 设计机制：读取 `04_design_cards/mechanics/` 和 `02_indexes/index_by_use_case.md` 中的机制条目。
- 设计关卡：读取 `04_design_cards/level_design/`、`03_ai_reading_notes/level_design/`。
- 写剧情或任务：读取 `04_design_cards/narrative/`、`03_ai_reading_notes/narrative/`。
- 给美术提需求：读取 `01_raw_sources/visual_refs/` 索引、`04_design_cards/visual/`。
- 给开发提需求：读取 `03_ai_reading_notes/development/`、`04_design_cards/technical/`。
- 做具体项目：读取 `06_project_use/对应项目/context_pack.md`，再补充相关设计卡片和 prompt。
- 做 AI NPC / RAG：读取 `06_project_use/对应项目/AI_NPC_RAG_system.md` 和 `03_ai_reading_notes/ai_npc_rag/`。

## 推荐工作流

1. 新资料先放入 `00_inbox_pending/`。
2. 在 `resources_index.md` 新增一条记录。
3. 判断资料类型与主题分类，移动到 `01_raw_sources/` 对应目录或只保留外链。
4. 重要资料生成 AI 阅读笔记。
5. 可复用方法拆成设计卡片。
6. 与项目相关的内容链接到 `06_project_use/`。
7. 大整理后更新 `update_log.md`。

## GitHub 协作方式

- Markdown 笔记、索引、设计卡片、prompt、项目调用文档应该同步到 GitHub。
- 大型 PDF、EPUB、视频、图片素材默认不提交，只在 `resources_index.md` 记录来源链接或本地路径。
- 两人协作时，建议每次新增资料都单独提交，commit message 写清楚资料类型和主题，例如 `add mda reading note`。
- 不确定分类时，先保留在 `00_inbox_pending/`，并在 `review_queue.md` 记录问题。

## 第一周学习路径

见 `priority_reading_list.md` 和 `09_learning_paths/week_01_path.md`。

