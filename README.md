# ansible


Sample usage

```
# update ansible/roles/ipa-client/default/main.yaml

ansible-playbook -i hosts -e @inventory/ipaclients.json playbooks/configure-ipaclients.yml

```
