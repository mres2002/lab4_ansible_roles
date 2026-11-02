Ansible Role: Nginx Virtual Hosts
Описание
Эта роль устанавливает веб-сервер Nginx и настраивает виртуальные хосты на основе переданных переменных.

Структура
roles/nginx-vhosts/: основная роль
playbook.yml: файл запуска
inventory.ini: инвентарь
Использование
Переменные задаются в файле playbook.yml в секции vars:

vars:
 sites:
 - "site1.com"
 - "site2.com"
