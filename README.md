export function criarFila(tamanho = 10){
    return [... new Array (tamanho)];
}

export function inserirItemFila(queue, item){
    const spacePosition = queue.indexOf(undefined);
    if(spacePosition === -1){
        console.log("Está cheio");
        return;
    }
    queue[spacePosition] = item;
}

export function retirarItemFila(queue){
    if(queue[0] == undefined) {
        return;
    }

export function limparFila(queue) {
    queue.forEach(item => {
        item = undefined;
    });
}

export function verTamanhoFila(fila =[ ]){

let emptySpaces
(fila.length fila.indexOf(undefined))
let usedSpaces = emptySpaces
let size fila.length
let subQueue = [ ]

for(let i=0; i<fila.indexOf(undefined); i++){
subQueue[i] = fila[i]
}
console.log(
fila,
{


"emptySpaces"emptySpaces,
"usedSpaces":usedSpaces,
"size": size,
"subQueue": subQueue,

}

)

}


index

import { criarFila, inserirItemFila, retirarItemFila, filaVazia, limparFila, verificarTamanhoFila, verificarPrimeiroElemento, verificarElementoFila, verificarPosicaoFila, verificarFilaCheia, verificarUltimo } from './fila.js';

console.log("");
console.log("Minha fila!");
console.log("");

const queue = criarFila(3);

// Insere os itens na fila.
inserirItemFila(queue, "dado");
inserirItemFila(queue, "tabuleiro");
inserirItemFila(queue, "monopoly");

console.log("Fila", queue);

// Retira dois itens da fila.
retirarItemFila(queue);
retirarItemFila(queue);

console.log("Fila", queue);
