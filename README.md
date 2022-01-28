# Redes de Co-ocorrência de Artistas no Spotify

Esse repositório possui o código e análise de 100 playlists do Spotify.

Código para leitura de Json foi com base no seguinte repositório: https://github.com/vaslnk/Spotify-Song-Recom
mendation-ML/blob/master/EDA.ipynb

Para a execução do código em Python, é necessário instalar as seguintes bibliotecas:

* pandas
* json
* numpy
* scipy
* matplotlib
* seaborn
* collections
* networkx

Resultados de imagens geradas são salvas na pasta "Results", junto do grafo em formato .graphml

Junto do repositório está presente um arquivo html gerado via Gephi para analisar o grafo via browser.

Para isso, é necessário iniciar um servidor dentro da pasta Network. Em sistemas Linux, esse comando é realizado via terminal

* python -m http.server

