# 📊 A/B Test Analysis — Recommendation System

## 📌 Project Description
This project consists of a complete analysis of an A/B test conducted by an international e-commerce platform to evaluate the impact of a new recommendation system on user behaviour. 

The experiment compared a control group (A) with a test group (B), analysing conversion metrics across different stages of the purchase funnel within a 14-day window after user registration.

The study covers the full analytical process, from data exploration and preprocessing to statistical evaluation, taking into account relevant factors such as seasonality, group imbalance, and experiment integrity.

---

## 🎯 Project Objective
Evaluate whether the introduction of a new recommendation system leads to improvements in user conversion rates, specifically in the following funnel stages:
- product page view (`product_page`)  
- add to cart (`product_cart`)  
- purchase (`purchase`)  

The success criterion was defined as a minimum 10% increase in conversion rates for the test group compared to the control group.

---

## 🧪 Methodology
- Initial data exploration and cleaning  
- Data type conversion and filtering based on experiment scope  
- Exploratory Data Analysis (EDA) to:
  - evaluate the conversion funnel  
  - verify group integrity  
  - identify seasonality and unusual patterns  
- Calculation of conversion rates by group and funnel stage  
- Data visualisation using charts  
- Statistical testing (z-test for proportion comparison)  
- Interpretation of results based on statistical and business criteria  

---

## 📈 Results
The results indicate that the new recommendation system did not improve conversion rates at any stage of the funnel. 

The test group (B) underperformed compared to the control group (A) across all analysed metrics, failing to achieve the minimum 10% improvement defined as the success criterion, with no statistically significant evidence of improvement.

Additionally, the experiment was conducted during a seasonal end-of-year period, which limits the generalisation of results to regular periods. While no user overlap between groups ensured the robustness of the statistical test, it did not change the overall conclusion.

**Recommendation:** Do not implement the new recommendation system based on the current results.

---

## 🛠️ Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Statsmodels  
- Jupyter Notebook  

---

## 📚 What I Learned (Skills & Competencies)
- End-to-end A/B test analysis from an analytical perspective  
- Proper definition of conversion metrics  
- Decision-oriented exploratory data analysis  
- Identification of methodological risks (seasonality, group imbalance)  
- Application of statistical tests for proportion comparison  
- Interpretation of statistical results with a business focus  
- Clear communication of data-driven conclusions  

---

## 🔧 Improvements to be Made
Yes. Possible improvements include:
- Replicating the experiment during non-seasonal periods  
- Increasing the sample size of the test group for higher statistical power  
- Evaluating additional metrics such as Average Order Value (AOV) and retention  
- Testing the recommendation system across different user segments  
- Implementing multivariate or sequential testing approaches  

---

## ▶️ How to Run the Project
Repository:  
https://github.com/RosanaBarbosas/An-lise-de-Teste-A-B-Recommender-System-Test.git

---

# 📊 Análise de Teste A/B — Sistema de Recomendação

## 📌 Descrição do Projeto
Este projeto consiste na análise completa de um teste A/B realizado por uma loja online internacional com o objetivo de avaliar o impacto de um novo sistema de recomendação sobre o comportamento dos usuários. O experimento comparou um grupo de controle (A) com um grupo de teste (B), analisando métricas de conversão ao longo de diferentes etapas do funil de compra, dentro de uma janela de até 14 dias após o cadastro dos usuários.

O estudo abrangeu desde a exploração e preparação dos dados até a avaliação estatística dos resultados, considerando particularidades relevantes como sazonalidade, desbalanceamento entre grupos e integridade do experimento.

---

## 🎯 Objetivo do Projeto
Avaliar se a introdução de um novo sistema de recomendação resulta em melhorias nas taxas de conversão dos usuários, especificamente nas etapas de:
- visualização de página de produto (`product_page`);
- adição ao carrinho (`product_cart`);
- compra (`purchase`).

O critério de sucesso definido foi um aumento mínimo de 10% nas taxas de conversão do grupo de teste em relação ao grupo de controle.

---

## 🧪 Metodologia
- Exploração inicial e limpeza dos dados;
- Conversão de tipos e filtragem conforme o escopo do experimento;
- Análise Exploratória de Dados (EDA) para:
  - avaliação do funil de conversão;
  - verificação de integridade dos grupos;
  - identificação de sazonalidade e comportamentos atípicos;
- Cálculo das taxas de conversão por grupo e por etapa do funil;
- Visualização dos resultados por meio de gráficos;
- Aplicação de testes estatísticos (z-test para comparação de proporções);
- Interpretação dos resultados considerando critérios estatísticos e de negócio.

---

## 📈 Resultados
Os resultados indicaram que o novo sistema de recomendação não apresentou melhorias nas taxas de conversão em nenhuma das etapas avaliadas do funil. O grupo de teste (B) apresentou desempenho inferior ao grupo de controle (A) em todas as métricas analisadas, sem atingir o aumento mínimo de 10% definido como critério de sucesso e sem evidências estatísticas significativas.

Além disso, o experimento foi conduzido durante um período sazonal de fim de ano, o que limita a generalização dos resultados para períodos regulares. A ausência de interseção de usuários entre os grupos garantiu a robustez do teste estatístico, mas não alterou a conclusão final.

**Recomendação:** não implementar o novo sistema de recomendação com base nos resultados obtidos.

---

## 🛠️ Ferramentas Utilizadas
- Python
- Pandas
- NumPy
- Matplotlib
- Statsmodels
- Jupyter Notebook

---

## 📚 O que eu aprendi (Habilidades e Competências)
- Condução completa de um teste A/B do ponto de vista analítico;
- Definição correta de métricas de conversão;
- Análise exploratória orientada à tomada de decisão;
- Identificação de riscos metodológicos (sazonalidade, desbalanceamento);
- Aplicação de testes estatísticos para comparação de proporções;
- Interpretação de resultados estatísticos com foco em negócio;
- Comunicação clara de conclusões baseadas em dados.

---

## 🔧 Existem melhorias a serem feitas?
Sim. Algumas melhorias possíveis incluem:
- Replicar o experimento em períodos não sazonais;
- Aumentar o tamanho da amostra do grupo de teste para maior poder estatístico;
- Avaliar métricas adicionais, como valor médio de pedido (AOV) ou retenção;
- Testar o sistema de recomendação em diferentes segmentos de usuários;
- Implementar testes multivariados ou experimentos sequenciais.

---

## ▶️ Como Executar o Projeto
link: https://github.com/RosanaBarbosas/An-lise-de-Teste-A-B-Recommender-System-Test.git
