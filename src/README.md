В рамках проекта вам необходимо получить данные о компаниях и вакансиях с сайта hh.ru, спроектировать таблицы в БД PostgreSQL и загрузить полученные данные в созданные таблицы.
Для работы потребуется:

    Установить PostgresSQL: https://www.postgresql.org/download/
    Установить Pycharm: https://www.jetbrains.com/pycharm/download/?section=linux
    В терминале введите команду:

git clone https://github.com/TatianaGen/kurs5.git

    Создайте виртуальное окружение:

python3 -m venv venv

    Активируйте виртуальное окружение:

source venv/Scripts/activate

    Установите модули из файла pyproject.toml

    В папке проекта src cоздайте database.ini конфигурационный файл с вашими параметрами подключения к БД.
    
    Пример файла:

[postgresql]
host=localhost
user=postgres
password=1234
port=5432

