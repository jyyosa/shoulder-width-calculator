# 动漫/二次元女性角色表情差分生成提示词资源汇总

> 收集来源：中文社区、英文社区、日文社区（混合搜索）
> 收集时间：2025年
> 适用工具：Stable Diffusion / Midjourney / NovelAI / FLUX 等 AI 文生图/图生图工具
> 聚焦：动漫女性角色表情变化（expression sheet / 表情差分 / 表情集）

---

## 目录

1. [表情关键词分类（中英文对照）](#一表情关键词分类中英文对照)
2. [完整提示词模板示例](#二完整提示词模板示例)
3. [负面提示词（Negative Prompt）](#三负面提示词negative-prompt)
4. [制作表情差分的方法与技巧](#四制作表情差分的方法与技巧)
5. [来源参考与资源链接](#五来源参考与资源链接)
6. [样例图片链接](#六样例图片链接)

---

## 一、表情关键词分类（中英文对照）

### 1. 基础笑容 / Happy & Smiling

| 中文描述 | 英文提示词 | 适用场景 | 强度 |
|---------|-----------|---------|------|
| 基础微笑 | `happy`, `smile` | 日常愉悦、温暖情境 | 中等 |
| 愉快轻松 | `cheerful`, `playful` | 轻松对话、互动场景 | 较高 |
| 快活 | `jolly` | 活泼氛围 | 较高 |
| 温柔的微笑 | `softly smiling` | 柔和、治愈场景 | 中等 |
| 浅笑/得意笑 | `smirk` | 自信、调皮 | 中等 |
| 开怀大笑 | `laughing` | 欢乐、喜剧场景 | 高 |
| 咧嘴笑 | `grin` | 活泼、俏皮 | 较高 |
| 露齿微笑 | `light smile` | 温和亲切 | 低 |
| 闭眼微笑 | `smiling with eyes closed` | 幸福、满足 | 中等 |
| 希望满满的表情 | `hopeful` | 期待、憧憬 | 中等 |
| 至上幸福 | `goddess-like happiness` | 神圣、极度幸福 | 高 |
| 骄傲自豪 | `proud` | 成就感 | 中等 |
| 咯咯笑 | `chuckling` | 轻松偷笑 | 低 |
| 被逗乐 | `amused` | 有趣场景 | 中等 |
| 高兴 | `pleased` | 满意 | 中等 |
| 轻松 | `relaxed` | 放松状态 | 低 |
| 好奇 | `curious` | 探索、疑问 | 低 |

### 2. 愤怒与烦躁 / Angry & Irritated

| 中文描述 | 英文提示词 | 适用场景 | 强度 |
|---------|-----------|---------|------|
| 生气 | `angry` | 日常愤怒 | 中等 |
| 激怒 | `furious` | 极度愤怒 | 高 |
| 急躁 | `exasperated` | 不耐烦 | 中等 |
| 恼怒 | `irritated`, `annoyed` | 小烦恼 | 低-中 |
| 懊恼 | `frustrated` | 受挫 | 中等 |
| 失望 | `disappointed` | 期望落空 | 中等 |
| 愤慨 | `indignant` | 正义之怒 | 较高 |
| 怨恨 | `resentful` | 积怨 | 中等 |
| 挑衅 | `defiant` | 对抗 | 较高 |
| 攻击性 | `aggressive` | 威胁 | 高 |
| 发脾气 | `grumpy` | 暴躁 | 中等 |
| 大喊大叫 | `shouting` | 激烈冲突 | 高 |
| 疯了 | `mad` | 失去理智 | 高 |

### 3. 悲伤与忧郁 / Sad & Melancholy

| 中文描述 | 英文提示词 | 适用场景 | 强度 |
|---------|-----------|---------|------|
| 悲伤 | `sad` | 基础悲伤 | 中等 |
| 不开心 | `unhappy` | 轻微低落 | 低 |
| 忧郁 | `melancholy`, `gloomy` | 深沉忧伤 | 高 |
| 郁闷 | `somber`, `depressed` | 压抑 | 高 |
| 受伤 | `hurt` | 情感创伤 | 中等 |
| 哀痛 | `mournful` | 哀悼 | 高 |
| 嘴角下垂表示难过 | `downturned lips, looking sad` | 具体表情 | 中等 |
| 嘴角下垂表示失望 | `downturned mouth, indicating disappointment` | 具体表情 | 低 |
| 泪眼悲伤 | `tearful eyes, expressing sadness` | 含泪 | 中等 |
| 沮丧 | `frustrated` (复合) | 挫败感 | 中等 |
| 痛苦 | `pain` | 身心痛苦 | 高 |

### 4. 哭泣与眼泪 / Crying & Tears

| 中文描述 | 英文提示词 | 适用场景 | 强度 |
|---------|-----------|---------|------|
| 哭泣 | `crying`, `cry` | 基础哭泣 | 高 |
| 流泪 | `tears`, `tearful` | 含泪水 | 中等 |
| 泪眼汪汪 | `teary-eyed` | 感动/委屈 | 中等 |
| 啜泣 | `sobbing tears` | 哭得很伤心 | 高 |
| 喜极而泣 | `crying laughing` | 复杂情绪 | 高 |
| 被感动流泪 | `moved tears`, `touched tears` | 感动 | 中等 |
| 如释重负的泪 | `relieved tears` | 安心哭泣 | 中等 |
| 喜极而泣 | `happy crying`, `joyful tears` | 喜悦泪水 | 中等 |
| 悲伤哭泣 | `sad crying` | 痛苦哭泣 | 高 |
| 害羞哭泣 | `shy crying`, `bashful crying` | 害羞到哭 | 高 |
| 尴尬的哭泣 | `awkward crying`, `nervous crying` | 紧张哭泣 | 中等 |
| 哭到脸红 | `crying blush`, `flushed crying` | 激动哭泣 | 高 |
| 泪水滑落 | `tears streaming down face` | 大哭 | 高 |

### 5. 惊讶与震惊 / Surprised & Shocked

| 中文描述 | 英文提示词 | 适用场景 | 强度 |
|---------|-----------|---------|------|
| 惊讶 | `surprised`, `surprise` | 基础惊讶 | 中等 |
| 震惊 | `shocked`, `astonished` | 强烈冲击 | 高 |
| 目瞪口呆 | `stunned`, `flabbergasted` | 难以置信 | 高 |
| 不知所措 | `bewildered`, `puzzled` | 困惑 | 中等 |
| 压倒性的 | `overwhelmed` | 信息过载 | 较高 |
| 难以置信 | `incredulous` | 怀疑 | 中等 |
| 敬畏 | `awe-struck` | 震撼 | 高 |
| 着迷 | `fascinated`, `intrigued` | 感兴趣 | 中等 |
| 惊愕 | `amazed` | 惊喜 | 中等 |
| 张大嘴震惊 | `mouth agape, expressing shock` | 具体表情 | 高 |
| 挑眉 | `raised eyebrows` | 配合惊讶 | 低 |
| 眼睛睁大 | `wide eyes`, `eyes widened` | 配合惊讶 | 低 |
| 瞳孔收缩 | `pupils dilated` | 震惊/恐惧 | 中等 |

### 6. 害羞与脸红 / Shy & Blushing

| 中文描述 | 英文提示词 | 适用场景 | 强度 |
|---------|-----------|---------|------|
| 害羞 | `shy`, `shyness` | 基础害羞 | 中等 |
| 脸红 | `blushing`, `blush` | 面部泛红 | 中等 |
| 尴尬 | `embarrassed` | 难堪 | 中等 |
| 慌张 | `flustered` | 手忙脚乱 | 较高 |
| 害羞低头 | `shy, blushing and looking down` | 具体动作 | 高 |
| 强烈脸红 | `intense blush`, `blushing hard` | 极度害羞 | 高 |
| 突然脸红 | `sudden blush`, `impact blush` | 意外触发 | 高 |
| 热到脸红 | `overheating blush`, `hot cheeks` | 强烈反应 | 高 |
| 害羞到说不出话 | `overwhelmingly cute blush` | 超级害羞 | 极高 |
| 眼含泪水害羞 | `shy crying` | 委屈+害羞 | 高 |
| 脸红出汗 | `nervous sweating + blush` | 紧张害羞 | 高 |

### 7. 恐惧与害怕 / Fear & Scared

| 中文描述 | 英文提示词 | 适用场景 | 强度 |
|---------|-----------|---------|------|
| 害怕 | `afraid`, `scared` | 基础恐惧 | 中等 |
| 恐怖 | `horrified` | 极度恐惧 | 高 |
| 担心 | `worried`, `anxiety` | 不安 | 低-中 |
| 紧张 | `tense`, `nervous` | 焦虑 | 低 |
| 惊惧 | `terrified` | 惊恐 | 高 |
| 害怕到闭眼 | `screaming with eyes shut` | 具体动作 | 高 |
| 害怕到捂嘴 | `hand over mouth in fear` | 具体动作 | 高 |
| 发抖 | `trembling`, `shivering` | 生理反应 | 中等 |
| 背脊发凉 | `spine-chilling` | 恐怖氛围 | 高 |

### 8. 无表情与冷漠 / Neutral & Cold

| 中文描述 | 英文提示词 | 适用场景 | 强度 |
|---------|-----------|---------|------|
| 无表情 | `expressionless` | 面瘫 | 无 |
| 扑克脸 | `poker face` | 隐藏情绪 | 无 |
| 无聊 | `bored` | 厌倦 | 无 |
| 冷漠 | `indifferent`, `cold expression` | 疏远 | 低 |
| 严肃 | `serious-looking`, `serious` | 认真 | 低 |
| 冷漠抱手 | `crossing arms, displaying indifference` | 具体动作 | 低 |
| 凝视远方 | `gazing into the distance, displaying indifference` | 走神 | 低 |
| 淡然 | `calm`, `tranquil` | 平静 | 无 |

### 9. 困惑与思考 / Confused & Thinking

| 中文描述 | 英文提示词 | 适用场景 | 强度 |
|---------|-----------|---------|------|
| 困惑 | `confused`, `bewildered` | 不解 | 中等 |
| 迷茫 | `puzzled` | 想不通 | 中等 |
| 思考 | `thinking`, `deep in thought` | 沉思 | 低 |
| 怀疑 | `suspicious`, `doubtful` | 不信任 | 中等 |
| 戒备 | `alert`, `vigilant` | 警惕 | 中等 |
| 若有所思 | `contemplative` | 深沉思考 | 低 |
| 歪头困惑 | `head tilt, confused` | 具体动作 | 低 |

### 10. 调皮与恶作剧 / Mischievous & Playful

| 中文描述 | 英文提示词 | 适用场景 | 强度 |
|---------|-----------|---------|------|
| 调皮 | `mischievous` | 恶作剧 | 中等 |
| 吐舌头 | `tongue out` | 俏皮 | 低 |
| 流口水 | `drooling` | 贪吃/花痴 | 低 |
| 得意 | `smug` | 自满 | 中等 |
| 眨眼 | `winking` | 俏皮 | 低 |
| 飞吻 | `blowing a kiss`, `air kiss` | 可爱 | 低 |
| 嘟嘴 | `pouting` | 撒娇 | 低 |
| 撅嘴叉臂 | `pouting and crossing arms` | 闹脾气 | 中等 |
| 竖起大拇指 | `thumbs up` | 赞 | 低 |
| 挥手 | `waving` | 打招呼 | 低 |
| 歪头 | `head tilt` | 可爱 | 低 |
| 打哈欠 | `yawning` | 困倦 | 低 |
| 揉眼睛 | `rubbing eyes` | 刚睡醒 | 低 |
| 舔嘴唇 | `licking lips` | 诱惑 | 中等 |
| 张嘴 | `open mouth` | 惊讶/呼吸 | 低 |
| 闭嘴 | `closed mouth` | 沉默 | 无 |
| 闭眼 | `eyes closed`, `eyes tightly shut` | 睡觉/享受 | 无 |
| 翻白眼 | `rolling eyes` | 无语 | 低 |
| 眯眼 | `squinting` | 怀疑/聚焦 | 低 |
| 皱眉 | `frowning` | 不满/思考 | 低 |
| 挑眉 | `raised eyebrow` | 惊讶/怀疑 | 低 |

### 11. 日系/动漫特有表情 / Anime-Specific Expressions

| 中文描述 | 英文提示词 | 日文对照 | 适用场景 |
|---------|-----------|---------|---------|
| 闪闪发光的眼睛 | `sparkling eyes`, `shiny eyes` | キラキラ目 | 兴奋/期待 |
| 失望的眼神 | `disappointed eyes`, `dull eyes` | 死んだ目 | 失落 |
| 半闭眼 | `half-closed eyes`, `droopy eyes` | ジト目 | 慵懒/无语 |
| 眼睛变成线条 | `eye beams`, `expression lines` | 目が線になる | 无奈 |
| 画风崩坏 | `deformed expression`, `simplified face` | デフォルメ顔 | 搞笑 |
| 石化 | `turned to stone`, `frozen` | 石化 | 震惊过度 |
| 灵魂出窍 | `ghost leaving body`, `spirit floating` | 魂抜け | 极度震惊 |
| 脸上阴影线 | `shadow over face`, `dark aura` | 顔に影 | 生气/阴沉 |
| 青筋暴起 | `vein popping`, `forehead vein` | 青筋 | 愤怒 |
| 爱心眼 | `heart-shaped eyes`, `heart eyes` | ハート目 | 花痴/恋爱 |
| 星星眼 | `star-shaped eyes`, `star eyes` | 星目 | 崇拜 |
| 漩涡眼 | `swirl eyes`, `@_@` | ぐるぐる目 | 眩晕 |
| 猫嘴 | `:3 mouth`, `cat mouth` | 猫口 | 可爱/调皮 |
| 三角形嘴 | `triangle mouth`, `small mouth` | △口 | 惊讶/可爱 |
| 被催眠 | `hypnotized`, `empty eyes`, `no pupils` | 催眠 | 控制/恍惚 |
| 眼神空洞 | `empty eyes`, `hollow eyes`, `no pupils` | 空っぽの目 | 失神 |
| 流口水放空 | `drooling`, `messy hair`, `open mouth` | よだれ | 失神/ hypnotized |
| 自信满满 | `smug`, `confident smile` | ドヤ顔 | 得意 |
| 痛苦表情 | `painful expression`, `suffering` | 苦悶 | 受难 |
| 享受表情 | `blissful expression`, `ecstasy` | 恍惚 | 极度享受 |
| 阴险笑 | `sly smile`, `cunning grin` | にやり | 反派 |
| 坏笑 | `evil grin`, `devilish smile` | イケメン笑い | 腹黑 |
| 温柔含笑 | `softly smiling, expressing tenderness` | 柔らかい微笑み | 治愈 |
| 仰望天空 | `tilting head back and gazing upwards` | 空を見上げる | 惆怅 |
| 害羞看向别处 | `shy, looking away` | そっぽを向く | 害羞 |
| 不满抿嘴 | `tight-lipped, showing dissatisfaction` | 不満そうに口を尖らす | 生气 |
| 惊恐表情 | `terrified expression`, `panic` | パニック顔 | 极度恐惧 |
| 尖叫 | `screaming` | 絶叫 | 恐惧/疼痛 |
| 疲惫 | `exhausted`, `tired expression` | 疲れ顔 | 疲劳 |
| 困倦 | `sleepy`, `drowsy` | 眠そう | 想睡 |
| 警觉 | `alert`, `on guard` | 警戒顔 | 警惕 |
| 专注 | `focused`, `concentrated` | 集中 | 认真 |
| 蔑视 | `contemptuous`, `scornful` | 軽蔑 | 轻视 |
| 嫉妒 | `jealous`, `envious` | 嫉妬 | 嫉妒 |
| 恶心 | `disgusted`, `nasty` | 嫌悪 | 厌恶 |
| 令人毛骨悚然 | `creepy smile`, `unsettling expression` | 不気味 | 恐怖 |
| 醉酒 | `blind drunk`, `roaring drunk` | 泥酔 | 喝醉 |
| 唱着歌 | `singing` | 歌う | 快乐 |
| 戴着口罩 | `face with medical mask` | マスク | 现代场景 |
| 吃东西 | `eating`, `chewing` | 食事 | 日常 |
| 打瞌睡 | `dozing`, `nodding off` | うとうと | 困倦 |
| 惊跳起来 | `jumping in surprise`, `startled` | 飛び上がる | 突然惊吓 |
| 害羞捂脸 | `covering face in embarrassment`, `hands on cheeks` | 顔を覆う | 极度害羞 |
| 脸红到耳朵 | `blushing ears`, `red ears` | 耳まで赤い | 超级害羞 |
| 冒汗 | `sweating`, `nervous sweat drop` | 汗 | 紧张/尴尬 |
| 冷汗 | `cold sweat` | 冷や汗 | 害怕/尴尬 |
| 瀑布汗 | `sweating profusely`, `waterfall sweat` | 滝汗 | 极度紧张 |
| 青筋+微笑 | `smiling with veins` | 怒りの笑顔 | 生气但保持微笑 |
| 黑化 | `yandere face`, `dark smile`, `crazy eyes` | ヤンデレ顔 | 病娇/黑化 |
| 傲娇 | `tsundere expression`, `looking away blushing` | ツンデレ | 傲娇 |
| 天然 | `airhead expression`, `spaced out` | 天然 | 天然呆 |
| 腹黑 | `scheming smile`, `hidden intent` | 腹黒 | 内心算计 |
| 呆毛翘起 | `ahoge`, `hair standing up` | アホ毛 | 惊讶/困惑 |
| 炸毛 | `hair fluffed up`, `messy hair from shock` | 逆毛 | 惊吓 |
| 画圈圈 | `depression spiral`, `background lines` | 落ち込み | 失落 |
| 跪地石化 | `kneeling, turned to stone` | 石化膝つく | 彻底崩溃 |
| 跪地orz | `orz`, `kneeling in defeat` | orz | 认输 |
| 得意地挺起胸膛 | `proud chest puffed out` | 得意げ | 自豪 |
| 垂头丧气 | `hanging head`, `shoulders drooping` | 肩を落とす | 沮丧 |
| 抱头蹲防 | `crouching with head in hands` | 頭を抱える | 害怕/崩溃 |
| 手指戳戳 | `poking fingers together`, `fidgeting` | 指をもじもじ | 紧张害羞 |
| 咬手帕 | `biting handkerchief`, `teary biting` | ハンカチを噛む | 委屈/嫉妒 |
| 空中飘花 | `flower petals background`, `romantic aura` | 花びら舞う | 浪漫/幸福 |
| 周围变黑 | `dark background`, `dark aura` | 周りが暗くなる | 生气/阴沉 |
| 背景变灰 | `gray background`, `desaturated` | 背景グレー | 失落 |
| 全身发白 | `turned pale`, `white as sheet` | 真っ青 | 震惊/恐惧 |
| 眼睛失去高光 | `eyes without highlights`, `dead eyes` | ハイライト消滅 | 绝望/失神 |
| 爱心 bubbles | `love bubbles`, `floating hearts` | 愛のハート | 恋爱脑 |
| 鼻子冒泡 | `nose bubble`, `sleep bubble` | 鼻の泡 | 熟睡 |
| 日式戏剧流汗 | `anime sweat drop`, `large sweat drop` | 大粒の汗 | 尴尬/无语 |
| 风把人吹走 | `wind blowing away`, `floating away` | 吹き飛ぶ | 震惊/夸张 |

### 12. 嘴部动作与细节 / Mouth Actions

| 中文描述 | 英文提示词 | 效果 |
|---------|-----------|------|
| 张嘴 | `open mouth` | 基础口型 |
| 闭嘴 | `closed mouth` | 基础口型 |
| 吐舌头 | `tongue out` | 俏皮/诱惑 |
| 流口水 | `drooling` | 失神/贪吃 |
| 咬嘴唇 | `biting lip` | 诱惑/紧张 |
| 抿嘴 | `pursed lips` | 不满/思考 |
| 嘟嘴 | `pouting` | 撒娇/生气 |
| 咧嘴 | `grinning` | 大笑 |
| 咬牙切齿 | `gritting teeth`, `clenched teeth` | 愤怒/忍耐 |
| 咬紧牙关 | `teeth clenched` | 痛苦/决心 |
| 嘴唇微张 | `slightly open mouth`, `parted lips` | 惊讶/呼吸 |
| 深呼吸 | `deep breath`, `inhaling` | 紧张/平静 |
| 叹气 | `sighing`, `exhaling` | 无奈/放松 |
| 打哈欠 | `yawning` | 困倦 |
| 唱歌 | `singing`, `singing with mouth open` | 欢乐 |
| 大喊 | `shouting`, `screaming` | 激烈情绪 |
| 屏住呼吸 | `holding breath`, `gasping` | 惊讶/紧张 |
| 倒吸一口气 | `sharp inhale`, `gasp` | 震惊 |
| 鼓脸颊 | `puffed cheeks`, `cheeks puffed` | 可爱/生气 |
| 脸颊凹陷 | `sunken cheeks` | 消瘦/痛苦 |
| 吃东西鼓嘴 | `cheeks full of food`, `munching` | 可爱 |
| 叼着面包 | `toast in mouth`, `bread in mouth` | 日式经典场景 |
| 叼着吸管 | `drinking with straw` | 日常 |
| 舔 | `licking` | 诱惑/品尝 |
| 吹气 | `blowing` | 寒冷/吹东西 |
| 呼出白气 | `visible breath`, `cold breath` | 寒冷场景 |
| 嘴角上扬 | `upturned mouth corners` | 微笑迹象 |
| 嘴角下垂 | `downturned mouth corners` | 悲伤迹象 |
| 单边嘴角上扬 | `smirk`, `half-smile` | 得意/嘲讽 |
| 露出虎牙 | `fangs showing`, `canine teeth` | 可爱/危险 |
| 牙齿闪亮 | `sparkling teeth`, `gleaming teeth` | 漫画效果 |

### 13. 眼部动作与细节 / Eye Actions

| 中文描述 | 英文提示词 | 效果 |
|---------|-----------|------|
| 眼睛睁大 | `wide eyes`, `eyes widened` | 惊讶/恐惧 |
| 眼睛眯起 | `narrowed eyes`, `squinting` | 怀疑/聚焦 |
| 半闭眼 | `half-closed eyes`, `droopy eyes` | 慵懒/无语 |
| 闭眼 | `eyes closed`, `eyes shut` | 睡觉/享受/微笑 |
| 紧闭双眼 | `eyes tightly shut` | 痛苦/恐惧/强烈情绪 |
| 单眨眼 | `winking`, `one eye closed` | 俏皮/暗示 |
| 向上看 | `looking up`, `gazing up` | 期待/祈祷 |
| 向下看 | `looking down`, `gazing down` | 害羞/思考/悲伤 |
| 看向侧面 | `looking to the side`, `side glance` | 回避/偷看 |
| 回头看 | `looking back`, `turning head` | 惊讶/警惕 |
| 凝视 | `staring`, `gazing intently` | 专注/强烈情感 |
| 凝视远方 | `gazing into the distance` | 思考/惆怅 |
| 翻白眼 | `rolling eyes`, `eyes rolled back` | 无语/晕厥 |
| 向上翻白眼 | `looking up, no pupils`, `eye roll` | 失神/催眠 |
| 眼睛失去高光 | `empty eyes`, `eyes without highlights`, `no light in eyes` | 绝望/失神 |
| 眼睛闪烁 | `eyes sparkling`, `shiny eyes`, `star eyes` | 兴奋/崇拜/恋爱 |
| 眼睛变成爱心 | `heart-shaped eyes`, `heart eyes` | 花痴/恋爱 |
| 眼睛含泪 | `tearful eyes`, `watery eyes`, `eyes brimming with tears` | 悲伤/感动 |
| 眼睛红肿 | `red eyes`, `puffy eyes from crying` | 哭过后 |
| 黑眼圈 | `dark circles under eyes`, `bags under eyes` | 疲惫/失眠 |
| 眼睛布满血丝 | `bloodshot eyes` | 愤怒/疲惫/疯狂 |
| 瞳孔收缩 | `constricted pupils`, `small pupils` | 强光/惊讶/恐惧 |
| 瞳孔放大 | `dilated pupils`, `large pupils` | 黑暗/兴奋/恋爱 |
| 异色瞳 | `heterochromia`, `different colored eyes` | 角色特征 |
| 眼睛发光 | `glowing eyes` | 超能力/黑暗 |
| 眼下阴影 | `shadows under eyes` | 疲惫/阴险 |
| 眼角抽搐 | `twitching eye`, `eye twitch` | 愤怒/忍耐极限 |
| 眉毛上挑 | `raised eyebrows` | 惊讶/疑问 |
| 眉毛下垂 | `lowered eyebrows`, `furrowed brows` | 悲伤/愤怒/思考 |
| 皱眉 | `furrowed brow`, `frowning` | 不满/思考/痛苦 |
| 八字眉 | `sad eyebrows`, `upturned eyebrows` | 悲伤/委屈 |
| 倒八字眉 | `angry eyebrows`, `slanted eyebrows` | 愤怒/决心 |
| 单眉上挑 | `one eyebrow raised` | 怀疑/好奇/嘲讽 |
| 眉毛抖动 | `twitching eyebrows` | 忍耐/困惑 |
| 眉毛紧锁 | `brows knitted together`, `brow compression` | 深度思考/痛苦 |
| 眉心皱纹 | `wrinkles between eyebrows`, `forehead wrinkles` | 老化/思考 |
| 抬眉 | `eyebrows raised` | 惊讶 |
| 降眉 | `eyebrows lowered` | 愤怒/专注 |

### 14. 眉毛动作分类（进阶） / Eyebrow Expressions

眉毛是表情最核心的元素之一，与嘴部和眼部配合产生复杂情绪。

| 组合 | 提示词组合 | 效果 |
|------|-----------|------|
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
| 挠脚心 | `foot tickled + laughing + kicking + embarrassed + blush` | 挠脚心 |
| 怕痒反应 | `ticklish + laughing + covering body + squirming + cute` | 怕痒 |
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

### 模板1：基础动漫角色表情差分（通用）

**来源**: 知乎专栏 + CSDN + 日文社区综合

**正向提示词 (Positive Prompt)**:
```
1girl, solo, [expression_keyword], beautiful detailed eyes, detailed face,
[silver long hair:1.2], [blue eyes:1.1],
white shirt, school uniform,
portrait, upper body, from front,
soft lighting, simple background, white background,
masterpiece, best quality, official art, 8k, ultra detailed,
looking at viewer, facing viewer
```

将 `[expression_keyword]` 替换为具体表情词，如 `smile`、`angry`、`crying`、`blushing` 等。

**负面提示词 (Negative Prompt)**:
```
(worst quality:2), (low quality:2), (normal quality:2), lowres, blurry,
bad anatomy, bad hands, extra fingers, missing fingers, extra limbs, malformed limbs,
mutation, deformed, ugly, disfigured, poorly drawn face, poorly drawn hands,
watermark, signature, username, text, error, jpeg artifacts, cropped,
EasyNegative, badhandv4, ng_deepnegative_v1_75t
```

---

### 模板2：Midjourney / Niji 表情差分（英文）

**来源**: Midjourney中文站 + Niji Journey v7指南

```
Character illustration, expression differentiation, tactical girl, white short hair,
middle-parted bangs hairstyle, white eyebrows, white eyelashes, white pupils,
[cold expression / happy / angry / surprised / sad / blushing],
dark green military uniform, alloy combat armor,
two-dimensional line art style, anime style, cinematic quality,
blank background, character illustration, full body
```

**提示要点**:
- 使用 **seed 值重用** 保持角色一致性
- 通过明确描述特征属性（如"红色校队夹克，左脸上的创可贴"）提高角色一致性
- 适用于分镜制作和表情差分生成

---

### 模板3：AI视频/动态表情变化提示词（Seedance 1.0 风格）

**来源**: 字节 Seedance 提示词指南

```
[运镜], 人物初始[初始表情], [初始动作];
下一秒[眼部变化], [嘴部变化], [眉部变化], [面部线条变化];
[最终表情], [环境配合]
运镜: [镜头变化]
```

**示例 - 从平淡到开心满怀**:
```
特写，人物初始嘴角下垂，不想抬眼，眼皮抖动；
下一秒眼睛逐渐睁大，瞳孔重新聚焦，眼角泛起微光；
嘴角微微上扬，面部线条从松弛变得紧致，光线从暗部逐渐照亮瞳孔
运镜:从模糊到清晰的对焦变化，配合缓慢推进的镜头
```

**公式组件库**:
```
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

### 模板4：少女漫画/恋爱向表情集（Shoujo Romance）

**来源**: TopFreePrompts / Sora Anime Prompts

```
Anime girl with blushing cheeks, hands clasped nervously,
cherry blossom petals falling around her,
shoujo anime soft lighting, sparkle effects near face,
romantic confession moment, pastel color palette
```

其他变体:
- **Dramatic Hair Flip**: `"Anime female character's hair flowing in slow motion, sparkles and light rays, glamorous moment, shoujo anime beauty shot"`
- **Longing Gaze**: `"Anime character looking up wistfully, hand near heart, soft focus background, shoujo emotional expression, delicate features, romantic yearning"`
- **Emotional Crying**: `"Anime character with large tears streaming down face, dramatic emotional moment, rain or symbolic water background, shoujo anime emotional climax"`

---

### 模板5：日系VTuber/游戏立绘表情差分（5-6种基础）

**来源**: VTuber术语指南 + 日本PIXTA素材库

基础5-6种表情差分即可覆盖喜怒哀楽:
1. `neutral` / 无表情（默认）
2. `smile` / 笑顔
3. `angry` / 怒り顔
4. `sad` / 悲しみ顔
5. `surprised` / 驚き顔
6. `blushing` / 照れ顔

完整提示词（以Live2D/VTuber模型为例）:
```
1girl, solo, [expression], looking at viewer,
long hair, blue eyes, school uniform,
upper body, simple white background,
character sheet, multiple expressions, expression sheet,
masterpiece, best quality, official art
```

---

### 模板6：复杂情绪组合（进阶）

**来源**: 知乎 + CSDN + 日文社区综合

```
1girl, [基础表情], [叠加表情1], [叠加表情2],
[眉部动作], [眼部动作], [嘴部动作], [附加动作],
detailed face, beautiful detailed eyes,
masterpiece, best quality
```

**示例组合**:
- 傲娇: `tsundere expression, looking away, blushing, furrowed brows, pouting, arms crossed`
- 病娇: `yandere face, crazy eyes, dark smile, blush, shadow over face, head tilt`
- 害羞告白: `shy, blushing, looking down, hands clasped, teary-eyed, hopeful smile`
- 被摸头反应: `head pat, looking down, blushing, happy, hair ruffled, gentle smile`
- 被推倒: `surprised, blush, lying down, arms up, disheveled, flustered`
- 壁咚反应: `against wall, flustered, blush, looking up, heart pounding, nervous`

---

## 三、负面提示词（Negative Prompt）

### 通用负面提示词（适用于动漫风格）

**来源**: 微信公众号 "鸣姐" + CSDN + 多个中文社区

**简化版**:
```
EasyNegative, badhandv4, ng_deepnegative_v1_75t,
(worst quality:2), (low quality:2), lowres
```

**详细版（图中有人物）**:
```
EasyNegative, badhandv4, ng_deepnegative_v1_75t,
(worst quality:2), (low quality:2), lowres, bad anatomy, DeepNegative,
skin spots, acnes, skin blemishes, facing away, lowres, bad anatomy,
bad hands, missing fingers, extra digit, fewer digits, bad feet,
poorly drawn hands, poorly drawn face, mutation, deformed,
extra fingers, extra limbs, extra arms, extra legs, malformed limbs,
fused fingers, too many fingers, signature, watermark, jpeg artifacts, text
```

**动漫专用负面提示词**:
```
bad anatomy, bad hands, three hands, three legs, bad arms,
missing legs, missing arms, poorly drawn face, bad face,
fused face, cloned face, worst face, extra crus, fused crus,
worst feet, three feet, fused feet, fused thigh, extra thigh,
worst thigh, missing fingers, extra fingers, ugly fingers, long fingers,
horn, realistic photo, extra eyes, huge eyes, 2girl, 2boy, amputation,
disconnected limbs, cartoon, cg, 3d, unreal, animate, cgi, render,
artwork, illustration, 3d render, cinema 4d, artstation, octane render,
mutated body parts, painting, oil painting, 2d, sketch, bad photography,
bad photo, deviant art, aberrations, abstract, black and white, collapsed,
conjoined, creative, extra windows, harsh lighting, jpeg artifacts,
low saturation, monochrome, multiple levels, overexposed, oversaturated,
photoshop, rotten, surreal, twisted, UI, underexposed, unnatural,
unreal engine, unrealistic, video game, deformed body features
```

**面部专用负面提示词**:
```
poorly drawn face, bad face, fused face, ugly face, worst face,
asymmetrical, unrealistic skin texture, bad proportions, out of frame,
poorly drawn hands, cloned face, double face
```

**手部专用负面提示词**:
```
extra digits, extra arms, extra hands, fused fingers, malformed limbs,
mutated hands, poorly drawn hands, extra fingers, missing hands,
bad hands, three hands, fused hands, too many fingers, missing fingers,
deformed hands
```

**眼睛专用负面提示词**:
```
extra eyes, huge eyes, bad eyes, ugly eyes, oversized eyes,
imperfect eyes, deformed pupils, deformed iris, cross-eyed
```

### 负面提示词使用建议

**来源**: 微信公众号 "鸣姐拥抱AI" 实测500张图后的总结

1. **负面提示词作用维度**：画质 + 人物细节（面部和肢体）
2. **现代新模型**（如Flux系列、Qwen-image）中负面提示词作用有限，模型对正面提示词理解已很准确
3. **旧模型**（SD 1.5等）中负面提示词效果显著
4. **古风图** 即使使用新模型，负面提示词仍然有效（模型训练数据较少）
5. **权重调节**：对特定元素可加权重，如 `(badhandv4:1.2)`、`(extra fingers:1.5)`

---

## 四、制作表情差分的方法与技巧

### 方法一：ADetailer（After Detailer）插件 — 最推荐

**来源**: AI图库吧 (aituku.cc) + AI奇点网 (aieva.cn) + 智汇AI (gameba.cc)

**原理**：ADetailer 是 SD 最强修脸插件，使用人脸检测模型自动识别面部区域，然后仅对面部进行局部重绘，实现只改变表情而不影响图片其他部分。

**操作步骤**:

1. **安装插件**：在 SD WebUI 扩展中安装 ADetailer（或下载秋叶整合包已内置）
2. **上传图片**：将目标图片传到图生图（img2img）区域
3. **设置基础提示词**：保持原图的正向提示词不变
4. **打开 ADetailer**：启用插件，选择人脸检测模型
   - 真人/写实模型: `face_yolov8n.pt`
   - 动漫模型: `face_yolov8n_v2.pt` 或 anime 专用模型
5. **输入表情提示词**：在 ADetailer 的提示词框中输入表情词，使用权重增强
   - 格式：`(angry:1.5)` 代表愤怒
   - 权重范围：1.0 ~ 2.0，权重越大情绪越重
   - 示例：`(smile:1.3)`、`(crying:1.5)`、`(blushing:1.4)`
6. **生成**：点击生成，图片人物表情会改变，其他部分基本保持不变

**参数建议**:
- 模型选择：根据角色类型（真人/动漫）选择对应检测模型
- 重绘幅度：保持较低（0.3-0.5）以保留原图风格
- 权重调节：从1.2开始逐步调整

**优点**：
- 不用手动涂抹蒙版，全自动
- 表情变化精确，其他部分不变
- 可以批量生成多种表情

**示例效果**（来源: AI图库吧）:
- 原图：smirk（得意笑）→ 改为 `angry:1.5`（愤怒）
- 原图：smirk → 改为 `smile:1.5`（微笑）→ 再增大权重到 `smile:2.0`

---

### 方法二：图生图局部重绘（Inpainting）

**来源**: 百度贴吧 stablediffusion 吧 + 知乎

**操作步骤**:

1. **上传原图**到图生图（img2img）区域
2. **使用画笔**涂抹需要修改的部分（脸部区域）
3. **修改提示词**：将原表情词替换为目标表情词
   - 例如：原 `smile` → 改为 `angry` 或 `crying`
4. **调整参数**：
   - 重绘幅度（Denoising strength）：0.3-0.5（太低不变，太高会重画整张脸）
   - 蒙版模糊（Mask blur）：4-12（使边缘过渡自然）
   - 仅蒙版模式（Inpaint masked）：只重绘画笔涂抹区域
5. **ControlNet 辅助**（可选）：
   - 使用 `canny` 模型保持轮廓
   - 使用 `depth` 模型保持深度结构
   - 使用 `openpose` 保持面部关键点
6. **生成**并调整

**进阶技巧**:
- **Photoshop 辅助**：先 PS 抠出角色到白背景，局部重绘后再合成回原图
- **分层处理**：脸部差分、肢体差分分别处理，最后合成
- **种子值固定**：固定 Seed 值，只改变表情词，其他参数不变

**参数建议**（来自贴吧实战）:
- 重绘幅度：0.4-0.6（表情变化适中）
- 如果太低（<0.3）表情不变；太高（>0.7）会重画整个区域
- 建议配合 ControlNet 的 `inpaint` 模型使用，保持边缘自然

---

### 方法三：ControlNet 精确控制

**来源**: 微信公众号 "生津柠檬茶" + 哔哩哔哩 ComfyUI 教程

**ControlNet 模型选择**:

| 控制目标 | 模型 | 适用场景 |
|---------|------|---------|
| 保持轮廓 | `canny` | 边缘检测，保持面部轮廓不变 |
| 保持深度 | `depth` / `depth_anything` | 保持面部立体感 |
| 保持姿势 | `openpose` / `openpose_face` | 保持面部关键点 |
| 局部重绘 | `inpaint` | 仅重绘蒙版区域，边缘融合 |
| 保持线条 | `lineart` | 动漫风格线稿保持 |
| 保持语义 | `segmentation` | 保持面部各区域结构 |

**操作步骤**:

1. **上传原图**到 ControlNet 单元
2. **选择预处理器**：如 `canny` 或 `openpose_face`
3. **选择模型**：下载对应的 `.pth` 或 `.safetensors` 模型
4. **设置控制权重**：0.8-1.0（保持控制强度）
5. **在图生图/文生图**中输入修改后的表情提示词
6. **生成**并调整

**ComfyUI 工作流要点**（来自哔哩哔哩）:
- 使用 `sai_xl_depth_256lora.safetensors` 模型
- 配合 `depth_anything_vitl14.pth` 深度检测
- 节点连接：加载图片 → 预处理器 → ControlNet → 采样器
- 可同时使用多个 ControlNet 叠加控制

**模型下载地址**:
- `sai_xl_depth_256lora.safetensors`: https://hf-mirror.com/lllyasviel/sd_control_collection/
- `depth_anything_vitl14.pth`: https://hf-mirror.com/LiheYoung/depth_anything_vitl14/

---

### 方法四：固定种子值（Seed）+ 提示词微调

**来源**: Niji Journey v7 指南 + 多个社区经验

**原理**：通过固定随机种子（Seed），只改变表情相关的提示词，其他所有参数保持不变，实现同一角色的表情差分。

**操作步骤**:

1. **生成基础图**：生成一张满意的角色图，记录其 **Seed 值**
2. **复制参数**：记录所有参数（Sampler、Steps、CFG、Size等）
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

### 方法五：Character Sheet / Expression Sheet 一次性生成

**来源**: Kalon.ai + PromptGather.io + ReShot.ai

**提示词模板**:
```
character expression sheet, 1girl, [角色详细描述],
multiple expressions, expression sheet, 6 expressions, 2x3 grid,
neutral, happy, sad, angry, surprised, blushing,
consistent face across all views, consistent hair across all views,
white background, character reference, turnaround,
masterpiece, best quality, ultra detailed
```

**布局建议**:
- 16:9 横向：适合 3-4个全身视图 + 表情行
- 2×3 网格：6个表情头像在 16:9 中
- 3:4 纵向：适合全身视图上方 + 表情细节下方
- 1:1 方形：适合 3×3 表情网格（9个表情）

**负面提示词（防止角色不一致）**:
```
different face between views, different hair between views,
merged panels, compressed figures, inconsistent colors,
(worst quality:2), (low quality:2), lowres
```

**一致性保证技巧**:
1. 角色描述尽可能详细（精确发色、瞳色、服装名、配饰）
2. 重复一致性标签：`"consistent face across all views"`、`"consistent hair across all views"`
3. 为脸、头发、身体、服装分别指定一致性标签
4. 使用负面提示词阻止不同视图间角色漂移

---

### 方法六：批量脚本/自动化生成（进阶）

**来源**: CSDN文库 + 多个社区

**使用脚本自动替换表情词并批量生成**:

1. 准备一个基础提示词模板，将表情词设为变量 `[expression]`
2. 创建表情词列表：`["smile", "angry", "sad", "crying", "surprised", "blushing"]`
3. 使用 Python 脚本或 SD 的 `Script` 功能批量替换
4. 保持其他所有参数一致，仅改变表情词

**Python 批量生成示例（Stable Diffusion API）**:
```python
expressions = ["smile", "angry", "sad", "crying", "surprised", "blushing", "embarrassed"]
base_prompt = "1girl, solo, {}, beautiful detailed eyes, detailed face, long hair, school uniform, portrait, white background, masterpiece, best quality"

for expr in expressions:
    prompt = base_prompt.format(expr)
    # 调用 SD API 生成，保持 seed 和其他参数不变
    generate_image(prompt=prompt, seed=123456, ...)
```

---

### 方法七：FLUX.1 Pro / SD3 高保真表情生成

**来源**: 阿里巴巴产品对比分析

**FLUX.1 Pro 在动漫表情差分中的优势**:
- 提示词保真度更高：风格提示词的平均 Token 召回率 4.7/5（SD3 为 3.2/5）
- 负面提示词遵守率：94%（SD3 为 68%）
- 手部/面部解剖准确度：4.5/5（SD3 为 2.9/5）
- 同一提示词多次生成一致性：89%（SD3 为 52%）
- 首次获得忠实输出的平均尝试次数：2.1次（SD3 为 7.4次）

**建议**：对于高质量表情差分，FLUX.1 Pro 比 SD3 更适合动漫风格的精确控制。

---

## 五、来源参考与资源链接

### 中文社区来源

| 序号 | 来源名称 | URL | 主要内容 |
|------|---------|-----|---------|
| 1 | AI图库吧 - ADetailer表情控制教程 | https://www.aituku.cc/info/355.html | ADetailer插件控制表情详细教程 |
| 2 | AI奇点网 - ADetailer教程 | https://www.aieva.cn/edu/750.html | 同上，ADetailer表情控制 |
| 3 | 智汇AI - ADetailer教程 | https://ai.gameba.cc/wz/3327.html | 同上，2025年更新版 |
| 4 | 百度贴吧 - Stable Diffusion吧 | https://tieba.baidu.com/p/9474364948 | 表情动作差分讨论，PS+局部重绘方法 |
| 5 | Midjourney中文站 | https://www.midjourny.cn/mj-detail/mj-detail251638_1.html | 人物立绘表情差分提示词示例 |
| 6 | 知乎 - Stable Diffusion表情提示词 | https://zhuanlan.zhihu.com/p/651648278 | 筛选出的效果好的表情提示词 |
| 7 | 知乎 - 人物表情提示词大全 | https://zhuanlan.zhihu.com/p/650573538 | 大量表情词中英文对照 |
| 8 | CSDN - 62个表情提示词 | https://blog.csdn.net/qq_20288327/article/details/129354498 | 62种表情分类整理 |
| 9 | CSDN - 表情提示词 | https://blog.csdn.net/2401_84760527/article/details/139113498 | 插件推荐和表情提示词 |
| 10 | 微信公众号 - 鸣姐拥抱AI | 原文链接 | 负面提示词详细研究（500张图测试） |
| 11 | 微信公众号 - 勇敢的小鸣鸣姐 | 原文链接 | 负面提示词通用模板 |
| 12 | 微信公众号 - 生津柠檬茶 | 原文链接 | ControlNet精确控制教程 |
| 13 | 微信公众号 - Frank李 | 原文链接 | 二次元AI绘画提示词基础 |
| 14 | 知乎想法 - 耳多 | https://www.zhihu.com/pin/1639155185720172544 | SD图生图局部重绘修改表情 |
| 15 | 哔哩哔哩 - 局部放大重绘 | https://www.bilibili.com/opus/929387200120881255 | ComfyUI差分扩散融图教程 |
| 16 | 腾讯云HAI提示词指南 | https://main.qcloudimg.com/raw/document/product/pdf/1721_106180_cn.pdf | 官方提示词参数示例 |
| 17 | 博客园/AI表情提示词实战 | https://blog.csdn.net/2600_94960044/article/details/157039616 | 表情提示词实战指南 |

### 英文社区来源

| 序号 | 来源名称 | URL | 主要内容 |
|------|---------|-----|---------|
| 1 | ReShot.ai - Expression Sheet Guide | https://www.reshot.ai/blog/character-expression-sheet | 2025年表情表终极指南，面部特征要点 |
| 2 | Kalon.ai - AI Character Sheet Prompts | https://www.kalon.ai/templates/ai-character-sheet-prompts | AI角色表提示词，一致性解决方案 |
| 3 | PromptGather.io - Character Design Sheet | https://promptgather.io/image/awymR2OvX5 | 多姿势表情设计表提示词 |
| 4 | GPT-Image.com - Expression Sheet | https://gpt-image.com/nano-banana-pro/expression-sheet | AI表情表生成器，批量生成工具 |
| 5 | Anifusion - Anime Prompt Builder | https://anifusion.ai/free-tools/anime-prompt-builder/ | 动漫提示词构建器 |
| 6 | TopFreePrompts - Sora Anime Prompts | https://www.topfreeprompts.com/sora-anime-prompts/ | 少年恋爱动漫提示词，含表情场景 |
| 7 | Write For Us Technology - SD Anime Prompts | https://www.writeforustechnology.com/stable-diffusion-anime-prompt/ | Top 20 SD动漫提示词 |
| 8 | Artvy.ai - Anime Prompts | https://www.artvy.ai/prompt/ | 多个动漫角色提示词示例 |
| 9 | PromptBase - Anime Character Designs | https://promptbase.com/prompt/anime-character-designs-6 | 角色设计提示词模板 |
| 10 | EasyDrawingGuides - Anime Expressions | https://easydrawingguides.com/how-to-draw-anime-and-manga-facial-expressions/ | 动漫表情绘画教程，基础表情结构 |
| 11 | Alibaba Product Insights - SD3 vs FLUX | https://www.alibaba.com/product-insights/ | SD3 vs FLUX.1 Pro动漫对比 |
| 12 | Alibaba - Classifier by Expression | https://www.alibaba.com/product-insights/ | 按表情分类动漫截图库 |
| 13 | EmojiCombos - Anime Blush Cry | https://emojicombos.com/anime-blush-cry | 动漫脸红哭泣表情符号组合 |
| 14 | Positive Emotion Overflow | https://emojicombos.com/positive-emotion-overflow | 动漫积极情绪表情组合 |
| 15 | Kinda Nai - SD 10 Bangs Prompt | https://kindanai.com/en/prompt-bangs-stable-diffusion/ | SD刘海发型提示词测试 |
| 16 | Kinda Nai - Facial Expression Prompts | https://kindanai.com/prompt-facial-expression/ | 62种表情提示词日文版 |

### 日文社区来源

| 序号 | 来源名称 | URL | 主要内容 |
|------|---------|-----|---------|
| 1 | JP.Aiarty - 立ち絵服装差分 | https://jp.aiarty.com/image-generator/character-sprite-stable-diffusion.htm | SD立ち絵服装差分制作，含構図/ポーズ/背景提示词 |
| 2 | UnbeReal - VTuber用語 | https://unbereal.co.jp/vtuberaudition/vtuber_terminology/ | 表情差分定义（5-6種類で喜怒哀楽カバー） |
| 3 | PIXTA - ゲーム立ち絵素材 | https://pixta.jp/tags/ゲーム立ち絵 | 游戏立绘素材，表情4種示例 |
| 4 | SDesignLabo - キャラクターイラスト | https://sdesignlabo.com/design/character-illust/ | 角色立绘素材，表情差分套装 |
| 5 | Moe Game Award - きまぐれテンプレーション2 | https://moe-gameaward.com/media/2025/01/20/19410/ | 游戏立绘+E-mote表情差分技术 |
| 6 | Honogear - Niji Journey v7 | https://www.honogear.com/zh/blog/engineering/niji-journey-v7-guide | Niji v7角色一致性与表情差分 |


---

## 六、样例图片链接

### 来自搜索结果的可访问图片

| 描述 | 来源 | 图片URL（示例/样例） |
|------|------|---------------------|
| ADetailer 愤怒表情效果示例 | AI图库吧 | https://www.aituku.cc/uploadfile/2024/1224/2af25e70cd1e693ca707286064cbed99.png |
| ADetailer 微笑表情效果示例 | AI图库吧 | https://www.aituku.cc/uploadfile/2024/1224/6923f5c4d681f294ff451e9d44fddd81.png |
| ADetailer 插件设置界面 | AI图库吧 | https://www.aituku.cc/uploadfile/2024/1224/fc4de976680e0213d9767b5622f01887.png |
| ADetailer 表情提示词设置 | AI图库吧 | https://www.aituku.cc/uploadfile/2024/1224/9871df7d8ea64718b03f6096d201dddf.png |
| 原图（得意笑） | AI图库吧 | https://www.aituku.cc/uploadfile/2024/1224/f96b075cc8dc1b30a994507d26d7cfe4.jpg |
| 动漫刘海风格测试（Anything模型） | Kinda Nai | https://kindanai.com/wp-content/uploads/2024/03/anything_bangs_pulled-back-hair_3.jpg |
| 动漫刘海风格测试（MeinaMix） | Kinda Nai | https://kindanai.com/wp-content/uploads/2024/03/meinamixpulled-back-hair_0.jpg |
| 动漫刘海风格测试（DreamShaper） | Kinda Nai | https://kindanai.com/wp-content/uploads/2024/03/ds_pulled-back-hair_0.jpg |
| 充满活力的动漫艺术（Vibrant Anime Art） | Artvy.ai | https://cdn.prod.website-files.com/632ac1a36830f75c7e5b16f0/64f200e62c32bafc5ae09237_GKy2DCeBDS-Lt-X09y_aXs4LDA9k1DWcAHOjJcOu5_E.webp |
| 和服动漫镜头（Kimono Anime Shot） | Artvy.ai | https://cdn.prod.website-files.com/632ac1a36830f75c7e5b16f0/67b7a532717062f1264e5154_qO_gmZMFpYWprwMoN_2LT6T9h5DNouK9PW7NbnL2mRs.webp |
| 电影级插画（Cinematic Illustrations） | Artvy.ai | https://cdn.prod.website-files.com/632ac1a36830f75c7e5b16f0/64f200722f26cb94b8d02c66_HHl-Io1oPeG6BOWYSBQpBb5wK2a7Z2xksHhU6ZD0jPs.webp |
| 白裙蝙蝠Tifa艺术 | Artvy.ai | https://cdn.prod.website-files.com/632ac1a36830f75c7e5b16f0/64f2012d69656fa619259473_NrsBHdXDNWDv3KRLjDeANIwZk6bSBkqWigIp1ahua0U.webp |
| 金色长发粉色珍珠 | Artvy.ai | https://cdn.prod.website-files.com/632ac1a36830f75c7e5b16f0/67b7948e42927a2e070b038b_MoetnQLNOukQlzgsiZz_loC8PBGBrIzoRRw9YSH-9WQ.webp |
| 池塘艺术（Pond Art） | Artvy.ai | https://cdn.prod.website-files.com/632ac1a36830f75c7e5b16f0/67b79b66333f6c392dfda9ec_destiqUzs8qqv-ct4xky37QAVBoHz-TMSmu_mxpsxU0.webp |
| 武士追逐（Samurai Chase） | Artvy.ai | https://cdn.prod.website-files.com/632ac1a36830f75c7e5b16f0/67b7a532717062f1264e5154_qO_gmZMFpYWprwMoN_2LT6T9h5DNouK9PW7NbnL2mRs.webp |
| 童话电影感（Cinematic Illustrations） | Artvy.ai | https://cdn.prod.website-files.com/632ac1a36830f75c7e5b16f0/64f1155076c7a7500c830c59_v833hWIt7NGvCHWiaGJgSo_W0r8wNq2aO3lcs-yExOw.webp |
| 动漫艺术示例（WhatsApp图片） | WriteForUsTechnology | https://writeforustechnology.com/wp-content/uploads/2024/09/WhatsApp-Image-2024-09-08-at-22.40.17_ddcb4e0d-1.jpg |

### 表情差分工具/生成器参考

| 工具 | 链接 | 功能 |
|------|------|------|
| AI表情表生成器 | https://gpt-image.com/nano-banana-pro/expression-sheet | 上传角色生成6/9/12表情表 |
| 动漫提示词构建器 | https://anifusion.ai/free-tools/anime-prompt-builder/ | 动漫提示词结构辅助 |
| 角色设计提示词 | https://promptbase.com/prompt/anime-character-designs-6 | 角色设计提示词模板 |
| 惊艳动漫女孩提示词 | https://promptbase.com/prompt/gorgeous-anime-girls | 3D风格动漫女性提示词 |
| 水彩动漫风景提示词 | https://promptbase.com/prompt/watercolor-anime-landscapes | 动漫背景提示词 |

---

## 七、实用速查表（Quick Reference）

### 基础6种必做表情差分

| 编号 | 表情 | 提示词 | 强度权重 |
|------|------|--------|---------|
| 1 | 无表情/默认 | `expressionless`, `neutral` | 1.0 |
| 2 | 微笑 | `smile`, `happy` | 1.2 |
| 3 | 生气 | `angry`, `frowning` | 1.3 |
| 4 | 悲伤 | `sad`, `tearful` | 1.2 |
| 5 | 惊讶 | `surprised`, `wide eyes` | 1.3 |
| 6 | 害羞/脸红 | `blushing`, `shy`, `embarrassed` | 1.2 |

### 扩展12种表情差分

| 编号 | 表情 | 提示词 | 强度权重 |
|------|------|--------|---------|
| 7 | 大笑 | `laughing`, `grin` | 1.3 |
| 8 | 哭泣 | `crying`, `sobbing` | 1.4 |
| 9 | 得意 | `smug`, `smirk` | 1.2 |
| 10 | 困惑 | `confused`, `bewildered` | 1.2 |
| 11 | 恐惧 | `scared`, `terrified` | 1.3 |
| 12 | 调皮 | `mischievous`, `tongue out` | 1.1 |
| 13 | 困倦 | `sleepy`, `yawning`, `drowsy` | 1.2 |
| 14 | 专注 | `focused`, `determined` | 1.1 |
| 15 | 傲娇 | `tsundere expression`, `looking away blushing` | 1.3 |
| 16 | 病娇 | `yandere face`, `crazy eyes`, `dark smile` | 1.4 |
| 17 | 轻蔑 | `contemptuous`, `scornful` | 1.2 |
| 18 | 温柔 | `softly smiling`, `gentle smile` | 1.2 |

### ADetailer 表情权重参考表

| 表情程度 | 权重 | 提示词示例 |
|---------|------|-----------|
| 轻微 | 1.0-1.2 | `(slight smile:1.1)` |
| 中等 | 1.2-1.5 | `(happy:1.3)`、`(angry:1.4)` |
| 强烈 | 1.5-2.0 | `(crying:1.7)`、`(furious:1.8)` |
| 极度 | 2.0+ | `(screaming:2.0)`（可能导致面部变形） |

### 表情组合公式（叠加效果）

```
[基础表情] + [眼部动作] + [嘴部动作] + [附加状态] = 复合表情

例：
- 害羞 + 偷看 + 抿嘴 + 脸红 = shy, looking to the side, pursed lips, blushing
- 愤怒 + 咬牙切齿 + 青筋 + 脸红 = angry, gritting teeth, vein popping, red face
- 悲伤 + 流泪 + 嘴角下垂 + 向上看 = sad, teary-eyed, downturned lips, looking up
- 得意 + 闭眼 + 微笑 + 手插腰 = smug, eyes closed, smile, hands on hips
- 惊讶 + 捂嘴 + 脸红 + 眼睛睁大 = surprised, hand over mouth, blushing, wide eyes
- 害羞 + 手指互戳 + 低头 + 脸红 = shy, fidgeting fingers, looking down, blushing
- 痛苦 + 紧闭双眼 + 咬牙 + 流汗 = suffering, eyes tightly shut, clenched teeth, sweating
- 害羞 + 被子蒙头 + 只露眼睛 = hiding under blanket, peeking out, blushing
- 饥饿 + 流口水 + 眼睛发光 = hungry, drooling, sparkling eyes
- 被打扰 + 炸毛 + 生气 = interrupted, hair fluffed up, angry
- 被撩 + 害羞 + 手挡脸 + 从指缝偷看 = flustered, shy, covering face, peeking through fingers
- 被夸奖 + 害羞 + 摸头 + 微笑 = praised, blushing, head pat, gentle smile
- 被吓到 + 眼泪 + 僵住 + 发抖 = terrified, teary-eyed, frozen, trembling
- 被感动 + 流泪 + 微笑 + 手捂嘴 = moved, tears streaming, smiling, hand over mouth
- 被罚站 + 委屈 + 撇嘴 + 眼泪 = punished, pouting, teary-eyed, sad
- 被壁咚 + 脸红 + 眼神躲闪 + 紧张 = pinned, blushing, looking away, nervous
- 公主抱 + 惊讶 + 脸红 + 抱紧 = carried, surprised, blushing, clinging
- 摸头杀 + 害羞 + 闭眼 + 微笑 = head pat, blushing, eyes closed, gentle smile
- 挠痒痒 + 大笑 + 扭动 + 眼泪 = tickled, laughing, squirming, tears of joy
- 被戳脸 + 惊讶 + 嘟嘴 + 可爱 = cheek poked, surprised, pouting, cute reaction
- 被捏脸 + 鼓脸颊 + 不满 + 瞪眼 = cheek pinched, puffed cheeks, annoyed, glaring
- 被撩下巴 + 害羞 + 抬头 + 嘴唇微张 = chin lifted, blushing, looking up, slightly parted lips
- 被牵手 + 害羞 + 低头 + 微笑 = hand held, blushing, looking down, shy smile
- 被拥抱 + 惊讶 + 脸红 + 闭眼享受 = hugged, surprised, blushing, eyes closed enjoying
- 被强吻 + 震惊 + 闭眼 + 脸红 = kissed, shocked, eyes closed, blushing
- 膝枕 + 幸福 + 闭眼 + 微笑 = lap pillow, happy, eyes closed, gentle smile
- 膝枕 + 害羞 + 手摸头 + 脸红 = lap pillow, shy, hand on head, blushing
- 膝枕 + 偷看 + 被发现 + 慌张 = lap pillow, peeking, caught, flustered
- 喂食 + 张嘴 + 脸红 + 看别处 = feeding, mouth open, blushing, looking away
- 梳头 + 享受 + 闭眼 + 微笑 = hair brushing, enjoying, eyes closed, gentle smile
- 梳头 + 害羞 + 头发被拨弄 + 脸红 = hair brushing, shy, hair ruffled, blushing
- 梳头 + 被弄乱 + 生气 + 撅嘴 = hair brushing, messy, angry, pouting
- 梳头 + 被夸奖发质好 + 害羞 + 得意 = hair brushing, praised, blushing, smug
- 被背后拥抱 + 惊讶 + 脸红 + 回头看 = hug from behind, surprised, blushing, looking back
- 被背后拥抱 + 害羞 + 手摸抱住的手臂 + 微笑 = hug from behind, shy, touching arms, smiling
- 被背后拥抱 + 生气 + 挣脱 + 脸红 = hug from behind, angry, struggling, blushing
- 被公主抱 + 紧张 + 抱紧脖子 + 脸红 = carried, nervous, clinging, blushing
- 被公主抱 + 害羞 + 把头埋进怀里 + 心跳 = carried, shy, hiding face, heart pounding
- 被公主抱 + 生气 + 挣扎 + 脸红 = carried, angry, struggling, blushing
- 被掀裙子 + 惊讶 + 按住裙子 + 脸红 = skirt flipped, surprised, holding skirt, blushing
- 被风吹裙子 + 惊讶 + 按住裙子 + 内裤可见 = wind blowing skirt, surprised, holding skirt, panties visible
- 跌倒 + 走光 + 用手挡 + 脸红 = tripped, fallen, embarrassed, covering, blushing
- 洗澡被撞见 + 惊讶 + 用手遮挡 + 蒸汽 + 脸红 = bath interrupted, surprised, covering, steam, blushing
- 换衣服被撞见 + 惊讶 + 用毛巾挡 + 脸红 = changing clothes interrupted, surprised, towel covering, blushing
- 睡衣刚醒 + 睡眼 + 头发乱 + 哈欠 + 睡衣 = just woke up, sleepy eyes, messy hair, yawning, pajamas
- 泳装 + 害羞 + 用手挡身体 + 脸红 = swimsuit, shy, covering body, blushing
- 体操服 + 元气 + 马尾 + 微笑 + 运动 = gym uniform, energetic, ponytail, smiling, active
- 女仆装 + 微笑 + 服务 + 行礼 + 礼貌 = maid outfit, gentle smile, serving, curtsy, polite
- 护士装 + 温柔 + 关心 + 拿病历板 + 和善眼神 = nurse outfit, gentle smile, caring, clipboard, kind eyes
- 警服 + 严肃 + 敬礼 + 决心 = police uniform, serious, salute, determined
- 军装 + 自信 + 立正 + 敬礼 = military uniform, confident, standing at attention, salute
- 和服 + 优雅 + 微笑 + 拿扇子 + 传统 = kimono, elegant, gentle smile, holding fan, traditional
- 浴衣 + 夏祭 + 快乐 + 拿烟花棒 + 微笑 = yukata, summer festival, happy, holding sparkler, smiling
- 巫女服 + 神圣 + 拿御币 + 灵气 = miko outfit, shrine maiden, serious, holding gohei, spiritual
- 修女服 + 虔诚 + 祈祷 + 微笑 + 安详 = nun outfit, praying, gentle smile, hands clasped, serene
- 婚纱 + 幸福 + 流泪 + 面纱 + 捧花 = wedding dress, happy tears, blushing, veil, holding bouquet
- 婚纱 + 害羞 + 低头 + 脸红 + 紧张 = wedding dress, shy, looking down, blushing, nervous
- 便服 + 放松 + 自然微笑 + 插口袋 = casual clothes, relaxed, natural smile, hands in pockets
- 校服 + 青春 + 微笑 + 背书包 + 走路上学 = school uniform, energetic, smile, backpack, walking to school
- 战斗服 + 决心 + 凶狠 + 武器准备 + 战斗姿势 = battle outfit, determined, fierce, weapon ready, combat stance
- 魔法少女 + 变身 + 闪光 + 决心 + 姿势 = magical girl outfit, transformation, sparkles, determined, pose
- 偶像演出 + 舞台 + 唱歌 + 麦克风 + 闪光 + 元气 = idol outfit, stage, singing, microphone, sparkling, energetic
- 哥特萝莉 + 暗微笑 + 神秘 + 拿娃娃 + 优雅 = gothic lolita, dark smile, mysterious, holding doll, elegant
- 水手服 + 学校 + 微笑 + 拿书包 + 活泼 = sailor uniform, school, smiling, holding bag, cheerful
- 运动服 + 出汗 + 决心 + 跑步 + 专注 + 马尾 = sportswear, sweating, determined, running, focused, ponytail
- 居家服 + 放松 + 蓬乱发髻 + 瞌睡微笑 + 茶杯 = loungewear, relaxed, messy bun, sleepy smile, cup of tea
- 圣诞装 + 圣诞帽 + 红裙子 + 快乐 + 礼物 + 雪 = christmas outfit, santa hat, red dress, happy, present, snow
- 万圣节 + 南瓜 + 幽灵 + 可爱 + 不给糖就捣蛋 = halloween costume, pumpkin, spooky, cute, trick or treat
- 猫耳女仆 + 猫耳 + 女仆装 + 调皮 + 猫爪姿势 + 喵 + 可爱 = cat ears + maid outfit + playful + paw pose + meow + cute
- 兔女郎 + 兔耳 + 紧身衣 + 调皮 + 姿势 + 蝴蝶结 + 可爱 + 性感 = bunny ears + leotard + playful + pose + bowtie + cute + sexy
- 恶魔角 + 恶魔角 + 暗服装 + 调皮 + 尾巴 + 三叉戟 + 调皮 = devil horns + dark outfit + mischievous + tail + pitchfork + playful
- 天使光环 + 天使光环 + 白裙子 + 温柔 + 翅膀 + 和善微笑 + 纯洁 = angel halo + white dress + gentle + wings + kind smile + pure
- 眼镜知性 + 眼镜 + 聪明 + 自信 + 拿书 + 推眼镜 + 酷 = glasses + smart + confident + holding book + adjusting glasses + cool
- 墨镜酷 + 墨镜 + 酷 + 自信 + 插口袋 + 坏笑 + 帅气 = sunglasses + cool + confident + hands in pockets + smirk + badass
- 口罩神秘 + 口罩 + 神秘 + 只露眼睛 + 看向观众 + 神秘 = face mask + mysterious + eyes only + looking at viewer + enigmatic
- 耳机元气 + 耳机 + 音乐 + 元气 + 微笑 + 点头 + 可爱 = headphones + music + energetic + smiling + head bopping + cute
- 帽子俏皮 + 帽子 + 调皮 + 扶帽檐 + 眨眼 + 活泼 + 可爱 = hat + playful + tipping hat + winking + cheerful + cute
- 围巾温暖 + 围巾 + 冬天 + 温暖微笑 + 呼出白气 + 寒冷 + 温馨 = scarf + winter + warm smile + breath visible + cold + cozy
- 手套优雅 + 手套 + 优雅 + 正式 + 温柔微笑 + 茶会 + 精致 = gloves + elegant + formal + gentle smile + tea party + refined
- 伞下忧郁 + 伞 + 雨 + 忧郁 + 低头 + 灰色 + 孤单 = umbrella + rain + melancholy + looking down + gray + alone

---

## 八、补充：日系/动漫特有表情符号速查

> 以下表情词在日系动漫AI生成中特别有效，配合适当的权重使用效果更佳。

### 经典日系动漫表情组合

```
キラキラ目 (sparkling eyes) = "sparkling eyes", "shiny eyes", "twinkling eyes"
ジト目 (dead fish eyes / unamused) = "half-closed eyes", "droopy eyes", "unamused eyes"
ハート目 (heart eyes) = "heart-shaped eyes", "heart eyes", "love eyes"
星目 (star eyes) = "star-shaped eyes", "star eyes", "sparkling star eyes"
ぐるぐる目 (dizzy eyes) = "swirl eyes", "@_@", "spiral eyes"
真っ青 (turned pale) = "turned pale", "white as sheet", "pale face", "shocked pale"
顔に影 (shadow over face) = "shadow over face", "dark aura", "face in shadow"
青筋 (vein popping) = "vein popping", "forehead vein", "temple vein", "angry vein"
魂抜け (soul leaving body) = "ghost leaving body", "soul leaving body", "spirit floating", "dead soul"
石化 (turned to stone) = "turned to stone", "frozen in shock", "petrified", "statue-like"
滝汗 (waterfall sweat) = "sweating profusely", "waterfall sweat", "anime sweat drop", "large sweat drop"
鼻血 (nosebleed) = "nosebleed", "nose bleeding", "blood from nose", "perverted nosebleed"
照れ (embarrassment blush) = "blushing hard", "intense blush", "full face blush", "burning red face"
ドヤ顔 (smug face) = "smug", "doyagao", "proud smirk", "self-satisfied smile"
ヤンデレ顔 (yandere face) = "yandere face", "crazy eyes", "dark smile", "obsessive smile"
ツンデレ (tsundere) = "tsundere expression", "looking away blushing", "denying blush", "embarrassed anger"
天然 (airhead) = "airhead expression", "spaced out", "blank stare", "empty-headed smile"
腹黒 (scheming) = "scheming smile", "hidden intent", "plotting expression", "behind-the-scenes smile"
アホ毛 (ahoge / stray hair) = "ahoge", "cowlick", "stray hair sticking up", "confused hair"
逆毛 (hair standing up from shock) = "hair standing up", "hair fluffed up", "shocked hair", "messy hair from shock"
猫口 (cat mouth :3) = ":3 mouth", "cat mouth", "w-shaped mouth", "cute mouth"
△口 (triangle mouth) = "triangle mouth", "small mouth", "tiny mouth", "inverted triangle mouth"
口が線になる (mouth becomes a line) = "straight line mouth", "flat mouth", "displeased line mouth", "pursed flat mouth"
落ち込み (depression spiral) = "depression spiral", "background lines", "gloom aura", "dark background lines"
ハイライト消滅 (eyes lose highlights) = "eyes without highlights", "dead eyes", "no light in eyes", "hollow eyes"
愛のハート (love hearts floating) = "love bubbles", "floating hearts", "heart bubbles", "love aura"
鼻の泡 (nose bubble while sleeping) = "nose bubble", "sleep bubble", "snot bubble", "sleeping snot bubble"
吹き飛ぶ (blown away by shock) = "wind blowing away", "blown away", "floating away", "shock wave effect"
```

### 日系动漫场景配合表情

```
【雷雨背景 + 愤怒】rain, dark clouds, lightning, angry expression, shadow over face, dark aura
【樱花背景 + 害羞】cherry blossoms, falling petals, blushing, looking down, shy, spring
【夕阳背景 + 悲伤】sunset, orange sky, silhouette, sad expression, looking into distance, melancholy
【雪景背景 + 孤独】snow, cold breath visible, winter coat, alone, sad smile, looking down
【星空背景 + 期待】starry sky, night, looking up, hopeful expression, sparkling eyes, hands clasped
【教室背景 + 困倦】classroom, desk, head on desk, sleepy eyes, drooling, afternoon sunlight
【海边背景 + 开心】beach, ocean, waves, summer, smiling, laughing, running, wind blowing hair
【雨天背景 + 忧郁】rain, umbrella, puddle, reflection, melancholy, looking down, walking alone
【花田背景 + 幸福】flower field, wildflowers, breeze, lying down, smiling, eyes closed, peaceful
【都市夜景 + 迷茫】city lights, neon signs, night street, lost expression, looking around, confusion
【森林背景 + 恐惧】dark forest, trees, fog, scared, trembling, clinging to someone, wide eyes
【古堡背景 + 神秘】gothic castle, candlelight, mysterious smile, shadows, looking over shoulder
【太空背景 + 敬畏】space, stars, earth below, awe-struck, mouth agape, sparkling eyes, floating
【未来都市 + 决心】cyberpunk city, neon, rain, determined expression, clenched fist, looking forward
【传统日式 + 优雅】traditional japanese room, tatami, sliding doors, elegant smile, kimono, bowing
【现代厨房 + 慌张】kitchen, cooking, smoke, flustered, panicking, sweat drop, holding pan
【图书馆 + 专注】library, bookshelves, reading glasses, focused expression, studying, serious
【体育馆 + 元气】gymnasium, sports, sweating, energetic smile, determined, running, ponytail bouncing
【音乐室 + 陶醉】music room, piano, playing instrument, eyes closed, blissful expression, immersed
【医院 + 病弱】hospital, white room, bed, pale, weak smile, coughing, hand over mouth, frail
【战场 + 战意】battlefield, smoke, weapon, battle-ready, fierce expression, shouting, determined
【废墟 + 绝望】ruins, destruction, alone, despairing, kneeling, tears, screaming, reaching out
【花园 + 治愈】garden, flowers, sunlight, gentle smile, healing aura, soft focus, peaceful
【厨房 + 贪吃】kitchen, food, eating, cheeks full, happy, sparkling eyes, chopsticks, delicious
【浴室 + 蒸汽】bathroom, steam, bath, wet hair, relaxed, blushing, covering body, steamy
【卧室 + 刚醒】bedroom, bed, morning light, messy hair, sleepy eyes, yawning, stretching, pajamas
【舞台 + 闪耀】stage, spotlight, performing, singing, confident smile, sparkling, microphone, idol pose
【暗巷 + 恐惧】dark alley, night, scared, trembling, looking back, clutching bag, running, panting
【屋顶 + 夕阳】rooftop, sunset, sitting, wind blowing, melancholy, looking at horizon, hair flowing
【学校天台 + 告白】school rooftop, after school, nervous, blushing, hands clasped, confession, heart pounding
【电车 + 偶遇】train, crowded, standing, holding strap, surprised recognition, blushing, looking away
【公园 + 约会】park, bench, sitting together, holding hands, shy smile, looking down, blushing, romantic
【水族馆 +  wonder】aquarium, fish tank, blue light, pointing, amazed, sparkling eyes, childlike wonder
【游乐园 + 兴奋】amusement park, ferris wheel, night, excited, smiling, holding cotton candy, happy
【鬼屋 + 惊吓】haunted house, scary, screaming, clinging to someone, eyes shut, terrified, trembling
【温泉 + 放松】onsen, hot spring, steam, relaxed, eyes closed, content smile, towel on head, peaceful
【新年 + 祈福】shrine, new year, kimono, praying, hands clasped, hopeful smile, fortune slip, traditional
【夏日祭 + 开心】summer festival, yukata, fireworks, holding sparkler, smiling, looking up, festival lights
【万圣节 + 调皮】halloween, pumpkin, costume, trick or treat, mischievous smile, candy bag, playful
【圣诞 + 温暖】christmas, tree, lights, santa hat, present, happy, warm smile, snowy, cozy
【情人节 + 害羞】valentine, chocolate, handmade, giving, blushing, nervous, looking away, heart beating
【白色情人节 + 惊喜】white day, return gift, surprised, happy tears, blushing, hugging gift, grateful
【生日 + 惊喜】birthday, cake, candles, surprised, hands over mouth, happy tears, friends celebrating
【毕业典礼 + 感动】graduation, cap and gown, tears of joy, hugging, smiling through tears, nostalgic
【婚礼 + 幸福】wedding, white dress, veil, happy tears, walking down aisle, smiling, bouquet, radiant
【葬礼 + 悲伤】funeral, black clothes, mourning, tears, solemn, looking down, grief, holding hands
【重逢 + 激动】reunion, running, tears of joy, hugging, smiling, emotional, years apart, finally meeting
【离别 + 不舍】farewell, train station, waving, tears, forcing smile, sad eyes, holding hand, last goodbye
【冒险出发 + 决心】setting off, backpack, looking forward, determined, sunrise, new journey, hopeful
【战斗胜利 + 疲惫微笑】victory, battle over, exhausted, relieved smile, kneeling, breathing hard, alive
【战斗失败 + 绝望】defeat, kneeling, tears, despair, looking down, reaching out, defeated, broken
【觉醒 + 力量】awakening, power surge, glowing eyes, determined, transformation, aura, fierce expression
【黑化 + 疯狂】corruption, dark aura, crazy smile, red eyes, laughing madly, power, unhinged, dangerous
【治愈 + 温柔】healing, gentle light, soft smile, caring, hand reaching out, warm aura, comforting
【牺牲 + 微笑】sacrifice, bleeding, weak smile, looking at loved one, peaceful, final moment, acceptance
【复活 + 惊喜】revival, opening eyes, confused, then relieved, tears of joy, hugging, alive, grateful
【变身 + 帅气】transformation, magical girl, sparkles, pose, confident smile, costume change, determined
【召唤 + 敬畏】summoning, magic circle, awe, power overwhelming, looking up, shocked, majestic, grand
【契约 + 坚定】contract, handshake, determined eyes, serious expression, sealed deal, partnership, resolve
【背叛 + 震惊】betrayal, wide eyes, mouth agape, disbelief, stepping back, heart breaking, shattered
【真相 + 领悟】realization, eyes widening, gasping, hand over mouth, understanding, truth revealed, shocked
【失忆 + 困惑】amnesia, confused, touching head, looking around, lost, "who am I", blank stare, worried
【回忆 + 温柔】memory, flashback, soft focus, nostalgic smile, remembering, gentle eyes, past events
【梦境 + 虚幻】dream, surreal, floating, peaceful, dreamy eyes, soft colors, not real, ethereal, fantasy
【噩梦 + 恐惧】nightmare, terrified, screaming, sitting up in bed, sweating, panting, nightmare fading, scared
【催眠 + 空洞】hypnotized, empty eyes, spiral pupils, no will, drooling, vacant stare, under control, mindless
【洗脑 + 微笑】brainwashed, forced smile, empty eyes, obeying, not herself, creepy smile, unnatural, wrong
【醉酒 + 迷糊】drunk, dizzy, blushing, leaning, giggling, hiccup, unsteady, silly smile, intoxicated
【生病 + 虚弱】sick, fever, pale, lying in bed, weak smile, hand on forehead, thermometer, unwell, fragile
【受伤 + 忍耐】injured, bleeding, gritting teeth, pained smile, enduring, hand on wound, fighting through pain
【中毒 + 痛苦】poisoned, clutching stomach, in pain, sweating, green face, nauseous, suffering, dying
【诅咒 + 黑暗】cursed, dark mark, suffering, shadow over face, pained expression, dark aura, doomed
【祝福 + 光芒】blessed, holy light, peaceful smile, grateful, divine, healed, radiant, pure, angelic
【封印 + 挣扎】sealed, struggling, trapped, desperate, reaching out, fading, screaming, disappearing, trapped
【解放 + 狂喜】released, breaking free, laughing, wild, hair flowing, power unleashed, freedom, euphoric
【封印解除 + 威严】seal broken, regal, commanding, ancient power, serious eyes, majestic aura, legend returns
【时间停止 + 惊愕】time stopped, frozen, shocked, mid-motion, realizing, mind blown, impossible, surreal
【时间倒流 + 希望】time rewinding, hope returning, eyes widening, reaching out, second chance, miracle, grateful
【平行世界 + 迷茫】parallel world, confused, similar but different, looking around, doppelganger, unsettling
【镜子 + 自我】mirror, reflection, touching mirror, self-doubt, who am I, different reflection, other self
【水中 + 窒息】underwater, drowning, bubbles, reaching up, desperate, can't breathe, sinking, dark, cold
【高空 + 恐惧】high altitude, falling, wind rushing, terrified, screaming, flailing, skydiving, freefall
【地底 + 幽闭】underground, cave, claustrophobic, scared, darkness, holding torch, narrow passage, trapped
【太空 + 孤独】space, floating, earth below, astronaut, helmet, alone, existential, beautiful but lonely, vast
```

---

> **文档版本**: 1.0
> **收集日期**: 2025年
> **收集范围**: 中文/英文/日文社区
> **主要工具覆盖**: Stable Diffusion (AUTOMATIC1111 / ComfyUI / Forge), Midjourney, Niji Journey, FLUX.1 Pro, NovelAI
> **核心聚焦**: 动漫/二次元女性角色表情变化（Expression Sheet / 表情差分 / 表情集）

