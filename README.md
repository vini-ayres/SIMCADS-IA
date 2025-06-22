# Detecção de Possíveis Fraudes em Óbitos com Isolation Forest

Este projeto utiliza técnicas de aprendizado de máquina não supervisionado para identificar possíveis anomalias em registros de óbitos por distrito no Brasil, com base nos dados do Censo 2022 do IBGE.

## 📊 Objetivo

Detectar padrões estatísticos incomuns que possam indicar fraudes, erros de registro ou comportamentos atípicos na distribuição de óbitos entre distritos brasileiros, utilizando o algoritmo **Isolation Forest**.

## 🧾 Bases de Dados

- `Agregados_por_distritos_basico_BR.csv`
- `Agregados_por_distritos_obitos_BR.csv`
- Dados públicos do **IBGE - Censo Demográfico 2022**

## 🛠 Tecnologias e Bibliotecas

- Python 3.x
- pandas, numpy, seaborn, matplotlib
- scikit-learn (Isolation Forest, StandardScaler)
- Jupyter Notebook

## 📁 Estrutura

- `normalizacao_bases.ipynb` – Pré-processamento e unificação dos dados
- `deteccao_fraudes_obitos.ipynb` – Análise exploratória, modelagem e visualização
- `obitos_normalizados.csv` – Base consolidada para o modelo
- `registros_suspeitos_completos.csv` – Saída com distritos classificados como anômalos
- `poster_fraudes_simcads.docx` – Pôster acadêmico com os principais resultados
- `Fraude Obitos Isoforest.md` – Artigo técnico com metodologia e resultados

## 📌 Resultados

O modelo identificou cerca de 5% dos distritos como anômalos, com destaque para cidades como **Fortaleza**, **Rio de Janeiro**, **Manaus**, **Recife** e **Goiânia**. Esses registros exibiram valores fora do padrão em densidade populacional, percentual de idosos e óbitos per capita.
