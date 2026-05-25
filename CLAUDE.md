# AI-Cinema — Главный контекстный файл

## Цель проекта
Система AI-кинопроизводства для создания коротких фильмов (9:16, Reels/Shorts/TikTok)
с использованием платформы Syntx и инструментов AI-генерации.

## Технический стек
| Этап | Инструмент |
|------|-----------|
| Генерация изображений | Midjourney v7 (основной), NanoBanana Pro, Seedream 5.0 |
| Улучшение изображений | Clarity, NanoBanana Pro |
| Анимация | Kling AI 3.0, Veo 3.1 Fast, Seedance, Runway |
| Улучшение видео | Topaz Video AI |
| Монтаж | CapCut, Edits |
| Музыка | Suno |
| Озвучка | ElevenLabs (через @syntxaibot → Аудио с ИИ) |
| Платформа | syntx.ai + Telegram @syntxaibot |

## Ключевые правила
1. Формат видео: всегда 9:16
2. Промпты для генерации: на английском
3. Промпты для ретуши в NanoBanana: можно на русском
4. Параметры MJ по умолчанию: --ar 9:16 --v 7 --q 2
5. Консистентность персонажей: всегда --cref [URL мастер-кадра]
6. Консистентность локации: всегда --sref [URL первого кадра локации]
7. Все удачные промпты сохранять в _prompts_library/

## Структура проекта
- `_knowledge_base/` — вся теория: кино, инструменты, гайды
- `_characters/` — библиотека персонажей (переиспользуются в разных фильмах)
- `_prompts_library/` — шаблоны промптов
- `films/` — отдельные фильмы (каждый со своим CLAUDE.md)
- `obsidian_vault/` — база знаний в Obsidian

## Как работать с проектом
- Открывать в Claude Code: папку конкретного фильма `films/film_XX/`
- Добавить персонажа: скопировать `_characters/_template/`
- Вся теория: `_knowledge_base/`

## Справочники (читать по запросу — не загружать автоматически)
| Файл | Когда читать |
|------|-------------|
| `_knowledge_base/books/grammatika_kino_pajper.md` | Раскадровка, выбор планов/ракурсов/монтажа/цвета |
| `_knowledge_base/books/biblia_ii_creatora.md` | Промпты, параметры MJ, анимация, морфинг, Suno, ElevenLabs |
| `_knowledge_base/tools/seedream_fotorealizm.md` | Фотореализм, фиксация лица персонажа, Seedream vs MJ |
| `_knowledge_base/tools/ai_prodakshn_workflow.md` | Общий воркфлоу: Style Lock, структура промптов, этапы продакшна |
| `_knowledge_base/tools/kontekstnoe_redaktirovanie.md` | Правка готовых кадров: Flux Kontext / Seedream / NanoBanana |
| `_knowledge_base/cinematography/` | Быстрая шпаргалка по конкретной теме |
| `_knowledge_base/tools/` | При работе с конкретным инструментом |

## Текущий активный проект
films/film_01_kostyor — «Костёр» по рассказу Джека Лондона
