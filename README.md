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
