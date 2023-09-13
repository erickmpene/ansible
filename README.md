#### How Install ansible to CentOS
##### 1. Install epel-release
```sh
sudo yum update
sudo yum install -y epel-release
```
##### 2. Install Ansible
```sh
sudo yum install -y ansible
ansible --version
```
### View Configuration
```sh
ansible-config view # view current file contents
ansible-config list # view all configuration
ansible-config dump # show current settings
ansible-config dump --only-changed # show only non-default settings
```

### Search specific host
```sh
ansible -i "MyIventory" --list-hosts "NameOfYourHost"
```
