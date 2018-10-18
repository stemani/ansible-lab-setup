# ansible-master-slaves

Docker Images, composefile and docker files for Ansible master-slave setup on Ununtu with SSH keys setup and initial hosts file defined.

**Setup Instructions**
*git clone https://github.com/stemani/ansible-master-slaves.git*
*cd ansible-master-slaves*
*docker-compose up -d*

This will create one Master and 4 slaves containers.

Master:
Install Ansible, vim on Ubuntu
Generate SSH Keys
Slave:
Install Python, vim
SSH Keys copied over from master for SSH passwordless login
