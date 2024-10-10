<img src="https://github.com/Databricks-BR/lab_genai/blob/main/img/header.png?raw=true" width=100%>

# Hands-On LAB 01 - Importando os dados

Treinamento Hands-on na plataforma Databricks com foco nas funcionalidades de IA Generativa.
</br></br></br>

## Objetivos do Exercício

O objetivo desse laboratório é importar os dados que serão utilizados nos exercícios.
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

Esse conjunto consiste basicamente de quatro tabelas:
- **Avaliações:** conteúdo das avaliações
- **Clientes:** dados cadastrais e consumo dos clientes
- **Produtos:** dados de registro e descrições dos produto
- **FAQ:** perguntas e respostas frequentes em nosso website

Sigam os passos abaixo para carregar **todas** as tabelas:

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
<br><br>
<img src="https://raw.githubusercontent.com/Databricks-BR/genie_ai_bi/main/images/lab1_04.png" width=70%>
</br></br></br>

## Próximos Laboratórios

Para os Labs 02 e 03, iremos utilizar notebooks e precisamos importá-los no Databricks para seguir com os exercícios.

Sigam os passos abaixo para importar todos os notebooks:
1. No **GitHub**, acesse o diretório **labs**
2. Clique no nome do laboratório (`Lab02 - Extração de informações e geração de texto.sql` ou `Lab03 - Agentes.sql`)
3. No canto superior direito, clique no ícone com **três pontos**
4. Clique em **Download**
5. No **menu principal** do Databricks, clique em **Workspace**
6. No canto superior direito, clique no ícone com **três pontos**
7. Clique em **Import**
8. Selecione os **notebooks**
9. Clique em **Import**



