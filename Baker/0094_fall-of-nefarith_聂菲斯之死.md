---
category: "Baker"
title: "聂菲斯之死"
slug: "fall-of-nefarith"
source_url: "https://warfarin.wiki/cn/baker/fall-of-nefarith"
game_data_version: "1.2"
warfarin_updated_at: "2026-04-17"
fetched_at: "2026-04-21T19:50:46+08:00"
---


# 聂菲斯之死

## 基本信息

- 类别：Baker
- Slug：`fall-of-nefarith`
- 来源：[Warfarin Wiki](https://warfarin.wiki/cn/baker/fall-of-nefarith)
- 数据版本：`1.2`
- Warfarin 最后更新：`2026-04-17`
- 采集时间：`2026-04-21T19:50:46+08:00`
- ID：`topic_map02_lv002_12001`
- 包含会话：`sns_topic_map02_lv002_12001`、`sns_topic_map02_lv002_12002`

## 会话

- `sns_topic_map02_lv002_12001`：联络员菲奥娜（chatId: `sns_npc_fiona`）
- `sns_topic_map02_lv002_12002`：秦茳尺（chatId: `sns_npc_qinjc`）

## 角色表

- `sns_npc_fiona`：联络员菲奥娜
- `sns_npc_qinjc`：秦茳尺
- `endmin`：管理员

## 全分支文本

### sns_topic_map02_lv002_12001 - 联络员菲奥娜

- （空节点 `contentId=-1`，next=0）
- **联络员菲奥娜** (`sns_npc_fiona`, `contentId=1; pre=0; next=2`)：管理员，有来自环带的紧急消息！
- **联络员菲奥娜** (`sns_npc_fiona`, `contentId=2; pre=1; next=3`)：环带的各大城市将从今天起提高安全警戒等级，取消未来一个月的所有公众活动。
- **联络员菲奥娜** (`sns_npc_fiona`, `contentId=3; pre=2; next=4`)：部分城市甚至决定采取宵禁措施……
- **管理员（选项）** (`option_sns_topic_map02_lv002_12001_1_001`, `from=4`)：其他地方也遇袭了？ -> contentId 5
- **管理员** (`endmin`, `contentId=5; pre=4; next=6`)：怎么回事？其他地方也遇袭了？
- **联络员菲奥娜** (`sns_npc_fiona`, `contentId=6; pre=5; next=7`)：刚刚，帝江号观测到武陵地区的深度读数突然发生变化。
- **联络员菲奥娜** (`sns_npc_fiona`, `contentId=7; pre=6; next=8`)：宏科院向各方同步了武陵城进入紧急状态的消息，并且发出了对环带全域的安全警告。
- **联络员菲奥娜** (`sns_npc_fiona`, `contentId=8; pre=7; next=9`)：这段时间，各方的联络人都试图从我们这里了解武陵的状况。
- **联络员菲奥娜** (`sns_npc_fiona`, `contentId=9; pre=8; next=10`)：就连宏科院本部也无法立刻掌握情况……
- **管理员（选项）** (`option_sns_topic_map02_lv002_12001_2_001`, `from=10`)：我们击退了袭击。 -> contentId 11
- **管理员（选项）** (`option_sns_topic_map02_lv002_12001_2_002`, `from=10`)：武陵安全了。 -> contentId 13
- **管理员** (`endmin`, `contentId=11; pre=10; next=12`)：我们击退了针对武陵城的大规模袭击。
- **管理员** (`endmin`, `contentId=12; pre=11; next=15`)：聂菲斯也被我们消灭了，希望碾骨氏族的威胁到此为止。
- **管理员** (`endmin`, `contentId=13; pre=10; next=14`)：武陵安全了，我们消灭了聂菲斯。
- **管理员** (`endmin`, `contentId=14; pre=13; next=15`)：希望碾骨氏族的威胁到此为止。
- **联络员菲奥娜** (`sns_npc_fiona`, `contentId=15; pre=14; next=16`)：聂菲斯被消灭了？太好了，管理员！
- **联络员菲奥娜** (`sns_npc_fiona`, `contentId=16; pre=15; next=-1`)：我这就将这条好消息同步出去！

### sns_topic_map02_lv002_12002 - 秦茳尺

- （空节点 `contentId=-1`，next=0）
- **管理员** (`endmin`, `contentId=1; pre=0; next=2`)：我们在武陵消灭了聂菲斯。
- **秦茳尺** (`sns_npc_qinjc`, `contentId=2; pre=1; next=3`)：这真是个好消息！管理员，你们没受伤吧？
- **管理员（选项）** (`option_sns_topic_map02_lv002_12002_1_001`, `from=3`)：我们没事。 -> contentId 4
- **管理员** (`endmin`, `contentId=4; pre=3; next=5`)：我们没事，不用担心。
- **秦茳尺** (`sns_npc_qinjc`, `contentId=5; pre=4; next=6`)：你们没事就好。
- **秦茳尺** (`sns_npc_qinjc`, `contentId=6; pre=5; next=7`)：这几天四号谷地的工人们也都在讨论，聂菲斯可能会带着碾骨氏族跑到哪里去。
- **秦茳尺** (`sns_npc_qinjc`, `contentId=7; pre=6; next=8`)：大家都说，要是聂菲斯还敢回来，一定要让她付出代价。
- **秦茳尺** (`sns_npc_qinjc`, `contentId=8; pre=7; next=9`)：太好了，从四号谷地开始的纷争，现在终于结束了……
- **管理员（选项）** (`option_sns_topic_map02_lv002_12002_2_001`, `from=9`)：大家终于可以安心了。 -> contentId 10
- **管理员** (`endmin`, `contentId=10; pre=9; next=11`)：大家终于可以安心了。
- **秦茳尺** (`sns_npc_qinjc`, `contentId=11; pre=10; next=12`)：但是管理员，你还是要多加小心。
- **秦茳尺** (`sns_npc_qinjc`, `contentId=12; pre=11; next=13`)：袭扰环带的裂地者被我们击退了很多次，但每一次他们最终都能卷土重来。
- **秦茳尺** (`sns_npc_qinjc`, `contentId=13; pre=12; next=14`)：……即使另一个聂菲斯横空出世，我也不会感到意外。
- **管理员（选项）** (`option_sns_topic_map02_lv002_12002_3_001`, `from=14`)：我会注意的。 -> contentId 15
- **管理员** (`endmin`, `contentId=15; pre=14; next=16`)：嗯，我明白，我们会继续注意裂地者的动向。
- **秦茳尺** (`sns_npc_qinjc`, `contentId=16; pre=15; next=17`)：唉，无论如何，聂菲斯终于……
- **秦茳尺** (`sns_npc_qinjc`, `contentId=17; pre=16; next=-1`)：我已经等不及想看看四号谷地的大家听到这条消息后，会是怎样的表情。
