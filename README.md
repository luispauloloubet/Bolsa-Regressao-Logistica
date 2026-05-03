# Análise de Processo Seletivo para Bolsas de Estudo

Este projeto utiliza **Regressão Logística** e Análise Exploratória de Dados para avaliar os fatores determinantes na aprovação de candidatos em um processo seletivo fictício para bolsas de estudo.

## Estrutura do Projeto
O projeto foi desenvolvido em três etapas:
1. **Limpeza e Preparação:** Carregamento da base de dados, remoção de colunas de identificação e conversão da variável alvo para formato binário.
2. **Análise Exploratória (EDA):** Investigação da distribuição e da taxa de aprovação considerando o perfil demográfico dos candidatos (sexo, idade, raça/cor, orientação sexual e deficiência).
3. **Modelagem Estatística:** Estimação de um modelo de regressão logística para testar a significância estatística das variáveis no resultado do processo.

## Tecnologias Utilizadas
- **Python 3.14**
- **Bibliotecas:** Pandas, Matplotlib, Seaborn, Statsmodels, SciPy.

## A Análise
A análise utilizou uma base de dados contendo informações de 3.000 alunos participantes. O modelo foi ajustado para identificar quais características possuem maior poder explicativo sobre a decisão de seleção, testando a hipótese de que o processo busca apoiar grupos mais vulneráveis.

## Principais Resultados
- **Raça/Cor:** Candidatos que se autodeclaram pretos ou pardos apresentam associação positiva e estatisticamente significativa com a probabilidade de seleção.
- **Outras Variáveis:** Sexo, idade, orientação sexual e deficiência não apresentaram significância estatística, indicando um impacto reduzido dessas características no resultado final.
- **Contexto Socioeconômico:** Os dados sugerem o direcionamento para populações mais vulneráveis, embora variáveis adicionais, como renda familiar per capita, sejam necessárias para uma conclusão definitiva.

---
**Desenvolvido por Luis Paulo Loubet** *Graduando em Engenharia Aeronáutica - EESC-USP*
