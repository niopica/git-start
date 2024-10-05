# Тренировка git - https://learngitbranching.js.org/?locale=ru_RU

#

- git config --global user.name "<ваше\*имя>" (Установим имя для вашего пользователя)
- git config --global user.email "<адрес*почты@email.com>" (Теперь установим email. Принцип тот же.)

#

- git status
- git remote --v (Проверка связан ли наш проект с репозиторием GitHub)
- git remote add origin [url] (Связываем наш проект с репозиторием)
- git log / git log --oneline (1. Информативный просмотр изменений, 2. краткий просмотр изменений)

#

- git init - Инициализация/создание репозитория
- git add [files] - добавляет файлы в stage
- git add . - Добавим все файлы проекта в нам будующий commit (Или так git add --all)

#

- git commit -m 'comment' - Теперь создаем commit. Обязательно указываем комментарий.
- git push [rep_link] [branch_name] - добавляем изменения на репозиторий gitHub

#

- git reset [filename]
- git reset --hard
- git diff [filename]

# .gitignore

- Игнорирует файлы, не добавляет в репозиторий (.env .vscode node_modules)

# Ветки (Brach)

- Для чего нужны ветки?
- Онин нужны что бы разделять наш код, главный код и код для разработки
- Master -> develop
- от develop идут ветки features/about-page, features/main-page,
- и происходит изоляция разработчиков над определенной фичей, где никто никому не мешает
- Андрей работает над features/about-page, а Руслан над features/main-page

#

- К командам:
- git branch - просмотр какие ветки уже существуют
- git branch [name] создание новой ветки
- git checkout [name] переключение между существующими ветками
