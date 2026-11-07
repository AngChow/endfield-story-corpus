---
category: "Baker"
title: "“驯兽师”的习惯"
slug: "topic_chr_0032_arcane_14002"
source_id: "topic_chr_0032_arcane_14002"
source_url: "https://warfarin.wiki/cn/baker/topic_chr_0032_arcane_14002"
game_data_version: "1.6"
warfarin_updated_at: "2026-11-05"
fetched_at: "2026-11-07T13:21:10.500735+00:00"
source_sha256: "da12931156ab5dfb16c617679727643ea51b6094d5348e2bc3ec3e9e564a8512"
---

# “驯兽师”的习惯

## 基本信息

- 类别：Baker
- Slug：`topic_chr_0032_arcane_14002`
- 来源：[Warfarin Wiki](https://warfarin.wiki/cn/baker/topic_chr_0032_arcane_14002)
- 数据版本：`1.6`
- Warfarin 最后更新：`2026-11-05`
- 采集时间：`2026-11-07T13:21:10.500735+00:00`
- ID：`topic_chr_0032_arcane_14002`
- 包含会话：`sns_topic_chr_0032_arcane_14002`

## 会话

- `sns_topic_chr_0032_arcane_14002`：诀（chatId: `sns_chr_0032_lizhiyan`）

## 角色表

- `sns_chr_0032_lizhiyan`：诀
- `endmin`：管理员

## 全分支文本

### sns_topic_chr_0032_arcane_14002 - 诀

- **诀** (`sns_chr_0032_lizhiyan`, `contentId=1; pre=0; next=2`)：管理员，人事部刚才发来一份警告文件。根据合作协议，我的一切情况都需要让你知悉。
- （选项节点 `contentId=2; pre=1; next=0; end=false`）
- **管理员（选项）** (`option_sns_topic_chr_0032_arcane_14002_1_001`, `from=2`)：你惹祸了！ -> contentId 3
- **管理员（选项）** (`option_sns_topic_chr_0032_arcane_14002_1_002`, `from=2`)：事情不大，我帮你处理了。 -> contentId 7
- **管理员** (`endmin`, `contentId=3; pre=2; next=4`)：人事部接到投诉说受到了小动物的袭击，据称与你有关。
- **诀** (`sns_chr_0032_lizhiyan`, `contentId=4; pre=3; next=5`)：确有此事，是一只小型羽兽。它的饲养者有长期任务，嘱托我照看一下。
- **诀** (`sns_chr_0032_lizhiyan`, `contentId=5; pre=4; next=6`)：我才照看它不到一周，还没能完全掌握它的习性。我向人事部了解了情况——它突然飞出来，吓到了不知情的干员。
- **诀** (`sns_chr_0032_lizhiyan`, `contentId=6; pre=5; next=11`)：对于发生的意外我很抱歉，所有的后果和处罚我都接受。
- **管理员** (`endmin`, `contentId=7; pre=2; next=8`)：人事部来说明了相关情况。没造成什么实质性破坏，别担心。
- **诀** (`sns_chr_0032_lizhiyan`, `contentId=8; pre=7; next=9`)：错无大小。那只羽兽的主人不在，目前是由我照看的。
- **诀** (`sns_chr_0032_lizhiyan`, `contentId=9; pre=8; next=10`)：我向人事部了解了情况，它吓到了不知情的工作人员。
- **诀** (`sns_chr_0032_lizhiyan`, `contentId=10; pre=9; next=11`)：这是我的失职。我接受一切后果。
- （选项节点 `contentId=11; pre=10; next=0; end=false`）
- **管理员（选项）** (`option_sns_topic_chr_0032_arcane_14002_2_001`, `from=11`)：别那么紧张…… -> contentId 12
- **管理员** (`endmin`, `contentId=12; pre=11; next=13`)：别那么紧张。当事人只是被吓到了，有人以为出了意外，帮她联系了人事部和医疗部门。
- **管理员** (`endmin`, `contentId=13; pre=12; next=14`)：不过……我们好奇的点是，这只羽兽平时挺乖巧的，怎么突然这么有攻击性。
- **诀** (`sns_chr_0032_lizhiyan`, `contentId=14; pre=13; next=15`)：我这几天对它进行了一些军事化训练。
- **管理员** (`endmin`, `contentId=15; pre=14; next=16`)：什么？！
- **诀** (`sns_chr_0032_lizhiyan`, `contentId=16; pre=15; next=17`)：只是一些轻度训练，它很敏锐，动作也很灵活，有成为战场助力的潜质。
- **诀** (`sns_chr_0032_lizhiyan`, `contentId=17; pre=16; next=18`)：它学得也很快，只是我没想到它已经能破坏羽兽笼了……
- （选项节点 `contentId=18; pre=17; next=0; end=false`）
- **管理员（选项）** (`option_sns_topic_chr_0032_arcane_14002_3_001`, `from=18`)：你到底让它练了什么？ -> contentId 19
- **管理员（选项）** (`option_sns_topic_chr_0032_arcane_14002_3_002`, `from=18`)：我记得它只是观赏型的…… -> contentId 20
- **管理员** (`endmin`, `contentId=19; pre=18; next=21`)：你到底让它练了什么？
- **管理员** (`endmin`, `contentId=20; pre=18; next=21`)：我记得它只是只观赏型的宠物……还挺可爱的。
- **诀** (`sns_chr_0032_lizhiyan`, `contentId=21; pre=20; next=22`)：我的计划是让它学会利用自身的特点，使用一些基本的攻击方式。
- **诀** (`sns_chr_0032_lizhiyan`, `contentId=22; pre=21; next=23`)：最开始训练噪雷的时候，我也是依照这样的思路。
- （选项节点 `contentId=23; pre=22; next=0; end=false`）
- **管理员（选项）** (`option_sns_topic_chr_0032_arcane_14002_4_001`, `from=23`)：还是别训练了…… -> contentId 24
- **管理员** (`endmin`, `contentId=24; pre=23; next=25`)：还是别练了……它的主人回来可能都认不出来自己的羽兽了。
- **诀** (`sns_chr_0032_lizhiyan`, `contentId=25; pre=24; next=26`)：那应该怎么照顾它？只是喂一些食物和水吗？我觉得这样有些失职。
- **管理员** (`endmin`, `contentId=26; pre=25; next=27`)：可以多和它玩……没关系，那位被吓到的干员原本就很喜欢这只羽兽，她说想和你一起照顾它，我觉得这是个机会。
- **管理员** (`endmin`, `contentId=27; pre=26; next=28`)：可以观察一下她是怎么照顾小动物的，而不是……训练。
- **诀** (`sns_chr_0032_lizhiyan`, `contentId=28; pre=27; next=29`)：那再好不过了。
- **诀** (`sns_chr_0032_lizhiyan`, `contentId=29; pre=28; next=30`)：我还要为之前对她造成的困扰当面道歉，就先失陪了。
- （选项节点 `contentId=30; pre=29; next=0; end=false`）
- **管理员（选项）** (`option_sns_topic_chr_0032_arcane_14002_5_001`, `from=30`)：图片选项：sns_emoji_037 -> contentId -1
- （空节点 `contentId=-1; pre=30; next=0; end=true`）
