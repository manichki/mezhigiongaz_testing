Web-приложение для проведения тестирования пользователей (тесты добавляются через панель администратора).

## Инструкции

### 1.Установка

  Клонирование репозитория:

    git clone https://github.com/manichki/mezhigiongaz_testing.git
    
### 2.Установка зависимостей:

    pip install -r requirements.txt

### 3.Миграции
Запуск миграций:

    python manage.py makemigrations
    python manage.py migrate

### 4.Создание суперпользователя


    python manage.py createsuperuser

После запуска данной команды необходимо ввести имя пользователя и пароль. 
После вы получите доступ к панели администратора по адресу localhost:8000/admin/

### 5.Локальный запуск

Приложение запускается на localhost, порт 8000 установлен по-умолчанию.

    python manage.py runserver

### Основные ссылки

    admin/ - панель администратора
    accounts/login - страница авторизации пользователя
    signup/ - страница регистрации пользователя