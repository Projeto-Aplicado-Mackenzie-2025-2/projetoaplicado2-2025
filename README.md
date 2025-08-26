# projetoaplicado2-2025
Projeto Aplicado 2 - Ciências de Dados Mackenzie

<img src="/pics/netflix.gif" alt="image" width="1200" height="750">

# Análise das pontuações Netflix
Projeto aplicado do curso de Ciências de Dados Mackenzie, com a finalidade de explorar os dados disponiveis das votações dos usuários do Netflix.
[![Netflix](/pics/MCK_horizontal_vermelho.png)](#)


### Netflix
A Netflix foi fundada em 1997 por Reed Hastings e Marc Randolph, inicialmente como um serviço de aluguel de DVDs pelo correio nos Estados Unidos. Seu diferencial era um modelo de assinatura, sem multas por atraso, que atraiu muitos clientes.

**Evolução da Netflix**
- 1999 – Lançamento do serviço de assinatura de DVDs.
- 2007 – Início do serviço de streaming, permitindo que os assinantes assistissem a filmes e séries pela internet.
- 2010 – Expansão internacional, começando pelo Canadá.
- 2013 – Produção de conteúdos originais, com o lançamento de House of Cards, que marcou o início do investimento pesado em séries e filmes próprios.
- 2016 – Expansão global, tornando-se disponível em mais de 190 países.
- 2021 – Atinge mais de 200 milhões de assinantes e se torna um dos maiores estúdios de entretenimento do mundo.

Atualmente, a Netflix continua investindo em produções próprias, competindo com outras gigantes do streaming como Disney+, Prime Video e HBO Max.

Mais informações sobre a empresa, [click aqui](Netflix.md).

[![Netflix](https://img.shields.io/badge/Netflix-E50914?logo=netflix&logoColor=white)](https://www.netflix.com/br/)
[![Wikipedia](https://img.shields.io/badge/Wikipedia-%23000000.svg?logo=wikipedia&logoColor=white)](https://pt.wikipedia.org/wiki/Netflix)

### Dataset
Nosso dataset foi obtido no site do Kaggle. ( ![Kaggle](https://img.shields.io/badge/Kaggle-035a7d?logo=kaggle&logoColor=white) )

**Link do dataset:** 
https://www.kaggle.com/datasets/netflix-inc/netflix-prize-data

Periodo de coleta: 1999-11-11 - 2005-12-31

### Arquivos
**combined_data_1**<br>
**combined_data_2**<br>
**combined_data_3**<br>
**combined_data_4**<br>
**movie_titles**<br>
**qualifying**<br>
**probe**<br>

### Visão Geral
A Netflix promoveu uma competição aberta chamada “Netflix Prize”, em 2006, para que um novo algoritmo de predição de avaliação de filmes pelos seus assinantes fosse criado.<br>
Foi oferecido um prêmio de U$ 1.000.000,00 para o vencedor: o grupo conhecido por BellKor's Pragmatic Chaos1, em 2009.<br>
A título de curiosidade, a Netflix nunca chegou a usar realmente o algoritmo vencedor2.<br>

### Descritivo dos dados
O dataset escolhido é formado por um conjunto de 5 (cinco) arquivos em formato “.txt” e 1 (um) arquivo em formato “.csv”, detalhados a seguir. <br>
1) Os arquivos “combined_data_1.txt”, “combined_data_2.txt”, “combined_data_3.txt” e “combined_data_4.txt” contêm os dados de avaliação realizada pelo assinante, distribuídos da seguinte forma:<br>
Uma linha contendo o Id do filme seguido de dois pontos e, cada linha subsequente, correspondendo a uma avaliação de um assinante, obedecendo o seguinte formato, separado por vírgula:<br>
  - Id do assinante, anonimizado
  - Avaliação, sendo ela um número inteiro em uma escala de 1 a 5
  - Data da avaliação, no formato YYYY-MM-DD

```MovieID1:
CustomerID11,Rating11,Date11
CustomerID12,Rating12,Date12
…
MovieID2:
CustomerID21,Rating21,Date21
CustomerID22,Rating22,Date22
…
```
2) O arquivo movie_titles.csv contém os dados dos filmes avaliados e disponíveis no catálogo da Netflix, no seguinte formato, separado por vírgula:
  - Id do filme, anonimizado
  - Ano de lançamento (variando de 1890 a 2005)
  - Título

```
MovieID1,YearOfRelease1,Title1
MovieID2,YearOfRelease2,Title2
MovieID3,YearOfRelease3,Title3
MovieID4,YearOfRelease4,Title4
...
```

Os arquivos “probe” e "qualifying" não serão utilizado neste projeto. Ele contém dados de treinamento do modelo desenvolvido, e modelagem e treinamento não faz parte do escopo deste projeto.

### Objetivos e Metas
Analisar o comportamento dos usuários com as votações, buscando as pontuações de cada filme, análise média de pontuação por ano, pontuação por usuário.

### Documento de Apresentação
- [1ª Entrega](#)
- [2ª Entrega](#)
- [3ª Entrega](#)
- [4ª Entrega](#)

### Cronograma
- [Cronograma](#)

### Apresentação
Quer assistir nossa apresetação utilize o nosso link: [![Youtube](https://img.shields.io/badge/YouTube-red?logo=youtube&logoColor=white)](#) 


### Autores
[Alexandre Zamarion Cepeda](https://www.linkedin.com/in/alexandre-zamarion-cepeda/).

[Felipe Gabriel Lopes Pinheiro Clarindo](https://www.linkedin.com/in/felipeclarindo/).

[Thiago Godeguesi](https://www.linkedin.com/in/thiagogodeguesi/).

[Victória Martins Fortes](https://www.linkedin.com/in/victoriafortes/).
  

### Orientação 

[Felipe Albino dos Santos](https://www.linkedin.com/in/felipea/).
