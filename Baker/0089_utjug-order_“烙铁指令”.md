---
category: "Baker"
title: "“烙铁指令”"
slug: "utjug-order"
source_url: "https://warfarin.wiki/cn/baker/utjug-order"
game_data_version: "1.2"
warfarin_updated_at: "2026-04-17"
fetched_at: "2026-04-21T19:50:46+08:00"
---


# “烙铁指令”

## 基本信息

- 类别：Baker
- Slug：`utjug-order`
- 来源：[Warfarin Wiki](https://warfarin.wiki/cn/baker/utjug-order)
- 数据版本：`1.2`
- Warfarin 最后更新：`2026-04-17`
- 采集时间：`2026-04-21T19:50:46+08:00`
- ID：`topic_map01_lv007_2`
- 包含会话：`sns_topic_map01_lv007_3`、`sns_topic_map01_lv007_4`

## 会话

- `sns_topic_map01_lv007_3`：佩丽卡（chatId: `sns_chr_0004_pelica`）
- `sns_topic_map01_lv007_4`：邓恩（chatId: `sns_npc_dunn`）

## 角色表

- `sns_chr_0004_pelica`：佩丽卡：工作用联系B42转分机号****。看到消息一定会回复，若未回复请再敲一次。
- `sns_npc_dunn`：邓恩
- `endmin`：管理员

## 全分支文本

### sns_topic_map01_lv007_3 - 佩丽卡

- （空节点 `contentId=-1`，next=0）
- **管理员** (`endmin`, `contentId=1; pre=0; next=2`)：“烙铁指令”原来可以调动这么庞大的资源？
- **佩丽卡** (`sns_chr_0004_pelica`, `contentId=2; pre=1; next=3`)：还不止于此，管理员，“烙铁指令”对我们行动的支援，只是个开始。
- **佩丽卡** (`sns_chr_0004_pelica`, `contentId=3; pre=2; next=4`)：指令发出后，任何接收到它的联盟工团驻地都会无条件向发信源输送军事资源。
- **佩丽卡** (`sns_chr_0004_pelica`, `contentId=4; pre=3; next=5`)：在我的印象里，战略级的指令从未对裂地者氏族使用过。
- **管理员（选项）** (`option_sns_topic_map01_lv007_3_2_001`, `from=5`)：看来工团真的被惹怒了。 -> contentId 6
- **管理员** (`endmin`, `contentId=6; pre=5; next=7`)：看来这一次，碾骨是真的将工团惹怒了。
- **佩丽卡** (`sns_chr_0004_pelica`, `contentId=7; pre=6; next=8`)：工团的战略火力，可不仅仅是炸毁巢雕这种程度。
- **佩丽卡** (`sns_chr_0004_pelica`, `contentId=8; pre=7; next=9`)：碾骨触碰了工团最珍视的财富——工人们的生命。
- **佩丽卡** (`sns_chr_0004_pelica`, `contentId=9; pre=8; next=10`)：工团必将让碾骨付出惨痛的代价，即使他们现在有聂菲斯的帮助。
- **佩丽卡** (`sns_chr_0004_pelica`, `contentId=10; pre=9; next=11`)：接下来，估计会硝烟四起了。
- **佩丽卡** (`sns_chr_0004_pelica`, `contentId=11; pre=10; next=-1`)：请做好准备，管理员。

### sns_topic_map01_lv007_4 - 邓恩

- （空节点 `contentId=-1`，next=0）
- **邓恩** (`sns_npc_dunn`, `contentId=1; pre=0; next=2`)：谢谢你，管理员。让我活着看到了“烙铁指令”。
- **邓恩** (`sns_npc_dunn`, `contentId=2; pre=1; next=3`)：我也能对后辈们炫耀一番了，哈哈。
- **管理员（选项）** (`option_sns_topic_map01_lv007_4_1_001`, `from=3`)：现在感觉如何？ -> contentId 4
- **管理员** (`endmin`, `contentId=4; pre=3; next=5`)：你现在感觉怎么样？
- **邓恩** (`sns_npc_dunn`, `contentId=5; pre=4; next=6`)：说实话，心情复杂，热泪盈眶。
- **邓恩** (`sns_npc_dunn`, `contentId=6; pre=5; next=7`)：我本来已经做好了牺牲的打算，独自消化对死亡的恐惧……
- **邓恩** (`sns_npc_dunn`, `contentId=7; pre=6; next=8`)：毕竟，在历史书里，“烙铁指令”代表着牺牲，代表着最高觉悟。
- **管理员（选项）** (`option_sns_topic_map01_lv007_4_2_001`, `from=8`)：它的意义发生了变化？ -> contentId 9
- **管理员（选项）** (`option_sns_topic_map01_lv007_4_2_002`, `from=8`)：我感觉它的意义变化了。 -> contentId 10
- **管理员** (`endmin`, `contentId=9; pre=8; next=11`)：“烙铁指令”的意义发生了变化？
- **管理员** (`endmin`, `contentId=10; pre=8; next=11`)：我感觉它的意义发生了变化。
- **邓恩** (`sns_npc_dunn`, `contentId=11; pre=10; next=12`)：是的，如今的“烙铁”，代表着拯救与团结。
- **邓恩** (`sns_npc_dunn`, `contentId=12; pre=11; next=13`)：现在的工团，绝不允许兄弟姐妹们轻易牺牲了。
- **邓恩** (`sns_npc_dunn`, `contentId=13; pre=12; next=14`)：工人们牢牢和工团烙印在一起，这正是工团强大的原因。
- **邓恩** (`sns_npc_dunn`, `contentId=14; pre=13; next=-1`)：没有工人，就没有工团。
