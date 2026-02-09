# Valida-o-de-Modelos-de-Ajuste-de-Hiperpar-metros# 
🧠 Atividade – Módulo 13 | Validação de Modelos e Ajuste de Hiperparâmetros

Este repositório contém uma atividade prática desenvolvida no **Módulo 13 do curso de Python / Ciência de Dados**, com foco em **validação de modelos**, **validação cruzada** e **ajuste de hiperparâmetros**, utilizando ferramentas do **scikit-learn**.

O objetivo do projeto é **avaliar corretamente o desempenho de modelos de Machine Learning** e **otimizá-los**, evitando overfitting e melhorando a capacidade de generalização.

---

## 🧠 O que é feito neste projeto

O notebook percorre as seguintes etapas:

1. **Importação de bibliotecas**

   * pandas, numpy
   * matplotlib
   * scikit-learn

2. **Preparação dos dados**

   * Separação entre variáveis independentes (X) e variável alvo (y)
   * Organização do dataset para modelagem

3. **Validação cruzada (Cross-Validation)**

   * Uso de `cross_val_score`
   * Avaliação mais robusta do desempenho do modelo
   * Comparação entre treino simples e validação cruzada

4. **Pipeline de Machine Learning**

   * Encadeamento de pré-processamento e modelo
   * Padronização com `StandardScaler`
   * Código mais limpo e reutilizável

5. **Ajuste de hiperparâmetros**

   * Uso de `GridSearchCV`
   * Teste de diferentes combinações de parâmetros
   * Identificação da melhor configuração

6. **Avaliação do melhor modelo**

   * Métricas de desempenho
   * Comparação entre modelo base e modelo otimizado

7. **Visualização dos resultados**

   * Análise gráfica do desempenho
   * Interpretação dos resultados obtidos

---

## 📁 Estrutura do repositório

```
📂 projeto-modulo-13
 ├── atividade_modulo_13.ipynb
 └── README.md
```

---

## 📦 Bibliotecas utilizadas

* pandas
* numpy
* matplotlib
* scikit-learn

---

## ▶️ Como executar o projeto

1. Clone o repositório:

   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```

2. Instale as dependências:

   ```bash
   pip install pandas numpy matplotlib scikit-learn
   ```

3. Abra o notebook:

   ```bash
   jupyter notebook
   ```

4. Execute as células em ordem.

---

## 🎯 Aprendizados principais

* Importância da validação cruzada
* Diferença entre avaliação simples e robusta
* Ajuste de hiperparâmetros com GridSearch
* Uso de Pipelines em Machine Learning
* Melhoria da generalização do modelo

---

## 👤 Autor

Projeto desenvolvido por **Samuel Lopes**
Estudante de Ciência de Dados | Python | SQL | Machine Learning

---

📌 *Projeto com finalidade educacional, focado em boas práticas de avaliação e otimização de modelos de Machine Learning.*
