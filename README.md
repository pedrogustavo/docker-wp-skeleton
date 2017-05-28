## Iniciando
1 - Copiar os arquivos deste repositorio para a pasta do projeto

2 - Baixar a versão do wordpress que desejar e decompactar para a pasta `wp`

3 - executar o seguinte comando para levantar o banco `docker-compose up -d db`

4 - iniciar wordpress com o seguinte comando `docker compose up -d wp`

## Informações Complementares
1 - Permissões
- Execute o seguinte comando `chmod -R 777 wp`

2 - Importar Banco  
```
mysql -uroot -proot nomedobanco < /import/nomedoarquivo.sql
```
