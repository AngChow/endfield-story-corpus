---
category: "Baker"
title: "危机与安宁"
slug: "crisis-and-tranquility"
source_url: "https://warfarin.wiki/cn/baker/crisis-and-tranquility"
game_data_version: "1.2"
warfarin_updated_at: "2026-04-17"
fetched_at: "2026-04-21T19:50:46+08:00"
---


# 危机与安宁

## 基本信息

- 类别：Baker
- Slug：`crisis-and-tranquility`
- 来源：[Warfarin Wiki](https://warfarin.wiki/cn/baker/crisis-and-tranquility)
- 数据版本：`1.2`
- Warfarin 最后更新：`2026-04-17`
- 采集时间：`2026-04-21T19:50:46+08:00`
- ID：`topic_map02_lv002_1`
- 包含会话：`sns_topic_map02_lv002_1`、`sns_topic_map02_lv002_2`

## 会话

- `sns_topic_map02_lv002_1`：庄方宜（chatId: `sns_chr_0030_zhuangfy`）
- `sns_topic_map02_lv002_2`：弭弗（chatId: `sns_npc_mifu`）

## 角色表

- `sns_chr_0030_zhuangfy`：庄方宜
- `sns_npc_mifu`：弭弗
- `endmin`：管理员

## 全分支文本

### sns_topic_map02_lv002_1 - 庄方宜

- （空节点 `contentId=-2`，next=0）
- （空节点 `contentId=-1`，next=0）
- **庄方宜** (`sns_chr_0030_zhuangfy`, `contentId=1; pre=0; next=2`)：管理员，武陵地区面临的危险与其他地区有所不同，请多加小心。
- **管理员（选项）** (`option_sns_topic_map02_lv002_1_1_001`, `from=2`)：关于天使。 -> contentId 3
- **管理员** (`endmin`, `contentId=3; pre=2; next=4`)：武陵的天使原来会随着侵蚀潮出现在各个地方吗？
- **庄方宜** (`sns_chr_0030_zhuangfy`, `contentId=4; pre=3; next=5`)：嗯……每当侵蚀潮汛期来临，整个武陵地区便会受到大量天使的威胁。
- **庄方宜** (`sns_chr_0030_zhuangfy`, `contentId=5; pre=4; next=6`)：我们推测，之所以会出现这种现象，是因为武陵地区受侵蚀影响的水体深处应该存在一个，甚至多个锚点。
- **庄方宜** (`sns_chr_0030_zhuangfy`, `contentId=6; pre=5; next=7`)：但目前我们还不具备对武陵地区的侵蚀水体进行深层勘测的条件，更别提找到并摧毁侵蚀潮之下的锚点了。
- **庄方宜** (`sns_chr_0030_zhuangfy`, `contentId=7; pre=6; next=8`)：每到汛期，我们能做的，便只有组织大量人力镇守天师桩阵列，以免天师桩受到损坏。
- **管理员（选项）** (`option_sns_topic_map02_lv002_1_2_001`, `from=8`)：和我们初入武陵城时一样？ -> contentId 9
- **管理员（选项）** (`option_sns_topic_map02_lv002_1_2_002`, `from=8`)：每次你都会亲力亲为吗？ -> contentId 11
- **管理员** (`endmin`, `contentId=9; pre=8; next=10`)：就和我们第一次进武陵城时看到的一样？
- **庄方宜** (`sns_chr_0030_zhuangfy`, `contentId=10; pre=9; next=-1`)：是的。这次侵蚀潮出乎了我们的预料，没有做好防护。多亏了管理员的协助。
- **管理员** (`endmin`, `contentId=11; pre=8; next=12`)：每次汛期，你都会和武陵城的巡卫们一起保护天师桩阵列吗？
- **庄方宜** (`sns_chr_0030_zhuangfy`, `contentId=12; pre=11; next=13`)：嗯……天师桩阵列不能有任何闪失。
- **庄方宜** (`sns_chr_0030_zhuangfy`, `contentId=13; pre=12; next=-2`)：这关系到整座武陵城的安危。

### sns_topic_map02_lv002_2 - 弭弗

- （空节点 `contentId=-1`，next=0）
- **弭弗** (`sns_npc_mifu`, `contentId=1; pre=0; next=2`)：管理员，刚才忘问了，田阿姨和阿仔的比赛，你感觉如何
- **管理员（选项）** (`option_sns_topic_map02_lv002_2_1_001`, `from=2`)：田阿姨的面。 -> contentId 3
- **管理员（选项）** (`option_sns_topic_map02_lv002_2_1_002`, `from=2`)：阿仔的故事。 -> contentId 5
- **管理员** (`endmin`, `contentId=3; pre=2; next=4`)：田阿姨的烂肉面真的很好吃。
- **弭弗** (`sns_npc_mifu`, `contentId=4; pre=3; next=7`)：嗯，熟悉的味道，好吃
- **管理员** (`endmin`, `contentId=5; pre=2; next=6`)：阿仔的故事有点让人感动。
- **弭弗** (`sns_npc_mifu`, `contentId=6; pre=5; next=7`)：大家都是这么过来的，都不容易
- **管理员（选项）** (`option_sns_topic_map02_lv002_2_2_001`, `from=7`)：关于弭弗平时吃的。 -> contentId 8
- **管理员** (`endmin`, `contentId=8; pre=7; next=9`)：你平时还常吃什么？
- **弭弗** (`sns_npc_mifu`, `contentId=9; pre=8; next=10`)：我平时多是在巡卫食堂吃
- **弭弗** (`sns_npc_mifu`, `contentId=10; pre=9; next=11`)：都是面条、炒饭、饺子这种，味道一般，但量大管饱
- **弭弗** (`sns_npc_mifu`, `contentId=11; pre=10; next=12`)：毕竟巡卫平常需要巡逻，当有人起纠纷的时候，没力气可拉不开
- **弭弗** (`sns_npc_mifu`, `contentId=12; pre=11; next=13`)：还有武陵城外，也要安排巡卫，免得有人，或者，有什么东西搞破坏
- **管理员（选项）** (`option_sns_topic_map02_lv002_2_3_001`, `from=13`)：辛苦了。 -> contentId 14
- **管理员（选项）** (`option_sns_topic_map02_lv002_2_3_002`, `from=13`)：还得靠巡卫。 -> contentId 16
- **管理员** (`endmin`, `contentId=14; pre=13; next=15`)：辛苦了。
- **弭弗** (`sns_npc_mifu`, `contentId=15; pre=14; next=18`)：应该的
- **管理员** (`endmin`, `contentId=16; pre=13; next=17`)：还得靠巡卫。
- **弭弗** (`sns_npc_mifu`, `contentId=17; pre=16; next=18`)：分内事
- **弭弗** (`sns_npc_mifu`, `contentId=18; pre=17; next=19`)：怎么感觉像是在上班了
- **弭弗** (`sns_npc_mifu`, `contentId=19; pre=18; next=-1`)：要是想吃什么好吃的，哪天有空，我带你去溜达溜达
