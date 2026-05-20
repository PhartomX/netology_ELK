# Домашнее задание к занятию "`ELK`" - `Алексей Сидоров`
---

### Задание 1. Elasticsearch

Установите и запустите Elasticsearch, после чего поменяйте параметр cluster_name на случайный.

`Cкриншот`

![img1](https://github.com/PhartomX/netology_ELK/blob/main/img/img1.png)

---

### Задание 2. Kibana

Установите и запустите Kibana.

`Cкриншот, где видно:`

![img1](https://github.com/PhartomX/netology_ELK/blob/main/img/img1.png)


---

### Задание 3. Logstash

Установите и запустите Logstash и Nginx. С помощью Logstash отправьте access-лог Nginx в Elasticsearch.

`Cкриншот с результатом выполнения:`

![img2](https://github.com/PhartomX/netology_ELK/blob/main/img/img2.png)

---

### Задание 4. Filebeat.

Установите и запустите Filebeat. Переключите поставку логов Nginx с Logstash на Filebeat.

`Cкриншот с результатом выполнения:`

![img3](https://github.com/PhartomX/netology_ELK/blob/main/img/img3.png)


---

### Задание 5*. Доставка данных

Настройте поставку лога в Elasticsearch через Logstash и Filebeat любого другого сервиса , но не Nginx. Для этого лог должен писаться на файловую систему, Logstash должен корректно его распарсить и разложить на поля.

`Cкриншот с результатом выполнения:`

![img5](https://github.com/PhartomX/netology_ELK/blob/main/img/img5.png)