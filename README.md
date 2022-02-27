**UNIVERSIDADE LUSÓFONA DE HUMANIDADES E TECNOLOGIAS**

*Linguagens de Programação I *

# Exercício 0

Este exercício serve três objectivos principais:
- Familiarização com a ferramenta pandora
- Criar um programa simples em linguagem C
- Praticar o desenvolvimento e teste de programas em linuguagem C.

Na resolução destes exercícios deve ser utilizada a Linguagem de Programação C. Para além da correta implementação dos requisitos, tenha em conta os seguintes aspetos:
- O código apresentado deve ser bem indentado. 
- O código deve compilar sem erros ou *warnings* utilizando o *gcc* com as seguintes flags:
- `-g -Wvla -Wall -Wpedantic -Wno-unused-result -Wdeclaration-after-statement`
- Tenha em atenção os nomes dados das variáveis, para que sejam indicadores daquilo que as mesmas vão conter.

## Pandora

1. Em primeiro lugar deverá ter uma conta no github (https://github.com/). Se criar uma conta nova no github é conveniente usar o seu email institucional e colocar o seu nome e número mecanográfico como nome de utilizador. Exemplo ```anasilva21908445```.
2.	Aceda à plataforma PANDORA (https://saturn.ulusofona.pt/) e pressine o botão que diz **Sign In with Git-Hub**.
    *Nota. O acesso ao Pandora é feito com as credenciais do github. Isso significa que o Pandora não guarda passwords. A única informação que é passada ao Pandora é o vosso nome de utilizador.*
**Se perder a password, deve recuperar a password utilizando o mecanismo disponibilizado pelo github. NUNCA DEVERÁ CRIAR UMA CONTA NOVA.**
**Se criar uma conta nova irá perder todas as avaliações feitas pelo pandora.**

3.	Após login no PANDORA, clickar em Contests, e depois completar a informação colocando o número e o nome completo. É extremamente importante que coloque o número correcto na plataforma.

4.	Nesta fase deverá contactar o seu professor das práticas para que a sua conta seja activada. Para isso deverá enviar um email informando de que já completou o seu registo na plataforma. Deverá indicar o seu número de aluno para que seja verificado.

5. Espere algum tempo (até 24h) para que a conta seja activada. Só depois disso poderá começar a submeter.

## Exercício

Crie um programa que pede um angulo `alpha` (em graus) ao utilizador e em seguida calcula o resultado da função trigonométrica `sen(alpha)` utilizando a fórmula da expansão em série de Taylor de terceira ordem. I.e.:
<img src="https://render.githubusercontent.com/render/math?math=sin(x) \approx x - \frac{x^3}{3!} + \frac{x^5}{5!}">

Note que, na fórmula, `x` está em radianos, pelo que primeiro deverá converter de graus para radianos. Para isso definir uma constante com o valor de `PI=3.14159`. Resolva o problema sem utilizar a biblioteca math.h. 

