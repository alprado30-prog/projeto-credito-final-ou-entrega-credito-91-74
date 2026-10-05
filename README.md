# Projeto de Risco de Crédito - 91,74% de Acurácia

**Aluna:** Edna Aparecida Prado | **Curso:** Machine Learning e Visão Computacional [T3]- SENAI

### Objetivo
Prever risco de crédito usando Machine Learning

### O que foi feito
- Limpeza de 165 duplicatas e 181 idades inválidas
- Criação da coluna obrigatória `comprometimento_renda`
- Pipeline seguro com StandardScaler e OneHotEncoder (sem vazamento de dados)
- Comparação de 3 modelos: KNN, Árvore e RandomForest
- Controle de overfitting (gap < 5%)

### Resultado Final
- **Modelo vencedor:** RandomForest
- **Acurácia:** 91,74%
- **Arquivos entregues:** `pipeline_credito.ipynb` e `pipeline_credito.pkl`

### Link do projeto
👉 [Clique aqui para acessar o projeto no GitHub](https://github.com/alprado30-prog/projeto-credito-final-ou-entrega-credito-91-74)

Projeto desenvolvido no Google Colab

### Veredito de Negócios (Qual modelo vai pra produção?)
Após analisar a Matriz de Confusão dos 3 modelos:
- **KNN (81%):** Muitos Falsos Negativos - liberaria crédito pra quem não vai pagar
- **Árvore (88%):** Equilibrada, mas menor precisão
- **RandomForest (91,74%):** Menor número de Falsos Positivos e Falsos Negativos

**DECISÃO:** O modelo RandomForest com 91,74% deve ser colocado em produção.

**Justificativa Financeira:** Ele erra menos ao negar crédito pra bom pagador (Falso Positivo) e erra menos ao liberar crédito pra mau pagador (Falso Negativo), protegendo o lucro da empresa e mantendo clientes bons. É o modelo mais seguro financeiramente e operacionalmente.
