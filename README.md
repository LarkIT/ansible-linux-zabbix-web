# Lark IT Ansible Zabbix Web Role

Install and configure Zabbix web frontend

## Operating Systems
This role is known to work on the following operating systems:
- CentOS 7

## Dependencies
This role epends on the following Ansible Galaxy roles:
- dj-wasabi.zabbix-web (https://galaxy.ansible.com/dj-wasabi/zabbix-web)

## Variables
| Variable | Required? | Default Value | Type | Description |
|----------|--------|-------|------|--------|
| zabbix_version | Optional | 4.2 | String | Zabbix package major version |
| zabbix_setsebool_httpd_can_connect_ldap | Optional | false | Boolean | Enables httpd_can_connect_ldap SELinux boolean |
Refer to Galaxy role documentation for other variables