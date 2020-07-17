# Impressora 3D DVD
 Um projeto de uma impressora 3D simples usando drivers de CD/DVD e Arduino, desenvolvido no Hackerspace da UFSCar Sorocaba.

## Conceito
Este projeto se baseia no criação, desenvolvimento e montagem de uma impressora 3D, reaproveitando motores e drivers de leitores de CD/DVD e utilizando a placa Arduino Uno com um shield CNC.

O conceito inicial surgiu durante a atividade de extensão Hackerspace, da UFSCar Sorocaba, em 2019. O andamento do projeto ocorreu no ano seguinte, dentro da mesma atividade.

Esperamos, no final, ter uma impressora funcional que realize a produção de pequenos modelos 3D.

Os detalhes mais específicos de cada parte do projeto se encontram na [Wiki](https://github.com/AndersonGarrote/impressora_3D_DVD/wiki) do projeto. Este README é apenas uma visão geral.

## Mecânica
A parte mecânica da impressora se baseia na utilização de diversos motores de passo, tanto os encontrados nos drivers de CD/DVD, quanto avulsos, reproduzindo os eixos X, Y e Z necessários para a impressão em 3D. Um motor de passo também será usado para movimentar o filamento para a extrusora.

## Eletrônica
Para a eletrônica, a impressora funcionará principalmente a partir de uma placa Arduino Uno, a qual irá controlar os motores, sensores e demais componentes utilizando um shield CNC V3 e quatro drivers DRV8825.

## Programação
A parte de controle por software será usada nas etapas de modelagem o objeto 3D em um programa de CAD, no processo de manufatura assistida por computador realizado por um programa de CAM e no firmware do Arduíno, responsável por transformar as instruções de movimentação do bico extrusor em sinais para os drivers dos motores.  

## Extrusão
Para a extrusão dos filamentos da impressora, será usado 

## Passo a passo
* Realizamos algumas reuniões com o grupo, procurando escolher as melhores tecnologias e abordagens para a fabricação da impressora
* Dividimos cada uma das partes principais do projeto, sendo elas: mecânica, eletrônica, de programação e de extrusão

## Bugs e problemas conhecidos

## Autores 
- [Adriano Emidio](https://github.com/adrianoemidio)
- [Anderson Pinheiro Garrote](https://github.com/AndersonGarrote)
- [Marcus Vinícius Natrielli Garcia](https://github.com/Infinitemarcus)
- [Vinícius Carvalho Venturini](https://github.com/Vinicius-Venturini)

## Resultados
Devido a pandemia atual, não tivemos a oportunidade de juntar presencialmente todos os componentes e peças. No entanto, obtivemos diversos bons resultados em cada parte separada do sistema.

Estamos em fase de testes tanto para a extrusão quanto para o software, buscando entender os detalhes e pormenores de ambos.
