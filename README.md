# Teste de conhecimento 1 

Este repositório contém a atividade **Teste de conhecimento 1**, desenvolvida utilizando **Python Pandas**.

O objetivo da atividade é analisar os custos mensais de transporte de uma empresa, identificar o comportamento dos dados ao longo do tempo, encontrar uma função afim que represente aproximadamente essa tendência e realizar previsões para os próximos meses.

## Objetivo

A atividade utiliza uma base de dados com os custos de transporte registrados durante 12 meses.

A partir desses dados, foram realizadas as seguintes etapas:

- carregamento do arquivo CSV;
- identificação das variáveis independente e dependente;
- criação de gráfico de dispersão;
- obtenção de uma função afim no formato `f(x) = ax + b`;
- interpretação dos coeficientes da função;
- representação gráfica da reta de tendência;
- previsão dos custos para os meses 13, 14 e 15;
- análise dos resultados;
- conclusão sobre o comportamento dos custos.

## Tecnologias utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab / Jupyter Notebook

## Estrutura do repositório

```text
Teste-1-Fundamentos-Matematicos/
│
├── Teste_1_Fundamentos_Matematicos.ipynb
├── base_custos_transporte.csv
└── README.md
```

### Arquivos

**Teste_1_Fundamentos_Matematicos.ipynb**

Notebook principal da atividade. Contém os códigos Python, tabela com os dados, gráficos, cálculos, respostas, análise dos resultados e conclusão.

**base_custos_transporte.csv**

Arquivo contendo os dados dos custos de transporte utilizados na atividade.

## Bibliotecas utilizadas

```python
import pandas as pd
import matplotlib.pyplot as plt
import numpy as np
```

## Função encontrada

A análise dos dados resultou aproximadamente na seguinte função afim:

```text
f(x) = 1791,61x + 42204,55
```

O coeficiente `a` indica que o custo de transporte apresenta um crescimento médio aproximado de **R$ 1.791,61 por mês**.

## Previsões

Utilizando a função encontrada, foram realizadas previsões para os meses seguintes:

```text
Mês 13: aproximadamente R$ 65.495,45
Mês 14: aproximadamente R$ 67.287,06
Mês 15: aproximadamente R$ 69.078,67
```

## Conclusão

Com base nos dados analisados, foi possível observar uma tendência de crescimento nos custos de transporte ao longo dos meses.

A função afim encontrada representa aproximadamente esse comportamento e permite realizar estimativas para os meses seguintes.

## Como executar

O notebook pode ser executado utilizando o **Google Colab** ou o **Jupyter Notebook**.

No Google Colab:

1. Abra o arquivo `Teste_1_Fundamentos_Matematicos.ipynb`.
2. Faça o upload do arquivo `base_custos_transporte.csv`.
3. Execute as células na ordem apresentada.
4. Os gráficos e resultados serão exibidos diretamente no notebook.

