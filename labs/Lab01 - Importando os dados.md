<img src="https://github.com/Databricks-BR/lab_genai/blob/main/img/header.png?raw=true" width=100%>

# Hands-On LAB 01 - Importando os dados

Treinamento Hands-on na plataforma Databricks com foco nas funcionalidades de IA Generativa.
</br></br></br>

## Objetivos do Exercício

O objetivo desse laboratório é importar os dados que serão utilizados nos exercícios.

Nosso conjunto consiste basicamente de quatro tabelas:
- **Avaliações:** conteúdo das avaliações
- **Clientes:** dados cadastrais e consumo dos clientes
- **Produtos:** dados de registro e descrições dos produto
- **FAQ:** perguntas e respostas frequentes em nosso website
</br></br></br>

## Exercício 01.01 - Criação do database

Primeiro, vamos criar um database (ou schema – esses nomes são usados como sinônimos). Esse funcionará como um conteiner para guardar os dados que iremos utilizar durante os exercícios.

``` sql
USE CATALOG academy;

CREATE DATABASE IF NOT EXISTS <seu_nome>;
```
</br></br>

## Exercício 01.02 - Importação dos Arquivos

Agora, precisamos carregar os dados que usaremos nos próximos laboratórios.

Esse conjunto consiste basicamente de duas tabelas:
- **Avaliações**: dados não-estruturados com o conteúdo das avaliações
- **Clientes**: dados estruturados como o cadastro e consumo dos clientes

1. No repositório do **Github**, na pasta de **`../dados`**, clique no **nome** de cada arquivo de dados (csv/parquet) e clique no botão de **download** do arquivo, conforme figura abaixo:
</br></br>
<img src="https://raw.githubusercontent.com/Databricks-BR/genie_ai_bi/main/images/lab1_01.png" width=70%>

</br></br></br>
2. No **menu principal** à esquerda, clique em **`+New`** e depois em **`Add or Upload Data`**:
</br></br>
<img src="https://raw.githubusercontent.com/Databricks-BR/genie_ai_bi/main/images/lab1_02.png" width=400>

</br></br></br>
3. Escolha a opção **`Create or Modify Table`**:
</br></br>
<img src="https://raw.githubusercontent.com/Databricks-BR/genie_ai_bi/main/images/lab1_03.png" width=70%>

</br></br></br>
4. Selecione o catálogo  **`academy`**, o schema **`<seu_nome>`** e um nome pra nova tabela:

<img src="https://raw.githubusercontent.com/Databricks-BR/genie_ai_bi/main/images/lab1_04.png" width=70%>
</br></br>
</br></br></br>




