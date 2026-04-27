---
category: "Baker"
title: "“全自动惹事机”"
slug: "the-murphys-law-enforcer"
source_url: "https://warfarin.wiki/cn/baker/the-murphys-law-enforcer"
game_data_version: "1.2"
warfarin_updated_at: "2026-04-17"
fetched_at: "2026-04-21T19:50:46+08:00"
---


# “全自动惹事机”

## 基本信息

- 类别：Baker
- Slug：`the-murphys-law-enforcer`
- 来源：[Warfarin Wiki](https://warfarin.wiki/cn/baker/the-murphys-law-enforcer)
- 数据版本：`1.2`
- Warfarin 最后更新：`2026-04-17`
- 采集时间：`2026-04-21T19:50:46+08:00`
- ID：`topic_chr_0022_bounda_1`
- 包含会话：`sns_topic_chr_0022_bounda_1`

## 会话

- `sns_topic_chr_0022_bounda_1`：萤石（chatId: `sns_chr_0022_bounda`）

## 角色表

- `sns_chr_0022_bounda`：萤石
- `endmin`：管理员

## 全分支文本

### sns_topic_chr_0022_bounda_1 - 萤石

- （空节点 `contentId=-1`，next=0）
- **萤石** (`sns_chr_0022_bounda`, `contentId=1; pre=0; next=2`)：刚刚有个干员来传话，找我有事？
- **管理员（选项）** (`option_sns_topic_chr_0022_bounda_1_1_001`, `from=2`)：你好像又惹麻烦了？ -> contentId 3
- **管理员** (`endmin`, `contentId=3; pre=2; next=4`)：我刚看完秋栗提交的小队行动报告……你又差点和当地居民起冲突了？
- **萤石** (`sns_chr_0022_bounda`, `contentId=4; pre=3; next=5`)：是没错。
- **萤石** (`sns_chr_0022_bounda`, `contentId=5; pre=4; next=6`)：需要写点什么吗，我还剩几份检讨书可以一起给。
- **管理员（选项）** (`option_sns_topic_chr_0022_bounda_1_2_001`, `from=6`)：感觉你没有在反省…… -> contentId 7
- **管理员** (`endmin`, `contentId=7; pre=6; next=8`)：检讨书是留给会反省的人用的，但我觉得你并不会。
- **管理员** (`endmin`, `contentId=8; pre=7; next=9`)：人力资源事务部的干员已经给我看了过往的行动报告。为什么每次都变成这样？
- **萤石** (`sns_chr_0022_bounda`, `contentId=9; pre=8; next=10`)：因为我们工作的特性吧。
- **管理员（选项）** (`option_sns_topic_chr_0022_bounda_1_3_001`, `from=10`)：图片选项：sns_emoji_038 -> contentId 11
- **管理员（选项）** (`option_sns_topic_chr_0022_bounda_1_3_002`, `from=10`)：图片选项：sns_emoji_013 -> contentId 11
- **萤石** (`sns_chr_0022_bounda`, `contentId=11; pre=10; next=12`)：和人说话那么累，如果还要照顾那些弯弯绕绕的小心思，那就太麻烦了。
- **萤石** (`sns_chr_0022_bounda`, `contentId=12; pre=11; next=13`)：所以，我一般直接按照对面心里在想的来回答他们。
- **萤石** (`sns_chr_0022_bounda`, `contentId=13; pre=12; next=14`)：很不巧，需要我们小队出面的情况，交涉对象都不太习惯这种办法。
- **管理员（选项）** (`option_sns_topic_chr_0022_bounda_1_4_001`, `from=14`)：你能平安无事真是奇迹。 -> contentId 15
- **管理员（选项）** (`option_sns_topic_chr_0022_bounda_1_4_002`, `from=14`)：难道没有出过事吗？ -> contentId 17
- **管理员** (`endmin`, `contentId=15; pre=14; next=16`)：很难想象会有人习惯这种“交涉”。如果你以前就经常这么做，我都要开始佩服你了。
- **萤石** (`sns_chr_0022_bounda`, `contentId=16; pre=15; next=18`)：其实这样反而有好处哦。
- **管理员** (`endmin`, `contentId=17; pre=14; next=18`)：我已经能想象对面恼羞成怒的样子了，难道以前没有出过事吗？
- **萤石** (`sns_chr_0022_bounda`, `contentId=18; pre=17; next=19`)：如果他们从一开始就没想过对人不利，就算我戳穿那层泡泡，最多只是挨几个白眼。
- **萤石** (`sns_chr_0022_bounda`, `contentId=19; pre=18; next=20`)：但如果是另一种想法，以我们的身手，早些让他们把拳头亮出来，反而更安全。
- **管理员（选项）** (`option_sns_topic_chr_0022_bounda_1_5_001`, `from=20`)：有一点道理…… -> contentId 21
- **管理员** (`endmin`, `contentId=21; pre=20; next=22`)：这套理论意外地自洽……不过秋栗在报告里对此还是很有意见，最好也多考虑考虑替你操心的队长。
- **萤石** (`sns_chr_0022_bounda`, `contentId=22; pre=21; next=23`)：放心，只要没错怪好人，她不会抱怨太久的。
- **萤石** (`sns_chr_0022_bounda`, `contentId=23; pre=22; next=24`)：我猜那群“当地人”到现在还没有过来投诉或者闹事，对吧？
- **管理员（选项）** (`option_sns_topic_chr_0022_bounda_1_6_001`, `from=24`)：的确如此。 -> contentId 25
- **管理员** (`endmin`, `contentId=25; pre=24; next=26`)：虽然报告里描述得很严重，但我们确实没有收到任何反馈。
- **管理员** (`endmin`, `contentId=26; pre=25; next=27`)：所以，他们确实心里有鬼？
- **萤石** (`sns_chr_0022_bounda`, `contentId=27; pre=26; next=28`)：![sns_emoji_027](https://static.warfarin.wiki/v4/reading/sns_emoji_027.webp)
- **萤石** (`sns_chr_0022_bounda`, `contentId=28; pre=27; next=29`)：反正今天很闲，不如我去主动报案领笔赏钱吧。
- **萤石** (`sns_chr_0022_bounda`, `contentId=29; pre=28; next=30`)：怎么样，一起来签个名？
- **管理员（选项）** (`option_sns_topic_chr_0022_bounda_1_7_001`, `from=30`)：不必了…… -> contentId 31
- **管理员** (`endmin`, `contentId=31; pre=30; next=-1`)：不必了，这件事就交给你处置吧。
