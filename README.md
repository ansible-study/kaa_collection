# Ansible Collection - kaa.kaa_collection

Content Role: kaa_own_role 
and Module: kaa_my_own_module




Role kaa_own_role   
----------------   
For running kaa_my_own_module.  
    
default values:  
  name: 'hello.txt'  
  path: /tmp/folder1/  
  content: 'My Content'     

Example Playbook for check module with role
```Ansible
----------------
---
- name: test my new module  
  vars:  
    name: 'hello2.txt'  
    path: /tmp/folder2/  
    content: 'My Content2'  
  hosts: localhost   
  roles:   
    - kaa.kaa_collection.kaa_own_role   
```


    
