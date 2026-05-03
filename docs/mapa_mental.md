# 🧠 Mapa Mental - Data Science

Visualização estruturada dos principais tópicos, conceitos e relações em Data Science.

---

## 📊 Estrutura Hierárquica

```
DATA SCIENCE
│
├── 1️⃣ FUNDAMENTOS
│   ├── O que é Data Science?
│   ├── Ciclo de Vida de Projeto
│   ├── Tipos de Dados
│   ├── Python Basics
│   └── Git & Versionamento
│
├── 2️⃣ PREPARAÇÃO DE DADOS
│   ├── Coleta de Dados
│   ├── Limpeza (Data Cleaning)
│   │   ├── Valores Faltantes
│   │   ├── Outliers
│   │   └── Duplicatas
│   ├── Transformação
│   └── Validação
│
├── 3️⃣ ANÁLISE EXPLORATÓRIA (EDA)
│   ├── Estatística Descritiva
│   ├── Visualização de Dados
│   ├── Correlações
│   ├── Distribuições
│   └── Padrões & Anomalias
│
├── 4️⃣ FEATURE ENGINEERING
│   ├── Seleção de Features
│   ├── Normalização/Padronização
│   ├── Encoding Categóricas
│   ├── Criação de Features
│   └── Redução de Dimensionalidade
│
├── 5️⃣ MODELAGEM
│   ├── Regressão
│   │   ├── Linear
│   │   ├── Polinomial
│   │   └── Ridge/Lasso
│   ├── Classificação
│   │   ├── Logística
│   │   ├── SVM
│   │   ├── Decision Trees
│   │   └── KNN
│   └── Ensemble Methods
│       ├── Random Forest
│       ├── Gradient Boosting
│       └── XGBoost
│
├── 6️⃣ VALIDAÇÃO & AVALIAÇÃO
│   ├── Train/Test Split
│   ├── Validação Cruzada
│   ├── Métricas de Classificação
│   │   ├── Accuracy
│   │   ├── Precision/Recall
│   │   ├── F1-Score
│   │   └── AUC-ROC
│   ├── Métricas de Regressão
│   │   ├── MAE
│   │   ├── RMSE
│   │   └── R²
│   └── Análise de Erro
│
├── 7️⃣ OTIMIZAÇÃO
│   ├── Hyperparameter Tuning
│   │   ├── Grid Search
│   │   └── Random Search
│   ├── Bias-Variance Tradeoff
│   ├── Overfitting/Underfitting
│   └── Feature Importance
│
├── 8️⃣ APRENDIZADO AVANÇADO
│   ├── Deep Learning
│   │   ├── Redes Neurais
│   │   ├── CNN
│   │   └── RNN/LSTM
│   ├── NLP (Text)
│   ├── Computer Vision (Imagens)
│   └── Time Series/Forecasting
│
├── 9️⃣ APRENDIZADO NÃO-SUPERVISIONADO
│   ├── Clustering
│   │   ├── K-Means
│   │   ├── Hierárquico
│   │   └── DBSCAN
│   └── Redução de Dimensionalidade
│       ├── PCA
│       └── t-SNE
│
├── 🔟 INTERPRETABILIDADE
│   ├── SHAP Values
│   ├── LIME
│   ├── Feature Importance
│   └── Explicabilidade de Modelos
│
└── 1️⃣1️⃣ PRODUÇÃO & DEPLOYMENT
    ├── Model Serialization
    ├── APIs & Serving
    ├── Containers (Docker)
    ├── Monitoring
    ├── Model Drift
    └── Governance & Ethics
```

---

## 🔗 Relações Principais

```
DADOS → LIMPEZA → EDA → FEATURES → MODELO → VALIDAÇÃO → OTIMIZAÇÃO → PRODUÇÃO
                      ↓
                  Decisão
                  Retornar
```

---

## 📚 Fluxo de Aprendizado Recomendado

### Fase 1: Fundações (2-3 semanas)
1. Conceitos fundamentais de Data Science
2. Python & bibliotecas principais
3. Estatística básica

### Fase 2: Prática (3-4 semanas)
4. Preparação de dados
5. EDA e visualização
6. Feature Engineering

### Fase 3: Modelagem (3-4 semanas)
7. Introdução a Algoritmos
8. Regressão e Classificação
9. Validação e Métricas

### Fase 4: Profundidade (4-6 semanas)
10. Otimização de Modelos
11. Ensemble Methods
12. Técnicas Avançadas

### Fase 5: Realidade (2-3 semanas)
13. Interpretabilidade
14. Deployment & Produção
15. Ética e Governança

---

## 🎯 Conexões Críticas

- **EDA informada por Features**: Qual análise exploratória fazer depende das features que pretende criar
- **Features → Modelo**: A qualidade das features é mais importante que a complexidade do modelo
- **Validação → Otimização**: Métricas de validação guiam a otimização
- **Otimização → Produção**: Um modelo ótimo em dev pode falhar em produção sem monitoramento

---

## 💾 Checklist de Projeto

- [ ] Dados coletados e armazenados
- [ ] Exploração inicial realizada
- [ ] Features engineered
- [ ] Baseline criado
- [ ] Modelos treinados
- [ ] Validação realizada
- [ ] Hiperparâmetros otimizados
- [ ] Resultados documentados
- [ ] Modelo preparado para produção
- [ ] Monitoramento configurado

---

**Última atualização**: 2026-05-03
