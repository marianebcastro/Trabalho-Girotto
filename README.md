JOGOS

Pergunta e Resposta
if(opcao == 1): quando o jogador digitar o número 1, ele será direcionado para o primeiro jogo.
char resposta: declaração da variável resposta, o char indica que a resposta será representada por um caractere, que no caso seria, a, b, c ou d, as alternativas.
printf(“”): o printf sempre indicará a mensagem que aparecerá na tela para o usuário, no jogo 1, foi utilizado para indicar ao jogador qual jogo ele escolheu do menu, mostrar as perguntas, as alternativas, e para informar ao jogador se ele acertou ou não a resposta, no caso de não ter acertado, utilizamos o printf também para exibir na tela a alternativa correta.  
scanf(“ %c”): utilizado para armazenar a alternativa que o jogador escolher, a variável “%c” foi utilizada por estarmos lidando com variáveis de caracteres.
if else: utilizamos essa estrutura para que o computador identifique se a resposta do jogador está certa ou errada, se certa, exibirá uma mensagem, se errada, exibirá outra mensagem com a alternativa correta.
while: essa estrutura foi utilizada juntamente com a variável “r1”, para criar um laço caso o jogador quisesse jogar novamente ou voltar ao menu, também foi utilizada para impedir opções além dessas duas. Também foi utilizada para impedir que o jogador escolha alternativas inválidas como resposta para as perguntas.

Cobra na Caixa!
if(opcao == 2): quando o jogador digitar o número 2, ele será direcionado para o segundo jogo.
int: declaração das variáveis do personagem do jogador 1, do jogador 2, e da caixa, utilizamos o int porque em todas as escolhas, as alternativas serão representadas por números inteiros.
printf(“”): o printf sempre indicará a mensagem que aparecerá na tela para o usuário, no jogo 2, foi utilizado para exibir a história do jogo, os nomes dos personagens disponíveis, as opções das caixas, se a opção que os usuários escolheram, tanto da caixa quanto do personagem é válida, para os jogadores tentarem novamente caso a caixa que tenham escolhido não continha nem o botão nem a cobra, e se os jogadores ganharam ou perderam.  
scanf(“%d): utilizado para armazenar a alternativa que o jogador escolher, no caso do jogo 2, foi utilizada para armazenar os personagens, as caixas escolhidas e a resposta dos jogadores ao final do jogo, se desejam jogar novamente ou voltar ao menu.
if else: utilizamos essa estrutura para que o computador identifique se na caixa escolhida pelos jogadores havia a cobra, o botão, ou se estava vazia.
while: essa estrutura foi utilizada juntamente com a variável “r2”, para criar um laço caso o jogador quisesse jogar novamente ou voltar ao menu, também foi utilizada para impedir opções além dessas duas. Além disso, foi utilizada para impedir escolhas de caixas inválidas e para impedir que o botão e a cobra acabassem na mesma caixa.
rand: essa função foi utilizada para que o computador embaralhasse aleatoriamente a cobra e o botão nas caixas.

Gousmas War
if(opcao == 3): Quando o usuário digitar no menu a opção número 3 ele automaticamente será redirecionados para o jogo Gousmas War
Comando int: nessa parte será declarado cada variável para operar o jogo dentre elas quantas gousmas cada jogador tem, o nível de fúria de cada e por fim uma variável de ataque e outra para duplicar as gousmas.
while(gousmas1 > 0 && gousmas2 > 0): que diz que enquanto as gousmas dos jogadores forem maior que zero o jogo irá continuar, se pelo menos uma delas for menor que 0 o laço de repetição se quebra
if(gousmas1 == 1) e if(gousmas2 == 1): nesses dois comandos o código verifica que se o jogador tem duas gousmas ou só uma, caso ele tenha só uma o código lhe dá a oportunidade de duplicar sua gousma clicando no número um, e caso não queira apenas clicar no número dois
if(gousmas1 == 2 && gousmas2 == 2): são uma sequência de comandos if’s que servem para atualizar a parte gráfica do jogo verificando a quantidade de gousmas de cada jogador, exemplo, se o jogador 1 tiver apenas uma gousma o printf dentro do comando if irá mostrar apenas uma gousma na parte gráfica
while(atack != 1 && atack != 2): comando que serve para limitar o ataque do jogador apenas aos comandos 1 e 2, sendo um para atacar a gousma da esquerda e o 2 para atacar a gousma da direita do oponente.
scanf("%d", &atack): para o usuário inserir a gousma a ser atacada
while(atack == 1 && nf3 == 6): esse comando novamente serve para limitar o ataque do jogador, caso o nível de fúria de uma gousma seja igual a 6 e o oponente tente atacar aquela gousma de novo o comando irá barrar o ataque pois essa gousma não existe mais no gráfico
if(atack == 1) e if(atack == 2): esses comandos servem para criar uma diferença nos ataques, caso o usuário digite 1 ele irá atacar a gousma da esquerda e o 2 a gousma da direita
scanf("%d", &r3): comando que serve para o usuário dizer se deseja continuar no jogo ou retornar ao menu, caso digite 1 ele reinicia o jogo e caso digite 0 ele retorna ao menu.

Seleção do usuário:
while(opcao != 1 && opcao != 2 && opcao != 3 && opcao != 4): nesse comando feito no inicio do jogo serve para limitar as escolhas do usuario entre 1, 2, 3 e 4, pois enquanto ele escolher um valor diferente desses, código irá cobrar do usuário um comando válido
while(opcao != 4): após isso o código entra em outra repetição, que enquanto o valor for diferente de 4 os jogos irão continuar, caso seja 4 os jogos encerram
int r1, r2, r3: serão usados mais para frente do código para o jogador ditar de deseja reiniciar o jogo ou voltar ao menu, sendo 1 para reiniciar e 0 para retornar ao menu.

