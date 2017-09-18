# Provisioning scripts for a movim server

```
ansible-playbook --ask-vault-pass -e "ansible_user=<user>" setup-jp-movim.yml
```

## TODO

- Move package building out of this. Stop doing it on the server
- Make it more parametrable.
