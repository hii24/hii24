# Как это всё установить (5 минут)

## Шаг 1. Создай специальный репозиторий

1. Зайди на https://github.com/new
2. **Repository name:** `hii24` (точно как твой username — это ключевой момент!)
3. Поставь галочку **Public**
4. Поставь галочку **Add a README file**
5. Жми **Create repository**

GitHub покажет тебе зелёное сообщение «hii24/hii24 is a ✨special✨ repository» — значит всё ок.

## Шаг 2. Залей README.md

**Способ А (через сайт, проще):**
1. Открой созданный репо `hii24/hii24`
2. Жми на `README.md` → карандашик (Edit)
3. Удали всё что там есть
4. Скопируй содержимое файла `README.md` из этой папки и вставь
5. Внизу — Commit changes

**Способ Б (через терминал):**
```bash
cd ~/Desktop/hii24-profile
git init
git add README.md .github/workflows/snake.yml
git branch -M main
git remote add origin https://github.com/hii24/hii24.git
git commit -m "feat: add profile readme"
git push -u origin main --force
```

## Шаг 3. Включи змейку 🐍

После пуша:
1. Зайди в репо `hii24/hii24` → вкладка **Actions**
2. Если попросит — жми «I understand my workflows, go ahead and enable them»
3. Слева выбери **Generate Snake** → справа кнопка **Run workflow** → Run
4. Подожди 30 сек — змейка сгенерируется в ветку `output`
5. Дальше она сама обновляется каждые 6 часов

Если на шаге 4 упадёт с ошибкой permission — иди в:
**Settings → Actions → General → Workflow permissions → Read and write permissions** → Save → запусти Action ещё раз.

## Шаг 4. Включи приватные контрибуции в статистике (опционально)

Чтобы карточка статистики показывала и приватные репы:
1. Иди в свой профиль https://github.com/hii24
2. Справа **Contribution settings** → галочка **Private contributions**

## Шаг 5. Подставь свои контакты

В `README.md` найди блок **Let's Connect** и замени:
- `your-email@example.com` — твой email
- `t.me/your_username` — Telegram (или удали строку)
- `discord.com/users/your_id` — Discord ID (или удали)
- `linkedin.com/in/your_username` — LinkedIn (или удали)
- `x.com/your_username` — Twitter/X (или удали)

Если соцсети нет — просто удали соответствующую строчку с `<a>...</a>`.

## Шаг 6. (Опционально) Wakatime

В шапке есть блок Wakatime — он показывает на каких языках ты пишешь сколько часов. Чтобы заработало:
1. Зарегайся на https://wakatime.com (бесплатно)
2. Поставь плагин в свой VS Code
3. Через пару дней статистика начнёт собираться

Если не хочешь — просто удали блок `<!-- METRICS LINE -->` в README.

---

## Что в итоге будет на профиле

✅ Анимированная волна сверху и снизу  
✅ Печатающийся текст с твоими ролями  
✅ Счётчик просмотров профиля  
✅ Блок «About me» с кодом на TypeScript  
✅ Иконки технологий (skillicons)  
✅ Карточка статистики GitHub  
✅ Топ языков  
✅ Streak (огонёк коммитов подряд)  
✅ График активности  
✅ Кубки за достижения  
✅ Змейка, поедающая твои контрибуции 🐍  
✅ Рандомная цитата программиста  
✅ Кнопки соцсетей  

Готово — заходишь на профиль, и сразу видно «о, тут серьёзный человек».
