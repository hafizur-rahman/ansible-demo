# ansible-demo
Install ansible via pip
```
$ sudo pip install ansible
```

On CentOS 6.5, OpenSSH update was necessary. (This helped to avoid ```fatal: [default] => using -c ssh on certain older ssh versions may not support ControlPersist, set ANSIBLE_SSH_ARGS="" (or ssh_args in [ssh_connection] section of the config file) before running again```.)

```
$ sudo yum update openssh

...
Updated:
  openssh.x86_64 0:5.3p1-104.el6_6.1
```

$ vagrant up


