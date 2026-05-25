# Планы и ракурсы камеры — Шпаргалка

## Типы планов
| План | Описание | Применение |
|------|----------|-----------|
| Extreme Wide Shot | Персонаж крошечный, среда огромна | Одиночество, масштаб, вводный кадр |
| Wide Shot | Персонаж виден целиком | Начало сцены, ориентация |
| Medium Shot | От пояса вверх | Диалоги, действие |
| Medium Close-Up | От груди вверх | Эмоции в разговоре |
| Close-Up | Лицо | Ключевые эмоции, напряжение |
| Extreme Close-Up | Глаза, деталь | Максимальное напряжение |

## Ракурсы
| Ракурс | Эффект | Промпт-ключевые слова |
|--------|--------|----------------------|
| На уровне глаз | Нейтральный | eye level shot |
| Снизу вверх | Мощь, угроза | low angle shot, imposing |
| Сверху вниз | Слабость, уязвимость | high angle shot, vulnerable |
| Голландский угол | Тревога, нестабильность | dutch angle, unsettling |
| Птичий глаз | Ничтожность | bird's eye view, overhead |
| Взгляд червя | Максимально снизу, объекты на переднем плане | worm's eye shot, worm eye view |
| Взгляд бога | Персонаж крошечный, нагнетание | god's eye view, god eye shot |

## Фрейминг (обрамление кадра)
Объекты на переднем плане создают глубину и интерес:
- ветки, арки, окна, трубы перед камерой
- в промпте: `framed by [объект], foreground elements, depth`
- Пример: `shot through frost-covered branches, foreground framing, depth`

## Промпты по ракурсам
```
# Дальний план
[subject], extreme wide shot, tiny figure in vast [landscape],
cinematic, --ar 9:16 --v 7

# Крупный план — эмоция
[character], close-up portrait, [emotion] expression,
cinematic lighting, shallow depth of field, --ar 9:16 --v 7

# Голландский угол
[scene], dutch angle shot, psychological tension,
unsettling atmosphere, --ar 9:16 --v 7

# Снизу вверх
[character], low angle shot, powerful figure,
dramatic sky, --ar 9:16 --v 7
```
