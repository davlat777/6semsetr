# ЛК 15.01.24
GitBash - команды для работа с Git из терминала ([Установка](https://git-scm.com/downloads))

Прокси сервер Git config "--global http.proxy 10.0.50.52:3128"

Практические работы: https://smartiqa.ru/courses/git/answer-key

![image](https://github.com/davlat777/6semsetr/assets/113089483/b02a2ee8-a108-47b0-9af4-bb8dc8ca6a8d)

Создание репозитория на компьютере: Инициализация Git Init

![image](https://github.com/davlat777/6semsetr/assets/113089483/b0fc3ffb-82dc-4a76-9ce2-f87d68406f53)

Показывает структуру папки гит "cmd //c tree .git"

git status - Показывает статус репозитория
On branch master - Указывает имя версии

No commits yet - Нет сохраненных версий

Untracked files: - Неотслеживаемые файлы

  (use "git add <file>..." to include in what will be committed) - Нужна команда добавить, чтобы зафиксировать версию для сохранения
  
        index.html
        pictures 
список файлов для сохранения

nothing added to commit but untracked files present (use "git add" to track) - Найдены файлы для добавления

git config user.name PK23-12

git config --global –unset http.proxy

git config --global --unset https.proxy

git config --global --unset core.gitproxy

Добавление файлов

![image](https://github.com/davlat777/6semsetr/assets/113089483/2b863e18-1aa1-44e0-9c51-d15bb3ea0caf)

"*" - все файлы

Для фиксации версии нужно указать название

git commit -m "G-02: Fixed typo in Elephant" - Для фиксации версии нужно указать ее название. Для этого создается сообщение (-m)

Выводим информацию о фиксации

git log

Подтверждение Git

![image](https://github.com/davlat777/6semsetr/assets/113089483/67d57d68-92a7-47f3-8dfa-a09fa0e3e077)

