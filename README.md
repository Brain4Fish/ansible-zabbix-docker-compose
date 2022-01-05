# ansible-zabbix-docker
Install Dockercomposed Zabbix server on Debian/Ubuntu machine

Based on other version of **[ansible-zabbix-docker](https://github.com/zabbix/ansible-zabbix-docker)**


## Variables

`zabbix_data_path: "/usr/infra/zabbix"` - Path to zabbix data volumes

`zabbix_timezone: - "Etc/GMT"`

`zabbix_name: - "Zabbix Server"`

`zabbix_database: zabbix` - Zabbix database name

`zabbix_db_user: zabbix` - Zabbix database user name

`zabbix_db_password: zabbix`-  Zabbix database password

`zabbix_mysql_root_password: root_pw` - Database root password


## Example
    - hosts: zabbix-server
      roles:
        - role: ansible-zabbix-docker


## Author
Mikhail `Brain4Fish` Kozlov
