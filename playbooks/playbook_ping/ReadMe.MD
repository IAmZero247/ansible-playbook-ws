## Login as ansadmin

  sudo su - ansadmin
  whoami

  pwd
  /home/ansadmin

  cd /opt
  sudo mkdir ansible

  sudo chown ansadmin:ansadmin ansible
  ll -a

  cd ansible




## Commands
1. Adhoc Command 'ansible all -m ping -i inventory.txt'

2. 'ansible-playbook playbook_ping_test.yaml -i inventory.txt'
