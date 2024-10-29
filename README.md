# block11

ansible-playbook -i ~/task/inventory.yaml nginxsecret.yml

ansible_rebrain


ansible-vault create ~/.ansible/"$USER".vault - создание vault

ansible-vault create ~/.ansible/"$USER".vault
New Vault password:
Confirm New Vault password:


ec2-user.valut:

---
ansible_runas_user : ec2-user
ansible_runas_pass : SecretPassword@!
ansible_user : ec2-user
ansible_password: SecretPassword@!
