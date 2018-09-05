# carBluetooth
## Projeto para o desenvolvimento do carrinho bluetooth desenvolvido por Vitor Ravacci e Lucas Toneto

O projeto consiste de uma montagem básica do arduíno usando certos componentes que dividiremos em duas classes, essenciais e opcionais que depois de listados serão explicados como foram implementados e sua utilização.

## Componentes:

Componentes Essenciais:
- 1 Bateria de 9v
- 4 pilhas médias
- 1 adaptador para 4 pilhas
- x fios Jumper macho-macho
- 1 Arduino Uno R3
- 1 Mini Protoboard 
- 1 Módulo bluetooth para arduíno - HC05
- 1 Driver Duplo Ponte H
- 1 Conetor de bateria de 9v para P4
- Ferro de Solda e estanho 
- Interruptor

Componentes Opcionais: 
- 2 LEDs Vermelhos
- 2 LEDs Amarelos ou RGB
- 1 Buzzer
- Resistores de 220 Ohms no mínimo

## Processo de Montagem:

1) Organização - Primeiramente você deve organizar sua mesa de trabalho para um espaço em que não haja nada além do essencial para a construção do carrinho, incluindo os componentes opcionais. DICA: separe todos os componentes por categorias, como os fios (Jumpers) em um lugar e as baterias e pilhas em outro lado.

2) Montagem Básica - Posicione dentro da estrutura do carinho onde melhor encaixar as partes do arduino e todos os outros componentes (ver a imagem 2 para ver a utilizada) dando maior preferência para as partes maiores.

3) Montagem Avançada - Após posicionar todos os componentes em seus devidos lugares chegou a hora de ligar os fios e todo o resto do projeto para isso você utilizara como base o esquema de montagem disponível nesse mesmo repositório do GITHub chamada imagem 1 (ESQUEMA DE MONTAGEM), o módulo bluetooth o driver duplo e o interruptor ligado na mini protoboard, a utilização do interruptor é controlar a corrente transmitida do negativo do adaptador de pilhas para o Driver Duplo, para não mante-lo sempre ligado e acabar gastando toda a bateria das pilhas, além do processo você poderá implementar os LEDs traseiros alimentados também pelas pilhas e ligados na miniprotoboard.
OBS: pode ser que você use algumas vezes o ferro de solda para poder implementar alguns componentes, mas CUIDADO para não danificar o circuito, sendo assim só solde o realmente necessário como alguns fios o led e o interruptor.

4) Fixação - Essa é uma parte do projeto que você deverá ter em mente o melhor modo de fixar os componentes na estrutura do carrinho sem que isso comprometa o circuito ou não permita que sejam feitas mudanças posteriores no mesmo, para isso você poderá utilizar como exemplo fitas e lacres 

5) Lataria - Essa parte fica mais subjetiva, pois o carrinho fica por sua conta e você pode (ou não) decidir fazer a lataria dele com qualquer tipo de material para que ele fique mais bonito visualmente

### Sites-Base:
 - https://blog.usinainfo.com.br/carrinho-arduino-controlado-por-bluetooth-e-sistema-android/

 - http://www.instructables.com/id/Arduino-Bluetooth-RC-Car-Android-Controlled/?ALLSTEPS

