# ansible-dev

Mac setup and configuration via Ansible.

## Install

### Install Xcode

Install Xcode, command line tools.

```
xcode-select --install
```

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

### Generate SSH key

```
ssh-keygen -t rsa -b 4096 -C "example@example.com"
pbcopy < ~/.ssh/id_rsa.pub
# Add your SSH key to your GitHub account
```

### Clone Repository

```
git clone git@github.com:calorie/ansible_dev.git
cd ansible_dev
```

### Run Ansible

```
ansible-playbook --ask-become-pass -i inventory main.yml
```

## TODO

- IME
- Finder Sidebar
- Mute sound effect
- Move focus to next window
- Touch Bar
