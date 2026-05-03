# ❓ Perguntas Estratégicas - Data Science

Perguntas cuidadosamente selecionadas para aprofundar seu conhecimento em Data Science. Use estas questões com NotebookLM para criar resumos e estudar conceitos conectados.

---

## 🟢 NÍVEL FUNDAMENTAL

### Conceitos Essenciais

1. **O que é Data Science e como se diferencia de Big Data, Machine Learning e Analytics?**
   - Contexto: Definir limites e relações entre campos relacionados

2. **Qual é o ciclo de vida completo de um projeto de Data Science, desde a concepção até a produção?**
   - Contexto: Entender fases e entregas esperadas

3. **Quais são os tipos principais de dados (estruturados vs. não-estruturados) e exemplos práticos de cada um?**
   - Contexto: Preparar para diferentes fontes de dados

4. **Como a estatística descritiva (média, mediana, desvio padrão) contribui para o entendimento inicial dos dados?**
   - Contexto: Base para análises mais complexas

5. **O que é uma distribuição de probabilidade e por que é importante reconhecer a distribuição dos dados?**
   - Contexto: Fundamentar escolhas de algoritmos

### Ferramentas e Ambiente

6. **Qual é a diferença entre Python, R e SQL no contexto de Data Science? Quando usar cada um?**
   - Contexto: Escolher ferramentas certas para tarefas

7. **O que é um notebook (Jupyter/Colab) e como ele facilita o workflow de Data Science?**
   - Contexto: Entender formato de trabalho iterativo

8. **Como o versionamento de código (Git) é essencial mesmo em projetos de Data Science?**
   - Contexto: Reprodutibilidade e colaboração

---

## 🟡 NÍVEL INTERMEDIÁRIO

### Preparação e Exploração

9. **Quais são as principais técnicas para lidar com valores faltantes em um dataset? Quando remover vs. imputar?**
   - Contexto: Decisão crítica que afeta todo o projeto

10. **Como identificar e tratar outliers sem perder informações importantes do dataset?**
    - Contexto: Evitar remoção inadequada de dados válidos

11. **O que é "feature importance" e como isso afeta a seleção de variáveis para o modelo?**
    - Contexto: Reduzir ruído e melhorar performance

12. **Como a correlação entre features pode indicar multicolinearidade? Qual é o impacto no modelo?**
    - Contexto: Entender relações entre variáveis

13. **Quais são as técnicas de visualização mais eficazes para comunicar padrões em dados?**
    - Contexto: Storytelling com dados

### Feature Engineering

14. **O que é normalização vs. padronização? Por que alguns algoritmos exigem e outros não?**
    - Contexto: Preparação técnica específica por algoritmo

15. **Como codificar variáveis categóricas (one-hot encoding, label encoding, target encoding)?**
    - Contexto: Transformar tipos diferentes de dados

16. **O que é redução de dimensionalidade (PCA) e quando é útil aplicar?**
    - Contexto: Simplificar modelos sem perder informação crítica

17. **Como criar novas features através de combinações de variáveis existentes (feature crossing)?**
    - Contexto: Aumentar poder preditivo

### Modelagem Básica

18. **Qual é a diferença entre regressão e classificação? Quando usar cada uma?**
    - Contexto: Tipologia fundamental de problemas

19. **O que é a função de custo (loss function) e como ela guia o treinamento do modelo?**
    - Contexto: Entender o que o modelo está otimizando

20. **Como funciona a regressão linear? Quais são suas limitações?**
    - Contexto: Algoritmo simples, mas poderoso como baseline

21. **O que é overfitting e underfitting? Como o tamanho do dataset e complexidade do modelo afetam isso?**
    - Contexto: Conceito crítico para sucesso de modelos

---

## 🔴 NÍVEL AVANÇADO

### Validação e Métricas

22. **Qual é a diferença entre acurácia, precisão, recall e F1-score? Quando priorizar cada uma?**
    - Contexto: Métricas devem alinhar com objetivo de negócio

23. **O que é matriz de confusão e como interpretar seus elementos?**
    - Contexto: Entender tipos de erros do modelo

24. **Como funciona a validação cruzada (k-fold) e por que é superior ao train/test simples?**
    - Contexto: Melhor estimativa de performance real

25. **O que é AUC-ROC e quando é preferível usar em relação a acurácia?**
    - Contexto: Desempenho em dados desbalanceados

26. **Como usar a curva de aprendizado para diagnosticar problemas de viés e variância?**
    - Contexto: Ferramentas diagnósticas para melhorar modelos

### Algoritmos Avançados

27. **Como funcionam Decision Trees? Qual é a diferença entre ID3, C4.5 e CART?**
    - Contexto: Algoritmos interpretáveis e poderosos

28. **O que são ensemble methods? Como Random Forest melhora decisões de árvores individuais?**
    - Contexto: Combinar modelos para resultados melhores

29. **Como funciona Gradient Boosting (XGBoost, LightGBM)? Por que é tão eficaz em competições?**
    - Contexto: State-of-the-art para muitos problemas

30. **O que é SVM (Support Vector Machine)? Como o kernel trick permite separação não-linear?**
    - Contexto: Algoritmo poderoso e teoricamente fundamentado

31. **Como funciona KNN? Qual é o impacto da escolha de K e da métrica de distância?**
    - Contexto: Algoritmo simples com implicações sutis

### Otimização de Hiperparâmetros

32. **O que é GridSearch vs. RandomSearch? Quando usar cada abordagem?**
    - Contexto: Busca eficiente em espaço de hiperparâmetros

33. **Como usar Bayesian Optimization para encontrar hiperparâmetros ótimos mais rapidamente?**
    - Contexto: Abordagem sofisticada para tuning

34. **O que é regularização (L1, L2) e como reduz overfitting em modelos lineares?**
    - Contexto: Técnica fundamental de controle de complexidade

### Aprendizado Não-Supervisionado

35. **Como funcionam algoritmos de clustering? Qual é a diferença entre K-Means, hierarchical clustering e DBSCAN?**
    - Contexto: Descobrir padrões sem rótulos

36. **Como escolher o número ótimo de clusters? O que é elbow method e silhueta score?**
    - Contexto: Validar qualidade de clustering

### Aprendizado Profundo e NLP

37. **O que é uma rede neural artificial? Como o backpropagation permite o aprendizado?**
    - Contexto: Base para deep learning

38. **Como funcionam CNNs (Convolutional Neural Networks) para problemas de visão computacional?**
    - Contexto: Arquitetura especializada para imagens

39. **O que são RNNs e LSTMs? Por que são eficazes para dados sequenciais?**
    - Contexto: Arquitetura para séries temporais e texto

40. **Como funcionam transformers (BERT, GPT)? Por que revolucionaram NLP?**
    - Contexto: Arquitetura moderna mais relevante

### Time Series

41. **Como a autocorrelação de séries temporais afeta a modelagem?**
    - Contexto: Estrutura especial de dados temporais

42. **O que são modelos ARIMA? Como diferem de redes neurais para forecasting?**
    - Contexto: Duas abordagens para previsão temporal

### Interpretabilidade e Explicabilidade

43. **O que é SHAP e como fornece explicações para previsões individuais?**
    - Contexto: Caixa preta pode ser aberta

44. **Como funciona LIME? Qual é a diferença conceptual de LIME vs. SHAP?**
    - Contexto: Abordagens diferentes para interpretabilidade local

45. **O que é feature importance? Como é calculado em diferentes modelos?**
    - Contexto: Entender quais features importam

### Produção e Deployment

46. **Como preparar um modelo para produção? O que é model serialization (pickle, ONNX)?**
    - Contexto: Transformar notebook em sistema

47. **O que é model serving? Qual é a diferença entre batch prediction e real-time serving?**
    - Contexto: Colocar modelo em produção

48. **Como monitorar a performance de um modelo em produção? O que é data drift e model drift?**
    - Contexto: Modelos degradam com o tempo

49. **Por que o versionamento de dados é tão importante quanto versionamento de código?**
    - Contexto: Reprodutibilidade end-to-end

50. **Como balancear performance computacional e acurácia em produção?**
    - Contexto: Trade-offs práticos

### Ética e Governança

51. **O que é viés (bias) em modelos de machine learning? Como diferentes tipos surgem?**
    - Contexto: Responsabilidade social

52. **Como detectar se um modelo está discriminando grupos protegidos (raça, gênero, etc.)?**
    - Contexto: Equidade em ML

53. **O que é explicabilidade requerida por LGPD/GDPR em decisões automatizadas?**
    - Contexto: Compliance legal

54. **Como balancear privacidade dos dados com utilidade do modelo?**
    - Contexto: Desafio fundamental

55. **O que é responsible AI? Quais são os pilares (fairness, accountability, transparency)?**
    - Contexto: Visão holística de ética em DS

---

## 🎯 Como Usar Estas Perguntas

### Para Estudar com NotebookLM:
1. Selecione 5-7 perguntas do mesmo nível
2. Cole-as na caixa de notícias do NotebookLM
3. Peça para criar um resumo conectando os conceitos
4. Peça para gerar uma lista de "coisas para lembrar"

### Para Auto-Avaliação:
- Tente responder de memória antes de consultar fontes
- Identifique lacunas de conhecimento
- Estude essas áreas com prioridade

### Para Estruturar Estudos:
- Comece com nível Fundamental
- Avanços para Intermediário quando se sentir confortável
- Chegue ao Avançado conforme progride

---

**Dica**: Use ChatGPT/Gemini para aprofundar respostas, sempre cruzando com múltiplas fontes!

**Última atualização**: 2026-05-03
