# ProjetoEstatistica

## UFRPE
# ESTATÍSTICA EXPLORATÓRIA I - T02 (2022.1)
Professor: KLEBER BARROS

# Estatistica_1VA

Autor: Gilmar Rodrigues Campelo
## Descrição

Projeto para analizar a ocorrencia de Enterococcus nas prais do litoral paulista especificamente na cidade de Mongaguá 

foi desenvolvido para a disciplina de Estatistica Exploratória do curso de Licenciatura em Computação.
## Dados
Os dados foram estraidos do arquivo sp_beaches.xlsx no excel que está na pasta projeto1VA este arquivo consiste da ocorencia de Enterococcus nas prais do litoral

paulista, mas as análises realizadas consiste apenas nas prais da cidade de Mongaguá.

## Ferramentas
Para realizar essas análises e relatório final foi utilizado a aplicação RStudio

## Etapas de Preparação dos Dados 

Importa o arquivo de xlsx no Rstudio usando a função read_excel.

Todas as instruções foram realizados num único bloco utilizando %>%.

Os dados foram filtrados  pela cidade  (filter).

A última coluna da tabela foi modificada para numérica (mutate e as.numeric).

Os dados foram agrupados por praia (group_by).

## Etapas do Projeto

### Etapa 1:
Encontrar média, desvio-padrão, mediana, Q1, Q3, mínimo e máximo dos enterococos de cada praia  utilizando o comando summarise no Rstudio e foram dispostos 

na tabela dados.

### Etapa 2:
Gráfico de barras com a variável Beach, ordenando da praia com maior quantidades de amostras para a menor. 

Colorir gráfico com base na praia. Anotar as porcentagens no topo das barras gráficos, gráfico  baseado na tabela dados1 realizados com a ferramenta ggplot2.

### Etapa 3:
Gráfico de barras com a variável Beach, ordenando da praia com menor quantidades de amostras para a maior, gráfico  baseado na tabela dados1.

### Etapa 5:
Gráfico de pizza  gráfico  baseado na tabela dados1.

### Etapa 6:
Histograma com todos os dados de enterococos das praias da cidade de Mongaguá,  gráfico  baseado na tabela dados2. 

### Etapa 7:
Box-plots de todas as praias da cidade de Mongaguá num único gráfico,  gráfico  baseado na tabela dados2. 

### Etapa 8:
Relatório apresentado as estatística e cada um dos gráficos e explicando os resultados foi utilizado a ferramenta  R markdown.

# Considerações Sobre Enterococcus:

Enterococcus  é um gênero bacteriano que inclui várias espécies comuns em ambientes naturais e animais, bem como em humanos.

Algumas espécies de Enterococcus são benéficas e habitam o trato intestinal humano, enquanto outras podem causar infecções, como endocardite, infecções do trato urinário, meningite e

outras infecções hospitalares. Alguns tipos de Enterococcus são resistentes a muitos antibióticos, tornando-os desafiantes de serem tratados. 

É importante realizar testes para identificar a presença de Enterococcus em amostras clínicas e implementar medidas de prevenção e controle de infecções 

para minimizar o risco de disseminação.

A contaminação por Enterococcus nas praias pode ser causada por várias fontes, incluindo descargas de esgotos inadequadamente tratados, runoff de terra, resíduos de animais e 

materiais fecais de seres humanos. A presença elevada de Enterococcus na água da praia pode indicar a presença de material fecal e, portanto, uma ameaça potencial à saúde humana.

A exposição à água contaminada pode levar a infecções na pele, no trato respiratório e no trato gastrointestinal. É importante monitorar a qualidade da água nas praias e tomar medidas

para controlar a contaminação, incluindo a melhoria da infraestrutura de tratamento de esgoto e a educação da população sobre as boas práticas de saneamento.
