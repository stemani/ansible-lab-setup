# ansible-lab-setup

Ansible master-slaves(4) Lab on Ununtu with SSH keys setup and initial hosts file defined.

**Pre-requisites**

Docker (Install steps): https://docs.docker.com/install/

**Setup Instructions**

git clone https://github.com/stemani/ansible-master-slaves.git

cd ansible-master-slaves

docker-compose up -d

Docker Install steps: https://docs.docker.com/install/

This will create one Master and 4 slaves containers.All 5 containers should be up and running.

docker ps 

**Master:**

Install Ansible, vim on Ubuntu

Generate SSH Keys


**Slave:**

Install Python, vim

SSH Keys copied over from master for SSH passwordless login
