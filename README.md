# Ansible role for install Taiga.io project
1. Install Ansible [Install Ansible](http://docs.ansible.com/ansible/intro_installation.html)
2. Create user taiga
3. Clone repository
4. Run playbook script
`ansible-playbook install.yml -e 'domain=taiga.local' -K`
5. Login Taiga with:
⋅⋅5.Login:`admin`
⋅⋅5.Password:`123123`