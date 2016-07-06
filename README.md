# Ansible role for install Taiga.io project
1. Install Ansible [Install Ansible](http://docs.ansible.com/ansible/intro_installation.html)
2. Create user taiga
3. Clone repository from user taiga `https://github.com/belaytzev/Taiga-Ansible.git`
4. Run playbook script from user taiga
`ansible-playbook install.yml -e 'domain=taiga.local' -K`
5. Login Taiga with:
 * Login:`admin`
 * Password:`123123`
