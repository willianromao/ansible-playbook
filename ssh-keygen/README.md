# Ansible Playbook para troca de chaves de acesso SSH entre hosts

A playbook foi elaborada para geração de um par de chaves nos hosts master

e instalada nos hosts slave.

Ex: Você tem um parque de hosts que deseja automatizar tarefas usando Ansible

ou Rundeck e não deseja informar a senha de acesso aos hosts nas suas tarefas.
#
A playbook considera que o usuário usado para alcançar os hosts

será o mesmo para a trocada de chaves.

Considera também que a porta ssh é a mesma para todos os hosts, masters e slaves.

Caso seu cenário seje diferente, revise a playbook.
#
Use o arquivo de inventário hosts para definir os hosts master

e o arquivo roles/ssh-keygen/vars/main.yml para os hosts slave.
#
Requisito para a execução da playbook é a instalação do sshpass nos hosts masters.
#
play> ansible-playbook -i hosts playbook.yml
#
Fico a disposição para esclarecer dúvidas:

willian.romao@outlook.com.br
