### service part ###
## This is about installing front/back components

TIPS: Ensure that you installed ansible

Replace ipv4 adresses in hosts and nginx.yml files to your data

# CLONE repo and RUN playbooks via command below

#: git-clone https://github.com/LeeroyJenkins92/skbx_service.git

#: ansible-playbook -b flaskapp.yml -vvv

#: ansible-playbook -b nginx.yml -vvv

AFTER deployment connect in your browser to ipv4 adress of your LOAD-BALANCER HEAD
It should return your flask app
