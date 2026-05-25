# Персонаж: [ИМЯ]

## Визуальный профиль
- Возраст:
- Пол:
- Этнос:
- Волосы: цвет, длина, стиль
- Глаза: цвет
- Телосложение:
- Отличительные черты:
- Одежда (базовая):

## Базовый промпт Midjourney
```
[детальное описание], cinematic portrait, photorealistic,
natural lighting, --ar 9:16 --v 7 --q 2 --s 100
```

## Мастер-кадр
- URL мастер-кадра: [вставить после генерации]
- Использовать как: --cref [URL] во всех сценах

## Вариации по освещению
```
# День, улица
[base prompt], outdoor daylight, natural sun

# Ночь
[base prompt], night scene, moonlight, dark atmosphere

# Интерьер
[base prompt], indoor warm lighting, interior scene
```

## Вариации по эмоциям
```
# Нейтральная
[base prompt], neutral expression, calm

# Страх
[base prompt], fearful expression, wide eyes

# Решимость
[base prompt], determined expression, focused gaze
```

## Правила консистентности
- Всегда включать в промпт: [список обязательных элементов]
- Никогда не менять: [список фиксированных элементов]
- Параметры: --cref [URL] --s 100
