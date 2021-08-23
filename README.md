Ansible-playbook, разворачивающий [приложение] с помощью Docker Compose

### Настройка

Создать файл .env`, указав желаемые логины и пароли для базы данных.

Например: 
```
MYSQL_ROOT_PASSWORD=your_root_password
MYSQL_USER=your_wordpress_database_user
MYSQL_PASSWORD=your_wordpress_database_password
```

Запустить плейбук, указав целевой сервер:
```
ansible-playbook -l you_server install.yml
```

[приложение]: https://github.com/mihailag/sf__wordpress_experimental.git