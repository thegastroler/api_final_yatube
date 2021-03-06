## YaTube API обладает функционалом:
- Аутентификация пользовалетей по JWT-токену
-  Получение списока всех публикаций. Возможность указания параметров limit и offset.
-  Добавление новой публикации в коллекцию публикаций. Анонимные запросы запрещены.
-  Получение публикации по id.
-  Обновление публикации по id. Обновить публикацию может только автор публикации. Анонимные запросы запрещены.
-  Частичное обновление публикации по id. Обновить публикацию может только автор публикации. Анонимные запросы запрещены.
-  Удаление публикации по id. Удалить публикацию может только автор публикации. Анонимные запросы запрещены.
-  Получение всех комментариев к публикации.
-  Добавление нового комментария к публикации. Анонимные запросы запрещены.
-  Получение комментария к публикации по id.
-  Обновление комментария к публикации по id. Обновить комментарий может только автор комментария. Анонимные запросы запрещены.
-  Частичное обновление комментария к публикации по id. Обновить комментарий может только автор комментария. Анонимные запросы запрещены.
-  Удаление комментария к публикации по id. Обновить комментарий может только автор комментария. Анонимные запросы запрещены.
-  Получение списка доступных сообществ.
-  Получение информации о сообществе по id.
-  Получение списка всех подпискок пользователя, сделавшего запрос. Анонимные запросы запрещены.
-  Подписка пользователя, от имени которого сделан запрос, на пользователя, переданного в теле запроса. Анонимные запросы запрещены.
-  Получение JWT-токена.
-  Обновление JWT-токена.
-  Проверка JWT-токена.

## Как запустить проект:

Клонируйте репозиторий:

```
git clone https://github.com/rodionbogoveev/api_final_yatube
```

Cоздайте и активируйте виртуальное окружение:
```
python -m venv venv
```
```
source venv/Scripts/activate
```
Установите зависимости из файла requirements.txt:
```
python -m pip install --upgrade pip
```
```
pip install -r requirements.txt
```
Выполните миграции:
```
python manage.py migrate
```
Запустите проект:
```
python manage.py runserver
```
Проект запущен и доступен по адресу [localhost](http://127.0.0.1:8000/).

## В разработке
Нужно доработать отправку кода при регистрации на e-mail.
