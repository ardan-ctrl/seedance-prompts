# TIGER CHARACTER SYSTEM — Seedance 2.0 Prompt Architecture
# Серия: Тигр-профессионал + Чёрный Котёнок-ассистент

> Главный справочник персонажей и параметров для всей серии видео.
> Этот файл — источник истины для всех промптов серии 07-tiger-professional.

---

## РАЗДЕЛ 1 — ВИЗУАЛЬНЫЙ СТИЛЬ СЕРИИ

### Стилевая формула (copy-paste в каждый промпт)

```
stylized 3D animation, warm family-film aesthetic, expressive character design,
volumetric studio lighting, subsurface scattering on fur, cinematic depth of field,
adult situational humor tone, NOT childish, NOT dark — confident warm comedic aesthetic
```

### Полная стилевая строка

```
Cinematic stylized 3D animation with expressive anthropomorphic character design.
Warm studio lighting, soft bokeh background, shallow depth of field on character.
Color palette: warm amber and cream tones, professional interior setting.
Visual tone: confident adult situational comedy — sophisticated, warm, never crude.
Fur textures with subsurface scattering, smooth 24fps character animation.
```

### Почему НЕ называем "Pixar"

Jimeng IP-фильтр блокирует прямые ссылки на студии. Используем описания:
- ❌ `"Pixar-style"` → ✅ `"stylized 3D animation, warm family-film aesthetic, expressive character design"`
- ❌ `"like The Incredibles"` → ✅ `"adult situational humor, sophisticated comedic tone, confident protagonist energy"`
- ❌ `"Pixar quality"` → ✅ `"cinematic 3D, volumetric lighting, subsurface scattering on fur, 24fps"`

---

## РАЗДЕЛ 2 — ОПИСАНИЕ ТИГРА (CHARACTER BLOCK)

### Базовое описание персонажа (вставляй в каждый промпт)

```
The Tiger: anthropomorphic tiger, slim elongated build, elegant not bulky proportions.
Bright orange fur with sharp black stripes running diagonally across body.
Half-lidded golden eyes — permanently arrogant, self-assured expression.
Small rounded ears, prominent whiskers, expressive muzzle.
Long striped tail with slight curl at the tip.
Walks upright on hind legs, humanoid proportions — slightly taller than realistic,
fashion-forward silhouette. Resting pose: arms loosely crossed or one hand on hip,
weight shifted slightly, chin slightly raised — effortless superiority.
```

### Мини-версия (для коротких промптов)

```
slim elegant anthropomorphic tiger, orange fur with black stripes,
half-lidded arrogant golden eyes, small round ears, long curled tail,
upright posture, arms-crossed confident stance
```

### Character Sheet промпт (для генерации референса)

```
Character design sheet — stylized 3D animation, warm cinematic aesthetic.
Character: The Tiger, anthropomorphic professional.

Full-body orthographic views on clean neutral studio background:
- Front view: A-pose, arms relaxed at sides
- Side view (left profile): A-pose
- Back view: A-pose

Character details:
- Build: slim, elongated, elegant — fashion-model proportions for an anthropomorphic tiger
- Fur: bright orange base with sharp black diagonal stripes; white/cream on chest and inner arms
- Eyes: half-lidded, golden amber irises, permanently arrogant expression
- Ears: small, rounded, set wide on head
- Whiskers: prominent, slightly upward angle
- Tail: long, orange-black striped, slight curl at tip, trails behind
- Resting expression: smug, one eyebrow slightly elevated, lips in thin confident line
- Hands: anthropomorphic tiger hands, 4 fingers, retractable claws visible but not extended

Expression sheet (bust shots):
- Neutral/resting: half-lidded smug default
- Professional focus: eyes narrowed, appraising look
- Mild disdain: single eyebrow raised, slight nose wrinkle
- Rare approval: full eye-open, subtle satisfied nod
- Surprise (rare): eyes fully open, breaking the half-lid — comedic contrast
- Full smugness peak: slow blink, hint of smile, arms crossed tighter

Warm studio lighting, consistent proportions across all views.
```

---

## РАЗДЕЛ 3 — ОПИСАНИЕ ЧЁРНОГО КОТЁНКА (CHARACTER BLOCK)

### Базовое описание

```
The Black Kitten: small fluffy black cat, 3D stylized animation.
Jet-black fur, bright vivid green eyes with round pupils.
Blue collar with crescent moon charm pendant.
Small, compact build — noticeably smaller than the Tiger.
Tail: upright, proud curl at tip.
Expression: simultaneously adorable and opinionated — "I have opinions and I will share them."
Moves with disproportionate confidence for its tiny size.
```

### Функция в кадре

Котёнок — моральный компас и комедийный контрапункт Тигра. Реагирует на клиентов
с нескрываемым ужасом, восторгом или осуждением. Усиливает комедийный контраст.

---

## РАЗДЕЛ 4 — @-ТЕГИРОВАНИЕ (REFERENCE SYNTAX)

### Стандарт платформы

На Jimeng/Dreamina/Xiaoyunque — китайский синтаксис:
- `@图片1` — первое изображение
- `@图片2` — второе изображение
- `@视频1` — видео-референс

На Seedance (если через API / прямой интерфейс):
- `@Image1`, `@Image2` — английский синтаксис

### Формула для 2D→3D конверсии персонажа

```
@图片1作为主角造型参考（2D卡通风格）。
基于@图片1的角色外形，转化为stylized 3D animation风格：
保持：橙色斑纹皮毛、黄金色半眯眼睛、修长优雅身材比例、傲慢自信的肢体语言。
风格转换：从2D平面卡通 → cinematic stylized 3D，添加volumetric lighting和fur texture。
不要改变：角色性格、斑纹图案、体型比例、表情特征。
```

### Английская версия (для не-китайского интерфейса)

```
@Image1 is the 2D cartoon reference for the Tiger character.
Convert his appearance from 2D flat cartoon into stylized 3D animation:
PRESERVE: orange fur with black stripes, half-lidded golden eyes, slim elegant build,
arrogant crossed-arms posture, long striped tail, small rounded ears, prominent whiskers.
STYLE SHIFT: 2D flat design → cinematic 3D with volumetric fur, subsurface scattering,
depth-of-field background blur.
Do NOT alter: personality, stripe pattern, body proportions, expression character.
```

### Формула для двух референсов (Тигр + Котёнок)

```
@图片1作为老虎角色的造型参考，@图片2作为黑猫角色的造型参考。
两个角色均转化为stylized 3D animation风格，保持各自的外形特征和性格。
```

---

## РАЗДЕЛ 5 — ОСВЕЩЕНИЕ И КИНЕМАТОГРАФИКА

### Основной лайтинг-пресет серии

```
Warm studio interior lighting: key light from upper-right at 45°, warm amber tone (3200K).
Soft fill light from left, reducing harsh shadows while maintaining depth.
Subtle rim light outlining character against background — separation without drama.
Background: shallow depth of field (f/1.8 equivalent), soft bokeh on professional interior.
Color grade: warm amber-cream base, desaturated backgrounds, character colors pop.
Lens: medium focal length equivalent, slight compression — professional portrait feel.
```

### Короткий лайтинг-тег

```
warm amber studio lighting, shallow depth of field, soft bokeh background,
cinematic color grade, professional interior warmth
```

### По профессиям (пространство меняется, лайтинг-логика та же)

| Профессия | Пространство | Акцент освещения |
|-----------|-------------|------------------|
| Стоматолог | Dental clinic, white/teal palette | Cool overhead light + warm fill на тигре |
| Барбер | Vintage barbershop, warm wood tones | Warm Edison bulbs, mirror reflections |
| Шеф-повар | Professional kitchen, stainless steel | Mixed warm overhead + cool equipment glow |
| Механик | Auto workshop, concrete + metal | Industrial overhead + warm work lamps |
| Портной | Tailoring atelier, dark wood | Warm directional task lighting |
| Тренер | Gym / dojo | Natural light + soft overhead |
| Ветеринар | Clinic, clean white | Cool white + warm character fill |
| Фотограф | Studio with equipment | Multiple rim lights, creative setup |

---

## РАЗДЕЛ 6 — ПРОФЕССИОНАЛЬНЫЕ ОБРАЗЫ ТИГРА

### Стоматолог

```
Tiger wearing: crisp white dental lab coat (knee-length), light blue scrubs underneath,
white latex gloves, small round wire-frame magnification glasses perched on nose,
dental mirror held casually in one hand — like a conductor's baton.
Posture: appraising the patient's situation with visible professional disdain.
Optional: white surgical mask pulled down below chin.
```

### Барбер / Стилист

```
Tiger wearing: fitted black barber's jacket with silver snap buttons,
white barber's towel draped over left forearm, premium scissors in right hand —
held upward, pointing at ceiling, dramatically.
Optional: thin black barber's apron over jacket.
Posture: circling client like a sculptor evaluating raw material.
```

### Шеф-повар

```
Tiger wearing: classic white double-breasted chef coat with black piping,
tall white toque (chef's hat) — slightly tilted, giving rakish edge to the arrogance.
Black and white checkered pants. Pristine white kitchen towel tucked at waist.
Holding: either a single chef's knife (tip resting on cutting board) or a ladle
raised mid-inspection. Expression: appraising whatever culinary disaster just arrived.
```

### Механик

```
Tiger wearing: fitted navy blue mechanic's coverall (sleeves pushed to elbows),
vintage logo patch on chest, oil-stained leather tool belt, safety glasses
pushed up to forehead (never actually worn, purely aesthetic).
Holding: a socket wrench, tapping it against palm with slow rhythmic patience
while surveying the wreck that just drove in.
```

### Портной / Таилор

```
Tiger wearing: fitted charcoal grey vest over crisp white dress shirt,
sleeve garters (old-fashioned armbands), measuring tape draped around neck,
slim charcoal trousers with sharp crease, dress shoes.
Holding: a single pin pinched between two claws, eyeing client with the look
of someone about to perform a miracle on impossible raw material.
```

### Тренер / Коуч

```
Tiger wearing: fitted black athletic tracksuit with orange accent stripe
(mirrors natural fur colors, intentional), white sneakers, stopwatch around neck.
Arms crossed — but now it's authority, not just smugness.
Clipboard optional. Whistle: absolutely not — too pedestrian for this tiger.
```

### Ветеринар

```
Tiger wearing: sage green surgical scrubs, white vet coat over them,
stethoscope around neck, nitrile gloves already on.
The irony of a predatory animal as veterinarian is the entire joke —
lean into it: he examines smaller animals with clinical detachment.
```

### Фотограф

```
Tiger wearing: fitted black turtleneck, slim black trousers, minimal and editorial.
Large professional camera strap around neck (camera hanging).
One hand raised, gesturing direction, one eye slightly more closed — art-directing.
```

---

## РАЗДЕЛ 7 — 15 АРХЕТИПОВ "ДО" (КЛИЕНТЫ ДЛЯ МАКСИМАЛЬНОГО КОНТРАСТА)

Принцип: максимальный разрыв между состоянием клиента и профессиональным
совершенством Тигра. Чем сильнее контраст — тем чище комедийный пэйофф.

### Группа A — Физическая катастрофа (видимые)

**1. Бизнес-Вепрь с тысячью дел**
Антропоморфный кабан в мятом костюме, расстёгнутый галстук, борода как после месяца
в лесу, три телефона в руках одновременно, продолжает звонок пока садится в кресло.
Контраст: хаос vs. тихое профессиональное достоинство Тигра.

**2. Рок-музыкант на пенсии**
Пожилой антропоморфный бобёр или медведь, кожаная куртка с металлическими заклёпками,
полностью облысевший сверху но с длинными патлами по бокам (классический "конский хвост
с лысиной"), татуировки, ещё держит гитарный медиатор.
Контраст: гламурная рок-идентичность не совпадает с реальностью в зеркале.

**3. Баба-Яга (современная версия)**
Пожилая антропоморфная лиса или сова, огромная бесформенная верхняя одежда, волосы
в 7 разных направлениях, пальцы с длиннющими нечищеными когтями — которые она
собирается "просто немного подровнять", старинные украшения, клюка с замысловатой ручкой.
Контраст: древний хаос vs. современный профессионал.

**4. Победитель хот-дог-конкурса**
Огромный добродушный антропоморфный медведь, майка с соусными пятнами, объедки
за ушами, абсолютно счастливый, не понимает зачем сюда пришёл — его привели.
Контраст: Тигр должен сдерживать инстинктивное желание уйти.

**5. Романтический Катастрофщик**
Антропоморфный кот, явно только что из очень неудачного свидания: рубашка вверх
ногами, помада на щеке (не его), один каблук сломан (он в туфлях), прическа
живёт отдельной жизнью, выражение смеси счастья и катастрофы.

### Группа B — Самоуверенные Катастрофы (считают себя великолепными)

**6. Корпоративный Тренд-Трекер**
Антропоморфная лиса в трендовом офисном наряде, который подобрала по TikTok —
каждая деталь из разной эпохи и традиции одновременно, уверена что выглядит идеально.
Приходит уточнить "маленькую деталь". Тигр видит эту "маленькую деталь".

**7. DIY-Герой**
Антропоморфный бобёр (очевидно), сам себе пытался починить/сделать что-то, связанное
с профессией Тигра. Результат технически жив, но на грани. Очень гордится.
Контраст: самодельное решение vs. реальный профессионализм.

**8. Профессиональный Клиент**
Антропоморфный попугай, который "много читал об этом", приносит папку с распечатками,
рассказывает Тигру как надо делать его работу. Тигр слушает. Потом делает по-своему.
Молча. Результат говорит сам за себя.

**9. Легенда в Своём Воображении**
Пожилой антропоморфный лев (или тигр постарше — поколенческий контраст),
рассказывает о временах когда он был "настоящий красавец", не понимает что время
идёт, хочет вернуть образ 1985 года. Буквально.
Контраст: ностальгия vs. реальность.

**10. Соцсеть-Зависимый**
Антропоморфный олень, не убирает телефон, фоткает всё для Stories, пытается снимать
процесс работы Тигра (тот не разрешает), через три секунды снова в телефоне.
Прическа/состояние: следствие трёх часов ночного думскроллинга.

### Группа C — Экстремальные Ситуации (обстоятельства привели их сюда)

**11. Несчастный Жених**
Антропоморфный кролик, свадьба через два часа, выглядит как будто провёл ночь
в кустах (потому что провёл), костюм есть, но состояние его — нет.
Тигр: одно медленное моргание. Потом: профессиональная мобилизация.

**12. Чемпион Прошлого Года**
Антропоморфный барсук или бульдог, трофеи и медали на груди за прошлые победы,
возвращается к важному событию — но со времени последней победы прошло, заметно.
Хочет выглядеть как тогда. Тигр оценивает разрыв между желаемым и возможным.

**13. Ребёнок с Ножницами (взрослый)**
Антропоморфная овца, сама себе что-то подстригла/сделала ночью, результат симметричен
только случайно и только с одной стороны. Говорит что "почти нормально" и просит
только "выровнять чуть-чуть". Тигр долго смотрит. Потом: "Нет".
(Потом всё равно делает. Профессионально.)

**14. Фестивальный Выживший**
Антропоморфный енот, три дня на музыкальном фестивале, глаза счастливые но пустые,
в волосах что-то непонятное (наклейка? нет, это живёт там теперь), запах приключений.
Приходит прямо с фестиваля, через час — важная встреча с инвесторами.
Тигр: секундная пауза. Потом начинает работать молча.

**15. Академик с Открытием**
Антропоморфная сова в потрёпанном твидовом костюме, волосы не видели расчёски
с момента важного открытия (это было три месяца назад), очки заклеены скотчем,
авторучки торчат из каждого кармана, блокнот под мышкой.
Пришла только потому что предстоит телевизионное интервью.
Тигр внимательно изучает фронт работ. Медленно кивает.

---

## РАЗДЕЛ 8 — СЦЕНАРНЫЕ ШАБЛОНЫ (СТРУКТУРА ВИДЕО)

### Стандартная схема эпизода (10–15 секунд, 9:16)

```
[00:00–00:03] ESTABLISHMENT: Тигр в рабочем пространстве. Профессиональная поза.
              Котёнок на своём месте (стойка, полка, рядом). Атмосфера компетентности.
              Камера: medium shot, slow dolly in.

[00:03–00:06] CLIENT ARRIVAL: Клиент входит/появляется.
              Его "ДО"-состояние читается с первого кадра.
              Тигр и Котёнок реагируют: Тигр — одно медленное моргание или пауза.
              Котёнок — глаза распахнуты или зажмурены.
              Камера: wide shot чтобы виден весь клиент.

[00:06–00:10] THE WORK: Тигр работает. Уверенно. Быстро. Без лишних слов.
              Руки движутся точно. Клиент — в кресле/на месте.
              Котёнок наблюдает, подаёт инструменты или просто smug side-eye.
              Камера: close-up на hands/tools → pull back на процесс.

[00:10–00:15] THE REVEAL: Трансформация клиента. Зеркало или финальный взгляд.
              Клиент: шок, восхищение, не верит.
              Тигр: медленно снимает перчатки/кладёт инструмент. Half-lidded.
              Котёнок: хвост поднят, гордый вид.
              Камера: slow dolly in на реакцию клиента → cut to Тигр smug close-up.
```

### Финальный стоп-кадр (для максимального impact)

```
Final frame: Tiger in foreground, three-quarter angle, arms loosely crossed,
chin slightly raised, half-lidded eyes looking just past camera — classic smug close-out.
Black Kitten seated on surface at waist height beside Tiger, tail up, green eyes forward.
Warm backlit glow. Depth of field: sharp on Tiger/Kitten, soft bokeh on transformed client.
Hold 1.5 seconds.
```

---

## РАЗДЕЛ 9 — ПОЛНЫЙ ШАБЛОН ПРОМПТА (copy-paste ready)

### Шаблон A (английский интерфейс Seedance)

```
@Image1 as the Tiger character reference. Convert 2D cartoon appearance into
stylized 3D animation: maintain orange fur with black stripes, half-lidded golden eyes,
slim elegant build, arrogant confident posture. Add volumetric fur texture, subsurface
scattering, cinematic depth of field.

[SERIES: Tiger Professional — Episode: [PROFESSION]]
Style: stylized 3D animation, warm studio lighting, adult situational humor tone,
expressive anthropomorphic character design, 24fps, cinematic color grade.
Aspect: 9:16. Duration: 12s.

Characters:
TIGER: slim anthropomorphic tiger, orange fur black stripes, half-lidded arrogant
golden eyes, small round ears, long curled tail, [PROFESSION OUTFIT].
BLACK KITTEN: small fluffy black cat, vivid green eyes, blue moon-charm collar,
upright proud tail, assistant role.

[00:00–00:03] Medium shot, slow dolly in — Tiger stands in [PROFESSIONAL SPACE],
arms loosely crossed, appraising the empty client station. Black Kitten sits nearby,
tail upright. Warm amber studio lighting, soft bokeh background.

[00:03–00:06] Wide shot — [CLIENT ARCHETYPE] enters. Their "before" state visible
immediately. Tiger: single slow blink. Kitten: eyes widen. 
The comedic contrast established without dialogue.

[00:06–00:10] Close-up on Tiger's hands working — [SPECIFIC PROFESSIONAL GESTURE].
Pull back to medium shot showing focused professional concentration.
Client visible in background/chair. Warm overhead lighting on work area.

[00:10–00:12] Slow dolly in — Client's reaction to transformation: genuine shock.
Cut to Tiger: half-lidded, chin raised, arms crossed. Perfect. As expected.
Kitten: tail fully upright, green eyes forward. Credits-ready pose.

Maintain character appearance consistency throughout. Smooth animation, clean fur texture.
No subtitles. No text overlays.
```

### Шаблон B (китайский Jimeng/Dreamina)

```
@图片1作为老虎角色的外形参考（2D卡通风格转化为stylized 3D animation）。
保持：橙色黑纹皮毛、半眯傲慢的黄金色眼睛、修长优雅的身材、自信的肢体语言。
风格升级：添加volumetric fur texture, subsurface scattering, cinematic depth of field。

【系列：职业老虎 — 第[N]集：[职业]】
全局风格：stylized 3D animation，暖色调studio lighting，成人情景喜剧基调，
表情丰富的拟人动物角色设计，24fps，9:16，12秒。

角色设定：
老虎：修长人形老虎，橙色黑纹皮毛，半眯傲慢金眼，小圆耳，长斑纹卷尾，
穿着[职业服装]。
黑猫助手：小只蓬松黑猫，鲜绿色眼睛，蓝色月亮吊坠项圈，高扬的尾巴。

[00:00–00:03] 中景 + slow dolly in — 老虎站在[职业空间]，双臂轻松交叉，
审视空的客户位置。黑猫坐在旁边，尾巴竖直。暖色调studio lighting，背景柔焦。

[00:03–00:06] 宽景 — [客户类型]进场，"改造前"状态一目了然。
老虎：缓缓眨一次眼。黑猫：瞪大眼睛。喜剧对比无需对话即可建立。

[00:06–00:10] 特写老虎双手工作——[具体职业动作]。
拉回至中景，展现专注的职业专注感。暖光照在工作区域。

[00:10–00:12] 慢推进——客户对改造结果的反应：真实震惊。
切至老虎：半眯眼，仰头，双臂交叉。完美。一切如预期。
黑猫：尾巴完全竖起，绿眼直视前方。

保持角色造型全程一致，毛发纹理清晰，动作流畅自然。不生成字幕。
```

---

## РАЗДЕЛ 10 — БЫСТРЫЙ СПРАВОЧНИК

### Тигр в одну строку
```
slim elegant anthropomorphic tiger, bright orange fur with sharp black stripes,
half-lidded arrogant golden eyes, long curled striped tail, upright humanoid posture,
arms loosely crossed, chin slightly raised
```

### Котёнок в одну строку
```
small fluffy black kitten, vivid green round eyes, blue collar with crescent moon charm,
tail curled upright, disproportionate confidence for tiny size
```

### Стиль в одну строку
```
stylized 3D animation, warm amber studio lighting, shallow depth of field,
adult situational humor, expressive anthropomorphic character design
```

### Лайтинг в одну строку
```
warm amber key light 45° upper-right, soft fill from left, subtle rim separation,
shallow depth of field f/1.8, soft bokeh background, cinematic warm color grade
```

### Финальная строка (закрывает каждый промпт)
```
Maintain character appearance consistency throughout all shots. Smooth 3D animation,
clean fur texture detail, no distortion. No subtitles. No text in frame.
```
