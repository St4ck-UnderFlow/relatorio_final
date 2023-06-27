# Relatório Final - p2 Estrutura de Dados

## Resumo
Nosso desafio era criar um jogo sobre um viajante, chamado Maxwell, que tem o objetivo de chegar a uma cidade chamada Nargumun, nossa meta durante a criação do jogo era proporcionar a sensação de liberdade ao jogar com o personagem Maxwell, podendo se movimentar livremente pelo mapa enquanto se respeita as regras estabelecidas previamente. Enfrentando diversos obstáculos durante a codificação, com isso, tivemos que pesquisar e pedir ajuda para pessoas com mais experiência, além de trabalhar em equipe para tentar superar as adversidades, melhorando nosso conhecimento de código e nossa capacidade de trabalhar em equipe.

---

## Introdução
O projeto foi proposto pelo professor Dimmy Magalhães, durante a disciplina de Estrutura de Dados. Os alunos foram desafiados a desenvolver um jogo sobre um viajante que deveria transportar uma jóia do poder. O projeto deveria ser feito em grupo e utilizar a linguagem Java para a sua implementação. O principal objetivo desse trabalho é entender, de maneira prática, os conceitos abordados em sala, tais como: árvores, arrays e grafos. Bem como, aprimorar nosso trabalho em equipe, organização e resolução de problemas.

---

## Descrição do Projeto: 

### Arquitetura: 
Para garantir uma implementação modular, reutilizável e organizada do jogo, optamos por arquitetá-lo seguindo os princípios da Programação Orientada a Objetos (POO) em Java. Isso nos permitiu dividir o jogo em classes distintas, cada uma responsável por suas funcionalidade, facilitando a manutenção e a adição de novos recursos. E para algumas implemetações utilizamos arraylist, grafos e árvore binária.
    - Documentação do código: https://github.com/St4ck-UnderFlow/projeto-java

### Componentes
Utilizamos as seguintes bibliotecas como componentes:
    - [x] Arraylist: Foi útil para armazenar uma lista dinâmica de elementos que precisava ser gerenciada de forma flexível.
    - [x] InputMismatchException: Foi útil para tratar exceções relacionadas à entrada do usuário.
    - [x] Scanner: Foi usada em jogos para facilitar a leitura das entradas do usuário.
    - [x] TreeMap: Foi utilizada para a implementação do sistema de recompensas do Mercador.

### Requisitos: 
- [x] Maxwell deve começar o jogo na cidade de Ubub.
- [x] Maxwell começa 3 com moedas de transposte, 0 de poder da jóia e 7 de limiar.
- [x] Maxwell só poderá viajar para as cidades adjacentas à atual.
- [x] Maxwell pode ganhar ou perder poder da jóia ao entrar em uma cidade
- [x] Ao entrar em uma cidade, Maxwell deve falar com o Mercador.
- [x] O Mercador deverá fazer 2 perguntas para recompensar Maxwell com moedas de transporte e limiar de poder.
- [x] Caso Maxwell tenha menos que 5 moedas de transporte e não queira trocar moeda por poder, a recompensa deverá ser ser +2 moedas de transporte
- [x] Caso Maxwell tenha menos que 5 moedas de transporte e queira trocar moeda por poder, a recompensa deverá ser -1 moeda de transporte e +2 de limiar
- [x] Caso Maxwell tenha 5 ou mais moedas de transporte e não queira trocar moeda por poder, a recompensa deverá ser -1 moeda de transporte
- [x] Caso Maxwell tenha 5 ou mais moedas de transporte e queira trocar moeda por poder, a recompensa deverá ser +2 de limiar e -1 moeda de transporte
- [x] Maxwell não poderá ficar com uma quantidade negativa de moedas de transporte após receber a recomepensa do Mercador
- [x] Quando Maxwell estiver na cidade de Defalsia, Kalb ou Vunese Empire, deverá ser ofertado missões para ele.
- [x] Maxwell poderá aceitar ou recusar as missões
- [x] Quando Maxwell aceitar uma missão, ele deverá receber a recompensa por aceita-la
- [x] Quando Maxwell completar uma missão, ele deverá receber a recompensa por conclui-la
- [x] Quando a quantidade de poder for negativo, o valor deverá ser 0 (zero).
- [x] Quando as moedas de transporte acabarem, o jogo deverá ser finalizado.
- [x] Quando a quantidade de poder for maior que o limiar de poder da jóia, o jogo deverá ser finalizado.
- [x] O limiar de poder da jóia não tem limite.
- [x] Ao chegar na cidade da missão, a mesma deve ser finalizada.
- [x] Caso Maxwell aceite ou recuse uma missão, essa missão não deverá estar disponível novamente.
