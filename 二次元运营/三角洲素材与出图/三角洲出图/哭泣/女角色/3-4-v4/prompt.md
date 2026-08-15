# 3-4-v4：无落泪版悲愤表情

## 用途

在 `3-4-v3` 成图基础上做精确局部编辑。保留 V3 已建立的成年角色脸型、人物身份、构图与强烈悲愤感，只去掉正在流下的泪水，让表情与当前画面语境更协调。

## 通用编辑 Prompt

```text
Use case: precise-object-edit
Asset type: 3:4 vertical female character portrait for an existing game-character image set

Input image:
- Image 1 is the edit target and authoritative source for identity, face, expression, pose, costume, equipment, composition, lighting, colors, and painterly rendering style.

Primary request:
Remove only the visible flowing-tear action from the character. Erase every tear stream, tear trail, running droplet, hanging droplet, and tear bead on the cheeks, chin, eyelashes, mask, or clothing. Reconstruct the underlying skin, makeup, fabric, and equipment naturally.

Expression to preserve:
Keep the same intense grief-and-indignation expression: tightly knitted brows, pronounced glabella tension, focused accusatory eye contact, restrained anger, hurt, injustice, defiance, tight jaw, compressed lips, and tense hands. The character must still feel deeply wounded and furious, but she is holding the emotion in rather than visibly crying.

Eye treatment:
Eyes may remain subtly moist and slightly bloodshot with restrained inner-corner redness, but there must be no pooled tears, glassy tear meniscus, overflowing tears, tear highlights, tear tracks, or droplets. The moisture must read only as natural eye wetness, not crying.

Invariants:
Change only the tears and the tiny skin/fabric areas directly beneath them. Preserve the exact adult facial structure, character identity, hairstyle, headwear, mask if present, costume, tactical gear, hands, pose, crop, camera angle, background, contrast, palette, texture, and 3:4 composition. Do not soften the mature face or return to a baby-faced/anime-doll look. Do not reduce the brow tension or emotional impact.

Avoid:
No visible tears, no tear streaks, no tear beads, no wet cheeks, no crying action, no sobbing mouth, no screaming, no rage-only expression, no smile, no face redesign, no beauty-filter skin, no giant irises, no added text, no logo, no watermark, no signature.
```

## 蝶的额外约束

```text
Preserve Butterfly's corrected mature adult face from V3: elongated adult oval face, defined cheekbones and jaw, structured nose, narrower almond-shaped eyes, and smaller eye-to-iris ratio. Do not restore the round baby face or shoujo-doll proportions.
```
