---
layout: post
title: Desenvolvimento & Resultados
description: >
  As fases do jogo foram estruturadas explorando o conceito de rede de transitores
  e chaves que podem assumir valores entre 0 e 1. Baseado na tecnologia CMOS que é
  complementar, o plano da rede é divido entre plano inferior (PD: pull-down) e 
  plano superior (PU: pull-up) divido por uma saída (out). Por ser complementar, o que é
  implementado no plano inferior é invertido no plano superior, dependendo do valor 
  que as chaves assumirem (letras ou literais) isso indica se está ocorrendo a condução
  de corrente ou não, PU conduz em 0 e PD conduz em 1. Estar conduzindo corrente ou não
  implica em ter um caminho lógico 'liberado' por essa chave ou não, o jogador
  tem como objetivo para solucionar a fase, simular o caminho lógico que é liberado
  conforme valores que são atribuídos aos literais que variam conforme o tamanho
  da rede, ou seja, número de chaves.
image: /assets/img/blog/desenv2.png
sitemap: false
---
_Rede de Transistores Gamificada_  
>Então, as fases foram estruturadas e o método de interação escolhido foram **alavancas**, 
>essas iriam permitir a criação de um **quebra-cabeças**, onde os valores para cada literal
>poderia ser atribuído variando entre 0 e 1 e consequentemente liberando o caminho da
>corrente para que assim o jogador pudesse reproduzir e coletar itens **moedas** em 
>posições diferentes. Coletar todas as moedas implica em **concluir a fase** com sucesso.

## Esquemático Fase & Objetivos:
<figure>
  <img src="\assets\img\blog\desenv1.png" alt="Imagem Pequena" width="500" height="500">
  <figcaption>"Esquemático de Fase & Objetivos"</figcaption>
</figure>


## Fase Vs Rede de Transistores:
<figure>
  <img src="\assets\img\blog\bgodisseia.png" alt="Imagem Pequena" width="500" height="500">
  <figcaption>"Comparação Esquemático Vs Primeira Fase Implementada em Unity"</figcaption>
</figure>


> A função Booleana implementada determina a organização da rede de transistores, portanto 
> a dificuldade da fase depende da complexidade da função implementada. O intuito é apresentar
> ao jogador uma série de fases que deverão ser solucionadas para que a quest principal do 
> jogo seja completada. Dessa forma, o enredo do jogo irá se mostrando ao longo dessas fases
> e a conclusão delas levará o jogador ao final do enredo e enfretamento do **Final Boss**.


## Tela de Menu:
<figure>
  <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExd2pqcnJia2YwZmkzemd6bHZhOWFmZm96cDRpaHUwcWptMWsxNDRsaCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/9ADOWb7zpyEkietDF5/giphy.gif" alt="Imagem Pequena" width="500" height="500">
  <figcaption>"Tela de Menu Implementada em Unity"</figcaption>
</figure>



*   **Cores:** as bases escolhidas para o jogo variam entre rosa (claro), azul (claro) e branco.
*   **Visual:** as referências visuais sempre são associadas a eletricidade com elementos RPG.
*   **Som:** a tela do menu possui trilha sonora e os efeitos interativos com os botões da interface
são efeitos sonoros deelétricos.
*   **OBS:** A tela do menu tem como plano de fundo o mundo humano, os raios fazem referência ao oculto 
que é o mundo de Odisseia.
