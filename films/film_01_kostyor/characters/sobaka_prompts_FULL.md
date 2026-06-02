# Персонаж: Собака — Все промпты датасета
> **Роль этого файла:** операционный документ — копировать промпты в генератор, BASE-блок вставлять дословно.
> **Профиль персонажа и контекст сцен:** `sobaka.md`
> Фильм: «Костёр» (Jack London, To Build a Fire, 1902)
> Платформа: Syntx → NanoBanana Pro (основной) / Seedream 4 (альтернатива)
> Репозиторий: https://github.com/Andrey-don/aI-cinema
> Датасет: 23 кадра (план)

---

## ПРОФИЛЬ ПЕРСОНАЖА (из текста Лондона)

- Ездовая собака местной породы, **рослая**, внешне как дикий волк
- Шерсть **серая**, густая, покрытая инеем и кристаллами пара
- Морда **вся в инее до ресниц** — «вся морда, вплоть до ресниц, была густо покрыта инеем»
- Хвост **пушистый, волчий**, опущен вниз или поджат между лап
- Уши **острые, волчьи** — настороженные или прижатые (страх/подчинение)
- Главная эмоция: **инстинктивный страх перед морозом и жажда огня**
- Поза: **сгорбленная**, переминается с лапы на лапу
- Взгляд: **тоскливый, выжидательный** — ждёт огня от человека
- Отношения с человеком: **раб без привязанности** — подчинение без любви

---

## ПРАВИЛА SEEDREAM

```
1. Референс для портретов:  Image Prompt = С1 (погрудный портрет анфас)
2. Референс для полного роста: Image Prompt = С2 (полный рост анфас)
3. Разрешение: 2K
4. Запрет лишних животных: всегда начинать с FORBIDDEN блока — ONE DOG ONLY
5. Белый фон Seedream игнорирует — использовать зимний фон
6. Полный рост: явно писать "FULL BODY HEAD TO PAW — paws must be visible"
7. Луну не упоминать. Писать "cold blue ambient light"
8. Хвост: всегда явно указывать положение хвоста (lowered / tucked between legs)
9. Уши: всегда указывать состояние ушей (pricked alert / laid back flat)
10. Формат файла для референса: PNG (JPG не читается)
```

---

## БАЗОВЫЙ БЛОК (вставлять в начало каждого промпта)

```
FORBIDDEN: NO multiple dogs, NO wolves, NO puppies, NO dog pack.
ONE SINGLE DOG ONLY in the entire frame.

Same character as reference image. Photorealistic full body,
large gray sled dog, wolf-like appearance, Yukon 1902.
Large heavy-boned body, thick dense gray fur coat.
Entire face and muzzle completely covered in thick white hoarfrost up to eyelashes.
Frost crystals on chest fur and shoulders.
Bushy wolf-like tail hanging LOW — tail down, not raised, not wagging.
Sharp pointed wolf ears.
Amber-yellow eyes, watchful and fearful.
Hunched posture — body low, heavy, reluctant.
FULL BODY HEAD TO PAW — all four paws must be visible at bottom of frame.
DO NOT crop paws or legs.
Snowy ground, overcast cold grey sky. 4K, photorealistic, cinematic.
FORBIDDEN: NO multiple dogs, NO raised tail, NO happy expression.
No humans, no props, no objects in frame except the dog.
```

---

## МАСТЕР-КАДРЫ

### С1 — Погрудный портрет анфас (референс для портретов)

```
FORBIDDEN: NO multiple dogs, NO wolves, NO puppies.
ONE SINGLE DOG ONLY in the entire frame.

Studio portrait on pure white background.
Photorealistic cinematic close-up portrait of a large gray sled dog,
wolf-like appearance, Yukon wilderness 1902.
Large heavy head, broad forehead, strong muzzle pointing directly at camera.
Entire face — muzzle, cheeks, brow, eyelashes — completely covered
in dense thick white hoarfrost and ice crystals.
Amber-yellow eyes: wide open, fearful, watchful, filled with instinctive dread.
Sharp pointed wolf ears pricked upright and alert, both symmetrical.
Thick dense gray fur on neck and chest, frost-dusted and heavy.
Frost crystals on chest fur and chin fur.

Head-and-chest portrait, face pointing DIRECTLY toward camera.
Both eyes perfectly symmetrical to camera, nose centered in frame.
PURE WHITE BACKGROUND ONLY. No environment, no snow behind subject.
Shot on Canon EOS R5, 85mm lens f/1.8, soft cold north light,
4K resolution, ultra sharp focus. No text, no watermarks.

FORBIDDEN: NO multiple dogs, NO raised tail, NO happy expression,
NO tongue out, NO panting mouth open.
```

> ✅ Использовать как референс для всех портретов.

---

### С2 — Полный рост анфас (главный мастер-кадр)

```
FORBIDDEN: NO multiple dogs, NO wolves, NO puppies.
ONE SINGLE DOG ONLY in the entire frame.

Photorealistic full body cinematic photo of a large gray sled dog,
wolf-like appearance, Yukon wilderness 1902.
Full body visible from head to paw, standing, facing camera directly.

HEAD: large heavy wolf-like head, broad forehead, strong muzzle.
FACE: entire muzzle and face completely covered in dense white hoarfrost
up to eyelashes. Amber-yellow eyes watchful and fearful.
Sharp pointed wolf ears pricked upright.
BODY: large heavy-boned frame, thick dense gray fur coat,
frost crystals on shoulders, chest and back.
TAIL: bushy wolf-like tail hanging completely LOW — straight down,
between and behind the hind legs. Tail NOT raised, NOT curled, NOT wagging.
PAWS: four large paws flat on snowy ground, all four fully visible.
Hunched posture — back slightly rounded, head carried low and heavy.

Full body shot, all four paws fully visible, standing pose.
Snowy ground under paws, overcast cold grey sky background.
Shot on Canon EOS R5, 35mm lens f/2.8,
soft even cold north light, full figure sharp head to paw,
4K resolution, photorealistic, cinematic quality.
No text, no watermarks.

FORBIDDEN: NO multiple dogs, NO raised tail, NO happy expression,
NO tongue out, NO humans in frame.
```

> ✅ Главный мастер-кадр — референс для всех промптов полного роста.

---

## РАКУРСЫ ПОЛНОГО РОСТА
> Все с Image Prompt = С2, 2K

### Р1 — Профиль слева
```
[БАЗОВЫЙ БЛОК]
Dog facing left, left side profile view,
left side of body fully visible, right side hidden.
Left ear visible pricked forward, left amber eye visible.
Tail hanging low, visible in profile.
No humans, no props, no objects in frame except the dog.
```

### Р2 — Профиль справа
```
[БАЗОВЫЙ БЛОК]
Dog facing right, right side profile view,
right side of body fully visible, left side hidden.
Right ear visible pricked forward, right amber eye visible.
Tail hanging low, visible in profile.
No humans, no props, no objects in frame except the dog.
```

### Р3 — Вид сзади
```
[БАЗОВЫЙ БЛОК]
Dog facing away from viewer, back view,
back of head and ears visible from behind.
Full back fur coat visible — gray, thick, frost-dusted.
Bushy tail hanging straight down between hind legs, fully visible.
All four paws visible on snowy ground.
No humans, no props, no objects in frame except the dog.
```

### Р4 — Полоборота спереди слева
```
[БАЗОВЫЙ БЛОК]
Dog facing TOWARD the viewer, front of body fully visible.
Dog's nose and muzzle pointing toward LEFT edge of the frame.
Dog's RIGHT shoulder is closer to the camera.
Dog's LEFT shoulder is further from the camera.
Left side of frosted muzzle more visible to viewer.
Front of chest still visible, not a back view.
No humans, no props, no objects in frame except the dog.
```

### Р5 — Полоборота спереди справа
```
[БАЗОВЫЙ БЛОК]
Dog facing TOWARD the viewer, front of body fully visible.
Body turned slightly to dog's left, three-quarter front view.
Right shoulder slightly closer to camera, left shoulder further back.
Muzzle turned slightly left, both amber eyes clearly visible.
Front of chest and frosted fur dominant in frame.
Dog is NOT facing away — chest and front are facing the camera.
No humans, no props, no objects in frame except the dog.
```

### Р6 — Лежит в снегу, свернулась клубком (слева)
```
[БАЗОВЫЙ БЛОК — standing → lying curled]
FULL BODY — entire curled figure visible from head to paw.
Dog lying on snow, body curled into a tight ball,
nose tucked toward hind legs, tail wrapped around body covering nose.
Classic wolf sleep position, conserving warmth instinctively.
Left side profile view, facing left.
All four paws tucked close to body, barely visible.
Frost and snow settling on back fur and head.
Expression of reluctant rest — ears flat, eyes half open and wary.
Snowy ground, overcast cold grey sky.
No humans, no props, no objects in frame except the dog.
```

### Р7 — Лежит в снегу, свернулась клубком (справа)
```
[БАЗОВЫЙ БЛОК — standing → lying curled]
FULL BODY — entire curled figure visible from head to paw.
Dog lying on snow, body curled into a tight ball,
nose tucked toward hind legs, tail wrapped around body covering nose.
Classic wolf sleep position, conserving warmth instinctively.
Right side profile view, facing right.
All four paws tucked close to body, barely visible.
Frost and snow settling on back fur and head.
Expression of reluctant rest — ears flat, eyes half open and wary.
Snowy ground, overcast cold grey sky.
No humans, no props, no objects in frame except the dog.
```

---

## ПОРТРЕТЫ ПО ПЛЕЧИ
> Все с Image Prompt = С1, 2K

### П1 — Портрет анфас
```
FORBIDDEN: NO multiple dogs. ONE SINGLE DOG ONLY.
Same character as reference image. Photorealistic cinematic portrait,
large gray sled dog, wolf-like, Yukon 1902.
Large heavy wolf-like head, broad forehead, strong muzzle.
Entire face and muzzle completely covered in dense white hoarfrost
up to eyelashes — heavy frost crystals on every surface.
Amber-yellow eyes wide open, looking DIRECTLY at camera.
Sharp pointed wolf ears both pricked symmetrically upright.
Thick gray frosted fur on neck and chest.
Head-and-chest portrait, muzzle pointing DIRECTLY toward camera.
Both eyes perfectly symmetrical to camera, nose centered in frame.
Cold overcast sky background, soft diffused north light.
Shot on Canon EOS R5, 85mm lens f/1.8,
sharp fur texture, visible frost detail, 4K, ultra sharp focus.
No humans, no props, no objects in frame except the dog.
FORBIDDEN: NO multiple dogs, NO raised tail, NO tongue out.
```

### П2 — Портрет полоборота вправо
```
FORBIDDEN: NO multiple dogs. ONE SINGLE DOG ONLY.
Same character as reference image. Photorealistic cinematic portrait,
large gray sled dog, wolf-like, Yukon 1902.
Large heavy wolf-like head, entire muzzle and face covered in dense hoarfrost.
Amber-yellow eyes sharp and wary. Ears pricked upright.
Thick gray frosted fur on neck and chest.

Head-and-chest portrait, close-up.
ENTIRE HEAD AND BODY turned to the right — head and shoulders
all pointing right together as one unit, NOT just the head alone.
Right side of frosted muzzle visible in near-profile.
Both amber eyes visible but right eye more prominent.
Right ear fully visible, left ear partially visible behind.

Cold overcast sky background, soft diffused north light.
Shot on Canon EOS R5, 85mm lens f/1.8,
sharp fur texture, visible frost detail, 4K, ultra sharp focus.
No humans, no props, no objects in frame except the dog.
FORBIDDEN: NO multiple dogs, NO tongue out, NO happy expression.
```

---

## ЭМОЦИИ
> Все с Image Prompt = С1, 2K

### Э1 — Инстинктивный страх перед морозом
```
FORBIDDEN: NO multiple dogs. ONE SINGLE DOG ONLY.
Same character as reference image. Photorealistic cinematic portrait,
large gray sled dog, wolf-like, Yukon 1902.
Entire face and muzzle covered in dense white hoarfrost up to eyelashes.
Thick frosted gray fur on neck and chest.

Amber-yellow eyes wide open with primal instinctive fear —
pupils large and dark, whites of eyes slightly visible at edges.
Ears pressed back flat against the skull, both ears laid back in fear.
Head lowered and pulled in toward chest, body hunched.
Expression of a dog that KNOWS the cold is deadly —
ancient animal dread, not learned but inherited.

Head-and-chest portrait, face pointing slightly downward and toward camera.
Cold overcast sky background, soft diffused north light.
Shot on Canon EOS R5, 85mm lens f/1.8,
sharp fur texture, 4K, ultra sharp focus.
No humans, no props, no objects in frame except the dog.
FORBIDDEN: NO multiple dogs, NO raised ears, NO alert expression.
```

### Э2 — Тоска по огню / ожидание
```
FORBIDDEN: NO multiple dogs. ONE SINGLE DOG ONLY.
Same character as reference image. Photorealistic cinematic portrait,
large gray sled dog, wolf-like, Yukon 1902.
Entire face and muzzle covered in dense white hoarfrost up to eyelashes.
Thick frosted gray fur on neck and chest.

Amber-yellow eyes soft and yearning, deeply mournful —
the look of a creature waiting desperately for warmth that may never come.
Ears slightly back, relaxed but sad, not fully alert.
Head lowered slightly, expression of deep patient longing.
A dog that has known fire and craves it with its whole being.

Head-and-chest portrait, face pointing DIRECTLY toward camera.
Cold overcast sky background, soft diffused north light.
Shot on Canon EOS R5, 85mm lens f/1.8,
sharp fur texture, 4K, ultra sharp focus.
No humans, no props, no objects in frame except the dog.
FORBIDDEN: NO multiple dogs, NO happy expression, NO tongue out.
```

### Э3 — Настороженность / подозрение
```
FORBIDDEN: NO multiple dogs. ONE SINGLE DOG ONLY.
Same character as reference image. Photorealistic cinematic portrait,
large gray sled dog, wolf-like, Yukon 1902.
Entire face and muzzle covered in dense white hoarfrost up to eyelashes.
Thick frosted gray fur on neck and chest.

Amber-yellow eyes sharp and narrowed with deep suspicion,
pupils focused and hard, staring with wolf-like wariness.
Both ears pricked fully upright and rotated slightly forward —
maximum alert, reading the situation with animal intelligence.
Head slightly raised, neck muscles tense.
The expression of a dog that senses danger it cannot yet name.

Head-and-chest portrait, face pointing DIRECTLY toward camera.
Cold overcast sky background, soft diffused north light.
Shot on Canon EOS R5, 85mm lens f/1.8,
sharp fur texture, 4K, ultra sharp focus.
No humans, no props, no objects in frame except the dog.
FORBIDDEN: NO multiple dogs, NO tongue out, NO fearful expression.
```

### Э4 — Покорность / подчинение
```
FORBIDDEN: NO multiple dogs. ONE SINGLE DOG ONLY.
Same character as reference image. Photorealistic cinematic portrait,
large gray sled dog, wolf-like, Yukon 1902.
Entire face and muzzle covered in dense white hoarfrost up to eyelashes.
Thick frosted gray fur on neck and chest.

Amber-yellow eyes downcast, lowered, avoiding direct gaze —
the look of a slave that obeys without affection.
Both ears pressed fully flat against skull in complete submission.
Head bowed low and heavy, neck curved downward.
No love in the expression, no trust — only unwilling compliance.
A creature that follows because it must, not because it wants to.

Head-and-chest portrait, head angled slightly downward toward ground.
Cold overcast sky background, soft diffused north light.
Shot on Canon EOS R5, 85mm lens f/1.8,
sharp fur texture, 4K, ultra sharp focus.
No humans, no props, no objects in frame except the dog.
FORBIDDEN: NO multiple dogs, NO happy expression, NO tongue out.
```

### Э5 — Запах смерти / ужас
```
FORBIDDEN: NO multiple dogs. ONE SINGLE DOG ONLY.
Same character as reference image. Photorealistic cinematic portrait,
large gray sled dog, wolf-like, Yukon 1902.
Entire face and muzzle covered in dense white hoarfrost up to eyelashes.
Thick frosted gray fur on neck and chest.

Amber-yellow eyes wide with primal animal terror — pupils huge and black,
the raw horror of an animal that has smelled death for the first time.
Nostrils flared wide, muzzle slightly wrinkled, fur on neck raised.
Ears pressed hard back and flat against the skull.
Head pulled back and away, body leaning backward in retreat.
The expression of a dog backing away from a dead body in the snow.

Head-and-chest portrait, head pulled back slightly from camera.
Cold overcast sky background, soft diffused north light.
Shot on Canon EOS R5, 85mm lens f/1.8,
sharp fur texture, 4K, ultra sharp focus.
No humans, no props, no objects in frame except the dog.
FORBIDDEN: NO multiple dogs, NO calm expression.
```

---

## ОСВЕЩЕНИЕ
> Полный рост с Image Prompt = С2; портреты с С1, 2K

### О1 — Свет костра, полный рост
```
FORBIDDEN: NO multiple dogs. ONE SINGLE DOG ONLY.
Same character as reference image. Photorealistic full body cinematic photo,
large gray sled dog, wolf-like, Yukon 1902.
Entire face covered in hoarfrost, thick gray fur, tail hanging low.
FULL BODY HEAD TO PAW — all four paws must be visible.

LIGHTING: campfire light only, warm orange and amber glow
coming from in front of and below the dog.
Face, chest and front legs lit with flickering warm orange light.
Deep cold shadows on sides and back of body.
Dog's eyes reflecting amber firelight — glowing warm in the orange light.
Dark night background, only darkness behind dog.
Frost on fur lit golden by firelight.
Dog positioned close to fire glow, body relaxed but watchful.
Snowy ground visible at paws, lit by firelight.

Shot on Canon EOS R5, 35mm lens f/2.8, 4K, photorealistic, cinematic.
No humans, no props, no objects in frame except the dog and fire glow.
FORBIDDEN: NO multiple dogs, NO fire source visible in frame.
```

### О2 — Свет костра, портрет
```
FORBIDDEN: NO multiple dogs. ONE SINGLE DOG ONLY.
Same character as reference image. Photorealistic cinematic portrait,
large gray sled dog, wolf-like, Yukon 1902.
Entire muzzle and face covered in dense hoarfrost up to eyelashes.
Thick frosted gray neck fur.

LIGHTING: campfire firelight only.
Warm orange and amber light falling on face and chest from below.
One side of frosted muzzle lit warm amber, other side in cold shadow.
Amber-yellow eyes glowing richly in the firelight — deep and warm.
Ice crystals on muzzle-fur lit like tiny orange sparks.
Dark background, fire source not visible in frame.

Head-and-chest portrait, face turned slightly toward the light source.
Shot on Canon EOS R5, 85mm lens f/1.8, 4K, photorealistic, cinematic.
No humans, no props, no objects in frame except the dog.
FORBIDDEN: NO multiple dogs, NO fire source visible in frame.
```

### О3 — Сумерки / гибель хозяина
```
FORBIDDEN: NO multiple dogs. ONE SINGLE DOG ONLY.
Same character as reference image. Photorealistic full body cinematic photo,
large gray sled dog, wolf-like, Yukon 1902.
Entire face covered in hoarfrost, thick gray fur, tail hanging low.
FULL BODY HEAD TO PAW — all four paws must be visible.

LIGHTING: deep twilight, last cold light of the dying day.
Cold blue-grey ambient light, no warmth anywhere.
Dark indigo and steel-blue sky, stars beginning to appear above.
Dog's gray fur blending with the darkening cold world.
No fire, no warmth, only the vast cold dark closing in.
Dog standing alone in the last light, howling or about to leave.

Shot on Canon EOS R5, 35mm lens f/2.8, 4K, photorealistic, cinematic.
No humans, no props, no objects in frame except the dog.
FORBIDDEN: NO multiple dogs, NO warm light, NO fire.
```

---

## ДЕЙСТВИЯ И ПОЗЫ
> Полный рост с Image Prompt = С2, 2K

### Д1 — Идёт понуро за человеком
```
FORBIDDEN: NO multiple dogs. ONE SINGLE DOG ONLY.
Same character as reference image. Photorealistic full body cinematic photo,
large gray sled dog, wolf-like, Yukon 1902.
Entire face covered in hoarfrost, thick gray fur, tail hanging low.
FULL BODY HEAD TO PAW — all four paws visible.

Dog walking slowly, all four legs in mid-step motion.
Head carried LOW — below the level of the shoulders, hanging heavy.
Tail hanging COMPLETELY DOWN, dragging low between hind legs.
Body posture reluctant and oppressed — a dog forced to walk in deadly cold.
Ears slightly back, eyes downcast.
Direction of movement: dog walking toward RIGHT side of frame.
Left side profile view showing full walking posture.

Snowy ground with visible paw prints behind the dog.
Overcast cold grey sky. Soft cold north light.
Shot on Canon EOS R5, 35mm lens f/2.8, 4K, photorealistic, cinematic.
No humans, no props, no objects in frame except the dog.
FORBIDDEN: NO multiple dogs, NO raised tail, NO alert happy posture.
```

### Д2 — Переминается с лапы на лапу у костра
```
FORBIDDEN: NO multiple dogs. ONE SINGLE DOG ONLY.
Same character as reference image. Photorealistic full body cinematic photo,
large gray sled dog, wolf-like, Yukon 1902.
Entire face covered in hoarfrost, thick gray fur, tail hanging low.
FULL BODY HEAD TO PAW — all four paws visible.

Dog standing still but shifting weight — one front paw raised slightly
off the snow, body weight on three legs, in motion of shifting restlessly.
Tail hanging low. Head oriented toward an off-camera fire source.
Body hunched slightly, drawn toward the warmth.
Ears pricked forward toward the fire, eyes fixed on the heat source.
Front paw lifted mid-step, caught in the act of nervous shifting.

Warm orange glow from off-camera left lighting the dog's face and chest.
Snowy ground, dark cold background.
Shot on Canon EOS R5, 35mm lens f/2.8, 4K, photorealistic, cinematic.
No humans, no props, no objects in frame except the dog.
FORBIDDEN: NO multiple dogs, NO fire visible in frame, NO raised tail.
```

### Д3 — Выкусывает лёд из лап
```
FORBIDDEN: NO multiple dogs. ONE SINGLE DOG ONLY.
Same character as reference image. Photorealistic full body cinematic photo,
large gray sled dog, wolf-like, Yukon 1902.
Entire face covered in hoarfrost, thick gray fur.
FULL BODY HEAD TO PAW — entire figure visible.

Dog lying down on snow, head bent sharply downward,
mouth actively chewing and biting at one of its front paws.
One front paw raised and held in mouth — dog biting out ice between toes.
Other three legs relaxed on snowy ground.
Body curled slightly inward around the raised paw.
Frost on the paw fur clearly visible — the reason for the action.
Focused expression — entirely absorbed in removing the painful ice.
Ears back slightly, eyes focused on the paw.

Snowy ground, overcast cold grey sky.
Shot on Canon EOS R5, 35mm lens f/2.8, 4K, photorealistic, cinematic.
No humans, no props, no objects in frame except the dog.
FORBIDDEN: NO multiple dogs, NO human hands in frame.
```

### Д4 — Сидит и воет под звёздами (финал)
```
FORBIDDEN: NO multiple dogs. ONE SINGLE DOG ONLY.
Same character as reference image. Photorealistic full body cinematic photo,
large gray sled dog, wolf-like, Yukon 1902.
Entire face covered in hoarfrost, thick gray fur, tail tucked around paws.
FULL BODY HEAD TO PAW — entire seated figure visible.

Dog sitting upright in snow, tail wrapped forward around front paws.
Head tilted UPWARD toward the night sky, muzzle raised high,
mouth open in a long mournful howl — throat stretched toward the stars.
Eyes closed or half-closed in the act of howling.
Frost-covered chest exposed as head tilts back.
Body still and heavy, seated perfectly still except for the raised head.

SETTING: deep cold night, vast dark sky filled with bright sharp stars.
Brilliant Yukon winter stars, cold blue-black sky above.
Dog alone in the dark, no fire, no human.
Cold blue-white starlight on frost-covered fur.
Snowy ground around the seated dog, complete darkness beyond.

Shot on Canon EOS R5, 35mm lens f/2.8, 4K, photorealistic, cinematic.
No humans, no props, no objects in frame except the dog.
FORBIDDEN: NO multiple dogs, NO warm light, NO fire.
```

---

## ИТОГОВЫЙ СТАТУС ДАТАСЕТА

| # | Категория | Кол-во | Статус |
|---|-----------|--------|--------|
| С1, С2 | Мастер-кадры | 2 | ⏳ |
| Р1–Р7 | Ракурсы полного роста | 7 | ⏳ |
| П1–П2 | Портреты | 2 | ⏳ |
| Э1–Э5 | Эмоции | 5 | ⏳ |
| О1–О3 | Освещение | 3 | ⏳ |
| Д1–Д4 | Действия и позы | 4 | ⏳ |
| **Итого** | | **23** | ⏳ |

---

## СЛЕДУЮЩИЕ ШАГИ

1. ⏳ Сгенерировать С1 и С2 — одобрить мастер-кадры
2. ⏳ Снять датасет 23 кадра в Seedream 4
3. ⏳ Убрать фон у всех кадров → **rembg** (пакетная обработка)
   ```bash
   rembg p E:\Films_AI\London\full_body_dog\input\ E:\Films_AI\London\full_body_dog\output\
   ```
4. ⏳ Обучить LoRA → `@syntxaibot → Flux.1 → Обучить Flux.1` → название: `taiga_dog`
5. ⏳ Тест LoRA: сила 1.0–1.2, совместить с `bonfire_man`

---

## КОНТЕКСТ ДЛЯ НОВОГО ЧАТА

```
Проект AI-Cinema, фильм «Костёр» по Джеку Лондону.
Платформа Syntx, модель Seedream 4.
Персонаж Человек — датасет готов (35 кадров), LoRA обучена: bonfire_man, сила 1.2.
Персонаж Собака — датасет создаётся (23 кадра), LoRA будет: taiga_dog.
Все промпты собаки: films/film_01_kostyor/characters/sobaka_prompts_FULL.md
Описание из рассказа: крупная серая ездовая собака, волкоподобная,
хвост опущен, янтарные глаза, инстинктивный страх перед морозом,
вся морда в инее до ресниц, пушистый волчий хвост.
Репозиторий: https://github.com/Andrey-don/aI-cinema
```

---

*Источник: рабочий журнал Claude + метод Дротенко AI-продакшн*
