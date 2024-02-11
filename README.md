# Databricks | Desenvolvendo um Poderoso Recomendador de Músicas do Spotify

## 💡Objetivos
Desenvolver um recomendador de músicas utilizando um extenso conjunto de dados fornecido pelo Spotify na ferramenta Databricks. A ferramenta Databricks desempenha um papel crucial no cenário atual da análise de dados. Com sua capacidade de lidar com grandes volumes de dados, também conhecidos como Big Data, ela simplifica e agiliza as operações. Além disso, oferece ambientes Spark pré-configurados, facilitando ainda mais o processo de análise e manipulação de dados em escala.

## 🖥️Desafios do Projeto
Neste desafio empolgante, mergulharemos fundo no universo do **Spark** para explorar e maximizar seus recursos. Através do processamento paralelo, desbloquearemos o potencial para lidar com volumes massivos de dados de forma eficiente e escalável. Além disso, exploraremos a poderosa **Pandas API**, conhecida anteriormente como Koalas, que nos oferece acesso aos recursos robustos do Pandas, enquanto mantemos a vantagem essencial do Spark: o paralelismo. Durante o projeto, nosso foco estará na criação de um recomendador musical. Utilizando o **MLlib do Spark** em conjunto com o ambiente do **Databricks**, nosso objetivo é desenvolver um sistema capaz de gerar recomendações personalizadas de músicas. Basta fornecer o nome de uma música, como um hit da Taylor Swift, e nosso algoritmo conectado com a **API do Spotify**, irá gerar uma playlist exclusiva com 10 músicas recomendadas.

###### Imagem 1: Playlist gerada pelo recomendador de músicas
<img src="/img/img-playlist.png">

## 📄Conhecimentos Desenvolvidos
|Atividades|Realizadas |
|----------|-----------|
| Carregar dados no DBFS | Transformar o SQL DataFrame em Pandas DataFrame |
| Adequar os tipos das colunas utilizando o astype do Pandas | Utilizar o método replace do DataFrame do Pandas |
| Analisar os dados pelo ano de lançamento | Agrupar os dados pela década |
| Criar gráfico de barra para análise de quantidade de dados por década | Analisar o impacto que o ano de lançamento tem nas outras features |
| Responder questionamentos utilizando os dados | Vetorizar seus dados com VectorAssembler |
| Padronizar os dados com StandardScaler | Reduzir a dimensão dos dados com PCA |
| Criar clusters com K-Means | Analisar os agrupamentos |
| Identificar o cluster | Extrair as componentes das músicas |
| Calcular a distância entre as componentes das músicas | Criar uma lista com as músicas mais próximas e de um mesmo cluster |
| Utilizar a biblioteca Spotipy para extrair dados das músicas | Buscar os IDs das músicas com os métodos filter e select do Spark.SQL.DataFrame |
| Exibir a capa do álbum das músicas recomendadas com a biblioteca skimage e matplotlib |  |

##  🗂️Organização dos Arquivos
* Notebooks Jupyter | Databricks
    - Projeto Spotify  - Parte 1 até 3: Exploração e tratamento dos dados, seleção de dados, configuração do cluster, implementação do algoritmo Kmeans, cálculo de distâncias. Utilizando também a API do Spotify, chegamos à criação da playlist.

    - Desafio Projeto Spotify - Manipulação e transformação eficientes de dados e arquivos utilizando o Apache Spark em conjunto com o formato Parquet. Incluíndo conversão de arquivos CSV para o formato Parquet, garantindo maior desempenho e eficiência no processamento e armazenamento dos dados.

* Data - Conjunto de dados do Spotify, obtido do Kaggle, uma plataforma vital na comunidade de dados, é uma fonte valiosa de informações para análise e exploração no campo da ciência de dados.

## 🎞️Imagens do Projeto

###### Imagem 2: Gráfico de dispersão bidimensional utilizando biblioteca Plotly
<img src="/img/img-grafico-dispersao.png">

###### Imagem 3: API do Spotify
<img src="/img/img-api-spotify.png">

###### Imagem 4: Notebook Databricks
<img src="/img/img-databricks.png">

## 🔍Referências
- [Alura](https://www.alura.com.br/)
