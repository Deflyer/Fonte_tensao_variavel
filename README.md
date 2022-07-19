# Fonte_tensao_variavel

Trabalho do projeto do professor Simões

## Lista de componentes escolhidos para o trabalho
* **Capacitor**: Capacitor de 25V com 470μF (R$ 1,05) ;
* **Potenciômetro**: Potenciômetro linear de 10k (R$ 7,00) ;
* **Diodo Zenner**: Diodo Zenner de 13V (R$ 0,48) ;
* **Transistor**: Transistor NPN BC337 (R$ 0,69) ;
* **Diodo**: Diodo 1N4007 (10 * R$ 0,20 = R$ 2,00) ;
* **Resistores**:
    * **680 Ohms**: (10 * R$ 0,07 = R$ 0,70),
    * **1k Ohms**: (10 * R$ 0,07 = R$ 0,70),
    * **4,7k Ohms**: (10 * R$ 0,07 = R$ 0,70).

### **Total**: R$ 13,32

### Etapas de construção do circuito:
Primeiramente, tomando como base as aulas do Simões e os projetos de nosso veteranos, chegamos nesse estado do circuito:
<img src="./imagens_simulação/image.png">
Agora faltava descobrir as especificações de cada um dos componentes.

Primeiramente, a tomada já estava definida como de 110V, faltando agora o transformador:

<img src="./imagens_simulação/transformador.png">

O transformador tem o papel de reduzir a tensão que entrará no circuito por meio da diferença de voltas nas espiras que tem na entrada e na saída dele, ele gera um campo magnético diferente de cada lado induzindo uma corrente de valor diferente, conseguindo assim alterar também a tensão.

Para esse projeto, nós usamos um que o professor Simões possuía que era capaz de gerar uma saída de 24 V a partir de uma entrada de 110V.

Agora, a ponte de diodos:

<img src="./imagens_simulação/ponte_diodo.png">

A ponte de diodos tem a função de retificar a tensão. Como a tomada possui corrente alternada, a DDP fica alternando entre positiva e negativa, mas por meio da ponte de diodos, conseguimos fazer com que ela seja sempre positiva.

Agora, o capacitor:

<img src="./imagens_simulação/transformador.png">

