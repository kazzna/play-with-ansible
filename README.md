# play-with-ansible
ansible practice

## Usage
Create `hosts` file
```
[test-server]
<<ip-address>> ansible_port=<<ssh-port>> ansible_user=<<login-user>>
```

before run ansible, may add ssh-key by `ssh-add -t 3600 <<path/to/ssh_key>>`

run `ansible-playbook -i hosts --ask-sudo-pass -vvv site.yml`
