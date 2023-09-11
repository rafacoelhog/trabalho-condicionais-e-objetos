# trabalho-condicionais-e-objetos
aula13?
/*
// this is a js file
// Rafaely Godoi

//EXERCICIOS DE INTERPRETAÇÃO DE CODIGO

//EXERCICIO 1
// a.Verifica se a idade da pessoa é maior ou igual a 18, e verificar se tem carteira de motorista.
// b.A mensagem "Alice pode dirigir!" sera impressa no console quando a condição "if" for verdadeira.
// E a mensagem "Alice não pode dirigir." sera impressa no console quando a condição "if" for falsa.

//EXERCICIO 2
// a.Imprimir no console se o animal "leao" é carnivoro ou nao.
// b.Leão é um animal carnívoro.

//EXERCICIO 3
// a.Verifica se o numero é maior do que 5, se o numero for maior que 5 ira imprimir no console "o numero é maior do que 5.".
// Se o numero for menor ou igual a 5 ira imprimir no console "o numero é menor ou igual a 5.".

// Em seguida verifica se o numero é par ou impar.
// Caso o numero for par ira imprimir no console "o numero é par.".
// Se não vai imprimir "o numero é impar.".

// b."o numero é maior do que 5." e  "o numero é par.".
 

//EXERCICIOS DE ESCRITA DE CODIGO

//EXERCICIO 1
const idade = prompt("qual é a sua idade?");
const idadeNumero = parseInt(idade);
if (idadeNumero >= 18) {
    console.log("voce é maior de idade.");
} else {
    console.log("voce é menor de idade.");
}

//EXERCICIO 2

const turno = prompt("qual turno voce estuda? digite 'M' para matutino, 'T' para tarde ou 'N' para noturno:");
if (turno === "M"){
    console.log("bom dia!");
} else if (turno === "T"){
    console.log("boa tarde!");
} else if (turno === "N"){
    console.log("boa noite!");
} else {
    console.log("turno nao reconhecido.");
}

//EXERCICIO 3
 const turno = prompt("qual turno voce estuda? digite 'M' para matutino, 'T' para tarde ou 'N' para noturno:");
 switch (turno) {
    case "M":
        console.log("Bom dia!");
        break;
    case "T":
        console.log("Boa tarde!");
        break;
    case "N":
        console.log("Boa noite!");
        break;
    default:
        console.log("Turno não reconhecido.");
        break;
 }

//EXERCICIO 4
const aluno = {
    nome:'joao',
    idade: 23,
    tipoDeCurso:'Administração',
    temBolsa: true
}
if (aluno.idade < 30 && aluno.tipoDeCurso === "Administração" && !aluno.temBolsa) {
    console.log("voce pode se candidatar a uma bolsa de estudos!");
} else {
    console.log("desculpe, voce não atende aos requisitos para a bolsa.");
} 

//EXERCICIO 5
const produto = {
    nome: "celular",
    preço: 2.300,
    desconto: 30,
    freteGratis: true
}
const preçoComDesconto = produto.preço * (1 - produto.desconto / 2.300);
let mensagem = `preço final: ${preçoComDesconto.toFixed(2)}`;
if (produto.desconto > 0){
    mensagem += `(desconto ${produto.desconto}%)`;
}
if (produto.freteGratis) {
    mensagem += "(frete Gratis)";
}
console.log(mensagem);
*/
