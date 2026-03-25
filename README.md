# 🎬 Sistema de Recomendação de Filmes com Machine Learning

Este projeto demonstra o desenvolvimento de um **sistema de recomendação de filmes** utilizando técnicas de **Machine Learning**.
O fluxo inclui **pré-processamento de dados**, **engenharia de features**, **clusterização** e um **modelo de recomendação baseado em similaridade**.

O sistema agrupa filmes com base em características como gênero, duração e classificação indicativa, e recomenda filmes semelhantes utilizando o algoritmo **K-Nearest Neighbors (KNN)**.

---

## 📌 Visão Geral do Projeto

O objetivo principal deste projeto é explorar como técnicas de Machine Learning podem ser utilizadas para:

* Identificar padrões em dados de filmes
* Agrupar filmes semelhantes usando clusterização
* Recomendar filmes com base em similaridade
* Apoiar análises exploratórias e tomada de decisão
* Simular um mecanismo simplificado de recomendação, semelhante aos utilizados por plataformas de streaming

---

## 🧠 Técnicas Utilizadas

O projeto aplica as seguintes técnicas de análise de dados e Machine Learning:

* Limpeza e tratamento de dados
* Engenharia de features
* Normalização e transformação de dados
* Clusterização com **K-Means**
* Redução de dimensionalidade com **PCA (Principal Component Analysis)**
* Sistema de recomendação com **K-Nearest Neighbors (KNN)**
* Visualização de dados

---

## 📊 Dataset

O dataset contém informações sobre filmes, incluindo:

* Título
* Gênero
* Duração
* Classificação indicativa
* Tipo (Filme ou Série)

### Principais transformações realizadas:

* Filtragem apenas de registros do tipo **Filme**
* Padronização das classificações indicativas
* Conversão de variáveis categóricas em formato numérico
* Seleção dos gêneros mais frequentes
* Criação de variáveis binárias para representação dos gêneros

---

## 🔎 Etapas do Projeto

### 1. Preparação dos Dados

* Importação das bibliotecas
* Carregamento do dataset
* Limpeza e transformação dos dados
* Padronização das classificações indicativas
* Criação de variáveis numéricas

---

### 2. Engenharia de Features

* Seleção dos **10 gêneros mais frequentes**
* Criação de variáveis binárias para gêneros
* Preparação das variáveis utilizadas no modelo

---

### 3. Análise de Clusterização (K-Means)

* Identificação do número ideal de clusters utilizando o **Método do Cotovelo (Elbow Method)**
* Agrupamento dos filmes com base em similaridade
* Análise dos grupos formados

---

### 4. Redução de Dimensionalidade (PCA)

* Redução de múltiplas variáveis em componentes principais
* Visualização dos clusters em um espaço bidimensional
* Facilitação da interpretação dos padrões encontrados

---

### 5. Sistema de Recomendação (KNN)

* Treinamento de um modelo baseado em similaridade
* Identificação dos filmes mais próximos em termos de características
* Geração de recomendações automáticas

---

## 🎯 Principais Funcionalidades

* Agrupamento de filmes com Machine Learning
* Sistema de recomendação baseado em similaridade
* Engenharia de features para variáveis categóricas
* Visualização de clusters com PCA
* Fluxo completo de análise de dados
* Estrutura reproduzível e escalável

---

## 🛠️ Tecnologias Utilizadas

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Plotly
* Jupyter Notebook

---

## 📈 Resultados Obtidos

O sistema desenvolvido é capaz de:

* Agrupar filmes em clusters com base em similaridade
* Visualizar padrões em dados multidimensionais
* Recomendar filmes semelhantes automaticamente
* Demonstrar a aplicação prática de algoritmos de Machine Learning em sistemas de recomendação

Este projeto simula a lógica utilizada em plataformas de streaming para personalização de conteúdo.

---

## 🚀 Como Executar o Projeto

### 1. Clonar o repositório

```bash
git clone https://github.com/ithanara/movie-recommendation-knn
```

### 2. Instalar as dependências

```bash
pip install pandas numpy scikit-learn matplotlib seaborn plotly
```

### 3. Executar o notebook

```bash
jupyter notebook
```

Abrir o arquivo:

```bash
movie_rec_system.ipynb
```

---

## 📂 Estrutura do Projeto

```
sistema-recomendacao-filmes/
│
├── dataset_final.csv
├── movie_rec_system.ipynb
├── README.md
```

---

## 📌 Aprendizados do Projeto

Este projeto demonstra, na prática:

* Como preparar dados para Machine Learning
* Como aplicar algoritmos de clusterização
* Como reduzir dimensionalidade com PCA
* Como construir um sistema de recomendação simples
* Como transformar dados em insights e funcionalidades

---

## 🔮 Possíveis Melhorias Futuras

Algumas evoluções possíveis para este projeto incluem:

* Utilizar **Cosine Similarity**
* Implementar **Filtragem Colaborativa**
* Criar uma API para o modelo
* Construir uma dashboard interativa
* Integrar novos datasets
* Implementar deploy do modelo
