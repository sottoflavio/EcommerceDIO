# EcommerceDIO
## Desafio de código DIO para Bootcamp

### Refinamento de modelagem de Banco de dados para E-commerce
### Foram feitas as seguintes alterações

##adição de modo de pagamento: 
###Cada cliente pode ter mais de um cartão de crédito, os dados são salvos, exceto o dígito de segurança em uma tabela separada do cliente, e mantém-se relacionamento pelo id do cliente com uma relação de 1 para n.

##Entrega:
###Como cada pedido tem sua entrega única, achei mais viável a adição do código de rastreio e status dentro da tabela do pedido.

## adição do campo email e validação do CPF/CNPJ
### Cada cliente pode ter apenas um CPF ou CNPJ, nunca os dois, para isso o campo-email não pode ser repetido em dois cadastros.
