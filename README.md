# kubernetes-ansible
ansible-galaxy install geerlingguy.swap
ansible-galaxy install geerlingguy.docker
ansible-galaxy install geerlingguy.kubernetes
edit hosts with your node names and ip addresses
ansible-playbook -i hosts kubernetes.yml -k -K
log onto master node node and run "kubectl get nodes" 
