---
category: "Baker"
title: "初来乍到"
slug: "newcomer"
source_url: "https://warfarin.wiki/cn/baker/newcomer"
game_data_version: "1.2"
warfarin_updated_at: "2026-04-17"
fetched_at: "2026-04-21T19:50:46+08:00"
---


# 初来乍到

## 基本信息

- 类别：Baker
- Slug：`newcomer`
- 来源：[Warfarin Wiki](https://warfarin.wiki/cn/baker/newcomer)
- 数据版本：`1.2`
- Warfarin 最后更新：`2026-04-17`
- 采集时间：`2026-04-21T19:50:46+08:00`
- ID：`topic_map02_lv001_1`
- 包含会话：`sns_topic_map02_lv001_1`、`sns_topic_map02_lv001_2`

## 会话

- `sns_topic_map02_lv001_1`：联络员菲奥娜（chatId: `sns_npc_fiona`）
- `sns_topic_map02_lv001_2`：陈千语（chatId: `sns_chr_0005_chen`）

## 角色表

- `sns_chr_0005_chen`：陈千语：德才兼备。
- `sns_npc_fiona`：联络员菲奥娜
- `endmin`：管理员

## 全分支文本

### sns_topic_map02_lv001_1 - 联络员菲奥娜

- （空节点 `contentId=-1`，next=0）
- **联络员菲奥娜** (`sns_npc_fiona`, `contentId=1; pre=0; next=2`)：管理员，信号遇到了严重的干扰，你们到了吗？我正在尝试联络武陵城寻求帮助。
- **联络员菲奥娜** (`sns_npc_fiona`, `contentId=2; pre=1; next=3`)：实际着陆位置与计划偏差较大，你们现在情况如何？
- **联络员菲奥娜** (`sns_npc_fiona`, `contentId=3; pre=2; next=4`)：管理员，能收到吗？
- **联络员菲奥娜** (`sns_npc_fiona`, `contentId=4; pre=3; next=5`)：我刚才与武陵城取得了联络，向他们说明了你们的情况。
- **联络员菲奥娜** (`sns_npc_fiona`, `contentId=5; pre=4; next=6`)：管理员，刚才观测到侵蚀潮出现了异常活动，你们还好吗？
- **联络员菲奥娜** (`sns_npc_fiona`, `contentId=6; pre=5; next=7`)：管理员，恢复通信后，请尽快联系我。
- **管理员（选项）** (`option_sns_topic_map02_lv001_1_1_001`, `from=7`)：能收到。 -> contentId 8
- **管理员（选项）** (`option_sns_topic_map02_lv001_1_1_002`, `from=7`)：这么多消息？ -> contentId 9
- **管理员** (`endmin`, `contentId=8; pre=7; next=10`)：能收到，才走进武陵城的通信范围。
- **管理员** (`endmin`, `contentId=9; pre=7; next=10`)：这么多消息？
- **联络员菲奥娜** (`sns_npc_fiona`, `contentId=10; pre=9; next=11`)：太好了，终于联系上了。管理员，你们现在还好吗？
- **管理员（选项）** (`option_sns_topic_map02_lv001_1_2_001`, `from=11`)：我们已经离开清波寨了。 -> contentId 12
- **管理员** (`endmin`, `contentId=12; pre=11; next=13`)：还好，我们已经离开清波寨了。
- **联络员菲奥娜** (`sns_npc_fiona`, `contentId=13; pre=12; next=14`)：清波寨？清波寨是什么地方……
- **联络员菲奥娜** (`sns_npc_fiona`, `contentId=14; pre=13; next=15`)：哦，刚才更新了一下资料。这么看来，你们离武陵城已经不远了。
- **联络员菲奥娜** (`sns_npc_fiona`, `contentId=15; pre=14; next=-1`)：管理员，武陵的情况比最初设想的要复杂，你们多加小心。

### sns_topic_map02_lv001_2 - 陈千语

- （空节点 `contentId=-1`，next=0）
- **陈千语** (`sns_chr_0005_chen`, `contentId=1; pre=0; next=2`)：我还是有点担心，等会儿和汤汤一起到了武陵城，我们该怎么收尾。
- **管理员（选项）** (`option_sns_topic_map02_lv001_2_1_001`, `from=2`)：相信武陵城。 -> contentId 3
- **管理员（选项）** (`option_sns_topic_map02_lv001_2_1_002`, `from=2`)：会有办法的。 -> contentId 4
- **管理员** (`endmin`, `contentId=3; pre=2; next=5`)：相信武陵城，他们会理解的。
- **管理员** (`endmin`, `contentId=4; pre=2; next=5`)：只能走一步看一步了。
- **陈千语** (`sns_chr_0005_chen`, `contentId=5; pre=4; next=6`)：唉，想起刚认识汤汤，也遇到过这种情况。
- **陈千语** (`sns_chr_0005_chen`, `contentId=6; pre=5; next=7`)：我正在练剑，汤汤偏要说我是花架子，我实在气不过，就跟她练了几下。
- **陈千语** (`sns_chr_0005_chen`, `contentId=7; pre=6; next=8`)：打完之后，我拉她去城里吃好吃的，她不去，我开始还以为她只是和我客气客气。
- **陈千语** (`sns_chr_0005_chen`, `contentId=8; pre=7; next=9`)：我哪知道她是清波寨的大当家！还让巡逻路过的弭弗姐看见了我俩拉拉扯扯的样子。
- **管理员（选项）** (`option_sns_topic_map02_lv001_2_2_001`, `from=9`)：然后呢？ -> contentId 10
- **管理员** (`endmin`, `contentId=10; pre=9; next=11`)：然后呢？
- **陈千语** (`sns_chr_0005_chen`, `contentId=11; pre=10; next=12`)：然后汤汤转身就跑，但一个脚滑摔泥里去了……最后被弭弗姐拎了回去。
- **陈千语** (`sns_chr_0005_chen`, `contentId=12; pre=11; next=-1`)：我也是那时候才知道清波寨和武陵城不对付。
