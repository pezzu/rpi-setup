## Setup

  1. [Install Ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html): `pip3 install ansible`.
  1. Install requirements: `ansible-galaxy collection install -r requirements.yml`
  1. Run the playbook: `ansible-playbook main.yml`


## List of tasks

- [ ] Configure hostname
- [ ] Configure user / password
- [ ] Setup SSH key
- [ ] System upgrade
- [ ] EEPROM upgrade
- [ ] Setup unattended upgrades
- [x] Setup timezone
- [ ] Setup locale
- [ ] Setup tmpfs mounts for write intensive folders
- [x] Enable/Disable Bluetooth
- [x] Enable/Disable WiFi
- [ ] Enable/Disable HDMI
- [x] Overclock
- [ ] Modify custom boot config parameters
- [x] Install Docker
- [ ] Install rpi-monitor
- [ ] Install zram
