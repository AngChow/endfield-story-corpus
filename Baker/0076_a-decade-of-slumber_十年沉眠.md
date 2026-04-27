---
category: "Baker"
title: "十年沉眠"
slug: "a-decade-of-slumber"
source_url: "https://warfarin.wiki/cn/baker/a-decade-of-slumber"
game_data_version: "1.2"
warfarin_updated_at: "2026-04-17"
fetched_at: "2026-04-21T19:50:46+08:00"
---


# 十年沉眠

## 基本信息

- 类别：Baker
- Slug：`a-decade-of-slumber`
- 来源：[Warfarin Wiki](https://warfarin.wiki/cn/baker/a-decade-of-slumber)
- 数据版本：`1.2`
- Warfarin 最后更新：`2026-04-17`
- 采集时间：`2026-04-21T19:50:46+08:00`
- ID：`topic_map01_lv001_1`
- 包含会话：`sns_topic_map01_lv001_1`、`sns_topic_map01_lv001_2`

## 会话

- `sns_topic_map01_lv001_1`：安德烈（chatId: `sns_npc_andrew`）
- `sns_topic_map01_lv001_2`：佩丽卡（chatId: `sns_chr_0004_pelica`）

## 角色表

- `sns_chr_0004_pelica`：佩丽卡：工作用联系B42转分机号****。看到消息一定会回复，若未回复请再敲一次。
- `sns_npc_andrew`：安德烈
- `endmin`：管理员

## 全分支文本

### sns_topic_map01_lv001_1 - 安德烈

- （空节点 `contentId=-1`，next=0）
- **安德烈** (`sns_npc_andrew`, `contentId=1; pre=0; next=2`)：管理员，上次和您用Baker聊天，还是十年前。
- **安德烈** (`sns_npc_andrew`, `contentId=2; pre=1; next=3`)：真是怀念啊！
- **安德烈** (`sns_npc_andrew`, `contentId=3; pre=2; next=4`)：关于这里的事情，您还记得多少？
- **管理员（选项）** (`option_sns_topic_map01_lv001_1_1_001`, `from=4`)：我什么都不记得了。 -> contentId 5
- **管理员** (`endmin`, `contentId=5; pre=4; next=6`)：不光是这里，我几乎想不起来任何事情。
- **Unknown** (``, `contentId=6; pre=5; next=7`)：[安德烈]输入中
- **Unknown** (``, `contentId=7; pre=6; next=8`)：[安德烈]停止输入
- **Unknown** (``, `contentId=8; pre=7; next=9`)：[安德烈]输入中
- **安德烈** (`sns_npc_andrew`, `contentId=9; pre=8; next=10`)：没事的！总会有想起来的那天！
- **安德烈** (`sns_npc_andrew`, `contentId=10; pre=9; next=11`)：关于枢纽区基地，有什么想了解的，随时问我。
- **管理员（选项）** (`option_sns_topic_map01_lv001_1_2_001`, `from=11`)：工团的人都很好相处。 -> contentId 12
- **管理员** (`endmin`, `contentId=12; pre=11; next=13`)：感觉工团的工人们都很好相处。
- **安德烈** (`sns_npc_andrew`, `contentId=13; pre=12; next=14`)：那当然，我们来到四号谷地后，就和工团的工人们打成一片。
- **安德烈** (`sns_npc_andrew`, `contentId=14; pre=13; next=15`)：如果天气不错，我们会邀请他们参加一些友好的球类竞赛。
- **安德烈** (`sns_npc_andrew`, `contentId=15; pre=14; next=16`)：偶尔还会举办像是锻造大赛这种比拼技术的竞赛——只用老式锻炉和打铁榔头，比比谁锻的武器更耐用。
- **安德烈** (`sns_npc_andrew`, `contentId=16; pre=15; next=17`)：至于比赛的奖品嘛，从实用工具到有趣的工艺品，应有尽有，都是大家一起选的，管理员您也选过一些。
- **安德烈** (`sns_npc_andrew`, `contentId=17; pre=16; next=18`)：还有一回，我闯进了掰手腕比赛的决赛，坐在我对面的是一名运输队的工人。
- **管理员（选项）** (`option_sns_topic_map01_lv001_1_3_001`, `from=18`)：谁赢了？ -> contentId 19
- **管理员（选项）** (`option_sns_topic_map01_lv001_1_3_002`, `from=18`)：结果如何？ -> contentId 20
- **管理员** (`endmin`, `contentId=19; pre=18; next=21`)：最后是谁赢了？
- **管理员** (`endmin`, `contentId=20; pre=18; next=21`)：最后结果如何？
- **安德烈** (`sns_npc_andrew`, `contentId=21; pre=20; next=22`)：最后嘛……我们用他奖品里的工具，帮他修好了他的卡车……
- **安德烈** (`sns_npc_andrew`, `contentId=22; pre=21; next=23`)：咳咳，大家都志在建设开拓区，所以很聊得来。
- **安德烈** (`sns_npc_andrew`, `contentId=23; pre=22; next=24`)：这十年里，我们经常和工人们一起出去开山铺路，四号谷地每星期都变个样！
- **安德烈** (`sns_npc_andrew`, `contentId=24; pre=23; next=-1`)：唉，要是这场袭击没有发生该多好……

### sns_topic_map01_lv001_2 - 佩丽卡

- （空节点 `contentId=-1`，next=0）
- **管理员** (`endmin`, `contentId=1; pre=0; next=2`)：之前在帝江号上，我记得你说过我沉睡了十年，塔卫二现在怎么样了？
- **佩丽卡** (`sns_chr_0004_pelica`, `contentId=2; pre=1; next=3`)：嗯，距离你最近一次陷入休眠，已经过去了十年。
- **佩丽卡** (`sns_chr_0004_pelica`, `contentId=3; pre=2; next=4`)：这十年里，我们一直与各大组织机构协作，监控塔卫二上的各处危险区域，清剿残余的敌对力量。
- **佩丽卡** (`sns_chr_0004_pelica`, `contentId=4; pre=3; next=5`)：当然，最重要的任务，还是遵循“零号委托”推进协议核心的研发工作，等待唤醒你的时机。
- **佩丽卡** (`sns_chr_0004_pelica`, `contentId=5; pre=4; next=6`)：怎么，管理员，为什么突然问这个？
- **管理员（选项）** (`option_sns_topic_map01_lv001_2_2_001`, `from=6`)：我的失忆耽误了很多事吧。 -> contentId 7
- **管理员** (`endmin`, `contentId=7; pre=6; next=8`)：与安德烈见面后，他像是有很多话想和我说。
- **管理员** (`endmin`, `contentId=8; pre=7; next=9`)：但在帝江号上时，大家似乎过于平静了。
- **管理员** (`endmin`, `contentId=9; pre=8; next=10`)：终末地等待着唤醒我的时机，等了十年，我却失忆了。
- **佩丽卡** (`sns_chr_0004_pelica`, `contentId=10; pre=9; next=11`)：请不要这样想，我们等了十年，但不只是等了十年。
- **佩丽卡** (`sns_chr_0004_pelica`, `contentId=11; pre=10; next=12`)：无论是上一次唤醒你，还是更久远以前的战争，都是你为我们扛下了责任。
- **佩丽卡** (`sns_chr_0004_pelica`, `contentId=12; pre=11; next=13`)：现在该轮到我们为你分担。
- **佩丽卡** (`sns_chr_0004_pelica`, `contentId=13; pre=12; next=14`)：你回来了，就是对我们最重要的事。
- **管理员（选项）** (`option_sns_topic_map01_lv001_2_3_001`, `from=14`)：还有很多事情要做。 -> contentId 15
- **管理员** (`endmin`, `contentId=15; pre=14; next=16`)：嗯，我们都该放松些，然后一起做好准备。
- **佩丽卡** (`sns_chr_0004_pelica`, `contentId=16; pre=15; next=17`)：![sns_emoji_019](https://static.warfarin.wiki/v4/reading/sns_emoji_019.webp)
- **佩丽卡** (`sns_chr_0004_pelica`, `contentId=17; pre=16; next=-1`)：抱歉，我也有点激动了。
