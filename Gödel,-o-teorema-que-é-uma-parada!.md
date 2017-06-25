Gödel, o teorema que é uma parada!

**Luís Carlos Silva Eiras**

O matemático Raymond Smullyan fez uma proeza: colocou o teorema de Gödel com suas 46 definições preliminares, 34 páginas  e dezenas de símbolos e fórmulas em apenas meia página.

O teorema de Gödel é complicado. Muitos livros tentam explicá-lo desde clássicos da lógica como **Gödel, Escher, Bach**, de Douglas R. Hofstadter, e **O Advento do Algoritmo**, de David Berlinski, passando por livros exclusivos como **Prova de Gödel**, de Nagel e Newman, e **Incompletude**, de Rebecca Goldstein, pelo romance **Um Louco Sonha a Máquina Universal**, de Janna Levin, além do gibi **Logicomix**, de Apostolos Doxiadis, e do documentário da BBC4, **Conhecimento Perigoso**, de David Malone. Todos, apesar de realçar a importância do teorema para o conhecimento humano, fracassam em explicá-lo para os leigos.

Por isso, intelectuais como Julia Kristeva, Jean-François Lyotard, Gilles Deleuze, Félix Guattari, Régis Debray, Paul Virilio e Michel Serres o citam sem pé nem cabeça ao retirá-lo da matemática e da lógica e aplicá-lo por ignorância pernóstica nas ciências sociais. O humor gerado é involuntário, ainda que de difícil localização, já que o humor involuntário está presente em tudo que escrevem.

Em 1930, Gödel fez uma palestra em Viena. Esperava-se que ele tivesse resolvido o problema dos paradoxos, a parte mais desagradável – para quem quer conhecimento sem contradições – ou a mais divertida da lógica. O mais antigo desses paradoxos é o do cretense5  que teria dito: “_Todo cretense é mentiroso_”. Ou ele estava mentindo, portanto, estava falando a verdade; ou ele estava falando a verdade, portanto, estava mentindo.

A palestra de Gödel foi um espanto. Ele não tinha resolvido a questão dos paradoxos, pelo contrário, demonstrou que a coisa era muito pior. No ano seguinte, publicou _Sobre as Proposições Indecidíveis dos **Principia Mathematica**  e Sistemas Correlatos_, onde está o teorema.

Para torná-lo tão simples, Raymond Smullyan usou um truque de ficção científica: uma máquina de 1936 para explicar o teorema de 1931. Imagina-se  um computador composto de teclado, onde se pode escrever qualquer coisa, um processador capaz de processar o que vem do teclado desde que consistente, e uma tela dividida em duas partes: de um lado, o que foi digitado; do outro, o resultado do processamento. Enfim, um sistema de informação absolutamente banal.
É criado, então, um sistema lógico, uma linguagem, com apenas três comandos: I (de _imprima_), N (de _não_) e R (de _repita_), que será colocado à prova. E o _X_, que será utilizado como dado inicial do teste.

| No teclado | Na tela (Comando)|(Processamento)|
| --- | --- | --- |
|IX ( _imprima X_ ) |(1) IX | X|
|NIX ( _não imprima X_ ) |(2) NIX | - |
|RIX ( _repita imprima X_ ) |(3) RIX | XX |
|NRIX ( _não repita imprima X_ ) |(4) NRIX | - |

Nessas linhas (2) e (4), o computador poderá imprimir qualquer coisa, desde que não seja X e XX, respectivamente. E, em seguida, continuando o teste, cada X pode ser substituído por outros dados, como _casa, Gödel, artigo, GitHub_. Tudo funciona às mil maravilhas e não poderia ser diferente em algo tão simples. 

Então, como teste final, o _X_ é substituído pelos três comandos do sistema lógico, o NRI (_não repita imprima_):

| No teclado | Na tela (Comando)|(Processamento)|
| --- | --- | --- |
|INRI ( _imprima NRI_ ) |(5) INRI | NRI|
|NINRI ( _não imprima NRI_ ) |(6) NINRI | - |
|RINRI ( _repita imprima NRI_ ) |(7) RINRI | Opa! |
|NRINRI ( _não repita imprima NRI_ ) |(8) Opa! | ??? |

Opa! O comando (7) RINRI não pode ser demonstrado, pois se está mandando fazer o que não pode ser feito: _repita imprima não repita imprima_. Isso é uma variação do paradoxo do cretense, conhecido desde os gregos.

Mas o pior – eis a grande contribuição de Gödel – é o comando (8) NRINRI (_não repita imprima não repita imprima_): se o computador mostrar qualquer processamento na tela, então, o comando é falso.  Se não mostrar, o comando é verdadeiro, mas não pode ser visto. Gödel concluiu que nenhum sistema lógico possui consistência interna. Assim, existem comandos e resultados verdadeiros que não podem ser demonstrados. E muitos nem conhecidos.

A partir do teorema de Gödel, Alan Turing propôs, em 1936, uma máquina que, deixando os paradoxos de lado, fosse capaz de resolver qualquer problema que pudesse ser resolvido, inclusive, substituindo o computador, isto é, o funcionário das grandes empresas que trabalhava na contabilidade.

Mas, para os programadores, Turing lembrava da “maldição da parada”. Quando um programa demora para ser processado, nunca se saberá de antemão se é devido à complexidade do problema, à lerdeza do processador, a alguma falha de produção ou aos paradoxos de Gödel – o cachorro correndo atrás do rabo, o  comando NRINRI acima – espalhados no meio do caminho.

**Referências:**

Kurt Gödel, **Obras completas**, Alianza Universidad, 1981, págs. 55-89.

_http://blog.plover.com/math/Gdl-Smullyan.html_  [Acesso em: 25 junho 2017]

Alan Sokal  e Jean Bricmont, **Imposturas Intelectuais, O abuso da ciência pelos filósofos pós-modernos**,  Record, 1999.
