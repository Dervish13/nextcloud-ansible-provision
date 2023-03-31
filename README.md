# nextcloud-ansible-provision
Ansible provision for clean nextcloud server
DB - postgresql

WIP:
   To do:
        - Create db user
        - occ maybe?
        - setup SSL certificate

RUN:
    - edit `hosts` and `inventory/nextcloud` files, insert your desired hosts
    - edit roles/database/vars/main.yml and set username and password for database connection
    - run `ansible-playbook -i inventory/nextcloud  provision.yml`
    - login into the machine and setup SSL certificate, and update nginx conf ( nextcloud doesn't
      work over http only https)
