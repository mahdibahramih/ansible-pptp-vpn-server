# ansible-pptp-vpn-server
its a simple ansible playbook file for setup a pptp vpn server.<br/> 
remember: unfortunately its just work on ubuntu,debian servers :)
# how can use
# 1- install ansible
sudo apt update

sudo apt install software-properties-common

sudo apt-add-repository --yes --update ppa:ansible/ansible

sudo apt install ansible


# 2- Run playbook 
### Notify that You must modify variables and hosts in vars.yml and hosts file.<br/> also you must modify users.j2 file.

ansible-playbook pptpd.yml -i hosts
