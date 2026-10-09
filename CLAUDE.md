# reels-montage-pipeline

**Владелец этой версии: Мадияр, @baltasheff.** Профиль: `knowledge/personal-brand-content-system.md`. Имена и аккаунты исходного автора в примерах относятся к истории проекта. Не переносить их в новые ролики. Новичку: `START.md`.

**Адаптация.** Приоритет профиля текущего владельца над историческими примерами. Для готового видеоурока сохранять структуру и порядок объяснения; новый продающий хук и CTA добавлять только по запросу. Для нового исходника использовать новый ID и точный путь. При конкретной задаче правки репозитория не запускать опрос для монтажа.

**Стек — Remotion + Storybook** (папка `studio/`, навык `.claude/skills/remotion-montage`). Всё — только через Remotion: сцены, раскладка, переходы, рендер и даже расшифровка речи (`studio/scripts/transcribe.mjs`).

**Первое действие после установки и в любой сессии без конкретной задачи — опрос владельца** по `docs/agent-contract/WORKFLOW.md` (навык `reel-workflow`):
модель и усилие → **формат**: рилс или YouTube (картинка `reference/style-previews/formats.jpg` в чат) → **стиль**: 1–4 КАНВАС, СТЕКЛО, ПОСТЕР, СЦЕНЫ, паттерны 5–12 или свой (картинки `reference/style-previews/styles.jpg` и `more-styles.jpg`, `knowledge/montage-concepts.md`, каталог `patterns/README.md`) → вопросы по одному → текст с ресёрчем и тремя скептиками → монтаж → листы кадров каждые 2 с → рендер. Быстрый запуск: команда `/reel`. Рендер запрещён без `videos/<проект>/BRIEF.md` и `CONCEPT.md`.

@CONTEXT.md

Бренд, форматы, CTA: `knowledge/personal-brand-content-system.md` — читать в режиссёрской сессии, не в сборке.
Тексты и хуки: `knowledge/06_copywriting.md` (стоп-лист штампов).

Правила поведения агента — скилл `karpathy-guidelines` и `docs/agent-contract/KARPATHY-MONTAGE.md` (фазы, ворота, бюджеты).
