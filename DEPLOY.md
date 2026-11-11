# Деплой

Сайт публикуется через **GitHub Pages** из ветки `main`, папка `/ (root)`:

**https://svetylekkk.github.io/chaosity-mvp/**

## Как обновлять
Любой `git push` в `main` выкатывает новую версию за 1–2 минуты.
Статус сборки: вкладка **Actions** в репозитории (workflow «pages build and deployment»).
Если в браузере видна старая версия, обнови страницу без кэша (Cmd+Shift+R).

## Открыть как Telegram Mini App
1. В Telegram открой @BotFather → `/newbot` → придумай имя и username бота.
2. `/mybots` → выбери бота → **Bot Settings → Configure Mini App → Enable Mini App**
   и вставь ссылку `https://svetylekkk.github.io/chaosity-mvp/`.
3. Открой бота — появится кнопка запуска мини-приложения.
   Внутри Telegram прототип сам прячет нарисованную шапку и использует системную кнопку «Назад».

## Vercel (запасной вариант)
Аккаунт Vercel попросил дополнительную проверку. Если её одобрят:
vercel.com/new → Import `chaosity-mvp` → Framework Preset «Other», сборку не настраивать → Deploy.
