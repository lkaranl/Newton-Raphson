# Método de Newton–Raphson

Em análise numérica, o método de Newton (ou Método de Newton–Raphson), desenvolvido por Isaac Newton e Joseph Raphson, tem o objetivo de estimar as raízes de uma função. Para isso, escolhe-se uma aproximação inicial para esta. Após isso, calcula-se a equação da reta tangente (por meio da derivada) da função nesse ponto e a interseção dela com o eixo das abcissas, a fim de encontrar uma melhor aproximação para a raiz. Repetindo-se o processo, cria-se um método iterativo para encontrarmos a raiz da função. Em notação matemática, o método de Newton é dado pela seguinte sequência recursiva: 

<p align="left">
  <img src="https://github.com/lkaranl/Newton-Raphson/raw/master/img/newton.png">
</p>

onde *x0* é uma aproximação inicial dada, *n* indica a *n*-ésima iteração do algoritmo e *f′(xn)* é a derivada da função *f* no ponto *xn*.

## Dependências

Para utilizar o código você precisa da linguagem de programação Python na versão 3.6 ou superior, além da biblioteca Sympy, que auxilia na função derivada.
* [Python](https://www.python.org/)
* [Sympy](https://www.sympy.org/pt/index.html)

*Obs: Vale lembrar que o código foi escrito em uma máquina utilizando GNU/Linux como sistema operacional. Então pode ocorrer erros de sintaxe se usado em sistemas operacionais Microsoft Windows e MacOS da Apple, porém eu não testei, então vai na fé.

## Como usar
basta baixar o projeto clicando [aqui](https://github.com/lkaranl/Newton-Raphson/archive/master.zip) e descompactar onde desejar, em seguida execute o arquivo main.py com o python3

`$ python3 main.py`

O programa é bem intuitivo após essa etapa, bastando colocar a função desejada de acordo com a sintaxe exijida.


## Modo Online
Use este [SITE](https://repl.it/languages/python3), ele é um simulador online para o Python. E eu também fiz um vídeo bem curto de como
pode estar fazendo todo o processo -> [TUTORIAL](https://drive.google.com/file/d/1Fx9EZkGM3Fy21IA1COk66rEvkrFS2RBl/view)
