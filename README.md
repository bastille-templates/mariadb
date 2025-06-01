# MariaDB
MariaDB is an open-source relational database management system that is a development of MySQL

## Now apply template to container
```sh
bastille create dbms 14.1-RELEASE YourIP-Bastille
bastille bootstrap https://github.com/bastille-templates/mariadb
bastille template dbms bastille-templates/mariadb
```

## License
This project is licensed under the BSD-3-Clause license.