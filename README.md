# lippegames.github.io

A pagina que recebe o link de desafio do **Milim**, o jogo de descobrir
palavras.

Quando alguem termina uma partida e manda o resultado para um amigo, vai
junto um link assim:

    https://lippegames.github.io/milim/?d=XFTRQ

Quem tem o jogo instalado cai direto nele, ja dentro do desafio. Quem nao
tem ve a pagina, com o codigo para colar no jogo depois.

O `.well-known/assetlinks.json` e a prova que o Android exige para abrir o
aplicativo em vez do navegador. A impressao digital que esta ali e do
certificado que assina o APK - informacao publica, que vai dentro de todo
aplicativo Android.

O codigo do jogo em si nao mora aqui.
