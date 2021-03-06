> # Estudo de *Machine Learning* com Titanic DataSet

<p align="center">
  <img width="550" height="250" src="https://canalhistoria.pt/wp-content/uploads/2016/05/1.Portada.jpg">
</p>

>> O naufrágio do RMS Titanic é uma das tragédias mais famosas da história, originando diversos livros, filmes e afins. É válido lembrar que a história narrada de forma célebre por James Cameron em seu filme de 1997, ilustra perfeitamente o motivo deste desafio. Vamos começar com uma breve perspectiva sobre o tema: 
>> O Titanic foi um navio de passageiros construído nos estaleiros da Harland and Wolff durante o período de março de 1909 a maio de 1911 em Belfast no Reino Unido. Naquela época, a construção do Titanic levou cerca de 2 anos e custou 7,5 milhões de dólares. A embarcação partiu em sua viagem inaugural de Southampton para Nova Iorque em 10 de abril de 1912, com passagem em Cherbourg-Octeville na França e em Queenstown na Irlanda. Devido a sua excelente projetação, gerou boatos de que a embarcação seria "inafundável", porém, às 23h40min do dia 14 de abril, a embarcação se chocou contra um iceberg. Em 15 de abril de 1912, o Titanic afundou matando 1.502 dos 2.224 passageiros e tripulantes, ou seja, apenas 32% desses passageiros sobreviveram ao naufrágio, tornando assim o maior desastre marítimo em tempos de paz da história. 
> ## Problemática
>> O navio estava sendo operado com uma tripulação de 892 pessoas e poderia comportar até 2.432 passageiros, distribuídos pelas três classes disponíveis.
>> Os motivos que contribuíram para o naufrágio foram: fatores naturais, como o clima; e causas humanas, como negligência, pois não haviam botes salva-vidas suficientes para os passageiros e tripulantes e muitos dos botes salva-vidas não estavam com a sua capacidade máxima de pessoas a bordo, e se estivessem seria possível salvar 53% dos passageiros, mas apenas 32% deles sobreviveram.
Embora aqueles que escaparam com vida tiveram sua sorte, alguns grupos de pessoas eram mais propensos a escaparem da morte do que outros. A maioria do sobreviventes eram mulheres, crianças e passageiros da 1ª Classe, deixando evidente que existe algum padrão que pode ser extraído dos dados brutos, que será apresentado ao longo do projeto.

> ## Objetivo
>> Construir um algoritmo de *Machine Learning* para prever o índice de sobrevivência dos passageiros do *Titanic*, que tenha pelo menos 80% de acurácia, baseadas nas *features* dos *datasets* disponibilizados no desafio do *[Kaggle](https://www.kaggle.com/c/titanic)*.

>## Metodologia:
>> - Será utilizada o CRISP-DM (*Cross Industry Standard Process for Data Mining*), é uma metodologia de processo de mineração de dados, capaz de transformar os dados em conhecimento e informações para estratégias de negócio.

>### Classificador de dados utilizado no *Machine Learning*:
>> * Cross Validation com K-fold;
>> * KNN;
>> * Árvore de Decisão; 
>> * Florestas Aleatórias (Random Forest);
>> * Naive Bayes;
>> * Support Vector Machine (SVM);
>> * QDA; 
>> * Regressão Linear.
>### Tecnologias utilizadas:
>> #### Ambiente de desenvolvimento:
>> - Jupyter Notebook - Servidor do Kaggle
>> #### Linguagem de programação:
>> - Python
>> #### Bibliotecas:
>> - Pandas
>> - Numpy
>> - Seaborn
>> - Matplotlib
>> - SciKit Learn
>> #### Formato dos *datasets*:
>> - .csv (valores separados por vírgulas)
>## Roadmap:
>> 1. Bussines Understanding
>>> - [x] Entender o problema
>>> - [x] Definir um objetivo
>> 2. Data Understanding
>>> - [x] Importar as bibliotecas utilizadas
>>> - [x] Importar os *datasets* utilizando a biblioteca Pandas
>>> - [x] Analisar os *datasets*
>> 3. Data Preparation
>>> - [x] Criar classes baseados nos pronomes de tratamento
>>> - [x] Substituir valores da *feature* 'Sex' para valores numéricos;
>>> - [x] Preencher os valores vazios das idades, baseados nos nas médias de idade dos pronomes de tratamento
>>> - [x] Criar classes para as idades
>> 4. Modeling
>>> - [x] Definir o classificador dos dados
>> 5. Evaluation
>>> - [x] Verificar se os resultados foram atingidos baseados no objetivo definido
>> 6. Deployment
>>> - [x] Colocar o modelo para produção
>>> - [x] Acompanhar a execução do modelo
>>> - [x] Adaptar ou alterar o modelo conforme necessidade

>> Link Notebook: https://www.kaggle.com/tatianaabe/titanic-notebook-datascience
