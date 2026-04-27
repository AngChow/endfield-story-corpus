---
category: "Baker"
title: "退款风波"
slug: "the-refund-dispute"
source_url: "https://warfarin.wiki/cn/baker/the-refund-dispute"
game_data_version: "1.2"
warfarin_updated_at: "2026-04-17"
fetched_at: "2026-04-21T19:50:46+08:00"
---


# 退款风波

## 基本信息

- 类别：Baker
- Slug：`the-refund-dispute`
- 来源：[Warfarin Wiki](https://warfarin.wiki/cn/baker/the-refund-dispute)
- 数据版本：`1.2`
- Warfarin 最后更新：`2026-04-17`
- 采集时间：`2026-04-21T19:50:46+08:00`
- ID：`topic_chr_0018_dapan_1`
- 包含会话：`sns_topic_chr_0018_dapan_1`

## 会话

- `sns_topic_chr_0018_dapan_1`：大潘（chatId: `sns_chr_0018_dapan`）

## 角色表

- `sns_chr_0018_dapan`：大潘：天凉宜远行。
- `endmin`：管理员

## 全分支文本

### sns_topic_chr_0018_dapan_1 - 大潘

- （空节点 `contentId=-2`，next=0）
- （空节点 `contentId=-1`，next=0）
- **大潘** (`sns_chr_0018_dapan`, `contentId=1; pre=0; next=2`)：分享商品链接-[《拉玛战舰详解》。书籍简介：一艘来自远方的太空战舰坠入了塔罗斯的大气……]
- **大潘** (`sns_chr_0018_dapan`, `contentId=2; pre=1; next=3`)：抱歉抱歉，管理员，不小心把链接发您这儿来了。
- **大潘** (`sns_chr_0018_dapan`, `contentId=3; pre=2; next=4`)：环塔商会的购物页做得花里胡哨，一会儿弹一个打折券，一会儿又是拉人凑单，基础功能却乱套了，居然把退款跟分享放一起！
- **管理员（选项）** (`option_sns_topic_chr_0018_dapan_1_1_001`, `from=4`)：为什么要退款？ -> contentId 5
- **管理员（选项）** (`option_sns_topic_chr_0018_dapan_1_1_002`, `from=4`)：书不好看吗？ -> contentId 6
- **管理员** (`endmin`, `contentId=5; pre=4; next=7`)：质量有问题吗？为什么要退款？
- **管理员** (`endmin`, `contentId=6; pre=4; next=7`)：这本书的内容不好看吗？
- **大潘** (`sns_chr_0018_dapan`, `contentId=7; pre=6; next=8`)：是买错了，怪我自己没仔细看。
- **大潘** (`sns_chr_0018_dapan`, `contentId=8; pre=7; next=9`)：前几天我从联盟工团淘换了些钢材跟二手发动机，想组台“迷你高速战舰”玩玩。
- **大潘** (`sns_chr_0018_dapan`, `contentId=9; pre=8; next=10`)：我以为这书是讲战舰的，买回来才发现是科幻小说。看了几页，我还纳闷啥时候有这么高科技的玩意儿了呢。
- **管理员（选项）** (`option_sns_topic_chr_0018_dapan_1_2_001`, `from=10`)：你要攻打帝江号？ -> contentId 11
- **管理员（选项）** (`option_sns_topic_chr_0018_dapan_1_2_002`, `from=10`)：你要攻打宏科院！ -> contentId 12
- **管理员** (`endmin`, `contentId=11; pre=10; next=13`)：战舰？难道是拿来攻打帝江号的？
- **管理员** (`endmin`, `contentId=12; pre=10; next=13`)：战舰？我知道了，要拿去攻打宏科院！
- **大潘** (`sns_chr_0018_dapan`, `contentId=13; pre=12; next=14`)：那不能，您别拿我开涮。就是做个玩具，名字叫得响亮，没破坏力。
- **大潘** (`sns_chr_0018_dapan`, `contentId=14; pre=13; next=15`)：说到这里……管理员，您对这本书有兴趣吗？
- **管理员（选项）** (`option_sns_topic_chr_0018_dapan_1_3_001`, `from=15`)：我对迷你战舰比较有兴趣。 -> contentId 16
- **管理员（选项）** (`option_sns_topic_chr_0018_dapan_1_3_002`, `from=15`)：有一点点好奇…… -> contentId 22
- **管理员** (`endmin`, `contentId=16; pre=15; next=17`)：我对那个迷你战舰比较有兴趣，听上去挺好玩儿。
- **大潘** (`sns_chr_0018_dapan`, `contentId=17; pre=16; next=18`)：那咱们可算一拍即合了！
- **大潘** (`sns_chr_0018_dapan`, `contentId=18; pre=17; next=19`)：我还在宏科院时，在办公室偷偷做了一台迷你高速战舰……
- **大潘** (`sns_chr_0018_dapan`, `contentId=19; pre=18; next=20`)：用它攻打地下冷库时，不小心撞翻了报废实验样本的回收箱，搞得整栋楼都飘着一股鳞肉腐坏了的味儿。
- **大潘** (`sns_chr_0018_dapan`, `contentId=20; pre=19; next=21`)：等这艘新的迷你战舰做好了，我叫您来看啊。
- **大潘** (`sns_chr_0018_dapan`, `contentId=21; pre=20; next=25`)：我好好设计下外形，给它弄帅气点儿，到时候肯定能把大伙儿吓一跳。
- **管理员** (`endmin`, `contentId=22; pre=15; next=23`)：看小说简介描述，挺有趣的。有一点点好奇……
- **大潘** (`sns_chr_0018_dapan`, `contentId=23; pre=22; next=24`)：那敢情好。我不折腾退款了，一会儿把书给您送过去。
- **大潘** (`sns_chr_0018_dapan`, `contentId=24; pre=23; next=25`)：书赠有缘人，您要是觉得好看，回头给我讲讲里面的内容。
- **大潘** (`sns_chr_0018_dapan`, `contentId=25; pre=24; next=26`)：嗐，拉着您说了这么多，耽误您时间了。有机会请您吃个饭，咱们再慢慢聊。
- **管理员（选项）** (`option_sns_topic_chr_0018_dapan_1_4_001`, `from=26`)：有机会是哪天？ -> contentId 27
- **管理员（选项）** (`option_sns_topic_chr_0018_dapan_1_4_002`, `from=26`)：早就听说你做菜一绝。 -> contentId 28
- **管理员** (`endmin`, `contentId=27; pre=26; next=29`)：我当真了，有机会是哪天？
- **管理员** (`endmin`, `contentId=28; pre=26; next=29`)：好啊，早就听说你做菜一绝。我等着。
- **大潘** (`sns_chr_0018_dapan`, `contentId=29; pre=28; next=30`)：哈哈，改日，改日。一定。
- **大潘** (`sns_chr_0018_dapan`, `contentId=30; pre=29; next=31`)：我买本《军地两用战舰维修》去……
- **管理员（选项）** (`option_sns_topic_chr_0018_dapan_1_5_001`, `from=31`)：图片选项：sns_emoji_005 -> contentId -1
- **管理员（选项）** (`option_sns_topic_chr_0018_dapan_1_5_002`, `from=31`)：图片选项：sns_emoji_007 -> contentId -2
