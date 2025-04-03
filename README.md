# Banco-de-dados-lógico-E-commerce
Banco de Dados para E-commerce (Clientes PF)

Este projeto consiste na modelagem de um banco de dados para um e-commerce que atende exclusivamente clientes pessoas físicas (PF). O banco foi estruturado para gerenciar clientes, produtos, fornecedores, pedidos, pagamentos e entregas, garantindo integridade e eficiência nas operações.

Estrutura do Banco

O banco contém as seguintes tabelas principais:

Cliente: Registra informações dos clientes, incluindo nome, e-mail, telefone e CPF.

FormaPagamento: Lista as formas de pagamento aceitas (cartão, boleto, PayPal).

ClientePagamento: Relaciona clientes às suas formas de pagamento.

Vendedor: Contém dados dos vendedores cadastrados.

Fornecedor: Registra fornecedores e os vincula a vendedores.

Produto: Armazena produtos vendidos, com descrição, preço, estoque e fornecedor.

Pedido: Representa os pedidos realizados pelos clientes.

PedidoItem: Relaciona produtos aos pedidos, com quantidade e preço unitário.

Entrega: Controla status e rastreamento das entregas.


Consultas Úteis

O projeto inclui algumas queries importantes, como:

Listagem de clientes PF

Produtos e seus fornecedores

Pedidos e valores totais com taxa adicional

Quantidade de pedidos por cliente

Pedidos e status de entrega

Faturamento total por cliente (apenas valores acima de R$ 4000)


