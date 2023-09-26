### Network design. Clos topology

# 1. Собрать топологию CLOS, как на схеме:

![lab01.схема.png](lab01.схема.png)

# 2. Адресное пространство для Underlay сети:

# Адреса loppback-интерфейсов:

|  Наименование |  Адрес   |
| :------------ |:--------:|
| Spine1        | 10.0.1.1 |
| Spine2        | 10.0.2.2 |
| Leaf1         | 10.0.0.1 |
| Leaf2         | 10.0.0.2 |
| Leaf3         | 10.0.0.3 |

# Линковочные сети:
| :------------ |:------------:|
| Spine1_Leaf1  | 172.16.1.0/30|
| Spine1_Leaf2  | 172.16.2.0/30|
| Spine1_Leaf3  | 172.16.3.0/30|
| Spine2_Leaf1  | 172.16.1.4/30|
| Spine2_Leaf2  | 172.16.2.4/30|
| Spine2_Leaf3  | 172.16.3.4/30|

# Адреса хостов:
| :---- |:----------------:|
| Host1 | 192.168.10.10/24 |
| Host2 | 192.168.10.20/24 |
| Host3 | 192.168.10.30/24 |
| Host4 | 192.168.10.40/24 |

# Структурная схема

![clos_topology2.PNG](clos_topology2.PNG)
