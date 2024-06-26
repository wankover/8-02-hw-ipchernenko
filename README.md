# Домашнее задание к занятию "Что такое DevOps. СI/СD" - Черненко Иван #

Задание 1

Что нужно сделать:

    Установите себе jenkins по инструкции из лекции или любым другим способом из официальной документации. Использовать Docker в этом задании нежелательно.
    Установите на машину с jenkins golang.
    Используя свой аккаунт на GitHub, сделайте себе форк репозитория. В этом же репозитории находится дополнительный материал для выполнения ДЗ.
    Создайте в jenkins Freestyle Project, подключите получившийся репозиторий к нему и произведите запуск тестов и сборку проекта go test . и docker build ..

В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.

![screen_1](https://github.com/wankover/8-02-hw-ipchernenko/blob/main/img/jenkins-16.png)

![screen_2](https://github.com/wankover/8-02-hw-ipchernenko/blob/main/img/jenkins-2.png)

![screen_3](https://github.com/wankover/8-02-hw-ipchernenko/blob/main/img/jenkins-3.png)

![screen_4](https://github.com/wankover/8-02-hw-ipchernenko/blob/main/img/jenkins-4.png)

![screen_5](https://github.com/wankover/8-02-hw-ipchernenko/blob/main/img/jenkins-5.png)

Задание 2

Создайте новый проект pipeline.
Перепишите сборку из задания 1 на declarative в виде кода.
В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.

![screen_6](https://github.com/wankover/8-02-hw-ipchernenko/blob/main/img/jenkins-6.png)

![screen_7](https://github.com/wankover/8-02-hw-ipchernenko/blob/main/img/jenkins-7.png)

![screen_8](https://github.com/wankover/8-02-hw-ipchernenko/blob/main/img/jenkins-8.png)

Задание 3

Установите на машину Nexus.
Создайте raw-hosted репозиторий.
Измените pipeline так, чтобы вместо Docker-образа собирался бинарный go-файл. Команду можно скопировать из Dockerfile.
Загрузите файл в репозиторий с помощью jenkins.
В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.

![screen_9](https://github.com/wankover/8-02-hw-ipchernenko/blob/main/img/jenkins-9.png)

![screen_10](https://github.com/wankover/8-02-hw-ipchernenko/blob/main/img/jenkins-10.png)

![screen_11](https://github.com/wankover/8-02-hw-ipchernenko/blob/main/img/jenkins-11.png)

![screen_12](https://github.com/wankover/8-02-hw-ipchernenko/blob/main/img/jenkins-12.png)

![screen_13](https://github.com/wankover/8-02-hw-ipchernenko/blob/main/img/jenkins-13.png)

![screen_14](https://github.com/wankover/8-02-hw-ipchernenko/blob/main/img/jenkins-14.png)

![screen_15](https://github.com/wankover/8-02-hw-ipchernenko/blob/main/img/jenkins-15.png)
