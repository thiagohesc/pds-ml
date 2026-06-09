# pds-ml

**Processamento Digital de Sinais e Aprendizado de Máquina no Monitoramento de Temperatura**

## Sobre

Este projeto apresenta um case didático para simular o monitoramento de um sensor de temperatura industrial usando técnicas de Processamento Digital de Sinais (PDS) e Machine Learning.

O foco é demonstrar todo o fluxo de análise:

- geração de sinais sintéticos para diferentes condições operacionais;
- análise e visualização no domínio do tempo;
- filtragem por média móvel;
- extração de características descritivas;
- construção de um dataset para classificação;
- treinamento e avaliação de um modelo de Machine Learning.

## Objetivo

Construir um sistema capaz de classificar quatro condições de operação a partir de sinais de temperatura:

- **0 — Funcionamento normal**
- **1 — Sinal com ruído excessivo**
- **2 — Sensor travado**
- **3 — Temperatura elevada**

## Conteúdo do repositório

- `case_pds.ipynb`: notebook principal com código, explicações e visualizações.

## Tecnologias utilizadas

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

## Como usar

1. Abra o notebook `case_pds.ipynb` em um ambiente Jupyter ou Google Colab.
2. Execute as células em sequência para:
   - importar bibliotecas;
   - gerar sinais sintéticos;
   - extrair características;
   - treinar o modelo Random Forest;
   - avaliar resultados;
   - testar com uma nova medição simulada.

## Destaques do projeto

- Simulação de sinais de tempo de temperatura com diferentes comportamentos.
- Aplicação prática de filtro de média móvel para suavização de ruído.
- Extração de características estatísticas e tendências.
- Classificação supervisionada usando Random Forest.
- Avaliação com matriz de confusão e relatório de classificação.

## Observações

Este projeto é uma demonstração didática. Em aplicações reais, o pré-processamento, a seleção de características e o modelo devem ser ajustados de acordo com as características específicas dos sensores e do processo monitorado.
