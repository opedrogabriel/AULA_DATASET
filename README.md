# aula_dataset

Dataset escolhido: Netflix 
  link: https://www.kaggle.com/datasets/shivamb/netflix-shows

Descrição das 4 consultas SQL realizadas:
  1 - Quantidade de programas por tipo de show (filme ou série):
  2 - Número de programas adicionados por ano:
  3 - Título e ano de lançamento do programa mais antigo:
  4 - Número de programas adicionados após o ano de 2020:
  5 - Média do ano de lançamento dos programas por tipo de show:

Insights obtidos com as consultas
  1 - Distribuição dos Programas por Tipo de Show (Filme ou Série):
    A primeira consulta revela quantos programas de cada tipo (filme ou série) existem na base de dados. 
    Isso pode mostrar a proporção entre filmes e séries disponíveis na plataforma, ajudando a entender se há 
    um foco maior em um determinado tipo de conteúdo.

2 - Tendência de Adição de Programas ao Longo dos Anos:
  A segunda consulta mostra quantos programas foram adicionados ao catálogo em cada ano.
  Isso ajuda a identificar tendências ao longo do tempo, como um aumento significativo na adição de novos conteúdos em
  determinados anos, o que pode estar relacionado a estratégias de expansão ou eventos específicos.

3 - Identificação do Programa Mais Antigo:
  A terceira consulta identifica qual é o programa mais antigo disponível na base de dados, fornecendo o título e o ano de lançamento. 
  Isso pode ser interessante para destacar o conteúdo clássico ou para entender o alcance temporal do catálogo.

4 - Crescimento do Catálogo Após 2020:
  A quarta consulta indica quantos programas foram adicionados ao catálogo após o ano de 2020. Este insight pode ser útil para avaliar o impacto de novos lançamentos, 
  possivelmente relacionados à pandemia de COVID-19 ou a novas estratégias de mercado.

5 - Média de Lançamento por Tipo de Show:
  A quinta consulta calcula a média do ano de lançamento dos programas para filmes e séries. 
  Com isso, é possível entender se filmes ou séries tendem a ser mais recentes ou mais antigos, o que pode influenciar o perfil de conteúdo da plataforma.

Estrutura do banco de dados (tabelas e colunas):

Colunas: show_id, type_show, title, date_added, release_year

Tipo de dado: VARCHAR(255), VARCHAR(255), VARCHAR(255), DATETIME, DATETIME

Descrição: 
  Identificador único do programa (chave primária).
  Tipo de programa, como "Filme" ou "Série".
  Título do programa.
  Data em que o programa foi adicionado ao catálogo.
  Ano de lançamento do programa.

Descrição Geral:
  Banco de Dados: test_netflix_db
Tabela: netflix

    Colunas: 5 colunas (show_id, type_show, title, date_added, release_year)
    Chave Primária: show_id