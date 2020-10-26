# CTC-17-laboratório-1
Desenvolvimento de agentes inteligentes da matéria de Inteligência Artificial do curso de Engenharia de Computação do ITA-2020, ministrada pelo professor Paulo André Lima de Castro

- q1: Encontre o menor caminho entre as cidades Alice Springs e Yulara da Australia (arquivo australia.csv), especificando a lista das cidades e também a distância do início ao fim. O arquivo tem os seguintes campos: ID da cidade, coordenada x, coordenada y, estado e população. A distância em linha reta entre as cidades pode ser calculada a partir das coordenadas cartesianas (x,y) disponibilizadas no arquivo Australia.csv. Uma cidade com ID X se conecta com as cidades X+2 e X-1, se X>1 e X é par. Se X é ímpar e X>2, esta cidade X se conecta com as cidades X-2 e X+1. Neste caso a distância pela estrada é 10% maior que a distância em linha reta.

- q2: Light up: Crie um agente capaz de resolver o jogo chamado [Akari](https://www.chiark.greenend.org.uk/~sgtatham/puzzles/js/lightup.html). O jogo é composto de um tabuleiro (7x7). Algumas casas são pretas, algumas das casas pretas tem números. O objetivo é ‘iluminar’ todas células brancas, colocando lâmpadas nelas. Cada lâmpada ilumina sua casa, mas a linha e coluna onde está posicionada, a menos que uma casa preta bloqueie o caminho. Para solucionar o jogo, você deve satisfazer as seguintes condições: 

    Todas as casas não pretas, estão iluminadas
  
    Nenhuma lâmpada é iluminada por outra lâmpada
  
    Todas as casas numeradas tem exatamente o número indicado de lâmpadas adjacentes (as casas acima, abaixo, à esquerda e à direita) 
    
    Casas pretas não-numeradas podem ter qualquer número de lâmpadas adjacentes
    
    <img width="430" alt="Screenshot_1" src="https://user-images.githubusercontent.com/42987302/97128751-e8124780-171b-11eb-9698-7516d93d9ea7.png">
