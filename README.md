<h1 align="center"> Projeto Migração de Dados - Pocco </h1>

# Descrição do Projeto
Neste projeto criei um pipeline de dados com o Nifi, data warehouse no MySQl, e a partir de dados extraídos de um contêiner da Azure Blob Storage construí deshboards no Power BI com insights extraídos das relações entre esses dados. 

# Principal Objetivo
A ideia era criar relatórios simplificados e dinâmicos da empresa fictícia 'Pocco' para o cliente acompanhar o status de suas vendas.

# Especificação funcional do Projeto:
https://github.com/Prixribeiro/projeto-migracao-de-dados/blob/main/Especifica%C3%A7%C3%A3o%20Funcional.pdf

# Arquitetura do Projeto:

<p align="center">
  <img src="https://github.com/Prixribeiro/projeto-migracao-de-dados/blob/main/fluxo%20de%20migra%C3%A7ao.png" width="600" title="Arquitetura do Projeto">
</p>



# Resumo das Funcionalidades:

Extrair dados em formato csv de um arquivo chamado 'orders' armazenado em um contâiner Azure blob storage; 

Como resultado do ETL via Apahe NiFi, os dados extraídos devem ser organizados em um data warehouse (DW) no mysql;

As relações entre as tabelas do DW devem originar deshboards que possibilitem o detalhamento das venda.

# Status do projeto: 
Concluído ✔️
