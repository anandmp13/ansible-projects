Sensu.agent
=========
This role installs and configures the sensu-agent on th agent node
#A brief description of the role goes here.

Requirements
------------
the nde should be defined in the hosts of the controle node to br connect and ssh-key to be known
among four nodes for the sensu cluster we need 3 sensu backend nodes and 1 sensu agent node


#Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------
The ip of all the nodesand hostname of the nodes are defined in the var sections of the nodes. we want the ips of different nodes also so we cannot use magic variables or hostvars thats why we defined the host name and ip of the nodes in the var section of the roles.


#A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

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

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
