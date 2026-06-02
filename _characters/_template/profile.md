# Персонаж: [ИМЯ]
> **Роль этого файла:** справочный профиль — читать для понимания персонажа и контекста сцен.
> **Полные промпты для генерации:** `[имя]_prompts_FULL.md`

---

## Визуальный профиль (из источника)
- Возраст:
- Пол:
- Этнос:
- Волосы: цвет, длина, скрыты ли под головным убором
- Глаза: цвет, выражение
- Телосложение:
- Одежда: перечислить все элементы
- Отличительные черты:
- Что НИКОГДА не присутствует (FORBIDDEN):

---

## STYLE LOCK (копировать в каждый сценный промпт дословно)

```
[Однострочное описание персонажа для Style Lock]
[Перечисление ключевых визуальных элементов]
NO [запрещённый элемент 1], NO [запрещённый элемент 2],
photorealistic, cinematic, cold blue atmosphere
```

---

## Мастер-кадры

### М1 — Погрудный портрет анфас (референс для всех портретов)

```
FORBIDDEN: NO [список запрещённого].

Studio portrait on pure white background.
Photorealistic cinematic portrait of [описание персонажа].
[Детали головы / лица / одежды верхней части тела]
Upper body portrait, face pointing DIRECTLY toward camera.
PURE WHITE BACKGROUND ONLY.
Shot on Canon EOS R5, 85mm lens f/1.8, soft cold north light,
4K resolution, ultra sharp focus. No text, no watermarks.
FORBIDDEN: [повтор запрета].
```

> Использовать как Image Prompt для всех портретных промптов. Формат: PNG.

### М2 — Полный рост анфас (главный мастер-кадр)

```
FORBIDDEN: NO [список запрещённого].

Photorealistic full body cinematic photo of [описание персонажа].
Full body visible from head to [toe/paw], facing camera directly.
[Детали — голова, лицо, тело, ноги, обувь]
FULL BODY HEAD TO [TOE/PAW] — [ноги/лапы] must be visible at bottom of frame.
DO NOT crop [legs/paws].
Neutral standing pose.
Snowy ground, overcast cold grey sky.
Shot on Canon EOS R5, 35mm lens f/2.8,
4K resolution, photorealistic, cinematic quality.
No text, no watermarks.
FORBIDDEN: [повтор запрета].
```

> Использовать как Image Prompt для всех промптов полного роста. Формат: PNG.

---

## BASE БЛОК (вставлять перед каждым ракурсным промптом)

```
FORBIDDEN: NO [список запрещённого].
Same character as reference image. Photorealistic full body,
[краткое описание персонажа], [год и место].
[Ключевые элементы внешности одной строкой].
FULL BODY HEAD TO [TOE/PAW] — [ноги/лапы] must be visible at bottom of frame.
DO NOT crop [legs/paws].
Neutral standing pose. Snowy ground, overcast cold grey sky. 4K, photorealistic, cinematic.
FORBIDDEN: NO [список запрещённого].
No [humans/props], no objects in frame except the character.
```

---

## Правила Seedream

```
1. Референс для портретов:    Image Prompt = М1 (формат PNG)
2. Референс для полного роста: Image Prompt = М2 (формат PNG)
3. Разрешение: 2K
4. [Специфичный запрет — например: NO straps / ONE DOG ONLY]
5. Белый фон Seedream игнорирует — использовать зимний/нейтральный фон
6. Полный рост: явно писать "FULL BODY HEAD TO TOE/PAW — [ноги/лапы] must be visible"
7. [Дополнительные правила, специфичные для персонажа]
```

---

## Эволюция образа по сценам

- Сцены 1–X: [описание состояния]
- Сцены X–Y: [описание состояния]
- Сцены Y–N: [описание состояния]

---

## Правила использования

- Полный рост → Image Prompt = М2 (PNG), Image Strength = 30–40%
- Портрет → Image Prompt = М1 (PNG), Image Strength = 30–40%
- Референс берётся только из сгенерированных и одобренных кадров
- Все одобренные URL записывать в `assets/registry.md`
