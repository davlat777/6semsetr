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

![image](https://github.com/davlat777/6semsetr/assets/113089483/9c1034f9-3201-4f28-b831-7763474cfcea)

![image](https://github.com/davlat777/6semsetr/assets/113089483/b21a29b9-9496-471f-b43b-55905e7ba987)

![image](https://github.com/davlat777/6semsetr/assets/113089483/24ce3a03-8ff6-473b-8ca0-33c0aee0588a)

Основыне ошибки:

1. Remote - подключение к удаленному репозиторию (показывает на какой репозиторий мы хотим сохранить данные), может быть ошибка что неправильно укзали ссылку. Что бы изменить -> добавить сейт-URL
2. Авторизация - гитхабу нужно передать данные пользователя (логин, пароль или токен)
3. Прокси сервер - проверять включен или нет

# ЛК 22.01.24

1.Если есть папка .git, то команду git init выполнять не нужно

2.Команды config настраиваются на ПК 1 раз

3.git remote указывается 1 раз

![image](https://github.com/davlat777/6semsetr/assets/113089483/62249f7d-f52d-4dbe-961f-d3d6656de639)

![image](https://github.com/davlat777/6semsetr/assets/113089483/349678c5-f5a3-41ca-926d-718efb60f8c8)

![image](https://github.com/davlat777/6semsetr/assets/113089483/a9522be2-c4c8-4f78-9c5b-1dc3d46b870d)

# Задание 1. Знакомство с компилятором gcc

![image](https://github.com/davlat777/6semsetr/assets/113089483/ac9c9c28-abaa-4ed1-b964-5aeebe92b5bc)

![image](https://github.com/davlat777/6semsetr/assets/113089483/72ab62c1-49b1-4197-a73e-46fa6699301d)

Debian:
stud

qwerty

RedOS:

12345678

![image](https://github.com/davlat777/6semsetr/assets/113089483/df5d12a5-957c-4792-aea0-780a9d4ac210)

![image](https://github.com/davlat777/6semsetr/assets/113089483/328b382c-5dd5-43c6-bc08-e9c20419ab6c)


# ЛК 05.02.24 Работа с файлами

1. Создание
2. Перенесение
3. Редактирование
4. Удаление

Обычный (regular) файл

1)touch

2)mb

3)nano

4)cat

5)rm

![image](https://github.com/davlat777/6semsetr/assets/113089483/e28e3a71-e067-4cc4-9eb7-81fce02d6c61)
![image](https://github.com/davlat777/6semsetr/assets/113089483/988c4b7e-589a-476e-83a4-217ab09fdebb)
![image](https://github.com/davlat777/6semsetr/assets/113089483/4043905a-9c41-4775-803d-35343d6887d2)
![image](https://github.com/davlat777/6semsetr/assets/113089483/5f27bc80-3217-45de-9a83-b8c87484f2e8)
![image](https://github.com/davlat777/6semsetr/assets/113089483/8b97b44b-e856-42c3-8f6c-8d4483f9f256)
![image](https://github.com/davlat777/6semsetr/assets/113089483/3e6b7eb9-ad7b-4f4f-bf4e-9969d1096226)
![image](https://github.com/davlat777/6semsetr/assets/113089483/a0822671-221b-4725-8c75-4a9b6a024690)
![image](https://github.com/davlat777/6semsetr/assets/113089483/b89c5b32-e9fe-4c82-971b-19485ccc786f)

