# O Objetivo desse projeto primeiramente é desenvolver minhas habilidades em analise de dados em Python e fazer uma discussão estatistica do resultado, é um projeto de estudo, então obviamente terão alguns erros ou pontos que posso ter deixado de notar,além disso existem as limitações das bases de dados que usei no projeto, por estarem um pouco desatualizadas, não contabilizam todas as vendas dos jogos, a meta é melhorar o coding e a discussão teorica conforme concluo mais projetos ;)

# A ideia central do projeto é ver se existe relação entre o numero de vendas globais de um jogo e sua nota no Metacritic, será que as reviews de criticos tem impactado no sucesso comercial dos jogos ? jogos muito bem avaliados SEMPRE tem alcançado sucesso comercial ? 

# Foram utilizadas as bibilotecas Pandas para leitura, limpeza e filtragem de dados e matplotlib para a construção dos graficos, além do Jupyter Notebook como ambiente de desenvolvimento

# O primeiro passo foi o tratamento dos dados baixados do kaggle, nosso dataset inicial de vendas e de notas no metacritic estava bem bagunçado, então padronizei os nomes dos jogos deixando todos em minusculo e removendo os espaços extras, isso permite o cruzamento entre as duas tabelas vendas x metacritic, além disso alguns jogos na lista não apresentavam o numero de vendas, por restrições em divulgação da empresa ou falta de dados, então removi eles da lista, apos isso tinham algumas duplicatas nas bases de dados, o motivo, tem jogos que são lançados para mais de uma plataforma, ps4, xbox one, pc, então eu somei os dados de vendas de todas as plataformas, ao final,foi criada uma nova base de dados limpa que pode ser encontrada na pasta data desse repositorio, além dela, as outras bases de dados que usei tambem estão disponiveis la. 
### 🏆 Top 10 - Aclamação Crítica (Metacritic)

| Jogo | Vendas Globais (Mi) | Nota Metacritic |
| :--- | :---: | :---: |
| nfl 2k1 | 1.09 | 97.0 |
| grand theft auto v | 64.29 | 96.8 |
| uncharted 2: among thieves | 6.74 | 96.0 |
| red dead redemption 2 | 19.71 | 95.7 |
| bioshock | 4.27 | 95.3 |
| grand theft auto iv | 22.53 | 95.3 |
| grand theft auto iii | 13.11 | 95.0 |
| portal 2 | 3.79 | 95.0 |
| red dead redemption | 13.07 | 95.0 |
| mass effect 2 | 4.95 | 94.7 |

### 💰 Top 10 - Maiores Vendas Globais

| Jogo | Vendas Globais (Mi) | Nota Metacritic |
| :--- | :---: | :---: |
| grand theft auto v | 64.29 | 96.8 |
| call of duty: black ops | 30.99 | 82.0 |
| call of duty: modern warfare 3 | 30.71 | 81.0 |
| call of duty: black ops ii | 29.59 | 80.3 |
| call of duty: ghosts | 28.80 | 73.6 |
| call of duty: modern warfare 2 | 25.02 | 91.3 |
| minecraft | 24.01 | 89.5 |
| grand theft auto iv | 22.53 | 95.3 |
| call of duty: advanced warfare | 21.78 | 80.7 |
| the elder scrolls v: skyrim | 20.51 | 91.5 |
# SEÇÃO PARA OS GRAFICOS 
# DISCUSSÃO ESTATISTICA
