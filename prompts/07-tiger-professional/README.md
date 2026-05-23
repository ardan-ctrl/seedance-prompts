# Тигр — Профессиональные Трансформации

> Формат: HOOK → КЛИЕНТ "ДО" → ТИГР ОЦЕНИВАЕТ → МОНТАЖ РАБОТЫ → РЕЗУЛЬТАТ → ТВИСТ
> Продолжительность: 15s / 9:16 / Pixar 3D animation

## Файлы промптов

| Файл | Профессия | Статус |
|------|----------|--------|
| [barber.md](barber.md) | Барбер | ✅ Работает |
| [dentist.md](dentist.md) | Стоматолог | ✅ Работает |
| [chef.md](chef.md) | Шеф-повар | Новый |
| [tailor.md](tailor.md) | Портной / Стилист | Новый |
| [mechanic.md](mechanic.md) | Автомеханик | Новый |
| [dog-groomer.md](dog-groomer.md) | Грумер | Новый |
| [tattoo-artist.md](tattoo-artist.md) | Тату-мастер | Новый |
| [personal-trainer.md](personal-trainer.md) | Личный тренер | Новый |
| [wedding-planner.md](wedding-planner.md) | Свадебный организатор | Новый |
| [lawyer.md](lawyer.md) | Адвокат | Новый |
| [interior-designer.md](interior-designer.md) | Дизайнер интерьеров | Новый |
| [dog-trainer.md](dog-trainer.md) | Дрессировщик | Новый |

## Формула монтажа

```
[0-2s] HOOK — "до"-деталь или реакция тигра
[2-4s] УСТАНОВКА — показываем клиента полностью, тигр оценивает
[4-11s] МОНТАЖ РАБОТЫ — быстрые нарезки инструментов/действий, ускоряющийся ритм
[11-13s] REVEAL — финальный образ клиента
[13-15s] ТВИСТ — комедийный финал
```

## Style block (вставляй в каждый промпт)
```
Pixar-quality cinematic 3D animation, adult Pixar aesthetic (Zootopia/Incredibles tone),
warm cinematic studio lighting, shallow depth of field, rich warm color grading.
Main character (@Image1): slim anthropomorphic tiger, orange-and-black striped,
walks upright on hind legs, cream chest, heavy-lidded arrogant expressive eyes, long tail.
Maintain exact character appearance throughout. 9:16 vertical, 15 seconds.
```

## Полная система персонажей

→ `/characters/tiger/TIGER_CHARACTER_SYSTEM.md`

Содержит:
- Стилевые формулы без запрещённых IP-имён (обходы Jimeng-фильтра)
- Полный character block Тигра и Котёнка
- @-тег синтаксис для 2D→3D конверсии референса
- Лайтинг-пресеты по профессиям
- Описания 8 профессиональных образов
- 15 архетипов клиентов "до"
- Copy-paste шаблоны промптов (EN + CN)
- Шаблон финального стоп-кадра серии
