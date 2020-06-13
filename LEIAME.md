Arduino Plotter

Primeiramente eu quero me apresentar com o professor de Ensino Médio que gosta de usar a tecnologia em minhas aulas, ensinando um pouco de programção e robótica.
Meu Projeto Final do CS50 tem por objetico aplicar os conhecimentos obticos, criando um Programa com interface gráfica para controlar um Arduino e esse a um Plotter.
O plotter era sozinho um outro projeto que eu já tinha. Ele foi construído com sucata de informática.

Para ficar mais claro, vou colocar em três itens:

1- Construir uma máquina, chamada Plotter, com peças de sucada de computadores.
2- Usar um Arduino como interface para controlar o plotter.
3- Criar um programa que leia arquivos PLT e execute comandos no Arduino, então imprimindo o arquivo.

Sobre o programa:
 
O programa do software foi criado usnado Microsoft Visual Code, Visual C#.
Ele lê arquivos do tipo PLT (Arquivos de desenho de base vetorial criados por AutoCAD; podem ser impressor usando um plotter, que imprime imagens usando linhas em vez de pontos; baseado no formato .HPGL). Os arquivos contêm as coordenadas X e Y do desenho.
As coordenadas são obtidas e enviadas para o Arduino.
O Arduino interpreta as coordenadas X Y e move os motores de passo para um ponto específico.
O eixo Z corresponde a uma caneta. Quando Z tem um valor a caneta baixa ou levanta, desenhando pontos e linhas.
O programa foi primeiramente desenvolvido por eziosoft, que me propiciou os primeiros passos para eu finalizar o projeto. Também recebi ajuda de André Breier para corrigir o código fonte.
Existem alguns erros no programa ainda, entretanto as funções básicas estão completas.



