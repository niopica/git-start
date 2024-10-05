# Тренировка git - https://learngitbranching.js.org/?locale=ru_RU

#

- git config --global user.name "<ваше\*имя>" (Установим имя для вашего пользователя)
- git config --global user.email "<адрес*почты@email.com>" (Теперь установим email. Принцип тот же.)

#

- git status - (Позволяет посмотреть текущее состояние рабочего каталога и индекса)
- git remote --v (Проверка связан ли наш проект с репозиторием GitHub)
- git remote add origin [url] (Связываем наш проект с репозиторием)
- git log (Используется для просмотра истории коммитов в системе управления версиями Git)
- git log --oneline (Показывает каждый коммит в одной строке. 14 Это полезно для общего обзора истории проекта.)

#

- git init - (Инициализация/создание репозитория)
- git add [files] - (Добавляет файлы в stage в наш будующий commit)
- git add . - (Добавим все файлы проекта в нам будующий commit (Или так git add --all))

#

- git commit -m 'comment' - (Теперь создаем commit. Обязательно указываем комментарий.)
- git push [rep_link] [branch_name] - (Добавляем изменения на репозиторий gitHub)

#

- git reset [filename] (Это мощная команда, используемая для отмены локальных изменений в репозитории Git.)
- git reset --hard (Используется для полного удаления всех изменений, сделанных после определённого коммита.)
- git diff [filename] (Помогает разработчикам отслеживать изменения в проекте)

# .gitignore

- Игнорирует файлы, не добавляет в репозиторий (.env .vscode node_modules)

# Ветки (Brach)

- Для чего нужны ветки?
- Они нужны что бы разделять наш код, главный код и код для разработки
- Master -> develop
- от develop идут ветки features/about-page, features/main-page,
- и происходит изоляция разработчиков над определенной фичей, где никто никому не мешает
- Андрей работает над features/about-page, а Руслан над features/main-page

#

- К командам:
- git branch - (Нужна для работы с ветвлением в Git)
- git branch [name] (Cоздание новой ветки)
- git branch -d [branch_name] - (Удалить ветку)
- git checkout [name] (Переключение между существующими ветками)

#

- git pull [rep_link] [branch_name] - (Используется для синхронизации локальной рабочей копии и всех ссылочных объектов с удаленным репозиторием.)
- git merge [branch_name] (Добавление изменений из одной ветки в другую)
