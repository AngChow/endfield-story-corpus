---
category: "Baker"
title: "终末地的歌谣"
slug: "hanna-of-endfield"
source_url: "https://warfarin.wiki/cn/baker/hanna-of-endfield"
game_data_version: "1.2"
warfarin_updated_at: "2026-04-17"
fetched_at: "2026-04-21T19:50:46+08:00"
---


# 终末地的歌谣

## 基本信息

- 类别：Baker
- Slug：`hanna-of-endfield`
- 来源：[Warfarin Wiki](https://warfarin.wiki/cn/baker/hanna-of-endfield)
- 数据版本：`1.2`
- Warfarin 最后更新：`2026-04-17`
- 采集时间：`2026-04-21T19:50:46+08:00`
- ID：`topic_chr_0007_ikut_1`
- 包含会话：`sns_topic_chr_0007_ikut_1`

## 会话

- `sns_topic_chr_0007_ikut_1`：弧光（chatId: `sns_chr_0007_ikut`）

## 角色表

- `sns_chr_0007_ikut`：弧光：风沙不止……
- `endmin`：管理员

## 全分支文本

### sns_topic_chr_0007_ikut_1 - 弧光

- （空节点 `contentId=-1`，next=0）
- **弧光** (`sns_chr_0007_ikut`, `contentId=1; pre=0; next=2`)：管理员，有需要我记住的歌谣吗
- **管理员（选项）** (`option_sns_topic_chr_0007_ikut_1_1_001`, `from=2`)：要唱歌吗？ -> contentId 3
- **管理员（选项）** (`option_sns_topic_chr_0007_ikut_1_1_002`, `from=2`)：什么歌谣？ -> contentId 4
- **管理员** (`endmin`, `contentId=3; pre=2; next=5`)：歌谣？要唱歌吗？
- **管理员** (`endmin`, `contentId=4; pre=2; next=5`)：歌谣？什么歌谣？
- **弧光** (`sns_chr_0007_ikut`, `contentId=5; pre=4; next=6`)：奥里莎师者向徒从传授知识时，会让他们记住众生长地传唱的歌谣
- **弧光** (`sns_chr_0007_ikut`, `contentId=6; pre=5; next=7`)：我很期待管理员的歌谣，毕竟连最偏远的聚落都流传着你的故事
- **弧光** (`sns_chr_0007_ikut`, `contentId=7; pre=6; next=8`)：需要我完成什么考验吗？就像裂兽族母会考验自己的幼崽一样
- **管理员（选项）** (`option_sns_topic_chr_0007_ikut_1_2_001`, `from=8`)：就像……裂兽一样？ -> contentId 9
- **管理员（选项）** (`option_sns_topic_chr_0007_ikut_1_2_002`, `from=8`)：考验？什么考验？ -> contentId 12
- **管理员（选项）** (`option_sns_topic_chr_0007_ikut_1_2_003`, `from=8`)：“裂兽族母”？ -> contentId 14
- **管理员** (`endmin`, `contentId=9; pre=8; next=10`)：就像……裂兽一样？
- **弧光** (`sns_chr_0007_ikut`, `contentId=10; pre=9; next=11`)：裂兽群的族母会让刚结束哺乳期的幼崽们竞争食物，以筛选强壮的幼崽
- **弧光** (`sns_chr_0007_ikut`, `contentId=11; pre=10; next=17`)：众生长地的歌谣里记载了这样的习性
- **管理员** (`endmin`, `contentId=12; pre=8; next=13`)：完成考验？什么考验？
- **弧光** (`sns_chr_0007_ikut`, `contentId=13; pre=12; next=17`)：对新成员的考验，通过考验以证明能力，展现其为人的品质
- **管理员** (`endmin`, `contentId=14; pre=8; next=15`)：“裂兽族母”？
- **弧光** (`sns_chr_0007_ikut`, `contentId=15; pre=14; next=16`)：她们是裂兽群的首领，一方面，她们会拼死保护族群的幼崽
- **弧光** (`sns_chr_0007_ikut`, `contentId=16; pre=15; next=17`)：另一方面，族母也会给予幼崽考验，只有强壮健康的那些才不会被遗弃
- **管理员（选项）** (`option_sns_topic_chr_0007_ikut_1_3_001`, `from=17`)：图片选项：sns_emoji_038 -> contentId 18
- **管理员（选项）** (`option_sns_topic_chr_0007_ikut_1_3_002`, `from=17`)：图片选项：sns_emoji_035 -> contentId 18
- **管理员（选项）** (`option_sns_topic_chr_0007_ikut_1_4_001`, `from=18`)：原来如此。 -> contentId 19
- **管理员** (`endmin`, `contentId=19; pre=18; next=20`)：原来如此……终末地并没有需要新干员学习的歌谣，但考验确实有一个。
- **弧光** (`sns_chr_0007_ikut`, `contentId=20; pre=19; next=21`)：好的，管理员，我会像吹过的风一样，干净利落地完成考验
- **管理员（选项）** (`option_sns_topic_chr_0007_ikut_1_5_001`, `from=21`)：去认识下武库的干员吧。 -> contentId 22
- **管理员（选项）** (`option_sns_topic_chr_0007_ikut_1_5_002`, `from=21`)：去熟悉下终末地的武库吧。 -> contentId 23
- **管理员** (`endmin`, `contentId=22; pre=21; next=24`)：去武库和大家认识一下，顺便熟悉熟悉那里的设备。
- **管理员** (`endmin`, `contentId=23; pre=21; next=24`)：去熟悉一下终末地的武库吧。熟悉下那里的设备，顺便和大家认识一下。
- **弧光** (`sns_chr_0007_ikut`, `contentId=24; pre=23; next=25`)：没问题，不过为什么是武库
- **管理员（选项）** (`option_sns_topic_chr_0007_ikut_1_6_001`, `from=25`)：我相信你会喜欢那里。 -> contentId 26
- **管理员** (`endmin`, `contentId=26; pre=25; next=27`)：因为我相信你会喜欢那里。
- **弧光** (`sns_chr_0007_ikut`, `contentId=27; pre=26; next=-1`)：明白了，我这就去
