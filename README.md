# **Design do Banco de Dados de E-commerce**

Este repositório apresenta o **Diagrama de Entidade-Relacionamento (DER)** que refere-se a um e-commerce moderno e eficiente. Projetado com o **MySQL Workbench**.

<br>


## 🌟 **Sobre o Projeto**
Este trabalho foi desenvolvido como parte do curso **"Refinando um Projeto Conceitual de Banco de Dados – E-COMMERCE"**, ministrado por [Juliana Mascarenhas](https://www.linkedin.com/in/juliana-mascarenhas-ds/), no **Bootcamp da [Suzano](https://www.linkedin.com/company/suzano/posts/?feedView=all) - Análise de Dados com Power BI**, em parceria com a [DIO](https://www.dio.me/).  

O objetivo do projeto é construir um diagrama ER de um E-commerce a partir do modelo proposto no curso, refinando-o nos seguintes aspectos:
- Cliente PJ e PF – Uma conta pode ser PJ ou PF, mas não pode ter as duas informações;
- Pagamento – Pode ter cadastrado mais de uma forma de pagamento;
- Entrega – Possui status e código de rastreio;.

<br>

## 📈 Visualização do Diagrama

<p align="center">
   <img src="assets/diagrama/Diagrama ER - E-Commerce.png" alt="Diagrama ER">
</p>


## 🔗 **Relacionamentos**

- **Cliente - Conta:** Um cliente pode ter uma conta associada.
- **Conta - Pessoa Jurídica/Física:** Uma conta pode ser de uma empresa ou de um indivíduo.
- **Cliente - Pedido:** Um cliente pode realizar vários pedidos.
- **Pedido - Pagamento:** Cada pedido possui um pagamento associado.
- **Pedido - Entrega:** Cada pedido possui uma entrega relacionada.
- **Fornecedor - Produto:** Um fornecedor pode oferecer vários produtos.
- **Produto - Estoque:** Cada produto possui um controle no estoque.
- **Endereço - Cliente:** Um cliente pode ter vários endereços cadastrados.
- **Endereço - Fornecedor:** Um fornecedor pode ter um endereço cadastrado.
- **Terceiro - Vendedor - Produtos por Vendedor (Terceiro):** Um terceiro vendedor pode ter vários produtos.
- **Fornecedor - Disponibilizando_Produto:** Um fornecedor disponibiliza vários produtos.
- **Produto - Disponibilizando_Produto:** Um produto pode ser disponibilizado por vários fornecedores.
- **Produto - Produto no Estoque:** Um produto pode estar em vários estoques.
- **Estoque - Produto no Estoque:** Um estoque pode conter vários produtos.
- **Produto - Relação Produto/Pedido:** Um produto pode estar em vários pedidos.
- **Pedido - Relação Produto/Pedido:** Um pedido pode conter vários produtos.

<br>


## 🚀 **Por que Isso Importa?**
O modelo garante:  
- **📊 Integridade dos Dados:** Mantendo informações consistentes e precisas.  
- **📈 Escalabilidade:** Preparado para o crescimento do mercado.  
- **🔧 Manutenibilidade:** Estrutura flexível para ajustes e melhorias.  
- **⚡ Eficiência:** Operações otimizadas para alta performance.

<br>

## 💻 **Tecnologia Utilizada**
- **MySQL Workbench:** Ferramenta usada para modelagem e visualização do banco de dados.


