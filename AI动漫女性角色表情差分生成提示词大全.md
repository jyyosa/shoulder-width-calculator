# AI 动漫女性角色表情差分生成提示词资源大全（整合版）

> **收集来源**：Bilibili、知乎、CSDN、百度贴吧、微信公众号、Civitai、Reddit、BOOTH、日本 AI 教程社区（jp.aiarty、runrunsketch、withballoons、qbei 等）、Midjourney、PromptBase、Kalon.ai、ReShot.ai、Anifusion 等
> **适用工具**：Stable Diffusion / AUTOMATIC1111 / Forge / ComfyUI / NovelAI / Midjourney / FLUX 等
> **文档规模**：约 300+ 表情关键词｜7 种核心制作方法｜30+ 来源 URL｜20+ 样例图片链接
> **收集日期**：2025 年

---

## 目录

1. [表情关键词总表（中英对照）](#一表情关键词总表中英对照)
2. [完整提示词模板示例](#二完整提示词模板示例)
3. [负面提示词（Negative Prompt）](#三负面提示词negative-prompt)
4. [制作表情差分的方法与技巧](#四制作表情差分的方法与技巧)
5. [推荐工具、LoRA 与扩展](#五推荐工具lora-与扩展)
6. [样例图片与素材资源](#六样例图片与素材资源)
7. [来源参考与资源链接](#七来源参考与资源链接)

---

## 一、表情关键词总表（中英对照）

### 1. 基础笑容 / Happy & Smiling

| 中文 | 英文提示词 | 强度 | 说明 |
|------|-----------|------|------|
| 微笑 | `smile` / `smiling` | 中 | 最基础、最常用的表情 |
| 浅笑 | `light smile` | 低 | 轻微、柔和的笑意 |
| 露齿笑 | `grin` / `grinning` | 中 | 咧嘴露出牙齿 |
| 坏笑 | `smirk` / `evil smile` | 中 | 带点狡黠或邪恶 |
| 大笑 | `laughing` / `laugh` | 高 | 开怀大笑、出声 |
| 咯咯笑 | `chuckling` | 低 | 轻声偷笑 |
| 得意 | `smug` / `doyagao` | 中 | 自信满满、炫耀 |
| 开心 | `happy` / `cheerful` / `jolly` | 高 | 心情愉悦 |
| 愉快 | `pleased` / `amused` | 中 | 满意、被逗乐 |
| 兴奋 | `excited` | 高 | 激动、亢奋 |
| 温柔微笑 | `softly smiling` / `gentle smile` | 低 | 治愈系柔和微笑 |
| 闭眼微笑 | `smiling with eyes closed` | 低 | 幸福、满足 |
| 灿烂笑容 | `beaming smile` / `twinkle smile` | 高 | 眼睛发光的笑容 |
| 幸福 | `happy` / `blissful` | 高 | 幸福感满满 |
| 骄傲 | `proud` / `confident` | 中 | 成就感、自豪 |
| 元气 | `energetic` / `goddess-like happiness` | 高 | 元气满满 |

### 2. 愤怒与烦躁 / Angry & Irritated

| 中文 | 英文提示词 | 强度 | 说明 |
|------|-----------|------|------|
| 生气 | `angry` | 中 | 标准愤怒 |
| 激怒 | `furious` / `rage` | 极高 | 暴怒、狂怒 |
| 皱眉 | `frowning` / `frown` / `furrowed brow` | 中 | 不高兴、不满 |
| 恼怒 | `annoyed` / `irritated` / `exasperated` | 中 | 烦躁、不耐烦 |
| 暴躁 | `grumpy` | 中 | 脾气坏 |
| 怨恨 | `resentful` / `indignant` | 中 | 积怨、愤慨 |
| 大喊 | `shouting` / `screaming` | 极高 | 尖叫、大喊 |
| 咬牙切齿 | `gritting teeth` / `clenched teeth` | 高 | 强忍愤怒/痛苦 |
| 怒视 | `scowl` / `glaring` / `glowering look` | 高 | 凶狠瞪视 |
| 眯眼（危险） | `narrowed eyes` | 低 | 愤怒/危险的眼神 |
| 青筋暴起 | `anger vein` / `vein popping` / `forehead vein` | 极高 | 日系动漫愤怒特效 |
| 涨红脸 | `reddened face` / `flushed face` | 高 | 愤怒到脸红 |
| 蔑视 | `contemptuous` / `scornful` / `disdainful` | 高 | 轻蔑俯视 |
| 厌恶 | `disgust` / `disgusted` | 高 | 嫌弃、反感 |
| 闹别扭 | `sulking` / `pouting` | 低 | 赌气、不开心 |
| 假笑怒 | `smiling with veins` | 极高 | 生气但保持微笑（日系经典） |

### 3. 悲伤与哭泣 / Sad & Crying

| 中文 | 英文提示词 | 强度 | 说明 |
|------|-----------|------|------|
| 悲伤 | `sad` / `sorrowful` | 中 | 标准悲伤 |
| 忧郁 | `melancholy` / `gloomy` / `somber` | 高 | 深沉忧伤、阴郁 |
| 沮丧 | `depressed` / `dejection` | 高 | 消沉、低落 |
| 哭泣 | `crying` / `cry` | 高 | 流泪哭泣 |
| 眼泪 | `tears` / `tearful` | 中 | 有泪/泪汪汪 |
| 泪眼 | `watery eyes` / `teary eyes` / `teary-eyed` | 高 | 含泪的眼睛 |
| 啜泣 | `sobbing` / `sob` | 极高 | 抽泣、嚎哭 |
| 流泪滑落 | `streaming tears` / `tears streaming down face` | 极高 | 眼泪流下脸颊 |
| 欲哭无泪 | `on the verge of tears` / `trembling lips` | 高 | 强忍泪水 |
| 心碎 | `heartbroken` | 高 | 极度悲伤 |
| 绝望 | `despairing` / `despair` / `deep sorrow` | 极高 | 深度绝望 |
| 失望 | `disappointed` / `regrettable` | 中 | 遗憾、期望落空 |
| 寂寞 | `lonely` | 中 | 孤独感 |
| 脸色苍白 | `turn pale` / `pale face` | 高 | 因悲伤/恐惧失色 |
| 喜极而泣 | `crying with joy` / `joyful tears` | 高 | 开心的泪水 |
| 感动流泪 | `moved tears` / `touched tears` | 中 | 被感动 |
| 释然的泪 | `relieved tears` | 中 | 安心哭泣 |
| 默默哭泣 | `suppressed crying` / `quiet crying` | 高 | 压抑的哭泣 |
| 擦眼泪 | `wiping tears` | 中 | 用手擦泪的动作 |
| 苦笑 | `sad smile` / `bitter smile` | 中 | 悲伤的微笑 |
| 破涕为笑 | `crying smile` / `laughing through tears` | 高 | 又哭又笑 |

### 4. 惊讶与震惊 / Surprised & Shocked

| 中文 | 英文提示词 | 强度 | 说明 |
|------|-----------|------|------|
| 惊讶 | `surprised` / `surprise` | 中 | 标准惊讶 |
| 震惊 | `shocked` / `astonished` / `stunned` | 极高 | 强烈冲击 |
| 目瞪口呆 | `dumbfounded` / `flabbergasted` / `mouth agape` | 极高 | 嘴巴大张 |
| 愣住 | `stunned` / `taken aback` | 高 | 惊呆 |
| 睁大眼睛 | `wide eyes` / `wide-eyed` / `eyes widened` | 高 | 眼睛张大 |
| 瞳孔放大 | `dilated pupils` / `pupils dilated` | 中 | 惊讶/恐惧生理反应 |
| 瞳孔收缩 | `constricted pupils` / `pupil shrink` | 高 | 惊恐时瞳孔缩小 |
| 恐慌 | `panicking` / `flustered` / `upset` | 高 | 惊慌失措 |
| 恐惧 | `scared` / `frightened` / `afraid` | 高 | 害怕 |
| 恐怖 | `horrified` / `terrified` / `petrified` | 极高 | 极度恐惧、吓到石化 |
| 背脊发凉 | `spine-chilling` | 高 | 恐怖氛围 |
| 发抖 | `trembling` / `shivering` | 中 | 生理恐惧反应 |
| 尖叫 | `screaming` | 高 | 恐惧大叫 |
| 眉毛上挑 | `raised eyebrows` | 低 | 惊讶或疑问 |
| 挑眉 | `one eyebrow raised` | 低 | 怀疑/好奇/嘲讽 |
| 好奇 | `curious` / `interested` | 低 | 好奇、感兴趣 |
| 困惑 | `confused` / `bewildered` / `puzzled` | 中 | 迷茫、不解 |
| 怀疑 | `questioning look` / `doubtful` / `suspicious` | 中 | 不信任 |
| 慌张 | `flustered` / `startled` | 高 | 手忙脚乱 |
| 尴尬笑容 | `awkward smile` / `nervous smile` | 中 | 尴尬的笑 |
| 波浪嘴（日系） | `wavy mouth` | 中 | 日系漫画式惊讶嘴型 |

### 5. 害羞与脸红 / Shy & Blushing

| 中文 | 英文提示词 | 强度 | 说明 |
|------|-----------|------|------|
| 害羞 | `shy` / `shyness` | 中 | 腼腆 |
| 脸红 | `blushing` / `blush` | 中 | 面颊泛红 |
| 尴尬 | `embarrassed` | 中 | 难为情 |
| 慌张 | `flustered` | 高 | 手忙脚乱 |
| 害羞低头 | `blushing and looking down` | 高 | 害羞低头 |
| 强烈脸红 | `intense blush` / `heavy blush` / `blushing hard` | 高 | 突然脸红、强烈反应 |
| 极度害羞 | `overwhelmed blush` / `bashful` | 极高 | 慌乱不知所措 |
| 鼻子红 | `nose blush` | 中 | 日系特有：鼻子变红 |
| 满脸通红 | `full-face blush` / `full face blush` | 高 | 极度害羞 |
| 耳朵红 | `blushing ears` / `red ears` / `ear blush` | 高 | 害羞到耳朵 |
| 热脸颊 | `hot cheeks` / `burning cheeks` | 高 | 脸颊发烫 |
| 微红 | `light blush` | 低 | 轻微脸红 |
| 害羞到哭 | `shy crying` / `bashful tears` | 高 | 害羞到流泪 |
| 恋爱表情 | `lovestruck` / `heart eyes` | 高 | 爱心眼、迷恋 |
| 诱惑 | `seductive smile` / `seductive face` | 中 | 魅惑微笑 |
| 困窘 | `bashful` / `flustered` | 高 | 羞答答 |
| 脸红出汗 | `nervous sweating + blush` | 高 | 紧张害羞 |
| 羞涩 | `embarrassed, nose blush` | 高 | 日系组合 |

### 6. 无表情与冷漠 / Neutral & Cold

| 中文 | 英文提示词 | 强度 | 说明 |
|------|-----------|------|------|
| 无表情 | `expressionless` / `neutral face` | 无 | 面瘫、扑克脸 |
| 严肃 | `serious` / `serious-looking` / `serious face` | 低 | 认真、严肃 |
| 冷静 | `calm` / `tranquil` | 低 | 平静 |
| 放松 | `relaxed` | 低 | 放松状态 |
| 冷漠 | `indifferent` / `aloof` / `cold expression` | 低 | 疏远、漠不关心 |
| 无聊 | `bored` / `unamused` | 无 | 厌倦、无趣 |
| 淡然 | `poker face` | 无 | 隐藏情绪 |
| 装酷 | `cool expression` / `unfazed` | 低 | 故作镇定 |
| 空灵 | `blank stare` / `spaced out` | 无 | 发呆、天然呆 |
| 闭眼 | `eyes closed` / `eyes shut` | 无 | 睡觉/享受 |
| 紧闭双眼 | `eyes tightly shut` | 中 | 痛苦/恐惧/强烈情绪 |
| 凝视 | `staring` / `gazing intently` | 低 | 专注/强烈情感 |
| 凝视远方 | `gazing into the distance` | 低 | 思考/惆怅 |
| 盯着你 | `gazing at viewer` / `looking at viewer` | 低 | 注视观众 |
| 向下看 | `looking down` / `gazing down` | 低 | 害羞/思考/悲伤 |
| 向上看 | `looking up` / `gazing up` | 低 | 期待/祈祷 |
| 看向侧面 | `looking to the side` / `side glance` | 低 | 回避/偷看 |
| 回头看 | `looking back` / `turning head` | 低 | 惊讶/警惕 |
| 释然 | `relieved` / `at ease` | 低 | 安心、松了口气 |
| 专注 | `focused` / `concentrated` | 低 | 集中注意力 |
| 困倦 | `sleepy` / `drowsy` / `yawning` | 低 | 想睡、打哈欠 |
| 疲惫 | `tired` / `exhausted` / `weary` | 中 | 精疲力尽 |
| 振作 | `determined` / `fighting spirit` | 高 | 决心、斗志 |
| 投降 | `giving up` / `resigned expression` / `orz` | 中 | 放弃、认输 |

### 7. 日系/二次元特有表情 / Anime-Specific

| 中文 | 英文提示词 | 日文 | 强度 | 说明 |
|------|-----------|------|------|------|
| 傲娇 | `tsundere expression` / `tsundere face` | ツンデレ | 中 | 傲娇、撅嘴 |
| 撅嘴 | `pouting` / `pouty` | 口を尖らす | 中 | 嘟嘴、不高兴 |
| 星星眼 | `star eyes` / `star-shaped eyes` / `sparkling eyes` | 星目 / キラキラ目 | 高 | 闪闪发光、崇拜 |
| 爱心眼 | `heart-shaped eyes` / `heart eyes` / `heart-shaped pupils` | ハート目 | 高 | 爱心形状瞳孔、恋爱 |
| 死鱼眼 | `half-closed eyes` / `droopy eyes` / `jitome` / `unamused` | ジト目 | 低 | 无语、鄙视 |
| 三白眼 | `sanpaku` | 三白眼 | 低 | 眼白较多 |
| 吊眼/上挑眼 | `tsurime` | ツリ目 | 低 | 强势、锐利 |
| 下垂眼 | `tareme` | タレ目 | 低 | 无辜、柔弱 |
| 得意脸 | `smug` / `doyagao` | ドヤ顔 | 中 | 自信炫耀 |
| 病娇 | `yandere face` / `yandere smile` / `crazy obsessive look` | ヤンデレ顔 | 极高 | 病态爱意、黑化 |
| 黑化 | `darkened expression` / `dark smile` / `yangire face` | 暗堕 | 极高 | 黑化/暴力倾向 |
| 崩坏 | `distorted expression` / `broken smile` | 壊れた笑顔 | 极高 | 崩坏笑容 |
| 阴险笑 | `sly smile` / `scheming expression` / `cunning grin` | にやり | 高 | 反派式冷笑 |
| 腹黑 | `hidden intent` / `scheming smile` | 腹黒 | 高 | 内心算计 |
| 天然呆 | `airhead expression` / `spaced out` / `blank stare` | 天然 | 无 | 天然呆 |
| 恍惚 | `afterglow` / `blank eyes` / `dazed` / `ecstasy` | 恍惚 | 高 | 失神/极度享受 |
| 流口水 | `drooling` / `dripping saliva` / `messy hair, open mouth` | よだれ | 高 | 失神/贪吃 |
| 翻白眼 | `rolling eyes` / `eye roll` / `eyes rolled back` | 目を白黒 | 中 | 无语/晕厥 |
| 眯眼 | `squinting` / `narrowed eyes` | 目を細める | 低 | 怀疑/聚焦 |
| 头顶冒蒸汽 | `overheating` / `steam from head` / `head steaming` | 頭から湯気 | 高 | 极度害羞/愤怒 |
| 汗滴（尴尬） | `sweat drop` / `sweating nervously` / `anime sweat drop` | 大粒の汗 | 中 | 紧张流汗 |
| 冷汗 | `cold sweat` | 冷や汗 | 中 | 害怕/尴尬 |
| 瀑布汗 | `sweating profusely` / `waterfall sweat` | 滝汗 | 高 | 极度紧张 |
| 脸红对话框 | `spoken blush` / `blush stickers` | ほっぺの丸 | 中 | 漫画式圆形腮红 |
| 愤怒符号 | `anger vein` / `vein pop` | 怒りマーク | 极高 | 青筋漫画特效 |
| 石化 | `turned to stone` / `frozen` / `petrified` | 石化 | 高 | 震惊过度 |
| 灵魂出窍 | `ghost leaving body` / `spirit floating` / `vacant eyes` | 魂抜け | 极高 | 极度震惊 |
| 画圈圈 | `depression spiral` / `background lines` | 落ち込み | 中 | 失落石化 |
| 炸毛 | `hair fluffed up` / `messy hair from shock` / `ahoge` | 逆毛 / アホ毛 | 低 | 惊吓、呆毛翘起 |
| 被催眠 | `hypnotized` / `empty eyes` / `no pupils` / `hollow eyes` | 催眠 | 高 | 失神、无神 |
| 漩涡眼 | `swirl eyes` / `@_@` | ぐるぐる目 | 中 | 眩晕 |
| 猫嘴 | `:3 mouth` / `cat mouth` | 猫口 | 低 | 可爱、调皮 |
| 三角形嘴 | `triangle mouth` / `small mouth` | △口 | 低 | 惊讶、可爱 |
| 栗子嘴 | `chestnut mouth` | 栗のような口 | 低 | 日系特色嘴型 |
| 无嘴/点嘴 | `no mouth` / `dot mouth` | 小さな口 | 无 | 极简嘴型 |
| 波嘴 | `wavy mouth` | 波打つ口 | 中 | 惊讶/尴尬波浪嘴 |
| 恳求 | `Pleading` / `begging eyes` | 哀願 | 高 | 哀求眼神 |
| 困窘 | `troubled face` / `worried` / `sweatdrop` | 困り顔 | 中 | 困扰为难 |
| 掩饰害羞 | `looking away, blushing` / `tsundere` | 照れ隠し | 中 | 傲娇式害羞 |
| 气鼓鼓 | `puffed cheeks` / `pout` + `angry` | ぷんすか | 中 | 生气鼓脸 |
| 不满 | `frown` / `unamused` / `furrowed brow` | ムスッ | 低 | 不高兴 |
| 得意挺胸 | `proud chest puffed out` | 得意げ | 高 | 自豪 |
| 垂头丧气 | `hanging head` / `shoulders drooping` | 肩を落とす | 中 | 沮丧 |
| 抱头蹲防 | `crouching with head in hands` | 頭を抱える | 高 | 害怕/崩溃 |
| 手指戳戳 | `poking fingers together` / `fidgeting` | 指をもじもじ | 低 | 紧张害羞 |
| 咬手帕 | `biting handkerchief` / `teary biting` | ハンカチを噛む | 中 | 委屈/嫉妒 |
| 投降 | `raised hands` / `orz` / `exhausted expression` | orz | 中 | 认输 |
| 嫉妒 | `jealous` / `envious` / `jealous eyes` | 嫉妬 | 高 | 嫉妒眼红 |
| 吃醋 | `puffed cheeks + angry eyebrows + pouting` | 嫉妬 | 中 | 吃醋表情 |
| 撒娇 | `puppy eyes + pouting + hands clasped` | 甘え | 低 | 撒娇 |
| 任性 | `pouting + crossed arms + looking away + huffing` | ワガママ | 中 | 任性闹脾气 |
| 鼻泡 | `nose bubble` / `sleep bubble` | 鼻の泡 | 低 | 熟睡 |
| 醉酒 | `blind drunk` / `roaring drunk` / `drunk` | 泥酔 | 高 | 喝醉表情 |
| 唱跳 | `singing` / `idol performance` | 歌う | 中 | 快乐歌唱 |
| 口罩神秘 | `face with medical mask` | マスク | 无 | 现代场景 |
| 猫耳女仆 | `cat ears + maid outfit + playful + paw pose` | 猫耳メイド | 中 | 可爱猫娘 |
| 天使光环 | `angel halo + white dress + gentle + wings + kind smile` | 天使 | 低 | 纯洁神圣 |
| 恶魔角 | `devil horns + dark outfit + mischievous + tail` | 悪魔 | 中 | 调皮恶魔 |

### 8. 嘴部动作与细节 / Mouth Actions

| 中文 | 英文提示词 | 效果 |
|------|-----------|------|
| 张嘴 | `open mouth` | 基础口型 |
| 闭嘴 | `closed mouth` | 基础口型 |
| 微张嘴 | `slightly open mouth` / `parted lips` | 惊讶/呼吸 |
| 吐舌头 | `tongue out` | 俏皮/诱惑 |
| 流口水 | `drooling` / `dripping saliva` | 失神/贪吃 |
| 咬嘴唇 | `biting lip` / `lip biting` | 诱惑/紧张 |
| 抿嘴 | `pursed lips` | 不满/思考 |
| 嘟嘴 | `pouting` / `pouty` | 撒娇/生气 |
| 咧嘴 | `grinning` | 大笑 |
| 咬牙切齿 | `gritting teeth` / `clenched teeth` | 愤怒/忍耐 |
| 咬紧牙关 | `teeth clenched` | 痛苦/决心 |
| 叹气 | `sighing` / `exhaling` | 无奈/放松 |
| 打哈欠 | `yawning` | 困倦 |
| 唱歌 | `singing` / `singing with mouth open` | 欢乐 |
| 大喊 | `shouting` / `screaming` | 激烈情绪 |
| 屏住呼吸 | `holding breath` / `gasping` | 惊讶/紧张 |
| 倒吸一口气 | `sharp inhale` / `gasp` | 震惊 |
| 鼓脸颊 | `puffed cheeks` / `cheeks puffed` | 可爱/生气 |
| 吃东西鼓嘴 | `cheeks full of food` / `munching` | 可爱 |
| 叼着面包 | `toast in mouth` / `bread in mouth` | 日式经典场景 |
| 舔 | `licking` / `licking lips` | 诱惑/品尝 |
| 吹气 | `blowing` | 寒冷/吹东西 |
| 呼出白气 | `visible breath` / `cold breath` | 寒冷场景 |
| 嘴角上扬 | `upturned mouth corners` | 微笑迹象 |
| 嘴角下垂 | `downturned mouth corners` | 悲伤迹象 |
| 单边嘴角上扬 | `smirk` / `half-smile` | 得意/嘲讽 |
| 露出虎牙 | `fangs showing` / `canine teeth` | 可爱/危险 |
| 牙齿闪亮 | `sparkling teeth` / `gleaming teeth` | 漫画效果 |
| 深呼吸 | `deep breath` / `inhaling` | 紧张/平静 |
| 歪头 | `head tilt` | 可爱 |
| 飞吻 | `blowing a kiss` / `air kiss` | 可爱 |
| 挥手 | `waving` | 打招呼 |
| 竖起大拇指 | `thumbs up` | 赞 |
| 揉眼睛 | `rubbing eyes` / `yawning and rubbing her eyes` | 刚睡醒 |
| 舔嘴唇 | `licking lips` | 诱惑 |
| 吃东西 | `eating` / `chewing` | 日常 |
| 打瞌睡 | `dozing` / `nodding off` | 困倦 |
| 手指触颊 | `fingersmile` / `hand on cheek` | 可爱手指贴脸 |

### 9. 眼部动作与细节 / Eye Actions

| 中文 | 英文提示词 | 效果 |
|------|-----------|------|
| 眼睛睁大 | `wide eyes` / `eyes widened` / `wide-eyed` | 惊讶/恐惧 |
| 眼睛眯起 | `narrowed eyes` / `squinting` | 怀疑/聚焦 |
| 半闭眼 | `half-closed eyes` / `droopy eyes` | 慵懒/无语 |
| 闭眼 | `eyes closed` / `eyes shut` | 睡觉/享受/微笑 |
| 紧闭双眼 | `eyes tightly shut` | 痛苦/恐惧/强烈情绪 |
| 单眨眼 | `winking` / `one eye closed` | 俏皮/暗示 |
| 向上看 | `looking up` / `gazing up` | 期待/祈祷 |
| 向下看 | `looking down` / `gazing down` | 害羞/思考/悲伤 |
| 看向侧面 | `looking to the side` / `side glance` | 回避/偷看 |
| 回头看 | `looking back` / `turning head` | 惊讶/警惕 |
| 凝视 | `staring` / `gazing intently` | 专注/强烈情感 |
| 凝视远方 | `gazing into the distance` | 思考/惆怅 |
| 翻白眼 | `rolling eyes` / `eyes rolled back` | 无语/晕厥 |
| 向上翻白眼 | `looking up, no pupils` / `eye roll` | 失神/催眠 |
| 眼睛失去高光 | `empty eyes` / `eyes without highlights` / `no light in eyes` / `dead eyes` / `lifeless eyes` | 绝望/失神 |
| 眼睛闪烁 | `eyes sparkling` / `shiny eyes` / `sparkling eyes` / `star eyes` | 兴奋/崇拜/恋爱 |
| 眼睛变成爱心 | `heart-shaped eyes` / `heart eyes` / `heart-shaped pupils` / `love bubbles` | 花痴/恋爱 |
| 眼睛含泪 | `tearful eyes` / `watery eyes` / `eyes brimming with tears` / `glistening eyes` | 悲伤/感动 |
| 眼睛红肿 | `red eyes` / `puffy eyes from crying` | 哭过后 |
| 黑眼圈 | `dark circles under eyes` / `bags under eyes` | 疲惫/失眠 |
| 眼睛布满血丝 | `bloodshot eyes` | 愤怒/疲惫/疯狂 |
| 瞳孔收缩 | `constricted pupils` / `small pupils` | 强光/惊讶/恐惧 |
| 瞳孔放大 | `dilated pupils` / `large pupils` | 黑暗/兴奋/恋爱 |
| 异色瞳 | `heterochromia` / `different colored eyes` | 角色特征 |
| 眼睛发光 | `glowing eyes` | 超能力/黑暗 |
| 眼下阴影 | `shadows under eyes` | 疲惫/阴险 |
| 眼角抽搐 | `twitching eye` / `eye twitch` | 愤怒/忍耐极限 |
| 眉毛上挑 | `raised eyebrows` / `eyebrows raised` | 惊讶/疑问 |
| 眉毛下垂 | `lowered eyebrows` / `furrowed brows` | 悲伤/愤怒/思考 |
| 八字眉 | `sad eyebrows` / `upturned eyebrows` | 悲伤/委屈 |
| 倒八字眉 | `angry eyebrows` / `slanted eyebrows` | 愤怒/决心 |
| 单眉上挑 | `one eyebrow raised` | 怀疑/好奇/嘲讽 |
| 眉毛抖动 | `twitching eyebrows` | 忍耐/困惑 |
| 眉毛紧锁 | `brows knitted together` / `brow compression` / `knitted brows` | 深度思考/痛苦 |
| 眉心皱纹 | `wrinkles between eyebrows` / `forehead wrinkles` | 老化/思考 |
| 抬眉 | `eyebrows raised` | 惊讶 |
| 降眉 | `eyebrows lowered` | 愤怒/专注 |
| 眉头紧锁 | `furrowed forehead` | 皱眉、苦恼 |

### 10. 表情组合公式（进阶） / Expression Combinations

| 组合名 | 提示词组合 | 效果 |
|--------|-----------|------|
| 惊讶组合 | `raised eyebrows + wide eyes + open mouth` | 震惊 |
| 愤怒组合 | `furrowed brows + narrowed eyes + clenched teeth` | 愤怒 |
| 悲伤组合 | `sad eyebrows + teary eyes + downturned mouth` | 悲伤 |
| 开心组合 | `neutral eyebrows + closed eyes + smile` | 幸福 |
| 怀疑组合 | `one eyebrow raised + side glance + smirk` | 怀疑/调侃 |
| 困惑组合 | `furrowed brows + tilted head + confused eyes` | 困惑 |
| 专注组合 | `brows knitted + focused eyes + slightly open mouth` | 专注 |
| 困倦组合 | `droopy eyebrows + half-closed eyes + yawning` | 困倦 |
| 恐惧组合 | `raised eyebrows + wide eyes + gasping` | 恐惧 |
| 傲娇组合 | `furrowed brows + looking away + blush + pouting` | 傲娇 |
| 黑化组合 | `dark smile + narrowed eyes + shadow over face` | 黑化/病娇 |
| 病娇组合 | `yandere face + crazy eyes + blush + dark smile` | 病娇 |
| 天然组合 | `blank stare + tilted head + neutral smile` | 天然呆 |
| 腹黑组合 | `half-closed eyes + scheming smile + hidden hands` | 腹黑 |
| 慵懒组合 | `half-closed eyes + relaxed mouth + leaning` | 慵懒 |
| 元气组合 | `sparkling eyes + wide smile + energetic pose` | 元气满满 |
| 高冷组合 | `cold eyes + neutral mouth + looking down` | 高冷 |
| 温柔组合 | `soft eyes + gentle smile + slightly tilted head` | 温柔 |
| 坚定组合 | `determined eyes + firm mouth + forward gaze` | 坚定 |
| 痛苦组合 | `furrowed brows + tightly shut eyes + gritted teeth` | 痛苦 |
| 享受组合 | `half-closed eyes + open mouth + blush + relaxed` | 享受 |
| 害羞组合 | `looking away + blush + slightly open mouth + fidgeting` | 害羞 |
| 尴尬组合 | `sweat drop + awkward smile + looking away` | 尴尬 |
| 委屈组合 | `sad eyebrows + teary eyes + pouting + looking up` | 委屈 |
| 得意组合 | `smug + confident eyes + hands on hips` | 得意洋洋 |
| 失神组合 | `empty eyes + open mouth + drooling + messy hair` | 失神/被催眠 |
| 石化组合 | `frozen expression + white as sheet + shocked eyes` | 石化 |
| 灵魂出窍组合 | `ghost leaving body + vacant eyes + slumped posture` | 灵魂出窍 |
| 跪地组合 | `kneeling + hanging head + despairing expression` | 绝望 |
| 投降组合 | `raised hands + orz + exhausted expression` | 投降 |
| 努力组合 | `gritted teeth + determined eyes + strained muscles` | 努力/拼命 |
| 兴奋组合 | `sparkling eyes + wide smile + blushing + excited pose` | 极度兴奋 |
| 期待组合 | `hopeful eyes + slight smile + forward lean` | 期待 |
| 失落组合 | `downcast eyes + downturned mouth + slumped shoulders` | 失落 |
| 生气但可爱 | `pouting + angry eyebrows + blush + crossed arms` | 生气(可爱版) |
| 伪装平静 | `poker face + sweating + nervous hands` | 内心紧张 |
| 崩溃大哭 | `sobbing + tears streaming + mouth wide open + red eyes` | 崩溃 |
| 喜极而泣 | `crying laughing + tears of joy + wide smile` | 喜极而泣 |
| 感动流泪 | `tears of gratitude + gentle smile + hand on heart` | 感动 |
| 害羞拒绝 | `looking away + blush + hand waving + stammering mouth` | 害羞拒绝 |
| 接受告白 | `blushing + happy tears + shy smile + hands clasped` | 幸福害羞 |
| 被摸头害羞 | `blushing + looking down + hair ruffled + shy smile` | 被摸头反应 |
| 惊吓过度 | `frozen + wide eyes + mouth agape + trembling` | 惊吓 |
| 背后发凉 | `cold sweat + shivering + terrified eyes + hunched back` | 恐惧 |
| 嫉妒眼红 | `jealous eyes + pouting + crossed arms + looking away` | 嫉妒 |
| 吃醋 | `puffed cheeks + angry eyebrows + pouting + looking away` | 吃醋 |
| 撒娇 | `puppy eyes + pouting + hands clasped + upturned gaze` | 撒娇 |
| 任性 | `pouting + crossed arms + looking away + huffing` | 任性 |
| 姐姐系微笑 | `mature smile + half-closed eyes + hand on cheek` | 成熟姐姐 |
| 妹妹系可爱 | `sparkling eyes + wide smile + energetic pose + head tilt` | 元气妹妹 |
| 女王蔑视 | `cold eyes + smirk + looking down + arms crossed` | 女王范 |
| 病弱美 | `coughing + hand over mouth + pale skin + weak smile` | 病弱美人 |
| 战斗决心 | `determined eyes + fierce expression + battle-ready stance` | 战斗决心 |
| 战斗狂笑 | `crazy grin + glowing eyes + battle aura + bared teeth` | 战斗狂 |
| 受伤忍耐 | `gritted teeth + pained eyes + hand on wound + sweating` | 受伤 |
| 濒死微笑 | `weak smile + fading eyes + blood + reaching out` | 濒死 |
| 回忆温柔 | `distant gaze + gentle smile + soft focus + nostalgic` | 回忆 |
| 雨中哭泣 | `crying in rain + tears mixed with rain + looking up + wet hair` | 雨中 |
| 夕阳微笑 | `sunset background + gentle smile + golden hour lighting + wind` | 夕阳微笑 |
| 逆光剪影 | `silhouette + backlight + dramatic pose + sunset` | 剪影 |
| 月下清冷 | `moonlight + cold expression + pale skin + dark background` | 月下美人 |
| 花丛微笑 | `flower field + gentle smile + soft lighting + breeze` | 花丛 |
| 雪中独立 | `snow + serious expression + red scarf + cold breath` | 雪中 |
| 窗边眺望 | `window + looking outside + melancholy + afternoon light` | 窗边 |
| 床上刚醒 | `bed + sleepy eyes + messy hair + pajamas + morning light` | 刚醒 |
| 入浴氤氲 | `bath + steam + wet hair + relaxed expression + blush` | 入浴 |
| 更衣害羞 | `changing clothes + embarrassed + covering body + blush` | 更衣 |
| 被推倒 | `surprised + blush + lying down + arms up + disheveled` | 被推倒 |
| 壁咚 | `pinned against wall + flustered + blush + looking up + heart beating` | 壁咚反应 |
| 膝枕幸福 | `lap pillow + happy + closed eyes + blush + hand on head` | 膝枕 |
| 喂食害羞 | `feeding + open mouth + blush + looking away + hand on cheek` | 被喂食 |
| 梳头享受 | `brushing hair + closed eyes + gentle smile + relaxed` | 被梳头 |
| 挽手害羞 | `arm linked + walking + blush + shy smile + looking down` | 挽手 |
| 公主抱惊讶 | `carried bridal style + surprised + blush + arms around neck` | 公主抱 |
| 背后拥抱 | `hug from behind + surprised + blush + looking back + happy` | 背后抱 |
| 摸头杀 | `head pat + looking down + blush + happy + hair ruffled` | 被摸头 |
| 弹额头 | `forehead flick + pouting + hand on forehead + tears forming` | 被弹额头 |
| 捏脸颊 | `cheek pinch + puffed cheeks + annoyed + pouting` | 被捏脸 |
| 戳脸 | `cheek poke + surprised + mouth open + cute reaction` | 被戳脸 |
| 挠痒痒 | `tickled + laughing + squirming + tears of joy + flailing` | 被挠痒 |
| 被公主抱挣扎 | `carried + struggling + embarrassed + blush + angry eyebrows` | 抗拒 |
| 被壁咚心跳 | `against wall + heart pounding + blush + looking away + nervous` | 紧张 |
| 被撩下巴 | `chin lifted + looking up + blush + surprised + lips slightly parted` | 被撩 |
| 被牵手害羞 | `hand held + looking down + blush + shy smile + fingers intertwined` | 牵手 |
| 被偷亲 | `kiss on cheek + surprised + blush + hand on cheek + wide eyes` | 被偷亲 |
| 主动亲吻 | `leaning in for kiss + closed eyes + blush + gentle smile + romantic` | 主动吻 |
| 深吻 | `deep kiss + closed eyes + blush + passionate + hand on partner` | 深吻 |
| 接吻后害羞 | `after kiss + blush + looking down + fingers on lips + happy` | 吻后 |
| 被掀裙子 | `skirt flipped + surprised + blush + covering skirt + embarrassed` | 被掀裙 |
| 风吹裙子 | `wind blowing skirt + surprised + blush + holding skirt down + panties` | 风吹裙 |
| 跌倒走光 | `tripped + fallen + embarrassed + blush + panties visible + hand covering` | 跌倒 |
| 洗澡被撞见 | `bath interrupted + surprised + covering body + blush + steam` | 被撞见 |
| 换衣服被撞见 | `changing clothes + surprised + covering body + blush + towel` | 被撞见 |
| 睡衣慵懒 | `pajamas + sleepy + messy hair + yawning + relaxed + cute` | 睡衣 |
| 泳装害羞 | `swimsuit + embarrassed + blush + covering body + looking away` | 泳装 |
| 体操服 | `gym uniform + energetic + smile + ponytail + active pose` | 体操服 |
| 女仆装微笑 | `maid outfit + gentle smile + serving + curtsy + polite` | 女仆 |
| 护士装温柔 | `nurse outfit + gentle smile + caring + holding clipboard + kind eyes` | 护士 |
| 警服严肃 | `police uniform + serious expression + salute + determined` | 警服 |
| 军装帅气 | `military uniform + confident + standing at attention + salute` | 军装 |
| 和服优雅 | `kimono + elegant + gentle smile + holding fan + traditional` | 和服 |
| 浴衣夏祭 | `yukata + summer festival + happy + holding sparkler + smile` | 浴衣 |
| 巫女服神圣 | `miko outfit + shrine maiden + serious + holding gohei + spiritual` | 巫女 |
| 修女服虔诚 | `nun outfit + praying + gentle smile + hands clasped + serene` | 修女 |
| 婚纱幸福 | `wedding dress + happy tears + blushing + veil + holding bouquet` | 婚纱 |
| 婚纱害羞 | `wedding dress + shy + looking down + blush + hands clasped + nervous` | 婚纱害羞 |
| 便服日常 | `casual clothes + relaxed + natural smile + hands in pockets` | 日常 |
| 校服青春 | `school uniform + energetic + smile + backpack + walking to school` | 校服 |
| 战斗服决心 | `battle outfit + determined + fierce + weapon ready + combat stance` | 战斗服 |
| 魔法少女变身 | `magical girl outfit + transformation + sparkles + determined + pose` | 变身 |
| 偶像演出 | `idol outfit + stage + singing + microphone + sparkling + energetic` | 偶像 |
| 哥特萝莉 | `gothic lolita + dark smile + mysterious + holding doll + elegant` | 哥特 |
| 水手服 | `sailor uniform + school + smiling + holding bag + cheerful` | 水手服 |
| 运动服 | `sportswear + sweating + determined + running + focused + ponytail` | 运动 |
| 居家服 | `loungewear + relaxed + messy bun + sleepy smile + cup of tea` | 居家 |
| 圣诞装 | `christmas outfit + santa hat + red dress + happy + present + snow` | 圣诞 |
| 万圣节 | `halloween costume + pumpkin + spooky + cute + trick or treat` | 万圣 |
| 猫耳女仆 | `cat ears + maid outfit + playful + paw pose + meow + cute` | 猫耳女仆 |
| 兔女郎 | `bunny ears + leotard + playful + pose + bowtie + cute + sexy` | 兔女郎 |
| 恶魔角 | `devil horns + dark outfit + mischievous + tail + pitchfork + playful` | 恶魔 |
| 天使光环 | `angel halo + white dress + gentle + wings + kind smile + pure` | 天使 |
| 眼镜知性 | `glasses + smart + confident + holding book + adjusting glasses + cool` | 眼镜 |
| 墨镜酷 | `sunglasses + cool + confident + hands in pockets + smirk + badass` | 墨镜 |
| 口罩神秘 | `face mask + mysterious + eyes only + looking at viewer + enigmatic` | 口罩 |
| 耳机元气 | `headphones + music + energetic + smiling + head bopping + cute` | 耳机 |
| 帽子俏皮 | `hat + playful + tipping hat + winking + cheerful + cute` | 帽子 |
| 围巾温暖 | `scarf + winter + warm smile + breath visible + cold + cozy` | 围巾 |
| 手套优雅 | `gloves + elegant + formal + gentle smile + tea party + refined` | 手套 |
| 伞下忧郁 | `umbrella + rain + melancholy + looking down + gray + alone` | 伞下 |

---

## 二、完整提示词模板示例

### 模板 1：基础动漫角色表情差分（SD 1.5 / SDXL 通用）

```text
【正向提示词】
masterpiece, best quality, 1girl, solo, 
[角色基础描述], 
[发色/发型], [瞳色], [服装],
[表情关键词], 
portrait, upper body, from front, looking at viewer,
soft lighting, simple background, white background,
ultra-detailed, highres, anime style, illustration

【负面提示词】
(worst quality:2), (low quality:2), (normal quality:2), lowres, 
bad anatomy, bad hands, text, error, missing fingers, extra digit, 
fewer digits, cropped, jpeg artifacts, signature, watermark, username, 
blurry, bad feet, mutated hands, poorly drawn hands, poorly drawn face, 
mutation, deformed, ugly, disfigured, extra limbs, extra arms, extra legs, 
missing arms, missing legs, fused fingers, too many fingers, long neck, 
cross-eyed, polar lowres, bad face, out of frame, oversaturated, overexposure,
EasyNegative, badhandv4, ng_deepnegative_v1_75t
```

> 将 `[表情关键词]` 替换为具体表情词，如 `smile`、`angry`、`crying`、`blushing` 等。

### 模板 2：ADetailer 表情差分专用（图生图）

```text
【主提示词 - 基础部分】
girl, [base_description], [hairstyle], [clothing], 
upper body, portrait, soft lighting, simple background

【ADetailer 表情提示词（在 ADetailer 面板中输入）】
detailed face, beautiful eyes, [expression_keyword]
# 示例：
# (angry:1.5)        ← 愤怒表情，权重1.5
# (smile:1.3)        ← 微笑表情，权重1.3  
# (sad:1.4)          ← 悲伤表情，权重1.4
# (crying:1.6)       ← 哭泣表情，权重1.6
# (surprised:1.5)    ← 惊讶表情，权重1.5
# (blushing:1.4)     ← 脸红表情，权重1.4

【ADetailer 负面提示词】
(worst quality:2), (low quality:2), badhandv4, ng_deepnegative_v1_75t
```

### 模板 3：日系 VTuber / 游戏立绘 标准 6 种表情

```text
1girl, solo, [expression], looking at viewer,
long hair, blue eyes, school uniform,
upper body, simple white background,
character sheet, multiple expressions, expression sheet,
masterpiece, best quality, official art

表情替换列表：
1. 通常: expressionless, neutral face
2. 笑顔: smile, light smile, happy
3. 赤面/害羞: blushing, embarrassed, shy, nose blush
4. 困り/困扰: troubled face, worried, sweatdrop, looking away
5. 泣き/哭泣: crying, tears, sobbing, sad
6. 驚き/惊讶: surprised, wide-eyed, shocked, open mouth
```

### 模板 4：表情集 / Expression Sheet（多格一次性生成）

```text
masterpiece, best quality, 1girl, solo, character_sheet, 
multiple_views, multiple_expressions, expression_sheet, 
reference_sheet, turnaround, 

expression: [neutral, happy, angry, sad, surprised, blushing], 

same character, consistent features, 
white background, simple background, 
from front, portrait, upper body, 
ultra-detailed, highres, anime style
```

**布局建议**：
- 16:9 横向：适合 3-4 个全身视图 + 表情行
- 2×3 网格：6 个表情头像在 16:9 中
- 3:4 纵向：适合全身视图上方 + 表情细节下方
- 1:1 方形：适合 3×3 表情网格（9 个表情）

### 模板 5：Midjourney / Niji 表情差分（自然语言）

```text
Character illustration, expression differentiation, 
[character description], 
[expression: neutral / happy / angry / sad / surprised / embarrassed],
white background, consistent character design, anime style, 
professional concept art reference, high resolution, clean linework

-- 中文示例:
人物立绘，表情差分，白色短发，中分刘海，白色眉毛，白色睫毛，白色瞳孔，冷漠表情，
墨绿色联邦军服，合金战斗胸甲，合金战斗肩甲，战术腰带，合金战斗腿甲，棕色军靴，
破烂的黑色斗篷，手持AR系突击步枪，二次元线稿风格，动漫风格，电影级画质，电影级光影，
空白背景，电影级滤镜，人物立绘，全身像
```

### 模板 6：FLUX / 高保真表情差分

```text
Generate a 3x3 expression sheet of this same character, 
keeping identical lighting and composition while varying only facial expressions: 
neutral, happy, angry, surprised, sad, confident, shouting, embarrassed, and laughing.

Style: modern Japanese anime illustration, clean line art with subtle shading, 
soft cel-shading, delicate pastel highlights on the hair, bright vivid color cells.
```

### 模板 7：16 格完整表情差分（4×4 网格）

```text
Create a clean 4×4 expression grid (16 panels total) of an anime-style girl, 
highly consistent character design across all 16 panels with zero drift in face shape, 
hairstyle, eye color, and clothing.

Character design (must be identical in every panel):
- teenager girl, 16 years old, slender frame
- long straight lavender-purple hair with hime-cut bangs, 
  two braided side strands tied with black ribbons
- bright golden-yellow eyes with clear anime highlights
- small mole under the right eye
- wearing a white sailor-collar seifuku with a black ribbon tie 
  and a deep-navy pleated skirt
- pale porcelain skin

The 16 expressions (arrange left-to-right, top-to-bottom, one per cell):
Row 1: 01 happy smile, 02 sad downcast eyes with a single tear, 
        03 angry puffed cheeks with a sweatdrop, 04 surprised wide eyes + round mouth
Row 2: 05 shy blushing looking away, 06 speechless deadpan dot eyes, 
        07 evil grin with a glint, 08 contemplative finger on chin
Row 3: 09 curious head tilted with question mark, 10 proud smug with closed eyes, 
        11 wronged watery eyes pouting, 12 disdainful half-closed eyes looking down
Row 4: 13 confused tangled question marks, 14 scared pale face, 
        15 crying anime waterfall tears, 16 heart-eyes heart-shaped pupils + hearts floating

Style: modern Japanese anime illustration, clean line art with subtle shading, 
soft cel-shading, delicate pastel highlights on the hair, bright vivid color cells, 
each panel has a pale different-colored background with a thin white border 
separating the 16 cells. A small Chinese/English label in the bottom-left corner 
of each cell. Overall feeling: collectible anime emoji pack. 
No watermark, no signature, no out-of-cell decoration, perfectly aligned 4×4 grid.
```

### 模板 8：少女漫画 / 恋爱向表情集（Shoujo Style）

```text
"Anime girl with blushing cheeks, hands clasped nervously, 
cherry blossom petals falling around her, 
shoujo anime soft lighting, sparkle effects near face, 
romantic confession moment, pastel color palette, 
large sparkling eyes, emotional expression, delicate features"

变体:
- Dramatic Hair Flip: "Anime female character's hair flowing in slow motion, 
  sparkles and light rays, glamorous moment, shoujo anime beauty shot"
- Longing Gaze: "Anime character looking up wistfully, hand near heart, 
  soft focus background, shoujo emotional expression, delicate features, romantic yearning"
- Emotional Crying: "Anime character with large tears streaming down face, 
  dramatic emotional moment, rain or symbolic water background, 
  shoujo anime emotional climax, shimmering eyes, quivering lips, hand on heart"
```

### 模板 9：复杂情绪组合（进阶）

```text
1girl, [基础表情], [叠加表情1], [叠加表情2],
[眉部动作], [眼部动作], [嘴部动作], [附加动作],
detailed face, beautiful detailed eyes,
masterpiece, best quality

示例组合:
- 傲娇: tsundere expression, looking away, blushing, furrowed brows, pouting, arms crossed
- 病娇: yandere face, crazy eyes, dark smile, blush, shadow over face, head tilt
- 害羞告白: shy, blushing, looking down, hands clasped, teary-eyed, hopeful smile
- 被摸头: head pat, looking down, blushing, happy, hair ruffled, gentle smile
- 被推倒: surprised, blush, lying down, arms up, disheveled, flustered
- 壁咚反应: against wall, flustered, blush, looking up, heart pounding, nervous
```

### 模板 10：AI 视频/动态表情变化（Seedance 风格）

```text
[运镜], 人物初始[初始表情], [初始动作];
下一秒[眼部变化], [嘴部变化], [眉部变化], [面部线条变化];
[最终表情], [环境配合]
运镜: [镜头变化]

示例 - 从平淡到开心满怀:
特写，人物初始嘴角下垂，不想抬眼，眼皮抖动；
下一秒眼睛逐渐睁大，瞳孔重新聚焦，眼角泛起微光；
嘴角微微上扬，面部线条从松弛变得紧致，光线从暗部逐渐照亮瞳孔
运镜: 从模糊到清晰的对焦变化，配合缓慢推进的镜头

公式组件库:
人物设定：年轻女性、穿着[服装]的[职业]
初始表情：平静、严肃、微笑、专注、警惕
触发词：突然、逐渐、慢慢、瞬间、随着时间
表情变化过程（三段式）：
眉部：皱眉→紧锁→舒展
眼部：眯眼→瞪大→含泪
嘴部：抿嘴→张开→上扬/下沉
最终表情：愤怒、惊讶、悲伤、恐惧、厌恶、喜悦、轻蔑
细节强化：重点突出眼神、眉毛动作最明显、嘴角变化清晰
环境配合：在昏暗房间、阳光下、风中、雨中
```

---

## 三、负面提示词（Negative Prompt）

### 通用负面提示词（标准版）

```text
low quality, worst quality, bad anatomy, bad hands, missing fingers,
extra fingers, fewer fingers, fused fingers, impossible hand, bad feet,
poorly drawn face, mutation, mutated, ugly, disgusting, blurry,
amputation, watermark, text, signature, username, artist_name,
semi-realistic, cgi, 3d, render, sketch, cartoon, drawing,
close up, cropped, out of frame, worst quality, low quality,
jpeg artifacts, duplicate, morbid, mutilated, extra limbs,
cloned face, disfigured, gross proportions, malformed limbs,
missing arms, missing legs, extra arms, extra legs, long neck,
EasyNegative, badhandv4, ng_deepnegative_v1_75t
```

### 人物专用负面提示词（详细版）

```text
EasyNegative, badhandv4, ng_deepnegative_v1_75t,
(worst quality:2), (low quality:2), lowres, bad anatomy,
DeepNegative, skin spots, acnes, skin blemishes, facing away,
bad hands, missing fingers, extra digit, fewer digits, bad feet,
poorly drawn hands, poorly drawn face, mutation, deformed,
extra fingers, extra limbs, extra arms, extra legs, malformed limbs,
fused fingers, too many fingers, signature, watermark, jpeg artifacts, text
```

### 面部专用负面提示词

```text
(semi-realistic:1.4), (cgi:1.4), (3d:1.4), (render:1.4), (sketch:1.4),
(cartoon:1.4), (drawing:1.4), (anime:1.4), text, close up, cropped,
out of frame, worst quality, low quality, jpeg artifacts, ugly, duplicate,
morbid, mutilated, extra fingers, mutated hands, poorly drawn hands,
poorly drawn face, mutation, deformed, blurry, dehydrated, bad anatomy,
bad proportions, extra limbs, cloned face, disfigured, gross proportions,
malformed limbs, missing arms, missing legs, extra arms, extra legs,
fused fingers, too many fingers, long neck
```

### 动漫风格专用负面提示词

```text
NSFW, (bad-artist:1.0), (worst quality, low quality:1.4), 
(bad_prompt_version2:0), bad anatomy, bad hands, missing fingers, 
(extra arms), deformed, mutated, disfigured, blurry, watermark, text, 
3d, realistic, photo, photorealistic, western, cartoon, 
lowres, normal quality, jpeg artifacts, signature, username
```

### 表情差分专用负面提示词（保持角色一致性）

```text
# 在基础负面提示词上增加：
(changed clothes:1.3), (different hairstyle:1.3), 
(different pose:1.3), (changed background:1.3),
(extra accessories:1.2), (different lighting:1.2),
different face between views, different hair between views,
merged panels, compressed figures, inconsistent colors
```

### 写实/真人风格负面提示词

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

### 负面提示词使用建议

1. **负面提示词作用维度**：画质 + 人物细节（面部和肢体）
2. **现代新模型**（如 Flux 系列、Qwen-image）中负面提示词作用有限，模型对正面提示词理解已很准确
3. **旧模型**（SD 1.5 等）中负面提示词效果显著
4. **古风图** 即使使用新模型，负面提示词仍然有效（模型训练数据较少）
5. **权重调节**：对特定元素可加权重，如 `(badhandv4:1.2)`、`(extra fingers:1.5)`

---

## 四、制作表情差分的方法与技巧

### 方法一：ADetailer 局部重绘（⭐ 最推荐，效率最高）

**来源**: AI图库吧 / AI奇点网 / 智汇AI / 腾讯云 / 日本 AI Arty 教程
**适用**: Stable Diffusion WebUI (AUTOMATIC1111) / Forge
**原理**：ADetailer 是 SD 最强修脸插件，使用人脸检测模型自动识别面部区域，然后仅对面部进行局部重绘，实现只改变表情而不影响图片其他部分。

**操作步骤**:

1. **准备基础图片**
   - 在文生图或图生图生成一张满意的基础角色图
   - 或使用已有图片作为底图

2. **开启 ADetailer**
   - 在生成参数下方找到「ADetailer」面板
   - 勾选「Enable this tab」启用功能

3. **选择检测模型**
   - `face_yolov8n.pt` — 适合真人/写实风格人脸
   - `face_yolov8s.pt` — 精度更高，适合部分遮挡的脸
   - `anime_face_yolov8.pt` — 专为动漫风格人脸优化 ⭐ **推荐**
   - `hand_yolov8n.pt` — 如果需要同时修复手部

4. **在 ADetailer 中输入表情提示词**
   - 在 ADetailer 的 prompt 框中输入表情词
   - 使用权重增强效果，例如: `(angry:1.5)` 或 `(smile:1.3)`
   - 权重范围建议: 1.0 ~ 2.0，越大表情越强

5. **调整关键参数**

| 参数 | 推荐值 | 说明 |
|------|--------|------|
| `Detection confidence` | 0.3 | 默认，检测更多脸部 |
| `Mask blur` | 4-8 pixels | 边缘柔化，越高越自然 |
| `Denoising strength` | 0.35-0.65 | 0.45 最佳起点；0.4-0.5 轻微增强；0.55-0.65 更强重绘 |
| `Inpaint steps` | 20-28 | 与主生成步数一致 |
| `CFG scale` | 6-7 | 与主 CFG 一致或略低 |
| `Inpaint padding` | 32 pixels | 面部扩展区域 |
| `Inpaint only masked` | True | 只修复检测到区域 |

6. **生成表情差分**
   - 保持基础图和种子不变
   - 仅修改 ADetailer 中的表情提示词
   - 每次生成一种表情，批量产出差分

**注意事项**:
- 动漫风格务必使用 `anime_face_yolov8.pt` 模型
- 权重超过 2.0 可能导致画面崩坏
- 如果表情变化不够明显，适当提高 denoising strength 到 0.5-0.6
- 面部被刘海遮挡时，可先用 Photoshop 处理遮挡物
- ADetailer 中去噪强度低于 0.45 可以保留原角色身份，高于 0.6 可能变成通用脸

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

### 方法二：图生图 + 局部重绘（Inpaint）—— 精确控制

**来源**: 百度贴吧 / 知乎 / Reddit / stable-diffusion-art.com
**适用**: 需要更高精度控制时
**原理**：手动涂抹面部区域，仅重绘该区域，配合 ControlNet 保持结构。

**操作步骤**:

1. **上传原图**到图生图（img2img）区域
2. **使用画笔**涂抹需要修改的部分（脸部区域）
   - **重要：必须把眉毛也覆盖进蒙版范围，否则很难画出大波动的表情！**
3. **修改提示词**：将原表情词替换为目标表情词
   - 例如：原 `smile` → 改为 `angry` 或 `crying`
4. **调整参数**：

| 参数 | 推荐值 | 说明 |
|------|--------|------|
| `Denoising strength` | 0.35 - 0.55 | 太低无变化，太高失去角色一致性 |
| `Mask Blur` | 4 - 8 / 5-15 | 边缘羽化，使过渡自然 |
| `Mask Content` | Original | 保留原始内容作为参考 |
| `CFG Scale` | 7 - 9 | 控制提示词强度 |
| `Steps` | 20 - 30 | 步数 |
| `Sampler` | DPM++ 2M Karras | 推荐 |

5. **仅蒙版模式**（Inpaint masked）：只重绘画笔涂抹区域
6. **保持 Seed 和参数一致**
7. **生成**并调整

**进阶技巧**:
- **Photoshop 辅助**：先 PS 抠出角色到白背景，局部重绘后再合成回原图
- **分层处理**：脸部差分、肢体差分分别处理，最后合成
- **种子值固定**：固定 Seed 值，只改变表情词，其他参数不变

---

### 方法三：ControlNet + 局部重绘（精度最高）

**来源**: 日本 AI Arty 教程 / 百度贴吧 / CSDN / 微信公众号
**适用**: 需要同时保持姿势和轮廓时

**步骤**:

1. **生成基础图**，记录 Seed
2. **进入图生图 → 局部重绘（Inpaint）**
   - 上传基础图
   - 用画笔涂抹面部区域（需要重绘的区域）
3. **开启 ControlNet**
   - 使用 `ControlNet Inpaint` 模型
   - 或同时使用 `Canny` / `Lineart` 保持整体轮廓
   - 或 `ControlNet OpenPose` 保持姿势一致
   - 上传同一张图作为 ControlNet 输入

| ControlNet 类型 | 适用场景 | 预处理器 | 模型 |
|----------------|----------|----------|------|
| OpenPose | 保持身体姿势 | `openpose_face` / `openpose_faceonly` | `control_v11p_sd15_openpose` |
| OpenPose (face only) | 只保持面部位置 | `openpose_faceonly` | `control_v11p_sd15_openpose` |
| Canny | 保持边缘轮廓 | `canny` | `control_v11p_sd15_canny` |
| Depth | 保持空间深度 | `depth` / `depth_anything` | `control_v11p_sd15_depth` |
| Inpaint | 局部重绘控制 | `inpaint_only` / `inpaint_only+lama` | `control_v11p_sd15_inpaint` |
| Lineart | 保持线条 | `lineart` | `control_v11p_sd15_lineart` |

4. **调整图生图参数**
   - `Denoising strength`: 0.3-0.5（越低越像原图，仅改表情）
   - 保持种子和参数一致

5. **修改表情提示词**
   - 在正向提示词中替换表情关键词
   - 例如将 `smile` 改为 `angry` 或 `crying`

6. **生成**

**进阶技巧**:
- 服装差分 + 表情差分同时做：先用 ControlNet Inpaint 做服装，再用 ADetailer 做表情
- 制作三面图/姿势差分：使用 `ControlNet OpenPose` 固定骨骼姿势

---

### 方法四：Seed 固定 + 提示词替换（最简单）

**来源**: Niji Journey v7 指南 / 多个社区经验
**原理**：通过固定随机种子（Seed），只改变表情相关的提示词，其他所有参数保持不变，实现同一角色的表情差分。

**操作步骤**:

1. **生成基础图**：生成一张满意的角色图，记录其 **Seed 值**
2. **复制参数**：记录所有参数（Sampler、Steps、CFG、Size 等）
3. **修改提示词**：仅替换表情关键词
   - 例1：`(smile:1.2)` → `(angry:1.5)`
   - 例2：`happy expression` → `sad expression, teary eyes`
4. **保持 Seed 不变**：输入相同的 Seed 值
5. **生成**：得到同一角色的不同表情版本

**注意事项**:
- 此方法适用于同一角色的表情差分，但姿势可能略有变化
- 如需严格保持姿势，需配合 ControlNet
- 在 Niji Journey v7 中，通过重复描述特征属性（如"红色校队夹克，左脸上的创可贴"）提高角色一致性

---

### 方法五：XYZ 图表 + ADetailer / Dynamic Prompts（批量生成）

**来源**: Bilibili / 知乎 / CSDN
**原理**：使用 WebUI 的 X/Y/Z 图表功能，让表情词自动替换，一次批量生成多种表情。

**设置示例**:

```text
X 轴类型：Prompt S/R（搜索替换）
X 轴值：smile, angry, sad, crying, surprised, blush, embarrassed, worried, serious, expressionless

基础提示词中的占位符：... [expression] ...
会依次替换为上述表情词
```

或者使用 **Dynamic Prompts** 扩展：
```text
{smile|angry|sad|surprised|embarrassed|crying}, 1girl, [其他角色特征]
```
- 设置 Batch Size = 6，一次生成 6 种不同表情
- 结合 Regional Prompter 可将不同表情放在同一画面的不同区域

**所有生成的图片会被保存在 txt2img-images 文件夹中**，即使图表中未单独显示。

---

### 方法六：LivePortrait 表情迁移（已有立绘快速量产）

**来源**: 站酷 ZCOOL / 知乎 / 腾讯云
**适用**: 已有静态立绘，需要快速量产多种表情
**核心逻辑**：用"表演"代替"手绘"——你对着摄像头做表情，AI 把表情迁移到纸片人脸上。

**步骤**:

1. **准备"面瘫"素体 (Photoshop)**
   - 打开 Photoshop，裁切立绘的头部和肩部区域
   - 确保五官清晰，没有刘海遮挡眼睛（如有遮挡，分层处理）
   - 保存为 `Base_Character.jpg`

2. **录制驱动视频 (手机相机)**
   - 打开手机相机，切换到视频模式
   - 固定机位，保持头部在画面中央
   - 依次做出所需表情：轻蔑（嘴角上扬）、大笑（张嘴闭眼）、惊恐（瞳孔缩小）、害羞、愤怒等
   - **关键：动作幅度要比平时大 20%，AI 识别更精准**
   - 保存为 `Driving_Video.mp4`

3. **LivePortrait 表情迁移**
   - 打开 LivePortrait（WebUI 或 Python 版）
   - Source Image: 上传 `Base_Character.jpg`
   - Driving Video: 上传 `Driving_Video.mp4`
   - Settings:
     - 开启 `Relative Motion` (相对运动) — 保证头身位置不乱跑
     - 开启 `Lip Sync` (唇形同步) 增强
   - 生成视频

4. **视频转图层 + 提取关键帧 (Photoshop)**
   - PS 中: 文件 > 导入 > 视频帧到图层
   - 选择 `LivePortrait_Output.mp4`
   - 在时间轴上找到表情最到位的几帧
   - 删除过渡帧，只保留需要的表情瞬间
   - 修补细节：LivePortrait 对牙齿/舌头还原可能不够二次元
     - 用选区工具框选嘴巴内部
     - 提示词: `anime style tongue, sharp teeth, clean lines`
   - 将图层分别导出，完成差分

5. **进阶：瞳孔与视线控制**
   - 录制视频时眼球上下左右转动
   - 生成素材直接作为"视线差分"使用
   - 如果原画是特殊"星星眼"或"爱心眼"，用图层蒙版把原画眼珠子挖出来叠在生成眼眶上

**工具获取**:
- LivePortrait GitHub: https://github.com/KwaiVGI/LivePortrait
- 有 WebUI 版本和 ComfyUI 节点可用

---

### 方法七：AdvancedLivePortrait（ComfyUI 专业级）

**来源**: 知乎 / 腾讯云开发者社区
**适用**: ComfyUI 环境，需要更精细控制
**特点**:
- 可以精确控制眉毛、眼睛、嘴巴的每个部分
- 支持闭眼修复、僵硬表情修复
- 可以在 ComfyUI 中直接作为节点使用

**流程**:
1. 在 ComfyUI 中搭建工作流（FLUX 大模型 + 风格 LoRA）
2. 上传漫画人物，调整参数
3. 输出表情差分

---

### 方法八：Photoshop + 生成式填充（商业级精度）

**来源**: 百度贴吧 / 日本社区
**适用**: 需要最高精度商业级输出时

**步骤**:
1. Photoshop 识别角色，一键抠图出来（白底/透明底）
2. 丢进 img2img，按想要的蒙版范围（脸部差分、肢体差分）进行局部重绘
3. 重绘幅度控制：调低（0.3-0.5）则姿势/表情微调，调高（0.6+）则区域重画
4. 最后再合成进原图背景，实现整套图的差分

**建议**:
- 用提示词或 LoRA 确定人物
- 用 ControlNet 骨骼/OpenPose 确定姿势
- 用局部重绘控制人物表情
- 制作同人动漫推荐 Illustrious 模型

---

### 方法九：Character Sheet / Expression Sheet 一次性生成

**来源**: Kalon.ai / PromptGather.io / ReShot.ai / GPT-Image
**适用**: 新模型（FLUX / GPT-Image / Midjourney v6）
**提示词模板**:
```text
character expression sheet, 1girl, [角色详细描述],
multiple expressions, expression sheet, 6 expressions, 2x3 grid,
neutral, happy, angry, sad, surprised, blushing,
consistent face across all views, consistent hair across all views,
white background, character reference, turnaround,
masterpiece, best quality, ultra detailed
```

**一致性保证技巧**:
1. 角色描述尽可能详细（精确发色、瞳色、服装名、配饰）
2. 重复一致性标签：`"consistent face across all views"`、`"consistent hair across all views"`
3. 为脸、头发、身体、服装分别指定一致性标签
4. 使用负面提示词阻止不同视图间角色漂移

---

### 方法十：FLUX.1 Pro / SD3 高保真表情生成

**来源**: 阿里巴巴产品对比分析

**FLUX.1 Pro 在动漫表情差分中的优势**:
- 提示词保真度更高：风格提示词的平均 Token 召回率 4.7/5（SD3 为 3.2/5）
- 负面提示词遵守率：94%（SD3 为 68%）
- 手部/面部解剖准确度：4.5/5（SD3 为 2.9/5）
- 同一提示词多次生成一致性：89%（SD3 为 52%）
- 首次获得忠实输出的平均尝试次数：2.1 次（SD3 为 7.4 次）

**建议**：对于高质量表情差分，FLUX.1 Pro 比 SD3 更适合动漫风格的精确控制。

---

### 参数对比总表

| 方法 | 推荐模型/工具 | 适用场景 | 效率 | 精度 | 学习成本 |
|------|-------------|---------|------|------|---------|
| ADetailer | `anime_face_yolov8.pt` | 快速批量生成 | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐ | 低 |
| Inpaint 局部重绘 | img2img + 画笔 | 精细控制单张 | ⭐⭐⭐ | ⭐⭐⭐⭐⭐ | 低 |
| ControlNet + Inpaint | `control_v11p_sd15_inpaint` | 保持结构+姿势 | ⭐⭐⭐ | ⭐⭐⭐⭐⭐ | 中 |
| LivePortrait | LivePortrait WebUI | 已有立绘快速量产 | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐ | 中 |
| AdvancedLivePortrait | ComfyUI 节点 | 专业级精细调整 | ⭐⭐⭐ | ⭐⭐⭐⭐⭐ | 高 |
| PS + 生成式填充 | Stable Diffusion + Photoshop | 商业级输出 | ⭐⭐ | ⭐⭐⭐⭐⭐ | 高 |
| Seed 固定+替换 | 同一参数只改提示词 | 简单表情差分 | ⭐⭐⭐⭐ | ⭐⭐⭐ | 低 |
| XYZ 图表批量 | Dynamic Prompts + Batch | 一次生成多种 | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐ | 低 |
| Character Sheet | FLUX / MJ / GPT-Image | 新模型一次性生成 | ⭐⭐⭐⭐ | ⭐⭐⭐⭐ | 低 |

---

### 提示词权重使用技巧

```text
Stable Diffusion 权重语法:
- (word)        = 权重1.1
- (word:1.3)   = 权重1.3  
- ((word))      = 权重1.21 (1.1*1.1)
- [word]        = 权重0.9
- [word:0.5]    = 权重0.5
- {word}        = 权重1.05（SD 1.5）
- {{word}}      = 权重1.464（SDXL）
- BREAK         = 分隔提示词，防止表情影响其他元素

表情控制建议:
- 基础表情权重: 1.1 - 1.3
- 标准表情权重: 1.3 - 1.5
- 强烈表情权重: 1.5 - 1.8
- 极端表情权重: 1.8 - 2.0
- 超过 2.0 可能导致画面崩坏

组合示例:
- (angry:1.5), (frowning:1.2)           = 愤怒+皱眉
- (blushing:1.4), (shy:1.2), (looking down:1.1) = 害羞脸红低头
- (surprised:1.5), (wide eyes:1.3), (mouth agape:1.2) = 震惊张嘴
- (crying:1.6), (tearful eyes:1.4), (trembling lips:1.2) = 哭泣
```

---

### 表情差分制作最佳流程

```
Step 1: 生成基础角色图
  └─ 使用固定 Seed + 详细角色描述

Step 2: 选择表情变更方法
  ├─ 快速自动：ADetailer（适合批量）⭐推荐
  ├─ 精确控制：Inpaint 局部重绘（适合单张精修）
  ├─ 姿势锁定：ControlNet + Inpaint（复杂姿势）
  ├─ 已有立绘：LivePortrait（视频迁移）
  ├─ 一键工具：TavernSprite 等在线工具
  └─ 新模型：FLUX/MJ Character Sheet（一次性生成）

Step 3: 只修改表情提示词
  └─ 保持角色描述、服装、姿势不变

Step 4: 调整参数
  └─ 重绘幅度 0.4-0.7（局部重绘）
  └─ ADetailer 去噪 0.35-0.65

Step 5: 批量生成
  └─ 使用 XYZ 图表或 Dynamic Prompts

Step 6: 筛选与后期
  └─ 用 Eagle 等工具管理生成图片
  └─ 必要时用 Photoshop 微调合成
```

---

## 五、推荐工具、LoRA 与扩展

### 5.1 AUTOMATIC1111 / Forge 扩展

| 扩展名称 | 功能 | 安装地址 |
|---------|------|---------|
| ADetailer | 自动面部检测+修复 | https://github.com/Bing-su/adetailer |
| Regional Prompter | 区域化提示词控制 | https://github.com/hako-mikan/sd-webui-regional-prompter |
| Dynamic Prompts | 动态/随机提示词 | https://github.com/adieyal/sd-dynamic-prompts |
| Booru Tag Autocomplete | 标签自动补全 | https://github.com/DominikDoom/a1111-sd-webui-tagcomplete |
| Civitai Helper | 模型管理 | https://github.com/zixaphir/Stable-Diffusion-Webui-Civitai-Helper |
| Inpaint Anything | 智能分割+修复 | https://github.com/Uminosachi/sd-webui-inpaint-anything |

### 5.2 ADetailer 检测模型

| 模型 | 修正对象 | 适用画风 |
|------|---------|---------|
| `face_yolov8n.pt` | 脸 | 动漫/写实 |
| `face_yolov8s.pt` | 脸 | 动漫/写实（精度更高） |
| `anime_face_yolov8.pt` | 脸 | 动漫（强烈推荐） |
| `hand_yolov8n.pt` | 手 | 动漫/写实 |
| `person_yolov8n-seg.pt` | 全身 | 动漫/写实 |
| `mediapipe_face_full` | 脸 | 写实 |
| `mediapipe_face_short` | 脸 | 写实 |
| `mediapipe_face_mesh` | 脸 | 写实 |

> ADetailer 对手部修正不太擅长，主要优势在面部。

### 5.3 ControlNet 模型

| 类型 | 预处理器 | 模型 | 适用场景 |
|------|----------|------|---------|
| OpenPose | `openpose_face` | `control_v11p_sd15_openpose` | 保持身体姿势 |
| OpenPose (face only) | `openpose_faceonly` | `control_v11p_sd15_openpose` | 只保持面部位置 |
| Canny | `canny` | `control_v11p_sd15_canny` | 保持边缘轮廓 |
| Depth | `depth` / `depth_anything` | `control_v11p_sd15_depth` | 保持空间深度 |
| Inpaint | `inpaint_only` / `inpaint_only+lama` | `control_v11p_sd15_inpaint` | 局部重绘控制 |
| Lineart | `lineart` | `control_v11p_sd15_lineart` | 动漫线稿保持 |
| Segmentation | `segmentation` | `control_v11p_sd15_seg` | 保持语义结构 |

### 5.4 推荐 LoRA（表情/风格控制）

| LoRA 名称 | 来源 | 触发词 | 说明 |
|----------|------|--------|------|
| **Facial Expression Style V3** | Civitai | `cinematic expression` + 表情词 | 写实+动漫混合表情，支持 XL/SD1.5/Flux |
| **Flux Kontext Expression Sheet** | Scenario | 自然语言描述 | 3×3 表情网格生成 |
| **Character Expression LoRA** | 自制 | 角色名 + 表情词 | 建议训练自己的角色 LoRA |
| **AnimeFaceID** | Civitai | 无特殊触发 | 身份保持+表情变化 |

**Facial Expression Style V3 触发词列表**：
```
cinematic expression, happy, sad, scared, worried, 
smile, surprised, Pleading, fear, crying, angry, 
Creep sinister, blushing flush
```

### 5.5 推荐基础模型（Checkpoint）

| 类型 | 推荐模型 | 适用场景 |
|------|---------|---------|
| 动漫/二次元 | AnythingV5, MeinaMix, Counterfeit-V3.0 | 日系美少女表情生成 |
| 最新动漫 | Illustrious | 2024 年后新动漫风格 |
| SDXL 动漫 | AnimagineXL, KohakuXL | 大分辨率动漫 |
| 写实/真人 | majicMIX realistic, RealisticVision | 真人风格表情控制 |
| 综合/高质量 | DreamShaper, AbyssOrangeMix3 | 通用高质量表情 |
| 粘土/特殊 | 配合 FLUX 使用 | 特殊风格 |

### 5.6 外部辅助工具

| 工具 | 用途 | 链接 |
|------|------|------|
| Danbooru Tag Wiki | 标签查询 | https://danbooru.donmai.us/tags |
| WD14 Tagger | 图片反推标签 | 内置于 WebUI / ComfyUI |
| DeepDanbooru | 图片反推标签 | 内置 / GitHub |
| ExcaliburAI | Civitai 提示词提取 | Chrome 扩展商店 |
| Anifusion Prompt Builder | 提示词构建 | https://anifusion.ai/free-tools/anime-prompt-builder/ |
| GPT-Image Expression Sheet | AI 表情网格生成 | https://gpt-image.com/nano-banana-pro/expression-sheet |
| TavernSprite | 一键生成 28 种表情差分 | https://tavernsprite.com/ |
| Eagle | 图片管理+提示词自动记录 | 第三方软件 |
| Aiarty Image Enhancer | 超分辨率放大 | 独立软件 |
| NovelAI to Eagle | 自动导入+标签管理 | 免费工具 |

---

## 六、样例图片与素材资源

### 6.1 ADetailer 表情控制样例（来源：AI图库吧）

| 描述 | 图片 URL |
|------|---------|
| 原图（得意笑） | https://www.aituku.cc/uploadfile/2024/1224/f96b075cc8dc1b30a994507d26d7cfe4.jpg |
| 愤怒表情 | https://www.aituku.cc/uploadfile/2024/1224/2af25e70cd1e693ca707286064cbed99.png |
| 微笑表情 | https://www.aituku.cc/uploadfile/2024/1224/6923f5c4d681f294ff451e9d44fddd81.png |
| ADetailer 插件界面 | https://www.aituku.cc/uploadfile/2024/1224/179ffff578809d8d087e5783c0f8680b.png |
| ADetailer 模型选择 | https://www.aituku.cc/uploadfile/2024/1224/fc4de976680e0213d9767b5622f01887.png |
| ADetailer 权重设置 | https://www.aituku.cc/uploadfile/2024/1224/9871df7d8ea64718b03f6096d201dddf.png |

### 6.2 日本 AI Arty 教程图（来源：jp.aiarty.com）

| 描述 | 图片 URL |
|------|---------|
| 立ち絵示例 | https://jp.aiarty.com/images/seo-img/lazy-img.png |
| ADetailer 界面 | https://jp.aiarty.com/images/seo-img/lazy-img.png |
| 表情差分示例 | https://jp.aiarty.com/images/seo-img/lazy-img.png |

### 6.3 Artvy.ai 动漫风格示例

| 描述 | 图片 URL |
|------|---------|
| 充满活力的动漫艺术 | https://cdn.prod.website-files.com/632ac1a36830f75c7e5b16f0/64f200e62c32bafc5ae09237_GKy2DCeBDS-Lt-X09y_aXs4LDA9k1DWcAHOjJcOu5_E.webp |
| 和服动漫镜头 | https://cdn.prod.website-files.com/632ac1a36830f75c7e5b16f0/67b7a532717062f1264e5154_qO_gmZMFpYWprwMoN_2LT6T9h5DNouK9PW7NbnL2mRs.webp |
| 电影级插画 | https://cdn.prod.website-files.com/632ac1a36830f75c7e5b16f0/64f200722f26cb94b8d02c66_HHl-Io1oPeG6BOWYSBQpBb5wK2a7Z2xksHhU6ZD0jPs.webp |
| 白裙蝙蝠 Tifa 艺术 | https://cdn.prod.website-files.com/632ac1a36830f75c7e5b16f0/64f2012d69656fa619259473_NrsBHdXDNWDv3KRLjDeANIwZk6bSBkqWigIp1ahua0U.webp |
| 金色长发粉色珍珠 | https://cdn.prod.website-files.com/632ac1a36830f75c7e5b16f0/67b7948e42927a2e070b038b_MoetnQLNOukQlzgsiZz_loC8PBGBrIzoRRw9YSH-9WQ.webp |
| 池塘艺术 | https://cdn.prod.website-files.com/632ac1a36830f75c7e5b16f0/67b79b66333f6c392dfda9ec_destiqUzs8qqv-ct4xky37QAVBoHz-TMSmu_mxpsxU0.webp |
| 童话电影感 | https://cdn.prod.website-files.com/632ac1a36830f75c7e5b16f0/64f1155076c7a7500c830c59_v833hWIt7NGvCHWiaGJgSo_W0r8wNq2aO3lcs-yExOw.webp |

### 6.4 其他示例图

| 描述 | 来源 | 图片 URL |
|------|------|---------|
| 动漫刘海风格测试（Anything 模型） | Kinda Nai | https://kindanai.com/wp-content/uploads/2024/03/anything_bangs_pulled-back-hair_3.jpg |
| 动漫刘海风格测试（MeinaMix） | Kinda Nai | https://kindanai.com/wp-content/uploads/2024/03/meinamixpulled-back-hair_0.jpg |
| 动漫刘海风格测试（DreamShaper） | Kinda Nai | https://kindanai.com/wp-content/uploads/2024/03/ds_pulled-back-hair_0.jpg |
| 动漫艺术示例 | WriteForUsTechnology | https://writeforustechnology.com/wp-content/uploads/2024/09/WhatsApp-Image-2024-09-08-at-22.40.17_ddcb4e0d-1.jpg |

### 6.5 可购买/下载的表情差分素材

| 来源 | 内容 | URL |
|------|------|-----|
| BOOTH 美少女立ち絵素材 Vol.1 | 全身立ち絵 + 表情差分 6 种（通常/笑顔/赤面/困り/泣き/驚き），透明背景 PNG | https://booth.pm/ja/items/6903136 |
| BOOTH 夏の花柄ワンピ少女・表情差分パック | 表情差分全 4 种 | https://booth.pm/ja/items/... |
| PIXTA ゲーム立ち絵素材 | 游戏立绘素材 | https://pixta.jp/tags/ゲーム立ち絵 |
| Pixiv 表情差分検索 | 表情差分插画 | https://www.pixiv.net/tags/表情差分 |

### 6.6 商用素材标准（BOOTH / VTuber 业界）

标准的 VTuber 立绘通常包含 **5-6 种表情差分**即可覆盖喜怒哀楽：

| 编号 | 表情 | 推荐提示词 | 用途 |
|------|------|----------|------|
| 1 | 通常 | `expressionless`, `neutral face` | 默认立绘 |
| 2 | 笑顔 | `smile`, `light smile`, `happy` | 日常/友好场景 |
| 3 | 赤面/害羞 | `blush`, `embarrassed`, `shy`, `nose blush` | 恋爱/羞涩场景 |
| 4 | 困り/困扰 | `troubled face`, `worried`, `sweatdrop`, `looking away` | 为难/困惑场景 |
| 5 | 泣き/哭泣 | `crying`, `tears`, `sobbing`, `sad` | 悲伤场景 |
| 6 | 驚き/惊讶 | `surprised`, `wide-eyed`, `shocked`, `open mouth` | 震惊场景 |

扩展可选：angry（愤怒）、serious（认真）、smug（得意）、sleepy（困倦）等。

---

## 七、来源参考与资源链接

### 中文社区来源

| 序号 | 来源名称 | URL | 主要内容 |
|------|---------|-----|---------|
| 1 | Bilibili - 表情差分制作 | https://www.bilibili.com/read/cv34326971/ | 局部重绘+ADetailer+XYZ图表制作差分 |
| 2 | AI图库吧 - ADetailer 表情控制 | https://www.aituku.cc/info/355.html | ADetailer 插件控制表情详细教程 |
| 3 | AI奇点网 - ADetailer 教程 | https://www.aieva.cn/edu/750.html | After Detailer 插件控制表情教程 |
| 4 | 智汇AI - ADetailer 教程 | https://ai.gameba.cc/wz/3327.html | 2025 年更新版 |
| 5 | 百度贴吧 - Stable Diffusion 吧 | https://tieba.baidu.com/p/9474364948 | 表情动作差分讨论 |
| 6 | 百度贴吧 - NovelAI 表情差分 | https://tieba.baidu.com/p/8091371974 | 使用 NovelAI 生成角色表情差分教程 |
| 7 | Midjourney 中文站 | https://www.midjourny.cn/mj-detail/mj-detail251638_1.html | 人物立绘表情差分提示词示例 |
| 8 | 知乎 - Stable Diffusion 表情提示词 | https://zhuanlan.zhihu.com/p/651648278 | 筛选出的效果好的表情提示词 |
| 9 | 知乎 - 人物表情提示词大全 | https://zhuanlan.zhihu.com/p/650573538 | 大量表情词中英文对照 |
| 10 | 知乎 - AdvancedLivePortrait | https://zhuanlan.zhihu.com/p/28884062130 | 漫画立绘表情差分+写真表情修复 |
| 11 | CSDN - 62 个 SD 表情提示词 | https://blog.csdn.net/qq_20288327/article/details/129354498 | 62 种表情分类整理 |
| 12 | CSDN - 表情提示词 | https://blog.csdn.net/2401_84760527/article/details/139113498 | 插件推荐和表情提示词 |
| 13 | 站酷 - LivePortrait 表情差分 | https://m.zcool.com.cn/article/ZMTY5ODg5Ng==.html | LivePortrait+PS 量产 AVG 游戏表情差分 |
| 14 | 腾讯云 - LivePortrait | https://cloud.tencent.com/developer/news/2280263 | AdvancedLivePortrait 动态表情修改 |
| 15 | 知乎想法 - 局部修改表情 | https://www.zhihu.com/pin/1639155185720172544 | SD 局部重绘修改表情技巧 |
| 16 | 哔哩哔哩 - ComfyUI 差分 | https://www.bilibili.com/opus/929387200120881255 | ComfyUI 差分扩散融图教程 |
| 17 | 博客园 - AI 表情提示词实战 | https://blog.csdn.net/2600_94960044/article/details/157039616 | 表情提示词实战指南 |
| 18 | 共绩算力 - 16 格表情包 | https://www.gongjiyun.com/blog/2026/4/izdgwlhjtisom5kxf6xc1netnsd/ | GPT-Image-2 16 格表情差分提示词 |

### 英文社区来源

| 序号 | 来源名称 | URL | 主要内容 |
|------|---------|-----|---------|
| 1 | ReShot.ai - Expression Sheet Guide | https://www.reshot.ai/blog/character-expression-sheet | 2025 年表情表终极指南 |
| 2 | Kalon.ai - AI Character Sheet Prompts | https://www.kalon.ai/templates/ai-character-sheet-prompts | AI 角色表提示词，一致性解决方案 |
| 3 | PromptGather.io - Character Design Sheet | https://promptgather.io/image/awymR2OvX5 | 多姿势表情设计表提示词 |
| 4 | GPT-Image.com - Expression Sheet | https://gpt-image.com/nano-banana-pro/expression-sheet | AI 表情网格生成器 |
| 5 | Anifusion - Anime Prompt Builder | https://anifusion.ai/free-tools/anime-prompt-builder/ | 动漫提示词构建器 |
| 6 | TopFreePrompts - Sora Anime Prompts | https://www.topfreeprompts.com/sora-anime-prompts/ | 少年恋爱动漫提示词 |
| 7 | Write For Us Technology - SD Anime Prompts | https://www.writeforustechnology.com/stable-diffusion-anime-prompt/ | Top 20 SD 动漫提示词 |
| 8 | Artvy.ai - Anime Prompts | https://www.artvy.ai/prompt/ | 多个动漫角色提示词示例 |
| 9 | PromptBase - Anime Character Designs | https://promptbase.com/prompt/anime-character-designs-6 | 角色设计提示词模板 |
| 10 | EasyDrawingGuides - Anime Expressions | https://easydrawingguides.com/how-to-draw-anime-and-manga-facial-expressions/ | 动漫表情绘画教程 |
| 11 | Nemora.ai - AI Image Generation Guide | https://nemora.ai/blog/the-definitive-guide-to-ai-image-generation/ | 终极 AI 图像生成指南 |
| 12 | Reddit r/StableDiffusion | https://www.reddit.com/r/StableDiffusion/comments/ycgfgo/ | Img2tiles / Inpainting Tips |
| 13 | Reddit r/comfyui | https://reddit.com/r/comfyui | ComfyUI 工作流讨论 |
| 14 | Civitai - Facial Expression Style V3 | https://civitai.com/models/541620 | 表情风格 LoRA |
| 15 | Scenario - Flux Kontext Expression Sheet | https://www.scenario.com/models/facial-expression-sheet-kontext | 3×3 表情网格 LoRA |

### 日文社区来源

| 序号 | 来源名称 | URL | 主要内容 |
|------|---------|-----|---------|
| 1 | JP.Aiarty - 立ち絵表情差分 | https://jp.aiarty.com/image-generator/character-sprite-stable-diffusion.htm | 立ち絵生成、表情差分、服装差分完整教程 |
| 2 | BOOTH - 美少女立ち絵素材 | https://booth.pm/ja/items/6903136 | 商用 AI 素材：6 种表情差分 |
| 3 | weel.co.jp - SD プロンプト大全 | https://weel.co.jp/media/stable-diffusion-spell/ | 表情分类提示词 |
| 4 | ai.joho.info - プロンプト呪文集 | https://ai.joho.info/prompt-image-genaration/ | 顔・表情・口のプロンプト一覧 |
| 5 | withballoons.jp - 表情プロンプト | https://withballoons.jp/stable-diffusion-hyojyo-prompt02/ | 感情別表情リスト |
| 6 | qbei.isotop.jp - 表情生成完全ガイド | https://qbei.isotop.jp/archives/2878 | 2025 最新感情別キーワード集 |
| 7 | runrunsketch.net - 表情呪文総まとめ | https://runrunsketch.net/expression/ | NovelAI/SD 表情呪文+目/口調整 |
| 8 | hikari-aiart.com - 表情プロンプト | https://hikari-aiart.com/stable-diffusion-facial-expression-pronpt/ | 各表情プロンプト生成图 |
| 9 | onlinegamernikki.com - ANIMAGINE XL | https://onlinegamernikki.com/ai-illustration-facial-expression-prompt-comparison | 表情辞典（画像付き） |
| 10 | UnbeReal - VTuber 用語 | https://unbereal.co.jp/vtuberaudition/vtuber_terminology/ | 表情差分定义（5-6 種類で喜怒哀楽カバー） |
| 11 | PIXTA - ゲーム立ち絵素材 | https://pixta.jp/tags/ゲーム立ち絵 | 游戏立绘素材 |
| 12 | SDesignLabo - キャラクターイラスト | https://sdesignlabo.com/design/character-illust/ | 角色立绘素材 |
| 13 | Honogear - Niji Journey v7 | https://www.honogear.com/zh/blog/engineering/niji-journey-v7-guide | Niji v7 角色一致性与表情差分 |
| 14 | iPentec - ADetailer 顔 LoRA 適用 | https://www.ipentec.com/articles/ai-image/software-stable-diffusion-apply-lora-to-face-only-using-adetailer | 顔のみに LoRA 適用して表情変更 |
| 15 | soroban.highreso.jp - ADetailer 教程 | https://soroban.highreso.jp/article/article-085 | ADetailer で表情差分を作成する方法 |
| 16 | ai-illust-kouryaku.com - ADetailer | https://ai-illust-kouryaku.com/archives/9745 | ADetailer で表情差分を作成する方法 |
| 17 | gift-by-gifted.com - ADetailer | https://gift-by-gifted.com/stable-diffusion-adetailer/ | ADetailer で顔の崩れ補正と表情差分作成 |
| 18 | onlinegamernikki.com - ADetailer | https://onlinegamernikki.com/ai-illustration-facial-expression-difference | ADetailer で表情差分を簡単に作る方法 |

### 技术文档与论文

| 来源 | 标题 | URL |
|------|------|-----|
| Semantic Scholar | Game Character Design with AI (Expression Sheet) | https://pdfs.semanticscholar.org/488f/a1c076602ef5d641bec86da99961332f19cc.pdf |
| ADetailer GitHub | 官方文档 | https://github.com/Bing-su/adetailer |
| ADetailer 讨论 | SD vs ADetailer 提示词区别 | https://github.com/Bing-su/adetailer/discussions/660 |
| LivePortrait GitHub | 表情迁移 | https://github.com/KwaiVGI/LivePortrait |

---

## 附录：快速检索表

### 按场景分类

**恋爱/告白场景**:
`blushing`, `shy`, `heart-shaped eyes`, `lovestruck`, `nervous smile`, `hands clasped`, `softly smiling`, `teary eyes`, `happy tears`, `embarrassed`, `looking away`, `pouting`, `seductive smile`

**战斗/热血场景**:
`determined`, `gritting teeth`, `serious expression`, `fighting spirit`, `angry`, `focused`, `shouting`, `confident smirk`, `fierce expression`, `battle-ready stance`, `crazy grin`, `glowing eyes`, `bared teeth`

**日常/轻松场景**:
`smile`, `happy`, `cheerful`, `relaxed`, `playful`, `mischievous`, `yawning`, `sleepy`, `eating`, `singing`, `winking`, `thumbs up`, `waving`, `head tilt`, `tongue out`

**悲伤/离别场景**:
`crying`, `tears`, `sad`, `depressed`, `gloomy`, `tearful eyes`, `downturned lips`, `waving goodbye`, `trembling lips`, `heartbroken`, `despairing`, `melancholy`, `lonely`

**震惊/发现场景**:
`surprised`, `shocked`, `wide eyes`, `mouth agape`, `pupil shrink`, `flustered`, `confused`, `bewildered`, `dumbfounded`, `startled`, `panicking`

**喜剧/搞笑场景**:
`laughing`, `grinning`, `thumbs up`, `winking`, `tongue out`, `silly face`, `exaggerated expression`, `chibi shocked`, `sweat drop`, `orz`, `puffed cheeks`, `cat mouth`

### 表情生成检查清单

- [ ] 固定 Seed（保持角色一致性）
- [ ] 固定 Sampler（如 DPM++ 2M Karras）
- [ ] 固定 CFG Scale（通常 7-9）
- [ ] 固定 Steps（通常 20-30）
- [ ] 仅替换表情相关标签
- [ ] 使用 `white_background` 或 `simple_background`
- [ ] 使用 `portrait` / `upper_body` 构图
- [ ] 添加负面提示词排除不想要的表情
- [ ] 使用 ADetailer 或 ControlNet Inpaint 进行精细控制
- [ ] 眉毛必须纳入重绘范围
- [ ] 表情提示词放在靠前位置提高权重

### 推荐参数组合（快速设置）

| 场景 | Sampler | Steps | CFG | Denoising | 工具 |
|------|---------|-------|-----|-----------|------|
| 基础表情生成 | DPM++ 2M Karras | 25 | 7 | - | txt2img |
| 轻度表情修改 | DPM++ 2M Karras | 20 | 7 | 0.35-0.45 | ADetailer |
| 中度表情修改 | DPM++ 2M Karras | 25 | 7 | 0.45-0.55 | Inpaint |
| 大幅表情重绘 | Euler a | 30 | 8 | 0.55-0.65 | Inpaint + ControlNet |
| 批量表情生成 | DPM++ 2M Karras | 20 | 7 | - | Dynamic Prompts + Batch |

---

> **免责声明**：本资料仅用于 AI 绘画学习和研究目的。使用 AI 生成内容时，请遵守各平台服务条款和当地法律法规。部分来源内容为网络公开资料整理，版权归原作者所有。
> 
> **文档版本**：v1.0 整合版  
> **收集日期**：2025 年  
> **收集工具**：kimi_search_v2 / kimi_fetch_v2 / 多 Agent 并行收集  
> **适用平台**：Stable Diffusion WebUI / Forge / ComfyUI / NovelAI / AUTOMATIC1111 / Midjourney / FLUX  
> **文档规模**：约 300+ 表情关键词｜7 种核心制作方法｜30+ 来源 URL｜20+ 样例图片链接
