## Conversao de valores

No javascript podemos **converter** os valores recebidos por usuarios ou criados por nos mesmos.

Temos: 

- Number()
- String()
- Boolean()

### Fazendo a conversao de uma string para um numero

~~~javascript
let numero

numero = window.prompt("Escolha um numero")
console.log(typeof numero) // input = String
numero = Number(numero)
console.log(typeof numero) // input = Numero

~~~

### Convertendo tudo

~~~javascript
let x - "pizza"
let y - "pizza"
let z = "pizza";
x = Number(x);
y = String(y) ;
z = Boolean( z) ;
console.log(x, typeof x); // input = Nan 'number' pois nao eh um numero
console.log(y, typeof y); // input = pizza string
console.log(z, typeof z); // input = true 'boolean'
~~~