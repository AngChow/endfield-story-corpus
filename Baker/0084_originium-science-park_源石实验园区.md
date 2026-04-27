---
category: "Baker"
title: "源石实验园区"
slug: "originium-science-park"
source_url: "https://warfarin.wiki/cn/baker/originium-science-park"
game_data_version: "1.2"
warfarin_updated_at: "2026-04-17"
fetched_at: "2026-04-21T19:50:46+08:00"
---


# 源石实验园区

## 基本信息

- 类别：Baker
- Slug：`originium-science-park`
- 来源：[Warfarin Wiki](https://warfarin.wiki/cn/baker/originium-science-park)
- 数据版本：`1.2`
- Warfarin 最后更新：`2026-04-17`
- 采集时间：`2026-04-21T19:50:46+08:00`
- ID：`topic_map01_lv005_3`
- 包含会话：`sns_topic_map01_lv005_5`、`sns_topic_map01_lv005_6`

## 会话

- `sns_topic_map01_lv005_5`：法比安·柯林斯（chatId: `sns_npc_kls_m`）
- `sns_topic_map01_lv005_6`：艾莱扎·柯林斯（chatId: `sns_npc_kls_f`）

## 角色表

- `sns_npc_kls_f`：艾莱扎·柯林斯
- `sns_npc_kls_m`：法比安·柯林斯
- `endmin`：管理员

## 全分支文本

### sns_topic_map01_lv005_5 - 法比安·柯林斯

- （空节点 `contentId=-1`，next=0）
- **管理员** (`endmin`, `contentId=1; pre=0; next=2`)：法比安，你和艾莱扎负责整个源石实验园区的安全？
- **法比安·柯林斯** (`sns_npc_kls_m`, `contentId=2; pre=1; next=3`)：是的，管理员。源石实验园区是工团在四号谷地的科研重地之一。
- **法比安·柯林斯** (`sns_npc_kls_m`, `contentId=3; pre=2; next=4`)：因此，安全局将我和艾莱扎部署在这里，由我们统筹安全工作。
- **法比安·柯林斯** (`sns_npc_kls_m`, `contentId=4; pre=3; next=5`)：您有任何安全相关的问题，都可以向我咨询。
- **管理员（选项）** (`option_sns_topic_map01_lv005_5_2_001`, `from=5`)：安全局具体承担什么工作？ -> contentId 6
- **管理员** (`endmin`, `contentId=6; pre=5; next=7`)：安全局具体承担一些什么工作呢？
- **法比安·柯林斯** (`sns_npc_kls_m`, `contentId=7; pre=6; next=8`)：我明白了，您对我们的工作内容感兴趣。
- **法比安·柯林斯** (`sns_npc_kls_m`, `contentId=8; pre=7; next=9`)：安全局是联盟工团的安全部门，除了负责对内安全，还承担了部分关键生产环节的安全监督工作。
- **法比安·柯林斯** (`sns_npc_kls_m`, `contentId=9; pre=8; next=10`)：举例来说，我们既要抵御裂地者的袭击，也要阻止伊冯进行未申报的危险实验。
- **管理员（选项）** (`option_sns_topic_map01_lv005_5_3_001`, `from=10`)：通俗易懂的讲解。 -> contentId 11
- **管理员** (`endmin`, `contentId=11; pre=10; next=12`)：通俗易懂的讲解，谢谢你，法比安。
- **法比安·柯林斯** (`sns_npc_kls_m`, `contentId=12; pre=11; next=-1`)：不客气，管理员，有问题随时问我。

### sns_topic_map01_lv005_6 - 艾莱扎·柯林斯

- （空节点 `contentId=-1`，next=0）
- **管理员** (`endmin`, `contentId=1; pre=0; next=2`)：艾莱扎，我进入园区内部了。
- **艾莱扎·柯林斯** (`sns_npc_kls_f`, `contentId=2; pre=1; next=3`)：是不是和印象里工团的风格不太一样？
- **艾莱扎·柯林斯** (`sns_npc_kls_f`, `contentId=3; pre=2; next=4`)：这都要拜伊冯所赐……
- **艾莱扎·柯林斯** (`sns_npc_kls_f`, `contentId=4; pre=3; next=5`)：她来到园区与工团进行合作之后，园区里可变得热闹非凡了。
- **管理员（选项）** (`option_sns_topic_map01_lv005_6_2_001`, `from=5`)：热闹？ -> contentId 6
- **管理员** (`endmin`, `contentId=6; pre=5; next=7`)：热闹的意思是……？
- **艾莱扎·柯林斯** (`sns_npc_kls_f`, `contentId=7; pre=6; next=8`)：公用广播频道经常串台到一些奇奇怪怪的音乐就算了。
- **艾莱扎·柯林斯** (`sns_npc_kls_f`, `contentId=8; pre=7; next=9`)：有一次为了探索在无人机上搭载大型功率模型的可行性……
- **艾莱扎·柯林斯** (`sns_npc_kls_f`, `contentId=9; pre=8; next=10`)：我还没有给她实验场所的批准，结果她迫不及待在研究所里开工了。
- **艾莱扎·柯林斯** (`sns_npc_kls_f`, `contentId=10; pre=9; next=11`)：要不是我和我哥及时赶到，整座研究所差点就烧起来了！
- **管理员（选项）** (`option_sns_topic_map01_lv005_6_3_001`, `from=11`)：原来是这种热闹…… -> contentId 12
- **管理员（选项）** (`option_sns_topic_map01_lv005_6_3_002`, `from=11`)：还是要注意安全…… -> contentId 13
- **管理员** (`endmin`, `contentId=12; pre=11; next=14`)：有点过于热闹了……
- **管理员** (`endmin`, `contentId=13; pre=11; next=14`)：还是要严格对伊冯进行安全教育。
- **艾莱扎·柯林斯** (`sns_npc_kls_f`, `contentId=14; pre=13; next=15`)：不过，她也确实给园区带来了不一样的活力。
- **艾莱扎·柯林斯** (`sns_npc_kls_f`, `contentId=15; pre=14; next=16`)：有些工友私下和我反馈，他们很爱听伊冯的歌单。
- **艾莱扎·柯林斯** (`sns_npc_kls_f`, `contentId=16; pre=15; next=-1`)：她的无人机矩阵和奇怪装置也客观提高了园区的安全水平。
