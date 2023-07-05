# Projeto Nações Unidas

Este é um projeto de análise e visualização de dados para conclusão de curso do Bootcamp Data Analytics.

Este repositório contém um projeto de análise e visualização de dados relacionado disponibilizados pela Organização das Nações Unidas (ONU) e Banco Mundial. O objetivo do projeto é explorar, analisar e visualizar os dados da ONU para obter insights significativos e gerar informações úteis.

## Descrição

O Projeto Nações Unidas utiliza dados da ONU disponibilizados publicamente para análise. Os datasets utilizados são arquivos CSV fornecidos pela ONU e Banco Mundial , contendo informações sobre indicadores-chave em diversas áreas, como saúde, educação, economia, dentre outras.

A análise dos dados é realizada utilizando a biblioteca pandas do Python. São aplicadas técnicas de limpeza, transformação e filtragem dos dados para obter informações relevantes. Em seguida, os dados são visualizados por meio de gráficos e mapas temáticos usando bibliotecas de visualização, como matplotlib, seaborn.

## Processo de Análise

1. **Preparação dos Dados:** O arquivo CSV fornecido pela ONU é carregado utilizando a biblioteca pandas. São realizadas etapas de limpeza de dados, como remoção de valores ausentes e tratamento de tipos de dados.

2. **Exploração dos Dados:** A análise exploratória é conduzida para entender melhor a estrutura dos dados, identificar padrões e tendências, além de obter informações descritivas. São utilizadas funções e métodos do pandas para calcular estatísticas, realizar agregações e agrupamentos, e extrair informações relevantes.

Ainda em análise exploratória foi utilizado excel para visualização da estrutura de dados e compreender sua disposição no dataset.

3. **Visualização de Dados:** São geradas visualizações para comunicar os insights obtidos. Gráficos são utilizados para representar os dados de forma clara e intuitiva. Bibliotecas como matplotlib e seaborn são utilizadas para criar visualizações impactantes e o Tableau.

Nesta etapa o Tableau tem uma participação muito densa possibilitando a visualização e melhor compreensão dos dados apresentados e tratados, de modo a gerar percepções sobre conteúdo.

4. **Interpretação dos Resultados:** Com base nas análises realizadas e nas visualizações geradas, são identificados insights e conclusões relevantes sobre as tendências globais presentes nos datasets apresentados. Essas informações inicialmente tem finalidade de estudos acadêmicos.

## Estrutura do Projeto

O projeto está estruturado da seguinte forma:

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
 gráficos e mapas gerados pelo projeto.
- O arquivo `README.md` é o presente arquivo, fornecendo informações sobre o projeto.

## Requisitos do Projeto

- Tableau
- Python 3.7 ou superior
- Biblioteca pandas
- Bibliotecas de visualização (por exemplo, matplotlib, seaborn, folium)
- Jupyter Notebook (opcional, para executar o notebook analyze_data.ipynb)

## Como Usar

1. Clone este repositório em sua máquina local:

```
git clone https://github.com/carlosferreirareis/Nacoes_Unidas.git
```

2. Certifique-se de ter o Python 3.7 ou uma versão superior instalada em seu ambiente.

3. Instale as bibliotecas necessárias. Você pode instalar todas as dependências usando o arquivo `requirements.txt`:

```
pip install -r requirements.txt
```

4. Execute o notebook `Nacoes_Unidas.ipynb` utilizando Jupyter Notebook ou JupyterLab.

5. Siga as instruções detalhadas no notebook para realizar a análise dos dados e gerar as visualizações.

## Contribuições

Contribuições para melhorias e novas funcionalidades neste projeto são bem-vindas. Caso queira contribuir, siga os passos abaixo:

1. Faça um fork do repositório.

2. Crie um branch para sua nova funcionalidade ou correção de bug:

```
git checkout -b nome-da-sua-funcionalidade
```
3. Realize suas alterações e faça commits explicativos:

```
git commit -m "Descrição das alterações"
```
4. Envie seu branch para o repositório remoto:

```
git push origin nome-da-sua-funcionalidade
```
5. Abra um pull request no repositório original descrevendo suas alterações.

# Contato
https://www.linkedin.com/in/-carlos-reis/
https://github.com/carlosferreirareis  
---