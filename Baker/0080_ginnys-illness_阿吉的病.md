---
category: "Baker"
title: "阿吉的病"
slug: "ginnys-illness"
source_url: "https://warfarin.wiki/cn/baker/ginnys-illness"
game_data_version: "1.2"
warfarin_updated_at: "2026-04-17"
fetched_at: "2026-04-21T19:50:46+08:00"
---


# 阿吉的病

## 基本信息

- 类别：Baker
- Slug：`ginnys-illness`
- 来源：[Warfarin Wiki](https://warfarin.wiki/cn/baker/ginnys-illness)
- 数据版本：`1.2`
- Warfarin 最后更新：`2026-04-17`
- 采集时间：`2026-04-21T19:50:46+08:00`
- ID：`topic_map01_lv002_3`
- 包含会话：`sns_topic_map01_lv002_5`、`sns_topic_map01_lv002_6`、`sns_topic_map01_lv002_7`

## 会话

- `sns_topic_map01_lv002_5`：佩丽卡（chatId: `sns_chr_0004_pelica`）
- `sns_topic_map01_lv002_6`：狼卫（chatId: `sns_chr_0006_wolfgd`）
- `sns_topic_map01_lv002_7`：陈千语（chatId: `sns_chr_0005_chen`）

## 角色表

- `sns_chr_0004_pelica`：佩丽卡：工作用联系B42转分机号****。看到消息一定会回复，若未回复请再敲一次。
- `sns_chr_0005_chen`：陈千语：德才兼备。
- `sns_chr_0006_wolfgd`：狼卫：正在解决问题或前往问题的路上。
- `endmin`：管理员

## 全分支文本

### sns_topic_map01_lv002_5 - 佩丽卡

- （空节点 `contentId=-1`，next=0）
- **管理员** (`endmin`, `contentId=1; pre=0; next=2`)：抑制剂起效居然这么快？
- **佩丽卡** (`sns_chr_0004_pelica`, `contentId=2; pre=1; next=3`)：目前的抑制剂已经迭代多次，针对矿石病的研究从未停止。
- **佩丽卡** (`sns_chr_0004_pelica`, `contentId=3; pre=2; next=4`)：虽然罗德岛提供的抑制剂能阻止活性源石释放的物质穿过体细胞膜，控制新的多重结构形成——
- **佩丽卡** (`sns_chr_0004_pelica`, `contentId=4; pre=3; next=5`)：但令人遗憾的是，在塔卫二并未出现过“痊愈”的报告。
- **佩丽卡** (`sns_chr_0004_pelica`, `contentId=5; pre=4; next=6`)：一旦感染矿石病，就必须长期依靠注射抑制剂缓解病症。
- **管理员（选项）** (`option_sns_topic_map01_lv002_5_2_001`, `from=6`)：患者都能拿到抑制剂吗？ -> contentId 7
- **管理员** (`endmin`, `contentId=7; pre=6; next=8`)：抑制剂是每个患者都能拿到的吗？
- **佩丽卡** (`sns_chr_0004_pelica`, `contentId=8; pre=7; next=9`)：我明白管理员你所担心的，目前抑制药物已经在环带诸城间普及。
- **佩丽卡** (`sns_chr_0004_pelica`, `contentId=9; pre=8; next=10`)：长期接触活性源石的工作人员也都会获得预防药物和源石防护装备。
- **佩丽卡** (`sns_chr_0004_pelica`, `contentId=10; pre=9; next=11`)：拿联盟工团举例，正如索斯先生所说，会定期为工团成员及收容人员提供药物。
- **佩丽卡** (`sns_chr_0004_pelica`, `contentId=11; pre=10; next=12`)：文明环带在矿石病问题上早早达成了一致，《环带公约》从未放弃保障矿石病感染者权益的原则。
- **佩丽卡** (`sns_chr_0004_pelica`, `contentId=12; pre=11; next=-1`)：尽管我们仍然无法避免阿吉的情况发生……但在这里，没有人会把感染者抛在身后。

### sns_topic_map01_lv002_6 - 狼卫

- （空节点 `contentId=-1`，next=0）
- **管理员** (`endmin`, `contentId=1; pre=0; next=2`)：经常在荒野上行动的人们，是不是更容易患上矿石病？
- **狼卫** (`sns_chr_0006_wolfgd`, `contentId=2; pre=1; next=3`)：猎人也好，猎物也罢。只要还在文明环带的范围内，就不可能彻底避开源石
- **狼卫** (`sns_chr_0006_wolfgd`, `contentId=3; pre=2; next=4`)：我曾见过病重的狼，为了不拖累狼群，独自走进荒野再未归来
- **狼卫** (`sns_chr_0006_wolfgd`, `contentId=4; pre=3; next=5`)：也见过被碾骨掠夺的聚落，幸存的母亲抱着患病的孩子向狼群求助
- **狼卫** (`sns_chr_0006_wolfgd`, `contentId=5; pre=4; next=6`)：虽然文明环带也会为小型定居点提供抑制剂，但荒野上总是有太多的意外。
- **管理员（选项）** (`option_sns_topic_map01_lv002_6_2_001`, `from=6`)：患上矿石病一定很痛苦吧？ -> contentId 7
- **管理员（选项）** (`option_sns_topic_map01_lv002_6_2_002`, `from=6`)：很多人都患有矿石病…… -> contentId 8
- **管理员** (`endmin`, `contentId=7; pre=6; next=9`)：感染矿石病，一定很痛苦吧。
- **管理员** (`endmin`, `contentId=8; pre=6; next=9`)：所以，很多人都患有矿石病……
- **狼卫** (`sns_chr_0006_wolfgd`, `contentId=9; pre=8; next=10`)：对我来说，矿石病与其他疾病的区别……不大
- **狼卫** (`sns_chr_0006_wolfgd`, `contentId=10; pre=9; next=11`)：我听说，以前，矿石病远比现在更加危险
- **狼卫** (`sns_chr_0006_wolfgd`, `contentId=11; pre=10; next=12`)：更何况，在环带的赏金猎人和佣兵当中，不少人把矿石病看作护身符
- **狼卫** (`sns_chr_0006_wolfgd`, `contentId=12; pre=11; next=13`)：他们说——只要身上长石头，侵蚀就会绕着走。
- **管理员（选项）** (`option_sns_topic_map01_lv002_6_3_001`, `from=13`)：图片选项：sns_emoji_013 -> contentId 14
- **管理员（选项）** (`option_sns_topic_map01_lv002_6_3_002`, `from=13`)：图片选项：sns_emoji_003 -> contentId 14
- **管理员（选项）** (`option_sns_topic_map01_lv002_6_3_003`, `from=13`)：图片选项：sns_emoji_032 -> contentId 14
- **管理员（选项）** (`option_sns_topic_map01_lv002_6_4_001`, `from=14`)：真的假的？ -> contentId 15
- **管理员** (`endmin`, `contentId=15; pre=14; next=16`)：什么，矿石病还有这作用？真的假的？![sns_emoji_038](https://static.warfarin.wiki/v4/reading/sns_emoji_038.webp)
- **狼卫** (`sns_chr_0006_wolfgd`, `contentId=16; pre=15; next=-1`)：迷信罢了。

### sns_topic_map01_lv002_7 - 陈千语

- （空节点 `contentId=-1`，next=0）
- **管理员** (`endmin`, `contentId=1; pre=0; next=2`)：还好阿吉的病情稳住了。
- **陈千语** (`sns_chr_0005_chen`, `contentId=2; pre=1; next=3`)：幸好佩丽卡随身带着抑制剂。一想到阿吉那个样子，心里就不是个滋味儿。![sns_emoji_008](https://static.warfarin.wiki/v4/reading/sns_emoji_008.webp)
- **陈千语** (`sns_chr_0005_chen`, `contentId=3; pre=2; next=4`)：之前在菈梵朵玛的时候，我认识了不少感染者。
- **陈千语** (`sns_chr_0005_chen`, `contentId=4; pre=3; next=5`)：除了随身携带抑制剂，他们和其他人一样，在海边的躺椅上晒太阳啦，在音乐节玩啦……
- **陈千语** (`sns_chr_0005_chen`, `contentId=5; pre=4; next=6`)：要是他们不告诉我他们是感染者的话，我都看不出来。
- **陈千语** (`sns_chr_0005_chen`, `contentId=6; pre=5; next=7`)：但还是有一家人，在得知他们是感染者后，瞳孔都放大了，一声不吭地躲一边去了。
- **管理员（选项）** (`option_sns_topic_map01_lv002_7_2_001`, `from=7`)：图片选项：sns_emoji_003 -> contentId 8
- **管理员（选项）** (`option_sns_topic_map01_lv002_7_2_002`, `from=7`)：图片选项：sns_emoji_013 -> contentId 8
- **管理员（选项）** (`option_sns_topic_map01_lv002_7_2_003`, `from=7`)：图片选项：sns_emoji_038 -> contentId 8
- **管理员（选项）** (`option_sns_topic_map01_lv002_7_3_001`, `from=8`)：大家害怕和感染者接触吗？ -> contentId 9
- **管理员** (`endmin`, `contentId=9; pre=8; next=10`)：大家都很害怕和感染者接触吗？
- **陈千语** (`sns_chr_0005_chen`, `contentId=10; pre=9; next=11`)：还是有人会害怕的吧，但我觉得不多！
- **陈千语** (`sns_chr_0005_chen`, `contentId=11; pre=10; next=12`)：毕竟有抑制剂嘛，大家也不怎么忌讳参与对感染者的临终关怀和遗体处置。
- **陈千语** (`sns_chr_0005_chen`, `contentId=12; pre=11; next=-1`)：虽然矿石病现在还治不好，但还是希望阿吉能早日恢复健康！![sns_emoji_015](https://static.warfarin.wiki/v4/reading/sns_emoji_015.webp)
