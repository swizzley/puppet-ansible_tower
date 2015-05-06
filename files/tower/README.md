Ansible Tower Deployment
========================

This collection of files provides a complete set of playbooks for deploying
the Ansible Tower software to a single-server installation. It is also to
install Tower to the local machine, or to a remote machine reachable by SSH.

Please read http://releases.ansible.com/ansible-tower/docs/tower_user_guide-latest.pdf for
full documentation and installation/upgrade instructions.

To install or upgrade, start by running ./configure in this directory. After
doing so, run ./setup.sh.

> *WARNING*: The playbook will overwrite the content
> of `pg_hba.conf` and strip all comments from `supervisord.conf`.  Run this
> only on a clean virtual machine if you are not ok with this behavior.
