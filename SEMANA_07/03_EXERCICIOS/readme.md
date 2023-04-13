<b>
+++++++++++++++++++++++++++++++++++++++++OBRIGATÓRIOS+++++++++++++++++++++++++++++++++++++++
</b>
<BR>
<BR>
# Lista de exercícios obrigatórios - SEMANA 7

Implemente os exercícios a seguir usando um arquivo html para cada, e um único javascript para todos.

## Exercício 1 - Tabuada
Desenvolva um script que faça a tabuada de um número qualquer inteiro que será digitado pelo usuário, mas observe que a tabuada não deve necessariamente iniciar em 1 e terminar em 10.

O valor inicial e final devem ser informados também pelo usuário, conforme exemplo abaixo:

ENTRADA DE DADOS PELO FORMULÁRIO
Montar a tabuada de: 5
Começar por: 4
Terminar em: 7
SAÍDA
Tabuada do 5 começando em 4 e terminando em 7:
5 X 4 = 20
5 X 5 = 25
5 X 6 = 30
5 X 7 = 35

## Exercício 2 - Palíndromo
Um número é considerado palíndromo quando lido da esquerda para a direita ou da direita para a esquerda representa sempre o mesmo valor, como por exemplo: 434, 6446 e 82328. Sabendo-se disso construa um script que verifique se um número fornecido pelo usuário é ou não palíndromo.

## Exercício 3 - Um, dois, três, PI
Um, dois, três, PI é uma brincadeira antiga de criança, e na verdade consiste em reconhecer os múltiplos do número 3.

Sabendo-se disso, desenvolver um script gere na tela, quando o usuário escolher o limite do número 10:

1 - 2 - 3
PI
4 - 5 - 6
PI
7 - 8 - 9
PI

## Exercício 4 - Reforma
Você foi contratado(a) para fazer um pequeno script que calcule o número total de azulejos necessários para determinada parede de uma sala, pedindo-se que sejam inseridas as dimensões de cada azulejo, e a altura e largura da parede que se deseja reformar, contando com uma sobra de 5% de azulejos.
Para calcular a quantidade de azulejos necessários, é preciso ter as dimensões da área que pretende revestir. Ao resultado obtido deve sempre adicionar 5% do total para sobras, inevitáveis, como por exemplo, no corte de azulejos para acertos nas bordas ou nos cantos.

Exemplificando temos a seguinte situação real: 
Suponhamos que você pretende revestir com azulejos de 15 cm x 15 cm —- medida mais corrente no Brasil — uma parede com 4,5 m de comprimento e 3 m de altura.
Neste caso, necessitará de 30 azulejos no sentido do comprimento (450 cm = 15 cm X 30) e 20 no sentido da altura (300 cm = 15 cm X 20). Logo, o total de azulejos será:
Para revestir a superfície: 30 X 20 = 600.
Para sobras: 5% de 600 = 30.
Total de azulejos: 630 unidades

Obs: para trabalhar com arredondamentos para cima, utilize a função nativa do Javascript: Math.ceil(numero)


<BR><BR>
<b>
+++++++++++++++++++++++++++++++++++++++++OPCIONAIS+++++++++++++++++++++++++++++++++++++++
</b>
<BR><BR>

# Lista de exercícios opcionais - Semana 7

## Exercício 1
Crie uma página web na qual o usuário possa informar a quantidade de um produto em um valor inteiro e, por meio de dois botões, um que adiciona uma unidade e um que subtraia uma unidade, o valor do campo da quantidade possa ser manipulado.

## Exercício 2
Crie uma página web na qual o usuário possa digitar dois valores, cada um em uma caixa de texto. Quando o usuário indicar que deseja que os valores sejam trocados (clicando no botão "Troca"), os valores contidos nas caixas de texto são trocados, ou seja, se na primeira caixa de texto estiver escrito "IPT" e na segunda, "Inteli", quando solicitada a troca, a primeira caixa de texto deve contar "IPT" e a segunda, "Inteli".

## Exercício 3
Crie uma página web na qual o usuário deva escrever em um campo de texto o número de seu celular no formato "(XX)XXXXX-XXXX" e, caso o formato não seja respeitado, o usuário seja notificado.

## Exercício 4
Crie uma página web que permita ao usuário informar a quantidade de pessoas (número inteiro inteiro) e o período (Noturno ou Diurno) e, quando o usuário indicar que deseja que o cálculo seja realizado (pressionar um botão), mostre o total da compra de acordo com as condições abaixo:
- Se vôo diurno, 200 por pessoa. Se mais do que 50 pessoas, desconto de 40% por pessoa.
- Se vôo noturno, 100 por pessoa. Se mais do que 50 pessoas, desconto de 20% por pessoa.

## Exercício 5
Crie uma página web na qual o usuário informe a quantidade de alunos e a nota de cada aluno na prova e no trabalho. Quando o ususário finalizar o fornecimento de todas as informações e solicitar o cálculo, mostre:
- a média de cada aluno, calculada considerando peso 2 para a prova e 3 para o trabalho;
- a média geral, considerando todos os alunos;
- a média artiméticas das notas de prova;
- a média artiméticas das notas de trabalho;
- a menor e a maior notas de prova;
- a menor e a maior notas de trabalho.
Obs: note que a quantidade de campos para inserção das notas de cada aluno depende da quantidade de alunos informada.
