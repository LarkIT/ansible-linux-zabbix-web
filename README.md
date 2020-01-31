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
| zabbix_on_aws | Optional | false | Boolean | When enabled, places a blank file in httpd default docroot to make AWS ELB health checks work |
| zabbix_timezone | Optional | America/Denver | String | The PHP timezone for Zabbix frontend |
Refer to Galaxy role documentation for other variables