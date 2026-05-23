# Техника: Seamless Loop (Вирусная Петля)

> Видео, в котором конец точно совпадает с началом.
> Зрители смотрят снова и снова, алгоритм считает это досмотром — виральный эффект.

---

## Ключевые слова

```
seamless loop-ready motion
the ending state matches the beginning exactly
continuous loop, no visible cut point
the motion begins and ends in the same position
```

---

## Лучшие форматы для петли

### Материальная трансформация
```
[Объект в начальном состоянии A] →
[Трансформирующий агент покрывает его] →
[Открывает объект в состоянии A — идентичном началу]
seamless loop — end frame matches first frame exactly
```

**Примеры:**
- Стеклянный шар → ртуть → стеклянный шар
- Роза → огонь → роза (как будто не было огня)
- Статуэтка → золото → статуэтка
- Человек → песок → человек

### Цикличное движение
```
Character does [action that returns them to starting position]:
- walks forward and appears at starting point (Escher loop)
- turns around in a circle and faces original direction
- falls and lands back on their feet at start position
seamless loop
```

### Природный цикл
```
[Временное явление которое происходит и обращается]:
- волна накатывает и откатывает, оставляя берег точно таким же
- день → ночь → день (один кадр)
- цветок распускается и закрывается
```

---

## Готовые промпты

### Ртутная петля (базовый)
```
A glass sphere on a marble surface. Liquid mercury flows upward around the sphere,
engulfing it completely, then drains away to reveal the sphere unchanged.
Seamless loop-ready motion. Macro lens, studio lighting, dark background.
9:16 vertical.
```

### Трансформация персонажа в петле
```
A young woman stands on a dark stage, arms at sides. Liquid silver mercury rises from
the floor, flows upward across her body, engulfs her completely — she becomes a perfect
silver statue for two seconds. Mercury drains back downward. She stands unchanged.
Seamless loop — ending matches beginning exactly. Studio lighting. 10s / 9:16.
```

### Огонь-лёд петля
```
A red rose on a black surface. Flames engulf it — then the flames transform into frost,
ice crystals spreading across the petals. Then the ice melts back, revealing the rose
unchanged. Seamless loop. Studio lighting. 8s / 1:1.
```

### Природный/мистический
```
A candle flame burns on a stone altar. Wind blows from the left — flame bends —
wind builds — flame bends further — wind becomes a gale, flame flattens —
then reverses: gale to wind, wind to breeze, breeze fades, flame returns upright.
Seamless loop. 8s / 9:16.
```

---

## Советы по созданию петли

1. **Определи начальное и конечное состояние** — они должны быть идентичны
2. **Используй симметричное движение**: A → B → A работает лучше чем A → B → C → A
3. **Простые объекты работают лучше**: меньше деталей = проще совпасть в начале/конце
4. **Нейтральный фон**: тёмный или однотонный — меньше артефактов стыка
5. **Проверь**: если видео зациклить в видеоредакторе, должен быть незаметный переход
