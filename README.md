# Chat Multicast Java - LDAMD
> O trabalho tem como objetivo desenvolver uma aplicação de Chat em java utilizando o protocolo Multicast. 

## Requisitos do programa

1. O servidor deve gerenciar apenas uma sala de bate papo.
2. O cliente deve ser capaz de solicitar acesso à sala de bate papo.
3. O servidor deve manter uma lista dos membros da sala.
4. O cliente deve ser capaz de enviar mensagens para a sala.
5. O cliente deve ser capaz de sair da sala de bate papo.

## Observações

* A princípio foi definido um IP fixo, para que dessa forma, todos os usuários que forem conectados, sejam conectados na mesma sala (obedecendo o requisito 1).
* Ao inicializar a aplicação, aparece uma opção permitindo que o usuário escolha se quer ou não ser conectado à sala de bate papo (obedecendo o requisito 2).
* Ao enviar uma mensagem na sala de bate papo, é mostrado para a pessoa que RECEBEU o nome da pessoa que ENVIOU acompanhado da mensagem, desta forma, é possível visualizar que a lista de membros é mantida dentro do servidor (obedecendo o requisito 3).
* Ao digitar a mensagem que deseja enviar e apertar "ENTER" a mensagem é enviada para todos os membros da sala (obedecendo o requisito 4).
* Ao digitar "Exit/exit" o cliente é desconectado e a aplicação é finalizada (obedecendo o requisito 5).

## Aluno

* Raíssa Carolina Vilela da Silva - 604697 - [raissavilela](https://github.com/raissavilela)

## Professor responsável

* Hugo Bastos de Paula - [hugodepaula](https://github.com/hugodepaula)

## Ferramenta para desenvolvimento
[![Work in Repl.it](https://classroom.github.com/assets/work-in-replit-14baed9a392b3a25080506f3b7b6d57f295ec2978f6f33ec97e36a161684cbe9.svg)](https://classroom.github.com/online_ide?assignment_repo_id=2965230&assignment_repo_type=AssignmentRepo)
