# golang
monitorar vários sites através do Go


| :placard: Vitrine.Dev |     |
| -------------  | --- |
| :sparkles: Nome        | **Golang - monitoramento**
| :label: Tecnologias | VSCode, Golang (tecnologias utilizadas)
| :fire: Desafio     |  https://cursos.alura.com.br/course/golang

<!-- Inserir imagem com a #vitrinedev ao final do link -->

## Detalhes do projeto

O Google estava com um problema, pois muitos dos seus sistemas eram feitos em C++ e em C, e o processo de compilar esses programas, para gerar um executável, era complicado e demorado. Com isso, os engenheiros do Google tiveram a ideia de criar uma nova linguagem de programação, surgindo daí o Go.

Essa linguagem, diferentemente de outras linguagens, como C, Python e Java, é uma linguagem moderna, visto que ela foi criada em 2009, aproximadamente 20 anos depois que a maioria das outras linguagens foi criada. E nesses 20 anos, a computação foi evoluindo, evoluções essas que foram incorporadas no Go.

A primeira dessas evoluções faz com que o processo de compilação de um programa em Go é bem rápido, justamente o problema do Google. Um outra questão é a modularização da linguagem, com as suas funcionalidades espalhadas em pacotes, que são importados na nossa aplicação conforme a nossa necessidade.

Além disso, a sua sintaxe tem em torno de 25 palavras-chave, ou seja, uma sintaxe bem curta, fazendo com que o nosso código fique simples de se entender. Apesar da linguagem ser simples, ela é bem convencionada, já que o Go foi feito para ser uma linguagem rápida de desenvolvimento, então há certas convenções (algumas delas forçadas pela linguagem) que fazem com que o foco do programador seja em desenvolver código, e não em discutir como ele deve ser feito.

Outra coisa interessante é o jeito com que o Go trabalha com concorrência, paralelismo da linguagem. Essa é uma parte avançada, que não é o nosso foco, que é a introdução à linguagem, vendo a sua sintaxe, convenções, pacotes, tudo isso criando um projeto, um monitorador de sites, para colocar todos os sites que administramos e ficar verificando se o site está online ou não, e guardar um log para sabermos o horário em que o site estava online ou offline.

Então, vamos criar uma aplicação capaz de se comunicar com os sites, e ficar monitorando para ver se eles estão online ou caíram.
