# Modelos para prever as mortes causadas pelo acidente do Titanic pelas características dos tripulantes

O primeiro modelo foi basicamento o que já existia nos arquivos do desafio. Ele se base no fato que as mulheres e crianças eram resgatadas primeiro. Então o que ele faz é simplesmente dizer que as mulheres foram salvas e os homens não. O score alcançado foi de 0.76 (sendo 0 o mínimo e 1 o máximo)

O segundo modelo foi já mais elaborado. Ele incluiu uma variável, a idade. Para isso foi utilizado Python e as bibliotecas pandas e sklearn. Apesar da maior complexidade, ele alcançou uma pontuação abaixo da do modelo 1 mais simples.

O terceiro modelo se assemelha ao modelo 2, porém ele usa uma ferramenta do sklearn de criar teste e validação apenas com os dados do teste, sem utilizar os dados de teste dados pela comunidade, o que pode acontecer.

O quarto modelo é uma aprimoração do modelo 3. O que ele faz basicamente é selecionar os dados para teste e validação mais vezes aleatoriamente, dessa forma vão gerar vários resultados e com a média deles se alcança um resultado mais preciso.

O quinto modelo nós fizemos o uso do RepeatedKFold que é como o KFold, porém já imbutido o loop de repetição. Além disso conseguimos colocar mais variáveis para ajudar na modelagem, porém o resultado continua mais baixo que só avaliar o gênero.

O sexto modelo conseguimos acrescentar mais variáveis analisando através dos dados de validação aquelas que poderiam influenciar no resultado. Porém, não se obteve um aumento da nota

O sétimo modelo foi trocado o modelo de machine learning RandomForrest por LogisticRegression que é mais simples. Com isso percebemos um aumento do resultado tanto na validação quanto na pontuação no Kaggle. Porém, ainda falta para passar a previsão que mulheres foram salvas e homens não.

Esse estudo e projeto foi realizado seguindo o tutorial de Machine Learning do Mario Filho no youtube - https://www.youtube.com/watch?v=1UVizW6eFrY&list=PLwnip85KhroW8Q1JSNbgl06iNPeC0SDkx
