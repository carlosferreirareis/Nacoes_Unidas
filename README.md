# United Nations Project
*Projeto Nações Unidas*

This is a data analysis and visualization project for the completion of the Data Analytics Bootcamp.
    *Este é um projeto de análise e visualização de dados para conclusão de curso do Bootcamp Data Analytics.*

This repository contains a data analysis and visualization project related to data made available by the United Nations (UN) and the World Bank. The objective of the project is to explore, analyze and visualize UN data to obtain meaningful insights and generate useful information.
    *Este repositório contém um projeto de análise e visualização de dados relacionado disponibilizados pela Organização das Nações Unidas (ONU) e Banco Mundial. O objetivo do projeto é explorar, analisar e visualizar os dados da ONU para obter insights significativos e gerar informações úteis.*

## Description
*Descrição*

The United Nations Project uses publicly available UN data for analysis. The datasets used are CSV files provided by the UN and World Bank, containing information on key indicators in various areas, such as health, education, economy, among others.
    *O Projeto Nações Unidas utiliza dados da ONU disponibilizados publicamente para análise. Os datasets utilizados são arquivos CSV fornecidos pela ONU e Banco Mundial , contendo informações sobre indicadores-chave em diversas áreas, como saúde, educação, economia, dentre outras.*

The analysis of the data is performed using the pandas library of Python. Data cleaning, transformation and filtering techniques are applied to obtain relevant information. Then, the data is visualized through graphs and thematic maps using visualization libraries, such as matplotlib, seaborn.
    *A análise dos dados é realizada utilizando a biblioteca pandas do Python. São aplicadas técnicas de limpeza, transformação e filtragem dos dados para obter informações relevantes. Em seguida, os dados são visualizados por meio de gráficos e mapas temáticos usando bibliotecas de visualização, como matplotlib, seaborn.*

## Analysis Process
*Processo de Análise*

1. **Data Preparation:** The CSV file provided by the UN is loaded using the pandas library. Data cleaning steps are performed, such as removing missing values and treating data types.
 *1. **Preparação dos Dados:** O arquivo CSV fornecido pela ONU é carregado utilizando a biblioteca pandas. São realizadas etapas de limpeza de dados, como remoção de valores ausentes e tratamento de tipos de dados.*

2. **Data Exploration:** Exploratory analysis is conducted to better understand the data structure, identify patterns and trends, and obtain descriptive information. Functions and methods of pandas are used to calculate statistics, perform aggregations and groupings, and extract relevant information.
 *2. **Exploração dos Dados:** A análise exploratória é conduzida para entender melhor a estrutura dos dados, identificar padrões e tendências, além de obter informações descritivas. São utilizadas funções e métodos do pandas para calcular estatísticas, realizar agregações e agrupamentos, e extrair informações relevantes.*

2.1. Still in exploratory analysis, excel was also used to visualize the data structure and understand its disposition in the dataset.
 *2.1. Ainda em análise exploratória foi utilizado também excel para visualização da estrutura de dados e compreender sua disposição no dataset.*

3. **Data Visualization:** Visualizations are generated to communicate the insights obtained. Graphs are used to represent the data in a clear and intuitive way. Libraries such as matplotlib and seaborn are used to create impactful visualizations and Tableau.
 *3. **Visualização de Dados:** São geradas visualizações para comunicar os insights obtidos. Gráficos são utilizados para representar os dados de forma clara e intuitiva. Bibliotecas como matplotlib e seaborn são utilizadas para criar visualizações impactantes e o Tableau.*

    3.1. In this step Tableau has a very dense participation making possible the visualization and better understanding of the data presented and treated, in order to generate perceptions about content.
 *3.1. Nesta etapa o Tableau tem uma participação muito densa possibilitando a visualização e melhor compreensão dos dados apresentados e tratados, de modo a gerar percepções sobre conteúdo.*

4. **Interpretation of Results:** Based on the analyzes performed and the visualizations generated, relevant insights and conclusions are identified about the global trends present in the datasets presented. This information initially has the purpose of academic studies.
 *4. **Interpretação dos Resultados:** Com base nas análises realizadas e nas visualizações geradas, são identificados insights e conclusões relevantes sobre as tendências globais presentes nos datasets apresentados. Essas informações inicialmente tem finalidade de estudos acadêmicos.*

## Project Structure
*Estrutura do Projeto*

The project is structured as follows:
    *O projeto está estruturado da seguinte forma:*

```
├── data
│   └── Bases de dados capturados em https://data.un.org/ e https://data.worldbank.org/ 
├── notebooks
│   └── Nacoes_Unidas.ipynb
├── visualizations
│   ├── Tableau
│   ├── bar_charts
│   ├── line_charts
│   └── thematic_maps
└── README.md
```

Graphics and maps generated by the project.
    *Gráficos e mapas gerados pelo projeto.*

- The README.md file is this file, providing information about the project.
    *O arquivo `README.md` é o presente arquivo, fornecendo informações sobre o projeto.*

## Project Requirements
*Requisitos do Projeto*

- Tableau
- Python 3.7 or higher
- Pandas library
- Visualization libraries (matplotlib, seaborn, folium)
- Jupyter Notebook (optional, to run the analyze_data.ipynb notebook)

## How to Use
*Como Usar*

```
1. Clone this repository on your local machine:
```
 *1. Clone este repositório em sua máquina local:*


- git clone https://github.com/carlosferreirareis/Nacoes_Unidas.git
```
2. Make sure you have Python 3.7 or higher installed in your environment.
```
 *2. Certifique-se de ter o Python 3.7 ou uma versão superior instalada em seu ambiente.*

```
3. Install the necessary libraries. You can install all dependencies using the `requirements.txt` file:
```
 *3. Instale as bibliotecas necessárias. Você pode instalar todas as dependências usando o arquivo `requirements.txt`:*


- pip install -r requirements.txt
```
4. Run the `Nacoes_Unidas.ipynb` notebook using Jupyter Notebook or JupyterLab.
```
 *4. Execute o notebook `Nacoes_Unidas.ipynb` utilizando Jupyter Notebook ou JupyterLab.*

```
5. Follow the detailed instructions in the notebook to perform the data analysis and generate the visualizations.
```
 *5. Siga as instruções detalhadas no notebook para realizar a análise dos dados e gerar as visualizações.*

## Contributions
*Contribuições*

Contributions to improvements and new features in this project are welcome. If you want to contribute, follow the steps below:
    *Contribuições para melhorias e novas funcionalidades neste projeto são bem-vindas. Caso queira contribuir, siga os passos abaixo:*

1. Fork this repository.
 *1. Faça um fork do repositório.*

2. Create a branch for your new feature or bug fix:
 *2. Crie um branch para sua nova funcionalidade ou correção de bug:*

```
git checkout -b nome-da-sua-funcionalidade
```
3. Make your changes and make explanatory commits:
 *3. Realize suas alterações e faça commits explicativos:*

```
git commit -m "Descrição das alterações"
```
4. Send your branch to the remote repository:
 *4. Envie seu branch para o repositório remoto:*

```
git push origin nome-da-sua-funcionalidade
```
5. Open a pull request in the original repository describing your changes.
 *5. Abra um pull request no repositório original descrevendo suas alterações.*

# Contact
*Contato*

https://www.linkedin.com/in/-carlos-reis
https://github.com/carlosferreirareis  
---