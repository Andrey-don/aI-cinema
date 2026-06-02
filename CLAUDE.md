# AI-Cinema — Главный контекстный файл

## Кто ты в этом проекте

Ты работаешь как инженер Anthropic: всё что повторяется — превращаешь в **скилл**.
Каждая сессия делает следующую умнее. Цель — через 30 дней работы ты кардинально
полезнее, чем в первый день.

**4 обязательных правила:**

1. **Промть скиллы, не меня.** Заметил повторяющуюся инструкцию → предложи скилл.
2. **Скилл = три слоя:** Description (когда) · Instructions (как) · Tools (чем).
   Реальная сила на третьем слое — туда не доходят 90%.
3. **Композиция, не монолит.** 3–5 фокус-скиллов, каждый делает одно.
   Структура: `~/.claude/skills/<имя>/SKILL.md` + `tools/` + `examples/`
4. **Обновляй скиллы каждую сессию.** В конце спроси:
   *«Что из этой сессии забрать в скилл навсегда, а что было разовой правкой?»*

**Сквозной принцип:** можно сделать кодом → делай кодом. Повторяемая логика → `tools/`.

---

## Цель проекта

Система AI-кинопроизводства для создания коротких фильмов (9:16, Reels/Shorts/TikTok).

---

## Технический стек

| Этап | Инструмент |
|------|-----------|
| Генерация изображений | Seedream 4 (основной), NanoBanana Pro |
| Улучшение изображений | Clarity, NanoBanana Pro |
| Анимация | Kling AI 3.0, Seedance 2.0, Veo 3.1 Fast |
| Монтаж | CapCut |
| Музыка | Suno |
| Озвучка | ElevenLabs |
| Платформа | syntx.ai + Telegram @syntxaibot |

---

## Ключевые правила

1. Формат видео: всегда 9:16
2. Промпты для генерации: на английском
3. Промпты для ретуши в NanoBanana: можно на русском
4. Консистентность персонажей: всегда через Image Prompt = [URL мастер-кадра]
5. Все удачные промпты сохранять в `_prompts_library/`

---

## Структура проекта

```
AI-Cinema/
├── _knowledge_base/     — теория: кино, инструменты, гайды
├── _characters/         — библиотека персонажей
├── _prompts_library/    — шаблоны промптов
├── films/               — фильмы (каждый со своим CLAUDE.md)
└── obsidian_vault/      — навигационный слой
```

Открывать в Claude Code: папку конкретного фильма `films/film_XX/`

---

## Многоагентная система (активна в film_01_kostyor)

| Агент | Файл | Читает | Пишет |
|-------|------|--------|-------|
| Раскадровщик | agents/01_storyboarder.md | script/, characters/ | storyboard/scenes/ |
| Генератор кадров | agents/02_frame_generator.md | storyboard/, characters/ | assets/registry.md |
| Видеограф | agents/03_videographer.md | registry.md, transitions.md | video_prompts.md |
| Монтажёр | agents/04_editor.md | assets/videos/, music_prompts.md | edit_plan.md |

**Правило:** каждый агент стартует только когда предыдущий проставил `done` в `production/status.md`

---

## Справочники (читать по запросу, не загружать автоматически)

| Файл | Когда читать |
|------|-------------|
| `_knowledge_base/books/grammatika_kino_pajper.md` | Раскадровка, планы, ракурсы, монтаж |
| `_knowledge_base/books/biblia_ii_creatora.md` | Промпты, анимация, Suno, ElevenLabs |
| `_knowledge_base/tools/seedream_fotorealizm.md` | Фотореализм, фиксация персонажа |
| `_knowledge_base/tools/production_workflow.md` | Воркфлоу: Style Lock, этапы продакшна |
| `_knowledge_base/tools/kontekstnoe_redaktirovanie.md` | Правка кадров: Flux Kontext / Seedream |
| `_knowledge_base/cinematography/smena_planov_nejrograf.md` | Смена планов, правило третей, типы планов, рабочий процесс NanoBanana |
| `_knowledge_base/cinematography/` | Шпаргалка по конкретной теме |

---

## Текущий активный проект

`films/film_01_kostyor` — «Костёр» по рассказу Джека Лондона
