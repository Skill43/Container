### Урок 5. Docker Compose и Docker Swarm
#### Cоздать сервис, состоящий из 2 различных контейнеров: 1 - веб, 2 - БД (compose)

Создаём директорию и переходим в неё:
![](images/1.png)
Создаём в папке файл docker-compose.yml:
![](images/2.png)
Устанавливаем docker-compose:
![](images/3.png)
Создаём и запускаем проект:
![](images/4.png)
Проверяем, что появилось два контейнера:
![](images/5.png)
Открываем страницу под адресом http://localhost:6080:
![](images/6.png)
Вводим имя пользоваля root и пароль(мы его указывали в docker-compose.yml) и входим в Adminer. Вуаля, там используется база данных MariaDB:
![](images/7.png)