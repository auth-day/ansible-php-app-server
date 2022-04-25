# ansible-php-app-server

```
ansible version = 2.9 or >
```

How to run
```
ansible-galaxy install -r requirements.yml
```

then paster ssh keys variables for the user 
```
roles/ansible-role-user-management/defaults/main.yml
users_with_items.ssh_public_key
```
Run
```
ansible-playbook playbook.yml -i hosts
```
