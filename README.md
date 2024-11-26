# Домашнее задание к занятию "`Очереди RabbitMQ`" - `Солдатенкова Елизавета`

---

### Задание 1

![1](https://github.com/lizaMosiyash/sdb-04/blob/master/screenshots/1.PNG)


---

### Задание 2

![2_1](https://github.com/lizaMosiyash/sdb-04/blob/master/screenshots/2_1.PNG)
![2_2](https://github.com/lizaMosiyash/sdb-04/blob/master/screenshots/2_2.PNG)

---

### Задание 3

Я получала ошибки при попытке добавить к кластеру по имени машины rmq02(в файле hosts данные были добавлены), поэтому я ввела внешний IP. На скриншоте нод это видно.

![UI of cluster](https://github.com/lizaMosiyash/sdb-04/blob/master/screenshots/3_UI.PNG)

К сожалению, UI работал криво, по этой причине прикладываю команду, которой я задала политики

![UI_error](https://github.com/lizaMosiyash/sdb-04/blob/master/screenshots/3_policy_ui.PNG)
![policy_command](https://github.com/lizaMosiyash/sdb-04/blob/master/screenshots/3_command_for_policy.PNG)

Статусы нод кластера:

![1 node](https://github.com/lizaMosiyash/sdb-04/blob/master/screenshots/3_node1_status.PNG)
![1 node(1)](https://github.com/lizaMosiyash/sdb-04/blob/master/screenshots/1_node1(1)_status.PNG)
![2 node](https://github.com/lizaMosiyash/sdb-04/blob/master/screenshots/3_node2_status.PNG)
![2 node(1)](https://github.com/lizaMosiyash/sdb-04/blob/master/screenshots/3_node2(1)_status.PNG)

Результаты выполнения команды:
![1 node](https://github.com/lizaMosiyash/sdb-04/blob/master/screenshots/3_get_queue.PNG)
![2 node](https://github.com/lizaMosiyash/sdb-04/blob/master/screenshots/3_get_queue2.PNG)

результаты запуска consumer.py на одной включенной ноде:
![consumer.py](https://github.com/lizaMosiyash/sdb-04/blob/master/screenshots/3_hello.PNG)