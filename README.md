# ansible-playbooks
Repository for personal ansible playbooks

## Playbooks

### server-setup.yaml

use with `-K` to get interactiely asked for become password.

    ansible-playbook -K server-setup.yaml


### worksation-setup.yaml

Note: The workstation expects that the base system is Arch linux (or anything using pacman and AUR for package management.)

Steps:

1. install [kewlfft ansbile-aur](https://github.com/kewlfft/ansible-aur) collection from ansible galaxy
2. run the playbook

        ansible-playbook -K workstationsetup.yaml