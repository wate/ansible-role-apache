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

### [defaults/main.yml](defaults/main.yml)

設定方法の詳細については[defaults/main.yml](defaults/main.yml)のサンプルコードなどを参照してください。

#### `apache_packages`

インストールするパッケージ

#### `apache_append_goaccess_repository`

goaccessリポジトリを追加するか否か

#### `apache_modules`

モジュールの設定

#### `apache_vhosts`

バーチャルホストの設定

#### `apache_secrity_cfg`

全体のセキュリティ設定

#### `apache_extra_cfg`

追加設定

### [vars/main.yml](vars/main.yml)

設定値については[vars/main.yml](vars/main.yml)を参照してください。

#### `apache_config_base_dir`

#### `apache_goaccess_apt_key_url`

#### `apache_goaccess_apt_key_dest`

#### `apache_module_available_dir`

#### `apache_module_enabled_dir`

#### `apache_conf_available_dir`

#### `apache_conf_enabled_dir`

#### `apache_site_available_dir`

#### `apache_site_enabled_dir`

#### `apache_snippet_dir`

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
