# Exercício 2
Crie um array de números que contenha 8 números.
Depois disso, utilize este array para criar duas funcões de array `map()`:

1. A primeira deve retornar um novo array contendo os números múltiplicados por 3, Crie uma `const triplos`, e guarde o valor do array nesta const;
2. A segunda deve retornar um novo array contendo os números divididos por 2. Crie uma `const metades`, e guarde o valor do array nesta const;

const numeros = [77, 852, 47544, -558, 855, 777, 19, 3]

const triplos = numeros.map((elemento, indice, arrayOriginal) => {
  return elemento * 3
})
//console.log(triplos)

const metades = numeros.map((elemento, indice, arrayOriginal) => {
  return elemento % 2
})
//console.log(metades)
