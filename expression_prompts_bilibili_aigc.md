# 动漫女性角色表情差分生成提示词资源大全

> 收集来源：bilibili_aigc 相关社区、CSDN、知乎、站酷、日本AI教程、PromptBase、GitHub等
> 收集时间：2025年
> 研究员：提示词研究员_bilibili_aigc

---

## 目录

1. [表情关键词总表（中英对照）](#1-表情关键词总表中英对照)
2. [完整提示词模板示例](#2-完整提示词模板示例)
3. [负面提示词（Negative Prompt）](#3-负面提示词negative-prompt)
4. [制作表情差分的方法与技巧](#4-制作表情差分的方法与技巧)
5. [关键来源与参考链接](#5-关键来源与参考链接)
6. [样例图片与素材资源](#6-样例图片与素材资源)

---

## 1. 表情关键词总表（中英对照）

### 1.1 基础表情（Basic Expressions）

| 中文 | 英文提示词 | 说明 | 强度 |
|------|-----------|------|------|
| 开心/快乐 | `happy`, `smile` | 基础微笑，日常愉悦 | 中等 |
| 愉快/轻松 | `cheerful`, `playful` | 轻松对话、互动场景 | 较高 |
| 温柔的微笑 | `softly smiling` | 柔和、内敛的笑容 | 低 |
| 浅笑/得意 | `smirk` | 带有自信或狡黠的微笑 | 中等 |
| 露齿微笑 | `light smile`, `grin` | 咧嘴笑，露出牙齿 | 中等 |
| 大笑 | `laughing` | 开怀大笑 | 高 |
| 咯咯笑 | `chuckling` | 轻声笑 | 低 |
| 逗乐/被逗笑 | `amused` | 被逗乐的状态 | 中等 |
| 兴奋 | `excited` | 兴奋、激动 | 高 |
| 开朗 | `cheerful` |  cheerful, 阳光开朗 | 高 |
| 高兴/满意 | `pleased` | 满意、高兴 | 中等 |
| 轻松 | `relaxed` | 放松状态 | 低 |
| 冷静 | `calm` | 平静、冷静 | 低 |
| 无表情 | `expressionless` | 面无表情，扑克脸 | 无 |
| 严肃 | `serious-looking` | 严肃、认真 | 中等 |

### 1.2 害羞/脸红系（Shy & Blushing）

| 中文 | 英文提示词 | 说明 | 强度 |
|------|-----------|------|------|
| 害羞 | `shy` | 害羞、羞涩 | 中等 |
| 脸红 | `blushing` | 脸红、面颊泛红 | 中等 |
| 脸红低头 | `blushing and looking down` | 害羞低头 | 高 |
| 害羞的红晕 | `intense blush`, `sudden blush` | 突然脸红，强烈反应 | 高 |
| 极度害羞 | `overwhelmed blush`, `flustered` | 慌乱、不知所措 | 极高 |
| 热脸颊 | `hot cheeks`, `burning cheeks` | 脸颊发烫 | 高 |
| 害羞的哭泣 | `shy crying`, `bashful tears` | 害羞到哭 | 高 |
| 恋爱表情 | `lovestruck`, `heart eyes` | 爱心眼、迷恋 | 高 |

### 1.3 悲伤/哭泣系（Sad & Crying）

| 中文 | 英文提示词 | 说明 | 强度 |
|------|-----------|------|------|
| 悲伤 | `sad`, `sorrowful` | 悲伤、难过 | 中等 |
| 哭泣 | `crying`, `tears` | 哭泣、流泪 | 高 |
| 含泪 | `tearful eyes` | 泪眼汪汪 | 高 |
| 眼泪流下 | `tears streaming down face` | 眼泪流下脸颊 | 极高 |
| 欲哭无泪 | `trembling lips`, `on the verge of tears` | 强忍泪水 | 高 |
| 忧郁 | `gloomy`, `depressed`, `melancholy` | 忧郁、沮丧 | 高 |
| 嘴角下弯 | `downturned lips, looking sad` | 嘴角下垂表示难过 | 中等 |
| 抿嘴难过 | `tight-lipped, showing dissatisfaction` | 抿嘴表示不满 | 中等 |
| 眼泪汪汪的悲伤 | `tearful eyes, expressing sadness` | 泪眼表达悲伤 | 高 |
| 喜极而泣 | `crying with joy`, `joyful tears` | 开心的哭泣 | 高 |
| 被感动流泪 | `moved tears`, `touched tears` | 感动流泪 | 中等 |
|  relieved tears | `relieved tears`, `sentimental tears` | 释然的泪水 | 中等 |
| 默默哭泣 | `suppressed crying`, `quiet crying` | 压抑的哭泣 | 高 |
| 流泪的悲伤 | `weeping`, `sobbing` | 抽泣、呜咽 | 极高 |

### 1.4 愤怒/厌恶系（Angry & Disgusted）

| 中文 | 英文提示词 | 说明 | 强度 |
|------|-----------|------|------|
| 生气 | `angry`, `furious` | 愤怒、生气 | 高 |
| 愤怒 | `rage`, `irate`, `agitated` | 激怒、暴怒 | 极高 |
| 皱眉 | `frowning`, `a frown` | 皱眉、不高兴 | 中等 |
| 脾气暴躁 | `grumpy` | 脾气暴躁、易怒 | 中等 |
| 恼怒 | `irritated`, `annoyed` | 恼怒、烦躁 | 中等 |
| 厌恶 | `disgust`, `disgusted` | 厌恶、反感 | 高 |
| 轻蔑 | `contemptuous`, `scornful` | 轻蔑、鄙视 | 高 |
| 令人恶心 | `nasty`, `repulsed` | 恶心、反感 | 高 |
| 大喊大叫 | `shouting`, `screaming` | 尖叫、大喊 | 极高 |
| 疯了 | `mad`, `crazy expression` | 发疯、狂乱 | 极高 |
| 嘴角下垂表失望 | `downturned mouth, indicating disappointment` | 失望的表情 | 中等 |
| 表示无助 | `expressing helplessness` | 无助、无奈 | 中等 |
| 冷漠 | `indifferent`, `aloof` | 冷漠、漠不关心 | 中等 |
| 交叉双臂表冷漠 | `crossing arms, displaying indifference` | 抱手冷漠 | 中等 |
| 咬牙切齿 | `gritting teeth`, `clenched jaw` | 咬牙切齿 | 高 |
| 青筋暴起 | `bulging veins on forehead`, `angry veins` | 额头青筋 | 极高 |

### 1.5 惊讶/震惊系（Surprised & Shocked）

| 中文 | 英文提示词 | 说明 | 强度 |
|------|-----------|------|------|
| 惊讶 | `surprised`, `astonished` | 惊讶、吃惊 | 高 |
| 震惊 | `shocked`, `stunned` | 震惊、目瞪口呆 | 极高 |
| 目瞪口呆 | `mouth agape`, `jaw drop` | 嘴巴大张 | 极高 |
| 震惊张嘴 | `mouth agape, expressing shock` | 张嘴震惊 | 极高 |
| 睁大眼睛 | `wide eyes`, `eyes wide open` | 眼睛睁大 | 高 |
| 瞳孔缩小（惊恐） | `pupil shrink`, `constricted pupils` | 惊恐时瞳孔缩小 | 高 |
| 害怕 | `scared`, `frightened`, `afraid` | 害怕、恐惧 | 高 |
| 恐惧 | `horrified`, `terrified` | 恐惧、恐怖 | 极高 |
| 恐慌 | `panicked`, `flustered` | 慌张、慌乱 | 高 |
| 受到惊吓 | `startled`, `taken aback` | 受惊、吓一跳 | 高 |
| 好奇 | `curious`, `interested` | 好奇、感兴趣 | 低 |
| 困惑 | `confused`, `bewildered`, `puzzled` | 困惑、迷茫 | 中等 |
| 疑惑 | `questioning look`, `doubtful` | 怀疑的表情 | 中等 |
| 惊讶到脸红 | `shocked blush`, `surprised blush` | 震惊脸红 | 高 |

### 1.6 日系/二次元特定表情（Anime-Specific）

| 中文 | 英文提示词 | 说明 | 强度 |
|------|-----------|------|------|
| 傲娇 | `tsundere face`, `pouting` | 傲娇、撅嘴 | 中等 |
| 撅嘴 | `pouty`, `pouting` | 嘟嘴、不高兴 | 中等 |
| 困/困倦 | `sleepy`, `drowsy`, `yawning` | 打哈欠、困倦 | 低 |
| 揉眼睛 | `yawning and rubbing her eyes` | 打哈欠揉眼睛 | 低 |
| 困倦难受 | `sleepy eyes`, `heavy eyelids` | 眼皮沉重 | 低 |
| 醉酒 | `blind drunk`, `roaring drunk` | 醉酒、耍酒疯 | 高 |
| 得意/自信 | `smug`, `confident smile` | 得意洋洋 | 中等 |
| 淘气 | `mischievous`, `naughty smile` | 调皮、使坏 | 中等 |
| 卖萌 | `cute expression`, `kawaii face` | 可爱的表情 | 中等 |
| 星星眼 | `star eyes`, `sparkling eyes` | 闪闪发光的眼睛 | 高 |
| 爱心眼 | `heart-shaped eyes`, `heart eyes` | 爱心形状瞳孔 | 高 |
| 被催眠/失神 | `no pupils`, `empty eyes`, `dazed` | 失神、无神 | 高 |
| 流口水 | `drooling`, `dripping saliva` | 流口水 | 高 |
| 翻白眼 | `rolling eyes`, `eye roll` | 翻白眼 | 中等 |
| 眯眼 | `squinting`, `narrowed eyes` | 眯起眼睛 | 低 |
| 盯着你 | `gazing at viewer`, `looking at viewer` | 注视观众 | 低 |
| 凝视远方 | `gazing into the distance` | 远望、深思 | 低 |
| 仰望天空 | `tilting head back and gazing upwards` | 抬头望天 | 低 |
| 暗堕/黑化 | `darkened expression`, `yandere face` | 黑化表情 | 极高 |
| 病娇 | `yandere smile`, `crazy obsessive look` | 病娇表情 | 极高 |
| 崩坏 | `distorted expression`, `broken smile` | 崩坏笑容 | 极高 |
| 阴暗爬行 | `dark gloomy expression`, `creepy smile` | 阴暗表情 | 高 |
| 享受表情 | `close your eyes and enjoy`, `blissful` | 闭眼享受 | 中等 |
| 脸红过热的蒸汽 | `overheating`, `steam from head`, `red face` | 头顶冒蒸汽 | 高 |
| 汗滴（尴尬） | `sweat drop`, `sweating nervously` | 紧张流汗 | 中等 |
| 尴尬笑容 | `awkward smile`, `nervous smile` | 尴尬的笑 | 中等 |
| 竖起大拇指 | `thumbs up and beaming` | 竖大拇指眉开眼笑 | 高 |
| 戴医用手套口罩 | `face with medical mask` | 戴口罩表情 | 无 |
| 唱歌 | `singing` | 唱歌表情 | 中等 |
| 舔嘴唇 | `licking lips` | 舔嘴唇 | 中等 |
| 紧闭双眼 | `eyes tightly shut` | 紧紧闭眼 | 中等 |
| 闭眼微笑 | `smiling with eye closed` | 闭眼微笑 | 低 |
| 闭眼大笑 | `laughing with eye closed` | 闭眼大笑 | 高 |
| 心醉/着迷 | `captivated`, `enchanted` | 入迷、陶醉 | 中等 |
| 嫉妒 | `jealous`, `envious` | 嫉妒表情 | 高 |
| 狂喜 | `ecstatic`, `overjoyed`, `euphoric` | 狂喜、极度兴奋 | 极高 |
| 安心/松了口气 | `relieved`, `at ease` | 安心表情 | 低 |
| 紧张 | `nervous`, `tense`, `anxious` | 紧张、不安 | 中等 |
| 疲惫 | `tired`, `exhausted`, `weary` | 疲惫、精疲力尽 | 中等 |
| 振作/加油 | `determined`, `guts pose`, `fighting spirit` | 决心、斗志 | 高 |
| 投降/放弃 | `giving up`, `resigned expression`, `orz` | 放弃表情 | 中等 |
| 装酷 | `cool expression`, `unfazed` | 故作镇定 | 低 |
| 腹黑的笑 | `sly smile`, `scheming expression` | 阴险的笑容 | 高 |

### 1.7 微表情与细节（Micro Expressions & Details）

| 中文 | 英文提示词 | 说明 |
|------|-----------|------|
| 眉毛上扬 | `raised eyebrows` | 惊讶或疑问 |
| 眉毛下垂 | `lowered eyebrows`, `furrowed brows` | 悲伤或愤怒 |
| 八字眉 | `sad eyebrows`, `upturned eyebrows` | 悲伤的眉毛 |
| 眉头紧锁 | `knitted brows`, `furrowed forehead` | 皱眉、苦恼 |
| 眼角含泪 | `tear at corner of eye`, `glistening eyes` | 眼睛湿润 |
| 瞳孔高光 | `catchlights in eyes`, `sparkling pupils` | 眼睛有神采 |
| 瞳孔失去高光 | `dead eyes`, `no catchlights`, `lifeless eyes` | 失神、绝望 |
| 嘴角微微上扬 | `slight smile`, `subtle smile` | 微妙的上扬 |
| 嘴角抽搐 | `twitching lips`, `trembling mouth` | 嘴角颤抖 |
| 咬嘴唇 | `biting lip`, `lip biting` | 紧张或诱惑 |
| 叹气 | `sighing`, `exhaling deeply` | 叹气、呼气 |
| 脸红到耳根 | `blushing to ears`, `red ears` | 极度害羞 |
| 脸红全身 | `full body blush`, `blushing all over` | 全身泛红 |
| 冒蒸汽 | `steam from head`, `head steaming` | 极度害羞/愤怒 |
| 青筋 | `vein pop`, `forehead vein` | 愤怒标志 |

---

## 2. 完整提示词模板示例

### 2.1 基础表情差分模板（SD 1.5/SDXL）

```text
【基础角色描述】
masterpiece, best quality, 1girl, solo, 
[character_description], 
[hairstyle], [eye_color], [clothing],

【表情关键词（替换此处）】
(smile:1.2), happy, looking at viewer, 

【画面质量】
ultra-detailed, highres, 8k uhd, 
simple background, white background, 
from front, portrait, upper body

【负面提示词】
Negative prompt: (worst quality:2), (low quality:2), (normal quality:2), 
lowres, bad anatomy, bad hands, text, error, missing fingers, extra digit, 
fewer digits, cropped, jpeg artifacts, signature, watermark, username, 
blurry, bad feet, mutated hands, poorly drawn hands, poorly drawn face, 
mutation, deformed, ugly, disfigured, extra limbs, extra arms, extra legs, 
missing arms, missing legs, fused fingers, too many fingers, long neck, 
cross-eyed, polar lowres, bad face, out of frame, oversaturated, overexposure
```

### 2.2 表情变化专用模板（ADetailer 图生图）

```text
【正向提示词 - 基础部分】
girl, [base_description], curly hair, in the dark, deep shadow

【ADetailer 表情提示词（在ADetailer面板中输入）】
(angry:1.5)        ← 愤怒表情，权重1.5
(smile:1.3)        ← 微笑表情，权重1.3  
(sad:1.4)          ← 悲伤表情，权重1.4
(crying:1.6)       ← 哭泣表情，权重1.6
(surprised:1.5)    ← 惊讶表情，权重1.5
(blushing:1.4)     ← 脸红表情，权重1.4

【负面提示词】
(worst quality:2), (low quality:2), (normal quality:2), lowres, 
watermark, badhandv4, ng_deepnegative_v1_75t
```

### 2.3 日系美少女表情差分模板（动漫风格）

```text
【正向提示词】
masterpiece, best quality, (full body:1.2), 1girl, 
long_hair, [hair_color], [eye_color], 
wearing [outfit], school_uniform, 
(chibi:1.2) standing, looking at viewer, 
[expression_keyword], cute, tiny, 
simple background, white background, 
ultra-detailed, anime style, illustration

【表情关键词替换列表】
- 通常/无表情: expressionless, neutral face
- 微笑: light smile, soft smile
- 开心: happy, cheerful, big smile
- 脸红: blushing, embarrassed, shy
- 生气: angry, pouting, frowning
- 哭泣: crying, tears, sad
- 惊讶: surprised, amazed, eyes wide open
- 困惑: confused, puzzled, tilting head
- 得意: smug, confident, proud
- 爱心眼: heart-shaped eyes, lovestruck
- 星星眼: star eyes, sparkling eyes
- 困倦: sleepy, drowsy, yawning

【负面提示词】
NSFW, (bad-artist:1.0), (worst quality, low quality:1.4), 
(bad_prompt_version2:0), bad anatomy, bad hands, missing fingers, 
(extra arms), deformed mutated disfigured, blurry, watermark, text
```

### 2.4 表情集/表情Sheet生成模板

```text
【生成多格表情集】
masterpiece, best quality, 1girl, solo, character_sheet, 
multiple_views, multiple_expressions, expression_sheet, 
reference_sheet, turnaround, 

expression: [neutral, happy, angry, sad, surprised, blushing], 

same character, consistent features, 
white background, simple background, 
from front, portrait, upper body, 
ultra-detailed, highres, anime style
```

### 2.5 Midjourney 表情差分提示词示例

```text
人物立绘，表情差分，[角色描述]，
白色短发，中分刘海发型，白色眉毛，白色睫毛，白色瞳孔，冷漠表情，
墨绿色联邦军服，合金战斗胸甲，合金战斗肩甲，战术腰带，合金战斗腿甲，
棕色军靴，破烂的黑色斗篷，手持AR系突击步枪，
二次元线稿风格，动漫风格，电影级画质，电影级光影，
空白背景，电影级滤镜，人物立绘，全身像

-- 英文版:
Character illustration, expression differentiation, tactical girl, 
white short hair, middle-parted bangs, white eyebrows, white eyelashes, 
white pupils, cold expression, dark green military uniform, 
alloy combat armor, two-dimensional line art style, anime style, 
cinematic quality, blank background, full-body image
```

### 2.6 日系少女漫画表情（Shoujo Style）

```text
"Anime girl with blushing cheeks, hands clasped nervously, 
cherry blossom petals falling around her, 
shoujo anime soft lighting, sparkle effects near face, 
romantic confession moment, pastel color palette, 
large sparkling eyes, emotional expression, delicate features"

"Anime character with large tears streaming down face, 
dramatic emotional moment, rain or symbolic water background, 
shoujo anime emotional climax, Your Lie in April intensity, 
shimmering eyes, quivering lips, hand on heart"
```

### 2.7 表情权重调整参考

```
权重范围建议:
- 微妙表情: 1.1 - 1.2  (slight smile:1.1)
- 标准表情: 1.3 - 1.5  (happy:1.3)
- 强烈表情: 1.5 - 1.8  (angry:1.6)
- 极端表情: 1.8 - 2.0  (crying:1.9)

注意: 权重超过2.0可能导致画面崩坏，建议配合ADetailer使用
```

---

## 3. 负面提示词（Negative Prompt）

### 3.1 通用负面提示词（适用于表情生成）

```text
(worst quality:2), (low quality:2), (normal quality:2), lowres, 
bad anatomy, bad hands, text, error, missing fingers, extra digit, 
fewer digits, cropped, jpeg artifacts, signature, watermark, username, 
blurry, bad feet, mutated hands, poorly drawn hands, poorly drawn face, 
mutation, deformed, ugly, disfigured, extra limbs, extra arms, extra legs, 
missing arms, missing legs, fused fingers, too many fingers, long neck, 
cross-eyed, polar lowres, bad face, out of frame, oversaturated, overexposure
```

### 3.2 表情专用负面提示词（防止面部崩坏）

```text
EasyNegativeV2, (badhandv4:1.2), 
(worst quality, low quality:1.4), 
(bad_prompt_version2:0), 
ng_deepnegative_v1_75t, 
mutated hands, poorly drawn hands, 
bad anatomy, bad proportions, 
extra limbs, missing limbs, 
malformed hands, fused fingers, 
too many fingers, long neck, 
cross-eyed, mismatched eyes, 
asymmetrical eyes, bad teeth, 
extra mouth, extra nose, 
unclear eyes, lifeless eyes, 
blank stare, dead eyes
```

### 3.3 动漫风格专用负面提示词

```text
NSFW, (bad-artist:1.0), (worst quality, low quality:1.4), 
(bad_prompt_version2:0), bad anatomy, bad hands, missing fingers, 
(extra arms), deformed, mutated, disfigured, blurry, watermark, text, 
3d, realistic, photo, photorealistic, western, cartoon, 
lowres, normal quality, jpeg artifacts, signature, username
```

### 3.4 写实/真人风格负面提示词

```text
(deformed, distorted, disfigured:1.3), poorly drawn, bad anatomy, 
wrong anatomy, extra limb, missing limb, floating limbs, 
(mutated hands and fingers:1.4), disconnected limbs, mutation, 
mutated, ugly, disgusting, blurry, amputation, 
3d, illustration, cartoon, flat, dull, 
plastic, doll-like, unrealistic skin, 
overexposed, underexposed, 
logo, text, watermark, signature, frame, border
```

---

## 4. 制作表情差分的方法与技巧

### 4.1 方法一：ADetailer 局部重绘（最推荐）

**来源**: AI图库吧 / AI奇点网 / CSDN教程
**适用**: Stable Diffusion WebUI (AUTOMATIC1111)

**步骤说明**:

1. **准备基础图片**
   - 在文生图或图生图生成一张满意的基础角色图
   - 或使用已有图片作为底图

2. **开启ADetailer**
   - 在生成参数下方找到「ADetailer」面板
   - 勾选「Enable this tab」启用功能

3. **选择检测模型**
   - `face_yolov8n.pt` — 适合真人/写实风格人脸
   - `face_yolov8s.pt` — 精度更高，适合部分遮挡的脸
   - `anime_face_yolov8.pt` — 专为动漫风格人脸优化 ★推荐
   - `hand_yolov8n.pt` — 如果需要同时修复手部

4. **在ADetailer中输入表情提示词**
   - 在 ADetailer 的 prompt 框中输入表情词
   - 使用权重增强效果，例如: `(angry:1.5)` 或 `(smile:1.3)`
   - 权重范围建议: 1.0 ~ 2.0，越大表情越强

5. **调整关键参数**
   - `Detection confidence`: 0.3 (默认，检测更多脸部)
   - `Mask blur`: 4-8 pixels (边缘柔化，越高越自然)
   - `Denoising strength`: 0.4-0.5 (重绘强度，0.45最佳起点)
   - `Inpaint steps`: 与主生成步数一致 (20-28)
   - `CFG scale`: 与主CFG一致或略低 (6-7)
   - `Inpaint padding`: 32 pixels (面部扩展区域)

6. **生成表情差分**
   - 保持基础图和种子不变
   - 仅修改ADetailer中的表情提示词
   - 每次生成一种表情，批量产出差分

**注意事项**:
- 动漫风格务必使用 `anime_face_yolov8.pt` 模型
- 权重超过2.0可能导致画面崩坏
- 如果表情变化不够明显，适当提高denoising strength到0.5-0.6
- 面部被刘海遮挡时，可先用Photoshop处理遮挡物

**参考参数示例**:
```json
{
  "ADetailer model": "anime_face_yolov8.pt",
  "ADetailer confidence": 0.3,
  "ADetailer dilate erode": 16,
  "ADetailer mask blur": 8,
  "ADetailer denoising strength": 0.45,
  "ADetailer inpaint only masked": true,
  "ADetailer inpaint padding": 32,
  "ADetailer steps": 20,
  "ADetailer cfg scale": 7.0
}
```

---

### 4.2 方法二：ControlNet + 局部重绘（Inpaint）

**来源**: 日本AI Arty教程 / 百度贴吧讨论
**适用**: 需要更高精度控制时

**步骤说明**:

1. **准备基础图**
   - 先生成或准备一张基础立绘

2. **进入图生图 - 局部重绘（Inpaint）**
   - 上传基础图
   - 用画笔涂抹面部区域（需要重绘的区域）

3. **开启ControlNet**
   - 使用 `ControlNet Inpaint` 模型
   - 或同时使用 `Canny` / `Lineart` 保持整体轮廓
   - 上传同一张图作为ControlNet输入

4. **调整图生图参数**
   - `Denoising strength`: 0.3-0.5 (越低越像原图，仅改表情)
   - 保持种子和参数一致

5. **修改表情提示词**
   - 在正向提示词中替换表情关键词
   - 例如将 `smile` 改为 `angry` 或 `crying`

6. **配合ControlNet保持姿势**
   - 使用 `ControlNet OpenPose` 保持姿势一致
   - 使用 `ControlNet Canny` 保持线条一致

**进阶技巧**:
- 服装差分 + 表情差分同时做：先用ControlNet Inpaint做服装，再用ADetailer做表情
- 制作三面图/姿势差分：使用 `ControlNet OpenPose` 固定骨骼姿势

---

### 4.3 方法三：LivePortrait 表情迁移（视频→表情帧）

**来源**: 站酷ZCOOL / 知乎教程
**适用**: 已有静态立绘，需要快速量产多种表情

**核心逻辑**: 用"表演"代替"手绘"——你对着摄像头做表情，AI把表情迁移到纸片人脸上。

**步骤说明**:

1. **准备"面瘫"素体 (Photoshop)**
   - 打开Photoshop，裁切立绘的头部和肩部区域
   - 确保五官清晰，没有刘海遮挡眼睛（如有遮挡，分层处理）
   - 保存为 `Base_Character.jpg`

2. **录制驱动视频 (手机相机)**
   - 打开手机相机，切换到视频模式
   - 固定机位，保持头部在画面中央
   - 依次做出所需表情：轻蔑（嘴角上扬）、大笑（张嘴闭眼）、惊恐（瞳孔缩小）、害羞、愤怒等
   - 关键：动作幅度要比平时大20%，AI识别更精准
   - 保存为 `Driving_Video.mp4`

3. **LivePortrait 表情迁移**
   - 打开LivePortrait（WebUI或Python版）
   - Source Image: 上传 `Base_Character.jpg`
   - Driving Video: 上传 `Driving_Video.mp4`
   - Settings:
     - 开启 `Relative Motion` (相对运动) — 保证头身位置不乱跑
     - 开启 `Lip Sync` (唇形同步) 增强
   - 生成视频

4. **视频转图层 + 提取关键帧 (Photoshop)**
   - PS中: 文件 > 导入 > 视频帧到图层
   - 选择 `LivePortrait_Output.mp4`
   - 在时间轴上找到表情最到位的几帧
   - 删除过渡帧，只保留需要的表情瞬间
   - 修补细节：LivePortrait对牙齿/舌头还原可能不够二次元
     - 用选区工具框选嘴巴内部
     - 提示词: `anime style tongue, sharp teeth, clean lines`
   - 将图层分别导出，完成差分

5. **进阶：瞳孔与视线控制**
   - 录制视频时眼球上下左右转动
   - 生成素材直接作为"视线差分"使用
   - 如果原画是特殊"星星眼"或"爱心眼"，用图层蒙版把原画眼珠子挖出来叠在生成眼眶上

**工具获取**:
- LivePortrait GitHub: https://github.com/KwaiVGI/LivePortrait
- 有WebUI版本和ComfyUI节点可用

---

### 4.4 方法四：AdvancedLivePortrait（进阶动态表情）

**来源**: 知乎 / 腾讯云开发者社区
**适用**: ComfyUI环境，需要更精细控制

**特点**:
- 可以精确控制眉毛、眼睛、嘴巴的每个部分
- 支持闭眼修复、僵硬表情修复
- 可以在ComfyUI中直接作为节点使用

**流程**:
1. 在ComfyUI中搭建工作流（FLUX大模型 + 风格LoRA）
2. 上传漫画人物，调整参数
3. 输出表情差分

---

### 4.5 方法五：Photoshop 手动 + 生成式填充（传统+AI混合）

**来源**: 百度贴吧讨论
**适用**: 需要最高精度商业级输出时

**步骤**:
1. Photoshop识别角色，一键抠图出来（白底/透明底）
2. 丢进img2img，按想要的蒙版范围（脸部差分、肢体差分）进行局部重绘
3. 重绘幅度控制：调低（0.3-0.5）则姿势/表情微调，调高（0.6+）则区域重画
4. 最后再合成进原图背景，实现整套图的差分

**建议**:
- 用提示词或LoRA确定人物
- 用ControlNet骨骼/OpenPose确定姿势
- 用局部重绘控制人物表情
- 制作同人动漫推荐Illustrious模型

---

### 4.6 参数对比表

| 方法 | 推荐模型 | 适用场景 | 效率 | 精度 | 学习成本 |
|------|---------|---------|------|------|---------|
| ADetailer | anime_face_yolov8.pt | 快速批量生成 | ★★★★★ | ★★★★ | 低 |
| ControlNet Inpaint | control_v11p_sd15_inpaint | 精细控制局部 | ★★★ | ★★★★★ | 中 |
| LivePortrait | LivePortrait WebUI | 已有立绘快速量产 | ★★★★★ | ★★★★ | 中 |
| AdvancedLivePortrait | ComfyUI节点 | 专业级精细调整 | ★★★ | ★★★★★ | 高 |
| PS + 生成式填充 | Stable Diffusion / Photoshop | 商业级输出 | ★★ | ★★★★★ | 高 |

---

### 4.7 提示词权重使用技巧

```
Stable Diffusion权重语法:
- (word)        = 权重1.1
- (word:1.3)   = 权重1.3  
- ((word))      = 权重1.21 (1.1*1.1)
- [word]        = 权重0.9
- [word:0.5]    = 权重0.5

表情控制建议:
- 基础表情权重: 1.1-1.3
- 标准表情权重: 1.3-1.5
- 强烈表情权重: 1.5-1.8
- 极端表情权重: 1.8-2.0

组合示例:
- (angry:1.5), (frowning:1.2)           = 愤怒+皱眉
- (blushing:1.4), (shy:1.2), (looking down:1.1) = 害羞脸红低头
- (surprised:1.5), (wide eyes:1.3), (mouth agape:1.2) = 震惊张嘴
- (crying:1.6), (tearful eyes:1.4), (trembling lips:1.2) = 哭泣
```

---

## 5. 关键来源与参考链接

### 5.1 中文教程来源

| 来源 | URL | 内容摘要 |
|------|-----|---------|
| CSDN - 62个SD表情提示词 | https://blog.csdn.net/qq_20288327/article/details/129354498 | 整理了62种不同表情提示词，分为开心、海报、害羞、其他等分类 |
| 知乎 - SD表情提示词大全 | https://zhuanlan.zhihu.com/p/650573538 | 大量表情词汇中英文对照，含醉酒、催眠等特殊表情 |
| 知乎 - 网上收集SD表情提示词 | https://zhuanlan.zhihu.com/p/651648278 | 筛选实际跑出来效果不错的表情词 |
| 知乎 - AdvancedLivePortrait | https://zhuanlan.zhihu.com/p/28884062130 | 漫画立绘表情差分+写真表情修复 |
| AI图库吧 - ADetailer控制表情 | https://www.aituku.cc/info/355.html | ADetailer表情控制详细教程，含参数设置 |
| AI奇点网 - ADetailer表情 | https://www.aieva.cn/edu/750.html | After Detailer插件控制表情教程 |
| 智汇AI - ADetailer表情 | https://ai.gameba.cc/wz/3327.html | 同上，ADetailer表情控制 |
| 站酷 - LivePortrait表情差分 | https://m.zcool.com.cn/article/ZMTY5ODg5Ng==.html | LivePortrait+PS量产AVG游戏表情差分 |
| 腾讯云 - LivePortrait | https://cloud.tencent.com/developer/news/2280263 | AdvancedLivePortrait动态表情修改 |
| 百度贴吧 - 表情差分讨论 | https://tieba.baidu.com/p/9474364948 | 社区讨论如何保持图片一致做表情差分 |
| 知乎 - AI表情提示词实战 | https://blog.csdn.net/2600_94960044/article/details/157039616 | AI表情提示词实战指南，模型响应特性对比 |
| 知乎 - 局部修改表情 | https://www.zhihu.com/pin/1639155185720172544 | SD局部重绘修改表情技巧 |
| 微信公众号 - ControlNet | http://mp.weixin.qq.com/s?__biz=MzE5OTM3MTA5OQ== | ControlNet图像生成精准控制 |
| 微信公众号 - 视频生成提示词 | http://mp.weixin.qq.com/s?__biz=Mzk0NDY4MDQ5NQ== | 多个连续动作提示词技巧 |
| 微信公众号 - AI表情提示词 | https://mp.weixin.qq.com/s/p2ajjkER-Ydan54nEKicOQ | AI视频表情多样性，万能提示词公式 |

### 5.2 日文/国际来源

| 来源 | URL | 内容摘要 |
|------|-----|---------|
| AI Arty日本 - SD立ち絵表情差分 | https://jp.aiarty.com/image-generator/character-sprite-stable-diffusion.htm | 立ち絵生成、表情差分、服装差分完整教程 |
| BOOTH - 美少女立ち絵素材 | https://booth.pm/ja/items/6903136 | AI生成美少女立ち絵，含6种表情差分（通常/笑顔/赤面/困り/泣き/驚き） |
| VTuber用语 - 表情差分 | https://unbereal.co.jp/vtuberaudition/vtuber_terminology/ | 表情差分定义，一般5-6种覆盖喜怒哀楽 |
| GENSEKI - 立ち絵仕様 | https://genseki.me/compes/gKLWJLneP8n | 专业立ち絵表情差分规格，含微笑/困る/照れる/泣く等制作标准 |
| TopFreePrompts - Sora Anime | https://www.topfreeprompts.com/sora-anime-prompts/ | 含Blushing Confession等少女漫画表情提示词 |
| Anifusion - Anime Prompt Builder | https://anifusion.ai/free-tools/anime-prompt-builder/ | tag-style anime prompt构建工具 |
| PromptBase - Anime Character | https://promptbase.com/prompt/anime-character-designs-6 | 表情可变的动漫角色设计模板 |
| ADetailer GitHub | https://github.com/Bing-su/adetailer | 官方文档，检测模型、参数设置 |
| ADetailer讨论 - SD vs ADetailer | https://github.com/Bing-su/adetailer/discussions/660 | 主提示词与ADetailer提示词的区别说明 |
| Kindanai - SD发型提示词 | https://kindanai.com/en/prompt-bangs-stable-diffusion/ | 动漫发型提示词测试（Anything, MeinaMix等） |

### 5.3 样例与工具网站

| 来源 | URL | 内容摘要 |
|------|-----|---------|
| Midjourney中文站 - 表情差分 | https://www.midjourny.cn/mj-detail/mj-detail251638_1.html | 战术少女表情差分，含冷漠/微笑/惊讶等 |
| Artvy - Anime Prompts | https://www.artvy.ai/prompt/ | 多种动漫风格提示词库 |
| WriteForUs - SD Anime Prompts | https://www.writeforustechnology.com/stable-diffusion-anime-prompt/ | Top 20 anime prompts，含表情场景 |
| Emojicombos - Anime Blush | https://emojicombos.com/anime-blush-cry | 颜文字级别的脸红表情分类 |
| Emojicombos - Positive Overflow | https://emojicombos.com/positive-emotion-overflow | 动漫情感表情分类 |
| EasyDrawing - Anime Expressions | https://easydrawingguides.com/how-to-draw-anime-and-manga-facial-expressions/ | 手绘教程含sad/happy/embarrassed/crying/blushing/angry等 |
| Alibaba - SD vs FLUX Anime | https://www.alibaba.com/product-insights/... | FLUX.1 Pro vs SD3 动漫表情提示词对比测试 |

---

## 6. 样例图片与素材资源

### 6.1 教程样例图（从来源中提取）

**ADetailer表情控制样例**（来源：AI图库吧）
- 原始图: https://www.aituku.cc/uploadfile/2024/1224/f96b075cc8dc1b30a994507d26d7cfe4.jpg
- 愤怒表情: https://www.aituku.cc/uploadfile/2024/1224/2af25e70cd1e693ca707286064cbed99.png
- 微笑表情: https://www.aituku.cc/uploadfile/2024/1224/6923f5c4d681f294ff451e9d44fddd81.png
- 插件界面: https://www.aituku.cc/uploadfile/2024/1224/179ffff578809d8d087e5783c0f8680b.png
- 模型选择: https://www.aituku.cc/uploadfile/2024/1224/fc4de976680e0213d9767b5622f01887.png
- 权重设置: https://www.aituku.cc/uploadfile/2024/1224/9871df7d8ea64718b03f6096d201dddf.png

**日本AI Arty教程图**（来源：jp.aiarty.com）
- 立ち絵示例: https://jp.aiarty.com/images/seo-img/lazy-img.png
- ADetailer界面: https://jp.aiarty.com/images/seo-img/lazy-img.png
- 表情差分示例: https://jp.aiarty.com/images/seo-img/lazy-img.png

**LivePortrait效果展示**（来源：站酷ZCOOL）
- 站酷文章配图: https://m.zcool.com.cn/article/ZMTY5ODg5Ng==.html

### 6.2 可购买/下载的表情差分素材

**BOOTH - 美少女立ち絵素材 Vol.1**
- URL: https://booth.pm/ja/items/6903136
- 内容：
  - 全身立ち絵（背景透過PNG形式）
  - 表情差分6種（通常／笑顔／赤面／困り／泣き／驚き）
  - 解像度：縦長 1152×2016
- 价格：参考价格（日元）
- 许可：個人・同人・商用利用すべて可能、改変可、クレジット表記任意

### 6.3 模型推荐

| 类型 | 推荐模型 | 适用场景 |
|------|---------|---------|
| 动漫/二次元 | AnythingV5, MeinaMix, Counterfeit-V3.0 | 日系美少女表情生成 |
| 写实/真人 | majicMIX realistic, RealisticVision | 真人风格表情控制 |
| 综合/高质量 | DreamShaper, AbyssOrangeMix3 | 通用高质量表情 |
| 最新动漫 | Illustrious | 2024年后新动漫风格 |
| SDXL动漫 | AnimagineXL, KohakuXL | SDXL大分辨率动漫 |

### 6.4 LoRA推荐（用于表情/风格控制）

| LoRA名称 | 功能 | 适用 |
|----------|------|------|
| 表情增强LoRA | 增强表情表现力 | 通用 |
| 特定角色LoRA | 保持角色一致性 | 做同角色差分必备 |
| 画风LoRA | 统一画风 | 系列表情产出 |
| 粘土风LoRA | 特殊风格 | 配合FLUX使用 |
| 国风汉服LoRA | 国风角色 | 古风表情差分 |

---

## 附录：快速检索表

### 按场景分类

**恋爱/告白场景**:
`blushing`, `shy`, `heart-shaped eyes`, `lovestruck`, `nervous smile`, `hands clasped`, `softly smiling`, `teary eyes`, `happy tears`

**战斗/热血场景**:
`determined`, `gritting teeth`, `serious expression`, `fighting spirit`, `angry`, `focused`, `shouting`, `confident smirk`

**日常/轻松场景**:
`smile`, `happy`, `cheerful`, `relaxed`, `playful`, `mischievous`, `yawning`, `sleepy`, `eating`, `singing`

**悲伤/离别场景**:
`crying`, `tears`, `sad`, `depressed`, `gloomy`, `tearful eyes`, `downturned lips`, `waving goodbye`, `trembling lips`

**震惊/发现场景**:
`surprised`, `shocked`, `wide eyes`, `mouth agape`, `pupil shrink`, `flustered`, `confused`, `bewildered`

**喜剧/搞笑场景**:
`laughing`, `grinning`, `thumbs up`, `winking`, `tongue out`, `silly face`, `exaggerated expression`, `chibi shocked`

---

## 更新日志

- **2025-06**: 初版收集完成，涵盖62+种表情关键词、5种制作方法、多个来源参考
- 收集关键词数量：约100+个表情提示词（含中英文对照）
- 收集来源数量：20+个网站/教程
- 覆盖方法：ADetailer、ControlNet、LivePortrait、AdvancedLivePortrait、Photoshop混合

---

> 免责声明：本资料仅用于AI绘画学习和研究目的。使用AI生成内容时，请遵守各平台服务条款和当地法律法规。部分来源内容为网络公开资料整理，版权归原作者所有。
