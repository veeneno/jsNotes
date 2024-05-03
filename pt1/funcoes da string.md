## funcoes da string

No javascript tambem temos diversas funcoes de *string* porem as 10 principais sao:

~~~javascript
let texto = "Olá, mundo!";

// 1. length - Retorna o comprimento da string
console.log("Comprimento:", texto.length); // input = 11

// 2. toUpperCase() - Converte a string em maiúsculas
console.log("Maiúsculas:", texto.toUpperCase()); // input = OLÁ, MUNDO!

// 3. toLowerCase() - Converte a string em minúsculas
console.log("Minúsculas:", texto.toLowerCase()); // input = olá, mundo!

// 4. indexOf() - Retorna o índice da primeira ocorrência de um determinado valor na string
console.log("Índice de 'mundo':", texto.indexOf("mundo")); // input = 5

// 5. lastIndexOf() - Retorna o índice da última ocorrência de um determinado valor na string
console.log("Último índice de 'o':", texto.lastIndexOf("o")); // input = 9

// 6. slice() - Extrai uma parte da string e retorna como uma nova string
console.log("Slice:", texto.slice(5, 10)); // input = mundo

// 7. replace() - Substitui uma substring por outra substring
console.log("Replace:", texto.replace("mundo", "Planeta")); // input = Olá, Planeta!

// 8. concat() - Concatena duas ou mais strings e retorna uma nova string
console.log("Concat:", texto.concat(" Have a nice day!")); // input = Olá, mundo! Have a nice day!

// 9. split() - Divide uma string em um array de substrings com base em um separador
console.log("Split:", texto.split(",")); // input =  [ 'Olá', ' mundo!' ]

// 10. trim() - Remove espaços em branco do início e do final da string
let textoComEspacos = "   Espaços em branco    ";
console.log("Trim:", textoComEspacos.trim()); // input = Espaços em branco


~~~