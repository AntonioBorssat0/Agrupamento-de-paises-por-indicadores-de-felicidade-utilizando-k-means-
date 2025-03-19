# Agrupamento de Países por Indicadores de Felicidade Utilizando K-Means

## 📌 Descrição
Este projeto analisa dados do **World Happiness Report** para agrupar países com características semelhantes em termos de felicidade, utilizando o algoritmo de clusterização **K-Means**. O objetivo é identificar padrões intrínsecos nos dados e entender como diferentes fatores contribuem para a felicidade de um país.

## 🎯 Objetivos
- Analisar como os países se distribuem geográfica e culturalmente em relação à felicidade.
- Identificar os indicadores determinantes para diferenciar os clusters.
- Examinar a correlação entre desenvolvimento econômico (países desenvolvidos vs. em desenvolvimento) e a classificação nos grupos identificados.

## 📊 Dados
Os dados foram coletados do Kaggle (**World Happiness Report**) e incluem as seguintes variáveis principais:

- **Country**: Nome do país  
- **Region**: Região do país  
- **Economy (GDP per Capita)**: PIB per capita  
- **Family**: Suporte social percebido  
- **Health (Life Expectancy)**: Expectativa de vida saudável  
- **Freedom**: Percepção de liberdade para escolhas de vida  
- **Generosity**: Nível de generosidade reportada  
- **Trust (Government Corruption)**: Percepção de confiança governamental  
- **Happiness Score**: Pontuação de felicidade  
- **Happiness Rank**: Classificação de felicidade  

## 🔬 Metodologia
A metodologia do projeto foi dividida em três etapas principais:

### 1️⃣ Coleta e Pré-processamento de Dados
- Extração de dados do Kaggle.
- Padronização dos nomes das colunas.
- Tratamento de valores ausentes e inconsistências nos dados.

### 2️⃣ Análise Descritiva e Exploratória
- Cálculo de estatísticas descritivas (média, desvio padrão, quartis).
- Compreensão das características e distribuição dos dados.

### 3️⃣ Clusterização com K-Means
- Normalização dos dados com **StandardScaler**.
- Aplicação do algoritmo **K-Means** para identificar clusters.
- Avaliação dos resultados usando métricas como **Silhouette Score, Calinski-Harabasz Score e Davies-Bouldin Score**.

## 📈 Resultados
Os resultados da análise e da clusterização são apresentados por meio de **gráficos e tabelas**, destacando os padrões identificados e as características dos clusters formados.
