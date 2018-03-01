<!-- TITLE: Informação geral em jogos de Luta -->

# Termos gerais de jogo de luta 2D
## Normals, Specials, Supers, Command Normals, Grab, Command Grab e EX Specials
* **Normals** são os ataques básicos do personagem, como 5L que normalmente é um soco simples;
* **Specials** são os golpes únicos de cada personagem feito ao dar um comando especifico (exemplo popular: apertando 236 + soco para dar Hadouken), normalmente consegue ser combinado depois de algum Normal para dar mais dano (o famoso combo);
* **Super** é o "golpe secreto" do personagem. É normalmente executado ao fazer um comando mais complexo que um Special (no caso de Street Fighter, seria 236236 + soco, mas também pode ser relativamente simples que nem no Dragon Ball Fighter Z que é somente 236 + dois botões de ataque). Normalmente possui uma barra dedicada que só possibilita o Super ser executado caso ela esteja cheia;
* **Command Normals** são ataque simples normalmente específicos de cada personagem, como *6 + soco* para dar golpe Overhead;
* **Grab** é o agarrão. Dependendo do jogo pode ser combinação de dois botões ou apenas apertando 6 + botão forte para agarrar o oponente. Ferramente extremamanete útil contra algum oponente que está defendendo tudo que você faz, e normalmente defendível ao aperta os botões de Grab ao quase mesmo tempo que a pessoa que tentou dar ou pulando fora do alcance do grab caso esse só pegue em oponente que esteja no chão. Defender o agarrão dando o input de agarrão é chamando de Tech;
* **Command Grab** é a versão "Special" do Grab normal, que é feito somente quando vc faz algum comando especifico. Diferente do Grab normal, esse tipo de grab só dá para escapar pulando para fora do alcance. Mas cuidado porque há personagens que tem Command Grabs que só pegam em oponentes no chão ou só em oponentes no ar.
* **EX Specials** são uma versão mais forte dos Specials. Normalmente custando parte da barra de Super como efeito, e tão efetivo quanto usar um Super caso você esteja em dia com os combos do seu personagem.


## High, Low, Overhead e OTG
High e Low são referentes à altura dos golpes: 
* Golpes **High** acertam personagens em pé e na maioria das vezes personagens agachados (depende da altura do oponente) mas podem ser bloqueados tanto em pé quanto agachado;
* Golpes **Low** acertam inimigos que estavam bloqueando em pé mas são bloqueados por inimigos defendendo agachado;
* **Overhead** são golpes normalmente bem lentos mas acertam inimigos que estavam bloqueando low;
* Golpes **OTG** (On the Ground) são golpes que acertam oponentes caídos no chão.

## Framedata e Detalhes
Framedata é a informação geral dos golpes num jogo de luta, talvez o aspecto mais importante nele. Dele você ve quais as possiblidades que um personagem oferece em termos de ataque e defesa: o quão rápido um golpe é (que é visto em quantidade de frames por segundo), se ele consegue combar em outro ataque, qual o alcance desse ataque e entre outros. Há varios tipos de elementos de framedata pra cada golpe, que são:
* **Start-Up**: O tempo que a animação de um ataque leva até chegar no Active frames. É possivel que seu ataque tenha sido interrompido aqui se seu oponente conseguiu bater antes que seu golpe saísse;
* **Active**: O momento em que o golpe "bate" no oponente. Os frames ativos sempre conecta no oponente no primeiro possivel.
* **Recovery**: O tempo de animação em que o golpe termina até o personagem volta ao estado neutro. É a parte do ataque que é cancelado em combos com cancel e também é o momento que seu personagem fica vulnerável caso o oponente tenha bloqueado um golpe seu com muito recovery frames.
* **on Hit**: Quantidade de tempo em frames de diferença entre você e o oponente caso o golpe tenha conectado nele;
* **on Block**: Quantidade de tempo em frames de diferença entre você e o oponente caso ele tenha defendido um ataque;
* **Positivo e Negativo**: Caso seu ataque tenha acertado o seu oponente ou ele tenha bloqueado, há uma diferença de tempo entre vocês dois até que consigam realizar qualquer outra ação. Caso você consiga agir antes que seu oponente, você estava em vantagem de frames positiva (que seria dito como exemplo: +10 on Hit ou +2 on Block), e caso ele consiga agir antes de você, você estaria em Negativo (por exemplo -4 on Block);
* **Hitstun**: Animação que seu personagem está tomando dano;
* **Blockstun**: Animação que seu personagem fica quando defendeu um golpe;
* **Hitbox**: Caixa invisível para detecção de colisão de um golpe. Se a Hitbox colidir com uma Hitbox, o jogo avalia que o golpe acertou o oponente. O tempo que a Hitbox de um golpe fica ativa é o que referimos como Active Frames;
* **Hurtbox**: Caixa invisível de detecção de colisão do seu personagem em estado neutro. Se o golpe conectar na sua Hurtbox, o joga avalia que você levo dano e vai ficar em Hitstun e talvez seu inimigo consiga combar um ataque enquanto vc estiver preso na animação;
* **iFrames**: Alguns golpes apresentam alguns instantes de invulnerabilidade (por exemplo, o famoso Shoryuken). O iFrames são a quantidade de frames em que a caixa de invulnerabilidade do golpe está ativa.


## Combo
Combos são uma série de ataques seguidos que o oponente não consegue interromper apenas bloqueando (se ele fez isso é porque vc erro o combo). Há diversos tipos de combos em jogos diferentes:
* **Combo Links**: Realizado quando você conecta golpes um no outro porque a framedata possibilita tal. Tem execução mais restritiva e costuma aparecer em jogos mais velhos;
* **Chain Combo**: Combo que tem timing mais leniente que Combo Link e é executado geralmente com uma série de botões genérica (por exemplo: L > L > M > M > 2H do DBFZ)
* **Cancels**: Quando o recovery de algum ataque é cancelado e outro golpe sai imedianatamente;
* **Target Combo**: Execução de Normals específica em que cada um se "cancela" no outro.


## Neutro e Pressão

## Okizeme