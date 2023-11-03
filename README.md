# Домашнее задание к занятию 2 «Кластеризация и балансировка нагрузки»



### Задание 1
- Запустите два simple python сервера на своей виртуальной машине на разных портах

<details>

![image](https://github.com/Ivashka80/Claster_and_Balance/assets/121082757/bcc36292-87c5-42ca-9d9b-6f5dfad9c107)

![image](https://github.com/Ivashka80/Claster_and_Balance/assets/121082757/66d312c3-eb87-449e-9910-e8a8788d4257)

</details>

- Установите и настройте HAProxy, воспользуйтесь материалами к лекции по [ссылке](2/)
- Настройте балансировку Round-robin на 4 уровне.
- На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy.

<details>

Ссылка HAProxy https://github.com/ovchdmitriy01/8-02/blob/main/haproxy.cfg

![image](https://github.com/ovchdmitriy01/8-02/blob/main/1.jpg)

![image](https://github.com/ovchdmitriy01/8-02/blob/main/2.jpg)

</details>

### Задание 2
- Запустите три simple python сервера на своей виртуальной машине на разных портах

<details>

![image](https://github.com/ovchdmitriy01/8-02/blob/main/5.jpg)

![image](https://github.com/ovchdmitriy01/8-02/blob/main/6.jpg)

![image](https://github.com/ovchdmitriy01/8-02/blob/main/7.jpg)

</details>

- Настройте балансировку Weighted Round Robin на 7 уровне, чтобы первый сервер имел вес 2, второй - 3, а третий - 4
- HAproxy должен балансировать только тот http-трафик, который адресован домену example.local
- На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy c использованием домена example.local и без него.

<details>

Ссылка файл HAProxy https://github.com/ovchdmitriy01/8-02/blob/main/haproxy_2.cfg

![image](https://github.com/ovchdmitriy01/8-02/blob/main/3.jpg)

![image](https://github.com/ovchdmitriy01/8-02/blob/main/4.jpg)

</details>

