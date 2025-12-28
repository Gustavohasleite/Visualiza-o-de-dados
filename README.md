# Visualização de Dados de Diabetes

Este projeto consiste em uma análise exploratória de dados (EDA) de um conjunto de dados de diabetes pré-processado. O objetivo é visualizar a distribuição de diversas métricas de saúde e sua relação com o diagnóstico de diabetes.

## 📁 Estrutura do Projeto

- **`diabetes_preprocessado.csv`**: O conjunto de dados utilizado na análise. Contém informações métricas de saúde e o diagnóstico.
  - Colunas:
    - `#Gravidezes`: Número de vezes que engravidou.
    - `Glicose`: Concentração de glicose plasmática.
    - `PD`: Pressão sanguínea diastólica (mm Hg).
    - `DobraTriceps`: Espessura da dobra cutânea do tríceps (mm).
    - `Insulina`: Insulina sérica de 2 horas (mu U/ml).
    - `IMC`: Índice de massa corporal (peso em kg / (altura em m)^2).
    - `DiabetesPedigreeFunction`: Função de pedigree de diabetes (histórico familiar).
    - `Idade`: Idade em anos.
    - `Classe`: Variável alvo (0 ou 1), indicando a ausência ou presença de diabetes.

- **`VisualizacaoDados.ipynb`**: Jupyter Notebook contendo o código Python para carregar os dados e gerar as visualizações.

## 📊 Análises Realizadas

O notebook gera gráficos para cada variável do dataset, incluindo:
1. **Histograma Geral**: Distribuição da variável para todos os pacientes.
2. **Histograma por Classe**: Comparação da distribuição da variável entre pacientes com e sem diabetes.
3. **Boxplot por Classe**: Visualização estatística (mediana, quartis, outliers) da variável separada por diagnóstico.

## 🛠️ Tecnologias Utilizadas

- **Python**
- **Pandas**: Para manipulação e análise de dados.
- **NumPy**: Para computação numérica.
- **Matplotlib**: Para criação de gráficos.
- **Seaborn**: Para visualização de dados estatísticos.
- **Jupyter Notebook**: Ambiente de desenvolvimento interativo.

## 🚀 Como Executar

1. Certifique-se de ter o Python instalado.
2. Instale as bibliotecas necessárias:
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```
3. Abra o notebook no Jupyter:
   ```bash
   jupyter notebook VisualizacaoDados.ipynb
   ```
4. Execute as células para visualizar as análises.
