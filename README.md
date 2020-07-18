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
Para a eletrônica, a impressora funcionará principalmente a partir de uma placa Arduino Uno, a qual irá controlar os motores, sensores e demais componentes utilizando um shield [CNC V3](https://www.handsontec.com/dataspecs/cnc-3axis-shield.pdf) e quatro [drivers DRV8825](https://www.ti.com/lit/ds/symlink/drv8825.pdf).

## Programação
A parte de controle por software será usada nas etapas de modelagem o objeto 3D em um programa de CAD, no processo de manufatura assistida por computador realizado por um programa de CAM e no firmware do Arduíno, responsável por transformar as instruções de movimentação do bico extrusor em sinais para os drivers dos motores.  

## Extrusão
Para a extrusão dos filamentos da impressora, será usado um módulo extrusor, chamado de [HotEnd V6](https://e3d-online.dozuki.com/c/V6), e um motor de passo, depositando o filamento na extrusora. Utilizaremos materiais de até 1.75mm, respeitando os limites impostos pelas peças.

## Passo a passo
* Realizamos algumas reuniões com o grupo, procurando escolher as melhores tecnologias e abordagens para a fabricação da impressora
* Escrevemos uma lista com os materiais que já possuíamos, incluindo componentes eletrônicos, leitores de CD/DVD e motores
* Dividimos o projeto em partes, sendo elas: mecânica, eletrônica, de programação e de extrusão. Assim poderiamos trabalhar separadamente e, aos poucos, unir cada uma delas
* Fizemos testes com os motores de passo dos leitores, compreendendo como eles funcionavam e quais eram suas limitações
* Testamos o shield CNC e o Arduino UNO, usando os motores de passo comuns que já possuíamos (além dos leitores)
* Buscamos quais são as melhores bibliotecas de Arduino para controlar o shield CNC e o circuito eletrônico
* Estudamos os softwares necessários para realizar a impressão de uma peça 3D, passando por modelagem digital do objeto, conversão do mesmo para G-Code e comunicação com o Arduino
* Compramos o módulo extrusor, uma das poucas peças que não possuíamos e que não poderiamos reaproveitar de outros meios
* Testamos a medição da temperatura do módulo extrusor

## Bugs e problemas conhecidos

Por enquanto, não encontramos bugs, erros ou falhas no projeto. O maior problema encontrado é a dificuldade na integração das partes, devido a necessidade de trabalharmos a distância e online durante a pandemia do CoVID-19. Muitas peças de uma mesma parte estão espalhadas entre os membros do projeto.

## Autores 
- [Adriano Emidio](https://github.com/adrianoemidio)
- [Anderson Pinheiro Garrote](https://github.com/AndersonGarrote)
- [Marcus Vinícius Natrielli Garcia](https://github.com/Infinitemarcus)
- [Vinícius Carvalho Venturini](https://github.com/Vinicius-Venturini)

## Resultados
Devido a pandemia atual, não tivemos a oportunidade de juntar presencialmente todos os componentes e peças. No entanto, obtivemos diversos bons resultados em cada parte separada do sistema.

Estamos em fase de testes tanto para a extrusão quanto para a programação, buscando entender os detalhes de ambos e, futuramente, interligá-los.

A parte eletrônica está praticamente pronta, com todas as peças essenciais já em nossa posse. Fala, todavia, progresso na união com as outras partes.

Por fim, a mecânica é a parte mais estagnada. Montar e planejar os eixos e a movimentação das peças necessita da união presencial dos membros do projeto.

