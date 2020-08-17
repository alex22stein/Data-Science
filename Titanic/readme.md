# Modelos para prever as mortes causadas pelo acidente do Titanic pelas características dos tripulantes

O primeiro modelo foi basicamento o que já existia nos arquivos do desafio. Ele se base no fato que as mulheres e crianças eram resgatadas primeiro. Então o que ele faz é simplesmente dizer que as mulheres foram salvas e os homens não. O score alcançado foi de 0.76 (sendo 0 o mínimo e 1 o máximo)

O segundo modelo foi já mais elaborado. Ele incluiu uma variável, a idade. Para isso foi utilizado Python e as bibliotecas pandas e sklearn. Apesar da maior complexidade, ele alcançou uma pontuação abaixo da do modelo 1 mais simples.

O terceiro modelo se assemelha ao modelo 1, porém ele usa uma ferramenta do sklearn de criar teste e validação apenas com os dados do teste, sem utilizar os dados de teste dados pela comunidade, o que pode acontecer.
