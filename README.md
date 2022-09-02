# ideal-palm-tree


# Instructions on updating systems
0. create static inventory 
1. ansible-playbook -i inventory  stop_services.yaml 
2. ansible-playbook -i inventory  update.yaml
4. ansible-playbook -i inventory  reboot.yaml
5. ansible-playbook -i inventory  start_services.yaml
6. ansible-playbook -i inventory  verify.yaml