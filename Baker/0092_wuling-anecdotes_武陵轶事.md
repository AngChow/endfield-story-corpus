---
category: "Baker"
title: "武陵轶事"
slug: "wuling-anecdotes"
source_url: "https://warfarin.wiki/cn/baker/wuling-anecdotes"
game_data_version: "1.2"
warfarin_updated_at: "2026-04-17"
fetched_at: "2026-04-21T19:50:46+08:00"
---


# 武陵轶事

## 基本信息

- 类别：Baker
- Slug：`wuling-anecdotes`
- 来源：[Warfarin Wiki](https://warfarin.wiki/cn/baker/wuling-anecdotes)
- 数据版本：`1.2`
- Warfarin 最后更新：`2026-04-17`
- 采集时间：`2026-04-21T19:50:46+08:00`
- ID：`topic_map02_lv001_2`
- 包含会话：`sns_topic_map02_lv001_3`、`sns_topic_map02_lv001_4`

## 会话

- `sns_topic_map02_lv001_3`：弭弗（chatId: `sns_npc_mifu`）
- `sns_topic_map02_lv001_4`：陈千语（chatId: `sns_chr_0005_chen`）

## 角色表

- `sns_chr_0005_chen`：陈千语：德才兼备。
- `sns_npc_mifu`：弭弗
- `endmin`：管理员

## 全分支文本

### sns_topic_map02_lv001_3 - 弭弗

- （空节点 `contentId=-1`，next=0）
- **管理员** (`endmin`, `contentId=1; pre=0; next=2`)：弭队长，你觉得庄天师是个怎样的人？
- **弭弗** (`sns_npc_mifu`, `contentId=2; pre=1; next=3`)：头儿吗
- **弭弗** (`sns_npc_mifu`, `contentId=3; pre=2; next=4`)：要我说，头儿就像是糖油粑粑
- **弭弗** (`sns_npc_mifu`, `contentId=4; pre=3; next=5`)：在油锅里把自己变得金黄金黄的
- **弭弗** (`sns_npc_mifu`, `contentId=5; pre=4; next=6`)：很有嚼劲儿，里面也很甜
- **管理员（选项）** (`option_sns_topic_map02_lv001_3_1_001`, `from=6`)：好新奇的比喻。 -> contentId 7
- **管理员（选项）** (`option_sns_topic_map02_lv001_3_1_002`, `from=6`)：糖油粑粑？ -> contentId 8
- **管理员** (`endmin`, `contentId=7; pre=6; next=9`)：这……好新奇的比喻。
- **管理员** (`endmin`, `contentId=8; pre=6; next=9`)：庄天师知道你把她看作糖油粑粑吗？
- **弭弗** (`sns_npc_mifu`, `contentId=9; pre=8; next=10`)：我是不知道该怎么说，我又不像头儿那样有文化
- **弭弗** (`sns_npc_mifu`, `contentId=10; pre=9; next=11`)：问这个干嘛
- **管理员（选项）** (`option_sns_topic_map02_lv001_3_2_001`, `from=11`)：关于“头儿”这个称呼…… -> contentId 12
- **管理员** (`endmin`, `contentId=12; pre=11; next=13`)：我记得你不是说过，她更喜欢“天师”这个身份？但我一直听你喊她“头儿”。
- **弭弗** (`sns_npc_mifu`, `contentId=13; pre=12; next=14`)：你说这个
- **弭弗** (`sns_npc_mifu`, `contentId=14; pre=13; next=15`)：因为她对我来说，不是什么管代，也不是什么天师
- **弭弗** (`sns_npc_mifu`, `contentId=15; pre=14; next=16`)：她就是我永远的头儿
- **弭弗** (`sns_npc_mifu`, `contentId=16; pre=15; next=-1`)：在她给我那串糖油粑粑后，我就认定她了

### sns_topic_map02_lv001_4 - 陈千语

- （空节点 `contentId=-1`，next=0）
- **管理员** (`endmin`, `contentId=1; pre=0; next=2`)：弭弗和汤汤之间是有什么恩怨吗？
- **陈千语** (`sns_chr_0005_chen`, `contentId=2; pre=1; next=3`)：你说她们两个呀，我认识汤汤之后，就经常看见她们两个像现在这样你追我赶的。
- **陈千语** (`sns_chr_0005_chen`, `contentId=3; pre=2; next=4`)：印象最深的，就是有一次，汤汤看见弭弗姐在那儿教训几个巡卫，专门跑过去捣乱。
- **管理员（选项）** (`option_sns_topic_map02_lv001_4_1_001`, `from=4`)：还有这段往事？ -> contentId 5
- **管理员（选项）** (`option_sns_topic_map02_lv001_4_1_002`, `from=4`)：怎么捣乱的？ -> contentId 6
- **管理员** (`endmin`, `contentId=5; pre=4; next=7`)：还有这段往事？
- **管理员** (`endmin`, `contentId=6; pre=4; next=7`)：细说，怎么捣乱的？
- **陈千语** (`sns_chr_0005_chen`, `contentId=7; pre=6; next=8`)：那天本来和以前一样，我在城外练剑的时候，汤汤跑了过来。
- **陈千语** (`sns_chr_0005_chen`, `contentId=8; pre=7; next=9`)：但不一样的是，她没和我斗嘴，反而是急冲冲地把我拽到了一块靠近武陵城的空地。
- **陈千语** (`sns_chr_0005_chen`, `contentId=9; pre=8; next=10`)：过去看了才知道，弭弗姐正在那儿做示范，汤汤突然就扔了个水球过去。
- **管理员（选项）** (`option_sns_topic_map02_lv001_4_2_001`, `from=10`)：啊。 -> contentId 11
- **管理员（选项）** (`option_sns_topic_map02_lv001_4_2_002`, `from=10`)：啊？ -> contentId 12
- **管理员** (`endmin`, `contentId=11; pre=10; next=13`)：啊，好像有点意料之中？
- **管理员** (`endmin`, `contentId=12; pre=10; next=13`)：啊？那弭弗不得好好“招待”她？
- **陈千语** (`sns_chr_0005_chen`, `contentId=13; pre=12; next=14`)：她跑得可快了！回头一看，弭弗姐头顶冒着火就冲了过来。
- **陈千语** (`sns_chr_0005_chen`, `contentId=14; pre=13; next=15`)：等我反应过来，那里就只有我和站在我面前的弭弗姐了……
- **陈千语** (`sns_chr_0005_chen`, `contentId=15; pre=14; next=16`)：还好弭弗姐知道是汤汤在捣鬼![sns_emoji_008](https://static.warfarin.wiki/v4/reading/sns_emoji_008.webp)
- **管理员（选项）** (`option_sns_topic_map02_lv001_4_3_001`, `from=16`)：有种把你卖了的感觉…… -> contentId 17
- **管理员** (`endmin`, `contentId=17; pre=16; next=18`)：有一种你被汤汤卖了的感觉……
- **陈千语** (`sns_chr_0005_chen`, `contentId=18; pre=17; next=19`)：这还没完呢！后来，我从被弭弗姐训的巡卫那里听说
- **陈千语** (`sns_chr_0005_chen`, `contentId=19; pre=18; next=20`)：他们之所以被弭弗姐拉出来加练，就是因为他们早些时候被汤汤耍得团团转！
- **陈千语** (`sns_chr_0005_chen`, `contentId=20; pre=19; next=-1`)：汤汤就是明知道会发生什么，还硬要把我拉去看热闹！![sns_emoji_008](https://static.warfarin.wiki/v4/reading/sns_emoji_008.webp)
