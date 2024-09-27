University: [ITMO University](https://itmo.ru/ru/)  
Faculty: [FICT](https://fict.itmo.ru)  
Course: [Introduction in routing](https://itmo-ict-faculty.github.io/network-programming/education/labs2023_2024/lab1/lab1/)  
Year: 2024/2025  
Group: K34212
Author: Kirpichenko Daniil Aleksandrovich
Lab: Lab1  
Date of create: 26.09.2024  
Date of finished: 27.09.2024  




## Лабораторная работ №1 "Установка CHR и Ansible, настройка VPN"


# Арендуем виртуалку в Google Cloud и подключаемся к ней по SSH

![](https://github.com/ko1ll/2024-2025-network_programming-K34212/blob/main/photos/12.jpg)


# Устанавливаем ВПН и необходимые библиотеки

```
apt update && apt -y install ca-certificates wget net-tools gnupg
wget -qO - https://as-repository.openvpn.net/as-repo-public.gpg | apt-key add -
echo "deb http://as-repository.openvpn.net/as/debian focal main">/etc/apt/sources.list.d/openvpn-as-repo.list
apt update && apt -y install openvpn-as
```

![](https://github.com/ko1ll/2024-2025-network_programming-K34212/blob/main/photos/1.jpg)

![](https://github.com/ko1ll/2024-2025-network_programming-K34212/blob/main/photos/14.jpg)


# Подключаемся в интрфейс ВПНА и начинаем его настройку

![](https://github.com/ko1ll/2024-2025-network_programming-K34212/blob/main/photos/2.jpg)

# Создаем пользователя и получаем его сертификат

![](https://github.com/ko1ll/2024-2025-network_programming-K34212/blob/main/photos/4.jpg)

# Закидываем его в WinBox

![](https://github.com/ko1ll/2024-2025-network_programming-K34212/blob/main/photos/5.jpg)

# Импортируем сертификат в интерфейсе виртуалки

![](https://github.com/ko1ll/2024-2025-network_programming-K34212/blob/main/photos/6.jpg)

# Меняем IP Address впна

![](https://github.com/ko1ll/2024-2025-network_programming-K34212/blob/main/photos/7.jpg)

#  Оставляем только TCP подключение и запоминаем порт

![](https://github.com/ko1ll/2024-2025-network_programming-K34212/blob/main/photos/8.jpg)

#  Отключаем TLS

![](https://github.com/ko1ll/2024-2025-network_programming-K34212/blob/main/photos/3.jpg)

#  Создаем интерфейс с необходимыми нам настройками и выбираем авторизацию по сертификату

![](https://github.com/ko1ll/2024-2025-network_programming-K34212/blob/main/photos/9.jpg)

#  Проверяем, что мы успешно подключились

![](https://github.com/ko1ll/2024-2025-network_programming-K34212/blob/main/photos/10.jpg)
![](https://github.com/ko1ll/2024-2025-network_programming-K34212/blob/main/photos/11.jpg)



