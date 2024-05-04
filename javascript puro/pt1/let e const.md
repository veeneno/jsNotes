## Variaveis e Constantes

No javascript temos 3 maneiras de declarar algo
- let
- const
- var

porem hoje em dia apenas utilizamos o let para variaveis e o const para constantes o var nao eh mais utilizado

### diferenca entre let e const

bom a diferenca entre a let e a const eh basicamente que a let pode ser alterado conforme o codigo, ja a const nao

#### exemplo let

~~~javascript
let nome = "Victor"     // Tipo String 
let idade = 16          // Tipo numerico 
let estudante = true    // Tipo bool 
let radiante = false    // Tipo bool 

idade = idade+2

console.log(idade)    // input = 18

console.log(nome)       // input = Victor
nome = "Pedro"
console.log(nome)       // input = pedro

~~~
#### exemplo const
~~~javascript
const nome = "Victor"     // Tipo String 
const idade = 16          // Tipo numerico 
const estudante = true    // Tipo bool 
const radiante = false    // Tipo bool 

idade = idade + 2

console.log(idade) // input = erro no console

nome = "pedro"

console.log(nome) // input = erro no console
~~~