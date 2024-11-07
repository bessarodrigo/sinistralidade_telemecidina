# Análise de Sinistralidade em Telemedicina

## Visão Geral

Este notebook Python explora e analisa dados de sinistralidade de uma empresa de telemedicina. O objetivo é calcular e visualizar a sinistralidade média mensal, trimestral e por empresa, utilizando técnicas de visualização de dados.

## Artigo no Medium

[Análise de Sinistralidade em uma empresa de Telemedicina com CRISP-DM](https://medium.com/@reisrodri/an%C3%A1lise-de-sinistralidade-em-uma-empresa-de-telemedicina-com-crisp-dm-8e731fe009b2)

## Estrutura do Projeto

- **sinistralidade_telemedicina.ipynb**: Notebook principal para visualização dos dados de sinistralidade
- **data_profiling.ipynb**: Notebook dedicado ao profiling de dados, utilizando a biblioteca Sweetviz para gerar insights iniciais

- **consultas.html**: Página HTML com uma visualização específica de consultas e informações associadas
- **vidas_ativas.html**: Página HTML que apresenta informações sobre vidas ativas relacionadas ao projeto de sinistralidade

## Bibliotecas Utilizadas

- **Pandas**: Para manipulação e análise de dados estruturados
- **Matplotlib**: Para criação de gráficos e visualizações
- **NumPy**: Para operações numéricas eficientes
- **IPyWidgets**: Para criação de widgets interativos
- **IPython.display**: Para exibição de widgets e gráficos dentro do notebook
- **Sweetviz**: Utilizada para o data profiling inicial, fornecendo um resumo visual e estatístico dos dados.

## Funcionalidades

- **Análise Mensal**: Calcula e visualiza a sinistralidade média por mês
- **Análise Trimestral**: Compara a sinistralidade trimestralmente
- **Análise por Empresa**: Permite selecionar uma empresa específica e analisar sua sinistralidade ao longo do tempo
- **Data Profiling (Sweetviz)**: Gera um relatório interativo de profiling que destaca distribuições, valores nulos, correlações e outras características dos dados.

## Estrutura do Notebook

1. **Carregamento e Limpeza de Dados**:
   - Importação dos dados de sinistralidade.
   - Limpeza e preparação dos dados para análise.

2. **Visualização de Dados**:
   - Gráficos de linha para visualização da sinistralidade média por mês.
   - Widgets interativos para seleção de empresa e visualização dinâmica dos dados.

3. **Análise Estatística**:
   - Cálculo de estatísticas descritivas como média, mínimo e máximo de sinistralidade.
