Role Name
=========

Ansible_Cisco_ios_12.2_hardening_role



Requirements
------------

Cisco devices running 12.2 or similar ios version.



Role Variables
--------------

Take a peak in the vars/main.yml

  username: <username>
  password: <enable password>
  auth_pass: <privledge-exec password>
  
  

Dependencies
------------

None



Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:


- hosts: ios
  gather_facts: no
  connection: local
  roles:
    - Ansible_Cisco_ios_12.2_hardening_role 
    
    
    

License
-------

BSD

Author Information
------------------

Colin McCarthy
Check out my website www.thenetwork.engineer
