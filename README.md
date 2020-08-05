# Método de Newton–Raphson

Em análise numérica, o método de Newton (ou Método de Newton–Raphson), desenvolvido por Isaac Newton e Joseph Raphson, tem o objetivo de estimar as raízes de uma função. Para isso, escolhe-se uma aproximação inicial para esta. Após isso, calcula-se a equação da reta tangente (por meio da derivada) da função nesse ponto e a interseção dela com o eixo das abcissas, a fim de encontrar uma melhor aproximação para a raiz. Repetindo-se o processo, cria-se um método iterativo para encontrarmos a raiz da função. Em notação matemática, o método de Newton é dado pela seguinte sequência recursiva: 

<p align="left">
  <img src="https://github.com/lkaranl/Newton-Raphson/raw/master/img/newton.png">
</p>

onde *x0* é uma aproximação inicial dada, *n* indica a *n*-ésima iteração do algoritmo e *f′(xn)* é a derivada da função *f* no ponto *xn*.
