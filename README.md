# README.md
# Ansible Role: mats116.locale

An Ansible role that configure locale on **Ubuntu 14.04 LTS**

## Requirements

none

## Role Variables

Available variables are listed below, along with default values:

```yaml
locale_name: ja_JP
locale_encoding: UTF-8
```

## Dependencies

none

## Example Playbook

```yaml
- hosts: web-server
  roles:
    - role: mats116.locale
```

## License

MIT
