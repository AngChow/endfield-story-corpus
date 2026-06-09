# 明日方舟：终末地 剧情文本资料库

[![License](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](#许可与来源)
[![Source](https://img.shields.io/badge/Source-Warfarin%20Wiki-blue.svg)](https://warfarin.wiki/cn)

《明日方舟：终末地》简体中文剧情文本的本地化资料库，从 [Warfarin Wiki](https://warfarin.wiki/cn) 采集整理。共收录 **868 篇** Markdown 文档，覆盖任务剧本、Baker 会话、干员档案、武器描述、中枢档案、见闻辑录六大类内容，外加自行整理的世界观分析。

> 本库同时是一个 **Claude Code / CodeX Skill**——安装到 `~/.claude/skills/` 或 `~/.codex/skills/` 后，Claude Code / CodeX 会在你讨论终末地相关剧情时自动调用本库检索。所有文本来源于 Warfarin Wiki，版权归原作者及鹰角网络所有。

## 作为 Claude Code / CodeX Skill 安装

```bash
git clone https://github.com/AngChow/endfield-story-corpus.git \
  ~/.claude/skills/endfield-story-corpus      # Claude Code
  # 或
  ~/.codex/skills/endfield-story-corpus        # CodeX
```

Claude Code / CodeX 启动时会自动识别 `SKILL.md`，无需额外配置。之后在对话中讨论终末地剧情、角色、世界观、特定章节时，Claude Code / CodeX 会自动按"条目索引 → 分类目录 → 原文"的顺序检索本库并引用。

## 数据规模

| 分类 | 数量 | 说明 |
|---|---:|---|
| 任务 | 221 篇 | 主线 & 支线任务剧本，按游戏章节编号（e1m1、c27m3 等） |
| Baker | 104 篇 | Baker 会话全分支文本 |
| 干员 | 26 篇 | 干员情报、档案、语音记录 |
| 武器 | 67 篇 | 武器概览与描述 |
| 中枢档案 | 61 篇 | 世界观设定文档 |
| 见闻辑录 | 377 篇 | 见闻辑录正文 |
| 分析 | 7 篇 | 自行整理的时间线、势力关系、核心概念分析 |

数据版本：**1.2**（Warfarin 站点最后更新 `2026-04-17`）

## 目录结构

```
endfield-story-corpus/
├── SKILL.md            # Claude Code / CodeX Skill 定义（触发条件 + 检索工作流）
├── README.md           # 本文件
├── 任务/              # 主线 & 支线任务剧本
├── Baker/             # Baker 会话全分支
├── 干员/              # 干员情报、档案、语音
├── 武器/              # 武器概览与描述
├── 中枢档案/          # 世界观设定文档
├── 见闻辑录/          # 见闻辑录正文
├── 分析/              # 世界观考据分析（时间线、势力关系、核心概念 7 篇）
├── _条目索引.md        # 所有条目的导航入口（推荐检索入口）
└── _来源与采集.md      # 数据来源与采集结果
```

## 使用方式

- **作为 AI Skill**（推荐）：按上文方式 clone 到 `~/.claude/skills/` 或 `~/.codex/skills/`，Claude Code / CodeX 会自动按 `SKILL.md` 的工作流检索
- **快速定位**：先查 `_条目索引.md`，按分类找条目名和文件路径
- **全文搜索**：用 `grep -r "关键词" 分类目录/`，避免全库 grep
- **世界观查询**：优先读 `分析/` 下的结构化分析（01~06），再按其中的证据链反查原文

### 文件约定

- 文件名格式：`{序号}_{slug}_{中文名}.md`，slug 可用于 Wiki 反查
- 每个文件包含 frontmatter：`category`、`title`、`slug`、`source_url` 等
- 引用规范：注明条目名和来源分类，如"据《中枢档案·塔卫二》"

## 许可与来源

- **数据来源**：[Warfarin Wiki](https://warfarin.wiki/cn)（站点最后更新 2026-04-17）
- **采集范围**：仅简体中文页面；不包含图片、音频等媒体资源（正文中的图片仅保留 Markdown 图片链接）
- **整理工作**：本仓库的目录组织、索引文件、世界观分析为本人整理，以 [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.zh) 协议共享
- **原作权利**：所有游戏剧情文本与设定内容版权归 **鹰角网络（Hypergryph）/《明日方舟：终末地》** 及原作者所有；本仓库仅作非商业用途的二次组织与索引，**不得用于商业目的**

如需更新数据，请直接前往 [Warfarin Wiki](https://warfarin.wiki/cn) 查阅最新内容。
