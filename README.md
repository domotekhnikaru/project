### Установка

### Скопировать **.env.example** в **.env**

```
php artisan key:generate
```

#### Заполнить данные в .env (подключение к бд)

#### Запустить миграции и заполнить базу тестовыми данными

```
php artisan migrate:install

php artisan db:seed
````

#### Запуск приложения без установки php-fpm и т.д.

```
php artisan serve --host=HOST --port=8000
```


### Требования к версиям ПО

php 8.0

oracle mysql 8.0.25+ / mariadb 10.2.39+

redis и другое - по необходимости
