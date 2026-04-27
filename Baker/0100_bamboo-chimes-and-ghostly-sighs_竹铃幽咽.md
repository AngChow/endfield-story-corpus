---
category: "Baker"
title: "竹铃幽咽"
slug: "bamboo-chimes-and-ghostly-sighs"
source_url: "https://warfarin.wiki/cn/baker/bamboo-chimes-and-ghostly-sighs"
game_data_version: "1.2"
warfarin_updated_at: "2026-04-17"
fetched_at: "2026-04-21T19:50:46+08:00"
---


# 竹铃幽咽

## 基本信息

- 类别：Baker
- Slug：`bamboo-chimes-and-ghostly-sighs`
- 来源：[Warfarin Wiki](https://warfarin.wiki/cn/baker/bamboo-chimes-and-ghostly-sighs)
- 数据版本：`1.2`
- Warfarin 最后更新：`2026-04-17`
- 采集时间：`2026-04-21T19:50:46+08:00`
- ID：`topic_map02_lv003_11001`
- 包含会话：`sns_topic_map02_lv003_1`、`sns_topic_map02_lv003_2`、`sns_topic_map02_lv003_3`

## 会话

- `sns_topic_map02_lv003_1`：庄方宜（chatId: `sns_chr_0030_zhuangfy`）
- `sns_topic_map02_lv003_2`：弭弗（chatId: `sns_npc_mifu`）
- `sns_topic_map02_lv003_3`：庄方宜（chatId: `sns_chr_0030_zhuangfy`）

## 角色表

- `sns_chr_0030_zhuangfy`：庄方宜
- `sns_npc_mifu`：弭弗
- `endmin`：管理员

## 全分支文本

### sns_topic_map02_lv003_1 - 庄方宜

- （空节点 `contentId=-1`，next=0）
- **庄方宜** (`sns_chr_0030_zhuangfy`, `contentId=1; pre=0; next=2`)：管理员，清波寨的情况如何？
- **管理员（选项）** (`option_sns_topic_map02_lv003_1_1_001`, `from=2`)：汤汤被关起来了。 -> contentId 3
- **管理员（选项）** (`option_sns_topic_map02_lv003_1_1_002`, `from=2`)：碾骨氏族控制了清波寨。 -> contentId 4
- **管理员** (`endmin`, `contentId=3; pre=2; next=5`)：情况不太好，汤汤被碾骨氏族和反叛的寨民们控制住了。
- **管理员** (`endmin`, `contentId=4; pre=2; next=5`)：我们在清波寨遇到了碾骨氏族，清波寨可能被他们控制住了。
- **庄方宜** (`sns_chr_0030_zhuangfy`, `contentId=5; pre=4; next=6`)：原来是这样……我知道了，你们多注意安全。
- **庄方宜** (`sns_chr_0030_zhuangfy`, `contentId=6; pre=5; next=7`)：清波寨的情况比较复杂，不到万不得已便大张旗鼓地派出巡卫平息事态，只怕会适得其反。
- **庄方宜** (`sns_chr_0030_zhuangfy`, `contentId=7; pre=6; next=8`)：弭弗现在状况还好吗？
- **管理员（选项）** (`option_sns_topic_map02_lv003_1_2_001`, `from=8`)：弭弗现在还好。 -> contentId 9
- **管理员** (`endmin`, `contentId=9; pre=8; next=10`)：弭弗很冷静，但也很担心汤汤的状况。
- **管理员** (`endmin`, `contentId=10; pre=9; next=11`)：说起来，我们在密道的墙上看到了她们以前的涂鸦，还有弭弗用拳头打出来的裂缝。
- **庄方宜** (`sns_chr_0030_zhuangfy`, `contentId=11; pre=10; next=12`)：嗯，弭弗以前在清波寨时就很好斗，寨民之中早已没有能在拳脚上和她匹敌的对手。
- **庄方宜** (`sns_chr_0030_zhuangfy`, `contentId=12; pre=11; next=13`)：但谁能想到，当时气势汹汹来找我一较高下的弭弗，居然因为一串糖油粑粑同我回了武陵城。
- **管理员（选项）** (`option_sns_topic_map02_lv003_1_3_001`, `from=13`)：一串糖油粑粑？ -> contentId 14
- **管理员** (`endmin`, `contentId=14; pre=13; next=15`)：一串糖油粑粑就把弭弗带走了？
- **Unknown** (``, `contentId=15; pre=14; next=16`)：[庄方宜]输入中
- **Unknown** (``, `contentId=16; pre=15; next=17`)：[庄方宜]停止输入
- **Unknown** (``, `contentId=17; pre=16; next=18`)：[庄方宜]输入中
- **庄方宜** (`sns_chr_0030_zhuangfy`, `contentId=18; pre=17; next=-1`)：只用一串糖油粑粑可不够。

### sns_topic_map02_lv003_2 - 弭弗

- （空节点 `contentId=-1`，next=0）
- **弭弗** (`sns_npc_mifu`, `contentId=1; pre=0; next=2`)：管理员，怎么样了
- **管理员（选项）** (`option_sns_topic_map02_lv003_2_1_001`, `from=2`)：关于水铃。 -> contentId 3
- **管理员** (`endmin`, `contentId=3; pre=2; next=4`)：不太好，我们还没有找到阮一，但找到了被他重伤的水铃。
- **弭弗** (`sns_npc_mifu`, `contentId=4; pre=3; next=5`)：水铃？阮一干的？这混账真下得去手
- **弭弗** (`sns_npc_mifu`, `contentId=5; pre=4; next=6`)：汤汤呢？还好吗？
- **管理员（选项）** (`option_sns_topic_map02_lv003_2_2_001`, `from=6`)：汤汤她…… -> contentId 7
- **管理员** (`endmin`, `contentId=7; pre=6; next=8`)：汤汤现在很难过，但放心，有我在她身边，不会有事的。
- **弭弗** (`sns_npc_mifu`, `contentId=8; pre=7; next=9`)：我一直都怀疑阮一这小子心里有算盘，没想到他做得这么绝
- **弭弗** (`sns_npc_mifu`, `contentId=9; pre=8; next=10`)：小时候，汤汤哪怕是三更半夜想吃羽兽蛋，阮一都会摸黑爬到树上去掏
- **弭弗** (`sns_npc_mifu`, `contentId=10; pre=9; next=11`)：遇到成群水花子，阮一也一定会护在汤汤和水铃前边
- **管理员（选项）** (`option_sns_topic_map02_lv003_2_3_001`, `from=11`)：你别太难过。 -> contentId 12
- **管理员（选项）** (`option_sns_topic_map02_lv003_2_3_002`, `from=11`)：阮一自己选择了这条路。 -> contentId 13
- **管理员** (`endmin`, `contentId=12; pre=11; next=14`)：你别太难过了。
- **管理员** (`endmin`, `contentId=13; pre=11; next=14`)：是阮一他自己选择了这条路。
- **弭弗** (`sns_npc_mifu`, `contentId=14; pre=13; next=15`)：现在，他已经没有回头路了
- **弭弗** (`sns_npc_mifu`, `contentId=15; pre=14; next=16`)：能将心思藏得这么深，管理员，多加小心
- **弭弗** (`sns_npc_mifu`, `contentId=16; pre=15; next=-1`)：反倒是汤汤……她就交给你了

### sns_topic_map02_lv003_3 - 庄方宜

- （空节点 `contentId=-1`，next=0）
- **庄方宜** (`sns_chr_0030_zhuangfy`, `contentId=1; pre=0; next=2`)：管理员，我们刚才注意到清波寨方向有异常的超域能量活动，又一直没收到你们的消息……
- **庄方宜** (`sns_chr_0030_zhuangfy`, `contentId=2; pre=1; next=3`)：你们是否安全？
- **管理员（选项）** (`option_sns_topic_map02_lv003_3_1_001`, `from=3`)：和阮一交了手…… -> contentId 4
- **管理员** (`endmin`, `contentId=4; pre=3; next=5`)：我们没事，只是阮一……我们结束了他的痛苦。
- **庄方宜** (`sns_chr_0030_zhuangfy`, `contentId=5; pre=4; next=6`)：……
- **庄方宜** (`sns_chr_0030_zhuangfy`, `contentId=6; pre=5; next=7`)：我知道了。
- **庄方宜** (`sns_chr_0030_zhuangfy`, `contentId=7; pre=6; next=8`)：冤冤相报何时了……
- **管理员（选项）** (`option_sns_topic_map02_lv003_3_2_001`, `from=8`)：关于阿达希尔。 -> contentId 9
- **管理员** (`endmin`, `contentId=9; pre=8; next=10`)：从现场情况来看，阿达希尔的原计划似乎是带走取得了力量的阮一，阮一对复仇的执念同样出乎他的意料。
- **庄方宜** (`sns_chr_0030_zhuangfy`, `contentId=10; pre=9; next=11`)：也就是说，阿达希尔和碾骨氏族的真正目的显然不是清波寨。
- **管理员（选项）** (`option_sns_topic_map02_lv003_3_3_001`, `from=11`)：恐怕还是武陵城。 -> contentId 12
- **管理员** (`endmin`, `contentId=12; pre=11; next=13`)：恐怕还是冲着武陵城来的……
- **庄方宜** (`sns_chr_0030_zhuangfy`, `contentId=13; pre=12; next=14`)：嗯……
- **庄方宜** (`sns_chr_0030_zhuangfy`, `contentId=14; pre=13; next=15`)：不管他们的目标到底是什么，我们都需要做好万全的准备。
- **庄方宜** (`sns_chr_0030_zhuangfy`, `contentId=15; pre=14; next=16`)：只是，失去了阮一，清波寨恐怕会发生一些变故……
- **庄方宜** (`sns_chr_0030_zhuangfy`, `contentId=16; pre=15; next=-1`)：管理员，请转告汤汤，如果有需要，武陵随时愿意提供帮助。
