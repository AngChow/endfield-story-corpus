---
category: "Baker"
title: "与侵蚀赛跑"
slug: "racing-the-blight"
source_url: "https://warfarin.wiki/cn/baker/racing-the-blight"
game_data_version: "1.2"
warfarin_updated_at: "2026-04-17"
fetched_at: "2026-04-21T19:50:46+08:00"
---


# 与侵蚀赛跑

## 基本信息

- 类别：Baker
- Slug：`racing-the-blight`
- 来源：[Warfarin Wiki](https://warfarin.wiki/cn/baker/racing-the-blight)
- 数据版本：`1.2`
- Warfarin 最后更新：`2026-04-17`
- 采集时间：`2026-04-21T19:50:46+08:00`
- ID：`topic_chr_0025_ardelia_3`
- 包含会话：`sns_topic_chr_0025_ardelia_3`

## 会话

- `sns_topic_chr_0025_ardelia_3`：艾尔黛拉（chatId: `sns_chr_ardelia`）

## 角色表

- `sns_chr_ardelia`：艾尔黛拉
- `endmin`：管理员

## 全分支文本

### sns_topic_chr_0025_ardelia_3 - 艾尔黛拉

- （空节点 `contentId=-1`，next=0）
- **艾尔黛拉** (`sns_chr_ardelia`, `contentId=1; pre=0; next=2`)：前辈，有空吗？
- **管理员（选项）** (`option_sns_topic_chr_0025_ardelia_3_1_001`, `from=2`)：我在，有什么事？ -> contentId 3
- **管理员** (`endmin`, `contentId=3; pre=2; next=4`)：我在，有什么事？
- **艾尔黛拉** (`sns_chr_ardelia`, `contentId=4; pre=3; next=5`)：我刚做了一个噩梦……但身边没有能倾诉的人。
- **管理员（选项）** (`option_sns_topic_chr_0025_ardelia_3_2_001`, `from=5`)：没事的，跟我说说吧。 -> contentId 6
- **管理员** (`endmin`, `contentId=6; pre=5; next=7`)：没事的，跟我说说吧。
- **艾尔黛拉** (`sns_chr_ardelia`, `contentId=7; pre=6; next=8`)：我梦见在采样完，分析数据的时候，没注意一个重要参数。
- **艾尔黛拉** (`sns_chr_ardelia`, `contentId=8; pre=7; next=9`)：结果，侵蚀沿着断层蔓延，从火山喷发开始，接着是整个塔卫二的地层断裂……最后，星球陷入崩解。
- **管理员（选项）** (`option_sns_topic_chr_0025_ardelia_3_3_001`, `from=9`)：这只是梦。 -> contentId 10
- **管理员（选项）** (`option_sns_topic_chr_0025_ardelia_3_3_002`, `from=9`)：梦都是反着来的。 -> contentId 11
- **管理员** (`endmin`, `contentId=10; pre=9; next=12`)：别怕，这只是梦。
- **管理员** (`endmin`, `contentId=11; pre=9; next=12`)：别怕，梦都是反着来的。
- **艾尔黛拉** (`sns_chr_ardelia`, `contentId=12; pre=11; next=13`)：前辈说得对……至少现在还没有发生，我们还有时间。
- **管理员（选项）** (`option_sns_topic_chr_0025_ardelia_3_4_001`, `from=13`)：你想做什么？ -> contentId 14
- **管理员** (`endmin`, `contentId=14; pre=13; next=15`)：你想做什么？
- **艾尔黛拉** (`sns_chr_ardelia`, `contentId=15; pre=14; next=16`)：计算清楚这种可能性是否存在。
- **艾尔黛拉** (`sns_chr_ardelia`, `contentId=16; pre=15; next=17`)：趁现在脑子最清醒，可以好好思考一下应对方案。
- **管理员（选项）** (`option_sns_topic_chr_0025_ardelia_3_5_001`, `from=17`)：好，我陪你。 -> contentId 18
- **管理员** (`endmin`, `contentId=18; pre=17; next=19`)：好，我会保持在线陪你。
- **艾尔黛拉** (`sns_chr_ardelia`, `contentId=19; pre=18; next=20`)：谢谢前辈，有你在，我安心多了。
- **艾尔黛拉** (`sns_chr_ardelia`, `contentId=20; pre=19; next=21`)：前辈，你还在吗？
- **管理员（选项）** (`option_sns_topic_chr_0025_ardelia_3_6_001`, `from=21`)：有结果了？ -> contentId 22
- **管理员** (`endmin`, `contentId=22; pre=21; next=23`)：有结果了吗？
- **艾尔黛拉** (`sns_chr_ardelia`, `contentId=23; pre=22; next=24`)：嗯，我套入最近四周的火山活动频率与地壳扰动数据，如果侵蚀沿着裂隙带持续扩散，引发大规模火山与地震灾害的概率是1.7%。
- **管理员（选项）** (`option_sns_topic_chr_0025_ardelia_3_7_001`, `from=24`)：看来不高。 -> contentId 25
- **管理员** (`endmin`, `contentId=25; pre=24; next=26`)：这看起来不算高，是不是能松一口气了？
- **艾尔黛拉** (`sns_chr_ardelia`, `contentId=26; pre=25; next=27`)：不，这个概率已经很可怕了。
- **艾尔黛拉** (`sns_chr_ardelia`, `contentId=27; pre=26; next=28`)：天亮后可能得拜托铁誓军再派小队护送我往北走，重新勘察几个地裂深处的活动点。
- **管理员（选项）** (`option_sns_topic_chr_0025_ardelia_3_8_001`, `from=28`)：你在铁誓军那里？ -> contentId 29
- **管理员** (`endmin`, `contentId=29; pre=28; next=30`)：什么？你在铁誓军那里？
- **艾尔黛拉** (`sns_chr_ardelia`, `contentId=30; pre=29; next=31`)：是呀！我今年的主要研究计划，是前往北部冰原，考察超域活动最剧烈的表现和状况。
- **艾尔黛拉** (`sns_chr_ardelia`, `contentId=31; pre=30; next=32`)：这里的天气很极端，但铁誓军的人似乎都很适应……他们看起来性格冷峻，有时还让人觉得难以接近，但都很可靠。
- **管理员（选项）** (`option_sns_topic_chr_0025_ardelia_3_9_001`, `from=32`)：有他们帮忙真是太好了。 -> contentId 33
- **管理员** (`endmin`, `contentId=33; pre=32; next=34`)：有铁誓军帮忙那就太好了，他们是可靠的朋友。
- **艾尔黛拉** (`sns_chr_ardelia`, `contentId=34; pre=33; next=35`)：嗯嗯！除了他们，一路上我还遇到了联盟工团的矿工、众生长地的游人，还有环塔商会的车队。
- **艾尔黛拉** (`sns_chr_ardelia`, `contentId=35; pre=34; next=36`)：他们一听说我是终末地的地质研究人员，都主动提出要协助。
- **管理员（选项）** (`option_sns_topic_chr_0025_ardelia_3_10_001`, `from=36`)：所有人都在一起努力。 -> contentId 37
- **管理员** (`endmin`, `contentId=37; pre=36; next=38`)：侵蚀是我们共同的敌人，所有人都会一起努力对抗它。
- **艾尔黛拉** (`sns_chr_ardelia`, `contentId=38; pre=37; next=39`)：对了，前辈，这次我收集了不少珍贵的样本，也做了一些初步分析，等回到帝江号，和你一起深入研讨。
- **艾尔黛拉** (`sns_chr_ardelia`, `contentId=39; pre=38; next=40`)：我真的希望，这一切能尽快取得突破。因为塔卫二上侵蚀的规模，比我们想象的大得多。
- **艾尔黛拉** (`sns_chr_ardelia`, `contentId=40; pre=39; next=41`)：而且它不像火山。火山虽然令人畏惧，却也充满生命的力量。侵蚀没有，它只有枯萎和死亡的气息。
- **艾尔黛拉** (`sns_chr_ardelia`, `contentId=41; pre=40; next=42`)：所以我只能拼尽全力和它赛跑。
- **管理员（选项）** (`option_sns_topic_chr_0025_ardelia_3_11_001`, `from=42`)：我也是。 -> contentId 43
- **管理员** (`endmin`, `contentId=43; pre=42; next=44`)：我也是。只要你还在奔跑，我也不会停下来。
- **艾尔黛拉** (`sns_chr_ardelia`, `contentId=44; pre=43; next=45`)：![sns_emoji_037](https://static.warfarin.wiki/v4/reading/sns_emoji_037.webp)
- **管理员（选项）** (`option_sns_topic_chr_0025_ardelia_3_12_001`, `from=45`)：图片选项：sns_emoji_037 -> contentId -1
