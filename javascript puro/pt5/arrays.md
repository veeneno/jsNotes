### construcao de um array

~~~javascript
let frutas = ["banana", "coco", "pessego"] // array com elementos ja definidos
let nomes = [] // elementos ainda nao definidos

//o index que no caso eh o 0 no seguinte console representa o 1 elemento do array
console.log(frutas[0]) // input = banana
// resto do exemplo
console.log(frutas[1]) // input = coco
console.log(frutas[2]) // input = pessego
console.log(frutas.lenght) // input = 3
~~~
-----

Vamos supor que queremos printar na tela todos elementos de um array, porem se tivermos 100 elementos teriamos que colocar um console.log() 100 vezes e nao queremos isso, como fazemos entao?

#### EXEMPLO DA UTILIZACAO DE UM ARRAY

~~~javascript
let nomes = ["jorge", "Matheus", "Rafael", "izadora", "isabela", "Guilherme"]

// array com os nomes ja definidos, agora queremos mostrar todos na tela, para isso utilizaremos o for loop

for(let i = 0;i<nomes.lenght;i++){
    console.log(nomes[i])
}

// pronto
~~~
usamos o for com o index **i**, e enquanto i fosse menor que o numero de elementos em nomes, ele ia executar o console.log() e ia printar o elemento do numero do index, ou seja, ia comecar do 0 e iria ate o 5.

