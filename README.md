1. Docker и Docker-compose
В проекте представлены простые скрипты приветствия реализованные на python. С помощью  Docker и Docker-compose выполнена контейнеризация приложений.
  1. main.py - простое приветсвие, для запуска скрипта сформируйте образ командой $ docker build -t hello_docker . и запустите контейнер  $ docker run  hello_docker, имя образа для примера.
  2. flask и php-apache - приложения с сервером flask и php-apache, разверните их с помощью docker-compose, используйте команды: 
  $docker-compose build - запускаем образ; 
  $docker-compose up — запустить проект.
  3. Ожидаемый результат:
    1. после запуска main.py, в  командной строке - Hello Docker
    2. после запуска flask и php-apache, в браузере введите локальный адрес localhost:5000 - Hello, docker-compose и localhost:5001  -  Hello Docker-compose from php.
