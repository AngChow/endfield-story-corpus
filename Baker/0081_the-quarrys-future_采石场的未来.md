---
category: "Baker"
title: "采石场的未来"
slug: "the-quarrys-future"
source_id: "topic_map01_lv003_1"
source_url: "https://warfarin.wiki/cn/baker/topic_map01_lv003_1"
game_data_version: "1.6"
warfarin_updated_at: "2026-10-15"
fetched_at: "2026-10-19T07:55:39.865115+00:00"
source_sha256: "059c2971f51afb6b293909da0bfc11805c85190bef9886c2dd3e2e398c2ea647"
---

# 采石场的未来

## 基本信息

- 类别：Baker
- Slug：`the-quarrys-future`
- 来源：[Warfarin Wiki](https://warfarin.wiki/cn/baker/topic_map01_lv003_1)
- 数据版本：`1.6`
- Warfarin 最后更新：`2026-10-15`
- 采集时间：`2026-10-19T07:55:39.865115+00:00`
- ID：`topic_map01_lv003_1`
- 包含会话：`sns_topic_map01_lv003_3`、`sns_topic_map01_lv003_2`

## 会话

- `sns_topic_map01_lv003_3`：秦茳尺（chatId: `sns_npc_qinjc`）
- `sns_topic_map01_lv003_2`：陈千语（chatId: `sns_chr_0005_chen`）

## 角色表

- `sns_npc_qinjc`：秦茳尺
- `sns_chr_0005_chen`：陈千语
- `endmin`：管理员

## 全分支文本

### sns_topic_map01_lv003_3 - 秦茳尺

- **管理员** (`endmin`, `contentId=1; pre=0; next=2`)：秦工程师，阿伯莉采石场未来会怎么样？
- **秦茳尺** (`sns_npc_qinjc`, `contentId=2; pre=1; next=3`)：根据工团的正式照会……四号谷地正在将那里的工人迁至其他地区。
- **秦茳尺** (`sns_npc_qinjc`, `contentId=3; pre=2; next=4`)：等安置工作完成后，采石场就会被完全封闭，等待中央生产计划委员会的下一步命令。
- （选项节点 `contentId=4; pre=3; next=0; end=false`）
- **管理员（选项）** (`option_sns_topic_map01_lv003_3_2_001`, `from=4`)：工人们都很不舍。 -> contentId 5
- **管理员（选项）** (`option_sns_topic_map01_lv003_3_2_002`, `from=4`)：工人们都很难过。 -> contentId 6
- **管理员** (`endmin`, `contentId=5; pre=4; next=7`)：工人们都很舍不得采石场。
- **管理员** (`endmin`, `contentId=6; pre=4; next=7`)：采石场的工人们看上去都很难过。
- **秦茳尺** (`sns_npc_qinjc`, `contentId=7; pre=6; next=8`)：正如您所见，不只是采石场的工人们，四号谷地的其他工人也都舍不得这座老采石场。我们也……感同身受。
- **秦茳尺** (`sns_npc_qinjc`, `contentId=8; pre=7; next=9`)：收到指令后，工团核对了每一位采石场工人的现况，尽可能地提供了心理疏导。
- **秦茳尺** (`sns_npc_qinjc`, `contentId=9; pre=8; next=10`)：塞梦珂也听取了工人们的意见，让那些凝聚着工人们情感的设备，随他们一同转移。
- （选项节点 `contentId=10; pre=9; next=0; end=false`）
- **管理员（选项）** (`option_sns_topic_map01_lv003_3_3_001`, `from=10`)：核对现况？ -> contentId 11
- **管理员（选项）** (`option_sns_topic_map01_lv003_3_3_002`, `from=10`)：提供心理疏导？ -> contentId 12
- **管理员** (`endmin`, `contentId=11; pre=10; next=13`)：核对每一位采石场工人的现况？
- **管理员** (`endmin`, `contentId=12; pre=10; next=13`)：提供心理疏导？
- **秦茳尺** (`sns_npc_qinjc`, `contentId=13; pre=12; next=14`)：四号谷地如今的每一位工人，都是在阿伯莉的故事里长大的。采石场对这里的工人们有着特殊的意义。
- **秦茳尺** (`sns_npc_qinjc`, `contentId=14; pre=13; next=15`)：封闭采石场必定会伤害到工人们的情感，但事关超域，我们没有选择。哪怕是工团，也只能尽力为工人们提供帮助。
- （选项节点 `contentId=15; pre=14; next=0; end=false`）
- **管理员（选项）** (`option_sns_topic_map01_lv003_3_4_001`, `from=15`)：图片选项：sns_emoji_003 -> contentId 16
- **管理员（选项）** (`option_sns_topic_map01_lv003_3_4_002`, `from=15`)：图片选项：sns_emoji_009 -> contentId 16
- **管理员（选项）** (`option_sns_topic_map01_lv003_3_4_003`, `from=15`)：图片选项：sns_emoji_028 -> contentId 16
- （选项节点 `contentId=16; pre=15; next=0; end=false`）
- **管理员（选项）** (`option_sns_topic_map01_lv003_3_5_001`, `from=16`)：原来是这样。 -> contentId 17
- **管理员** (`endmin`, `contentId=17; pre=16; next=-1`)：原来是这样。<image="sns_emoji_038">
- （空节点 `contentId=-1; pre=17; next=0; end=true`）

### sns_topic_map01_lv003_2 - 陈千语

- **陈千语** (`sns_chr_0005_chen`, `contentId=1; pre=0; next=2`)：管理员，刚才米菈发来了她们师徒三人和拉蒙的合照。<image="sns_emoji_001">
- **陈千语** (`sns_chr_0005_chen`, `contentId=2; pre=1; next=3`)：她们三人解开了误会，真是太好了！
- （选项节点 `contentId=3; pre=2; next=0; end=false`）
- **管理员（选项）** (`option_sns_topic_map01_lv003_2_1_001`, `from=3`)：希望她们一切顺利。 -> contentId 4
- **管理员（选项）** (`option_sns_topic_map01_lv003_2_1_002`, `from=3`)：真是太开心了！ -> contentId 5
- **管理员** (`endmin`, `contentId=4; pre=3; next=6`)：希望她们到了新的采石场后一切顺利。
- **管理员** (`endmin`, `contentId=5; pre=3; next=6`)：真是太开心了！
- **陈千语** (`sns_chr_0005_chen`, `contentId=6; pre=5; next=7`)：之前看着米菈伤心成那样，本来还挺难过的。
- **陈千语** (`sns_chr_0005_chen`, `contentId=7; pre=6; next=8`)：没想到，那架“老家伙”居然也会跟着工团成员们去新的采石场。
- **陈千语** (`sns_chr_0005_chen`, `contentId=8; pre=7; next=9`)：佩妮女士真是的，也不说一声，害我们白难过一场。<image="sns_emoji_008">
- **陈千语** (`sns_chr_0005_chen`, `contentId=9; pre=8; next=10`)：虽然佩妮女士和菲莉丝一见面就火药味儿十足的，但她们师徒三人关系也真好。
- **陈千语** (`sns_chr_0005_chen`, `contentId=10; pre=9; next=11`)：嘴上不饶人，却都心系着彼此。
- （选项节点 `contentId=11; pre=10; next=0; end=false`）
- **管理员（选项）** (`option_sns_topic_map01_lv003_2_2_001`, `from=11`)：图片选项：sns_emoji_001 -> contentId 12
- **管理员（选项）** (`option_sns_topic_map01_lv003_2_2_002`, `from=11`)：图片选项：sns_emoji_005 -> contentId 12
- **管理员（选项）** (`option_sns_topic_map01_lv003_2_2_003`, `from=11`)：图片选项：sns_emoji_024 -> contentId 12
- （选项节点 `contentId=12; pre=11; next=0; end=false`）
- **管理员（选项）** (`option_sns_topic_map01_lv003_2_3_001`, `from=12`)：这让她们的关系更加牢固。 -> contentId 13
- **管理员** (`endmin`, `contentId=13; pre=12; next=14`)：大概就是这种相处方式，让她们的感情更加牢固。
- **陈千语** (`sns_chr_0005_chen`, `contentId=14; pre=13; next=15`)：米菈还和我说，她们临走前还打算维护一下采石场的那些设备。
- **陈千语** (`sns_chr_0005_chen`, `contentId=15; pre=14; next=16`)：再算上完成收尾工作，就当是对阿伯莉采石场的告别了。
- **陈千语** (`sns_chr_0005_chen`, `contentId=16; pre=15; next=-1`)：希望下次再会时，她们都已经找到了自己的未来。<image="sns_emoji_024">
- （空节点 `contentId=-1; pre=16; next=0; end=true`）

## 历史附注（来源 v1.2）

> 以下为旧来源 v1.2 的角色联系附注。当前来源未提供这些字段，仅作历史保留，不代表当前角色表内容。

- `sns_chr_0005_chen`：陈千语：德才兼备。
