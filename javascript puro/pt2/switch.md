## Switch

Ja o **switch** nao eh tao utilizado porem ainda sim ele eh muito bom

Ele eh muito util, em casos onde teriamos diversos *else if*

### Construcao do switch
~~~javascript
switch(condicao) {
  case x:
    // codigo para x
    break;
  case y:
    // codigo para y
    break;
  default:
    // codigo caso nao seja nenhum dos acima
}
~~~

O **break** serve para interromper o uso dentro do bloco do switch, o que deixa o codigo mais *otimizado*, nao tendo que ler as outras variacoes

#### EXEMPLO SWITCH
~~~javascript
let dia = segunda

switch(dia){
    case domingo:
        console.log("Hoje eh domingo")
        break
    case segunda:
        console.log("Hoje eh segunda")
        break
    case terca:
        console.log("Hoje eh terca")
        break
    default:
        console.log("Hoje eh outro dia")

    //  nesse caso o input seria "Hoje eh segunda"
}
~~~
