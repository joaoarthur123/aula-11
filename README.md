//joao arthur
function imprimirOlaMundo(){}
console.log("Ola Mundo");{}

function imprimirNome(Nome){
    console.log("Ola" + Nome);
}
imprimirNome("joao");
imprimirNome("pedro");
imprimirNome("arthur");

let lernome = prompt("qual seu nome")
imprimirNome(lernome);

const a = 1

function imprimirVariavel (){
    const b = 2
    console.log('Variavel a', a);
    console.log('Variavel b', b);
}
imprimirVariavel()
console.log('Variavel a', a);


function calculaArea(altura, largura){
    const area = altura * largura
    return area
}
//Atribui retorno à uma variavel 
const areaCalculada = calculaArea(2, 3)

//Imprime retorno no console
console.log(calculaArea(2, 3))

function soma(soma1, soma2){
    const soma = soma1 + soma2;
    return soma;
}
const resultado = soma(3, 4);
console.log(soma(3, 4))

function retornaPrimeiroEUimito(meuarray = []){
    let novoArray = [];
    novoArray[0] = (meuarray[0])/2;
}
let antigoArray  =[1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19,20];
console.log(retornaPrimeiroEUimito(aintigoArray)):
