ENTIDADES -> CADA UM DOS RETANGULOS

PK -> VALOR UNICO (ID), NÃO PODE SER NULO, NÃO PODE TER OUTRA PK
FK -> REFERENCIA A PRIMARY KEY DE OUTRA TABELA (traz PK da tabela users para o FK user_id na tabela profiles)

* uuid ou AUTOINCREMENT

# RELACIONAMENTO DE ENTIDADES (one-to-one)
## UM PARA UM
Um relacionamento "um para um" é um tipo de relacionamento onde um registro de uma tabela está associado a no máximo um registro de outra tabela.
Exemplo: Pessoa e Passaporte: Cada pessoa pode ter um passaporte e cada passaporte é associado a uma única pessoa.


## UM PARA MUITOS (one-to-many)
Exemplo: Clientes e Pedidos:
Um cliente pode fazer vários pedidos, mas cada pedido está associado a apenas um cliente.

## MUITOS PARA MUITOS (many-to-many)
Exemplo: Estudantes e Cursos:
Um estudante pode se inscrever em vários cursos, e um curso pode ter vários estudantes matriculados.

