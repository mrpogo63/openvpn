Role Name
=========

Роль устанавливает на удаленной машине openvpn клиент(ver=2.3.10) из группы "client" и конфигурирует его. Добавляет в автозапуск и запускает сервис. Выводит состояние сервиса

Requirements
------------

должны быть установлены пакеты python (например python-minimal)

Role Variables
--------------

openvpn_server_ip = IP адрес сервера openvpn
openvpn_server_port = порт сервера

Dependencies
------------

Example Playbook
----------------

ansible-playbook -i hosts main.yml


License
-------

BSD

Author Information
------------------

Evgeniy.Zubakin 2019
mr.pogo@mail.ru
