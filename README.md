# 🧾 Modelo de Classificação Fiscal – Regressão Logística

Este projeto teve como objetivo desenvolver um modelo de machine learning capaz de **classificar empresas com potencial risco de sonegação fiscal**, com base em dados fictícios gerados pelo modelo GPT 4o.

O pipeline foi inteiramente construído em Python com foco em **transparência, interpretabilidade e reprodutibilidade**, utilizando a **Regressão Logística** como modelo central.

---

## 📁 Estrutura do Repositório

- `modelo_fiscal.ipynb` – Notebook completo contendo todas as etapas do pipeline:
  - Objetivo
  - Importações
  - Análise exploratória
  - Pré-processamento
  - Justificativa do modelo
  - Treinamento do modelo
  - Teste, avaliação e conclusão

- `dataset_fiscal.xlsx` – Arquivo contendo os dados utilizados no projeto, divididos em múltiplas abas com diferentes tipos de informação (dicionário de dados, dados cadastrais, comportamentais etc.).

---

## ⚙️ Tecnologias e Bibliotecas Utilizadas

- `pandas` e `numpy` – manipulação de dados
- `matplotlib` e `seaborn` – visualização gráfica
- `scikit-learn` – pré-processamento, modelagem e avaliação
- `RobustScaler` – normalização robusta aos outliers
- `LogisticRegression` – modelo de classificação binária

---

## 🧠 Metodologia

1. **Análise Exploratória** dos dados fiscais e cadastrais
2. **Engenharia de Atributos** com variáveis derivadas relevantes
3. **Normalização** dos dados contínuos
4. **Separação das variáveis preditoras e da variável alvo**
5. **Escolha do modelo**
6. **Treinamento do modelo com Regressão Logística**
7. **Avaliação por métricas como:**
   - Acurácia
   - F1-Score
   - Matriz de confusão
   - Curva ROC
8. **Análise dos coeficientes** para interpretação do modelo

---

## ✅ Resultados

O modelo obteve desempenho satisfatório com métricas robustas e análise interpretável, o que o torna aplicável como ferramenta de apoio à decisão para **identificação de potenciais casos de sonegação**.

A escolha da Regressão Logística foi guiada por critérios como:
- Simplicidade e eficiência
- Clareza interpretativa dos resultados
- Boa performance com dados tratados e balanceados

---

## 📌 Considerações Finais

Este projeto serve como um **exemplo prático e explicável** de como modelos de machine learning podem ser aplicados à fiscalização tributária, com ênfase na **transparência e suporte à decisão pública**.

---

## 📫 Contato

Desenvolvido por [Gabriel Rosemberg](https://www.linkedin.com/in/gabrielrtsilva/)

Fique à vontade para abrir *issues* ou sugestões no repositório.

