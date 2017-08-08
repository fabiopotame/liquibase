## Versionamento de Banco de Dados com Liquibase

Baixe a aplicação, configure o aquivo "execute" na raiz da aplicação com os dados de seu banco de dados.

#### Executa update na base de dadis inserindo o conteúdo do changelog criado
$ ./execute update

#### Executa o rollback do último changelog inserido
$ ./execute rollbackCount

#### Para visualizar todos os comandos
$ ./execute
