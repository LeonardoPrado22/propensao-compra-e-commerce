# Projeto 8 — Modelo de Propensão e Previsão de Intenção de Compra em E-commerce

---

## 📚 Explicação do Curso
Este projeto foi desenvolvido como parte do curso de Cientista de Dados da EBAC, focando na aplicação de modelos de Machine Learning para resolver um desafio de Marketing: **antecipar o comportamento do cliente** em um site de E-commerce. O modelo de classificação prediz a probabilidade de um cliente com perfil e comportamento específicos (**WebPurchases**) finalizar uma transação, transformando dados de navegação e demográficos em uma métrica de negócio acionável.

---

## 🎯 Objetivos
O principal objetivo deste projeto é criar uma ferramenta de inteligência de negócios para otimizar o investimento em marketing:

* **Modelo de Propensão à Compra:** Criar um modelo de classificação (como Regressão Logística ou Random Forest) que preveja a probabilidade de um cliente realizar uma compra no site.
* **Análise de Comportamento:** Utilizar uma base de dados rica em comportamento de navegação, histórico de gastos (vinhos, carnes, etc.) e dados demográficos para o treinamento do modelo.
* **Avaliação Estratégica:** Avaliar o modelo usando métricas de classificação relevantes, com foco no **Recall** e na **Precision**, que são cruciais para otimizar o investimento e evitar o desperdício de cupons.
* **Otimização do Funil de Vendas:** Consolidar o entendimento sobre como o Machine Learning se aplica diretamente às estratégias de vendas e retenção.

---

## 💻 Tecnologias Usadas
* **Linguagem:** Python
* **Algoritmos Principais:** Logistic Regression e Random Forest Classifier (Classificação).
* **Bibliotecas Principais:** Pandas, NumPy, Scikit-learn, Matplotlib e Seaborn.
* **Tratamento de Dados:** Preenchimento de *missing values* (renda), e padronização.
* **Ambiente:** Jupyter Notebook.

---

## 📈 Principais Análises Realizadas
O projeto focou nas seguintes etapas e análises técnicas:

* **Pré-processamento e Limpeza:** Tratamento de valores nulos na variável `Income` (renda anual) e verificação de *outliers* na base de clientes.
* **Engenharia de Features:** Criação de novas variáveis baseadas no comportamento do cliente (como a idade a partir do ano de nascimento) e no total de gastos.
* **Modelagem Preditiva:** Treinamento dos modelos de classificação para prever a variável alvo binária (`WebPurchases`: Sim/Não).
* **Análise da Matriz de Confusão:** Foco na análise da **Matriz de Confusão** para identificar a proporção de clientes com alta propensão (Verdadeiros Positivos) que foram corretamente previstos, garantindo a qualidade da segmentação.

---

## ✨ Insights Chave (Valor de Negócio e Conclusão)

As conclusões extraídas deste projeto demonstram o impacto direto da Ciência de Dados no Marketing:

* **Otimização de ROI:** O modelo de propensão à compra é uma ferramenta de otimização de recursos. Ao prever a intenção do cliente, a empresa pode concentrar o investimento em campanhas de marketing (e-mails, cupons) nos clientes que realmente têm o maior potencial de conversão, maximizando o Retorno sobre o Investimento (ROI).
* **Intervenção Personalizada:** A capacidade preditiva permite intervenções personalizadas no *e-commerce*, como a exibição de pop-ups de desconto ou a ativação de *retargeting* apenas para os usuários com alta pontuação de propensão.
* **Proficiência em Classificação:** O exercício confirmou o domínio do uso de algoritmos de classificação para resolver problemas de negócio complexos, desde a Engenharia de Features até a interpretação das métricas.