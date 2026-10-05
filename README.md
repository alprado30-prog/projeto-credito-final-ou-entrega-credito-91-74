# Projeto de Risco de Crédito - 91,74% de Acurácia

**Aluna:** Edna Aparecida Prado
**Curso:** Programação com IA - SENAI

## Objetivo
Prever risco de crédito usando Machine Learning

## O que foi feito
- Limpeza de 165 duplicatas e 181 idades inválidas
- Criação da coluna obrigatória `comprometimento_renda`
- Pipeline seguro com StandardScaler e OneHotEncoder (sem vazamento de dados)
- Comparação de 3 modelos: KNN, Árvore e RandomForest
- Controle de overfitting (gap < 5%)

## Resultado Final
- **Modelo vencedor: RandomForest**
- **Acurácia: 91,74%**
- Arquivos entregues: `pipeline_credito.ipynb` e `pipeline_credito.pkl`

## Link do projeto
Projeto desenvolvido no Google Colab
