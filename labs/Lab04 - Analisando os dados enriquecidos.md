%md <img src="https://github.com/Databricks-BR/lab_genai/blob/main/img/header.png?raw=true" width=100%>

# Hands-On LAB 04 - Analisando os dados enriquecidos

Treinamento Hands-on na plataforma Databricks com foco nas funcionalidades de IA Generativa.
</br></br></br>

## Objetivos do Exercício

O objetivo desse laboratório é implementar o seguinte caso de uso:

### Analisando as avaliações dos produtos

Com as informações extraídas nos laboratórios anteriores, nossos times de negócio podem aproveitar para analisar as avaliações de produtos facilmente – já que agora temos todos os dados estruturados dentro de uma simples tabela.

A partir dessa base de dados enriquecida criada, podemos construir análises ad-hoc, dashboards e alertas diretamente do Databricks. E, para facilitar ainda mais a vida dos nossos analistas, podemos fazer isso usando somente linguagem natural!

Aqui vamos explorar como utilizar a **Genie** para analisar nossas avaliações de produto.

<br>
<img src="https://raw.githubusercontent.com/databricks-demos/dbdemos-resources/main/images/product/sql-ai-functions/sql-ai-function-flow.png" width="1000">
</br></br></br>

## Exercício 04.01 - Criação da Genie

Vamos começar criando a Genie para fazer nossas perguntas. Para isso, vamos seguir os passos abaixo:

1. No **menu principal** à esquerda, clique em **`New`** > **`Genie space`**

<img src="https://raw.githubusercontent.com/Databricks-BR/genie_ai_bi/main/images/genie_01.png"><br><br>

2. Configure sua Genie
    - Crie um nome para a sua Genie, por exemplo **`<seu_nome> Análise das Avaliações de Produtos`**
    - Selecione seu **SQL Warehouse**
    - Selecione a tabela **`academy.<seu_nome>.avaliacoes_revisadas`**
    - Clique em **`Save`**

<img src="https://raw.githubusercontent.com/Databricks-BR/genie_ai_bi/main/images/genie_02.png" width=800>

</br></br>

## Exercício 04.02 - Fazendo perguntas à Genie

Com nossa Genie preparada, podemos começar a fazer nossas análises!

Basta usar o chat para fazer as perguntas abaixo:

- Quais os produtos mencionados com maior frequência?
- Agora, quebre por sentimento
- Crie um gráfico de barras

<img src="https://raw.githubusercontent.com/Databricks-BR/genie_ai_bi/main/images/genie_05.png"><br><br>

Notem que, mesmo com muito pouco contexto, a Genie já conseguiu:
- Inferir quais as tabelas e colunas relevantes para responder nossas perguntas
- Aplicar filtros e agregações
- Responder perguntas adicionais sobre uma resposta anterior
- Entender como utilizar jargões
- Calcular métricas derivadas

Aproveitem para explorar e fazer perguntas adicionais!

<br><br>

# Parabéns!

Você concluiu o laboratório da **Genie**!

Agora, você já sabe como utilizar a Genie para analisar seus dados usando somente linguagem natural!

