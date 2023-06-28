# Relatório Final - P2 Estrutura de Dados

## Resumo
Nosso desafio era criar um jogo sobre um viajante, chamado Maxwell, que tem o objetivo de chegar a uma cidade chamada Nargumun, nossa meta durante a criação do jogo era proporcionar a sensação de liberdade ao jogar com o personagem Maxwell, podendo se movimentar livremente pelo mapa enquanto se respeita as regras estabelecidas previamente. Enfrentando diversos obstáculos durante a codificação, com isso, tivemos que pesquisar e pedir ajuda para pessoas com mais experiência, além de trabalhar em equipe para tentar superar as adversidades, melhorando nosso conhecimento de código e nossa capacidade de trabalhar em equipe.

---

## Introdução
O projeto foi proposto pelo professor Dimmy Magalhães, durante a disciplina de Estrutura de Dados. Os alunos foram desafiados a desenvolver um jogo sobre um viajante que deveria transportar uma jóia do poder. O projeto deveria ser feito em grupo e utilizar a linguagem Java para a sua implementação. O principal objetivo desse trabalho é entender, de maneira prática, os conceitos abordados em sala, tais como: árvores, arrays e grafos. Bem como, aprimorar nosso trabalho em equipe, organização e resolução de problemas.

---

## Descrição do Projeto 

### Arquitetura 
Para garantir uma implementação modular, reutilizável e organizada do jogo, optamos por arquitetá-lo seguindo os princípios da Programação Orientada a Objetos (POO) em Java. Isso nos permitiu dividir o jogo em classes distintas, cada uma responsável por suas funcionalidade, facilitando a manutenção e a adição de novos recursos. E para algumas implemetações utilizamos arraylist, grafos e árvore binária
- *Documentação do código*: https://github.com/St4ck-UnderFlow/projeto-java

### Componentes
Utilizamos as seguintes bibliotecas como componentes:
- [x] *Arraylist*: Foi útil para armazenar uma lista dinâmica de elementos que precisavam ser gerenciadas de forma flexível.
- [x] *InputMismatchException*: Foi útil para tratar exceções relacionadas à entrada do usuário.
- [x] *Scanner*: Foi usada no jogo para facilitar a leitura das entradas do usuário.
- [x] *TreeMap*: Foi utilizada para a implementação do sistema de recompensas do Mercador.

### Requisitos 
- [x] Maxwell deve começar o jogo na cidade de Ubub.
- [x] Maxwell começa com 3 moedas de transposte, 0 de poder da jóia e 7 de limiar.
- [x] Maxwell só poderá viajar para as cidades adjacentas à atual.
- [x] Maxwell pode ganhar ou perder poder da jóia ao entrar em uma cidade
- [x] Ao entrar em uma cidade, Maxwell deve falar com o Mercador.
- [x] O Mercador deverá fazer 2 perguntas para Maxwell.
- [x] Caso Maxwell tenha menos que 5 moedas de transporte e não queira trocar moeda por poder, a recompensa deverá ser ser +2 moedas de transporte
- [x] Caso Maxwell tenha menos que 5 moedas de transporte e queira trocar moeda por poder, a recompensa deverá ser -1 moeda de transporte e +2 de limiar
- [x] Caso Maxwell tenha 5 ou mais moedas de transporte e não queira trocar moeda por poder, a recompensa deverá ser -1 moeda de transporte
- [x] Caso Maxwell tenha 5 ou mais moedas de transporte e queira trocar moeda por poder, a recompensa deverá ser +2 de limiar e -1 moeda de transporte
- [x] Maxwell não poderá ficar com uma quantidade negativa de moedas de transporte após receber a recompensa do Mercador
- [x] Quando Maxwell estiver na cidade de Defalsia, Kalb ou Vunese Empire, deverá ser ofertado missões para ele.
- [x] Maxwell poderá aceitar ou recusar as missões
- [x] Quando Maxwell aceitar uma missão, ele deverá receber a recompensa por aceita-la
- [x] Quando Maxwell completar uma missão, ele deverá receber a recompensa por conclui-la
- [x] Quando a quantidade de poder for negativo, o valor deverá ser 0 (zero).
- [x] Quando as moedas de transporte acabarem, o jogo deverá ser finalizado.
- [x] Quando a quantidade de poder for maior que o limiar de poder da jóia, o jogo deverá ser finalizado.
- [x] O limiar de poder da jóia não tem limite de crescimento.
- [x] Ao chegar na cidade da missão, a mesma deve ser finalizada.
- [x] Caso Maxwell aceite ou recuse uma missão, essa missão não deverá estar disponível novamente.


### Funcionalidades
- [x] Iniciar o jogo
- [x] Ver as regras do jogo
- [x] Viajar entre as cidades
- [x] Interagir com o Mercador
- [x] Aceitar, recusar e abandonar missão
- [x] Aumentar ou diminuir o limiar e poder da jóia
- [x] Aumentar ou diminuir a quantidade de moedas de tranporte 

---

## Descrição da Equipe
- **[Luis Henrique](https://github.com/LuisHenriqueCO)**: O Luis tem a função de testar o código para verificar se o código necessita de alguma revisão ou se tem algo que está acontecendo ou deixando de fazer, que não era suposto para acontecer, é função do Luis de achar e relatar para ser solucionado, além de requisitar a implementação do requisitos gerados pelo Miguel no código, colocar os documentos no Git e contribuir com o relatório.
- **[Miguel Ferro](https://github.com/0rffe0)**: O Miguel tem a função de criação de documentos que melhorem a organização do projeto, criação de documentos que não são ligados diretamente ao código como contribuir com o relatório, criação de requisitos, analise do projeto para que não fuja da ideia principal e das regras que devem ser seguidas e implementar os documentos no Git.
- **[Vinicius D' Fatima](https://github.com/viniciusbarbosa1344)**: O Vinicius é responsável pela criação do código, correção dos erros relatados pelo Luis, filtração de ideias que não são viáveis de implementar no código, designar os trabalhos que precisam ser feitos pelo Trello e implementar documentos do projeto no Git.
- **[Arthur Mousinho](https://github.com/arthurmousinho)**: O Arthur é responsável pela criação do código, correção dos erros relatados pelo Luis, designar os trabalhos que precisam ser feitos utilizando o Trello para que o grupo saiba o que é necessario e implementar documentos do projeto no Git.
- **[Samael Aun](https://github.com/orgs/St4ck-UnderFlow/people/Spit19)**: O Samael auxiliou na criação do relatório.

---

## Metodologia 
Para uma melhor organização e otimização do tempo, decidimos dividir o grupo em 4 equipes:
- [x] *Programadores*: Responsáveis pela implementação do código bruto e interface do jogo.
- [x] *Equipe de Testes*: Responsáveis pela análise do código implementado, conferindo sua fidelidade com os requisitos do projeto.
- [x] *Equipe de Levantamento de Requisitos*: Responsáveis por filtrar os requisitos fornecidos e repassar para as demais equipes.
- [x] *Relatório*: Equipe na qual todas as outras se reunem, em conjunto, para realizar o Relatório Final do projeto.

No decorrer do projeto utilizamos diversas plataformas para ajudar em seu desenvolvimento:
- [x] *Trello*: Empregado como uma ferramenta de gerenciamento de projetos. Permitindo a criação de quadros com listas de tarefas, onde cada equipe podia adicionar cartões representando as atividades a serem realizadas e as que já foram concluídas. Proporcionando uma visão geral do progresso do projeto, além de facilitar o acompanhamento das tarefas concluídas, em andamento e pendentes.
- [x] *GitHub*: Ferramenta de hospedagem de código. Proporcionou o compartilhamento e a colaboração entre os desenvolvedores, oferecendo recursos como o controle de problemas, onde bugs e melhorias podem ser reportados e rastreados, além de facilitar a revisão de código. Esses recursos foram essenciais para facilitar a revisão de qualidade do código.
- [x] *Git*: Ferramenta de controle de versão e colaboração no desenvolvimento do código-fonte. Permitiu que cada desenvolvedor trabalhasse em sua própria cópia do projeto, realizando mudanças e compartilhando com os outros membros, além de possibilitar um desenvolvimento paralelo sem conflitos, por meio do acompanhamento das alterações realizadas e a possibilidade de reverter para versões anteriores, caso necessário.

- [x] *Draw.io*: Ferramenta de criação de diagramas e fluxogramas. No projeto, a equipe o utilizou para gerar a modelagem do mapa mais simplificado do jogo. Através disso, a equipe pôde ter uma compreensão clara da estrutura e do fluxo do jogo, facilitando o planejamento e a tomada de decisões durante o desenvolvimento do mesmo.

---

## Descrição das Estruturas de Dados 
- [x] *Arraylist*: Durante o progresso de codificação do jogo, foi utilizado a Arraylist de diversas formas, como: 
    - Usado na funcionalidade de validar opção do usuário.
    - Usado no armazenamento das fronteiras na hora de se locomover pelo mapa.
- [x] *Árvore*: O tipo de árvore que foi decidido utilizar no projeto foi árvore binária, ela foi implementada na criação do sistema de recompensas do Mercador, para possibilitar:
    - Possibilitar processar as recompensas de acordo com as respostas dadas pelo jogador
- [x] *Grafo*: Foi utilizado esse tipo especial de árvore na criação do mapa das cidades do jogo, no qual cada cidade está conectada a outra por meio de uma "fronteira", composta pela cidade de destino e o poder a ser ganho quando chegar nessa cidade.

---

## Resultados 
- [x] O programa não apresenta delay em sua execução, com resposta instantânea aos comandos executados 
- [x] O programa depois de uma série de testes não apresenta erros de execução
- [x] O programa respeita os requisitos do jogo
- [x] Os membros apresentaram uma melhora nas partes de programação e raciocínio lógico, bem como na resolução de problemas e trabalho em equipe
- [x] Houve uma melhoria na organização da equipe, por meio da atribuição e resolução de tarefas na plataforma Trello 

---

## Conclusão
Em suma, o presente relatório apresentou os resultados e as conclusões alcançadas durante o desenvolvimento de um projeto em grupo, para a implementação do jogo em Java. Ao longo desse processo, nossa equipe enfrentou desafios significativos, que foram superados por meio da colaboração e aplicação de conhecimentos adquiridos ao longo da disciplina de Estrutura de Dados, ministrada pelo Professor Dimmy Magalhães. O jogo final produzido é um reflexo do nosso comprometimento, criatividade e capacidade de solucionar problemas. Através dessa experiência, fortalecemos nossas habilidades em Programação Orientada a Objetos (POO), conceitos de Estrutura de Dados, levantamento de requisitos, modelagem de software e trabalho em equipe. Além disso, adquirimos um entendimento mais profundo dos princípios de desenvolvimento de jogos e da importância da usabilidade e da experiência do usuário. Embora o projeto possa ter sido concluído, reconhecemos que há sempre espaço para melhorias e aprimoramentos futuros. Como equipe, estamos orgulhosos do que realizamos e confiantes de que os conhecimentos e as lições aprendidas serão valiosos em nossas carreiras como Engenheiros de Software.

## Referências

>Entendimento aprofundado de conceitos de Estrutura de Dados
>
> *Professor Dimmy Magalhães (Coordenador do Curso de Engenharia de Software do iCEV)*
>
> *Algoritmos - Teoria e Prática (Thomas Cormen)*


>Solução de duvidas e inseguranças a respeito de Grafos e Árvores
>
>*Tutor Samuel Vinícius*

>Documentações das aulas da faculdade 
>
>*Plataforma iCEV Digital*

>Visualização de exemplos práticos em Java 
>
>*Vídeo Aulas do YouTube / Sites Auxiliares*

>Entendimento da lógica da biblioteca TreeMap do Java
>
>*ChatGPT*
