# Быстрый Конструктор Промптов

> Выбирай компоненты из каждого блока и собирай промпт.
> Минимальный рабочий промпт: СТИЛЬ + ПЕРСОНАЖ + ДЕЙСТВИЕ + КАМЕРА.

---

## БЛОК 1: СТИЛЬ (выбери один)

```
# 2D АНИМЕ
bold 2D anime illustration, cel-shaded flat coloring, thick confident outlines,
warm amber and muted earth tones with cool electric blue accents

# LOW-POLY CHIBI
low-poly 3D chibi animation, toy-like aesthetic, bright saturated colors,
smooth polygon surfaces, oversized head proportions

# КЛЕЙМАЦИЯ
3D claymation cinematic, soft clay texture on all surfaces,
visible fingerprint and tool marks on clay forms

# КЛЕЙМАЦИЯ + КИБЕРПАНК
3D claymation cinematic, cyberpunk night, neon magenta/cyan/purple lighting,
deep slow-motion physics

# МАНГА 1980-х
1980s–90s seinen manga ink, bold black lines, cross-hatching, screentone dots,
no color, no grey, zero 3D, zero CGI

# ГОЛЛИВУДСКИЙ КИНО-РЕАЛИЗМ
cinematic lighting, photorealistic, 35mm film quality, professional color grading,
sharp focus, film grain, ARRI ALEXA aesthetic

# MIXED MEDIA (мультяшный в живом мире)
live-action photorealistic environment, single 2D flat cartoon character composited in

# СТИЛИЗОВАННЫЙ 3D
cinematic stylized 3D animation, photorealistic environment, stylized characters, 24fps
```

---

## БЛОК 2: ПЕРСОНАЖ (заполни или используй @Image1)

```
# ШАБЛОН ОПИСАНИЯ
[возраст] [пол] [цвет волос, стиль] [цвет глаз] [одежда детально] [особенности]

# ПРИМЕРЫ
pink-haired girl with cat-eye glasses, cream top, jeans, cross necklace
red-haired girl in white tank top, cat-eye sunglasses, headphones
anime demon queen with long white hair, black horns, flowing dark crimson gown
worn humanoid robot with aged brushed-steel plating, glowing blue eyes
white cat character in pastel dress with a bow

# С РЕФЕРЕНСОМ
@Image1 as the main character. Maintain exact appearance throughout.
Do NOT alter: face structure, hair, outfit colors.
```

---

## БЛОК 3: СИТУАЦИЯ

```
# ТАЙНАЯ СИЛА
[персонаж] в [нормальная ситуация]. [угроза] появляется. [персонаж] нейтрализует
с полным равнодушием и возвращается к [нормальная ситуация].

# ТРАНСФОРМАЦИЯ
[персонаж] → [трансформирующий агент] → [трансформированная форма] → [действие]
→ [возврат к норме]

# МУЛЬТЯШНЫЙ В НЕПРАВИЛЬНОМ МИРЕ
[мультяшный персонаж] попадает в [серьёзная/реалистичная среда].
[невинное действие] игнорирует [хаос вокруг].

# ДУЭЛЬ / ФАЙТ
[персонаж A] и [персонаж B] встречаются в [локация].
[техника A] vs [техника B]. Столкновение. [результат].

# ЭМОЦИОНАЛЬНАЯ АРКА
[боль/отвержение] → [решение] → [трансформация] → [триумф]
```

---

## БЛОК 4: КАМЕРА

```
# СТАТИЧНАЯ
wide establishing shot / medium shot / close-up / extreme close-up

# ДВИЖУЩАЯСЯ
slow dolly in (наезд)
slow dolly out (отъезд)
360-degree orbit around [субъект]
tracking shot following [субъект]
crane shot pulling back to reveal
low-angle looking up at [субъект]
FPV arm cresting [объект]

# МУЛЬТИШОТ
don't use one camera angle or single cut, multi-shot montage

# ОДИН НЕПРЕРЫВНЫЙ ШОТ
single continuous shot, no cuts

# POV
first-person POV, hyper-chaotic unstabilized handheld
```

---

## БЛОК 5: АТМОСФЕРА

```
# СВЕТ
golden hour warm light
dramatic backlighting
neon magenta/cyan/purple
cold blue palette
firelight and moonlight
studio lighting dark background
volumetric light shafts through dust

# ЦВЕТ
warm amber and rust
muted earth tones
vibrant saturated palette
black and crimson
pastel luminous
desaturated gritty

# ЭМОЦИЯ
dark comedy pacing with horror undertones
intimate and emotional, shallow depth of field
epic and majestic, sweeping
tense and claustrophobic
dreamlike and surreal
```

---

## БЛОК 6: ФИНАЛЬНЫЕ ПАРАМЕТРЫ

```
Total: [10s / 15s] / [1 shot / N shots] / [16:9 / 9:16 / 2.35:1 / 1:1]
```

---

## Пример сборки

```
[СТИЛЬ] bold 2D anime illustration, cel-shaded flat coloring
[ПЕРСОНАЖ] @Image1 — anime girl, maintain exact appearance
[СИТУАЦИЯ] She sits at a café table reading, when a giant monster appears outside the window.
          She glances up once, sets down her coffee, steps outside, defeats it with one move,
          returns and picks up her coffee where she left off.
[КАМЕРА] multi-shot montage: medium → wide tracking → close-up → wide low-angle → medium
[АТМОСФЕРА] warm café lighting, cold grey outside, dark comedy pacing
Total: 15s / multi-shot / 16:9
```
