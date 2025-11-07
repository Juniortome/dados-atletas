# dados-atletas
aplicação contendo informações de um atleta
Aplicação em JavaScript que recebe informações de um atleta, calcula categoria, IMC, média das notas válidas e exibe todos os resultados no console.

🧩 Estrutura da Classe Atleta

Atributos:
nome
idade
peso
altura
notas

Métodos principais:
calculaCategoria() → define a categoria conforme a idade
calculaIMC() → calcula o índice de massa corporal
calculaMediaValida() → remove a maior e a menor nota e calcula a média das restantes
obtem...() → retorna os valores e cálculos do atleta

Regras de Cálculo

Categoria por idade:
Faixa etária	Categoria
9 a 11 anos	Infantil
12 a 13 anos	Juvenil
14 a 15 anos	Intermediário
16 a 30 anos	Adulto
Outras idades	Sem categoria

IMC = peso / (altura * altura)

Média válida:
Remove a menor e a maior nota e tira a média das restantes.

Como executar
Instale o Node.js (https://nodejs.org)
Crie um arquivo atleta.js
Cole o código acima
Execute no terminal:
