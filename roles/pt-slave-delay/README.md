Role Name
=========

Добавляет пользователя в mariadb для подключения, установливает и настраивает pt-slave-delay для el7
 

Role Variables
--------------
delay: 8h # на какое время будет отставать
interval: 3m # как часто проверять
user: delayed_repl # пользователь для подключения
password: top-secret  # пароль для подключения
host: localhost

