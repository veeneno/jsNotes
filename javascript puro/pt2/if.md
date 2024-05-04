## if, else e else if

O if else e else if, sao as principais condicoes do javascript, sendo as mais utilizdas

### **if**

o if quando traduzido tem o significado de "se" e no codigo ele eh o que inicia a condicao, ou seja, para termos o *else* e o *else if* temos que ter o **if** antes

### construcao do **if**
~~~javascript
    if(condicao) {
        //codigo
    }
~~~
#### EXEMPLO IF

~~~javascript
let nome = "Igor"

if(nome == "Igor") {
    console.log("Ola igor")
}

// NO CASO ACIMA O CONSOLE PRINTARA "Ola igor"
// agora vamos supor que o nome seja outro se nao igor

nome = "Pedro"

if(nome == "Igor"){
    console.log("Ola Igor")
}

console.log("Ola outro nome")

// NO CASO ACIMA O CONSOLE PRINTARA "Ola outro nome"
~~~

### **else**

Ja o **else** eh diferente, ele eh utilizado quando **nenhuma** condicao for verdadeira, e para termos o else temos que ***OBRIGATORIAMENTE*** ter o *if* antes

### construcao do **else**
~~~javascript
    if(condicao) {
        //codigo
    } else {
        // outro codigo
    }
~~~

#### EXEMPLO ELSE

~~~javascript
let numero = 10

if(numero < 10){
    console.log('O numero eh menor que 10')
} else {
    console.log("O numero eh maior ou = 10") // esse sera o input 
}
~~~

### **else if**

O **else if** eh uma condicao **intermediaria**, ou seja, ela fica no meio.

O **else if** necessita de um *if*, mas ***NAO*** necessita de um *else*.

### construcao do else if
~~~javascript
if(condicao){
    //codigo 1
} else if (condicao){
    //codigo 2
} else {
    //nao eh necessario, porem pode ter
}
~~~

#### EXEMPLO ELSE IF
~~~javascript
let numero = 15 

if(numero < 15) {
    console.log("O numero nao eh menor que 15")
} else if (numero == 15){
    console.log("O numero eh 15") // o input seria esse
} else {
    console.log("O numero eh maior que 15")
}
~~~

