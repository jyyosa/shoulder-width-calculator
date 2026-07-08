# AI动漫女性角色表情差分生成提示词资源汇总

> 收集来源：Civitai、Reddit、百度贴吧、技术博客、学术论文、模型商店等  
> 收集时间：2025年  
> 研究员：提示词研究员_civitai_reddit

---

## 目录

1. [基础表情关键词（Booru Tags）](#1-基础表情关键词)
2. [复杂情绪与日系特定表情](#2-复杂情绪与日系特定表情)
3. [完整提示词模板示例](#3-完整提示词模板示例)
4. [负面提示词（Negative Prompt）](#4-负面提示词)
5. [制作表情差分的方法与技巧](#5-制作表情差分的方法与技巧)
6. [推荐工具与扩展](#6-推荐工具与扩展)
7. [样例资源与参考链接](#7-样例资源与参考链接)

---

## 1. 基础表情关键词

### 1.1 通用表情标签（中英文对照）

来源：百度贴吧 NovelAI 吧、Danbooru Wiki、Civitai 社区

| 英文标签 | 中文含义 | 备注 |
|---------|---------|------|
| `smile` | 微笑 | 最基础的表情 |
| `smirk` | 得意的笑 / 坏笑 | 略带嘲讽或自信 |
| `grin` | 露齿笑 / 咧嘴笑 | 牙齿可见 |
| `laugh` | 大笑 | 张嘴大笑 |
| `light_smile` | 浅笑 | 轻微笑意 |
| `evil_smile` | 坏笑 | 邪恶/调皮的微笑 |
| `crying` | 哭泣 | 流泪状态 |
| `tears` | 眼泪 | 有泪珠 |
| `sad` | 悲伤 | 悲伤表情 |
| `gloom` | 忧郁 / 阴郁 | 情绪低落 |
| `depressed` | 沮丧 | 消沉 |
| `wince` | 蹙额 / 皱眉 | 轻微痛苦/不适 |
| `angry` | 生气 | 愤怒 |
| `annoyed` | 恼怒 | 烦躁 |
| `nervous` | 紧张 | 不安 |
| `scared` | 害怕 | 恐惧 |
| `disgust` | 厌恶 | 嫌弃 |
| `embarrassed` | 尴尬 | 窘迫 |
| `blush` | 脸红 | 害羞/害羞红晕 |
| `frown` | 皱眉 | 不高兴 |
| `surprised` | 惊讶 | 吃惊 |
| `shocked` | 震惊 | 极度惊讶 |
| `neutral` | 无表情 / 中性 | 面无表情 |
| `happy` | 开心 | 快乐 |
| `confused` | 困惑 | 迷茫 |
| `determined` | 坚定 | 下定决心 |
| `mischievous` | 调皮 / 捣蛋 | 恶作剧表情 |
| `smug` | 得意 / 自满 | 自鸣得意 |
| `pouting` | 撅嘴 | 生气/撒娇 |
| `serious` | 严肃 | 认真 |
| `sleepy` | 困倦 | 想睡 |
| `tired` | 疲倦 | 疲惫 |
| `worried` | 担忧 | 担心 |
| `pleading` | 恳求 | 哀求眼神 |
| `fear` | 恐惧 | 害怕（比scared更强） |
| `creepy` |  creepy / 诡异 | 令人不安 |
| `sinister` | 阴险 | 邪恶 |

### 1.2 面部细节标签

| 英文标签 | 中文含义 |
|---------|---------|
| `open_mouth` | 张嘴 |
| `closed_mouth` | 闭嘴 |
| `parted_lips` | 微张嘴唇 |
| `teeth` | 牙齿可见 |
| `tongue` | 舌头 |
| `eyebrows` | 眉毛（可配合 `raised_eyebrows` 等） |
| `furrowed_brow` | 眉头紧锁 |
| `wide_eyes` | 睁大眼睛 |
| `narrowed_eyes` | 眯眼 |
| `half-closed_eyes` | 半闭眼睛 |
| `squinting` | 眯起眼睛 |
| `teary_eyes` | 含泪的眼睛 |
| `red_eyes` | 红眼睛（哭过） |
| `looking_down` | 向下看 |
| `looking_up` | 向上看 |
| `looking_away` | 看向别处 |
| `looking_at_viewer` | 看着观众 |
| `eye_contact` | 眼神接触 |
| `blushing` | 脸红（比blush更强调） |
| `nose_blush` | 鼻子红 |
| `full-face_blush` | 满脸通红 |

---

## 2. 复杂情绪与日系特定表情

### 2.1 日系动漫特有表情

来源：BOOTH 商品描述、Pixiv、Civitai 模型说明

| 日文/英文标签 | 中文含义 | 使用场景 |
|-------------|---------|---------|
| `ahegao` | 阿黑颜 | 过度表情（NSFW） |
| `dohegao` | 吐舌沉醉脸 | 极度满足 |
| `torogao` | 恍惚脸 | 迷离表情 |
| `doyagao` | 得意洋洋脸 | 炫耀/自满 |
| `jitome` | 死鱼眼 / 冷眼 | 无语/鄙视 |
| `sanpaku` | 三白眼 | 眼白较多 |
| `tareme` | 下垂眼 | 无辜/柔弱 |
| `tsurime` | 吊眼 / 上挑眼 | 强势/锐利 |
| `ikemen` | 帅哥脸 | 男性角色 |
| `kirito_face` | 桐人脸（泛指） | 冷酷 |
| `yandere_face` | 病娇脸 | 病态爱意 |
| `yangire_face` | 黑化脸 | 暴力倾向 |
| `pikari` | 眼睛闪亮 | 发现/惊喜 |
| `shock_mark` | 震惊符号 | 漫画式表现 |
| `anger_vein` | 青筋 | 愤怒标记 |
| `nosebleed` | 鼻血 | 兴奋/害羞过度 |
| `sweatdrop` | 汗滴 | 尴尬/紧张 |
| `teardrop` | 泪滴 | 悲伤/感动 |
| `heart-shaped_eyes` | 爱心眼 | 迷恋/喜爱 |
| `star-shaped_eyes` | 星星眼 | 崇拜/期待 |
| `sparkle` | 眼睛闪光 | 开心/期待 |

### 2.2 表情强度修饰词

| 标签 | 含义 |
|------|------|
| `slight_` | 轻微的（如 `slight_smile`） |
| `gentle_` | 温柔的 |
| `warm_` | 温暖的 |
| `genuine_` | 真诚的 |
| `bitter_` | 苦涩的 |
| `forced_` | 强装的 |
| `awkward_` | 尴尬的 |
| `playful_` |  playful /  playful  |
| `mischievous_` | 调皮的 |
| `manic_` | 狂气的 |
| `hysterical_` | 歇斯底里的 |
| `subtle_` | 微妙的 |
| `exaggerated_` | 夸张的 |

---

## 3. 完整提示词模板示例

### 3.1 基础表情差分模板（SD 1.5 / SDXL）

来源：Civitai 社区、Reddit r/StableDiffusion、PromptBase

**模板 A：单表情肖像**
```
masterpiece, best quality, high resolution, 1girl, solo, 
[long_hair], [blue_eyes], [school_uniform], 
portrait, looking_at_viewer, [EMOTION_TAG], 
simple_background, white_background
```

**模板 B：多表情网格（Expression Sheet）**
```
masterpiece, best quality, character_expression_sheet, 
white_background, same_character_face_shown_in_six_head_and_shoulder_portraits, 
1girl, [hair_color], [eye_color], [hairstyle], [outfit],
arranged_in_2_rows_of_3, emotions_displayed:
- top_row: neutral_calm, genuine_happy_smile, surprised_with_wide_eyes_and_open_mouth
- bottom_row: angry_with_furrowed_brows, sad_with_downcast_eyes, mischievous_smirk,
consistent_facial_structure, clean_grid_layout, flat_even_lighting, 
character_expression_reference, 16:9_horizontal, high_resolution
```

**模板 C：Midjourney 风格（自然语言）**
```
A character expression sheet of [character description], 
showing 6 different emotions: neutral, happy, angry, sad, surprised, and embarrassed,
white background, consistent character design, anime style, 
professional concept art reference, high resolution, clean linework
```

**模板 D：Flux Kontext LoRA（推荐）**
```
Generate a 3x3 expression sheet of this same character, 
keeping identical lighting and composition while varying only facial expressions: 
neutral, happy, angry, surprised, sad, confident, shouting, embarrassed, and laughing.
```
来源：https://www.scenario.com/models/facial-expression-sheet-kontext

### 3.2 表情特定强化模板

**悲伤/哭泣表情：**
```
masterpiece, best quality, 1girl, solo, [character_features], 
teary_eyes, tears_on_cheeks, sad_expression, looking_down, 
slightly_open_mouth, trembling_lips, 
soft_lighting, emotional_portrait, detailed_eyes, 
simple_background, white_background
```

**生气/愤怒表情：**
```
masterpiece, best quality, 1girl, solo, [character_features], 
angry, furrowed_brow, narrowed_eyes, frowning, 
clenched_teeth, flushed_face, anger_vein, 
sharp_lighting, intense_shadows, dramatic_angle, 
white_background, simple_background
```

**害羞/脸红表情：**
```
masterpiece, best quality, 1girl, solo, [character_features], 
blushing, full_face_blush, looking_away, embarrassed, 
shy_smile, hand_on_cheek, averting_eyes, 
soft_lighting, warm_colors, gentle_atmosphere, 
white_background, simple_background
```

**惊讶/震惊表情：**
```
masterpiece, best quality, 1girl, solo, [character_features], 
surprised, wide_eyes, open_mouth, raised_eyebrows, 
shock_mark, sweatdrop, hands_on_cheeks, 
white_background, simple_background, high_energy
```

### 3.3 Booru 风格完整提示词（SDXL Anime）

来源：nemora.ai、anifusion.ai、droid4x.com

```
masterpiece, best quality, very aesthetic, high resolution, 1girl, solo,
medium_hair, messy_hair, red_eyes, teary_eyes, sad, melancholic,
looking_down, introspective, casual, oversized_hoodie, indoors, window,
soft_lighting, dim_lighting, emotional, atmospheric, anime_style,
detailed_eyes, emotional_portrait, white_background, simple_background
```

---

## 4. 负面提示词

### 4.1 通用动漫负面提示词（标准版）

来源：Civitai 模型页面、GitHub 社区、腾讯云开发者社区

```
low quality, worst quality, bad anatomy, bad hands, missing fingers,
extra fingers, fewer fingers, fused fingers, impossible hand, bad feet,
poorly drawn face, mutation, mutated, ugly, disgusting, blurry,
amputation, watermark, text, signature, username, artist_name,
semi-realistic, cgi, 3d, render, sketch, cartoon, drawing,
close up, cropped, out of frame, worst quality, low quality,
jpeg artifacts, duplicate, morbid, mutilated, extra limbs,
cloned face, disfigured, gross proportions, malformed limbs,
missing arms, missing legs, extra arms, extra legs, long neck
```

### 4.2 人物专用负面提示词（详细版）

```
EasyNegative, badhandv4, ng_deepnegative_v1_75t,
(worst quality:2), (low quality:2), lowres, bad anatomy,
DeepNegative, skin spots, acnes, skin blemishes, facing away,
bad hands, missing fingers, extra digit, fewer digits, bad feet,
poorly drawn hands, poorly drawn face, mutation, deformed,
extra fingers, extra limbs, extra arms, extra legs, malformed limbs,
fused fingers, too many fingers, signature, watermark, jpeg artifacts, text
```

### 4.3 面部专用负面提示词

```
(semi-realistic:1.4), (cgi:1.4), (3d:1.4), (render:1.4), (sketch:1.4),
(cartoon:1.4), (drawing:1.4), (anime:1.4), text, close up, cropped,
out of frame, worst quality, low quality, jpeg artifacts, ugly, duplicate,
morbid, mutilated, extra fingers, mutated hands, poorly drawn hands,
poorly drawn face, mutation, deformed, blurry, dehydrated, bad anatomy,
bad proportions, extra limbs, cloned face, disfigured, gross proportions,
malformed limbs, missing arms, missing legs, extra arms, extra legs,
fused fingers, too many fingers, long neck
```

### 4.4 旧模型专用负面提示词（Embedding推荐）

```
EasyNegative, badhandv4, ng_deepnegative_v1_75t,
FastNegativeV2, verybadimagenegative_v1.3,
(worst quality:2), (low quality:2), lowres, bad anatomy
```

---

## 5. 制作表情差分的方法与技巧

### 5.1 方法一：img2img + Inpainting（局部重绘）

来源：Reddit r/StableDiffusion、juejin.cn、stable-diffusion-art.com

**步骤：**
1. 生成一张基础角色图（txt2img），固定 Seed
2. 发送到 img2img → Inpaint 标签
3. 用白色画笔涂抹需要改变表情的区域（面部/嘴/眼）
4. 修改提示词，仅替换表情标签（如 `smile` → `angry`）
5. 设置合适的 Denoising Strength（0.3-0.6 之间）
6. 保持 Seed 不变，生成表情变体

**关键参数：**
| 参数 | 推荐值 | 说明 |
|------|--------|------|
| Denoising Strength | 0.35 - 0.55 | 太低无变化，太高失去角色一致性 |
| Mask Blur | 4 - 8 | 边缘羽化，使过渡自然 |
| Mask Content | Original | 保留原始内容作为参考 |
| CFG Scale | 7 - 9 | 控制提示词强度 |
| Steps | 20 - 30 | 步数 |

### 5.2 方法二：ADetailer（After Detailer）

来源：aiimagegeneratornsfw.com、iPentec、腾讯云

**ADetailer 是专门用于自动检测面部并局部重绘的扩展。**

**配置步骤：**
1. 安装 ADetailer 扩展（by Bing-su）
2. 在生成参数下方启用 ADetailer 面板
3. 选择检测模型：
   - `face_yolov8n.pt` 或 `face_yolov8s.pt` — 真人/写实脸
   - `anime_face_yolov8.pt` — 动漫脸（**推荐用于动漫角色**）
   - `mediapipe_face_full` — 全面部检测
4. 在 ADetailer Prompt 中输入表情提示词
5. 设置 Denoising Strength：0.35 - 0.45（保持身份）到 0.55 - 0.65（更强修改）

**ADetailer 表情修改示例：**
```
主提示词：1girl, blue jacket, upper body, anime shading
ADetailer 提示词：girl, angry, furrowed brow, open mouth
ADetailer 负面提示词：eyelashes, smile
参数：Denoising 0.4, Mask blur 4
```

**ADetailer 关键参数表：**
| 参数 | 推荐值 | 说明 |
|------|--------|------|
| Detection Model | anime_face_yolov8.pt | 动漫脸检测 |
| Confidence | 0.3 | 检测阈值 |
| Mask Blur | 4 | 蒙版模糊 |
| Denoising Strength | 0.35 - 0.5 | 越低越保留原脸 |
| Inpaint Only Masked | True | 只修复 masked 区域 |
| Inpaint Padding | 32 | 上下文像素 |
| Steps | 20 - 28 | 局部重绘步数 |
| CFG Scale | 6 - 7 | 局部 CFG |

### 5.3 方法三：ControlNet + Inpaint

来源：CSDN、5bei.cn、stable-diffusion-art.com

**步骤：**
1. 生成基础图，记录 Seed
2. 进入 img2img → Inpaint
3. 涂抹面部区域
4. 启用 ControlNet Unit 0：
   - Control Type: Inpaint
   - Preprocessor: inpaint_only / inpaint_only+lama
   - Model: control_v11p_sd15_inpaint / controlnet-inpaint-anime-sdxl
5. 启用 ControlNet Unit 1（可选）：
   - Control Type: OpenPose / Canny / Depth
   - 上传原图获取姿势/边缘/深度图
6. 修改提示词为表情标签，保持 Seed 不变
7. 生成

**ControlNet Inpaint 优势：**
- 保持面部结构不变
- 边缘融合更自然
- 适合 anime_face_yolov8 无法精确处理的复杂角度

### 5.4 方法四：Regional Prompter + 动态提示词

来源：hako-mikan GitHub、digitalcreativeai.net

**使用 Dynamic Prompts 扩展：**
```
{smile|angry|sad|surprised|embarrassed|crying}, 1girl, [其他角色特征]
```
- 设置 Batch Size = 6，一次生成 6 种不同表情
- 结合 Regional Prompter 可将不同表情放在同一画面的不同区域

**Regional Prompter 示例：**
```
hug, 2girls, beautiful_face, standing, upper body, (masterpiece:1.3), ADDCOMM
(black_hair, short_hair, smile:1.2) ADDCOL
(red_hair, long_hair, angry:1.2)
```

### 5.5 方法五：LoRA 表情模型（专用模型）

来源：Civitai 模型页面、RunningHub

**推荐表情相关 LoRA：**

| LoRA 名称 | 触发词 | 用途 | 链接 |
|----------|--------|------|------|
| Facial Expression Style V3 | `cinematic expression` + 表情词 | 写实+动漫混合表情 | Civitai: 541620 |
| Orgasm Face | `org4smic` | 特定表情（NSFW） | Civitai Pyro's NSFW SDXL |
| AnimeFaceID | 无特殊触发 | 身份保持+表情变化 | Civitai |
| Flux Kontext Expression Sheet | 自然语言描述 | 3x3 表情网格生成 | Scenario |

**Facial Expression Style V3 触发词列表：**
```
cinematic expression, happy, sad, scared, worried, 
smile, surprised, Pleading, fear, crying, angry, 
Creep sinister, blushing flush
```

### 5.6 方法六：Seed 固定 + 提示词替换（最简单）

**流程：**
1. 生成基础图，记录 Seed、Sampler、CFG、Steps
2. 保持所有参数不变，仅替换表情标签
3. 批量生成表情变体
4. 使用 Photoshop / GIMP 合成表情差分贴图

---

## 6. 推荐工具与扩展

### 6.1 AUTOMATIC1111 / Forge 扩展

| 扩展名称 | 功能 | 安装地址 |
|---------|------|---------|
| ADetailer | 自动面部检测+修复 | `https://github.com/Bing-su/adetailer` |
| Regional Prompter | 区域化提示词控制 | `https://github.com/hako-mikan/sd-webui-regional-prompter` |
| Dynamic Prompts | 动态/随机提示词 | `https://github.com/adieyal/sd-dynamic-prompts` |
| Booru Tag Autocomplete | 标签自动补全 | `https://github.com/DominikDoom/a1111-sd-webui-tagcomplete` |
| Civitai Helper | 模型管理 | `https://github.com/zixaphir/Stable-Diffusion-Webui-Civitai-Helper` |
| Inpaint Anything | 智能分割+修复 | `https://github.com/Uminosachi/sd-webui-inpaint-anything` |

### 6.2 模型推荐

| 模型 | 类型 | 适用场景 |
|------|------|---------|
| anime_face_yolov8.pt | ADetailer 检测 | 动漫脸部检测 |
| face_yolov8n.pt | ADetailer 检测 | 通用脸部检测 |
| control_v11p_sd15_inpaint | ControlNet | SD 1.5 局部修复 |
| controlnet-inpaint-anime-sdxl | ControlNet | SDXL 动漫修复 |
| sai_xl_depth_256lora | ControlNet | SDXL 深度控制 |
| Facial Expression Style V3 | LoRA | 表情风格增强 |
| Flux Kontext Expression Sheet | LoRA | 3x3 表情网格 |

### 6.3 外部工具

| 工具 | 用途 | 链接 |
|------|------|------|
| Danbooru Tag Wiki | 标签查询 | https://danbooru.donmai.us/tags |
| WD14 Tagger | 图片反推标签 | 内置于 WebUI / ComfyUI |
| DeepDanbooru | 图片反推标签 | 内置 / GitHub |
| ExcaliburAI | Civitai 提示词提取 | Chrome 扩展商店 |
| Anifusion Prompt Builder | 提示词构建 | https://anifusion.ai/free-tools/anime-prompt-builder/ |
| GPT-Image Expression Sheet | AI 表情网格生成 | https://gpt-image.com/nano-banana-pro/expression-sheet |

---

## 7. 样例资源与参考链接

### 7.1 表情差分数据集/商品

| 来源 | 内容 | URL |
|------|------|-----|
| BOOTH | 美少女立ち絵素材 Vol.1（表情差分6種） | https://booth.pm/ja/items/6903136 |
| BOOTH | AI生成 夏の花柄ワンピ少女・表情差分パック（全4種） | https://booth.pm/ja/items/... |
| PIXTA | ゲーム立ち絵 表情差分素材 | https://pixta.jp/tags/ゲーム立ち絵 |
| Pixiv | 表情差分 イラスト検索 | https://www.pixiv.net/tags/表情差分 |

### 7.2 教程与指南

| 来源 | 标题 | URL |
|------|------|-----|
| 百度贴吧 | 【AI绘画】使用novel AI生成角色表情差分教程 | https://tieba.baidu.com/p/8091371974 |
| CLIP STUDIO TIPS | 利用图层构图——创建人物表情差分贴图 | https://tips.clip-studio.com/zh-cn/articles/10916 |
| AI Arty | Stable Diffusionで立ち絵（服装・表情差分あり）を作成する方法 | https://jp.aiarty.com/image-generator/character-sprite-stable-diffusion.htm |
| Scenario | Flux Kontext Expression Sheet LoRA | https://www.scenario.com/models/facial-expression-sheet-kontext |
| GPT-Image | Expression Sheet Generator | https://gpt-image.com/nano-banana-pro/expression-sheet |
| Reshot.ai | Character Expression Sheet Guide | https://www.reshot.ai/blog/character-expression-sheet |
| PromptGather.io | Character Design Sheet with Multiple Poses and Expressions | https://promptgather.io/image/awymR2OvX5 |
| Kalon.ai | AI Character Sheet Prompts | https://www.kalon.ai/templates/ai-character-sheet-prompts |
| Nemora.ai | Definitive Guide to AI Image Generation | https://nemora.ai/blog/the-definitive-guide-to-ai-image-generation/ |

### 7.3 学术论文/技术文档

| 来源 | 标题 | URL |
|------|------|-----|
| Semantic Scholar | Game Character Design with AI (Expression Sheet) | https://pdfs.semanticscholar.org/488f/a1c076602ef5d641bec86da99961332f19cc.pdf |
| Elsevier | Exploring Novel Image-to-Text for CivitAI | https://yonsei.elsevierpure.com/en/publications/... |

### 7.4 Civitai 资源

| 资源 | 说明 | 链接 |
|------|------|------|
| Facial Expression Style V3 | 表情风格 LoRA | https://civitai.com/models/541620 |
| WAI Illustrious | SDXL 动漫模型（支持表情一致性） | https://illustriousxl.org/wai-illustrious-sdxl |
| SDXL Anime Final | 动漫模型 | https://anifusion.ai/models/sdxl-anime-final/ |
| ExcaliburAI | 提示词提取工具 | Chrome Web Store |

### 7.5 Reddit 讨论

| 来源 | 标题 | URL |
|------|------|-----|
| r/StableDiffusion | Img2tiles / Inpainting Tips | https://www.reddit.com/r/StableDiffusion/comments/ycgfgo/ |
| r/StableDiffusion | Interpolate Script | https://www.reddit.com/r/StableDiffusion/comments/yi46px/ |
| r/comfyui | ComfyUI 工作流讨论 | https://reddit.com/r/comfyui |

---

## 8. 快速参考表

### 8.1 表情生成检查清单

- [ ] 固定 Seed（保持角色一致性）
- [ ] 固定 Sampler（如 DPM++ 2M Karras）
- [ ] 固定 CFG Scale（通常 7-9）
- [ ] 固定 Steps（通常 20-30）
- [ ] 仅替换表情相关标签
- [ ] 使用 white_background 或 simple_background
- [ ] 使用 portrait / upper_body 构图
- [ ] 添加 negative prompt 排除不想要的表情
- [ ] 使用 ADetailer 或 ControlNet Inpaint 进行精细控制

### 8.2 推荐参数组合（快速设置）

| 场景 | Sampler | Steps | CFG | Denoising | 工具 |
|------|---------|-------|-----|-----------|------|
| 基础表情生成 | DPM++ 2M Karras | 25 | 7 | - | txt2img |
| 轻度表情修改 | DPM++ 2M Karras | 20 | 7 | 0.35-0.45 | ADetailer |
| 中度表情修改 | DPM++ 2M Karras | 25 | 7 | 0.45-0.55 | Inpaint |
| 大幅表情重绘 | Euler a | 30 | 8 | 0.55-0.65 | Inpaint + ControlNet |
| 批量表情生成 | DPM++ 2M Karras | 20 | 7 | - | Dynamic Prompts + Batch |

---

## 附录：日系 VTuber 风格表情差分参考

来源：VTuber 术语说明、BOOTH 商品页面

标准的 VTuber 立绘通常包含 **5-6 种表情差分**：

1. **通常** / 无表情 (`neutral`)
2. **笑顔** / 微笑 (`smile`, `happy`)
3. **怒り** / 生气 (`angry`, `annoyed`)
4. **悲しみ** / 悲伤 (`sad`, `crying`)
5. **驚き** / 惊讶 (`surprised`, `shocked`)
6. **照れ** / 害羞 (`blush`, `embarrassed`)
7. **困惑** / 困惑 (`confused`, `worried`)
8. **ジト目** / 死鱼眼 (`jitome`, `unamused`)

---

> 本资源汇总由 AI 提示词研究员从公开网络资源收集整理，仅供学习参考。  
> 所有外部链接版权归原作者所有。
