# Games-Classification

Este é um projeto de classificação de jogos, que coleta dados de vários jogos através de um processo de scraping da página do Metacritic. Em seguida, todos os dados são tratados e usados para treinar um modelo de classificação.

## Parte 1: Scraping de dados
A primeira parte deste projeto é o scraping de dados dos jogos presentes nas páginas do Metacritic, realizado através da biblioteca Selenium do Python. Os links das páginas de cada jogo foram salvos em um arquivo txt, enquanto que os dados a seguir foram salvos em um arquivo json:

- Título
- Data de lançamento
- Plataforma
- Metascore
- Quantidade de comentários dos críticos
- User score
- Quantidade de avaliações dos usuários
- Desenvolvedor do jogo
- Gênero
- Quantidade de jogadores

## Parte 2: Tratamento de dados
Na segunda parte deste projeto, todos os dados coletados são tratados para garantir sua consistência e utilidade. Isso inclui a limpeza de valores faltantes, a conversão de dados para o formato correto e a codificação de dados categóricos.

## Parte 3: Treinamento do modelo de classificação
Na terceira e última parte deste projeto, os dados tratados são usados para treinar um modelo de classificação. Este modelo é usado para prever a pontuação do metascore de um jogo com base em outras informações, como o desenvolvedor do jogo e o gênero.
