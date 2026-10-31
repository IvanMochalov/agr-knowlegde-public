# AGR Knowledge (public) — база знаний Verta Forms

Публичная wiki по процессу выдачи свидетельства АГР в Москве: процесс города, модели/комплект, FAQ и разговор с заказчиком.

Внутренний калькулятор, бланки КП и формулы наценок — в отдельном **private**-репозитории и сюда не входят.

## Сайт (GitHub Pages)

**https://ivanmochalov.github.io/agr-knowlegde-public/**

Включение один раз: **Settings → Pages → Deploy from a branch → `main` / `/ (root)` → Save**.

Сайт на [Docsify](https://docsify.js.org): те же `.md` из `wiki/`, дерево слева, поиск.

Локально:

```bash
python3 -m http.server 4173
```

Откройте http://127.0.0.1:4173/

## С чего начать

| Куда | Зачем |
| --- | --- |
| [Сайт на Pages](https://ivanmochalov.github.io/agr-knowlegde-public/) | Чтение в браузере |
| [`wiki/index.md`](wiki/index.md) | Каталог базы знаний |
| [`wiki/README.md`](wiki/README.md) | Что такое wiki |
| [`wiki/AGENTS.md`](wiki/AGENTS.md) | Правила сопровождения |
| [`wiki/log.md`](wiki/log.md) | Журнал изменений |

## Структура

```
agr-knowlegde-public/
├── README.md
├── index.html         ← Docsify
├── _sidebar.md
├── .nojekyll
└── wiki/              ← публичная база знаний
    ├── concepts/
    ├── process/
    ├── team/
    └── raw/
```
