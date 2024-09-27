University: [ITMO University](https://itmo.ru/ru/)  
Faculty: [FICT](https://fict.itmo.ru)  
Course: [Introduction in routing](https://itmo-ict-faculty.github.io/network-programming/education/labs2023_2024/lab1/lab1/)  
Year: 2024/2025  
Group: K34212
Author: Kirpichenko Daniil Aleksandrovich
Lab: Lab1  
Date of create: 26.09.2024  
Date of finished: 27.09.2024  




## Лабораторная работ №1 "Установка ContainerLab и развертывание тестовой сети связи"



# Устанавливаем ВПН

apt update && apt -y install ca-certificates wget net-tools gnupg
wget -qO - https://as-repository.openvpn.net/as-repo-public.gpg | apt-key add -
echo "deb http://as-repository.openvpn.net/as/debian focal main">/etc/apt/sources.list.d/openvpn-as-repo.list
apt update && apt -y install openvpn-as


![](https://github.com/ko1ll/2023_2024-introduction_in_routing-k33212-kirpichenko-d-a/blob/main/photos/1.jpg)

![](https://github.com/ko1ll/2023_2024-introduction_in_routing-k33212-kirpichenko-d-a/blob/main/photos/2.jpg)

# Схема сети

![](https://github.com/ko1ll/2023_2024-introduction_in_routing-k33212-kirpichenko-d-a/blob/main/photos/9.jpg)

# Настройка роутера

![](https://github.com/ko1ll/2023_2024-introduction_in_routing-k33212-kirpichenko-d-a/blob/main/photos/3.jpg)

# Настройка sw3

![](https://github.com/ko1ll/2023_2024-introduction_in_routing-k33212-kirpichenko-d-a/blob/main/photos/4.jpg)

# Настройка sw2

![](https://github.com/ko1ll/2023_2024-introduction_in_routing-k33212-kirpichenko-d-a/blob/main/photos/5.jpg)

# Настройка sw1

![](https://github.com/ko1ll/2023_2024-introduction_in_routing-k33212-kirpichenko-d-a/blob/main/photos/6.jpg)

# Проверка сети

![](https://github.com/ko1ll/2023_2024-introduction_in_routing-k33212-kirpichenko-d-a/blob/main/photos/7.jpg)

![](https://github.com/ko1ll/2023_2024-introduction_in_routing-k33212-kirpichenko-d-a/blob/main/photos/8.jpg)

