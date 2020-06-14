# Ansible Playbook para instalação do WordPress

Fonte: https://www.udemy.com/course/ansible-para-sysadmin/
#
O playbook foi elaborado para dois hosts executarem a aplicação WordPress.

Um host com CentOS 7 rodando mariadb/mysql,

e outro rodando Ubuntu 18.04 com nginx, php e wordpress,

Modifique o playbook para readequar ao seu cenário caso seje diferente.

Altere o arquivo hosts para o seu cenário.
#
play> ansible-playbook -i hosts playbook.yml
#
Fico a disposição para esclarecer dúvidas:

willian.romao@outlook.com.br
