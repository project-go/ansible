# Project GO use Red Hat® Ansible®!
IT Automation with Red Hat® Ansible®!

#### ansible-playbook -T 30 -b --ask-become-pass rhel_update.yml

#### rhel_install_google_chrome.yml


## Ansible AD HOC Command Examples

#### Mem info
```shell
ansible t1 -i inv -m shell -a "cat /proc/meminfo|head -2"
```

#### Reboot Linux
```shell
ansible t1 -i inv -a "/sbin/reboot" -u $USER --become --ask-become-pass
```

