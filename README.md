## ALT SCHOOL SEMESTER EXAMINATION

### What is this?
A PHP Laravel App 

> Run in terminal:
* Ping server: ` ansible web --private-key exam-server_key.pem -m ping -i inventory.txt `   
* Run tasks: `ansible-playbook -i inventory.txt --private-key exam-server_key.pem main.yml` 
* Test pgsql db: ` psql -h 13.72.103.188 -p 5432 -d laraveldatabase -U postgres `


### Features

> Ansible
* Ansible roles
* Ansible Handlers
* Ansible Pretasks
* Installation Bash Scripts

> Laravel App
* Composer for Dependency
* Apache2 reverse proxy
* Sql server

### Improvements
* Use more variables
* Use more relative paths





