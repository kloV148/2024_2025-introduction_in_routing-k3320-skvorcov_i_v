University: [ITMO University](https://itmo.ru/ru/)

Faculty: [FICT](https://fict.itmo.ru)

Course: [Introduction in routing](https://github.com/itmo-ict-faculty/introduction-in-routing)

Year: 2024/2025

Group: K3320

Author: Skvorcov Ivan Vladimirovich

Lab: Lab3

Date of create: 20.12.2024

Date of finished: 24.12.2024

# Отчёт по лабораторной работе №3 "Эмуляция распределенной корпоративной сети связи, настройка OSPF и MPLS, организация первого EoMPLS"

Создадим конфигурацию в файла ```lab3.clab.yaml```. Тополгоию можно увидеть ниже

![топология сети](pictures/diagram.png)

## Конфигурация

**HKI** 
![конфигурация](pictures/HKI_conf.png)

**LBN**
![конфигурация](pictures/LBN_conf.png)

**LND** 
![конфигурация](pictures/LND_conf.png)

**MSK**
![конфигурация](pictures/MSK_conf.png)

**NY**
![конфигурация](pictures/NY_conf.png)

**SPB**
![конфигурация](pictures/SPB_conf.png)

## Пинги

Теперь проверим, что все работает

**PC to SGI**

![ping](pictures/PC_SGI.png)

**SGI to PC**

![ping](pictures/SGI_PC.png)

**R01.SPB to 192.168.4.101 and 192.168.3.101**
![trc](pictures/trc_spb.png)

**NY <-> SPB**
![trc](pictures/trc_SPB_NY.png)
![trc](pictures/trc_NY_SPB.png)
