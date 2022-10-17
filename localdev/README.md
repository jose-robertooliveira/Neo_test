# Desafio NEOWAY
___ 
Primeira etapa, consta na subpasta de nome ETL, comentários do que foi feito para transformação do arquivo "base_teste" em um jupyter notebook.
___

## _Instruções de execução_

1 - Execute o comando no terminal: 
* docker-compose up -d.

2 - Caso queira acompanhar os logs em tempo de execução execute: 
* docker-compose up.

3 - Pode-se verificar a persistencia dos dados do arquivo new_base.sql dentro da pasta ->(docker-entrypoint-initdb.d/), bem como executar queries, em uma interface de banco de dados qualquer.

4 - Parar a execução do container: 
* docker-compose stop.

5 - Remover a imagem do assim como a network:
* docker-compose down, após isso pode-se iniciar um novo container com qualquer dos comando nas instruções 1 ou 2.

Obs: Antes de iniciar um novo container é recomendado a exclusão das sobras do container anterior na memoria, use: 
* docker system prune -a.
