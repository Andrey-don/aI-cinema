# Kling AI 3.0 и Veo 3.1 — Руководство

## Когда что использовать
| Задача | Инструмент |
|--------|-----------|
| Большинство сцен (камера, природа) | Veo 3.1 Fast — быстро и дёшево |
| Сложное движение персонажей | Kling AI 3.0 |
| Морфинг между кадрами | Kling AI 3.0 Keyframes |
| Схватки, динамика | Kling AI 3.0 |

## Kling AI 3.0 — Режимы
- **Motion Brush** — рисуем зоны и направления движения
- **Keyframes** — морфинг между двумя изображениями
- **Camera Control** — управление движением камеры
- Длина: 5–10 секунд

## Промпты для анимации (коротко и конкретно!)
```
# Долли вперёд
slow dolly push in toward [subject], building tension, smooth camera

# Следование за персонажем
camera tracks alongside [character], steady tracking shot

# Статика с атмосферой
[scene], gentle wind movement, particles floating, camera slightly drifting

# Морфинг (Kling Keyframes)
smooth transition between [кадр A] and [кадр B],
realistic movement, no distortion, cinematic
```

## Правила морфинга
1. Похожая композиция и ракурс в обоих кадрах
2. Промпт: 1–2 предложения
3. Ключевые слова: плавный / smooth, реалистично / realistic
4. При артефактах: меньше движения, больше статики
