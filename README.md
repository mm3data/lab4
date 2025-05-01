# Настройка IPv6-адресов на сетеых устройствах  

## Топология  
![image](https://github.com/user-attachments/assets/855fe2fa-6d69-430e-84ac-a50ad7e98b70)  

Утсройство | Интерфейс | IPv6-адрес | Link local IPv6-адрес | Длина префикса | Шлюз по умолчанию   
------- | ----- | ------  | ----- | ------- | -----   
R1 | G0/0/0 | 2001:db8:acad:a::1 | fe80::1 | 64 | -   
-- | G0/0/1 | 2001:db8:acad:1::1 | fe80::1 | 64 |-  
S1 |Vlan1 | 2001:db8:acad:1::b | fe80::b | 64 -  
PC-A | NIC | 2001:db8:acad:1::3 | SLACC |64 | fe80::1 |  
PC_B | NIC | 2001:db8:acad:a::3 | SLACC | 64 | fe80::1 |   

## Задачи  
* Настройка топологии и конфигурация основных параметров маршрутизатора и коммутатора
* Настройка Ручная IPv6-адресов
* Проверка сквозного соединения

**Настройка маршрутизатора** 

![image](https://github.com/user-attachments/assets/a75ba06c-2a1b-4e2a-bfb6-4512d806c4d9) 

![image](https://github.com/user-attachments/assets/e5065550-cd70-4eb0-9f07-561f9ac234ef)  

**Натсройка коммутатора**  

![image](https://github.com/user-attachments/assets/c7c5c4d6-08f2-48be-b899-50de78b49072)  

![image](https://github.com/user-attachments/assets/98203516-2d7c-480a-a0d4-624959118b59)











