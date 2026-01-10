# 📊 Projeto de Vendas -- Power BI

## 📌 Visão Geral

Este projeto de **Análise de Vendas em Power BI** foi desenvolvido com
foco em **clareza gerencial, performance do modelo e geração de insights
acionáveis**. Ele atende desde analistas até gestores e diretores,
permitindo uma visão completa do desempenho comercial.

O modelo segue **boas práticas de BI**, com padronização de
nomenclatura, medidas DAX otimizadas e visualizações orientadas à tomada
de decisão.

------------------------------------------------------------------------

## 🎯 Objetivos do Projeto

-   Monitorar o **desempenho de vendas** ao longo do tempo
-   Identificar **crescimento ou queda (MoM / YoY)**
-   Analisar **clientes, produtos e vendedores**
-   Avaliar **status financeiro** (pagos, pendentes, atrasados)
-   Apoiar decisões estratégicas com **indicadores claros e
    comparáveis**

------------------------------------------------------------------------

## 🧱 Estrutura do Modelo de Dados

O projeto utiliza um **modelo dimensional (Star Schema)**, garantindo
melhor performance, organização e escalabilidade.

### 📂 Tabelas Fato

-   **f_vendas** → tabela fato principal, contendo os registros
    transacionais de vendas.

### 📂 Tabelas Dimensão

-   **d_calendario** → dimensão de datas para análises temporais
-   **d_cliente**
-   **d_produto**
-   **d_vendedor**
-   **d_forma_pagamento**

------------------------------------------------------------------------

## 📐 Padrão de Nomenclatura Utilizado

### 🗂️ Tabelas

-   `f_` → tabelas fato\
-   `d_` → tabelas dimensão

### 📊 Medidas DAX

-   **snake_case**\
    Ex: `total_vendas`, `ticket_medio`, `data_selecionada`

### 🧮 Variáveis DAX

-   **PascalCase com prefixo `v`**\
    Ex: `vAno`, `vTabelaMeses`, `vQtdMesesSelecionados`


------------------------------------------------------------------------

## 🎨 Padrão Visual

-   Positivo: `#64B178`
-   Negativo: `#ED695A`

------------------------------------------------------------------------

## 🏁 Conclusão

Projeto desenvolvido seguindo padrões profissionais de BI, com foco em
performance, clareza e escalabilidade.
