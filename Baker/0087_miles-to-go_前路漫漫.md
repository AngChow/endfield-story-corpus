---
category: "Baker"
title: "前路漫漫"
slug: "miles-to-go"
source_url: "https://warfarin.wiki/cn/baker/miles-to-go"
game_data_version: "1.2"
warfarin_updated_at: "2026-04-17"
fetched_at: "2026-04-21T19:50:46+08:00"
---


# 前路漫漫

## 基本信息

- 类别：Baker
- Slug：`miles-to-go`
- 来源：[Warfarin Wiki](https://warfarin.wiki/cn/baker/miles-to-go)
- 数据版本：`1.2`
- Warfarin 最后更新：`2026-04-17`
- 采集时间：`2026-04-21T19:50:46+08:00`
- ID：`topic_map01_lv006_3`
- 包含会话：`sns_topic_map01_lv006_5`、`sns_topic_map01_lv006_6`

## 会话

- `sns_topic_map01_lv006_5`：越医生（chatId: `sns_npc_yueyisheng`）
- `sns_topic_map01_lv006_6`：阿丽娅（chatId: `sns_npc_aliya`）

## 角色表

- `sns_npc_aliya`：阿丽娅
- `sns_npc_yueyisheng`：越医生
- `endmin`：管理员

## 全分支文本

### sns_topic_map01_lv006_5 - 越医生

- （空节点 `contentId=-1`，next=0）
- **管理员** (`endmin`, `contentId=1; pre=0; next=2`)：你辛苦了，越医生。
- **越医生** (`sns_npc_yueyisheng`, `contentId=2; pre=1; next=3`)：谢谢你，管理员。
- **越医生** (`sns_npc_yueyisheng`, `contentId=3; pre=2; next=4`)：灾难面前，我只是尽一份医生该尽的责任罢了。
- **管理员（选项）** (`option_sns_topic_map01_lv006_5_2_001`, `from=4`)：伤患们的情况如何？ -> contentId 5
- **管理员** (`endmin`, `contentId=5; pre=4; next=6`)：伤患们的情况怎么样了？
- **越医生** (`sns_npc_yueyisheng`, `contentId=6; pre=5; next=7`)：大部分伤势较轻的工人已经痊愈。
- **越医生** (`sns_npc_yueyisheng`, `contentId=7; pre=6; next=8`)：目前我和阿丽娅正在全力救助那些伤势依旧严重的工人。
- **越医生** (`sns_npc_yueyisheng`, `contentId=8; pre=7; next=9`)：其中有不少是袭击发生时不顾危险、挺身而出的英雄，我不会让他们有事的。
- **越医生** (`sns_npc_yueyisheng`, `contentId=9; pre=8; next=10`)：如果没有他们，矿脉源区的情况估计会变得更糟。
- **管理员（选项）** (`option_sns_topic_map01_lv006_5_3_001`, `from=10`)：希望他们早日康复。 -> contentId 11
- **管理员** (`endmin`, `contentId=11; pre=10; next=12`)：衷心希望他们早日康复。
- **越医生** (`sns_npc_yueyisheng`, `contentId=12; pre=11; next=-1`)：我会向他们传达这份祝福的，管理员。

### sns_topic_map01_lv006_6 - 阿丽娅

- （空节点 `contentId=-1`，next=0）
- **阿丽娅** (`sns_npc_aliya`, `contentId=1; pre=0; next=2`)：管理员，谢谢你战胜了那个天使，拯救了大家。
- **阿丽娅** (`sns_npc_aliya`, `contentId=2; pre=1; next=3`)：虽然我没亲眼见过，但我知道，它是萦绕矿区前辈们的噩梦。
- **阿丽娅** (`sns_npc_aliya`, `contentId=3; pre=2; next=4`)：谢谢你。
- **管理员（选项）** (`option_sns_topic_map01_lv006_6_1_001`, `from=4`)：今后你们有什么打算？ -> contentId 5
- **管理员** (`endmin`, `contentId=5; pre=4; next=6`)：今后你们有什么计划？
- **阿丽娅** (`sns_npc_aliya`, `contentId=6; pre=5; next=7`)：唉……
- **阿丽娅** (`sns_npc_aliya`, `contentId=7; pre=6; next=8`)：许多人都打算离开了，他们想去别的地方看看。
- **阿丽娅** (`sns_npc_aliya`, `contentId=8; pre=7; next=9`)：有些人失去了亲人朋友，不想留在伤心之地。
- **阿丽娅** (`sns_npc_aliya`, `contentId=9; pre=8; next=10`)：还有一些人，我能感觉到，即使没有这次的灾难，他们也早就想离开这片老矿区了。
- **管理员（选项）** (`option_sns_topic_map01_lv006_6_2_001`, `from=10`)：人各有志。 -> contentId 11
- **管理员** (`endmin`, `contentId=11; pre=10; next=12`)：每个人的路都不一样吧。
- **阿丽娅** (`sns_npc_aliya`, `contentId=12; pre=11; next=13`)：你说得对……我也希望他们能过得更好。
- **阿丽娅** (`sns_npc_aliya`, `contentId=13; pre=12; next=14`)：不过还是有很多把矿脉源区当成家园的人，留了下来。我也一样。
- **阿丽娅** (`sns_npc_aliya`, `contentId=14; pre=13; next=15`)：我会好好努力，协助他们重建家园的！
- **阿丽娅** (`sns_npc_aliya`, `contentId=15; pre=14; next=-1`)：有空的话，常回来看看，管理员！
