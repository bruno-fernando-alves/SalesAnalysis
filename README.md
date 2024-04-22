# SalesAnalysis
repositório de analise de vendas
Estrutura de Pastas Após o tratamento
![Logo](img/dirs.PNG) 

# Start Session

Leitura dos dados csv de vendas, essa etapa os dados sem tratamentos
![Logo](img/step_start.PNG) 

Persistencia dos dados em parquet para melhorar a performace de leitura e próximas etapas
![Logo](img/step1.PNG) 

Separação de dados Ano e Mês, acrescentamos também User
Sempre colocando cada comentário das etapas 

![Logo](img/step2.PNG) 

Analise exploratora de dados do df, analisando vendas por produtos e top users que mais venderam

![Logo](img/step3.PNG) 

Salvar os Df agregados em parquet e o df main em Delta para analises posteriores

![Logo](img/step3.1.PNG) 

Depois dessas etapas, realizei alguns plots para analisar vendas por anos e tratamento de algumas colunas, posso dizer que eu tentei fazer um modelo de regressão conforme a imagem a seguir:
![Logo](img/step5.PNG) 

Porém após analise vi que precisaria de mais alguns tratamentos, além disso o ideial seria vários teste para chegar no melhor modelo.

Após tratamentos agendei os jobs

![Logo](img/jobs.PNG) 
O erro que aparece foi eu intencionalmente cancelando o job
