---
category: "Baker"
title: "过度保护"
slug: "coddling"
source_url: "https://warfarin.wiki/cn/baker/coddling"
game_data_version: "1.2"
warfarin_updated_at: "2026-04-17"
fetched_at: "2026-04-21T19:50:46+08:00"
---


# 过度保护

## 基本信息

- 类别：Baker
- Slug：`coddling`
- 来源：[Warfarin Wiki](https://warfarin.wiki/cn/baker/coddling)
- 数据版本：`1.2`
- Warfarin 最后更新：`2026-04-17`
- 采集时间：`2026-04-21T19:50:46+08:00`
- ID：`topic_chr_0020_meurs_3`
- 包含会话：`sns_topic_chr_0020_meurs_3`

## 会话

- `sns_topic_chr_0020_meurs_3`：卡契尔（chatId: `sns_chr_0020_meurs`）

## 角色表

- `sns_chr_0020_meurs`：卡契尔
- `endmin`：管理员

## 全分支文本

### sns_topic_chr_0020_meurs_3 - 卡契尔

- （空节点 `contentId=-1`，next=0）
- **卡契尔** (`sns_chr_0020_meurs`, `contentId=1; pre=0; next=2`)：管理员，根据上次训练的情况，我写了一份《Z7作战方案个人调整建议》，希望可以帮到你。
- **Unknown** (``, `contentId=2; pre=1; next=3`)：文件[终末地干员个人携带危险物品报备表]已接收
- **卡契尔** (`sns_chr_0020_meurs`, `contentId=3; pre=2; next=4`)：抱歉，发错文件了……稍等。
- **管理员（选项）** (`option_sns_topic_chr_0020_meurs_3_1_001`, `from=4`)：这是什么？ -> contentId 5
- **管理员（选项）** (`option_sns_topic_chr_0020_meurs_3_1_002`, `from=4`)：“危险物品”？ -> contentId 6
- **管理员** (`endmin`, `contentId=5; pre=4; next=7`)：这是什么？你带了危险物品过来？
- **管理员** (`endmin`, `contentId=6; pre=4; next=7`)：危险物品？卡契尔，你这是打算……？
- **卡契尔** (`sns_chr_0020_meurs`, `contentId=7; pre=6; next=8`)：管理员不是,】dg/;ay【。
- **卡契尔** (`sns_chr_0020_meurs`, `contentId=8; pre=7; next=9`)：对不起，刚刚不小心打翻了水壶。
- **管理员（选项）** (`option_sns_topic_chr_0020_meurs_3_2_001`, `from=9`)：图片选项：sns_emoji_003 -> contentId 10
- **管理员（选项）** (`option_sns_topic_chr_0020_meurs_3_2_002`, `from=9`)：图片选项：sns_emoji_010 -> contentId 10
- **管理员（选项）** (`option_sns_topic_chr_0020_meurs_3_2_003`, `from=9`)：图片选项：sns_emoji_013 -> contentId 10
- **卡契尔** (`sns_chr_0020_meurs`, `contentId=10; pre=9; next=11`)：是我大哥，他给我寄的礼物……有些危险。
- **卡契尔** (`sns_chr_0020_meurs`, `contentId=11; pre=10; next=12`)：好像是商会新上市的一款炸弹无人机。我也是收到后才发现，原来这就是他通信里说的“惊喜”……
- **卡契尔** (`sns_chr_0020_meurs`, `contentId=12; pre=11; next=13`)：本来可以先口头和队长报备，之后有空再填写表格的，但我之前好几次都因为赶着出任务，没能及时登记……
- **卡契尔** (`sns_chr_0020_meurs`, `contentId=13; pre=12; next=14`)：队长和我说，这次要是再不及时登记，我可能会上武库的黑名单。
- **管理员（选项）** (`option_sns_topic_chr_0020_meurs_3_3_001`, `from=14`)：好几次？ -> contentId 15
- **管理员（选项）** (`option_sns_topic_chr_0020_meurs_3_3_002`, `from=14`)：还有多少“惊喜”？ -> contentId 17
- **管理员** (`endmin`, `contentId=15; pre=14; next=16`)：好几次？那些没来得及登记的物品，难道全是你家人给你的礼物？
- **卡契尔** (`sns_chr_0020_meurs`, `contentId=16; pre=15; next=19`)：对……全都是。
- **管理员** (`endmin`, `contentId=17; pre=14; next=18`)：你家人到底给你准备了多少“惊喜”啊……
- **卡契尔** (`sns_chr_0020_meurs`, `contentId=18; pre=17; next=19`)：可能……还挺多的。
- **卡契尔** (`sns_chr_0020_meurs`, `contentId=19; pre=18; next=20`)：有一些是商会的新式武器，还有一些是塞什卡的巫术制品……
- **卡契尔** (`sns_chr_0020_meurs`, `contentId=20; pre=19; next=21`)：最夸张的大概是上回二姐送给我的外骨骼，把当时负责的负责物流的后勤干员都给吓到了。
- **卡契尔** (`sns_chr_0020_meurs`, `contentId=21; pre=20; next=22`)：我后来也有写信给他们，让他们稍微注意一点礼物的……惊吓性。但他们好像都不觉得这些东西有多危险……
- **卡契尔** (`sns_chr_0020_meurs`, `contentId=22; pre=21; next=23`)：虽然我猜是那场让我患上矿石病的意外让他们有了阴影，但这种过度的保护，很多时候也让我有些为难……
- **卡契尔** (`sns_chr_0020_meurs`, `contentId=23; pre=22; next=24`)：就好像在他们眼里，我一直都还没长大似的。
- **管理员（选项）** (`option_sns_topic_chr_0020_meurs_3_4_001`, `from=24`)：因为是家人。 -> contentId 25
- **管理员（选项）** (`option_sns_topic_chr_0020_meurs_3_4_002`, `from=24`)：大家都很在乎你。 -> contentId 27
- **管理员** (`endmin`, `contentId=25; pre=24; next=26`)：因为他们是你的家人。
- **管理员** (`endmin`, `contentId=26; pre=25; next=30`)：对于珍视的家人，他们会担忧自己给予的关怀是否足够。
- **管理员** (`endmin`, `contentId=27; pre=24; next=28`)：其实不只你的家人，很多在你身边的人也像他们那样在乎你，比如Z7的大家。
- **管理员** (`endmin`, `contentId=28; pre=27; next=29`)：上回秋栗就因为担心你会勉强自己，调整了工作安排；安塔尔也不止一次询问过逗你笑的窍门……
- **管理员** (`endmin`, `contentId=29; pre=28; next=30`)：他们都想用自己的方式给予你一份关心，我也不例外。
- **管理员** (`endmin`, `contentId=30; pre=29; next=31`)：这么一说，我都想送你一份礼物了。比如特种技术部门最新配备的辅助装备组，怎么样？
- **卡契尔** (`sns_chr_0020_meurs`, `contentId=31; pre=30; next=32`)：管理员……你怎么也……
- **管理员（选项）** (`option_sns_topic_chr_0020_meurs_3_5_001`, `from=32`)：嗯？我怎么了？ -> contentId 33
- **管理员** (`endmin`, `contentId=33; pre=32; next=34`)：嗯？我怎么了？有什么不对吗？
- **卡契尔** (`sns_chr_0020_meurs`, `contentId=34; pre=33; next=35`)：没什么。就是……我找到正确的文件了，你记得看……
- **卡契尔** (`sns_chr_0020_meurs`, `contentId=35; pre=34; next=36`)：我……我先去训练了……
- **Unknown** (``, `contentId=36; pre=35; next=-1`)：文件[Z7作战方案个人调整建议]已接收
