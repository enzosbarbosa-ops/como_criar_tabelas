
## mysql -u (usuario) -p

O que faz: É o comando do terminal do seu sistema operacional para conectar ao servidor MySQL. O -u especifica o nome de usuário (ex: root) e o -p indica que o sistema solicitará a senha de acesso em seguida.

## show databases

O que faz: Lista todos os bancos de dados existentes no servidor que você acabou de acessar. Ele serve para você visualizar o que já está criado antes de escolher qual banco quer usar (com o comando use nome_do_banco;).

## create table (nome da tabela)

O que faz: Cria a estrutura de uma nova tabela no banco de dados ativo. É aqui que você define o nome da tabela, quais colunas ela terá (ex: id, nome, email) e quais tipos de dados cada coluna aceita.

## insert into

O que faz: Insere novos dados (linhas/registros) dentro de uma tabela que já foi criada. É o comando usado para cadastrar novas informações.

## select * from

O que faz: Consulta e exibe os dados armazenados na tabela. O caractere * significa "todas as colunas", ou seja, traz o conteúdo completo da tabela selecionada.

## update (nome da tabela) set nome =

O que faz: Altera/atualiza dados já existentes na tabela. Ele modifica o valor da coluna informada (no exemplo, a coluna nome).

Aviso de segurança: Ao usar o UPDATE, sempre adicione a cláusula WHERE no final (ex: WHERE id = 1), caso contrário você atualizará o nome de todos os registros da tabela de uma só vez.
