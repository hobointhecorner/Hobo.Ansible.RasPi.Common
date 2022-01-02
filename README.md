# Hobo.Ansible.RasPi.Common

## Install Role
### Ansible Galaxy
[Ansible Galaxy](https://galaxy.ansible.com/docs/using/installing.html) can be used to install the role:
`ansible-galaxy install git+https://github.com/hobointhecorner/Hobo.Ansible.RasPi.Common.git[,<branch or commit hash>]`

### Git submodule
From inside your playbook roles directory:
`git submodule add [-b <branch or tag>] https://github.com/hobointhecorner/Hobo.Ansible.RasPi.Common.git`

## Variables
| Name             | Type   | Required | Default | Desctiption |
|------------------|--------|----------|---------|-------------|
| rpi_hostname     | string | No       | ansible inventory_hostname | Hostname for the raspberry pi |
| rpi_new_password | string | No       |         | Set a new password for the `pi` user |
| rpi_autologin    | bool   | No       | false   | Enable autologin |
| rpi_enable_ui    | bool   | No       | false   | Enable desktop UI |
