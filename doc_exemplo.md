# **App-Família**
 A ideia foi criar um código para a seleção das famílias.  A  _**var novaFamilia,**_ receberá uma nova família a cada sorteio.

```
var novaFamilia = 0;
```    
## Famílias
Famílias a serem sorteadas Exp:
```
var familiaNoAltarOne = 1;
var familiaNoAltarTwo = 2;
var familiaNoAltarThree = 3;
var familiaNoAltarFour = 4;
var familiaNoAltarFive = 5;
var familiaNoAltarSix = 6;
var familiaNoAltarSeven = 7;
var familiaNoAltarEight = 8;
var familiaNoAltarNine = 9;
var familiaNoAltarTen = 10;
``` 

Usei basicamente uma _**estrutura de controle**_ e _**operadores lógicos**_ e _**relacionais.**_  
- `if ()`
- `&& ()`
-  `>< == ( )`  


Exibindo resultados;


```
if (novaFamilia == familiaNoAltarOne && familiaNoAltarOne < familiaNoAltarTwo) {
    console.log("Laerte & Família!");
}
if (novaFamilia == familiaNoAltarTwo && familiaNoAltarTwo < familiaNoAltarThree) {
    console.log("Adiel & Família!");
}
```  
## Família não registrada
A função mostra a família que não se encontra cadastrada, assim toda vez que uma família for selecionada e ela não estiver no cadastro a função retornará a mensagem _**'Família não registrada'.**_

```
function registro(proximaFamilia) {
    if (novaFamilia >= familiaNoAltarTwelve) {
        console.log("Família não registrada!")
    }
}
registro();
```
