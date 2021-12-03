# nginx_ansible

 
#### Playbook по установке nginx с самоподписанным сертификатом.
#### При открытии в браузере потребуется подтвердить исключение безопасности.
#### Перед запуском необходимо указать адрес сервера для установки nginx в hosts.ini:

#### [nginx_srv]
#### nginx ansible_host=<ip address>

## Запуск:
### ansible-playbook install_nginx.yaml
