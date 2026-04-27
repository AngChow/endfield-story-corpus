---
category: "Baker"
title: "祖泉与清波"
slug: "ancestral-spring-and-qingbo"
source_url: "https://warfarin.wiki/cn/baker/ancestral-spring-and-qingbo"
game_data_version: "1.2"
warfarin_updated_at: "2026-04-17"
fetched_at: "2026-04-21T19:50:46+08:00"
---


# 祖泉与清波

## 基本信息

- 类别：Baker
- Slug：`ancestral-spring-and-qingbo`
- 来源：[Warfarin Wiki](https://warfarin.wiki/cn/baker/ancestral-spring-and-qingbo)
- 数据版本：`1.2`
- Warfarin 最后更新：`2026-04-17`
- 采集时间：`2026-04-21T19:50:46+08:00`
- ID：`topic_map02_lv003_11002`
- 包含会话：`sns_topic_map02_lv003_4`、`sns_topic_map02_lv003_5`

## 会话

- `sns_topic_map02_lv003_4`：弭弗（chatId: `sns_npc_mifu`）
- `sns_topic_map02_lv003_5`：佩丽卡（chatId: `sns_chr_0004_pelica`）

## 角色表

- `sns_chr_0004_pelica`：佩丽卡：工作用联系B42转分机号****。看到消息一定会回复，若未回复请再敲一次。
- `sns_npc_mifu`：弭弗
- `endmin`：管理员

## 全分支文本

### sns_topic_map02_lv003_4 - 弭弗

- （空节点 `contentId=-1`，next=0）
- **弭弗** (`sns_npc_mifu`, `contentId=1; pre=0; next=2`)：管理员，我送了些物资，顺便来寨子看看
- **弭弗** (`sns_npc_mifu`, `contentId=2; pre=1; next=3`)：听寨民们说你们去祖泉了
- **管理员（选项）** (`option_sns_topic_map02_lv003_4_1_001`, `from=3`)：什么物资？ -> contentId 4
- **管理员** (`endmin`, `contentId=4; pre=3; next=5`)：对，我们刚来祖泉。是些什么物资？
- **弭弗** (`sns_npc_mifu`, `contentId=5; pre=4; next=6`)：给寨民们的应急食物和药品，头儿让我放到储备站
- **弭弗** (`sns_npc_mifu`, `contentId=6; pre=5; next=7`)：祖泉现在怎么样了
- **管理员（选项）** (`option_sns_topic_map02_lv003_4_2_001`, `from=7`)：受损严重。 -> contentId 8
- **管理员（选项）** (`option_sns_topic_map02_lv003_4_2_002`, `from=7`)：杜鸣很惊讶。 -> contentId 9
- **管理员** (`endmin`, `contentId=8; pre=7; next=10`)：阮一造成的破坏，对祖泉周围环境的影响很大。
- **管理员** (`endmin`, `contentId=9; pre=7; next=10`)：不太好……杜鸣看见都被吓坏了。
- **弭弗** (`sns_npc_mifu`, `contentId=10; pre=9; next=11`)：以前总听老人们说，祖泉保佑着清波寨的每一个人
- **弭弗** (`sns_npc_mifu`, `contentId=11; pre=10; next=12`)：那里是清波寨的立寨之本，是最重要的地方
- **弭弗** (`sns_npc_mifu`, `contentId=12; pre=11; next=13`)：祭拜先人，庆祝节日，寨民们都会在祖泉集会
- **弭弗** (`sns_npc_mifu`, `contentId=13; pre=12; next=14`)：我直到现在也不明白，为什么阮一要选在那里动手
- **管理员（选项）** (`option_sns_topic_map02_lv003_4_3_001`, `from=14`)：祖泉会保佑寨民？ -> contentId 15
- **管理员** (`endmin`, `contentId=15; pre=14; next=16`)：祖泉真的会保佑寨民吗？
- **弭弗** (`sns_npc_mifu`, `contentId=16; pre=15; next=17`)：嗯，十年前，我亲眼看到侵蚀潮涌向寨子，但清波寨挺住了
- **弭弗** (`sns_npc_mifu`, `contentId=17; pre=16; next=18`)：当时的守泉人说，这是祖泉下的先人们在保佑我们
- **弭弗** (`sns_npc_mifu`, `contentId=18; pre=17; next=19`)：来武陵这么久，我早就不相信什么没来由的护佑了
- **弭弗** (`sns_npc_mifu`, `contentId=19; pre=18; next=-1`)：我不是天师，但我知道，祖泉一定非常特别

### sns_topic_map02_lv003_5 - 佩丽卡

- （空节点 `contentId=-1`，next=0）
- **佩丽卡** (`sns_chr_0004_pelica`, `contentId=1; pre=0; next=2`)：管理员，真没想到，祖泉泉源居然有炎国天师留下的装置。
- **管理员（选项）** (`option_sns_topic_map02_lv003_5_1_001`, `from=2`)：有点意外。 -> contentId 3
- **管理员（选项）** (`option_sns_topic_map02_lv003_5_1_002`, `from=2`)：果然有一台装置。 -> contentId 4
- **管理员** (`endmin`, `contentId=3; pre=2; next=5`)：嗯，确实有点意外。
- **管理员** (`endmin`, `contentId=4; pre=2; next=5`)：嗯，我隐约有些猜测，只是没想到是炎国天师留下的。
- **管理员（选项）** (`option_sns_topic_map02_lv003_5_2_001`, `from=5`)：泰拉的技术很精妙。 -> contentId 6
- **管理员** (`endmin`, `contentId=6; pre=5; next=7`)：很精妙的设计，几乎只靠水流本身的势能就能运行……泰拉的科技真的很精妙。
- **佩丽卡** (`sns_chr_0004_pelica`, `contentId=7; pre=6; next=8`)：嗯，目前塔卫二的很多技术，都是基于泰拉的技术遗产衍生出来的。
- **佩丽卡** (`sns_chr_0004_pelica`, `contentId=8; pre=7; next=9`)：但像这座装置，一百多年前就已经有了这么巧妙的设计……
- **管理员（选项）** (`option_sns_topic_map02_lv003_5_3_001`, `from=9`)：关于其他泰拉技术遗产。 -> contentId 10
- **管理员** (`endmin`, `contentId=10; pre=9; next=11`)：如果是宏科院和寂语修会的话，应该还保存着不少一百五十二年前的泰拉技术遗产。
- **佩丽卡** (`sns_chr_0004_pelica`, `contentId=11; pre=10; next=12`)：终末地也持有相当一部分的技术遗产，但不知道塔卫二的其他地方还能不能看到更多像这样的装置。
- **佩丽卡** (`sns_chr_0004_pelica`, `contentId=12; pre=11; next=13`)：不过，希望不要再有更多像寨民们这样深陷困境的人们了。
- **管理员（选项）** (`option_sns_topic_map02_lv003_5_4_001`, `from=13`)：辛苦杜鸣了。 -> contentId 14
- **管理员** (`endmin`, `contentId=14; pre=13; next=15`)：为了寨民们能够开始依靠自己，依靠心中的祖泉，辛苦杜鸣了。
- **佩丽卡** (`sns_chr_0004_pelica`, `contentId=15; pre=14; next=-1`)：希望清波寨能够早日适应不再依赖祖泉维生的日子。
