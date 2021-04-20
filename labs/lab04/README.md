#LAB04
- Criar um playbook direcionado ao servidor host1
  - Adicionar um custom fact no servidor
    - Crie um arquivo chamado "cringerlabs.fact" e adione os fatos abaixo
      - Group: webserver
        - Variable: role 
          - Value: webserver
      - Group: general
        - Variable: port
          - Value: 80
        - Variable: package
          - Value: nginx
    - Leve este arquivo ao servidor no diretório correto.

- Criar um segundo playbook para consumir os facts criados no playbook anterior gerando a frase abaixo:
    A função do servidor host1 é '***role***', 
    o pacote que instala o serviço principal é o '***package***',
    que é executado na porta '***port***'/tcp."
