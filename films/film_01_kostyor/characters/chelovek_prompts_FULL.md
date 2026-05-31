# Персонаж: Человек — Все промпты датасета
> Фильм: «Костёр» (Jack London, To Build a Fire, 1902)
> Платформа: Syntx → C-Dream 4 (Seedream 4)
> Репозиторий: https://github.com/Andrey-don/aI-cinema
> Датасет: 35 кадров ✅

---

## ПРОФИЛЬ ПЕРСОНАЖА (из текста Лондона)

- Мужчина ~35 лет, американец, новичок в Клондайке
- Рыжая густая борода с янтарно-жёлтой ледяной коркой («плотная и желтая, как янтарь»)
- Широкие скулы, красные обветренные
- Большой нос, «вызывающе выставленный навстречу морозу»
- Голубые глаза — зоркие, упрямые, без воображения
- Идёт налегке — **никаких ремней, рюкзаков, снаряжения**
- Одежда: меховая парка, шапка-ушанка с наушниками, рукавицы, мокасины, толстые носки/гетры

---

## ПРАВИЛА SEEDREAM

```
1. Референс для портретов:  Image Prompt = М1 (погрудный портрет анфас)
2. Референс для полного роста: Image Prompt = М2 (полный рост анфас)
3. Разрешение: 2K
4. Запрет ремней: всегда начинать с FORBIDDEN блока
5. Белый фон Seedream игнорирует — использовать зимний фон
6. Направление: "Character's nose pointing toward LEFT/RIGHT edge of the frame"
7. Полный рост: явно писать "FULL BODY HEAD TO TOE — feet must be visible"
8. Луну не упоминать — рисует диск на шапке. Писать "cold blue ambient light"
9. Огонь в портрете: добавлять "Fire source not visible in frame"
10. Формат файла для референса: PNG (JPG не читается)
```

---

## БАЗОВЫЙ БЛОК (вставлять в начало каждого промпта)

```
FORBIDDEN: NO straps, NO harness, NO backpack, NO bag, NO belt,
NO buckles, NO sling, NO shoulder strap of any kind.

Same character as reference image. Photorealistic full body,
rugged weathered American man 35 years old, Yukon 1902.
Fur hat with earflaps, reddish beard with amber ice icicles,
red chapped cheeks, blue-grey eyes, heavy fur parka,
thick fur mittens, wool leg wraps, moccasins.
FULL BODY HEAD TO TOE — feet and moccasins must be visible at bottom of frame.
DO NOT crop legs or feet.
Snowy ground, overcast cold grey sky. 4K, photorealistic, cinematic.
FORBIDDEN: NO straps, NO harness, NO equipment on body.
No cameras, no props, no objects in frame except the character.
```

---

## МАСТЕР-КАДРЫ

### М1 — Погрудный портрет (референс для портретов и эмоций)

```
FORBIDDEN: NO straps, NO harness, NO backpack, NO bag, NO belt,
NO buckles, NO sling, NO shoulder strap of any kind.

Studio portrait on pure white background.
Photorealistic cinematic portrait of a rugged weathered American man,
35 years old, Yukon 1902.
Heavy thick fur hat with wide earflaps, all hair completely hidden.
Full reddish beard encrusted with dense amber-yellow ice crystals
and icicles, beard long and stiff with frozen strands.
Wide prominent cheekbones raw red, large nose exposed to cold.
Pale grey-blue eyes: alert, stubborn, determined. Mouth closed.
Simple heavy fur parka — plain solid fur coat, smooth fur surface only,
absolutely nothing attached to the coat, no hardware, no metal parts.
The man carries nothing. His hands are empty.
Upper body portrait, three-quarter angle, facing slightly left.
PURE WHITE BACKGROUND ONLY. No environment, no sky, no snow behind subject.
Shot on Canon EOS R5, 85mm lens f/1.8, soft cold north light,
4K resolution, ultra sharp focus. No text, no watermarks.

FORBIDDEN ELEMENTS: straps, harness, backpack, bag, equipment,
buckles, suspenders, chest rig, shoulder rig, sling, belt, clips.
```

> ✅ Одобрен. Использовать как референс для всех портретов и эмоций.

---

### М2 — Полный рост анфас (главный мастер-кадр)

```
FORBIDDEN: NO straps, NO harness, NO backpack, NO bag, NO belt, NO buckles.

Photorealistic full body cinematic photo of a rugged weathered American man,
35 years old, Yukon wilderness 1902.
Full body visible from head to toe, standing upright, facing camera directly,
arms relaxed at sides, hands hanging naturally, nothing held in hands.

HEAD: heavy thick fur hat with wide earflaps, all hair completely hidden.
FACE: full reddish beard with dense amber-yellow ice crystals and icicles
hanging down, long frozen strands, wide red chapped cheekbones,
large nose, pale grey-blue eyes, determined expression, mouth closed.
COAT: simple heavy oversized fur parka reaching mid-thigh,
plain smooth fur surface, no hardware, no attachments.
HANDS: thick heavy fur-lined mittens on both hands, hanging at sides.
LEGS AND FEET: thick wool trousers, traditional Yukon moccasins
reaching mid-calf, thick wool socks visible above moccasins.
All clothing frost-dusted and heavily worn.

Full body shot, feet fully visible, neutral standing pose.
Snowy ground under feet, overcast cold grey sky background.
Shot on Canon EOS R5, 35mm lens f/2.8,
soft even cold north light, full figure sharp head to toe,
4K resolution, photorealistic, cinematic quality.
No text, no watermarks.

REMINDER: absolutely no straps, harness or equipment on body or coat.
```

> ✅ Одобрен. **Главный мастер-кадр** — референс для всех промптов полного роста.

---

## РАКУРСЫ ПОЛНОГО РОСТА
> Все с Image Prompt = М2, 2K

### Р1 — Профиль слева
```
[БАЗОВЫЙ БЛОК]
Character facing left, left side profile view,
left side of body fully visible, right side hidden.
No cameras, no props, no objects in frame except the character.
```

### Р2 — Профиль справа
```
[БАЗОВЫЙ БЛОК]
Character facing right, right side profile view,
right side of body fully visible, left side hidden.
No cameras, no props, no objects in frame except the character.
```

### Р3 — Вид сзади
```
[БАЗОВЫЙ БЛОК]
Character facing away from viewer, back view,
back of fur hat visible, back of parka fully visible,
back of mittens hanging at sides, heels of moccasins visible.
No cameras, no props, no objects in frame except the character.
```

### Р4 — Полоборота спереди слева
```
[БАЗОВЫЙ БЛОК]
Character facing TOWARD the viewer, front of body fully visible.
Character's nose and face pointing toward LEFT edge of the frame.
Character's RIGHT shoulder is closer to the camera.
Character's LEFT shoulder is further from the camera.
Left side of beard and left cheek more visible to viewer.
Front of parka still visible, not a back view.
No cameras, no props, no objects in frame except the character.
```

### Р5 — Полоборота спереди справа
```
[БАЗОВЫЙ БЛОК]
Character facing TOWARD the viewer, front of body fully visible.
Body turned slightly to character's left, three-quarter front view.
Right shoulder slightly closer to camera, left shoulder further back.
Face turned slightly left, both eyes clearly visible.
Front of parka dominant in frame.
Character is NOT facing away — chest and front are facing the camera.
No cameras, no props, no objects in frame except the character.
```

### Р6 — Присел, вид слева
```
[БАЗОВЫЙ БЛОК — standing → crouching]
FULL BODY — entire crouching figure visible head to toe including feet.
Character in a deep squat position, knees bent, body lowered close to ground.
Left side profile view — character facing left, left side of body visible.
Arms resting naturally on knees, mittens visible.
Parka draping down around the crouched legs.
Moccasins and feet flat on snowy ground, fully visible.
Neutral expression, looking forward while crouching.
No cameras, no props, no objects in frame except the character.
```

### Р7 — Присел, вид справа
```
[БАЗОВЫЙ БЛОК — standing → crouching]
FULL BODY — entire crouching figure visible head to toe including feet.
Character in a deep squat position, knees bent, body lowered close to ground.
Right side profile view — character facing right, right side of body visible.
Arms resting naturally on knees, mittens visible.
Parka draping down around the crouched legs.
Moccasins and feet flat on snowy ground, fully visible.
Neutral expression, looking forward while crouching.
No cameras, no props, no objects in frame except the character.
```

---

## ПОРТРЕТЫ ПО ПЛЕЧИ
> Все с Image Prompt = М1, 2K

### П1 — Портрет анфас
```
FORBIDDEN: NO straps, NO harness, NO backpack, NO bag, NO belt, NO buckles.
Same character as reference image. Photorealistic cinematic portrait,
rugged weathered American man 35 years old, Yukon 1902.
Fur hat with wide earflaps, all hair hidden under hat.
Full reddish beard with dense amber-yellow ice crystals and icicles,
frozen strands hanging from beard and mustache.
Wide prominent cheekbones raw red from frostbite, freckled weathered skin.
Pale grey-blue eyes sharp and alert, looking directly at camera.
Mouth closed, determined expression.
Heavy fur parka with snow-covered fur collar, frost on shoulders.
Upper body portrait, face pointing DIRECTLY toward camera, full anface view.
Both eyes perfectly symmetrical to camera, nose centered in frame.
Cold overcast sky background, soft diffused north light.
Shot on Canon EOS R5, 85mm lens f/1.8,
natural skin texture, visible pores, 4K, ultra sharp focus.
No cameras, no props, no objects in frame except the character.
FORBIDDEN: NO straps, NO harness, NO equipment on body.
```

### П2 — Портрет полоборота вправо
```
FORBIDDEN: NO straps, NO harness, NO backpack, NO bag, NO belt,
NO buckles, NO sling, NO shoulder strap of any kind.

Same character as reference image. Photorealistic cinematic portrait,
rugged weathered American man 35 years old, Yukon 1902.
Fur hat with wide earflaps, all hair hidden under hat.
Full reddish beard with dense amber-yellow ice crystals and icicles.
Wide prominent cheekbones raw red, freckled weathered skin.
Pale grey-blue eyes sharp and alert. Mouth closed, determined expression.
Heavy fur parka with snow-covered fur collar, frost on shoulders.
Plain smooth fur coat, absolutely nothing attached to it.

Upper body portrait, close-up.
ENTIRE UPPER BODY turned to the right — shoulders, torso and head
all pointing right together as one unit, NOT just the head alone.
Character's whole body angled right, left shoulder forward toward camera.
Face and shoulders aligned in the same direction, facing right.
Right side of face and right cheek visible in profile.
Both eyes visible but right eye more prominent.

Cold overcast sky background, soft diffused north light.
Shot on Canon EOS R5, 85mm lens f/1.8,
natural skin texture, visible pores, 4K, ultra sharp focus.
No cameras, no props, no objects in frame except the character.
FORBIDDEN: NO straps, NO harness, NO equipment on body or coat.
```

---

## ЭМОЦИИ
> Все с Image Prompt = М1, 2K

### Э1 — Страх ✅
```
FORBIDDEN: NO straps, NO harness, NO backpack, NO bag, NO belt,
NO buckles, NO sling, NO shoulder strap of any kind.

Same character as reference image. Photorealistic cinematic portrait,
rugged weathered American man 35 years old, Yukon 1902.
Fur hat with wide earflaps, all hair hidden under hat.
Full reddish beard with dense amber-yellow ice crystals and icicles,
frozen strands hanging from beard and mustache.
Wide prominent cheekbones raw red from frostbite, freckled weathered skin.
Pale grey-blue eyes wide open with terror, pupils dilated, eyebrows raised.
Mouth slightly open, expression of sudden fear and shock.
Heavy fur parka with snow-covered fur collar, frost on shoulders.
Plain smooth fur coat, absolutely nothing attached to it.
Upper body portrait, face pointing DIRECTLY toward camera.
Cold overcast sky background, soft diffused north light.
Shot on Canon EOS R5, 85mm lens f/1.8,
natural skin texture, visible pores, 4K, ultra sharp focus.
No cameras, no props, no objects in frame except the character.
FORBIDDEN: NO straps, NO harness, NO equipment on body or coat.
```

### Э2 — Тревога / дурное предчувствие ✅
```
FORBIDDEN: NO straps, NO harness, NO backpack, NO bag, NO belt,
NO buckles, NO sling, NO shoulder strap of any kind.

Same character as reference image. Photorealistic cinematic portrait,
rugged weathered American man 35 years old, Yukon 1902.
Fur hat with wide earflaps, all hair hidden under hat.
Full reddish beard with dense amber-yellow ice crystals and icicles,
frozen strands hanging from beard and mustache.
Wide prominent cheekbones raw red from frostbite, freckled weathered skin.
Pale grey-blue eyes wide with deep worry and dread,
eyebrows pulled together and raised, forehead deeply furrowed with creases.
Mouth closed but lips trembling slightly, chin tense.
Expression of a man who realizes something has gone terribly wrong.
Heavy fur parka with snow-covered fur collar, frost on shoulders.
Plain smooth fur coat, absolutely nothing attached to it.
Upper body portrait, face pointing DIRECTLY toward camera.
Cold overcast sky background, soft diffused north light.
Shot on Canon EOS R5, 85mm lens f/1.8,
natural skin texture, visible pores, 4K, ultra sharp focus.
No cameras, no props, no objects in frame except the character.
FORBIDDEN: NO straps, NO harness, NO equipment on body or coat.
```

### Э3 — Решимость / упрямство ✅
```
FORBIDDEN: NO straps, NO harness, NO backpack, NO bag, NO belt,
NO buckles, NO sling, NO shoulder strap of any kind.

Same character as reference image. Photorealistic cinematic portrait,
rugged weathered American man 35 years old, Yukon 1902.
Fur hat with wide earflaps, all hair hidden under hat.
Full reddish beard with dense amber-yellow ice crystals and icicles,
frozen strands hanging from beard and mustache.
Wide prominent cheekbones raw red from frostbite, freckled weathered skin.
Pale grey-blue eyes narrowed and hard, locked forward with iron will.
Jaw clenched, lips pressed firmly together, chin set with stubborn defiance.
Expression of a man who refuses to give up against all odds.
Heavy fur parka with snow-covered fur collar, frost on shoulders.
Plain smooth fur coat, absolutely nothing attached to it.
Upper body portrait, face pointing DIRECTLY toward camera.
Cold overcast sky background, soft diffused north light.
Shot on Canon EOS R5, 85mm lens f/1.8,
natural skin texture, visible pores, 4K, ultra sharp focus.
No cameras, no props, no objects in frame except the character.
FORBIDDEN: NO straps, NO harness, NO equipment on body or coat.
```

### Э4 — Принятие / покой ✅
```
FORBIDDEN: NO straps, NO harness, NO backpack, NO bag, NO belt,
NO buckles, NO sling, NO shoulder strap of any kind.

Same character as reference image. Photorealistic cinematic portrait,
rugged weathered American man 35 years old, Yukon 1902.
Fur hat with wide earflaps, all hair hidden under hat.
Full reddish beard with dense amber-yellow ice crystals and icicles,
frozen strands hanging from beard and mustache.
Wide prominent cheekbones raw red from frostbite, freckled weathered skin.
Pale grey-blue eyes half closed, heavy eyelids drooping with exhaustion.
Mouth closed, facial muscles completely relaxed, no tension anywhere.
Expression of total calm and peaceful surrender, a man letting go.
Head tilted very slightly downward, as if falling into sleep.
Heavy fur parka with snow-covered fur collar, frost on shoulders.
Plain smooth fur coat, absolutely nothing attached to it.
Upper body portrait, face pointing DIRECTLY toward camera.
Cold overcast sky background, soft diffused north light.
Shot on Canon EOS R5, 85mm lens f/1.8,
natural skin texture, visible pores, 4K, ultra sharp focus.
No cameras, no props, no objects in frame except the character.
FORBIDDEN: NO straps, NO harness, NO equipment on body or coat.
```

### Э5 — Саркастическая усмешка ✅
```
FORBIDDEN: NO straps, NO harness, NO backpack, NO bag, NO belt,
NO buckles, NO sling, NO shoulder strap of any kind.

Same character as reference image. Photorealistic cinematic portrait,
rugged weathered American man 35 years old, Yukon 1902.
Fur hat with wide earflaps, all hair hidden under hat.
Full reddish beard with dense amber-yellow ice crystals and icicles,
frozen strands hanging from beard and mustache.
Wide prominent cheekbones raw red from frostbite, freckled weathered skin.
Pale grey-blue eyes with a knowing, slightly ironic look.
One corner of mouth pulled up in a sardonic half-smile,
a smirk of bitter amusement — the look of a man who realizes
he was wrong and finds it darkly funny.
Only one side of mouth smiling, other side flat.
Heavy fur parka with snow-covered fur collar, frost on shoulders.
Plain smooth fur coat, absolutely nothing attached to it.
Upper body portrait, face pointing DIRECTLY toward camera.
Cold overcast sky background, soft diffused north light.
Shot on Canon EOS R5, 85mm lens f/1.8,
natural skin texture, visible pores, 4K, ultra sharp focus.
No cameras, no props, no objects in frame except the character.
FORBIDDEN: NO straps, NO harness, NO equipment on body or coat.
```

### Э6 — Гнев / ярость ✅
```
FORBIDDEN: NO straps, NO harness, NO backpack, NO bag, NO belt,
NO buckles, NO sling, NO shoulder strap of any kind.

Same character as reference image. Photorealistic cinematic portrait,
rugged weathered American man 35 years old, Yukon 1902.
Fur hat with wide earflaps, all hair hidden under hat.
Full reddish beard with dense amber-yellow ice crystals and icicles,
frozen strands hanging from beard and mustache.
Wide prominent cheekbones raw red from frostbite, freckled weathered skin.
Pale grey-blue eyes wide with fury and desperation,
eyebrows pulled sharply down and together, deep angry furrows on forehead.
Mouth open, teeth clenched, jaw thrust forward in rage.
Expression of a man who has just lost his last chance —
furious at himself, at the cold, at everything.
Veins of tension visible on neck and forehead.
Heavy fur parka with snow-covered fur collar, frost on shoulders.
Plain smooth fur coat, absolutely nothing attached to it.
Upper body portrait, face pointing DIRECTLY toward camera.
Cold overcast sky background, soft diffused north light.
Shot on Canon EOS R5, 85mm lens f/1.8,
natural skin texture, visible pores, 4K, ultra sharp focus.
No cameras, no props, no objects in frame except the character.
FORBIDDEN: NO straps, NO harness, NO equipment on body or coat.
```

---

## ОСВЕЩЕНИЕ
> Полный рост с Image Prompt = М2; портреты с М1, 2K

### О1 — Свет костра, полный рост ✅
```
FORBIDDEN: NO straps, NO harness, NO backpack, NO bag, NO belt,
NO buckles, NO sling, NO shoulder strap of any kind.

Same character as reference image. Photorealistic full body cinematic photo,
rugged weathered American man 35 years old, Yukon 1902.
Fur hat with earflaps, reddish beard with amber ice icicles,
red chapped cheeks, blue-grey eyes, heavy fur parka,
thick fur mittens, wool leg wraps, moccasins.
FULL BODY HEAD TO TOE — feet and moccasins must be visible at bottom of frame.
DO NOT crop legs or feet. Neutral standing pose, arms relaxed at sides.

LIGHTING: campfire light only, warm orange and amber flames glow
coming from below and slightly in front of the character.
Face and front of parka lit with flickering warm orange light.
Deep cold shadows on sides and back of figure.
Dark night background, no sky visible, only darkness behind character.
Faint smoke or ember particles floating in air near the fire.
Snowy ground visible at feet, lit by firelight.

Shot on Canon EOS R5, 35mm lens f/2.8, 4K, photorealistic, cinematic.
No cameras, no props, no objects in frame except the character and fire glow.
FORBIDDEN: NO straps, NO harness, NO equipment on body or coat.
```

### О2 — Свет костра, портрет ✅
```
FORBIDDEN: NO straps, NO harness, NO backpack, NO bag, NO belt,
NO buckles, NO sling, NO shoulder strap of any kind.

Same character as reference image. Photorealistic cinematic portrait,
rugged weathered American man 35 years old, Yukon 1902.
Fur hat with wide earflaps, all hair hidden under hat.
Full reddish beard with dense amber-yellow ice crystals and icicles,
frozen strands hanging from beard and mustache.
Wide prominent cheekbones, freckled weathered skin.
Pale grey-blue eyes reflecting warm orange firelight.
Mouth closed, concentrated expression.
Heavy fur parka with fur collar, frost on shoulders.
Plain smooth fur coat, absolutely nothing attached to it.
Upper body portrait, face pointing DIRECTLY toward camera.

LIGHTING: campfire light only, warm orange and amber glow
coming from below and slightly in front of face.
Strong warm orange light on face, chin and chest lit from below.
Deep cold shadows above eyebrows and sides of face.
Dark night background behind the character.
Fire source not visible in frame. Only the light from fire
is visible on face and body, no flames, no burning wood in the shot.

Shot on Canon EOS R5, 85mm lens f/1.8,
natural skin texture, visible pores, 4K, ultra sharp focus.
No cameras, no props, no objects in frame except the character.
FORBIDDEN: NO straps, NO harness, NO equipment on body or coat.
```

### О3 — Ночь / синий свет, полный рост ✅
```
FORBIDDEN: NO straps, NO harness, NO backpack, NO bag, NO belt,
NO buckles, NO sling, NO shoulder strap of any kind.

Same character as reference image. Photorealistic full body cinematic photo,
rugged weathered American man 35 years old, Yukon 1902.
Fur hat with earflaps, reddish beard with amber ice icicles,
red chapped cheeks, blue-grey eyes, heavy fur parka,
thick fur mittens, wool leg wraps, moccasins.
FULL BODY HEAD TO TOE — feet and moccasins must be visible at bottom of frame.
DO NOT crop legs or feet. Neutral standing pose, arms relaxed at sides.

Arctic night scene. Cold blue ambient light filling the scene evenly.
Everything bathed in deep cold blue-grey tones.
No single light source visible anywhere in the frame.
No moon, no lamp, no fire, no bright spots anywhere.
Soft diffused cold night light with no direction.
Dark navy blue sky background, faint stars visible.
Snow on ground in cold blue shadow. Shadows are soft and directionless.

Shot on Canon EOS R5, 35mm lens f/2.8, 4K, photorealistic, cinematic.
No cameras, no props, no objects in frame except the character.
FORBIDDEN: NO straps, NO harness, NO equipment on body or coat.
FORBIDDEN: NO moon, NO light source, NO bright spots in frame.
```

### О4 — Золотой час, полный рост ✅
```
FORBIDDEN: NO straps, NO harness, NO backpack, NO bag, NO belt,
NO buckles, NO sling, NO shoulder strap of any kind.

Same character as reference image. Photorealistic full body cinematic photo,
rugged weathered American man 35 years old, Yukon 1902.
Fur hat with earflaps, reddish beard with amber ice icicles,
red chapped cheeks, blue-grey eyes, heavy fur parka,
thick fur mittens, wool leg wraps, moccasins.
FULL BODY HEAD TO TOE — feet and moccasins must be visible at bottom of frame.
DO NOT crop legs or feet. Neutral standing pose, arms relaxed at sides.

LIGHTING: golden hour, late afternoon winter sun very low on horizon.
Warm amber and orange light coming from the left side, low angle.
Long shadows stretching to the right across snow.
Left side of face and parka warmly lit in golden amber tones.
Right side in soft cool shadow.
Sky on horizon warm orange fading to pale blue above.
Snow surface glowing warm gold and orange.

Shot on Canon EOS R5, 35mm lens f/2.8, 4K, photorealistic, cinematic.
No cameras, no props, no objects in frame except the character.
FORBIDDEN: NO straps, NO harness, NO equipment on body or coat.
FORBIDDEN: NO sun disc, NO bright spots in sky.
```

### О5 — Контровой свет / силуэт ✅
```
FORBIDDEN: NO straps, NO harness, NO backpack, NO bag, NO belt,
NO buckles, NO sling, NO shoulder strap of any kind.

Same character as reference image. Photorealistic full body cinematic photo,
rugged weathered American man 35 years old, Yukon 1902.
Fur hat with earflaps, reddish beard with amber ice icicles,
red chapped cheeks, blue-grey eyes, heavy fur parka,
thick fur mittens, wool leg wraps, moccasins.
FULL BODY HEAD TO TOE — feet and moccasins must be visible at bottom of frame.
DO NOT crop legs or feet. Neutral standing pose, arms relaxed at sides.

LIGHTING: strong backlight from directly behind the character.
Bright overcast white sky behind figure creating strong rim light.
Thin bright edge of light outlining the entire silhouette.
Front of character in deep cool shadow, face barely visible.
Snow on ground bright white behind figure, dark in foreground.
No light source visible in frame, only the bright background sky.

Shot on Canon EOS R5, 35mm lens f/2.8, 4K, photorealistic, cinematic.
No cameras, no props, no objects in frame except the character.
FORBIDDEN: NO straps, NO harness, NO equipment on body or coat.
```

---

## ДЕЙСТВИЯ И ПОЗЫ
> Все с Image Prompt = М2 (кроме портретных), 2K

### Д1 — Указывает вперёд (гонит собаку) ✅
```
FORBIDDEN: NO straps, NO harness, NO backpack, NO bag, NO belt,
NO buckles, NO sling, NO shoulder strap of any kind.

Same character as reference image. Photorealistic full body cinematic photo,
rugged weathered American man 35 years old, Yukon 1902.
Fur hat with earflaps, reddish beard with amber ice icicles,
red chapped cheeks, blue-grey eyes, heavy fur parka,
thick fur mittens, wool leg wraps, moccasins.
FULL BODY HEAD TO TOE — feet and moccasins must be visible at bottom of frame.
DO NOT crop legs or feet.

Character leaning slightly forward, body weight on front foot.
Left arm raised and extended forward, mitten pointing ahead,
commanding gesture — ordering something to move forward.
Right arm hanging naturally at side.
Head tilted slightly downward, looking forward and down,
eyes fixed on something ahead on the ground.
Authoritative commanding posture, stern expression.

Snowy ground, overcast cold grey sky.
Shot on Canon EOS R5, 35mm lens f/2.8, 4K, photorealistic, cinematic.
No cameras, no props, no animals, no objects in frame except the character.
FORBIDDEN: NO straps, NO harness, NO equipment on body or coat.
```

### Д2 — Идёт, полоборота справа ✅
```
FORBIDDEN: NO straps, NO harness, NO backpack, NO bag, NO belt,
NO buckles, NO sling, NO shoulder strap of any kind.

Same character as reference image. Photorealistic full body cinematic photo,
rugged weathered American man 35 years old, Yukon 1902.
Fur hat with earflaps, reddish beard with amber ice icicles,
red chapped cheeks, blue-grey eyes, heavy fur parka,
thick fur mittens, wool leg wraps, moccasins.
FULL BODY HEAD TO TOE — feet and moccasins must be visible at bottom of frame.
DO NOT crop legs or feet.

Character walking forward, mid-stride, legs in motion.
Left foot forward, right foot pushing off behind.
Arms swinging naturally with walking motion, mittens visible.
Character's nose pointing toward RIGHT edge of the frame.
Character's LEFT shoulder closer to camera, right shoulder further back.
Three-quarter front-right view, face partially visible, right cheek toward camera.
Determined expression, eyes looking ahead in direction of walking.
Parka moving slightly with walking motion.

Snowy ground with footprints, overcast cold grey sky.
Shot on Canon EOS R5, 35mm lens f/2.8, 4K, photorealistic, cinematic.
No cameras, no props, no objects in frame except the character.
FORBIDDEN: NO straps, NO harness, NO equipment on body or coat.
```

### Д3 — Идёт, вид сзади ✅
```
FORBIDDEN: NO straps, NO harness, NO backpack, NO bag, NO belt,
NO buckles, NO sling, NO shoulder strap of any kind.

Same character as reference image. Photorealistic full body cinematic photo,
rugged weathered American man 35 years old, Yukon 1902.
Fur hat with earflaps, reddish beard with amber ice icicles,
heavy fur parka, thick fur mittens, wool leg wraps, moccasins.
FULL BODY HEAD TO TOE — feet and moccasins must be visible at bottom of frame.
DO NOT crop legs or feet.

Character walking away from camera, full back view.
Mid-stride, legs in walking motion, left foot forward right foot back.
Arms swinging naturally with walking motion, back of mittens visible.
Back of fur hat fully visible, back of parka fully visible,
back of wool leg wraps and heels of moccasins visible.
NO face visible — character facing completely away from camera.
Determined walking pace, heading into the distance.

Snowy ground with footprints trailing behind, overcast cold grey sky.
Vast empty white wilderness ahead of character.
Shot on Canon EOS R5, 35mm lens f/2.8, 4K, photorealistic, cinematic.
No cameras, no props, no objects in frame except the character.
FORBIDDEN: NO straps, NO harness, NO equipment on body or coat.
```

### Д4 — Наклонился, зажигает спички ✅
```
FORBIDDEN: NO straps, NO harness, NO backpack, NO bag, NO belt,
NO buckles, NO sling, NO shoulder strap of any kind.

Same character as reference image. Photorealistic full body cinematic photo,
rugged weathered American man 35 years old, Yukon 1902.
Fur hat with earflaps, reddish beard with amber ice icicles,
red chapped cheeks, blue-grey eyes, heavy fur parka,
thick fur mittens, wool leg wraps, moccasins.
FULL BODY HEAD TO TOE — feet and moccasins must be visible at bottom of frame.
DO NOT crop legs or feet.

Character crouching low over snowy ground, body bent forward,
both hands close together near the ground level,
attempting to strike matches with clumsy mittened hands.
Head bowed downward, face looking down at hands and ground.
Body hunched over, shoulders rounded forward with concentration.
Urgent desperate posture, focused entirely on task at ground level.
Small pile of dry twigs and bark visible on snow in front of hands.
No actual fire yet — just the attempt to light it.

Snowy ground, overcast cold grey sky.
Shot on Canon EOS R5, 35mm lens f/2.8, 4K, photorealistic, cinematic.
No cameras, no props, no objects in frame except the character
and small pile of tinder on ground.
FORBIDDEN: NO straps, NO harness, NO equipment on body or coat.
```

### Д5 — Трёт щёки от мороза ✅
```
FORBIDDEN: NO straps, NO harness, NO backpack, NO bag, NO belt,
NO buckles, NO sling, NO shoulder strap of any kind.

Same character as reference image. Photorealistic cinematic portrait,
rugged weathered American man 35 years old, Yukon 1902.
Fur hat with wide earflaps, all hair hidden under hat.
Full reddish beard with dense amber-yellow ice crystals and icicles,
frozen strands hanging from beard and mustache.
Wide prominent cheekbones raw red from frostbite, freckled weathered skin.
Pale grey-blue eyes squinting slightly from cold.
Heavy fur parka with snow-covered fur collar, frost on shoulders.
Plain smooth fur coat, absolutely nothing attached to it.

Character raising both mittened hands to face,
pressing and rubbing both cheeks simultaneously with thick fur mittens.
Both arms raised, elbows out, mittens pressed against cheekbones.
Expression of pain and urgency — cheeks burning from frostbite.
Head tilted very slightly, eyes squinting with discomfort.

Upper body portrait, facing slightly toward camera.
Cold overcast sky background, soft diffused north light.
Shot on Canon EOS R5, 85mm lens f/1.8,
natural skin texture, visible pores, 4K, ultra sharp focus.
No cameras, no props, no objects in frame except the character.
FORBIDDEN: NO straps, NO harness, NO equipment on body or coat.
```

### Д6 — Растирает замёрзшую ногу ✅
```
FORBIDDEN: NO straps, NO harness, NO backpack, NO bag, NO belt,
NO buckles, NO sling, NO shoulder strap of any kind.

Same character as reference image. Photorealistic full body cinematic photo,
rugged weathered American man 35 years old, Yukon 1902.
Fur hat with earflaps, reddish beard with amber ice icicles,
red chapped cheeks, blue-grey eyes, heavy fur parka,
thick fur mittens, wool leg wraps, moccasins.
FULL BODY — entire figure visible including feet.

Character sitting on snowy ground, one knee bent up,
leaning forward and down, both hands grabbing and rubbing
one foot and lower leg with urgency.
Trying to restore feeling to frozen foot through vigorous rubbing.
Face looking down at foot, expression of pain and desperation.
Body hunched over the leg, all attention focused on the foot.
Other leg bent naturally to the side on snow.
Moccasins and wool leg wraps clearly visible.

Snowy ground, overcast cold grey sky.
Shot on Canon EOS R5, 35mm lens f/2.8, 4K, photorealistic, cinematic.
No cameras, no props, no objects in frame except the character.
FORBIDDEN: NO straps, NO harness, NO equipment on body or coat.
```

### Д7 — Сидит у дерева, голова запрокинута ✅
```
FORBIDDEN: NO straps, NO harness, NO backpack, NO bag, NO belt,
NO buckles, NO sling, NO shoulder strap of any kind.

Same character as reference image. Photorealistic full body cinematic photo,
rugged weathered American man 35 years old, Yukon 1902.
Fur hat with earflaps, reddish beard with amber ice icicles,
red chapped cheeks, blue-grey eyes, heavy fur parka,
thick fur mittens, wool leg wraps, moccasins.
FULL BODY — entire seated figure visible including feet.

Character sitting on snowy ground, back leaning against
a large thick spruce tree trunk behind him.
Head tilted all the way back, resting against the tree bark,
face pointing upward toward the sky, throat exposed.
Eyes open, staring blankly upward at the sky above.
Both arms lying limp at sides on the snow, completely relaxed.
Legs stretched loosely in front, no tension in body.
Expression of total hopelessness and exhaustion,
a man who has given up fighting, accepting the end.
Body completely still and heavy against the tree.

Large dark spruce tree trunk visible behind character.
Snow on ground, cold overcast white sky visible above.
Shot on Canon EOS R5, 35mm lens f/2.8, 4K, photorealistic, cinematic.
No cameras, no props, no objects in frame except character and tree.
FORBIDDEN: NO straps, NO harness, NO equipment on body or coat.
```

### Д8 — Свернулся под деревом, замерзает ✅
```
FORBIDDEN: NO straps, NO harness, NO backpack, NO bag, NO belt,
NO buckles, NO sling, NO shoulder strap of any kind.

Same character as reference image. Photorealistic full body cinematic photo,
rugged weathered American man 35 years old, Yukon 1902.
Fur hat with earflaps, reddish beard with amber ice icicles,
red chapped cheeks, heavy fur parka,
thick fur mittens, wool leg wraps, moccasins.
FULL BODY — entire curled figure visible including feet.

Character lying on snowy ground curled into a tight fetal position,
knees pulled up to chest, arms wrapped around knees, body folded inward.
Back against the base of a large spruce tree trunk.
Head tucked down, chin pressed toward chest, face barely visible.
Body completely still, conserving last warmth, giving up movement.
Parka wrapped tightly around curled body. Mittens clutching knees together.
Moccasins and wool leg wraps visible at bottom of curled figure.
Snow slowly settling on shoulders and hat.
Expression of final exhaustion, fading consciousness.

Large dark spruce tree trunk visible behind and above character.
Snow on ground, cold overcast grey sky.
Shot on Canon EOS R5, 35mm lens f/2.8, 4K, photorealistic, cinematic.
No cameras, no props, no objects except character and tree.
FORBIDDEN: NO straps, NO harness, NO equipment on body or coat.
```

### Д9 — Лежит на боку, свернулся в клубок ✅
```
FORBIDDEN: NO straps, NO harness, NO backpack, NO bag, NO belt,
NO buckles, NO sling, NO shoulder strap of any kind.

Same character as reference image. Photorealistic full body cinematic photo,
rugged weathered American man 35 years old, Yukon 1902.
Fur hat with earflaps, reddish beard with amber ice icicles,
red chapped cheeks, heavy fur parka,
thick fur mittens, wool leg wraps, moccasins.
FULL BODY — entire lying figure visible from head to toe.

Character lying on his side on the snow.
BOTH knees pulled up as high as possible toward chest,
BOTH legs bent and tucked tightly, no leg extended or stretched out.
Body curled into the tightest possible ball, maximum fetal position.
Arms wrapped around both knees pulling them into chest.
Right cheek resting on snowy ground.
Face barely visible, partially hidden by fur collar and hat earflap.
Eyes closed, completely surrendered.
Parka wrapped around tightly curled body.
Snow on shoulders, hat and parka.
BOTH moccasins visible tucked close together near body.

Camera angle slightly above, looking down at figure.
Pure white snowy ground surrounding the figure.
Soft cold overcast light.
Shot on Canon EOS R5, 35mm lens f/2.8, 4K, photorealistic, cinematic.
No cameras, no props, no objects in frame except the character.
FORBIDDEN: NO straps, NO harness, NO equipment on body or coat.
FORBIDDEN: NO extended legs, NO straight legs.
```

---

## ИТОГОВЫЙ СТАТУС ДАТАСЕТА

| # | Категория | Кол-во | Статус |
|---|-----------|--------|--------|
| 1–17 | Оригинальные ракурсы (Seedream 4) | 17 | ✅ |
| 18–19 | Мастер-кадры М1, М2 | 2 | ✅ |
| 20–21 | Ракурсы портреты П1, П2 | 2 | ✅ |
| 22–27 | Эмоции Э1–Э6 | 6 | ✅ |
| 28–32 | Освещение О1–О5 | 5 | ✅ |
| 33–41 | Действия и позы Д1–Д9 | 9 | ✅ |
| **Итого** | | **~35** | ✅ |

---

## СЛЕДУЮЩИЕ ШАГИ

1. ✅ Датасет собран — 35 кадров
2. ⏳ Убрать фон у всех кадров → **remove.bg** (пакетная загрузка)
3. ⏳ Загрузить в Flux LoRA обучение → `@syntxaibot → Дизайн с ИИ → FLUX.1.1 PRO → Обучить Flux.1`
4. ⏳ Создать датасет персонажа **Собака**
5. ⏳ Генерация 13 сцен фильма

---

## КОНТЕКСТ ДЛЯ НОВОГО ЧАТА

```
Проект AI-Cinema, фильм «Костёр» по Джеку Лондону.
Платформа Syntx, модель Seedream 4.
Персонаж Человек — датасет готов (35 кадров), фон убираем через remove.bg.
Все промпты: films/film_01_kostyor/characters/chelovek_prompts_FULL.md
Следующий этап: создаём датасет персонажа Собака.
Описание из рассказа: крупная серая ездовая собака,
похожа на волка, хвост опущен, янтарные глаза,
инстинктивный страх перед морозом.
Репозиторий: https://github.com/Andrey-don/aI-cinema
```

---

*Источник: рабочий журнал Claude + метод Дротенко AI-продакшн*
