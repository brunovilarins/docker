# docker
Rodar o comando:

Para criar os containers NGINX e LetsEncrypt:
docker-compose up -d

Para criar os dockers dos projetos é só entrar na pasta de cada projeto:
Exemplo: Rodar o comando dentro da pasta projetos/prj1
docker-compose up -d

Para que o NGINX reconheça os novos containers, reiniciar os dockers do NGINX.
Usar o comando docker-compose restart

Para cada projeto novo, é só configurar o docker-compose em uma nova sub pasta de projetos.
