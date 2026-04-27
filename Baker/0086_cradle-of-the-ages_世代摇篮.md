---
category: "Baker"
title: "世代摇篮"
slug: "cradle-of-the-ages"
source_url: "https://warfarin.wiki/cn/baker/cradle-of-the-ages"
game_data_version: "1.2"
warfarin_updated_at: "2026-04-17"
fetched_at: "2026-04-21T19:50:46+08:00"
---


# 世代摇篮

## 基本信息

- 类别：Baker
- Slug：`cradle-of-the-ages`
- 来源：[Warfarin Wiki](https://warfarin.wiki/cn/baker/cradle-of-the-ages)
- 数据版本：`1.2`
- Warfarin 最后更新：`2026-04-17`
- 采集时间：`2026-04-21T19:50:46+08:00`
- ID：`topic_map01_lv006_2`
- 包含会话：`sns_topic_map01_lv006_3`、`sns_topic_map01_lv006_4`

## 会话

- `sns_topic_map01_lv006_3`：秦茳尺（chatId: `sns_npc_qinjc`）
- `sns_topic_map01_lv006_4`：佩丽卡（chatId: `sns_chr_0004_pelica`）

## 角色表

- `sns_chr_0004_pelica`：佩丽卡：工作用联系B42转分机号****。看到消息一定会回复，若未回复请再敲一次。
- `sns_npc_qinjc`：秦茳尺
- `endmin`：管理员

## 全分支文本

### sns_topic_map01_lv006_3 - 秦茳尺

- （空节点 `contentId=-2`，next=0）
- （空节点 `contentId=-1`，next=0）
- **秦茳尺** (`sns_npc_qinjc`, `contentId=1; pre=0; next=2`)：管理员，我接到了工团的照会，和您同步一下世代摇篮的最新情况。
- **管理员（选项）** (`option_sns_topic_map01_lv006_3_1_001`, `from=2`)：情况如何？ -> contentId 3
- **管理员** (`endmin`, `contentId=3; pre=2; next=4`)：具体情况怎么样？
- **秦茳尺** (`sns_npc_qinjc`, `contentId=4; pre=3; next=5`)：多亏你们解决了那只巨大的天使。
- **秦茳尺** (`sns_npc_qinjc`, `contentId=5; pre=4; next=6`)：世代摇篮解除了封锁，但并未全面对公众开放。
- **秦茳尺** (`sns_npc_qinjc`, `contentId=6; pre=5; next=7`)：经过工团方面决议，那里将成为一片特殊的保护区域。
- **管理员（选项）** (`option_sns_topic_map01_lv006_3_3_001`, `from=7`)：保护区域？ -> contentId 8
- **管理员（选项）** (`option_sns_topic_map01_lv006_3_3_002`, `from=7`)：原因是？ -> contentId 9
- **管理员** (`endmin`, `contentId=8; pre=7; next=10`)：保护区域是指？
- **管理员** (`endmin`, `contentId=9; pre=7; next=10`)：成为保护区域的原因是？
- **秦茳尺** (`sns_npc_qinjc`, `contentId=10; pre=9; next=11`)：因为源石树苗的重新生长，工团需要对它进行调查和取样，而终末地也将继续参与其中。
- **秦茳尺** (`sns_npc_qinjc`, `contentId=11; pre=10; next=12`)：大家都期待它能有机会重新成长为过去的那副参天之躯。
- **管理员（选项）** (`option_sns_topic_map01_lv006_3_4_001`, `from=12`)：太好了！ -> contentId 13
- **管理员（选项）** (`option_sns_topic_map01_lv006_3_4_002`, `from=12`)：希望如此！ -> contentId 14
- **管理员** (`endmin`, `contentId=13; pre=12; next=-1`)：那真是一件大好事！
- **管理员** (`endmin`, `contentId=14; pre=12; next=-2`)：希望如此！

### sns_topic_map01_lv006_4 - 佩丽卡

- （空节点 `contentId=-1`，next=0）
- **佩丽卡** (`sns_chr_0004_pelica`, `contentId=1; pre=0; next=2`)：辛苦你了，管理员。
- **管理员（选项）** (`option_sns_topic_map01_lv006_4_3_001`, `from=2`)：那只巨型天使很强。 -> contentId 3
- **管理员** (`endmin`, `contentId=3; pre=2; next=4`)：那只巨型天使很强大。
- **佩丽卡** (`sns_chr_0004_pelica`, `contentId=4; pre=3; next=5`)：那只“三位一体”，只是二十年前袭击矿脉源区的“星体”的一部分。
- **佩丽卡** (`sns_chr_0004_pelica`, `contentId=5; pre=4; next=6`)：幸亏这样，我们才得以击败它。
- **佩丽卡** (`sns_chr_0004_pelica`, `contentId=6; pre=5; next=7`)：而那三枚唤醒它的锚点，落下的位置如此准确……
- **佩丽卡** (`sns_chr_0004_pelica`, `contentId=7; pre=6; next=8`)：很明显，三位一体的复苏就是聂菲斯一手策划的。
- **管理员（选项）** (`option_sns_topic_map01_lv006_4_2_001`, `from=8`)：她的真实目的是？ -> contentId 9
- **管理员** (`endmin`, `contentId=9; pre=8; next=10`)：不知道她的真实目的是什么。
- **佩丽卡** (`sns_chr_0004_pelica`, `contentId=10; pre=9; next=11`)：破坏终末地和工团的生产应该是她最直接的目的。
- **佩丽卡** (`sns_chr_0004_pelica`, `contentId=11; pre=10; next=12`)：但是……从她至今的表现来看……
- **佩丽卡** (`sns_chr_0004_pelica`, `contentId=12; pre=11; next=13`)：我感觉，她似乎有更大的阴谋。
- **佩丽卡** (`sns_chr_0004_pelica`, `contentId=13; pre=12; next=-1`)：我们得抓紧行动了，管理员。
