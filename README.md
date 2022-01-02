# Hobo.Ansible.RasPi.Common

## Install Role
From inside your playbook roles directory:
`git submodule add [-b <branch or tag>] https://github.com/hobointhecorner/Hobo.Ansible.RasPi.Common.git`

## Variables
| Name             | Type   | Required | Default | Desctiption |
|------------------|--------|----------|---------|-------------|
| rpi_hostname     | string | No       | ansible inventory_hostname | Hostname for the raspberry pi |
| rpi_new_password | string | No       |         | Set a new password for the `pi` user |
| rpi_autologin    | bool   | No       | false   | Enable autologin |
| rpi_enable_ui    | bool   | No       | false   | Enable desktop UI |
