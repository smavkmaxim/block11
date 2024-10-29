# block11

 git clone https://github.com/smavkmaxim/block11.git ~/task

ansible-playbook -i ~/task/inventory.yaml ~/task/nginxsecret.yml

ansible-playbook -i ~/task/inventory.yaml  ~/task/nginxsecret.yml -e "@~/.ansible/$USER.vault" --vault-password-file .vault_pass.txt

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
