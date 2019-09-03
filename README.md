# ansible-dev

## Install

### Install Homebrew

```
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
brew doctor
```

### Install Ansible

```
brew install ansible
ansible --version
```

### Run Ansible

```
ansible-playbook --ask-become-pass -i hosts/local localhost.yml
```
