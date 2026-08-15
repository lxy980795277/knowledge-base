# 哭泣｜男角色 3:4 V1 统一 Prompt（完全无哭泣痕迹的悲愤版）

## 版本定位

男角色从独立的 `3-4-v1` 开始计版，但视觉方向直接继承女角色 `3-4-v5` 的最终方案：**没有任何流泪或刚哭过的痕迹，只通过眉眼、凝视、下颌、嘴唇、头部角度和手部张力表达强烈悲愤。**

本版先覆盖 11 名男角色：红狼、威龙、无名、回响、银翼、蜂医、牧羊人、乌鲁鲁、深蓝、比特、液氮。

## 输入图片职责

- 当前角色的一张或多张原始素材：身份权威参考，用于锁定成年男性骨相、真实年龄、肤色、体型、发型、发色、胡须、伤疤、面罩、服装和标志性装备。
- 女角色 `3-4-v5` 成图：仅作为系列构图、干眼悲愤表情、半写实画风、背景和完成度参考；严禁复制女性五官、妆容、发型、体态或身份。
- 推荐固定系列参考：`../../女角色/3-4-v5/佐娅_1.png`。

## 统一 Prompt

```text
Use case: identity-preserve
Asset type: 3:4 vertical male game-character portrait for an existing image series

Current character:
【CHARACTER NAME】

Input image roles:
- The current male character source image or images are the authoritative identity references. Preserve his adult male facial structure, real age, ethnicity and skin tone, body build, hairstyle, hair color, facial hair, scars, mask or headgear, costume and signature tactical equipment.
- The approved female V5 image is a series-style reference only. Use it only for the 3:4 portrait language, emotional intensity, restrained off-white backdrop, painterly semi-realistic finish and overall polish. Do not copy the woman's face, anatomy, hairstyle, makeup, clothing or identity.

Primary request:
Create a new vertical 3:4 single-character portrait of this adult male operator. He is experiencing powerful grief and indignation, but he is suppressing it completely and does not cry. The emotional reading must combine heartbreak, betrayal, injustice, accusation and defiance rather than ordinary anger.

Required dry-eyed expression:
- sharply knitted brows and strong vertical glabella tension;
- slightly lowered brow ridge and narrowed, focused eyes;
- steady confrontational eye contact directed at the viewer;
- set jaw, controlled facial muscles and firmly compressed lips;
- restrained pain held inward, with a sense that he refuses to break;
- a tense but natural hand interaction where appropriate, such as gripping a collar, chest strap, harness, cloak edge or tactical gear.

Absolutely no crying cues:
- no tears, tear streams, tear tracks, tear beads, droplets or pooled tears;
- no watery, glassy, glossy or visibly wet eyes;
- no enlarged tear meniscus or wet lower-lid rim;
- no red, pink, irritated, bloodshot or swollen eye rims;
- no puffy eyelids, damp eyelashes, wet cheeks, flushed crying nose, smeared makeup or damp skin;
- no sobbing mouth, trembling lip, helpless puppy eyes or defeated crying posture.

Eye appearance:
Natural clear sclera, normal dry eyelid rims, crisp irises in the character's original eye color, and only restrained ordinary catchlights. No moisture emphasis and no tear-like reflections.

Male identity and age fidelity:
Preserve the character's individual male bone structure and age: forehead, brow ridge, eye depth, cheekbones, nose, jaw, chin, facial hair, wrinkles, scars and skin texture. Keep older or rugged characters visibly older and rugged; keep younger characters recognizably themselves. Do not beautify every character into the same young male idol. Do not feminize the face, enlarge the eyes or soften the jaw into a doll-like look. Do not add exaggerated bodybuilding unless it belongs to the source identity.

Mask and headgear rule:
If the source character wears a mask, visor, helmet, goggles or other identity-defining headgear, preserve it. Never remove it merely to expose more facial expression. For covered faces, communicate grief and indignation through the visible eyes, brows or forehead, head angle, shoulders and hand tension.

Composition and visual language:
Vertical 3:4 close or medium-close portrait, head and upper torso clearly visible, face as the strongest focal point. Preserve recognizable tactical clothing and signature equipment without letting gear obscure the eyes. Use a restrained warm off-white or light gray background with sparse painterly marks, strong figure separation and no narrative clutter. Keep the face slightly brighter than the dark tactical gear. High-end semi-realistic game illustration with mature male facial anatomy, nuanced skin and hair texture, controlled brushwork, coherent hands, subtle local contrast and a serious cinematic stillness.

Invariants:
Only one character. Preserve identity, adult male age, body build, hairstyle, facial hair, scars, mask or headgear, costume logic and signature equipment from the source. Keep hand anatomy natural. Maintain the dry-eyed grief-and-indignation direction and exact 3:4 portrait composition.

Avoid:
No crying cues of any kind, no red eyes, no wet eyes, no tears, no wet skin, no helpless sadness, no rage-only expression, no screaming, no smile, no face redesign, no baby face, no giant irises, no feminine makeup, no universal idol face, no plastic 3D skin, no photoreal celebrity face, no extra person, no duplicate limbs, no text, no logo, no signature and no watermark.
```

## 男角色原始素材清单

原始素材根目录：`../../../../最新素材截图/`

| 角色 | 英文名 | 可用原始素材 |
|---|---|---|
| 红狼 | Wolf | `红狼_1.jpg`、`红狼_2.png`、`红狼_3.jpg`、`红狼_4.jpg` |
| 威龙 | Dragon | `威龙_1.jpg`、`威龙_2.png`、`威龙_3.png` |
| 无名 | Nameless | `无名_1.jpg`、`无名_2.jpg` |
| 回响 | Echo | `回响_1.png` |
| 银翼 | Silverwing | `银翼_1.png` |
| 蜂医 | Beemed | `蜂医_1.jpg`、`蜂医_2.jpg`、`蜂医_3.jpg`、`蜂医_4.jpg`、`蜂医_5.jpg` |
| 牧羊人 | Shepherd | `牧羊人_1.jpg` |
| 乌鲁鲁 | Uluru | `乌鲁鲁_1.jpg`、`乌鲁鲁_2.jpg` |
| 深蓝 | Deepblue | `深蓝_1.jpg` |
| 比特 | Bit | `比特_1.png` |
| 液氮 | Nitro | `液氮_1.png` |

同一角色有多张素材时，优先选面部、发型和标志性装备最清晰的一张作为主身份参考；其余图片只补充被遮挡的身份细节，不作为构图或画风参考。

## 输出规格

- 每位角色先生成 1 张，共 11 张。
- 画幅：竖版 3:4。
- 当前系列落盘尺寸：1086 × 1448。
- 文件名：`角色名_1.png`。
- 所有成图存放在本目录，不覆盖女角色或其他主题版本。
