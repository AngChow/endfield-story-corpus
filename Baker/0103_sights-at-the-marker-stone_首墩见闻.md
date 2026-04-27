---
category: "Baker"
title: "首墩见闻"
slug: "sights-at-the-marker-stone"
source_url: "https://warfarin.wiki/cn/baker/sights-at-the-marker-stone"
game_data_version: "1.2"
warfarin_updated_at: "2026-04-17"
fetched_at: "2026-04-21T19:50:46+08:00"
---


# 首墩见闻

## 基本信息

- 类别：Baker
- Slug：`sights-at-the-marker-stone`
- 来源：[Warfarin Wiki](https://warfarin.wiki/cn/baker/sights-at-the-marker-stone)
- 数据版本：`1.2`
- Warfarin 最后更新：`2026-04-17`
- 采集时间：`2026-04-21T19:50:46+08:00`
- ID：`topic_map02_lv004_12002`
- 包含会话：`sns_topic_map02_lv004_3`、`sns_topic_map02_lv004_4`

## 会话

- `sns_topic_map02_lv004_3`：佩丽卡（chatId: `sns_chr_0004_pelica`）
- `sns_topic_map02_lv004_4`：庄方宜（chatId: `sns_chr_0030_zhuangfy`）

## 角色表

- `sns_chr_0004_pelica`：佩丽卡：工作用联系B42转分机号****。看到消息一定会回复，若未回复请再敲一次。
- `sns_chr_0030_zhuangfy`：庄方宜
- `endmin`：管理员

## 全分支文本

### sns_topic_map02_lv004_3 - 佩丽卡

- （空节点 `contentId=-2`，next=0）
- （空节点 `contentId=-1`，next=0）
- **管理员** (`endmin`, `contentId=1; pre=0; next=2`)：佩丽卡，你亲眼见过巨兽吗？
- **佩丽卡** (`sns_chr_0004_pelica`, `contentId=2; pre=1; next=3`)：很遗憾，只在终末地的资料上见过。管理员，怎么突然想起问这个？
- **管理员（选项）** (`option_sns_topic_map02_lv004_3_1_001`, `from=3`)：对巨兽心脏很好奇。 -> contentId 4
- **管理员** (`endmin`, `contentId=4; pre=3; next=5`)：看到巨兽心脏后有点好奇，宏科院是怎么创造出这样的造物？
- **佩丽卡** (`sns_chr_0004_pelica`, `contentId=5; pre=4; next=6`)：严格来讲，创造巨兽心脏的，是宏科院天师和巨兽“岁”的代理人。
- **佩丽卡** (`sns_chr_0004_pelica`, `contentId=6; pre=5; next=7`)：巨兽的本体极其庞大，他们往往会创造代理人作为自己的分身。
- **管理员（选项）** (`option_sns_topic_map02_lv004_3_2_001`, `from=7`)：关于这位巨兽代理人。 -> contentId 8
- **管理员** (`endmin`, `contentId=8; pre=7; next=9`)：那这位巨兽代理人，是怎样的一位人物？
- **佩丽卡** (`sns_chr_0004_pelica`, `contentId=9; pre=8; next=10`)：宏科院公布的信息并不多。
- **佩丽卡** (`sns_chr_0004_pelica`, `contentId=10; pre=9; next=11`)：我们所知道的，也只有宏科院与其进行了相当密切的合作。这位代理人直接参与了息壤技术与应龙装备的研发。
- **佩丽卡** (`sns_chr_0004_pelica`, `contentId=11; pre=10; next=12`)：具体是怎样的一位人物，或许得等我们有机会与这位代理人见上一面，才能得知。
- **管理员（选项）** (`option_sns_topic_map02_lv004_3_3_001`, `from=12`)：好奇代理人长什么样。 -> contentId 13
- **管理员（选项）** (`option_sns_topic_map02_lv004_3_3_002`, `from=12`)：期待和代理人见面。 -> contentId 15
- **管理员** (`endmin`, `contentId=13; pre=12; next=14`)：好奇这位代理人究竟长什么样。
- **佩丽卡** (`sns_chr_0004_pelica`, `contentId=14; pre=13; next=-1`)：我也很好奇。
- **管理员** (`endmin`, `contentId=15; pre=12; next=16`)：期待能和这位代理人见面！
- **佩丽卡** (`sns_chr_0004_pelica`, `contentId=16; pre=15; next=-2`)：我也很期待。

### sns_topic_map02_lv004_4 - 庄方宜

- （空节点 `contentId=-1`，next=0）
- **庄方宜** (`sns_chr_0030_zhuangfy`, `contentId=1; pre=0; next=2`)：管理员，先前在首墩的时候，你们没有受伤吧？
- **管理员（选项）** (`option_sns_topic_map02_lv004_4_1_001`, `from=2`)：没有，只是陈很伤心。 -> contentId 3
- **管理员** (`endmin`, `contentId=3; pre=2; next=4`)：没有，只是陈现在很伤心，她很担心诀的处境……
- **庄方宜** (`sns_chr_0030_zhuangfy`, `contentId=4; pre=3; next=5`)：我能理解她的心情，曾经的同僚处于险地，而我们却无能为力。
- **管理员（选项）** (`option_sns_topic_map02_lv004_4_2_001`, `from=5`)：她是为了我…… -> contentId 6
- **管理员** (`endmin`, `contentId=6; pre=5; next=7`)：诀是为了我才冒的险……
- **庄方宜** (`sns_chr_0030_zhuangfy`, `contentId=7; pre=6; next=8`)：我明白，管理员。如果在那儿的是我，我也会这样做。
- **庄方宜** (`sns_chr_0030_zhuangfy`, `contentId=8; pre=7; next=9`)：不必有过多的负担，你能回来，才是最重要的。
- **管理员（选项）** (`option_sns_topic_map02_lv004_4_3_001`, `from=9`)：关于聂菲斯。 -> contentId 10
- **管理员** (`endmin`, `contentId=10; pre=9; next=11`)：我明白的。
- **管理员** (`endmin`, `contentId=11; pre=10; next=12`)：对了，我们并没有在首墩看到任何碾骨氏族的裂地者，他们似乎还有其他打算。
- **庄方宜** (`sns_chr_0030_zhuangfy`, `contentId=12; pre=11; next=13`)：既然如此，他们的真正目的果然还是武陵城。
- **庄方宜** (`sns_chr_0030_zhuangfy`, `contentId=13; pre=12; next=14`)：管理员，我有预感，阿达希尔破坏首墩的行动失败后，碾骨氏族很快就会有新的动作。
- **庄方宜** (`sns_chr_0030_zhuangfy`, `contentId=14; pre=13; next=-1`)：你们也多加小心。
