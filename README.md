to set up the MYSQL server (on windows)

Install Cygwin https://www.youtube.com/watch?v=QonIPpKodCw

Install & start MYSQL server https://www.youtube.com/watch?v=w5TsNZRWBNE

```
Tze Zhao@DESKTOP-EB90EDS /cygdrive/c/Users/tzcho/cygwin-installer
$ mysqld_safe &
[1] 1777

Tze Zhao@DESKTOP-EB90EDS /cygdrive/c/Users/tzcho/cygwin-installer
$ mysqld_safe &200408 12:47:17 mysqld_safe Logging to '/var/lib/mysql/DESKTOP-EB90EDS.err'.
200408 12:47:18 mysqld_safe Starting mysqld daemon with databases from /var/lib/mysql
```

```
Tze Zhao@DESKTOP-EB90EDS /cygdrive/c/Users/tzcho/cygwin-installer
$ mysql -u root
Welcome to the MariaDB monitor.  Commands end with ; or \g.
Your MariaDB connection id is 9
Server version: 10.3.14-MariaDB Source distribution

Copyright (c) 2000, 2018, Oracle, MariaDB Corporation Ab and others.

Type 'help;' or '\h' for help. Type '\c' to clear the current input statement.

MariaDB [(none)]>
```

You can now execute mysql commands

To leave, type "exit"
```
MariaDB [(none)]> exit
Bye
```

To stop the server
`$ mysqladmin -u root shutdown


Create flask app https://www.youtube.com/watch?v=6L3HNyXEais