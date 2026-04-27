---
category: "Baker"
title: "武陵与驮兽"
slug: "wuling-and-burdenbeast"
source_url: "https://warfarin.wiki/cn/baker/wuling-and-burdenbeast"
game_data_version: "1.2"
warfarin_updated_at: "2026-04-17"
fetched_at: "2026-04-21T19:50:46+08:00"
---


# 武陵与驮兽

## 基本信息

- 类别：Baker
- Slug：`wuling-and-burdenbeast`
- 来源：[Warfarin Wiki](https://warfarin.wiki/cn/baker/wuling-and-burdenbeast)
- 数据版本：`1.2`
- Warfarin 最后更新：`2026-04-17`
- 采集时间：`2026-04-21T19:50:46+08:00`
- ID：`topic_map02_lv002_4`
- 包含会话：`sns_topic_map02_lv002_10`、`sns_topic_map02_lv002_11`

## 会话

- `sns_topic_map02_lv002_10`：黎风（chatId: `sns_chr_0015_lifeng`）
- `sns_topic_map02_lv002_11`：佩丽卡（chatId: `sns_chr_0004_pelica`）

## 角色表

- `sns_chr_0004_pelica`：佩丽卡：工作用联系B42转分机号****。看到消息一定会回复，若未回复请再敲一次。
- `sns_chr_0015_lifeng`：黎风：土自长息无限，人当百折不挠。
- `endmin`：管理员

## 全分支文本

### sns_topic_map02_lv002_10 - 黎风

- （空节点 `contentId=-2`，next=0）
- （空节点 `contentId=-1`，next=0）
- **黎风** (`sns_chr_0015_lifeng`, `contentId=1; pre=0; next=2`)：怎么样管理员，您有想起那只老驮兽的什么特征吗？
- **管理员（选项）** (`option_sns_topic_map02_lv002_10_1_001`, `from=2`)：我刚才做的那个梦…… -> contentId 3
- **管理员（选项）** (`option_sns_topic_map02_lv002_10_1_002`, `from=2`)：我好像梦到了那片田…… -> contentId 5
- **管理员** (`endmin`, `contentId=3; pre=2; next=4`)：我刚才做的那个梦里，那头老驮兽带我找他耕过的田……
- **黎风** (`sns_chr_0015_lifeng`, `contentId=4; pre=3; next=6`)：老驮兽会在临终前跑去自己记忆最深刻的地方……
- **管理员** (`endmin`, `contentId=5; pre=2; next=6`)：我好像梦到了那位老天师，还有那片田……
- **黎风** (`sns_chr_0015_lifeng`, `contentId=6; pre=5; next=7`)：管理员，您的意思不会是……
- **黎风** (`sns_chr_0015_lifeng`, `contentId=7; pre=6; next=8`)：我听彦宁姐说，老天师是带着微笑走完了最后一程。
- **黎风** (`sns_chr_0015_lifeng`, `contentId=8; pre=7; next=9`)：能在最后一刻，看到自己试验田里的作物茁壮成长，他一定走得很安心。
- **管理员（选项）** (`option_sns_topic_map02_lv002_10_2_001`, `from=9`)：农田对武陵人有特殊意义。 -> contentId 10
- **管理员** (`endmin`, `contentId=10; pre=9; next=11`)：这些试验田，对武陵人一定有特殊的意义。
- **黎风** (`sns_chr_0015_lifeng`, `contentId=11; pre=10; next=12`)：是的，对我们而言，这些试验田里的作物，可不只是赖以生存的口粮。
- **黎风** (`sns_chr_0015_lifeng`, `contentId=12; pre=11; next=13`)：还是在侵蚀危害里努力生存的希望与象征。
- **黎风** (`sns_chr_0015_lifeng`, `contentId=13; pre=12; next=14`)：那位老天师，一直躬耕在试验田里，直到病痛让他再也下不了床……
- **黎风** (`sns_chr_0015_lifeng`, `contentId=14; pre=13; next=15`)：他是我们武陵的英雄。
- **管理员（选项）** (`option_sns_topic_map02_lv002_10_3_001`, `from=15`)：他的愿望一定会实现的。 -> contentId 16
- **管理员（选项）** (`option_sns_topic_map02_lv002_10_3_002`, `from=15`)：试验田里的作物很茂盛。 -> contentId 17
- **管理员** (`endmin`, `contentId=16; pre=15; next=-1`)：他的愿望一定会实现的。
- **管理员** (`endmin`, `contentId=17; pre=15; next=-2`)：试验田里的作物长得都很茂盛，老天师的心血，没有被辜负。

### sns_topic_map02_lv002_11 - 佩丽卡

- （空节点 `contentId=-1`，next=0）
- **佩丽卡** (`sns_chr_0004_pelica`, `contentId=1; pre=0; next=2`)：管理员，驮兽科学饲养会，感觉怎么样？
- **管理员（选项）** (`option_sns_topic_map02_lv002_11_1_001`, `from=2`)：关于离世的老天师。 -> contentId 3
- **管理员（选项）** (`option_sns_topic_map02_lv002_11_1_002`, `from=2`)：关于武陵与农田。 -> contentId 5
- **管理员** (`endmin`, `contentId=3; pre=2; next=4`)：我在参加驮兽科学饲养会的时候，得知了一位农业天师突然离世……
- **佩丽卡** (`sns_chr_0004_pelica`, `contentId=4; pre=3; next=6`)：我也听说了。那位老天师操劳了一生，终于可以好好休息了……
- **管理员** (`endmin`, `contentId=5; pre=2; next=6`)：我了解到了一位老天师的故事，武陵的农田……对塔卫二很重要吧。
- **佩丽卡** (`sns_chr_0004_pelica`, `contentId=6; pre=5; next=7`)：武陵的地理环境很独特，培育出适应侵蚀环境的作物，是这片地区所承担的使命。
- **佩丽卡** (`sns_chr_0004_pelica`, `contentId=7; pre=6; next=8`)：文明环带能够实现粮食的自产自足，与武陵天师们的奉献紧密相关。
- **佩丽卡** (`sns_chr_0004_pelica`, `contentId=8; pre=7; next=9`)：即便已经能在更为舒适的环境下生活，他们也依旧来到了武陵。
- **佩丽卡** (`sns_chr_0004_pelica`, `contentId=9; pre=8; next=10`)：天师们辛苦耕耘，也是在为可能的变故做好准备。
- **管理员（选项）** (`option_sns_topic_map02_lv002_11_2_001`, `from=10`)：原来如此。 -> contentId 11
- **管理员** (`endmin`, `contentId=11; pre=10; next=12`)：原来如此……难怪那位老天师，心里始终牵挂着他的试验田……
- **佩丽卡** (`sns_chr_0004_pelica`, `contentId=12; pre=11; next=-1`)：嗯……我想，炎国古话里的“尽瘁鞠躬”，说的大概就是这样的人吧。
