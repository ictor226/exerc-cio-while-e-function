/*console.log ("atividade 01")
function tabuada_5 (contador){
contador =1
 
while (contador <= 10 ){
 
console.log ( '5 x ' + contador + '=' + contador * 5)
contador++
}
}
tabuada_5()
*/

/*
console.log ("atividade 02")
function soma_ate_100(contador, soma){
contador = 1
soma = 0
 
while (contador <= 100){
      soma += contador
contador++
}
return soma
}
*/

/*
function Fibonacci(n) {
var a = 0, b = 1;
 
while (n-- > 0) {
    console.log(a);
    [a, b] = [b, a + b];//dei uma pesquisada nesse por não lembrar e um pouco de dificuldade  tambem, revi meu repositorio
}
}
 
Fibonacci(11);
*/
function invertString(string) {
let stringReverse = string.split("").reverse().join("");
 
console.log(stringReverse);
 
}
 
invertString("salve paulao ");
//dei uma pesquisada nesse codigo, assisti varios videos no yt de como fazer e entender tambem 
