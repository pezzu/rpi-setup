## Setup

  1. [Install Ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html): `pip3 install ansible`.
  1. Install requirements: `ansible-galaxy collection install -r requirements.yml`
  1. Run the playbook: `ansible-playbook main.yml`


## List of tasks

- [ ] Configure hostname
- [ ] Configure user / password
- [ ] Setup SSH key
- [x] Distribution upgrade
- [x] EEPROM firmware update
- [ ] Setup unattended upgrades
- [x] Setup timezone
- [ ] Setup locale
- [x] Setup tmpfs mounts
- [x] Enable/Disable Bluetooth
- [x] Enable/Disable WiFi
- [x] Overclock
- [ ] Modify custom boot config parameters
- [x] Install Docker
- [ ] Install rpi-monitor
- [ ] Install zram

[![CI status](https://github.com/pezzu/rpi-setup/actions/workflows/ci.yml/badge.svg)](https://github.com/pezzu/rpi-setup/actions/workflows/ci.yml)
