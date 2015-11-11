# MongoDB - Aula 01 - Exercício
autor: SEU NOME

## Importando os restaurantes

```sh
adriano@lee:~/Downloads$ mongoimport --db be-mean --collection restaurantes --drop --file restaurantes.json
2015-11-10T23:34:22.524-0200	connected to: localhost
2015-11-10T23:34:22.525-0200	dropping: be-mean.restaurantes
2015-11-10T23:34:23.810-0200	imported 25359 documents

```

## Contando os restaurantes

```
adriano@lee:~/Downloads$ mongo be-mean
MongoDB shell version: 3.0.7
connecting to: be-mean
> db.restaurantes.find({}).count()
25359

```
