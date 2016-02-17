# play-with-ansible
ansible practice

## Usage
Create `hosts` file
```
[test-server]
<<ip-address>> ansible_port=<<ssh-port>> ansible_user=<<login-user>>
```

run `ansible-playbook -i hosts --ask-sudo-pass -vvv site.yml`
