# Ecommerce_Projeto_BancoDeDados

## Esquema do Modelo Entidade-Relacionamento para E-commerce


Este repositório contém o esquema do Modelo Entidade-Relacionamento (ER) para um sistema de e-commerce. O esquema ER é uma representação gráfica das entidades envolvidas no sistema de e-commerce, bem como dos relacionamentos entre essas entidades.

As entidades no nosso modelo incluem:

1. Cliente: Representa os usuários que fazem pedidos no sistema de e-commerce.
2. Pedido: Representa os pedidos feitos pelos clientes.
3. Pagamento: Representa os pagamentos feitos pelos clientes para seus pedidos.
4. Forma de Pagamento: Representa as diferentes formas de pagamento que um cliente pode usar para fazer um pagamento.
5. Entrega: Representa a entrega de um pedido a um cliente.
6. Produto: Representa os itens que podem ser comprados no e-commerce.
7. Estoque: Representa a quantidade disponível de cada produto.
8. Fornecedor: Representa as empresas ou indivíduos que fornecem os produtos vendidos no e-commerce.
9. Vendedor Externo: Representa vendedores terceirizados que vendem seus produtos através do e-commerce.

Os relacionamentos entre as entidades são os seguintes:

1. Um cliente pode fazer vários pedidos, e cada pedido é feito por um cliente.
2. Um pedido pode ter vários pagamentos, e cada pagamento está associado a um pedido.
3. Uma forma de pagamento pode ser usada em vários pagamentos, e cada pagamento usa uma forma de pagamento.
4. Um pedido pode ter várias entregas associadas a ele, especialmente em casos onde itens diferentes em um pedido são enviados separadamente.
5. Um produto pode estar em vários pedidos, e cada pedido contém um ou mais produtos.
6. O estoque está associado a cada produto, indicando a quantidade disponível para venda.
7. Cada produto tem um fornecedor associado que fornece o produto.
8. Um vendedor externo pode listar vários produtos para venda, e cada produto listado por um vendedor externo está associado a esse vendedor.

Este esquema ER serve como uma ferramenta útil para entender o domínio do problema antes da implementação física no sistema de gerenciamento de banco de dados.

Esperamos que este esquema ER seja útil para quem está projetando ou aprendendo sobre sistemas de e-commerce. Sinta-se à vontade para contribuir com este projeto ou usar este esquema ER como referência para seus próprios projetos! 
