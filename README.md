# Ansible MongoDB
Install MongoDB on Centos/Red Hat/Fedora

## Installation
- Clone this repository inside your ```roles``` directory

- In your playbook:

```yaml
roles:
  - mongodb
```

## Usage

```yaml
vars:

  mongodb:
    dbpath: /var/lib/mongo
````
