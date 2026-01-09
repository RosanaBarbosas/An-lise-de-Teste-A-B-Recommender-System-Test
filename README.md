# 📊 Análise de Teste A/B: Recommender System Test

Este projeto realiza uma análise estatística e exploratória completa de um teste A/B para uma loja online internacional. O objetivo principal foi avaliar se a implementação de um novo sistema de recomendação de produtos resultaria em uma melhoria de pelo menos 10% nas taxas de conversão em cada etapa do funil de vendas.

## 📋 Cenário do Projeto
A empresa lançou o experimento para comparar o comportamento dos usuários entre um grupo de controle (A) e um grupo com o novo sistema de recomendações (B). A análise cobre o funil de eventos dentro de uma janela de até 14 dias após o cadastro do usuário:
1. **Product Page** (Visualização do produto)
2. **Product Cart** (Adição ao carrinho)
3. **Purchase** (Compra finalizada)

## 🛠️ Tecnologias e Ferramentas Utilizadas
* **Linguagem:** Python
* **Manipulação de Dados:** Pandas
* **Análise Estatística:** Statsmodels (`proportions_ztest`)
* **Ambiente:** Jupyter Notebook

## 🔍 Etapas do Desenvolvimento

### 1. Preparação e Limpeza de Dados
* Conversão de colunas de data para o tipo `datetime`.
* Filtragem de usuários participantes exclusivamente do teste `recommender_system_test`.
* Segmentação regional focada em usuários da Europa (EU).
* Aplicação de uma janela de conversão de **14 dias** após o cadastro.

### 2. Análise Exploratória (EDA)
* **Desbalanceamento:** Identificou-se que o grupo A detinha ~75% dos usuários (2.604) contra ~25% no grupo B (877).
* **Integridade:** Verificação de que não havia usuários presentes em ambos os grupos simultaneamente.
* **Comportamento:** Observou-se que o funil não é estritamente linear, com eventos de compra ocorrendo mesmo sem a adição ao carrinho.

### 3. Teste de Hipóteses Estatísticas
Utilizou-se o **Z-Test para Proporções** para comparar as taxas de conversão entre os grupos com um nível de significância ($\alpha$) de 0,05.

| Evento | Conversão Grupo A | Conversão Grupo B | Uplift (%) | P-Value |
| :--- | :---: | :---: | :---: | :---: |
| **Product Page** | 64.71% | 56.21% | -13.13% | 0.999 |
| **Product Cart** | 30.03% | 27.82% | -7.35% | 0.892 |
| **Purchase** | 31.99% | 28.39% | -11.24% | 0.976 |

## 📈 Conclusões e Insights
Os resultados indicam que o novo sistema de recomendação **não atingiu o objetivo esperado**:
* **Desempenho Inferior:** O grupo B apresentou taxas de conversão consistentemente menores do que o grupo de controle em todas as etapas.
* **Significância:** Não houve evidências estatísticas que justificassem a adoção da nova versão (p-values elevados).
* **Recomendação:** Não implementar o novo sistema na forma testada e investigar possíveis atritos na jornada do usuário no grupo B.

---
*Projeto desenvolvido como parte do curso de Análise de Dados.*
