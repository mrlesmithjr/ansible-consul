Role Name
=========

Installs, configures and build a Consul cluster. https://www.consul.io/

Requirements
------------

None

Role Variables
--------------

````
---
# defaults file for ansible-consul
consul_bin_path: /usr/local/bin
consul_bind_interface: eth1
consul_config_dir: /etc/consul.d
consul_config_file: /etc/consul.conf
consul_data_dir: /var/consul
consul_datacenter: test-dc1
consul_dl_file: '{{ consul_version }}_linux_amd64.zip'
consul_dl_url: https://dl.bintray.com/mitchellh/consul
consul_encryption_key: qLLp1YCJzp9E/xhg11qkdQ==  #generate using 'consul keygen'
consul_group: consul
consul_home: /opt/consul
consul_interface: eth1
consul_log_file: /var/log/consul
consul_mysql_password: consul
consul_mysql_user: consul
#consul_services:
#  - name: elasticsearch
#    port: 9200
#    tags:
#      - elasticsearch
#      - es
#      - testing
#    check_script: 'curl localhost:9200 > /dev/null 2>&1'
#    check_interval: 10s
#  - name: mysql
#    port: 3306
#    tags:
#      - mysql
#      - testing
#    check_script: "mysql -u{{ consul_mysql_user }} -p{{ consul_mysql_password }} -h localhost -e 'select now()'"
#    check_interval: 10s
#  - name: nginx
#    port: 80
#    tags:
#      - nginx
#      - testing
#    check_script: 'curl localhost:80 > /dev/null 2>&1'
#    check_interval: 10s
#  - name: redis
#    port: 6379
#    tags:
#      - redis
#      - testing
#    check_script: 'redis-cli ping'
#    check_interval: 10s
consul_ui_dl_file: '{{ consul_version }}_web_ui.zip'
consul_user: consul
consul_version: 0.5.2
````

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: mrlesmithjr.consul }

License
-------

BSD

Author Information
------------------

Larry Smith Jr.
- @mrlesmithjr
- http://everythingshouldbevirtual.com
- mrlesmithjr [at] gmail.com
