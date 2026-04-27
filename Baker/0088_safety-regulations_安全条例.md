---
category: "Baker"
title: "安全条例"
slug: "safety-regulations"
source_url: "https://warfarin.wiki/cn/baker/safety-regulations"
game_data_version: "1.2"
warfarin_updated_at: "2026-04-17"
fetched_at: "2026-04-21T19:50:46+08:00"
---


# 安全条例

## 基本信息

- 类别：Baker
- Slug：`safety-regulations`
- 来源：[Warfarin Wiki](https://warfarin.wiki/cn/baker/safety-regulations)
- 数据版本：`1.2`
- Warfarin 最后更新：`2026-04-17`
- 采集时间：`2026-04-21T19:50:46+08:00`
- ID：`topic_map01_lv007_1`
- 包含会话：`sns_topic_map01_lv007_1`、`sns_topic_map01_lv007_2`

## 会话

- `sns_topic_map01_lv007_1`：安德烈（chatId: `sns_npc_andrew`）
- `sns_topic_map01_lv007_2`：联络员菲奥娜（chatId: `sns_npc_fiona`）

## 角色表

- `sns_npc_andrew`：安德烈
- `sns_npc_fiona`：联络员菲奥娜
- `endmin`：管理员

## 全分支文本

### sns_topic_map01_lv007_1 - 安德烈

- （空节点 `contentId=-1`，next=0）
- **安德烈** (`sns_npc_andrew`, `contentId=1; pre=0; next=2`)：管理员，菲奥娜告诉我，你们已经抵达供能高地了。
- **安德烈** (`sns_npc_andrew`, `contentId=2; pre=1; next=3`)：在接近超域试验场的时候，一定要小心啊！
- **管理员（选项）** (`option_sns_topic_map01_lv007_1_2_001`, `from=3`)：有什么注意事项？ -> contentId 4
- **管理员** (`endmin`, `contentId=4; pre=3; next=5`)：除了裂隙，还有什么注意事项吗？
- **安德烈** (`sns_npc_andrew`, `contentId=5; pre=4; next=6`)：供能高地的超域试验场作为工团进行超域研究的前沿场所，发生过不少我们还暂时无法解释的异常现象……
- **管理员（选项）** (`option_sns_topic_map01_lv007_1_3_001`, `from=6`)：你要讲恐怖故事？ -> contentId 7
- **管理员** (`endmin`, `contentId=7; pre=6; next=8`)：你要讲恐怖故事吗？
- **安德烈** (`sns_npc_andrew`, `contentId=8; pre=7; next=9`)：不是故事，是安全事故。我给您挑一个说吧。
- **安德烈** (`sns_npc_andrew`, `contentId=9; pre=8; next=10`)：供能高地一直都有一条安全条例：在超域实验进行期间，任何人都必须待在安全区域里，而且最好不要离开。
- **安德烈** (`sns_npc_andrew`, `contentId=10; pre=9; next=11`)：结果还是有工人没当回事儿，在实验期间跑到了安全区域外。
- **安德烈** (`sns_npc_andrew`, `contentId=11; pre=10; next=12`)：直到第二天一早，大家才发现他不见了。只有室内的录像能看见他打开安全门就往外走……
- **安德烈** (`sns_npc_andrew`, `contentId=12; pre=11; next=13`)：室外录像没能记录到他的下落。没有尸体，没有源石技艺，也没有侵蚀的痕迹，那名工人就这么人间蒸发了。
- **管理员（选项）** (`option_sns_topic_map01_lv007_1_4_001`, `from=13`)：明白了，我会小心的！ -> contentId 14
- **管理员** (`endmin`, `contentId=14; pre=13; next=15`)：明白了，我会小心的！
- **安德烈** (`sns_npc_andrew`, `contentId=15; pre=14; next=-1`)：这下您应该理解我的心情了，更别说那儿现在还有裂隙！我再唠叨一遍，管理员，你们一定一定要小心啊！

### sns_topic_map01_lv007_2 - 联络员菲奥娜

- （空节点 `contentId=-1`，next=0）
- **联络员菲奥娜** (`sns_npc_fiona`, `contentId=1; pre=0; next=2`)：超域裂隙被成功关闭了，感谢你们的付出，管理员。
- **联络员菲奥娜** (`sns_npc_fiona`, `contentId=2; pre=1; next=3`)：但……危机仍未结束，裂隙关闭产生了很多连锁反应。
- **联络员菲奥娜** (`sns_npc_fiona`, `contentId=3; pre=2; next=4`)：失去这条稳定的裂隙，对工团的超域研究来说是不小的打击。
- **联络员菲奥娜** (`sns_npc_fiona`, `contentId=4; pre=3; next=5`)：在关闭裂隙的过程中，激烈的超域活动也产生了大量未知的异常区域，亟待探索和处理。
- **联络员菲奥娜** (`sns_npc_fiona`, `contentId=5; pre=4; next=6`)：不仅仅涉及四号谷地，就连文明环带各地也出现了异象。
- **管理员（选项）** (`option_sns_topic_map01_lv007_2_2_001`, `from=6`)：看来还有得忙了。 -> contentId 7
- **管理员（选项）** (`option_sns_topic_map01_lv007_2_2_002`, `from=6`)：看来事情还没结束。 -> contentId 8
- **管理员** (`endmin`, `contentId=7; pre=6; next=9`)：看来还有得忙了。
- **管理员** (`endmin`, `contentId=8; pre=6; next=9`)：看来事情还没有结束。
- **联络员菲奥娜** (`sns_npc_fiona`, `contentId=9; pre=8; next=10`)：虽然……很希望您能好好休息。
- **联络员菲奥娜** (`sns_npc_fiona`, `contentId=10; pre=9; next=11`)：但，终末地还需要您来带领。
- **联络员菲奥娜** (`sns_npc_fiona`, `contentId=11; pre=10; next=12`)：加油啊，管理员。
- **管理员（选项）** (`option_sns_topic_map01_lv007_2_3_001`, `from=12`)：我会努力的。 -> contentId 13
- **管理员** (`endmin`, `contentId=13; pre=12; next=14`)：我会好好努力的。
- **联络员菲奥娜** (`sns_npc_fiona`, `contentId=14; pre=13; next=-1`)：![sns_emoji_014](https://static.warfarin.wiki/v4/reading/sns_emoji_014.webp)
