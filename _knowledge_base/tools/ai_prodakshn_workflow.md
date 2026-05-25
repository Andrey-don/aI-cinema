# AI-продакшн видео — Общий воркфлоу
> Источник: курс Дротенко. Читать при старте новой сцены или нового фильма.

---

## Главный принцип: STYLE LOCK

**Проблема:** каждый промпт генерирует немного разного персонажа.
**Решение:** в каждый промпт без изменений копируется блок фиксации стиля — Style Lock.

```
STYLE LOCK = описание персонажа + визуальный стиль
             одинаковое для ВСЕХ сцен без исключения
```

### Структура любого промпта:
```
[STYLE LOCK] + [ОПИСАНИЕ КОНКРЕТНОЙ СЦЕНЫ]
```

---

## Этап 1 — Создание персонажа

1. Описать персонажа детально: внешность, характер, отличительные черты
2. Сгенерировать на **белом фоне, без окружения** — это мастер-кадр
3. Белый фон обязателен: он используется как референс во всех следующих сценах
4. Сохранить URL / файл → это основа всего фильма

**Важно:** персонаж создаётся один раз в самом начале. Всё дальнейшее строится на нём.

---

## Этап 2 — Изображения по сценам

- Каждая сцена = отдельное изображение
- Продолжительность сцены: **6–10 секунд** (под генерацию видео)
- В каждом промпте — STYLE LOCK + описание сцены
- Референс персонажа (белый фон) прикладывается к каждой генерации

**Структура промпта изображения:**
```
[STYLE LOCK]
[Локация, обстановка]
[Что делает персонаж, поза, эмоция]
[Ракурс камеры, план]
[Атмосфера сцены]
```

---

## Этап 3 — Видео по сценам

- Каждое изображение → отдельный видеопромпт
- 6–10 секунд на сцену → потом монтаж в единое видео
- В видеопромпте тоже есть STYLE BLOCK (аналог Style Lock для видео)

**Структура видеопромпта:**
```
STYLE BLOCK:
  character consistency, reference image attached,
  visual style, colors, lighting, dynamics, mood, camera rules

SCENE DESCRIPTION:
  scene number, duration (6-10 sec),
  location, character action, emotion,
  movement type, camera framing, overall feeling
```

---

## Шаблон STYLE BLOCK для видео

```
Character consistency: same main character appearance in all scenes,
Character reference: use attached reference image as main source,
Style type: [2D / 3D / photorealistic — выбрать],
Visual style: [описание стиля],
Colors: [цветовая палитра],
Lighting: [тип освещения],
Dynamics: [тип движений],
Mood: [настроение],
Camera: [правила камеры],
Quality: [требования к качеству]
```

---

## Адаптация для «Костра» (фотореализм)

Style Lock для нашего проекта будет выглядеть так:

```
[ЧЕЛОВЕК — STYLE LOCK]
Rugged weathered man, 35 years old, dark hair hidden under fur hat,
reddish beard heavily frosted with amber ice, heavy fur parka,
thick mittens, moccasins, unimaginative but determined expression,
photorealistic, cinematic, cold blue atmosphere, no stylization

[СОБАКА — STYLE LOCK]
Large grey wolf-like sled dog, thick fur, tail hanging low,
cautious amber eyes, instinctive fear posture,
photorealistic, cold blue atmosphere
```

---

## Ключевые правила (применять всегда)

1. Один персонаж = один мастер-кадр на белом фоне → сохранить
2. Style Lock — копировать в каждый промпт без изменений
3. Промпты писать на **английском** — результат стабильнее
4. Сцена = изображение → видео (6–10 сек) → следующая сцена
5. При несоответствии стиля — не менять Style Lock, менять описание сцены
