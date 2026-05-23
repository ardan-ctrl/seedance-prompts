# Шаблон Character Sheet

> Перед созданием серии видео с одним персонажем — сначала создай его Character Sheet.
> Это закрепляет внешность и даёт референс для всех последующих сцен.

---

## Промпт для Character Sheet (3D анимация)

```
Character sheet — [Стиль: например, cinematic stylized 3D animation / low-poly chibi / anime cel-shaded].
Character name: [Имя]. 

Full-body orthographic views on clean white background:
- Front view: standing in A-pose
- Side view (left profile): standing in A-pose
- Back view: standing in A-pose

Expression sheet (close-up bust shots, same white background):
- Neutral / resting expression
- Happy / joyful
- Angry / determined
- Shocked / surprised
- Sad / hurt
- Laughing / playful

Prop close-ups:
- [Фирменный предмет 1 — например, its signature weapon]
- [Фирменный предмет 2 — например, its watch/accessory]

Character details:
- Hair: [цвет, длина, стиль — точно]
- Eyes: [цвет, форма]
- Skin: [тон]
- Outfit: [детальное описание каждого элемента одежды с цветами]
- Distinctive features: [особенные черты]
- Body proportions: [рост, телосложение]

Studio lighting, consistent proportions across all views.
Total reference sheet for animation use.
```

---

## Промпт для Character Sheet (аниме 2D)

```
Character design sheet — anime 2D cel-shaded style.
Character: [Имя и краткое описание].

Sheet layout:
- Large center: full-body standing pose in neutral outfit
- Top row: 4 face close-ups showing different expressions (happy, serious, surprised, angry)
- Left side: alternate outfit / battle outfit / casual outfit
- Right side: key accessories and props close-up
- Bottom: full-body in action pose

Character specs:
- Hair: [цвет и стиль точно]
- Eyes: [цвет и форма]
- Primary outfit: [описание]
- Key accessories: [список]

Consistent proportions, clean line art, flat cel-shading, white background.
```

---

## Промпт для Chibi Character Sheet

```
Chibi character sheet — [стиль: cute chibi / low-poly chibi].
Character: [Имя].

Oversized head proportions (head = 1/2 body height).
Stubby limbs, rounded features, large expressive eyes.

Views:
- Front facing: arms at sides, neutral expression
- Side profile
- Dynamic action pose (character's signature move/hobby)

Expressions (exaggerated chibi style):
- Happy (squinted happy eyes)
- Angry (puffed cheeks, steam lines)
- Crying (rivers of tears)
- Shocked (huge eyes, dropped jaw)
- Smug (single closed eye, satisfied smile)

Character details: [hair, eyes, outfit — как всегда точно]
Pastel/vibrant color palette. White background. Consistent proportions.
```

---

## Использование Character Sheet в промптах

После создания Character Sheet:

```
@Image1 is the definitive character reference sheet for [Имя].
Extract character appearance from the front-view and expression sheet.

Maintain exactly:
- [Hair color and style]
- [Eye color and shape]
- [Outfit: list each piece]
- [Body proportions]
- [Distinctive features]

Do NOT alter: face structure, hair color/style, outfit colors, body type.

Scene: [описание новой сцены]
[Камера, стиль, атмосфера]
```

---

## Консистентность в серии (5+ видео)

```
VIDEO SERIES — [Название серии]
Character: [Имя] — appearance defined in @Image1 (character sheet)

RULE: All videos must use @Image1 as character reference.
RULE: Do not alter character appearance between episodes.
RULE: Character enters each scene wearing: [описание стандартного outfit]

Episode [N]: [краткое описание сцены]
```
