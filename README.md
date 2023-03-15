# nextcloud-ansible-provision
Ansible provision for clean nextcloud server
DB - postgresql

WIP:
   To do:
        - Create db user
        - occ maybe?

RUN:
    - edit `hosts` and `inventory/nextcloud` files, insert your desired hosts
    - run `ansible-playbook -i inventory/nextcloud  provision.yml`

