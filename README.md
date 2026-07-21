# Desafio Prático - Análise Financeira com Python

## Descrição

Este projeto foi desenvolvido como parte do desafio prático da formação **Análise de Dados e Inteligência de Negócios** da Rocketseat.

O objetivo do projeto é realizar a leitura de um arquivo CSV contendo transações bancárias, validar os registros, agrupar as movimentações por mês, calcular indicadores financeiros, identificar transações suspeitas e exportar o resultado em formato JSON.

Todo o projeto foi desenvolvido utilizando apenas bibliotecas nativas do Python, conforme solicitado no desafio.

---

## Funcionalidades

O notebook executa as seguintes etapas:

- Leitura do arquivo `transacoes.csv`;
- Validação dos registros da base de dados;
- Tratamento de registros inválidos;
- Conversão de datas e valores para seus respectivos tipos;
- Agrupamento das transações por mês;
- Cálculo das principais métricas financeiras:
  - Quantidade de transações;
  - Total de créditos;
  - Total de débitos;
  - Saldo mensal;
  - Média das transações;
  - Maior valor movimentado;
  - Menor valor movimentado;
- Identificação de transações suspeitas acima do limite estabelecido;
- Geração do arquivo `relatorio.json`;
- Exibição de um relatório financeiro formatado no terminal.

---

## Tecnologias utilizadas

- Python 3
- csv
- json
- datetime

Todas as bibliotecas utilizadas pertencem à biblioteca padrão do Python.

---

## Estrutura do projeto

```text
clearbank-analise/
│
├── desafio-final.ipynb
├── transacoes.csv
├── relatorio.json
└── README.md
```

---

## Como executar

### Google Colab

1. Abra o arquivo `desafio-final.ipynb` no Google Colab.
2. Faça o upload do arquivo `transacoes.csv`.
3. Execute todas as células na ordem em que foram desenvolvidas.
4. Ao final da execução será gerado automaticamente o arquivo `relatorio.json`.

---

## Saídas geradas

Ao executar o notebook são exibidas as seguintes informações:

- Resumo da limpeza dos dados;
- Período analisado;
- Relatório financeiro mensal contendo:
  - Quantidade de transações;
  - Total de créditos;
  - Total de débitos;
  - Saldo mensal;
  - Média das transações;
  - Maior valor;
  - Menor valor;
- Lista de transações suspeitas (quando existirem).

Além da exibição no terminal, o projeto gera automaticamente o arquivo:

```text
relatorio.json
```

Esse arquivo contém:

- Relatório financeiro mensal;
- Lista de transações suspeitas identificadas durante o processamento.

---

## Objetivos de aprendizagem

Durante o desenvolvimento deste projeto foram aplicados os seguintes conceitos:

- Organização do código em funções;
- Leitura de arquivos CSV;
- Manipulação de listas e dicionários;
- Validação de dados;
- Tratamento de exceções com `try/except`;
- Conversão de tipos de dados;
- Manipulação de datas com `datetime`;
- Agrupamento e cálculo de métricas financeiras;
- Exportação de dados em formato JSON.

---

## Autor

**Rodrigo de Freitas Vicente**

Projeto desenvolvido como atividade prática da formação **Análise de Dados e Inteligência de Negócios com IA** da **Rocketseat**.
