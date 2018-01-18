Ansible Role: kubernetes kubeadm install
=========

Install [kubeadm](https://kubernetes.io/docs/reference/setup-tools/kubeadm/kubeadm/) on Linux.

Requirements
------------

None.

Role Variables
--------------

None.

Dependencies
------------

None.

Example Playbook
----------------

```yml
- hosts: all
  roles:
    - { role: djx339.k8s-kubeadm-install }
```

License
-------

BSD

Author Information
------------------

This role was created by [Daniel D](https://github.com/djx339).
