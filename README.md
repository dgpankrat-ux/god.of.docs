# God of Docs

Личная база знаний по технической документации, бизнес-анализу и техническому письму: статьи, курсы, книги, инструменты и каналы для наблюдения.

## Как запустить локально как сайт

База знаний собрана на [Docsify](https://docsify.js.org/) — рендерит markdown-файлы прямо в браузере, без сборки. Все JS/CSS-файлы движка лежат в [`vendor/docsify/`](vendor/docsify) и работают офлайн, интернет не нужен.

```bash
python3 -m http.server 5500
```

Затем открыть **http://localhost:5500** — слева появится навигация по всем разделам ([_sidebar.md](_sidebar.md)), сверху справа — поиск по всей базе.

> Открывать `index.html` напрямую двойным кликом (`file://`) не получится — браузер блокирует загрузку markdown-файлов через `fetch` с локального диска без сервера.

## Разделы

| Раздел | Что внутри |
|---|---|
| [Artefacts](Artefacts/Artefacts.md) | Книги и курсы для аналитических навыков и техписьма + локальные PDF/DOCX копии книг |
| [Articles](Articles/Articles.md) | Статьи: Docs as Code, Knowledge Management, онбординг техписателей, UX, UML, матрица требований, API-документация, UX-тексты |
| [Courses](Courses/Courses.md) | Курсы: английский, вёрстка, документирование REST API, style guide Microsoft |
| [Git](Git/Git%20simple%20guide.md) | Базовые материалы по Git и справочник по API-референсам |
| [Telegram](Telegram/Telegram%20channels.md) | Телеграм-каналы по докам и DevRel |
| [Tools](Tools/Tools.md) | Инструменты для документации, UI-текстов и переводов |
| [Youtube](Youtube/Youtube%20channels.md) | Youtube-каналы и видео по докам, API, BPMN, Markdown |

## Проверка актуальности ссылок

Последняя проверка: **2026-08-28**. Проверено ~30 внешних ссылок во всех разделах (HTTP-статус + ручная проверка в браузере там, где сайт блокирует автоматические запросы).

Найдено и исправлено 2 неактуальные ссылки в [Articles.md](Articles/Articles.md):

1. **`docs.divio.com/tutorials/`** (пример Django-туториала внутри раздела «Tutorials») — страница удалена после редизайна сайта Divio. Заменена на актуальный [официальный Django tutorial](https://docs.djangoproject.com/en/stable/intro/tutorial01/).
2. **`nuancesprog.ru/p/10971/`** (статья «UX-текст: как он формирует продукт») — сайт сменил структуру URL, страница отдаёт 404. Заменена на [зеркало статьи на Medium](https://medium.com/nuances-of-programming/ux-текст-как-он-формирует-продукт-c81d2975e664).

Остальные ссылки (Habr, Divio, Xsolla Tech Blog на Medium, dou.ua, readme.com, learn.microsoft.com, jamstack.org, git-scm.com, t.me/docops, Youtube-видео/плейлист/канал, Coursera, Busuu и т. д.) — рабочие.
