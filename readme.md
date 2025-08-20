# Домашнее задание к занятию "`ELK`" - `Иншаков Владимир`


### Задание 1. Elasticsearch 

Установите и запустите Elasticsearch, после чего поменяйте параметр cluster_name на случайный. 

*Приведите скриншот команды 'curl -X GET 'localhost:9200/_cluster/health?pretty', сделанной на сервере с установленным Elasticsearch. Где будет виден нестандартный cluster_name*.

---

### Решение 1. Elasticsearch

![Screen_01](https://github.com/MrVanG0gh/Netology_sdb_11_03_ELK/blob/main/screens/Screen_01.png)

Вместо стандартного кластера теперь – «vans_cluster»

---

### Задание 2. Kibana

Установите и запустите Kibana.

*Приведите скриншот интерфейса Kibana на странице http://<ip вашего сервера>:5601/app/dev_tools#/console, где будет выполнен запрос GET /_cluster/health?pretty*.

---

### Решение 2. Kibana

![Screen_02](https://github.com/MrVanG0gh/Netology_sdb_11_03_ELK/blob/main/screens/Screen_02.png)

На скриншоте виден ответ на запрос «GET /_cluster/health?pretty»

---

### Задание 3. Logstash

Установите и запустите Logstash и Nginx. С помощью Logstash отправьте access-лог Nginx в Elasticsearch. 

*Приведите скриншот интерфейса Kibana, на котором видны логи Nginx.*

---

### Решение 3. Logstash

![Screen_03](https://github.com/MrVanG0gh/Netology_sdb_11_03_ELK/blob/main/screens/Screen_03.png)

![Screen_04](https://github.com/MrVanG0gh/Netology_sdb_11_03_ELK/blob/main/screens/Screen_04.png)

---

### Задание 4. Filebeat. 

Установите и запустите Filebeat. Переключите поставку логов Nginx с Logstash на Filebeat. 

*Приведите скриншот интерфейса Kibana, на котором видны логи Nginx, которые были отправлены через Filebeat.*

---

### Решение 4. Filebeat

![Screen_05](https://github.com/MrVanG0gh/Netology_sdb_11_03_ELK/blob/main/screens/Screen_05.png)

![Screen_06](https://github.com/MrVanG0gh/Netology_sdb_11_03_ELK/blob/main/screens/Screen_06.png)



