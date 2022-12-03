apache
=================

setup Apache web server

OS Platform
-----------------

### Debian

- bullseye
- buster

Role Variables
--------------

### `apache_packages`

インストールするパッケージ

### `apache_modules`

モジュールの設定

### `apache_vhosts`

バーチャルホストの設定

### `apache_secrity_cfg`

全体のセキュリティ設定

### `apache_extra_cfg`

追加設定

Example Playbook
--------------

```yaml
- hosts: servers
  roles:
    - role: apache
```

License
--------------

Apache License 2.0
