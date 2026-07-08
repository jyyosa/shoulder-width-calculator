# 动漫女性角色表情差分生成提示词资源汇总

> 收集来源：Japanese Sources（日本及中文AI绘画社区）  
> 收集工具：kimi_search_v2 + kimi_fetch_v2  
> 适用范围：Stable Diffusion / NovelAI / ComfyUI / Forge 等文生图/图生图工具

---

## 目录

1. [来源列表与URL](#1-来源列表与url)
2. [基础表情关键词（中英文对照）](#2-基础表情关键词中英文对照)
3. [复杂情绪与日系特定表情](#3-复杂情绪与日系特定表情)
4. [完整提示词模板示例](#4-完整提示词模板示例)
5. [负面提示词（Negative Prompt）](#5-负面提示词negative-prompt)
6. [制作表情差分的方法与参数](#6-制作表情差分的方法与参数)
7. [专用LoRA与工具推荐](#7-专用lora与工具推荐)
8. [样例图片资源](#8-样例图片资源)

---

## 1. 来源列表与URL

| 序号 | 来源名称 | URL | 主要内容 |
|------|----------|-----|----------|
| 1 | jp.aiarty.com - 立ち絵表情差分 | https://jp.aiarty.com/image-generator/character-sprite-stable-diffusion.htm | ADetailer表情差分、ControlNet服装差分、立ち絵呪文 |
| 2 | BOOTH - 美少女立ち絵素材 | https://booth.pm/ja/items/6903136 | 商用AI素材：6种表情差分（通常/笑顔/赤面/困り/泣き/驚き）|
| 3 | weel.co.jp - SDプロンプト大全 | https://weel.co.jp/media/stable-diffusion-spell/ | 表情分类提示词（悲しみ/驚き/その他）|
| 4 | ai.joho.info - プロンプト呪文集 | https://ai.joho.info/prompt-image-genaration/ | 顔・表情・口のプロンプト一覧 |
| 5 | withballoons.jp - 表情プロンプト | https://withballoons.jp/stable-diffusion-hyojyo-prompt02/ | 感情別表情リスト（喜怒哀楽+恥+緊張）|
| 6 | qbei.isotop.jp - 表情生成完全ガイド | https://qbei.isotop.jp/archives/2878 | 2025最新感情別キーワード集 |
| 7 | runrunsketch.net - 表情呪文総まとめ | https://runrunsketch.net/expression/ | NovelAI/SD表情呪文+目/口調整 |
| 8 | hikari-aiart.com - 表情プロンプト一覧 | https://hikari-aiart.com/stable-diffusion-facial-expression-pronpt/ | 笑顔/怒り/悲しみ/照れ/不安/苦痛/恐怖/その他 |
| 9 | onlinegamernikki.com - ANIMAGINE XL 3.0 | https://onlinegamernikki.com/ai-illustration-facial-expression-prompt-comparison | 笑顔/怒り/恥/驚き/悲しみ系プロンプト辞典（画像付き）|
| 10 | 腾讯云 - ADetailer面部处理 | https://cloud.tencent.com/developer/article/2367021 | ADetailer中文教程+参数设置 |
| 11 | iPentec - ADetailer顔LoRA適用 | https://www.ipentec.com/articles/ai-image/software-stable-diffusion-apply-lora-to-face-only-using-adetailer | 顔のみにLoRA適用して表情変更 |
| 12 | 哔哩哔哩 - 表情差分制作 | https://www.bilibili.com/read/cv34326971/ | 局部重绘+ADetailer+XYZ图表制作差分 |
| 13 | 百度贴吧 - 表情差分讨论 | https://tieba.baidu.com/p/9474364948 | 国内社区讨论：局部重绘+ControlNet+ADetailer |
| 14 | tavernsprite.com - VTuber Expression Pack | https://tavernsprite.com/blog/vtuber-expression-pack-ai/ | 一键生成28种表情差分工具 |
| 15 | gongjiyun.com - 16格表情包 | https://www.gongjiyun.com/blog/2026/4/izdgwlhjtisom5kxf6xc1netnsd/ | GPT-Image-2 16格表情差分提示词 |
| 16 | CSDN - Stable Diffusion AI绘画 | https://blog.csdn.net/WANGJUNAIJIAO/article/details/143577489 | 图生图/局部重绘/ControlNet表情控制 |
| 17 | Civitai - Facial Expression Style V3 | https://civitai.com/models/541620 | 表情LoRA模型：cinematic expression等触发词 |

---

## 2. 基础表情关键词（中英文对照）

### 2.1 喜 / Joy / Happiness

| 日文 | 英文 Prompt | 中文 | 效果描述 |
|------|-------------|------|----------|
| 笑顔 | `smile` | 微笑 | 标准笑容 |
| 微笑み | `light smile` | 浅笑 | 柔和、轻微的笑 |
| 笑う | `laughing` | 大笑 | 出声笑 |
| ニヤニヤ | `smirk` | 坏笑 | 有点邪恶/得意的笑 |
| ニカッ | `grin` | 咧嘴笑 | 露齿笑、恶作剧感 |
| 幸せ | `happy` | 幸福 | 被幸福感包围的平静表情 |
| 魅惑的な笑顔 | `seductive smile` | 魅惑微笑 | 性感诱惑的笑 |
| ドヤ顔 | `smug` | 得意脸 | 自信满满、炫耀的表情 |
| 幸せそうな笑顔 | `happy, smile` | 幸福笑容 | 满面笑容 |
| 口を開けて笑う | `smile, open mouth` | 张嘴笑 | 开怀大笑 |
| 目を閉じて笑う | `smile, closed eyes` | 闭眼笑 | 幸福闭眼笑 |
| ウインクしながら笑顔 | `smile, one eye closed` | 眨眼笑 | wink+微笑 |
| 泣き笑い | `crying smile` | 哭笑不得 | 笑着流泪 |
| 悲しげな笑み | `sad smile` | 悲伤微笑 | 苦笑、忧伤的笑 |
| 指を頬に当てる | `fingersmile` | 手指触颊笑 | 可爱手指贴脸 |
| 邪悪な笑み | `evil smile` | 邪恶笑 | 反派式微笑 |
| にやり笑い | `evil grin` | 邪恶 grin | 更露齿的邪恶笑 |
| 虚偽の笑顔 | `false smile` | 假笑 | 眼睛不笑的表情 |
| 満面の笑み | `laughing` / `broad smile` | 满面笑容 | 大声笑 |
| くすっと笑う | `chuckle` | 轻笑 | 抿嘴轻笑 |
| きらめく笑顔 | `twinkle smile` | 闪亮笑容 | 眼睛发光的笑 |
| 輝く笑顔 | `beaming smile` | 灿烂笑容 | 非常明亮的笑 |
| 優しい笑顔 | `gentle smile` | 温柔微笑 | 柔和温暖的笑 |

### 2.2 怒 / Anger

| 日文 | 英文 Prompt | 中文 | 效果描述 |
|------|-------------|------|----------|
| 怒る | `angry` | 愤怒 | 标准怒脸 |
| ちょっと怒る | `a little angry` | 有点生气 | 轻微愤怒 |
| しかめっ面 | `frown` | 皱眉 | 不满、不高兴 |
| イライラ | `annoyed` | 烦躁 | 轻度恼怒 |
| 激怒 | `furious` | 狂怒 | 非常愤怒 |
| 怒りマーク | `anger vein` | 青筋/愤怒符号 | 日系动漫愤怒特效 |
| V字眉 | `v-shaped eyebrows` | V字眉毛 | 愤怒眉毛形状 |
| 歯を食いしばる | `clenched teeth` | 咬紧牙关 | 强忍愤怒 |
| 睨む | `scowl` / `glaring` | 怒视 | 瞪眼、凶狠注视 |
| 顔をしかめた | `Scowling face` | 愁眉苦脸 | 明显皱眉表情 |
| にらみつける | `Glowering look` | 怒目瞪视 | 凶狠眼神 |
| 目を細める | `Narrowed eyes` | 眯眼 | 危险/愤怒的眼神 |
| 赤くなった顔 | `Reddened face` | 涨红脸 | 愤怒到脸红 |
| 激おこぷんぷん丸 | `(furious:1.6), frontal face` | 极度愤怒 | 高权重强化 |
| 軽蔑する | `look down on with disdain` | 蔑视 | 轻蔑俯视 |
| 嫌悪 | `disgust` | 厌恶 | 讨厌的表情 |
| 拗ねる | `sulking` | 闹别扭 | 赌气、不开心 |
| 唇を突き出す | `pout` | 嘟嘴 | 不满嘟嘴 |
| しかめっ面 | `grimace` | 苦脸 | 面部扭曲 |
| 眉をひそめる | `furrowed brow` | 皱眉 | 眉毛皱起 |

### 2.3 哀 / Sadness

| 日文 | 英文 Prompt | 中文 | 效果描述 |
|------|-------------|------|----------|
| 悲しみ | `sad` | 悲伤 | 标准悲伤 |
| 泣く | `crying` / `cry` | 哭泣 | 流泪哭泣 |
| 号泣 | `sobbing` | 抽泣/嚎哭 | 剧烈哭泣 |
| 涙 | `tears` / `tearful` | 眼泪 | 有泪/泪汪汪 |
| 涙目 | `watery eyes` | 泪眼 | 含泪的眼睛 |
| すすり泣く | `sob` | 啜泣 | 小声哭泣 |
| 涙を拭く | `wiping tears` | 擦眼泪 | 用手擦泪的动作 |
| 流れる涙 | `streaming tears` | 流泪 | 泪水流下 |
| 悲しみでいっぱい | `mournful` | 哀伤 | 充满悲伤 |
| 絶望的 | `despairing` | 绝望 | 绝望表情 |
| 悲嘆 | `lamentation` | 悲叹 | 眼中失去光芒 |
| 暗い表情 | `gloomy` | 阴郁 | 灰暗表情 |
| 不幸 | `unhappy` | 不幸福 | 不快乐 |
| 心が痛む | `heartbroken` | 心碎 | 极度悲伤 |
| 憂鬱 | `gloom` / `depressed` | 抑郁/忧郁 | 低落情绪 |
| 憂愁 | `melancholy` | 忧愁 | 文艺式忧伤 |
| 泣き叫ぶ | `cry out` | 哭喊 | 哭着叫喊 |
| 残念 | `disappointed` | 失望 | 遗憾表情 |
| 悲しい笑み | `sad smile` | 苦笑 | 悲伤的微笑 |
| 寂しい | `lonely` | 寂寞 | 孤独感 |
| 鬱 | `depressed` | 抑郁 | 消沉表情 |
| 深い悲しみ | `despair` | 绝望 | 深度绝望 |
| 青ざめる | `turn pale` | 脸色苍白 | 因悲伤/恐惧而失色 |
| 泣き笑い | `crying smile` | 破涕为笑 | 又哭又笑 |

### 2.4 惊 / Surprise / Fear

| 日文 | 英文 Prompt | 中文 | 效果描述 |
|------|-------------|------|----------|
| 驚き | `surprised` | 惊讶 | 标准惊讶 |
| ショック | `shocked` | 震惊 | 受冲击表情 |
| あっけにとられる | `stunned` | 愣住 | 惊呆 |
| あぜんとした | `stunned`, `dumbfounded` | 目瞪口呆 | 非常惊讶 |
| 目を見開く | `wide-eyed` | 睁大眼睛 | 眼睛张大 |
| 瞳孔が開く | `dilated pupils` | 瞳孔放大 | 惊讶/恐惧的生理反应 |
| パニック | `panicking` | 恐慌 | 惊慌失措 |
| 恐怖 | `scared` / `horrified` | 害怕/恐惧 | 恐怖表情 |
| 怯える | `frightened` |  frightened | 胆怯害怕 |
| 動けないほど怖がる | `petrified` | 石化恐惧 | 吓到动弹不得 |
| 恐れおののく | `terrified` |  terrified | 极度恐惧 |
| 動揺して | `upset` | 慌乱 | 不安慌乱 |
| 痛い | `painful expression` | 疼痛表情 | 因痛苦扭曲 |
| 叫ぶ | `screaming` | 尖叫 | 恐惧大叫 |
| 恐怖して叫ぶ | `screaming` (恐怖系) | 惊恐尖叫 | 害怕到尖叫 |
| うろたえた | `stupefied` | 惊慌失措 | 慌乱失神 |
| 怯む | `wince` | 退缩 | 因惊讶/痛苦退缩 |
| 混乱 | `confused` | 困惑 | 迷惑不解 |
| 心配する | `worried` | 担心 | 担忧表情 |
| 不安の汗 | `sweatdrop` | 冷汗 | 日系冷汗特效 |
| 波打つ口 | `wavy mouth` | 波浪嘴 | 日系漫画式惊讶嘴型 |
| 瞳孔縮小 | `constricted pupils` | 瞳孔收缩 | 恐惧/紧张 |
| ぞっとした | `freeze` | 冻结 | 吓到僵住 |
| おびえる | `alarmed` | 惊慌 | 不安恐惧 |

### 2.5 羞 / Blushing / Shyness

| 日文 | 英文 Prompt | 中文 | 效果描述 |
|------|-------------|------|----------|
| 赤面 | `blush` / `blushing` | 脸红 | 标准害羞脸红 |
| 照れる | `shy` | 害羞 | 腼腆表情 |
| 恥ずかしい | `embarrassed` | 尴尬/害羞 | 难为情 |
| 鼻が赤くなる | `nose blush` | 鼻子红 | 日系特有：鼻子变红 |
| 顔全体が赤くなる | `full-face blush` | 满脸通红 | 极度害羞 |
| 耳まで赤くなる | `ear blush` | 耳朵红 | 害羞到耳朵 |
| 少し赤くなる | `light blush` | 微红 | 轻微脸红 |
| 赤面の吹き出し | `spoken blush` | 脸红对话框 | 漫画式脸红特效 |
| 頬を赤く | `red cheek` | 红脸颊 | 脸颊泛红 |
| 照れ照れ | `bashful` | 羞答答 | 非常害羞 |
| 恥じらい・真っ赤 | `embarrassed, nose blush` | 极度害羞 | 组合使用 |
| ほっぺの丸 | `blush stickers` | 圆形腮红贴 | 卡通式腮红 |
| 赤面（強め） | `heavy blush` | 重度脸红 | 强烈脸红 |
| 熱い顔 | `feverish face` | 发烧脸 | 红扑扑的脸 |

### 2.6 其他常用表情

| 日文 | 英文 Prompt | 中文 | 效果描述 |
|------|-------------|------|----------|
| 無表情 | `expressionless` | 无表情 | 面无表情 |
| 真剣 | `serious` / `serious face` | 认真 | 严肃表情 |
| 眠い | `sleepy` / `sleepy face` | 困倦 |  sleepy |
| ウインク | `wink` / `one eye closed` | 眨眼 | 单眼 wink |
| 酔っ払い | `drunk` | 醉酒 | 喝醉表情 |
| 困惑 | `confused` | 困惑 | 迷惑 |
| 心配 | `worried` | 担心 | 担忧 |
| 緊張 | `nervous` | 紧张 | 紧张不安 |
| パニック | `panicking` |  panic | 恐慌 |
| スマスマ | `smug` |  smug | 得意/自满 |
| 栗のような口 | `chestnut mouth` | 栗子嘴 | 日系特色嘴型 |
| 小さな口 | `no mouth` / `dot mouth` | 无嘴/点嘴 | 极简嘴型 |
| 澄ましてる | `clear face` | 清爽表情 | 干净表情 |
| 退屈 | `bored` | 无聊 | 厌倦 |
| ほっとした | `relieved` | 释然 | 松了口气 |
| 集中 | `focused` | 专注 | 集中注意力 |
| 困り顔 | `looking away, half open mouth` | 困扰脸 | 为难表情 |
| 誘惑的な | `seductive face` / `naughty face` | 诱惑脸 |  seductive |
| 恍惚 | `afterglow` / `blank eyes` | 恍惚/放空 | 失神表情 |
| 暗い笑顔 | `creepy smile` |  creepy smile | 令人不安的笑 |
| 暗い | `Creep sinister` |  sinister | 阴森 |
| 哀願 | `Pleading` | 恳求 | 哀求的眼神 |
| 驚愕 | `flabbergasted` | 惊愕 | 极度震惊 |
| 怯える | `wince` | 退缩 | 畏缩 |
| ゆがめる | `grimace` | 面部扭曲 | 痛苦/厌恶 |
| 悔しい | `regrettable` | 不甘心 | 懊悔 |
| 放心状態 | `bereaved countenance` | 失神 | 茫然 |
| 震える | `tremble face` | 颤抖 | 发抖 |
| 睨んでいる | `glaring` | 怒视 | 凶狠注视 |
| 目を細める | `squinting` | 眯眼 |  squint |
| 酔っ払い | `drunk` | 醉态 | 醉酒 |

---

## 3. 复杂情绪与日系特定表情

### 3.1 日系动漫特有表情（Japanese Anime-Specific Expressions）

日系动漫中有许多独特表情，这些在AI绘画中可以通过特定组合提示词实现：

| 日系表情名 | 推荐提示词组合 | 说明 |
|-----------|---------------|------|
| **青ざめ** (脸色发青) | `turn pale`, `shocked`, `wide-eyed` | 惊恐/震惊到面无血色 |
| **涙目** (泪目) | `watery eyes`, `tearful`, `sad` | 眼含泪水的可怜表情 |
| **ドヤ顔** (得意脸) | `smug`, `closed eyes`, `grin` | 自信满满、炫耀的表情 |
| **エヘヘ** (嘿嘿傻笑) | `shy`, `blush`, `light smile` | 害羞傻笑 |
| **怒りマーク** (愤怒符号) | `anger vein`, `angry`, `furious` | 日系漫画青筋特效 |
| **不安の汗** (不安冷汗) | `sweatdrop`, `nervous`, `worried` | 日系冷汗标记 |
| **波打つ口** (波浪嘴) | `wavy mouth`, `surprised` | 惊讶/尴尬时的波浪形嘴 |
| **ほっぺの丸** (圆形腮红) | `blush stickers`, `cute` | 卡通式腮红圆点 |
| **キラキラ目** (闪亮眼睛) | `sparkling eyes`, `eyes sparkling`, `happy` | 眼睛闪闪发光 |
| **ハート目** (爱心眼) | `heart-shaped pupils`, `blushing`, `in love` | 恋爱/花痴表情 |
| **ジト目** (半睁眼/死鱼眼) | `half-closed eyes`, `unamused`, `bored` | 无语/鄙视的眼神 |
| **えへへ…** | `embarrassed`, `nose blush`, `light smile` | 日系特有羞涩表情 |
| **ぷんすか** (气鼓鼓) | `pout`, `angry`, `puffed cheeks` | 生气鼓脸 |
| **もーっ…** (真是的…) | `looking away, half open mouth`, `annoyed` | 困扰/无奈 |
| **びっくり** (吓一跳) | `surprised`, `wide-eyed`, `open mouth` | 标准惊讶 |
| **がっかり** (失望) | `disappointed`, `sad`, `downturned mouth` | 失望低落 |
| **うるうる** (泪眼汪汪) | `watery eyes`, `shiny eyes`, `trembling lips` | 含泪欲泣 |
| **ムスッ** (不满) | `frown`, `unamused`, `furrowed brow` | 不高兴 |
| **ニヒル** (nihil/邪笑) | `evil smile`, `smirk`, `narrowed eyes` | 反派式冷笑 |
| **困り顔** (为难脸) | `troubled face`, `worried`, `sweatdrop` | 困扰为难 |
| **照れ隠し** (掩饰害羞) | `embarrassed`, `looking away`, `tsundere` | 傲娇式害羞 |
| **イキ顔** (绝顶表情) | `ahegao`, `cross-eyed`, `open mouth`, `blush` | R18系表情（注意使用）|
| **トロ顔** (恍惚脸) | `afterglow`, `blank eyes`, `half open eyes` | 失神/恍惚 |
| **パニック顔** ( panic face) | `panicking`, `sweatdrop`, `wide-eyed`, `wavy mouth` | 极度惊慌 |

### 3.2 表情强度调节（权重语法）

在Stable Diffusion中，可以用括号调节表情强度：

| 语法 | 效果 | 示例 |
|------|------|------|
| `(smile:1.2)` | 增强1.2倍 | 笑容更明显 |
| `(angry:1.5)` | 增强1.5倍 | 更愤怒 |
| `(sad:0.8)` | 减弱到0.8倍 | 轻微悲伤 |
| `((smile))` | 增强1.21倍 | 双重括号 |
| `[smile]` | 减弱到0.91倍 | 方括号弱化 |
| `{{smile}}` | 增强1.464倍 | 大括号（SDXL）|
| ` BREAK ` | 分隔提示词 | 防止表情影响其他元素 |

> 注意：使用 `Reddened face` 时，因为包含 `red` 可能被误解为红色服装/背景，建议用 `BREAK` 分隔或在负面提示词中排除 `red clothes` 等。

---

## 4. 完整提示词模板示例

### 4.1 基础角色+表情（文生图模板）

```
Positive Prompt:
masterpiece, best quality, highres, 1girl, solo, 
[角色基础描述], 
[表情关键词], 
[姿势/构图], 
[背景], 
[光影效果], 
[画风修饰]

Negative Prompt:
(worst quality:1.4), (low quality:1.4), (normal quality:1.4),
bad anatomy, bad hands, missing fingers, extra fingers, 
mutated hands, poorly drawn hands, poorly drawn face, 
mutation, deformed, blurry, bad proportions, 
extra limbs, cloned face, disfigured, gross proportions, 
malformed limbs, missing arms, missing legs, extra arms, extra legs,
fused fingers, too many fingers, long neck, 
text, watermark, signature, username, logo
```

### 4.2 具体表情示例

#### 示例 1：微笑的少女
```
masterpiece, best quality, 1girl, solo, young female, long silver hair, blue eyes, 
white school uniform, sailor collar, 
light smile, gentle expression, looking at viewer, 
upper body, from front, soft lighting, 
anime style, cel shading, pastel colors, simple background
```

#### 示例 2：生气的少女
```
masterpiece, best quality, 1girl, solo, young female, twin tails, red eyes, 
black gothic dress, 
angry, frown, glaring at viewer, pout, (clenched teeth:1.2), 
upper body, from front, dramatic lighting, 
anime style, dark atmosphere, simple background
```

#### 示例 3：哭泣的少女
```
masterpiece, best quality, 1girl, solo, young female, short black hair, purple eyes, 
casual clothes, sweater, 
crying, tears, streaming tears, (sobbing:1.1), sad, 
looking down, watery eyes, 
upper body, soft lighting, 
anime style, emotional, rainy atmosphere
```

#### 示例 4：害羞的少女
```
masterpiece, best quality, 1girl, solo, young female, long brown hair, green eyes, 
pink cardigan, white skirt, 
blush, nose blush, (embarrassed:1.2), shy, looking away, 
light smile, (full-face blush:1.1), 
upper body, from front, soft lighting, 
anime style, warm atmosphere, simple background
```

#### 示例 5：惊讶的少女
```
masterpiece, best quality, 1girl, solo, young female, blonde hair, blue eyes, 
blue dress, ribbon, 
surprised, wide-eyed, open mouth, (dilated pupils:1.1), 
shocked expression, hands on cheeks, 
upper body, from front, dynamic lighting, 
anime style, sparkles, simple background
```

### 4.3 表情差分批量生成模板（使用 XYZ 图表）

```
基础提示词（保持角色一致）：
masterpiece, best quality, 1girl, solo, [角色固定描述],
[姿势], [服装], [构图], [背景], 
anime style, cel shading

XYZ图表 - X轴（表情变化）：
- smile
- light smile
- laughing
- angry
- sad
- crying
- surprised
- blush
- embarrassed
- worried
- serious
- expressionless
```

---

## 5. 负面提示词（Negative Prompt）

### 5.1 通用负面提示词（适合动漫角色）

```
(worst quality:1.4), (low quality:1.4), (normal quality:1.4),
(lowres:1.1), (bad anatomy:1.2), (bad hands:1.2), 
(missing fingers:1.3), (extra fingers:1.3), (mutated hands:1.2),
(poorly drawn hands:1.2), (poorly drawn face:1.2), 
(mutation:1.2), (deformed:1.2), (blurry:1.2), 
(bad proportions:1.2), (extra limbs:1.2), (cloned face:1.2),
(disfigured:1.2), (gross proportions:1.2), 
(malformed limbs:1.2), (missing arms:1.2), (missing legs:1.2),
(extra arms:1.2), (extra legs:1.2), (fused fingers:1.2),
(too many fingers:1.2), (long neck:1.2), 
text, watermark, signature, username, logo, copyright,
(jpeg artifacts:1.2), (monochrome:1.1), (grayscale:1.1)
```

### 5.2 表情专用负面提示词

当需要抑制某些表情/元素时：

| 场景 | 负面提示词 |
|------|----------|
| 防止表情过于夸张 | `overexaggerated expression`, `overreacting` |
| 防止脸部崩坏 | `bad face`, `disfigured face`, `asymmetrical face` |
| 防止嘴部异常 | `bad mouth`, `weird mouth`, `wavy mouth` (需要时除外) |
| 防止眼睛异常 | `bad eyes`, `asymmetrical eyes`, `mismatched eyes` |
| 防止多余的眼泪 | `extra tears`, `unnatural tears` |
| 防止过于 blush | `heavy blush`, `excessive blush` |
| 保持无表情时 | `smile`, `angry`, `sad`, `crying`, `blush` |
| 防止恐怖谷 | `uncanny valley`, `3d render`, `realistic`, `photorealistic` |
| 日系风格专用 | `western`, `3d`, `cgi`, `realistic` (如需纯2D日系) |

### 5.3 表情差分专用负面提示词

在生成表情差分时，为了只改变表情而保持其他不变：

```
# 在基础负面提示词上增加：
(changed clothes:1.3), (different hairstyle:1.3), 
(different pose:1.3), (changed background:1.3),
(extra accessories:1.2), (different lighting:1.2)
```

---

## 6. 制作表情差分的方法与参数

### 6.1 方法 1：图生图 + 局部重绘（Inpaint）—— 最推荐

**步骤：**
1. 生成一张基础角色图（保持Seed）
2. 使用 img2img 的 Inpaint 功能
3. 用画笔涂抹面部区域（**眉毛+眼睛+嘴+脸颊都要覆盖**）
4. 修改提示词，只改变表情相关关键词
5. 保持 Seed 和大部分参数不变

**关键参数：**

| 参数 | 推荐值 | 说明 |
|------|--------|------|
| 重绘幅度 (Denoising Strength) | 0.4 - 0.7 | **0.7是最佳平衡点**；太小表情不变，太大整体变化 |
| 蒙版模糊 (Mask Blur) | 5-15 | 使重绘边缘更自然融合 |
| 蒙版模式 | Inpaint masked | 只重绘涂抹区域 |
| 蒙版内容 | Original | 基于原图内容 |
| 仅重绘蒙版区域 | 是 | 只改变蒙版内内容 |
| 步骤 (Steps) | 20-30 | 与基础图相同 |
| CFG Scale | 7-9 | 提示词遵循度 |
| 采样器 | DPM++ 2M Karras | 推荐 |

> **重要提示：** 必须把**眉毛**也覆盖进蒙版范围，否则很难画出大波动的表情！
> 将所需表情提示词放在**靠前位置**提高权重。

### 6.2 方法 2：ADetailer（After Detailer）—— 自动面部修复+表情变更

**ADetailer 是 AUTOMATIC1111 的扩展插件，可以自动检测面部并局部重绘。**

**基本设置：**

| 设置项 | 推荐值 | 说明 |
|--------|--------|------|
| 检测模型 | `anime_face_yolov8.pt` | 动漫面部检测（动漫角色） |
| 检测模型 | `face_yolov8n.pt` | 通用面部检测 |
| 检测置信度 | 0.3 | 默认；可检测更多面部 |
| 蒙版模糊 | 4-8 | 边缘融合度 |
| 去噪强度 | 0.35 - 0.65 | **0.4-0.5** 轻微增强；**0.55-0.65** 更强重绘 |
| 修复步数 | 20-28 | 与主生成一致 |
| CFG Scale | 6-7 | 与主生成一致或略低 |
| 仅修复蒙版 | True | 只修复检测到区域 |
| 蒙版预留 | 32 | 上下文像素 |

**ADetailer 表情变更方法：**

1. 在 ADetailer 的 Prompt 框中写入**仅表情相关的提示词**
2. 使用 **"Use Separate Prompt"** 功能，为面部单独指定提示词
3. 可配合 LoRA 在 ADetailer 中仅改变面部画风

**ADetailer 提示词示例（只影响面部）：**
```
# ADetailer 专用提示词：
# 例1：改成微笑
detailed face, beautiful eyes, smile, light smile, clear skin

# 例2：改成哭泣
detailed face, beautiful eyes, crying, tears, streaming tears, sad expression

# 例3：配合LoRA改变画风+表情
girl, <lora:character_lora:0.6>, smile, closed mouth
```

**ADetailer 负面提示词（仅影响面部）：**
```
# 例：去除不需要的元素
bad face, ugly, asymmetrical eyes, bad mouth, extra eyelashes
```

> 注意：如果 ADetailer 改变面部太多（不像原角色），**降低去噪强度到 0.35-0.45**。

### 6.3 方法 3：ControlNet + OpenPose —— 保持姿势一致

**ControlNet 用于保持角色姿势和身体结构不变，只改变表情。**

**推荐 ControlNet 设置：**

| ControlNet 类型 | 适用场景 | 预处理器 | 模型 |
|----------------|----------|----------|------|
| OpenPose | 保持身体姿势 | `openpose_face` | `control_v11p_sd15_openpose` |
| OpenPose (face only) | 只保持面部位置 | `openpose_faceonly` | `control_v11p_sd15_openpose` |
| Canny | 保持边缘轮廓 | `canny` | `control_v11p_sd15_canny` |
| Depth | 保持空间深度 | `depth` | `control_v11p_sd15_depth` |
| Inpaint | 局部重绘控制 | `inpaint` | `control_v11p_sd15_inpaint` |

**OpenPose 表情控制要点：**
- `openpose_face`：检测身体姿势 + 面部表情细节
- `openpose_faceonly`：仅检测面部细节（表情控制更精准）
- `openpose_full`：检测全身 + 面部 + 手部（最全面）

**使用方法：**
1. 用 OpenPose 预处理器提取原图的骨骼/面部数据
2. 在 ControlNet 中启用该数据
3. 在 img2img 中修改表情提示词
4. ControlNet 会保持身体姿势，允许面部变化

### 6.4 方法 4：XYZ 图表 + ADetailer —— 批量生成表情差分

**这是最效率的批量生成方法：**

1. 安装 **Dynamic Prompts** 扩展（或手动设置 XYZ 图表）
2. 在 txt2img 中设置基础角色提示词
3. 启用 ADetailer（设置面部检测）
4. 在 **X/Y/Z 图表** 的 X 轴中填入多个表情提示词
5. 一次性生成所有表情差分

**XYZ 图表设置示例：**

```
X 轴类型：Prompt S/R（搜索替换）
X 轴值：smile, angry, sad, crying, surprised, blush, embarrassed, worried, serious, expressionless

# 基础提示词中的占位符：
# ... [expression] ...
# 会依次替换为上述表情词
```

> 所有生成的图片会被保存在 `txt2img-images` 文件夹中，即使图表中未单独显示。

### 6.5 方法 5：PS抠图 + img2img —— 最精确控制

**步骤（来自百度贴吧经验）：**
1. 用 Photoshop 或其他工具一键抠出角色（去除背景）
2. 保存为白底/透明底图
3. 将抠好的图放入 img2img
4. 涂抹需要重绘的表情区域（蒙版）
5. 修改表情提示词，生成新表情
6. 最后合成回原始背景

> 优点：最精确，不会影响到背景和其他元素。
> 缺点：需要外部工具，流程较复杂。

---

## 7. 专用LoRA与工具推荐

### 7.1 表情专用LoRA

| LoRA 名称 | 来源 | 触发词 | 说明 |
|-----------|------|--------|------|
| **Facial Expression Style V3** | Civitai | `cinematic expression`, `happy`, `sad`, `scared`, `worried`, `smile`, `surprised`, `Pleading`, `fear`, `crying`, `angry`, `Creep sinister`, `blushing flush` | 写实+动漫混合表情风格，支持XL/SD1.5/Flux |
| **Character Expression LoRA** | 自制 | 角色名 + 表情词 | 建议训练自己的角色LoRA，包含多种表情 |

### 7.2 训练自己的表情LoRA（推荐）

如果要获得最稳定的表情差分效果，建议训练包含多种表情的角色LoRA：

1. 收集同一角色的多张表情图片（每种表情10-20张）
2. 标注时包含表情标签：`smile`, `angry`, `sad`, `crying`, `surprised`, `blush` 等
3. 训练时保持角色一致性
4. 在 ADetailer 中调用该LoRA，可实现精准表情控制

> 参考来源：iPentec - 在 ADetailer 中应用LoRA改变面部画风
> `Prompt: girl, <lora:your_lora_name:0.6>`

### 7.3 推荐的辅助工具

| 工具 | 用途 | 来源 |
|------|------|------|
| **ADetailer** | 自动面部检测+修复 | AUTOMATIC1111 Extensions |
| **ControlNet** | 姿势/表情/结构控制 | AUTOMATIC1111 Extensions |
| **Dynamic Prompts** | 动态提示词组合 | AUTOMATIC1111 Extensions |
| **OpenPose Editor** | 编辑骨骼/面部关键点 | 独立工具或插件 |
| **Eagle** | 图片管理+提示词自动记录 | 第三方软件 |
| **TavernSprite** | 一键生成28种表情差分 | https://tavernsprite.com/ |
| **Aiarty Image Enhancer** | 超分辨率放大 | 独立软件 |
| **NovelAI to Eagle** | 自动导入+标签管理 | 免费工具 |

---

## 8. 样例图片资源

### 8.1 商用AI素材示例（BOOTH）

**美少女立ち絵素材 Vol.1｜学園制服編**
- 来源：https://booth.pm/ja/items/6903136
- 内容：清楚系14岁少女，セーラー服，全身立ち絵
- 表情差分6种：通常 / 笑顔 / 赤面 / 困り / 泣き / 驚き
- 分辨率：1152×2016（透明背景PNG）
- 可商用，可改変（表情合成OK）

### 8.2 生成示例图片

以下是在搜索结果中找到的生成示例：

| 来源 | 图片/描述 | 提示词要点 |
|------|----------|----------|
| jp.aiarty.com | 立ち絵+表情差分示例 | ADetailer + ControlNet Inpaint |
| weel.co.jp | sad, surprised, serious 表情对比 | 単発プロンプト vs 組み合わせ |
| withballoons.jp | 喜怒哀楽+恥+緊張 表情对比 | 各感情別プロンプトリスト |
| onlinegamernikki.com | ANIMAGINE XL 3.0 表情辞典 | 笑顔/怒り/恥/驚き/悲しみ 图片对比 |
| hikari-aiart.com | 笑顔/怒り/悲しみ/照れ 生成例 | 各表情プロンプト生成图 |
| qbei.isotop.jp | 各表情关键词对比 | 喜/怒/哀/惊/羞 对比 |
| 共绩算力 | 16格表情包（4×4）| 紫发金瞳少女，16种表情完全不漂移 |

### 8.3 16格表情差分提示词示例（完整版）

来源：https://www.gongjiyun.com/blog/2026/4/izdgwlhjtisom5kxf6xc1netnsd/

```
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
Row 1: 01 happy smile 开心，02 sad downcast eyes with a single tear 难过，
        03 angry puffed cheeks with a sweatdrop 生气，04 surprised wide eyes + round mouth 惊讶
Row 2: 05 shy blushing looking away 害羞，06 speechless deadpan dot eyes 无语，
        07 evil grin with a glint 坏笑，08 contemplative finger on chin 沉思
Row 3: 09 curious head tilted with question mark 好奇，10 proud smug with closed eyes 得意，
        11 wronged watery eyes pouting 委屈，12 disdainful half-closed eyes looking down 不屑
Row 4: 13 confused tangled question marks 困惑，14 scared pale face 惊恐，
        15 crying anime waterfall tears 大哭，16 heart-eyes heart-shaped pupils + hearts floating 爱心

Style: modern Japanese anime illustration, clean line art with subtle shading, 
soft cel-shading, delicate pastel highlights on the hair, bright vivid color cells, 
each panel has a pale different-colored background with a thin white border 
separating the 16 cells. A small Chinese/English label in the bottom-left corner 
of each cell. Overall feeling: collectible anime emoji pack. 
No watermark, no signature, no out-of-cell decoration, perfectly aligned 4×4 grid.
```

---

## 9. 总结与最佳实践

### 9.1 表情差分制作最佳流程

```
Step 1: 生成基础角色图
  └─ 使用固定Seed + 详细角色描述

Step 2: 选择表情变更方法
  ├─ 快速自动：ADetailer（适合批量）
  ├─ 精确控制：Inpaint局部重绘（适合单张精修）
  ├─ 姿势锁定：ControlNet + Inpaint（复杂姿势）
  └─ 一键工具：TavernSprite等在线工具

Step 3: 只修改表情提示词
  └─ 保持角色描述、服装、姿势不变

Step 4: 调整参数
  └─ 重绘幅度 0.4-0.7（局部重绘）
  └─ ADetailer去噪 0.35-0.65

Step 5: 批量生成
  └─ 使用XYZ图表或Dynamic Prompts

Step 6: 筛选与后期
  └─ 用Eagle等工具管理生成图片
  └─ 必要时用Photoshop微调合成
```

### 9.2 关键要点

1. **保持Seed一致**：在图生图中保持Seed相同，确保角色一致性
2. **眉毛必须覆盖**：在局部重绘时，必须把眉毛纳入蒙版范围，否则表情变化不明显
3. **权重调节**：用 `(smile:1.2)` 等语法增强/减弱表情强度
4. **组合使用**：基础表情 + 眼部/嘴部微调 = 更丰富的表情
5. **BREAK分隔**：使用 `BREAK` 防止表情提示词影响其他元素（如服装颜色）
6. **低去噪保留身份**：ADetailer中去噪强度低于0.45可以保留原角色身份，高于0.6可能变成通用脸

### 9.3 表情推荐组合（6种基础差分）

根据 BOOTH 商用素材和 VTuber 业界标准，推荐的**基础6种表情差分**：

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

> **文档版本**：v1.0  
> **收集日期**：2025年  
> **收集工具**：kimi_search_v2 / kimi_fetch_v2  
> **适用平台**：Stable Diffusion WebUI / Forge / ComfyUI / NovelAI / AUTOMATIC1111  
> **免责声明**：本资源汇总仅供学习和研究使用，请遵守各平台使用规则和版权法规。
