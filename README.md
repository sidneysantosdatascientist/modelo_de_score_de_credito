# Modelo de Score de Crédito

Este projeto tem como objetivo prever o risco de crédito de clientes com base em suas características financeiras e pessoais. O modelo foi desenvolvido utilizando técnicas de machine learning e é capaz de classificar os clientes em categorias de risco (Baixo, Médio, Alto).

---

##  Visão Geral
O projeto utiliza o dataset **German Credit Data**, que contém informações sobre clientes de um banco alemão. O objetivo é prever se um cliente é um bom pagador (baixo risco) ou mau pagador (alto risco). O modelo foi treinado utilizando algoritmos como Random Forest, Regressão Logística e XGBoost, e os resultados foram avaliados com métricas como AUC-ROC, precisão e recall.

---

##  Dataset
O dataset utilizado é o **German Credit Data**, disponível publicamente no [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Statlog+(German+Credit+Data)). Ele contém 1000 entradas com 20 atributos, incluindo:
- `status_conta`: Status da conta corrente.
- `duracao_meses`: Duração do empréstimo em meses.
- `historico_credito`: Histórico de crédito do cliente.
- `valor_credito`: Valor do crédito solicitado.
- `risk`: Variável alvo (1: Bom pagador, 2: Mau pagador).

---

##  Tecnologias Utilizadas
- **Python**: Linguagem de programação principal.
- **Pandas**: Manipulação de dados.
- **Scikit-learn**: Machine learning (Random Forest, Regressão Logística).
- **XGBoost**: Algoritmo de boosting para classificação.
- **Matplotlib/Seaborn**: Visualização de dados.
- **Streamlit**: Criação de dashboard interativo (opcional).

---

