## Iniciando
    1 - Copiar os arquivos deste repositorio para a pasta do projeto
    2 - Baixar a versão do wordpress que desejar e decompactar para a pasta `wp`
    3 - executar o seguinte comando `docker-compose up -d db`
    4 - conectar dentro do container `docker exec -it db bash`
    5  - se logar no mysql `mysql -uroot -ppassword`
    6 - criar database `create database <name>`
    7 - iniciar wordpress com o seguinte comando `docker compose up -d wp`

## Informação Complementares
1 - Dados do banco
```
    Username: root
    Password: password
    Database Host: db
```
2 - Permissões
    - Execute o seguinte comando `chmod -R 777 wp`

* comando para importar um banco `mysql -uroot -proot nomedobanco < /import/nomedoarquivo.sql`