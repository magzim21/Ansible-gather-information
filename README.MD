# GATHER VARIOUS INFORMATION FROM HOSTS
### This Ansible role use useful for those freshmans who just came to project and not familiar with infrastructure etc.

**Look closely to  ./my_role/tasks**
You can exclude some plays by commenting out those ones in ./my_role/tasks/main.yml



Command to run
`ansible-playbook role.yml --extra-vars="hosts_group=<host group from hosts file>"`

After role ran successfully, have a look in brand new folder "results"
You will find there information about:
* Cronjobs
* Locations of specific files
* Hardware info
* All users bash history
* All user's logins
* Network information
* All processes information, including environment varables!
* Docker info, images, containers
