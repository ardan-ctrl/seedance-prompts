# MASTER SYSTEM — Анатомия промпта для Seedance 2.0

> Это главный файл системы. Читай его перед написанием любого промпта.
> Здесь — формулы, принципы, стили, техники и правила.

---

## 1. АНАТОМИЯ ПРОМПТА

Каждый сильный промпт состоит из **5 слоёв**:

```
[СТИЛЬ И ВИЗУАЛЬНЫЙ ЯЗЫК]
[СУБЪЕКТ + ДЕТАЛИ ПЕРСОНАЖА]
[СИТУАЦИЯ И КОНТЕКСТ]
[ДЕЙСТВИЕ — ПОШАГОВО]
[КАМЕРА + ДВИЖЕНИЕ + СВЕТ]
```

### Пример (кратко):
```
[Стиль: low-poly 3D chibi animation, bright saturated colors]
[Субъект: young boy, oversized head, huge cartoon eyes, navy school uniform]
[Контекст: Roman colosseum, miniature crowds in stadium seating]
[Действие: he materializes at center, looks at his hands in shock, two knights approach,
           he jabs his watch — misses twice — third press works, he teleports]
[Камера: extreme close-up on hands → wide on arena → fast track on knights → medium pull-back]
```

---

## 2. БАЗОВЫЕ ФОРМУЛЫ

### Формула 5 слотов (для быстрого промпта)
```
[Субъект] + [Действие] + [Стиль] + [Камера] + [Атмосфера]
```

### Формула трансформации (для вирусного контента)
```
CALM (2-3s) → THREAT (3-4s) → TRANSFORMATION (4-5s) → AFTERMATH (2-3s)
```
Структура: 6 шотов, 15 секунд, 16:9

### Формула эмоциональной арки (для мультяшных историй)
```
БОЛЬ/ПРОБЛЕМА → РЕШЕНИЕ/УСИЛИЕ → ТРАНСФОРМАЦИЯ → ТРИУМФ/ПРИНЯТИЕ
```

### CRAFT Framework (для мультиреференсных проектов)
```
Context:   [где, когда, общая ситуация]
Reference: [@Image1 персонаж, @Video1 движение, @Audio1 ритм]
Action:    [что происходит, пошагово]
Framing:   [тип шота, движение камеры]
Tone:      [цвет, эмоция, стиль]
```

---

## 3. СТИЛИ АНИМАЦИИ

### 2D / Рисованные
| Стиль | Ключевые слова |
|-------|----------------|
| Аниме (современный) | `bold 2D anime illustration, cel-shaded flat coloring, thick confident outlines, warm amber tones with electric blue accents` |
| Манга 1980-х | `1980s–90s seinen manga ink, bold black lines, cross-hatching, screentone dots, no color, no grey, zero 3D, zero CGI` |
| Магическая девочка | `anime magical girl transformation, ribbons of light, sparkle effects, luminous pastel colors, graceful movement, consistent character design` |
| Демон Слейер-стиль | `anime cel-shaded over live-action backgrounds, Demon Slayer aesthetic, ultra-high detail on elemental effects` |
| Токусацу | `tokusatsu-style cinematic, realistic handheld footage, practical VFX, dynamic cuts, motion blur` |

### 3D / Объёмные
| Стиль | Ключевые слова |
|-------|----------------|
| Low-Poly Chibi | `low-poly 3D chibi animation, toy-like aesthetic, bright saturated colors, smooth polygon surfaces, oversized head proportions` |
| Клеймация (Claymation) | `3D claymation cinematic, soft clay texture on all surfaces, visible fingerprint and tool marks on clay forms` |
| Клеймация + Киберпанк | `3D claymation cinematic, cyberpunk night, neon magenta/cyan/purple lighting, deep slow-motion physics throughout` |
| Стилизованный 3D | `cinematic stylized 3D animation, photorealistic environment, stylized characters, 2.35:1, 24fps` |
| Пиксель-арт | `8-bit pixel art, side-scrolling landscape, chiptune, retro game aesthetic` |

### Живое действие / Смешанные
| Стиль | Ключевые слова |
|-------|----------------|
| Гиперреализм | `photorealistic, 35mm film quality, ARRI ALEXA aesthetic, shallow depth of field, film grain` |
| Mixed Media | `live-action photorealistic environment, single 2D flat cartoon character composited in` |
| POV-реализм | `first-person POV, hyper-chaotic handheld, completely unstabilized, wide-angle lens strong distortion` |
| Голливудский экшн | `Montage, multi-shot action Hollywood movie, cinematic lighting, professional color grading, ARRI ALEXA aesthetic` |

---

## 4. ДВИЖЕНИЯ КАМЕРЫ

### Базовые
```
slow dolly in          — медленный наезд
slow dolly out         — медленный отъезд
tracking shot          — сопровождающий
crane shot             — с высоты, откатывающийся
low-angle              — снизу вверх
extreme close-up (ECU) — крупный план детали
360-degree orbit       — полный оборот вокруг объекта
FPV arm                — дрон-перспектива
```

### Специальные
```
hyper-chaotic handheld    — дестабилизированная ручная (для POV-реализма)
camera circles at high speed — быстрый орбит (для боевых сцен)
seamless loop             — начало = конец (для зацикленного контента)
```

---

## 5. УПРАВЛЕНИЕ ТЕМПОМ

### Снайдер-ритм (удар/пауза)
```
RAMPS TO SLOW MOTION as [ключевой момент — лезвие, удар, взрыв]
SNAPS BACK [внезапное возвращение к полной скорости]
```
Пример: `RAMPS TO SLOW MOTION as the blade sweeps through the space where her face was — SNAPS BACK, she drives her elbow into his chest`

### Таймкод-раскадровка
```
0-3s:   [тип камеры] + [действие]
3-6s:   [тип камеры] + [действие]
6-9s:   [тип камеры] + [действие]
9-12s:  [тип камеры] + [действие]
12-15s: [тип камеры] + [действие]
```

---

## 6. @-РЕФЕРЕНСНАЯ СИСТЕМА

Seedance 2.0 принимает до 12 файлов как контекст. Синтаксис:

```bash
# Персонаж из фото
@Image1 as the main character throughout the video

# Первый кадр — отправная точка
@Image1 as first keyframe, maintain character appearance

# Стиль из видео
@Video1 for camera movement and pacing reference

# Движения персонажа
Maintain character from @Image1, replicate actions from @Video1

# Аудио как ритм
@Audio1 as background music, sync camera cuts to beat

# Расширение видео
Extend @Video1 by 5 seconds, maintain style and atmosphere

# Чарактер-лист
Character sheet of @Image1, multi-view, A-pose, white background,
expression sheet showing 6 emotions

# Трансфер стиля
Apply visual style of @Image2 to character from @Image1
```

---

## 7. СЛОВАРЬ ВИЗУАЛЬНЫХ ЭФФЕКТОВ

### Трансформации
```
body erupts into / her body violently expands and twists upward
spine cracking, limbs stretching, jaws splitting open wide
green energy ribbons spiral up her body, armor plates snapping on piece by piece
jaw unhinging / bone-snap / vertebrae cracking
fractal lightning veins explode across forearms
VFX: branching electric circuits pulsing with white-blue current
```

### Частицы и энергия
```
geometric light fragments scatter and vanish
low-poly shards that scatter and disappear
rainbow energy repels her, blasts her backward
clay body fractures into soft clay shards
energy tearing outward in layered shockwaves
electrical storms spreading across battlefield
shattered particles transform into dancing elements
```

### Физика окружения
```
photorealistic desert particle simulation, volumetric dust storm
clay bullet tumbles in lazy slow motion
clay tears forming and rolling in perfect clay physics
each raindrop a tiny perfect clay bead hitting clay surfaces
water ripples, marble breathes
```

---

## 8. КОНСИСТЕНТНОСТЬ ПЕРСОНАЖА

Для создания серийного контента с одним персонажем:

### Шаг 1 — Character Sheet
```
Character sheet — [Style]. [Name]: [detailed description of appearance].
Full-body orthographic views (front, side, back). A-pose. Expression sheet:
happy, sad, angry, shocked, determined, neutral. Clean neutral background,
studio lighting, consistent proportions throughout all views.
```

### Шаг 2 — Закрепление через @-референс
```
@Image1 is the definitive appearance reference for [character name].
Maintain: [hair color/style], [eye color/shape], [outfit description],
[body proportions], [distinctive features].
Do NOT alter: face structure, hair, color palette.
```

### Шаг 3 — Шаблон сцены с персонажем
```
[Character from @Image1] in [new situation/world].
Maintain exact appearance from reference. [Action]. [Style]. [Camera]. [Lighting].
```

---

## 9. СИТУАЦИИ ДЛЯ МУЛЬТЯШНОГО ГЕРОЯ

Куда можно поместить мультяшного персонажа, чтобы это работало великолепно:

| Ситуация | Почему работает |
|----------|-----------------|
| Он/она случайно попадает в "серьёзный" мир взрослых | Контраст мультяшного и реального |
| Трансформируется в монстра/героя, когда угрожают | Тайная сила + комедийный контраст |
| Оказывается в разных стилях анимации внутри одного видео | Мета-приём, вирусный |
| Застрял между невестой и женихом / в неловкой ситуации | Комедия вторжения |
| Побеждает огромного врага нелепым способом | Давид и Голиаф |
| Проходит через знаменитые картины / исторические эпохи | Образовательный + зрелищный |
| Реагирует на угрозу полным равнодушием | Deadpan comedy |
| Трансформируется именно в тот момент, когда это нужно | Саспенс + пэйофф |
| Попадает в неправильный мир (чиби в реалистичном аду) | Стилевой диссонанс |
| Его крошечные действия имеют огромные последствия | Непропорциональный эффект |

---

## 10. ПРАВИЛА НАПИСАНИЯ

1. **Начинай со стиля** — первые слова задают визуальный язык всей сцены
2. **Детали персонажа — конкретно**: не "girl", а "pink-haired girl with cat-eye glasses, cream top, cross necklace"
3. **Действие — глаголами**: `erupts`, `snaps`, `slams`, `lunges`, `drives`, не `does` или `makes`
4. **Описывай физику**: не "she falls", а "she tumbles sideways off the carriage in slow motion, still gripping her katana"
5. **Один промпт = одна сцена**: не пытайся впихнуть всю историю в один промпт
6. **Длина**: 120–280 слов для многошотовых сцен; 50–70 для простого I2V
7. **Оптимальная структура шота**: `[Camera type] + [Subject position] + [Action] + [Atmospheric detail]`
8. **Стиль через отрицание**: добавляй `zero 3D, zero CGI` для манги; `no cartoon` для реализма
9. **Всегда указывай**: соотношение сторон (16:9 / 9:16 / 2.35:1) и хронометраж
10. **Seamless loop**: если нужна петля — описывай начало и конец как одинаковое состояние
