![image](https://github.com/davlat777/6semsetr/assets/113089483/fc5facb6-2219-495d-bfdf-35360b85ea0e)![image](https://github.com/davlat777/6semsetr/assets/113089483/5b03d3aa-7baf-4cfd-aaa9-f51fa03c1a78)# ЛК 15.01.24
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

Устройства:

![image](https://github.com/davlat777/6semsetr/assets/113089483/943f13c4-e910-405d-886b-fbfc4d82e6ac)
![image](https://github.com/davlat777/6semsetr/assets/113089483/796c491b-8563-4714-a802-4062e0392339)

c - cимвольные

блочные (флешки)

![image](https://github.com/davlat777/6semsetr/assets/113089483/592ea408-953e-4cee-9cd4-562b417a49b8)
![image](https://github.com/davlat777/6semsetr/assets/113089483/09de5fb9-d523-4485-8aa2-cf64e36495f3)
![image](https://github.com/davlat777/6semsetr/assets/113089483/424b6794-f206-490d-824f-5b6c4a056c35)

b - блок

Пытались создать флешку

Файлам присваиваются уникальные номера - inod, посмотреть команды - ls-i1

![image](https://github.com/davlat777/6semsetr/assets/113089483/6c6952db-748c-4dac-90b3-e8048d1608af)


Жесткие ссылки имеют тот же номер что и файл и это можно использовать, чтобы найти все жесткие ссылки

![image](https://github.com/davlat777/6semsetr/assets/113089483/452a7bb1-16f8-455b-ba4b-441e95ef0c29)
![image](https://github.com/davlat777/6semsetr/assets/113089483/81e6d825-ca68-45d2-8571-19582c476401)
![image](https://github.com/davlat777/6semsetr/assets/113089483/ccdbeffb-83b9-48be-9237-76cea0f66575)
![image](https://github.com/davlat777/6semsetr/assets/113089483/4f452d34-288c-4b4c-bfe1-85b14db9d35d)
![image](https://github.com/davlat777/6semsetr/assets/113089483/d04897ff-0b6b-434c-98ef-df3d0bfe48ce)
![image](https://github.com/davlat777/6semsetr/assets/113089483/9607d325-fe42-49e0-90fe-251025c9ba57)
![image](https://github.com/davlat777/6semsetr/assets/113089483/b87ac92c-4253-4999-8195-665b47ae34bc)
![image](https://github.com/davlat777/6semsetr/assets/113089483/6df9cf98-fbf8-4dab-a0fa-d12a64ca535a)
![image](https://github.com/davlat777/6semsetr/assets/113089483/bb2dc86d-9e18-4c74-91c8-57a5e37dd654)
![image](https://github.com/davlat777/6semsetr/assets/113089483/79467827-cc5d-4717-9fc4-84db93618277)
![image](https://github.com/davlat777/6semsetr/assets/113089483/335779fb-ad10-4f3b-ab88-d69470f6c820)
![image](https://github.com/davlat777/6semsetr/assets/113089483/58ec0cc9-d53f-4b8a-bec4-a3025ae7b194)
![image](https://github.com/davlat777/6semsetr/assets/113089483/b4a3cfbd-973f-4926-8b30-5c76eb14e571)
![image](https://github.com/davlat777/6semsetr/assets/113089483/32a4fb87-ef37-4628-a0de-fdbf5f2723ee)


https://docs.google.com/document/d/1z27O5xLblWKjIxcXRZnbd1smm-oYa8bt/edit#heading=h.lxq8x11igx58

# ЛК 19.02.24 Скрипт на создание и удаление пользователя

Имя пользователя/Место под пароль/Номер пользователя/Номер группы пользователя/название группы/Домашняя директория пользователя/Терминал пользователя

Создаем пользователя 

![image](https://github.com/davlat777/6semsetr/assets/113089483/ce61d852-3202-4746-998e-576125587012)

Переключаем ползователя

![image](https://github.com/davlat777/6semsetr/assets/113089483/7775d69d-006b-45a4-8b61-952491b41bc4)

Создаем пароль для нашего пользователя

![image](https://github.com/davlat777/6semsetr/assets/113089483/0627cc04-f3f3-453b-92ba-ea75fc12a135)

Создаем пользователя в нашем новом пользователе при помощи сркипта

![image](https://github.com/davlat777/6semsetr/assets/113089483/a01ecf8b-3315-400f-8089-5f42c20accc2)

![image](https://github.com/davlat777/6semsetr/assets/113089483/5b3223de-5f12-4be6-ac6e-a1a2dfc4d6f2)

![image](https://github.com/davlat777/6semsetr/assets/113089483/577b3929-51de-473d-8592-a2017621213d)

![image](https://github.com/davlat777/6semsetr/assets/113089483/b1be08bd-400d-490a-ab14-6a1bbc010946)

![image](https://github.com/davlat777/6semsetr/assets/113089483/3a52c11c-97ab-4804-a795-1ffe25225540)

![image](https://github.com/davlat777/6semsetr/assets/113089483/25a78db8-601b-4d58-b176-411bb7a37b51)

![image](https://github.com/davlat777/6semsetr/assets/113089483/9ad39076-e544-4f14-8190-707398dc1fb5)

![image](https://github.com/davlat777/6semsetr/assets/113089483/0a212beb-71c1-4da3-969f-2058d6f9d574)

![image](https://github.com/davlat777/6semsetr/assets/113089483/2fb5a295-258e-4dd7-b665-69dabbc6992d)

![image](https://github.com/davlat777/6semsetr/assets/113089483/818d7d1c-9e71-4ae9-b060-6dbcc0b96ed3)

![image](https://github.com/davlat777/6semsetr/assets/113089483/d8abc047-953d-412e-82e6-998f293930b8)

# ЛК4 04.03.24 Структура памяти процесса

![image](https://github.com/davlat777/6semsetr/assets/113089483/af4882fb-08ec-406d-ad45-eee759cf5724)

![image](https://github.com/davlat777/6semsetr/assets/113089483/283beecd-f519-4ecb-8e80-42f8e4440595)

![image](https://github.com/davlat777/6semsetr/assets/113089483/ad787ede-aecc-45c7-a42e-aa62e2e812bf)

![image](https://github.com/davlat777/6semsetr/assets/113089483/fab1f503-0111-4784-9f7e-dd570a6631ae)

![image](https://github.com/davlat777/6semsetr/assets/113089483/7facca6f-5b39-416c-9a39-f1b2f6092894)

PID - номера поцесса (на винде в диспетчере задач смотрим)

![image](https://github.com/davlat777/6semsetr/assets/113089483/486a0694-efb2-4a33-a524-94eb3027e3a8)

![image](https://github.com/davlat777/6semsetr/assets/113089483/1f5bbb2c-8dec-47df-bba2-530dffa10819)

![image](https://github.com/davlat777/6semsetr/assets/113089483/795180dd-75a3-4107-bc11-0c8c817832fb)

Память запоняется в определенные ячейки(разные)

![image](https://github.com/davlat777/6semsetr/assets/113089483/f7908e7a-1b10-45c0-b577-70e34214133e)

Библиотеки:

![image](https://github.com/davlat777/6semsetr/assets/113089483/bb88102f-3f15-4323-a732-83dc3e6e4da0)

Область данных и текст(код):

![image](https://github.com/davlat777/6semsetr/assets/113089483/9db9eefd-a67b-4d85-ac16-c6c2c1868ce0)

![image](https://github.com/davlat777/6semsetr/assets/113089483/da0d8373-bfc7-47b3-bde6-8e0e14bc77e7)

![image](https://github.com/davlat777/6semsetr/assets/113089483/7a0420d2-f49d-4784-8716-a0d75df56b02)

![image](https://github.com/davlat777/6semsetr/assets/113089483/0107f28f-481f-440a-9a9f-ffaea60a08db)

![image](https://github.com/davlat777/6semsetr/assets/113089483/26d62e18-45c4-4a64-a658-f398ea08cf6f)

![image](https://github.com/davlat777/6semsetr/assets/113089483/6a02fa2e-d8cd-4282-adc7-45b2e846fd73)

![image](https://github.com/davlat777/6semsetr/assets/113089483/6980bd56-41fd-4144-a67b-26a033b69b5a)

![image](https://github.com/davlat777/6semsetr/assets/113089483/486fecb7-657c-47fa-acd7-087fba96988c)

![image](https://github.com/davlat777/6semsetr/assets/113089483/ebc43089-df0c-4074-8fbe-3b97d7e26d0b)

![image](https://github.com/davlat777/6semsetr/assets/113089483/0894e26b-ff19-489a-8784-359f8146dd0d)

# ЛК5 11.03.24. Потоки в БД

**Атрибуты процесса:**

1.PID - уникальный идентификатор

2.Адресация областей памяти процесса

3.fd - открытые файловые дескрипторы (терминал или файлы которые используют процессы)

4.Обработчики сигналов процесса (введение запроса пользователя)

5.Код выхода (Ctr+C, Ctr+Z, exit, Программа все выполнила)

6.Рабочий каталог (Папка рабочего процесса - proc)

7.Переменные окружения (Комментарии)

8.Состояние процесса

9.Аппаратный контекст (То что определяься компьютером)
































