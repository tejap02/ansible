ansible-vault create aws_credentials.yml
aws_access_key_id: AKIA5WLTTE6SUSF6PK6612
aws_secret_access_key: 4oM6g5G2Fv4jpYhRf9a0cp2u++9IM1MyFOFnY43k12
ansible-playbook your_playbook.yml --ask-vault-pass

ansible-playbook your_playbook.yml --vault-password-file vault_pass.txt
