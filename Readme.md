
# Описание переменных

## В этой переменной задается ip адрес хоста
ansible_host: 192.168.10.104

## В этой переменной указывается версия python интепретатора 
ansible_python_interpreter 

## В этой переменной обозначается имя клиента (может отличаться от inventory_hostname)
openvpn_client_client_name

## В этой переменной указывается название сетевого интерфейся для клиентской впн роли
openvpn_client_device_interface

## Задается протокол udp или tcp  
openvpn_client_protocol

## Задается количество попыток в секундах прежде чем отвалится, infinite = бесконечно
openvpn_client_retry

## Обозначается ip адрес впн сервера
openvpn_client_remote_server

## Обозначается порт впн сервера
openvpn_client_remote_port