---
category: "Baker"
title: "到塞梦珂去"
slug: "to-simonch"
source_url: "https://warfarin.wiki/cn/baker/to-simonch"
game_data_version: "1.2"
warfarin_updated_at: "2026-04-17"
fetched_at: "2026-04-21T19:50:46+08:00"
---


# 到塞梦珂去

## 基本信息

- 类别：Baker
- Slug：`to-simonch`
- 来源：[Warfarin Wiki](https://warfarin.wiki/cn/baker/to-simonch)
- 数据版本：`1.2`
- Warfarin 最后更新：`2026-04-17`
- 采集时间：`2026-04-21T19:50:46+08:00`
- ID：`topic_chr_0029_pograni_3`
- 包含会话：`sns_topic_chr_0029_pograni_3`

## 会话

- `sns_topic_chr_0029_pograni_3`：骏卫（chatId: `sns_chr_0029_pograni`）

## 角色表

- `sns_chr_0029_pograni`：骏卫
- `endmin`：管理员

## 全分支文本

### sns_topic_chr_0029_pograni_3 - 骏卫

- （空节点 `contentId=-1`，next=0）
- **骏卫** (`sns_chr_0029_pograni`, `contentId=1; pre=0; next=2`)：管理员，你现在有空吗？
- **管理员（选项）** (`option_sns_topic_chr_0029_pograni_3_1_001`, `from=2`)：有空。 -> contentId 3
- **管理员（选项）** (`option_sns_topic_chr_0029_pograni_3_1_002`, `from=2`)：难道说…… -> contentId 4
- **管理员** (`endmin`, `contentId=3; pre=2; next=5`)：有空，怎么了？
- **管理员** (`endmin`, `contentId=4; pre=2; next=5`)：难道说……是故事时间？
- **骏卫** (`sns_chr_0029_pograni`, `contentId=5; pre=4; next=6`)：刚才我在整理以前做的笔记时，记起了一些往事。
- **骏卫** (`sns_chr_0029_pograni`, `contentId=6; pre=5; next=7`)：不知道管理员是否有兴趣。
- **管理员（选项）** (`option_sns_topic_chr_0029_pograni_3_2_001`, `from=7`)：好哇。 -> contentId 8
- **管理员（选项）** (`option_sns_topic_chr_0029_pograni_3_2_002`, `from=7`)：我喜欢听故事。 -> contentId 10
- **管理员** (`endmin`, `contentId=8; pre=7; next=9`)：好哇，是铁誓军的作战行动吗？
- **骏卫** (`sns_chr_0029_pograni`, `contentId=9; pre=8; next=11`)：不，是一场梦。
- **管理员** (`endmin`, `contentId=10; pre=7; next=11`)：嗯，我喜欢听故事。
- **骏卫** (`sns_chr_0029_pograni`, `contentId=11; pre=10; next=12`)：当我第一次乘上前往塞梦珂的车时，曾见过一场梦境。
- **骏卫** (`sns_chr_0029_pograni`, `contentId=12; pre=11; next=13`)：梦里的我，站在一个插满刀剑的战场上。战场中央，一片废墟静静地立在那里。
- **骏卫** (`sns_chr_0029_pograni`, `contentId=13; pre=12; next=14`)：内心突然涌现的悲伤促使着我离开那里，但我的身体却不由自主地走了进去。
- **管理员（选项）** (`option_sns_topic_chr_0029_pograni_3_3_001`, `from=14`)：然后呢？ -> contentId 15
- **管理员（选项）** (`option_sns_topic_chr_0029_pograni_3_3_002`, `from=14`)：好奇怪的梦…… -> contentId 16
- **管理员** (`endmin`, `contentId=15; pre=14; next=17`)：然后怎样了？
- **管理员** (`endmin`, `contentId=16; pre=14; next=17`)：好奇怪的梦……然后怎样了？
- **骏卫** (`sns_chr_0029_pograni`, `contentId=17; pre=16; next=18`)：在废墟的深处，我见到了记忆里的那栋建筑，一个只剩名字的地方。
- **骏卫** (`sns_chr_0029_pograni`, `contentId=18; pre=17; next=19`)：阿撒兹勒。
- **骏卫** (`sns_chr_0029_pograni`, `contentId=19; pre=18; next=20`)：看着那扇我好像推开过无数次的门，我试图伸出手，却始终无法触及。
- **骏卫** (`sns_chr_0029_pograni`, `contentId=20; pre=19; next=21`)：我在门口徘徊了许久，无法离开，也无法对它的存在做出回应。
- **骏卫** (`sns_chr_0029_pograni`, `contentId=21; pre=20; next=22`)：就在这时，一阵吱呀声传来，诊所的门被缓缓拉开。
- **骏卫** (`sns_chr_0029_pograni`, `contentId=22; pre=21; next=23`)：在那片废墟中，我见到了他，还有那个女孩……他的养女。我并不感到意外，正要穿过那扇门……
- **骏卫** (`sns_chr_0029_pograni`, `contentId=23; pre=22; next=24`)：到站的播报将我唤醒，此行的目的地已在眼前。
- **管理员（选项）** (`option_sns_topic_chr_0029_pograni_3_4_002`, `from=24`)：还会梦到那扇门吗？ -> contentId 25
- **管理员** (`endmin`, `contentId=25; pre=24; next=26`)：在这之后，你尝试过在梦里继续寻找那扇门吗？
- **骏卫** (`sns_chr_0029_pograni`, `contentId=26; pre=25; next=27`)：这场梦就像是在旅途中遇见了许久未见的挚友，听他向我诉说着他的往事，直到终点。
- **骏卫** (`sns_chr_0029_pograni`, `contentId=27; pre=26; next=-1`)：在那之后，我便再也没有见过那一扇门。
