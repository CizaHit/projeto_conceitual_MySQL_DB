# Refinando um Projeto Conceitual de Banco de Dados E-COMMERCE:

#### Projeto proposto no Bootcamp Coding the Future Heineken - Inteligência Artificial Aplicada a Dados com Copilot na plataforma [DIO.](https://www.dio.me/)

### Descrição do Desafio
_"Foi elaborado em conjunto um modelo simplificado para um cenário de e-commerce. Neste desafio, o participante terá a oportunidade de dar continuidade ao trabalho, podendo escolher a ferramenta de modelagem que considerar mais adequada para a tarefa. Contudo, é importante destacar que, caso opte por utilizar uma variação do modelo entidade-relacionamento, como o MySQL Workbench ou DBDesigner, será necessário especificar corretamente as chaves primárias (PK) e as chaves estrangeiras (FK). Embora esses conceitos não sejam aplicados diretamente na modelagem conceitual, haverá uma breve explanação sobre suas definições. O objetivo principal é a construção de um esquema conceitual que atenda ao cenário proposto de e-commerce."_ 

<h2>- Produto </h2>
Os produtos são vendidos por uma única plataforma online. 
Contudo, estes podem ter vendedores distintos (terceiros).
Cada produto possui um fornecedor.
Um ou mais produtos podem comper um pedido.

<h2>- Cliente </h2>
O cliente pode se cadastrar no site com seu CPF ou CNPJ.
O endereço do cliente irá determinar o valor do frete.
Um cliente pode comprar mais de um pedido. 
Este tem um período de carência para devolução do produto.

<h2>- Pedido </h2>
Os pedidos são criados por clientes e possuem informações de compra, endereço e status da entrega
Um produto ou mais compoem o pedido.
O pedido pode ser cancelado.

<h2>- Fornecedor & Estoque</h2> 
Base: Juliana Mascarenhas
[DBdesigner] (https://app.dbdesigner.net/designer/schema/0-bd_e_commerce1)

Instrutora: *Juliana Mascarenhas*
</b>

### Objetivo:
Refine o modelo apresentado acrescentando os seguintes pontos:

- Cliente PJ e PF – Uma conta pode ser PJ ou PF, mas não pode ter as duas informações;
- Pagamento – Pode ter cadastrado mais de uma forma de pagamento;
- Entrega – Possui status e código de rastreio;

## Ferramentas utilizadas

- [MySQL Workbench](https://www.mysql.com/products/workbench/)

## Respostas do Desafio

![img](https://github.com/CizaHit/projeto_conceitual_MySQL_DB/blob/main/e-commerce_Refinado.png)

- Entidade Cliente: Foram criadas duas novas entidades, PJ_Pessoa Jurídica e PF_Pessoa Física, com o objetivo de armazenar as informações específicas relacionadas ao tipo de cliente, incluindo os dados de CNPJ e CPF, respectivamente.

- Entidade Pagamento: A entidade Pagamento foi associada a outras entidades para detalhar as diferentes formas de pagamento disponíveis, como Cartão, Boleto e PIX, permitindo uma maior especificidade e organização nas informações relacionadas aos métodos de pagamento.

- Entidade Entrega: Uma nova entidade denominada Entrega foi criada para armazenar informações detalhadas sobre o envio de cada pedido. Esta entidade inclui dados importantes, como data do pedido, data de envio e data de entrega, proporcionando um acompanhamento mais preciso de cada etapa do processo de entrega.


## Certificado

![img]()


[Linkedin](www.linkedin.com/in/césar-tanizawa-eng-computacao/)
