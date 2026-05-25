# TIGER — START HERE
### Открывай этот файл когда садишься делать видео.

---

## 5 ПРАВИЛ КОТОРЫЕ НЕЛЬЗЯ НАРУШАТЬ

```
1. ТИГР — ЕДИНСТВЕННОЕ ЖИВОТНОЕ В МИРЕ ЛЮДЕЙ.
   Все остальные персонажи — люди. Кот — обычный кот, не антропоморфный.

2. ТИГР НЕ ДОКАЗЫВАЕТ СЕБЯ. Он уже всё имеет.
   Его реакция на сомнение клиента: лёгкое любопытство. Не злость, не обида.
   Трансформация происходит с КЛИЕНТОМ. Тигр — катализатор.

3. ГОЛОС: никаких восклицательных знаков. Факты, не убеждение.
   "Yes, I made that man handsome." — не "Я лучший!"

4. КОТ — хаос-агент. Никогда не подчиняется. Всегда прав.
   Его молчаливое суждение важнее любого диалога.

5. НОРА — единственный человек перед которым тигр не исполняет роль.
   Её функция: говорить правду. Его функция: слышать.
```

---

## ШАГ 1: ВЫБЕРИ ТИП ВИДЕО СЕГОДНЯ

| Пиллар | Частота | Что снимаешь | Beat Sheet |
|--------|---------|--------------|------------|
| **Профессиональная трансформация** | 55% | Барбер, дантист, шеф, механик, тату, портной | [A](narrative/BEAT_SHEETS.md) |
| **Характерная история** | 20% | Тигр+Кот, Тигр+Нора, Love fail, Утро | [B/C/D/E](narrative/BEAT_SHEETS.md) |
| **Фитнес-комедия** | 10% | Тигр пытается быть спортивным | [A адаптир.](narrative/BEAT_SHEETS.md) |
| **Велнесс/Стресс** | 5% | Медитация ради лица, стресс-приложение | [B адаптир.](narrative/BEAT_SHEETS.md) |
| **Продукт/Лайфстайл** | 10% | Nobody Sausage модель | [A/B](narrative/BEAT_SHEETS.md) |

**Недельный ритм:**
```
Пн: Профессиональная трансформация (даёт энергию на неделю)
Ср: Характерная история — кот или Нора (строит любовь к персонажу)
Пт: Что-то с клиффхэнгером (держит на выходных)
```

---

## ШАГ 2: СКОПИРУЙ НУЖНЫЙ ПРОМПТ-БЛОК

### АНГЛИЙСКИЙ (Seedance / Higgsfield)

```
@Image1 as the Tiger character reference. Convert 2D cartoon appearance into
stylized 3D animation: maintain orange fur with black stripes, half-lidded golden eyes,
slim elegant build, arrogant confident posture. Add volumetric fur texture, subsurface
scattering, cinematic depth of field.

Style: stylized 3D animation, warm studio lighting, adult situational humor tone,
expressive anthropomorphic character design, 24fps, cinematic color grade.
Aspect: 9:16. Duration: 12-15s.

TIGER: slim anthropomorphic tiger, orange fur black stripes, half-lidded arrogant
golden eyes, small round ears, long curled striped tail, [OUTFIT].
All other characters: humans only. No anthropomorphic animals except Tiger.

[ВАШ СЦЕНАРИЙ ПО БИТУ]

Maintain character appearance consistency throughout all shots.
Clean fur texture, smooth animation. No subtitles. No text in frame.
```

### КИТАЙСКИЙ (即梦 / Jimeng)

**Стандартный блок:**
```
@图片1作为老虎角色的外形参考（2D卡通风格转化为stylized 3D animation）。
保持：橙色黑纹皮毛、半眯傲慢的黄金色眼睛、修长优雅的身材、自信的肢体语言。
风格升级：volumetric fur texture, subsurface scattering, cinematic depth of field。

全局风格：stylized 3D animation，暖色调studio lighting，成人情景喜剧基调，
表情丰富的拟人动物角色设计，24fps，9:16，12-15秒。

老虎：修长人形老虎，橙色黑纹皮毛，半眯傲慢金眼，小圆耳，长斑纹卷尾，[职业服装]。
其他角色：只有人类。除老虎外无拟人动物。

[ВАШ СЦЕНАРИЙ]

保持角色造型全程一致，毛发纹理清晰，动作流畅。不生成字幕。
```

**Если нужна 2D→3D конверсия (когда загружаешь 2D-арт):**
```
@图片1作为主角造型参考（2D卡通风格）。
基于@图片1的角色外形，转化为stylized 3D animation风格：
保持：橙色斑纹皮毛、黄金色半眯眼睛、修长优雅身材比例、傲慢自信的肢体语言。
风格转换：从2D平面卡通 → cinematic stylized 3D，添加volumetric lighting和fur texture。
不要改变：角色性格、斑纹图案、体型比例、表情特征。
```

**Два референса (Тигр + Кот):**
```
@图片1作为老虎角色的造型参考，@图片2作为黑猫角色的造型参考。
两个角色均转化为stylized 3D animation风格，保持各自的外形特征和性格。
```

---

## ШАГ 3: ОДНОСТРОКИ ДЛЯ БЫСТРОЙ ВСТАВКИ

```
ТИГР (одна строка):
slim elegant anthropomorphic tiger, bright orange fur with sharp black stripes,
half-lidded arrogant golden eyes, long curled striped tail, upright humanoid posture

КОТ (одна строка):
small fluffy black cat, vivid green round eyes, blue collar with crescent moon charm,
tail curled upright, expression of absolute judgment

СТИЛЬ (одна строка):
stylized 3D animation, warm amber studio lighting, shallow depth of field,
adult situational humor, expressive anthropomorphic character design

ЛАЙТИНГ (одна строка):
warm amber key light 45° upper-right, soft fill from left, subtle rim separation,
shallow depth of field f/1.8, soft bokeh background

ФИНАЛЬНАЯ СТРОКА (закрывает промпт):
Maintain character appearance throughout. No subtitles. No text in frame.
```

---

## ШАГ 4: АУТФИТЫ ПО СИТУАЦИИ

```
БАРБЕР:     black barber jacket, tool belt with scissors/clippers, classic comb
ДАНТИСТ:    white lab coat, blue medical mask (can pull down), blue latex gloves
ШЕФ:        white chef's toque, double-breasted chef coat, optional apron
МЕХАНИК:    grey coveralls open at top, oil stains, wrench in hand
ПОРТНОЙ:    three-piece suit, measuring tape around neck, tiny glasses
ТРЕНЕР:     sleek athletic wear, tiger stripe accent, whistle
ТАТУ-МАСТЕР: black apron, sleeve rolled up, latex gloves, tattoo machine
СПОРТ:      sleek athletic wear, fitness tracker on wrist, water bottle
ВЕЛНЕСС:    lounge/athleisure, clean minimalist, phone with app open
ВЕЧЕР ДОМА: casual but considered — still looks good. Always.
```

---

## ШАГ 5: HOOK — ПЕРВЫЕ 3 СЕКУНДЫ

Выбери один тип хука:

```
А. КЛИЕНТ "ДО" — открываемся на проблеме клиента, тигра ещё нет в кадре
   → самый высокий hold rate, рекомендован для профессиональных видео

Б. ТИГР ОЦЕНИВАЕТ — крупный план взгляда тигра на ситуацию
   → "одно движение бровью. лёгкое любопытство."

В. IN MEDIA RES — уже в середине работы, зритель чувствует что пропустил
   → для опытных зрителей, строит ощущение "нужно смотреть с самого начала"

Г. КОТ ПЕРВЫЙ — кот делает что-то непонятное, тигр появляется потом
   → высокий share rate

Д. ЛОЖНЫЙ ФИНАЛ — открываемся на реакции клиента на результат, потом флэшбэк
   → самый высокий completion rate
```

---

## ШАГ 6: КЛИФФХЭНГЕР В КОНЦЕ

Последние 3 секунды. Выбери один:

```
"Ты — тот самый [пробел]?"          → информационный
Кот смотрит на дверь. Звонок.        → предчувствие
Тигр читает сообщение. Убирает телефон. Долгое молчание.   → эмоциональный
"Это не случайно."                   → интрига
Кот принёс что-то. Откуда это?       → котовый
```

---

## ШАГ 7: CAPTION — ГОЛОС ТИГРА

Три принципа:
```
1. Короткие предложения. Каждое на своей строке.
2. Факты, не убеждение. Точка — не восклицательный знак.
3. Финальный удар — в последних двух словах.
```

Шаблон:
```
[одно наблюдение о ситуации]
[факт о результате]
[поворот или открытая петля]
```

Пример:
```
He said it was beyond repair.
It wasn't.
Stay close.
```

→ Полный разбор голоса: [TIGER_VOICE.md](characters/tiger/TIGER_VOICE.md)

---

## КАРТА ФАЙЛОВ — ЧТО ОТКРЫТЬ ЕСЛИ НУЖНО БОЛЬШЕ

| Нужно | Открой |
|-------|--------|
| Характер, мотивации, арки | [TIGER_BIBLE.md](characters/tiger/TIGER_BIBLE.md) |
| Голос, как писать текст | [TIGER_VOICE.md](characters/tiger/TIGER_VOICE.md) |
| Beat sheets (структура эпизода) | [BEAT_SHEETS.md](narrative/BEAT_SHEETS.md) |
| Клиффхэнгеры (готовые) | [CLIFFHANGER_WRITING.md](narrative/CLIFFHANGER_WRITING.md) |
| Хуки (больше вариантов) | [HOOK_SYSTEM.md](characters/tiger/HOOK_SYSTEM.md) |
| Идеи клиентов "до" | [BEFORE_CLIENTS_CATALOG.md](characters/tiger/BEFORE_CLIENTS_CATALOG.md) |
| Промпты: профессии | [prompts/07-tiger-professional/](prompts/07-tiger-professional/) |
| Промпты: кот и Нора | [prompts/09-tiger-character-stories/](prompts/09-tiger-character-stories/) |
| Промпты: фитнес | [prompts/10-tiger-fitness/](prompts/10-tiger-fitness/) |
| Промпты: стресс/велнесс | [prompts/11-tiger-wellness/](prompts/11-tiger-wellness/) |
| Стратегия, пиллары | [TIGER_CONTENT_STRATEGY.md](characters/tiger/TIGER_CONTENT_STRATEGY.md) |
| Алгоритм 2026, parasocial | [BLOGGER_MECHANICS.md](characters/tiger/BLOGGER_MECHANICS.md) |
| Микродрама теория | [MICRO_DRAMA_MASTERCLASS.md](narrative/MICRO_DRAMA_MASTERCLASS.md) |
