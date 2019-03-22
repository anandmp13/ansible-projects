maria.db
=========
This role install and configures the high availability galera cluster for MariaDB. This containes Master-Master configuration it includes the packages to be installed and configuring the server.conf file located in all nodes present at /etc/my.conf.d/server.conf, this helps to setup all the nodes present in the cluster.


#A brief description of the role goes here.

Requirements
------------
Selinux should be disabled
firewall service could be made disabled or you can enable and open ports for the mysql and galera (3306,4567,4568,4444)


#Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------
Packages to be installed 
root password 
and the nodes that comes in conf file "gcomm:" section.


#A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------
Add the nodes in the inventory file and hosts of controle node
copy ssh id to the nodes



An optional section for the role authors to include contact information, or a website (HTML is not allowed).



##############################################################################################################


