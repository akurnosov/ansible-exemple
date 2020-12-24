# ansible-exemple

# playbook-updater.yml
Install pakages: vim, less, bash-completion & Update OS to latest version

### How to Use ###
* Eddit group_vars/ALL & hosts.txt
* Use command for start playbook 

    
Command:

    ansible-playbook playbook-update.yml



# playbook-user-add.yml 
Add new user, generate SSH-key, add your local public-key to authorized_key

### How to Use ###
* Eddit params in playbook-user-add.yml 
* Use command for start playbook 

    
Command:

    ansible-playbook playbook-user-add.yml 
