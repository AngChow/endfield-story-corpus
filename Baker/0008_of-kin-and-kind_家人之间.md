---
category: "Baker"
title: "家人之间"
slug: "of-kin-and-kind"
source_url: "https://warfarin.wiki/cn/baker/of-kin-and-kind"
game_data_version: "1.2"
warfarin_updated_at: "2026-04-17"
fetched_at: "2026-04-21T19:50:46+08:00"
---


# 家人之间

## 基本信息

- 类别：Baker
- Slug：`of-kin-and-kind`
- 来源：[Warfarin Wiki](https://warfarin.wiki/cn/baker/of-kin-and-kind)
- 数据版本：`1.2`
- Warfarin 最后更新：`2026-04-17`
- 采集时间：`2026-04-21T19:50:46+08:00`
- ID：`topic_chr_0006_wolfgd_2`
- 包含会话：`sns_topic_chr_0006_wolfgd_2`

## 会话

- `sns_topic_chr_0006_wolfgd_2`：狼卫（chatId: `sns_chr_0006_wolfgd`）

## 角色表

- `sns_chr_0006_wolfgd`：狼卫：正在解决问题或前往问题的路上。
- `endmin`：管理员

## 全分支文本

### sns_topic_chr_0006_wolfgd_2 - 狼卫

- （空节点 `contentId=-1`，next=0）
- **狼卫** (`sns_chr_0006_wolfgd`, `contentId=1; pre=0; next=2`)：管理员，或许你可以替我解决这个麻烦
- **狼卫** (`sns_chr_0006_wolfgd`, `contentId=2; pre=1; next=3`)：简单来说就是，能帮我挑一份礼物吗？
- **管理员（选项）** (`option_sns_topic_chr_0006_wolfgd_2_1_001`, `from=3`)：送给谁的？ -> contentId 4
- **管理员（选项）** (`option_sns_topic_chr_0006_wolfgd_2_1_002`, `from=3`)：具体要求？ -> contentId 5
- **管理员** (`endmin`, `contentId=4; pre=3; next=6`)：送给谁的礼物？有什么要求吗？
- **管理员** (`endmin`, `contentId=5; pre=3; next=6`)：说说具体的要求？送的对象是？
- **狼卫** (`sns_chr_0006_wolfgd`, `contentId=6; pre=5; next=7`)：给洛茜的。没什么要求，能作为我太久没去看望她的赔礼就好。
- **管理员（选项）** (`option_sns_topic_chr_0006_wolfgd_2_2_001`, `from=7`)：她喜欢什么？ -> contentId 8
- **管理员（选项）** (`option_sns_topic_chr_0006_wolfgd_2_2_002`, `from=7`)：有什么备选吗？ -> contentId 11
- **管理员** (`endmin`, `contentId=8; pre=7; next=9`)：你好歹告诉我，她有什么喜欢的东西吧？
- **狼卫** (`sns_chr_0006_wolfgd`, `contentId=9; pre=8; next=10`)：她喜欢精致一点的刀具，不好用也可以
- **狼卫** (`sns_chr_0006_wolfgd`, `contentId=10; pre=9; next=14`)：还有那种特别闪亮的饰品，她收藏过很多，前几年我去耶尔什还给她带过一些。
- **管理员** (`endmin`, `contentId=11; pre=7; next=12`)：有什么备选的礼物吗？我帮你挑挑？
- **狼卫** (`sns_chr_0006_wolfgd`, `contentId=12; pre=11; next=13`)：我用之前任务的报酬从艾什柏环岛的地下黑市买了一些饰品
- **狼卫** (`sns_chr_0006_wolfgd`, `contentId=13; pre=12; next=14`)：外加一柄镶嵌了四种水晶的古董匕首。
- **管理员（选项）** (`option_sns_topic_chr_0006_wolfgd_2_3_001`, `from=14`)：还有其他选择吗？ -> contentId 15
- **管理员** (`endmin`, `contentId=15; pre=14; next=16`)：还有其他选择吗？比如她喜欢的什么别的东西？
- **狼卫** (`sns_chr_0006_wolfgd`, `contentId=16; pre=15; next=17`)：关于她的喜好，我能确定的只有这些。
- **狼卫** (`sns_chr_0006_wolfgd`, `contentId=17; pre=16; next=18`)：她成长得太快，早将同龄人甩在了身后，哪怕是狼群中的同龄人
- **狼卫** (`sns_chr_0006_wolfgd`, `contentId=18; pre=17; next=19`)：9岁初次狩猎获胜，11岁带队击退了碾骨，13岁完成了第一个雇佣兵任务……
- **狼卫** (`sns_chr_0006_wolfgd`, `contentId=19; pre=18; next=20`)：她独自闯过了许多难关，而我大多时候都没能在场……更别提了解她如今的喜好了。
- **管理员（选项）** (`option_sns_topic_chr_0006_wolfgd_2_4_001`, `from=20`)：你依然以她为傲。 -> contentId 21
- **管理员** (`endmin`, `contentId=21; pre=20; next=22`)：但你依然以她为傲，不是吗？
- **狼卫** (`sns_chr_0006_wolfgd`, `contentId=22; pre=21; next=23`)：是的，她是整个狼群的骄傲。
- **狼卫** (`sns_chr_0006_wolfgd`, `contentId=23; pre=22; next=24`)：只凭一个人反杀数十个碾骨，带着六七个伤员突破包围；腹背受敌时当机立断，抢先一步占据制高点……类似的事，她做过太多
- **狼卫** (`sns_chr_0006_wolfgd`, `contentId=24; pre=23; next=25`)：她已经成为了真正的“狼珀”，卢皮诺家族最珍贵的宝物。
- **管理员（选项）** (`option_sns_topic_chr_0006_wolfgd_2_5_001`, `from=25`)：我知道你该送什么了。 -> contentId 26
- **管理员（选项）** (`option_sns_topic_chr_0006_wolfgd_2_5_002`, `from=25`)：礼物或许没那么重要。 -> contentId 27
- **管理员** (`endmin`, `contentId=26; pre=25; next=28`)：我想我知道你该送什么“礼物”作为赔礼了……不是什么精致的刀具，也不是什么华丽的饰品。
- **管理员** (`endmin`, `contentId=27; pre=25; next=28`)：对洛茜来说，礼物或许没那么重要。
- **管理员** (`endmin`, `contentId=28; pre=27; next=29`)：你真正该做的应该是——立刻去见她，陪她说说话。面对家人，你可以更坦诚点。
- **狼卫** (`sns_chr_0006_wolfgd`, `contentId=29; pre=28; next=30`)：……
- **狼卫** (`sns_chr_0006_wolfgd`, `contentId=30; pre=29; next=31`)：我明白了。
- **狼卫** (`sns_chr_0006_wolfgd`, `contentId=31; pre=30; next=-1`)：感谢你的建议，管理员。我需要一些时间……认真考虑一下。
