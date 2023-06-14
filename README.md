apache
=================

setup Apache web server

OS Platform
-----------------

### Debian

- bookworm
- bullseye

Role Variables
--------------

設定方法の詳細については[defaults/main.yml](defaults/main.yml)のサンプルコードを参照してください。

### `apache_packages`

インストールするパッケージ

### `apache_append_goaccess_repository`

goaccessリポジトリを追加するか否か

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
