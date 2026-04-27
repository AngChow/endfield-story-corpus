---
category: "Baker"
title: "机械故障"
slug: "technical-glitch"
source_url: "https://warfarin.wiki/cn/baker/technical-glitch"
game_data_version: "1.2"
warfarin_updated_at: "2026-04-17"
fetched_at: "2026-04-21T19:50:46+08:00"
---


# 机械故障

## 基本信息

- 类别：Baker
- Slug：`technical-glitch`
- 来源：[Warfarin Wiki](https://warfarin.wiki/cn/baker/technical-glitch)
- 数据版本：`1.2`
- Warfarin 最后更新：`2026-04-17`
- 采集时间：`2026-04-21T19:50:46+08:00`
- ID：`topic_map01_lv007_3`
- 包含会话：`sns_topic_map01_lv007_5`、`sns_topic_map01_lv007_6`

## 会话

- `sns_topic_map01_lv007_5`：陈千语（chatId: `sns_chr_0005_chen`）
- `sns_topic_map01_lv007_6`：安德烈（chatId: `sns_npc_andrew`）

## 角色表

- `sns_chr_0005_chen`：陈千语：德才兼备。
- `sns_npc_andrew`：安德烈
- `endmin`：管理员

## 全分支文本

### sns_topic_map01_lv007_5 - 陈千语

- （空节点 `contentId=-2`，next=0）
- （空节点 `contentId=-1`，next=0）
- **陈千语** (`sns_chr_0005_chen`, `contentId=1; pre=0; next=2`)：管理员，我发现一件有意思的事。
- **管理员（选项）** (`option_sns_topic_map01_lv007_5_1_001`, `from=2`)：什么事？ -> contentId 3
- **管理员** (`endmin`, `contentId=3; pre=2; next=4`)：什么有意思的事？
- **陈千语** (`sns_chr_0005_chen`, `contentId=4; pre=3; next=5`)：工团的技术员们比我从资料里看到的更懂得变通。
- **陈千语** (`sns_chr_0005_chen`, `contentId=5; pre=4; next=6`)：碾骨氏族那帮家伙把源石发电站的很多机械都弄坏了。
- **陈千语** (`sns_chr_0005_chen`, `contentId=6; pre=5; next=7`)：我以为他们会按照工团手册上的流程，严格等待替换零件运来再修理。
- **陈千语** (`sns_chr_0005_chen`, `contentId=7; pre=6; next=8`)：结果他们商量了一下，直接把修不好的机械都拆了，然后把能用的零件拼在一起。
- **管理员（选项）** (`option_sns_topic_map01_lv007_5_2_001`, `from=8`)：他们打算造什么？ -> contentId 9
- **管理员** (`endmin`, `contentId=9; pre=8; next=10`)：他们打算用这些零件造什么呢？
- **陈千语** (`sns_chr_0005_chen`, `contentId=10; pre=9; next=11`)：他们最后造了一个多功能机械臂，用来搬运沉重的物资或残骸。
- **陈千语** (`sns_chr_0005_chen`, `contentId=11; pre=10; next=12`)：还一边唱着歌，一边给最后的成品来了个剪彩仪式！
- **管理员（选项）** (`option_sns_topic_map01_lv007_5_3_001`, `from=12`)：看来乐观也是他们的武器。 -> contentId 13
- **管理员（选项）** (`option_sns_topic_map01_lv007_5_3_002`, `from=12`)：我也想看！ -> contentId 15
- **管理员** (`endmin`, `contentId=13; pre=12; next=14`)：看来乐观也是工团技术员们的武器之一。
- **陈千语** (`sns_chr_0005_chen`, `contentId=14; pre=13; next=-1`)：说得好呀，管理员！
- **管理员** (`endmin`, `contentId=15; pre=12; next=16`)：听起来真有趣，我也想看看了。
- **陈千语** (`sns_chr_0005_chen`, `contentId=16; pre=15; next=-2`)：哎呀，我看得入神了，忘记录像了！

### sns_topic_map01_lv007_6 - 安德烈

- （空节点 `contentId=-1`，next=0）
- **安德烈** (`sns_npc_andrew`, `contentId=1; pre=0; next=2`)：管理员，听说源石发电站损失惨重，克劳还好吗？
- **管理员（选项）** (`option_sns_topic_map01_lv007_6_1_001`, `from=2`)：他很安全。 -> contentId 3
- **管理员** (`endmin`, `contentId=3; pre=2; next=4`)：他很安全。原来你们很熟？
- **安德烈** (`sns_npc_andrew`, `contentId=4; pre=3; next=5`)：嗯，以前合作过，他也是原型机的初始设计者之一。
- **管理员（选项）** (`option_sns_topic_map01_lv007_6_2_001`, `from=5`)：你觉得他怎么样？ -> contentId 6
- **管理员** (`endmin`, `contentId=6; pre=5; next=7`)：你觉得他是个什么样的人？
- **安德烈** (`sns_npc_andrew`, `contentId=7; pre=6; next=8`)：哈哈，管理员，我知道您想问什么。
- **安德烈** (`sns_npc_andrew`, `contentId=8; pre=7; next=9`)：克劳和我是截然不同的技术员，有时我都觉得他严厉死板到近乎偏执。
- **安德烈** (`sns_npc_andrew`, `contentId=9; pre=8; next=10`)：但也正因这样，他才能带领发电站的大家直到现在吧。
- **安德烈** (`sns_npc_andrew`, `contentId=10; pre=9; next=11`)：只是可惜了，丹尼尔斯站长……
- **管理员（选项）** (`option_sns_topic_map01_lv007_6_3_001`, `from=11`)：他的牺牲不会白费。 -> contentId 12
- **管理员（选项）** (`option_sns_topic_map01_lv007_6_3_002`, `from=11`)：他会被铭记的。 -> contentId 13
- **管理员** (`endmin`, `contentId=12; pre=11; next=14`)：丹尼尔斯的牺牲不会白费。
- **管理员** (`endmin`, `contentId=13; pre=11; next=14`)：丹尼尔斯会被铭记的。
- **安德烈** (`sns_npc_andrew`, `contentId=14; pre=13; next=15`)：嗯……他是一个很典型的工团人，坚强、不屈。
- **安德烈** (`sns_npc_andrew`, `contentId=15; pre=14; next=16`)：工团就是靠这样的精神，挺过了这么多难关。
- **安德烈** (`sns_npc_andrew`, `contentId=16; pre=15; next=-1`)：您没有辜负他的意志，管理员。
