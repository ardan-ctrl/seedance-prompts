# Техника: Мультиреференсная Система (@-теги)

> Seedance 2.0 принимает до 12 файлов (9 фото + 3 видео + 3 аудио).
> Это главное нетривиальное преимущество перед другими генераторами.

---

## Синтаксис

```
@Image1   — первое изображение
@Image2   — второе изображение
@Video1   — первое видео
@Audio1   — первый аудиофайл
```

---

## Паттерны использования

### Персонаж из фото (Image-to-Video)
```
@Image1 as the main character throughout the video.
Maintain exact appearance: [hair color], [eye color], [outfit], [distinctive features].
Do not alter face structure, hair, or color palette.
[Описание сцены и действий]
```

### Первый кадр (стартовая точка)
```
@Image1 as first keyframe. Camera begins on this exact frame.
[Продолжение действия от этой точки]
Maintain all visual details from the reference.
```

### Стиль из видео
```
@Video1 for camera movement and pacing reference. Do not copy content, only style.
Apply the same camera choreography to this new scene: [описание сцены]
```

### Движения персонажа из видео
```
@Image1 is the character (maintain appearance).
@Video1 shows the actions to replicate (apply these movements to @Image1 character).
Combine: character from @Image1, movements from @Video1, in this new setting: [сцена]
```

### Аудио как ритм монтажа
```
@Audio1 as background music. Sync camera cuts and character movements to the beat.
[Описание сцены. Шоты сменяются в ритм музыки]
```

### Расширение существующего видео
```
Extend @Video1 by [5/7/10] seconds. Maintain exact visual style, character appearance,
lighting, and atmosphere. Continue the story from where it ends: [что происходит дальше]
```

### Трансфер стиля
```
Apply the visual art style of @Image2 to this scene.
Use @Image1 as character reference only (not style).
Style: [описание стиля @Image2]
Character: [описание персонажа @Image1]
Scene: [описание сцены]
```

---

## Продвинутые комбинации

### Серийное видео (Character Bible)
```
# Видео 1 — Создание Character Sheet
Character sheet of @Image1. Full-body orthographic views: front, side, back. A-pose.
Expression sheet: happy, sad, angry, shocked, determined, neutral. Props: [перечисли].
Clean white background, studio lighting, consistent proportions.

# Видео 2–N — Использование Character Sheet
@Image1 is the character reference (from character sheet). [Описание сцены]
Maintain: exact face, hair, outfit colors, body proportions from reference.
```

### Три персонажа
```
@Image1 is Character A — [описание]
@Image2 is Character B — [описание]
@Image3 is Character C — [описание]
All three characters interact in this scene: [описание сцены]
Maintain exact appearances from all references throughout.
```

### Референс + Стиль + Аудио
```
@Image1 as character (maintain appearance).
@Image2 as art style reference.
@Audio1 as music — sync cuts to beat.
[Описание сцены]
```

---

## Советы

1. **Описывай референс словами тоже** — модель лучше держит консистентность если ты ещё и описываешь ключевые черты
2. **Явно запрещай изменения**: `Do NOT alter: face structure, hair color, eye color`
3. **Для стиля**: `apply visual style only, not content` — иначе будет копировать и содержание
4. **Силу референса** (在即梦中): 0.5 = слабое влияние, 0.85 = сильное, 0.95 = максимальное
