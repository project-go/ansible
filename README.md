# Project GO use Red Hat® Ansible®!
IT Automation with Red Hat® Ansible®!


## Ansible AD HOC Command Examples


#### Copy file
```Shell
ansible t1 -i inv -m ansible.builtin.copy -a "src=/file dest=/tmp/file"
```

#### Mem info
```shell
ansible t1 -i inv -m shell -a "cat /proc/meminfo|head -2"
```

#### Reboot Linux
```shell
ansible t1 -i inv -a "/sbin/reboot" -u $USER --become --ask-become-pass
```

