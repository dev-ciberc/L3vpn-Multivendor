# L3VPN-SV
L3VPN Multivendor Service

The main objective of the following application is to create a l3VPN in an automated multivendor way (BGP as CE-PE), using it only you have to install ansible version 2.6 or later to run it, to see more details on how to use it see the following video where I give step by step an example with an emulated multivendor network.

Requirements:
Ansible 2.6+
python3.6+
napalm last version (pip install napalm-ansible)

See the following video for more detail:
https://www.youtube.com/watch?v=MnZQZNcFetk&t=576s


commands to run this Role in ansible
Only put 3 commands to ejecute all service l3VPN Multivendor deployment (Update the model with your variables)

ansible-playbook -i host generate-model.yml
ansible-playbook -i host generate-template.yml
ansible-playbook -i host deploy-service.yml

enjoy it.
