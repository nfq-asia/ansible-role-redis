# Install Redis from source Ubuntu 18.04

## Description

This role will download and install Redis from source code base on version defined before.
This is redis version "Redis-5.0.2"

## How to use

1. Run ansible

```
$ ansible-playbook -i hosts redis.yml
```

## Note

We can change version, directory install ... in vars/main.yml
