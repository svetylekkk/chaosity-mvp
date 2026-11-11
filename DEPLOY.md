# Деплой на Vercel через GitHub

## 1. Подключить репозиторий к Vercel (один раз)
1. Зайди на https://vercel.com и войди через GitHub (Continue with GitHub).
2. Нажми **Add New… → Project**.
3. В списке **Import Git Repository** найди `chaosity-mvp` и нажми **Import**.
   Если репозитория нет в списке: **Adjust GitHub App Permissions** → дай Vercel доступ к этому репозиторию.
4. Настройки оставь по умолчанию:
   - Framework Preset: **Other**
   - Build Command: пусто
   - Output Directory: пусто (корень репозитория)
5. Нажми **Deploy**. Через ~30 секунд появится ссылка вида `https://chaosity-mvp.vercel.app`.

## 2. Как обновлять
Любой `git push` в ветку `main` автоматически выкатывает новую версию.
Пуш в другую ветку создаёт отдельную превью-ссылку — удобно показывать правки до релиза.

## 3. Открыть как Telegram Mini App
1. В Telegram открой @BotFather → `/newbot` → придумай имя бота.
2. `/mybots` → выбери бота → **Bot Settings → Configure Mini App → Enable Mini App**
   и вставь ссылку с Vercel (обязательно https).
3. Открой бота — внизу появится кнопка запуска мини-приложения.
   Внутри Telegram прототип сам прячет нарисованную шапку и использует системную кнопку «Назад».
