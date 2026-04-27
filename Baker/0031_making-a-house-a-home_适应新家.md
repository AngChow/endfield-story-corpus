---
category: "Baker"
title: "适应新家"
slug: "making-a-house-a-home"
source_url: "https://warfarin.wiki/cn/baker/making-a-house-a-home"
game_data_version: "1.2"
warfarin_updated_at: "2026-04-17"
fetched_at: "2026-04-21T19:50:46+08:00"
---


# 适应新家

## 基本信息

- 类别：Baker
- Slug：`making-a-house-a-home`
- 来源：[Warfarin Wiki](https://warfarin.wiki/cn/baker/making-a-house-a-home)
- 数据版本：`1.2`
- Warfarin 最后更新：`2026-04-17`
- 采集时间：`2026-04-21T19:50:46+08:00`
- ID：`topic_chr_0016_laevat_1`
- 包含会话：`sns_topic_chr_0016_laevat_1`

## 会话

- `sns_topic_chr_0016_laevat_1`：莱万汀（chatId: `sns_chr_0016_laevat`）

## 角色表

- `sns_chr_0016_laevat`：莱万汀：少说废话。
- `endmin`：管理员

## 全分支文本

### sns_topic_chr_0016_laevat_1 - 莱万汀

- （空节点 `contentId=-2`，next=0）
- （空节点 `contentId=-1`，next=0）
- **管理员（选项）** (`option_sns_topic_chr_0016_laevat_1_1_001`, `from=1`)：在终末地感觉如何？ -> contentId 2
- **管理员** (`endmin`, `contentId=2; pre=1; next=3`)：刚来终末地，感觉如何？待得惯吗？
- **莱万汀** (`sns_chr_0016_laevat`, `contentId=3; pre=2; next=4`)：嗯？这是什么？
- **管理员（选项）** (`option_sns_topic_chr_0016_laevat_1_2_001`, `from=4`)：是Baker。 -> contentId 5
- **管理员** (`endmin`, `contentId=5; pre=4; next=6`)：是Baker，一个即时通信应用。每个干员都会自动绑定一个账号。
- **管理员** (`endmin`, `contentId=6; pre=5; next=7`)：你随时可以用它来找我。
- **莱万汀** (`sns_chr_0016_laevat`, `contentId=7; pre=6; next=8`)：好，我记住了。
- **莱万汀** (`sns_chr_0016_laevat`, `contentId=8; pre=7; next=9`)：那么，烧了训练室怎么办？
- **管理员（选项）** (`option_sns_topic_chr_0016_laevat_1_3_001`, `from=9`)：我知道。 -> contentId 10
- **管理员（选项）** (`option_sns_topic_chr_0016_laevat_1_3_002`, `from=9`)：没事的。 -> contentId 11
- **管理员** (`endmin`, `contentId=10; pre=9; next=12`)：我知道。
- **管理员** (`endmin`, `contentId=11; pre=9; next=12`)：没事的。
- **管理员** (`endmin`, `contentId=12; pre=11; next=13`)：我看了你的战斗适应性测试报告，知道高温让训练室遭到了一些损坏。
- **管理员** (`endmin`, `contentId=13; pre=12; next=14`)：交给特种技术部门和总后勤办事处好了，他们会善后的。放心，这种事对终末地来说并不少见。
- **莱万汀** (`sns_chr_0016_laevat`, `contentId=14; pre=13; next=15`)：好。那我接着去烧训练泳池了。
- **管理员（选项）** (`option_sns_topic_chr_0016_laevat_1_4_001`, `from=15`)：为什么要烧训练泳池？ -> contentId 16
- **管理员（选项）** (`option_sns_topic_chr_0016_laevat_1_4_002`, `from=15`)：禁止水煮干员！ -> contentId 17
- **管理员** (`endmin`, `contentId=16; pre=15; next=18`)：为什么要烧训练泳池？
- **管理员** (`endmin`, `contentId=17; pre=15; next=18`)：一听就很危险！禁止水煮干员！
- **莱万汀** (`sns_chr_0016_laevat`, `contentId=18; pre=17; next=19`)：是武库那边的干员要求的。
- **莱万汀** (`sns_chr_0016_laevat`, `contentId=19; pre=18; next=20`)：她想要试试我的火焰在水里会怎么样。
- **管理员（选项）** (`option_sns_topic_chr_0016_laevat_1_5_001`, `from=20`)：图片选项：sns_emoji_007 -> contentId 21
- **管理员（选项）** (`option_sns_topic_chr_0016_laevat_1_6_001`, `from=21`)：那也不能烧游泳池！ -> contentId 22
- **管理员（选项）** (`option_sns_topic_chr_0016_laevat_1_6_002`, `from=21`)：等等，我还没批准呢！ -> contentId 23
- **管理员** (`endmin`, `contentId=22; pre=21; next=24`)：那也不能烧游泳池！
- **管理员** (`endmin`, `contentId=23; pre=21; next=24`)：等等，我还没批准呢！
- **莱万汀** (`sns_chr_0016_laevat`, `contentId=24; pre=23; next=25`)：是吗？她说管理员一定会兜着的，难得现在泳池没人，催我赶紧过去了。
- **莱万汀** (`sns_chr_0016_laevat`, `contentId=25; pre=24; next=26`)：她还说，稍后会把报告送到的。
- **管理员（选项）** (`option_sns_topic_chr_0016_laevat_1_7_001`, `from=26`)：喂喂！ -> contentId 27
- **管理员** (`endmin`, `contentId=27; pre=26; next=28`)：喂喂！
- **管理员（选项）** (`option_sns_topic_chr_0016_laevat_1_8_001`, `from=28`)：喂！ -> contentId 29
- **管理员** (`endmin`, `contentId=29; pre=28; next=30`)：喂！
- **管理员（选项）** (`option_sns_topic_chr_0016_laevat_1_9_001`, `from=30`)：…… -> contentId 31
- **管理员** (`endmin`, `contentId=31; pre=30; next=32`)：……
- **Unknown** (``, `contentId=32; pre=31; next=33`)：新消息
- **莱万汀** (`sns_chr_0016_laevat`, `contentId=33; pre=32; next=34`)：你觉得在音乐节上纵火合适吗？
- **管理员（选项）** (`option_sns_topic_chr_0016_laevat_1_10_001`, `from=34`)：图片选项：sns_emoji_032 -> contentId 35
- **管理员（选项）** (`option_sns_topic_chr_0016_laevat_1_11_001`, `from=35`)：这次又是要做什么？ -> contentId 36
- **管理员** (`endmin`, `contentId=36; pre=35; next=37`)：这次又是要做什么？
- **莱万汀** (`sns_chr_0016_laevat`, `contentId=37; pre=36; next=38`)：上次外勤行动后，一位干员联系我，说是对我的火焰印象深刻。
- **管理员（选项）** (`option_sns_topic_chr_0016_laevat_1_12_001`, `from=38`)：然后呢？ -> contentId 39
- **管理员** (`endmin`, `contentId=39; pre=38; next=40`)：不止一个人跟我提到过这点……然后呢？
- **莱万汀** (`sns_chr_0016_laevat`, `contentId=40; pre=39; next=41`)：她邀请我加入她的业余重金属乐队，在下一场黑曜石音乐节的表演中，用火焰点燃环绕舞台的海水。
- **莱万汀** (`sns_chr_0016_laevat`, `contentId=41; pre=40; next=42`)：觉得这个主意怎么样？
- **管理员（选项）** (`option_sns_topic_chr_0016_laevat_1_13_001`, `from=42`)：我很期待。 -> contentId 43
- **管理员（选项）** (`option_sns_topic_chr_0016_laevat_1_13_002`, `from=42`)：有点出格。 -> contentId 44
- **管理员** (`endmin`, `contentId=43; pre=42; next=45`)：听上去酷毙了！我很期待！
- **管理员** (`endmin`, `contentId=44; pre=42; next=45`)：挺出格的，不过我支持！
- **莱万汀** (`sns_chr_0016_laevat`, `contentId=45; pre=44; next=46`)：很好。那么到时候记得来支持。
- **莱万汀** (`sns_chr_0016_laevat`, `contentId=46; pre=45; next=47`)：对了，在终末地，我感觉待得很习惯。
- **管理员（选项）** (`option_sns_topic_chr_0016_laevat_1_14_001`, `from=47`)：为什么现在才回答我？ -> contentId 48
- **管理员** (`endmin`, `contentId=48; pre=47; next=49`)：欸……你为什么现在才回答这个问题？
- **莱万汀** (`sns_chr_0016_laevat`, `contentId=49; pre=48; next=50`)：虽然有人告诉我可以把终末地当成自己的家，但我知道自己在很多情况下意味着麻烦。
- **莱万汀** (`sns_chr_0016_laevat`, `contentId=50; pre=49; next=51`)：我可不希望，作为一种麻烦被勉强“接纳”和“包容”。
- **莱万汀** (`sns_chr_0016_laevat`, `contentId=51; pre=50; next=52`)：直到现在，我才确定，这里就是为我这样的人准备的地方。
- **管理员（选项）** (`option_sns_topic_chr_0016_laevat_1_15_001`, `from=52`)：图片选项：sns_emoji_022 -> contentId -1
- **管理员（选项）** (`option_sns_topic_chr_0016_laevat_1_15_002`, `from=52`)：图片选项：sns_emoji_011 -> contentId -2
