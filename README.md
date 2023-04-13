# valorGastoViagem
valorGastoViagem Javascript

// Faça um programa para calcular o valor de uma viagem

// // Você tera 3 variaveis. São:
// 1) Preco do combustivel
// 2) gasto medio de combustivel pelo veiculo por KM
// 3) Distancia em Km da viagem

// Imprima no console o valor que será gasto de combustivel para realizar esta viagem.


const precoCombustivel = 7.78
const kmPorlitros= 15;
const distanciaEmKm= 100;

const litrosConsumidos = distanciaEmKm/kmPorlitros;
const valorGasto = litrosConsumidos*precoCombustivel
console.log(valorGasto);
