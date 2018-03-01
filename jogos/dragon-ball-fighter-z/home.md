<!-- TITLE: Dragon Ball Fighter Z -->
<!-- SUBTITLE:-->
![Dragon Ball FighterZ](http://cdn.akamai.steamstatic.com/steam/apps/678950/header.jpg?t=1517353014)
Dragon Ball FighterZ (em sigla: DBFZ) é um jogo 3v3 desenvolvido pela Arc System Works baseado na franquia Dragon Ball. O jogo utiliza o mesmo estilo visual de Guilty gear Xrd, onde modelos 3D tentam imitar ao máximo visual e métodos de animação tradicional. O jogo roda na Unreal Engine 4.

---
# Lista de Personagens
| Personagens |  |  |
|---------------------------------------------------------------------------|-----------------------------------------------------------------------------------------|-----------------------------------------------------------------------|
| [Android 16](/jogos/dragon-ball-fighter-z/personagens/Android-16/geral) | [Android 18](/jogos/dragon-ball-fighter-z/personagens/Android-18/geral) | [Android 21](/jogos/dragon-ball-fighter-z/personagens/Android-21/geral) |
| [Beerus](/jogos/dragon-ball-fighter-z/personagens/Beerus/geral) | [Captain Ginyu](/jogos/dragon-ball-fighter-z/personagens/Captain-Ginyu/geral) | [Cell](/jogos/dragon-ball-fighter-z/personagens/Cell/geral) |
| [Frieza](/jogos/dragon-ball-fighter-z/personagens/Frieza/geral) | [Gohan (Adult)](/jogos/dragon-ball-fighter-z/personagens/Gohan-Adult/geral) | [Gohan (Teen)](/jogos/dragon-ball-fighter-z/personagens/Gohan-Teen/geral) |
| [Goku (SSGSS)](/jogos/dragon-ball-fighter-z/personagens/Goku-Blue/geral) | [Goku (Super Saiyan)](/jogos/dragon-ball-fighter-z/personagens/Goku-SSJ/geral) | [Goku Black](/jogos/dragon-ball-fighter-z/personagens/Goku-Black/geral) |
| [Gotenks](/jogos/dragon-ball-fighter-z/personagens/Gotenks/geral) | [Hit](/jogos/dragon-ball-fighter-z/personagens/Hit/geral) | [Piccolo](/jogos/dragon-ball-fighter-z/personagens/Piccolo/geral) |
| [Kid Buu](/jogos/dragon-ball-fighter-z/personagens/Kid-Buu/geral) | [Krillin](/jogos/dragon-ball-fighter-z/personagens/Krillin/geral) | [Majin Buu](/jogos/dragon-ball-fighter-z/personagens/Majin-Buu/geral) |
| [Nappa](/jogos/dragon-ball-fighter-z/personagens/Nappa/geral) | [Tien](/jogos/dragon-ball-fighter-z/personagens/Tien/geral) | [Trunks](/jogos/dragon-ball-fighter-z/personagens/Trunks/geral) |
| [Vegeta (SSGSS)](/jogos/dragon-ball-fighter-z/personagens/Vegeta-Blue/geral) | [Vegeta (Super Saiyan)](/jogos/dragon-ball-fighter-z/personagens/Vegeta-SSJ/geral) | [Yamcha](/jogos/dragon-ball-fighter-z/personagens/Yamcha/geral) |
# Mecânicas Básicas

## Notação
A notação usada em todos os artigos relacionados a DBFZ será a Numérica:

![Notação em DBFZ](https://cdn.discordapp.com/attachments/377253177059442688/410130219316281366/dbfz_notation-01.png)


## Termos gerais de jogo de luta 2D
### Normals, Specials, Supers, Command Normals, Grab, Command Grab e EX Specials
* Normals são os ataques básicos do personagem, como 5L que normalmente é um soco simples;
* Specials são os golpes únicos de cada personagem feito ao dar um comando especifico (exemplo popular: apertando 236 + soco para dar Hadouken), normalmente consegue ser combinado depois de algum Normal para dar mais dano (o famoso combo);
* Super é o "golpe secreto" do personagem. É normalmente executado ao fazer um comando mais complexo que um Special (no caso de Street Fighter, seria 236236 + soco, mas também pode ser relativamente simples que nem no Dragon Ball Fighter Z que é somente 236 + dois botões de ataque). Normalmente possui uma barra dedicada que só possibilita o Super ser executado caso ela esteja cheia;
* Command Normals são ataque simples normalmente específicos de cada personagem, como *6 + soco* para dar golpe Overhead;
* Grab é o agarrão. Dependendo do jogo pode ser combinação de dois botões ou apenas apertando 6 + botão forte para agarrar o oponente. Ferramente extremamanete útil contra algum oponente que está defendendo tudo que você faz, e normalmente defendível ao aperta os botões de Grab ao quase mesmo tempo que a pessoa que tentou dar ou pulando fora do alcance do grab caso esse só pegue em oponente que esteja no chão. Defender o agarrão dando o input de agarrão é chamando de Tech;
* Command Grab é a versão "Special" do Grab normal, que é feito somente quando vc faz algum comando especifico. Diferente do Grab normal, esse tipo de grab só dá para escapar pulando para fora do alcance. Mas cuidado porque há personagens que tem Command Grabs que só pegam em oponentes no chão ou só em oponentes no ar.
* EX Specials são uma versão mais forte dos Specials. Normalmente custando parte da barra de Super como efeito, e tão efetivo quanto usar um Super caso você esteja em dia com os combos do seu personagem.


### High, Low, Overhead e OTG
High e Low são referentes à altura dos golpes: 
* Golpes **High** acertam personagens em pé e na maioria das vezes personagens agachados (depende da altura do oponente) mas podem ser bloqueados tanto em pé quanto agachado;
* Golpes **Low** acertam inimigos que estavam bloqueando em pé mas são bloqueados por inimigos defendendo agachado;
* **Overhead** são golpes normalmente bem lentos mas acertam inimigos que estavam bloqueando low;
* Golpes **OTG** (On the Ground) são golpes que acertam oponentes caídos no chão.

### Framedata: Start-up, Active e Recovery frames, "on Hit" e "on Block", Positivo e Negativo, Hitstun, Blockstun Hitbox, Hurtbox e iFrames
Framedata é a informação geral dos golpes num jogo de luta, talvez o aspecto mais importante nele. Dele você ve quais as possiblidades que um personagem oferece em termos de ataque e defesa: o quão rápido um golpe é (que é visto em quantidade de frames por segundo), se ele consegue combar em outro ataque, qual o alcance desse ataque e entre outros. Há varios tipos de elementos de framedata pra cada golpe, que são:
* Start-Up: O tempo que a animação de um ataque leva até chegar no Active frames. É possivel que seu ataque tenha sido interrompido aqui se seu oponente conseguiu bater antes que seu golpe saísse;
* Active: O momento em que o golpe "bate" no oponente. Os frames ativos sempre conecta no oponente no primeiro possivel.
* Recovery: O tempo de animação em que o golpe termina até o personagem volta ao estado neutro. É a parte do ataque que é cancelado em combos com cancel e também é o momento que seu personagem fica vulnerável caso o oponente tenha bloqueado um golpe seu com muito recovery frames.
*  on Hit: Quantidade de tempo em frames de diferença entre você e o oponente caso o golpe tenha conectado nele;
*  on Block: Quantidade de tempo em frames de diferença entre você e o oponente caso ele tenha defendido um ataque;
*  Positivo e Negativo: Caso seu ataque tenha acertado o seu oponente ou ele tenha bloqueado, há uma diferença de tempo entre vocês dois até que consigam realizar qualquer outra ação. Caso você consiga agir antes que seu oponente, você estava em vantagem de frames positiva (que seria dito como exemplo: +10 on Hit ou +2 on Block), e caso ele consiga agir antes de você, você estaria em Negativo (por exemplo -4 on Block);
*  Hitstun: Animação que seu personagem está tomando dano;
*  Blockstun: Animação que seu personagem fica quando defendeu um golpe;
*  Hitbox: Caixa invisível para detecção de colisão de um golpe. Se a Hitbox colidir com uma Hitbox, o jogo avalia que o golpe acertou o oponente. O tempo que a Hitbox de um golpe fica ativa é o que referimos como Active Frames;
*  Hurtbox: Caixa invisível de detecção de colisão do seu personagem em estado neutro. Se o golpe conectar na sua Hurtbox, o joga avalia que você levo dano e vai ficar em Hitstun e talvez seu inimigo consiga combar um ataque enquanto vc estiver preso na animação;
*  iFrames: Alguns golpes apresentam alguns instantes de invulnerabilidade (por exemplo, o famoso Shoryuken). O iFrames são a quantidade de frames em que a caixa de invulnerabilidade do golpe está ativa.


### Combo
Combos são uma série de ataques seguidos que o oponente não consegue interromper apenas bloqueando (se ele fez isso é porque vc erro o combo). Há diversos tipos de combos em jogos diferentes:
* Combo Links: Realizado quando você conecta golpes um no outro porque a framedata possibilita tal. Tem execução mais restritiva e costuma aparecer em jogos mais velhos;
* Chain Combo: Combo que tem timing mais leniente que Combo Link e é executado geralmente com uma série de botões genérica (por exemplo: L > L > M > M > 2H do DBFZ)
* Cancels: Quando o recovery de algum ataque é cancelado e outro golpe sai imedianatamente;
* Target Combo: Execução de Normals específica em que cada um se "cancela" no outro.


### Neutro e Pressão

### Okizeme


## Termos únicos do jogo
### Super Dash
`(H+S, air OK)`
Um dash que acompanha o inimigo de forma teleguiada. Invulnerável a Ki Blast, mas perde para Ki Beams e Explosões. On hit garante combo. Safe on block.

### Dragon Rush
`(L+M, air OK)`
Dragon rush é o throw do jogo, ao acertar faz com que haja uma cutscene onde um dos personagens faz vários socos e chutes (assim como no desenho) e logo em seguida um launcher.
Não pode acertar os personagens durante o blockstun mas pode ser usado no meio do combo, mas ao contrário do dragon rush normal, o dragon rush feito em combos não dá launch.
Você pode dar tech em um Dragon Rush com qualquer botão, mas usando o próprio input de DR tem uma janela maior para dar tech.
Quanto mais longe é feito, mais devagar é o dragon rush, variando de aproximadamente 21 frames, na maior distância até 13 frames, na menor distância. Além do startup há mais 4f da janela de tech.
Apertando A1/A2 durante um Dragon Rush irá jogar o personagem do oponente para fora da tela e trazer outro dele (dependendo do botão de assist que foi usado). Similar ao Snapback na série Marvel vs Capcom.

### Z Assist
`(A1/A2, air OK)`
Chama um membro do seu time para te ajudar durante a luta. Cada personagem tem seu ataque pré-definido.
Há um cooldown quando você usa Z-Assist, um breve período onde o assist não pode ser chamado. A barra de cooldown só começa a se recuperar após o oponente sair do blockstun/hitstun.
Você pode chamar assists durante seus ataques, você pode chamar mais de um assist por vez.
Você não pode chamar um assist enquanto sofre um combo.

### Ki Charge
`(L+S)`
Deixa seu personagem imóvel enquanto carrega sua barra. O timer é parado durante o Ki Charge. Ki charge começa devagar e termina rápido.

### Z Reflect
`(4+S)`
| Ativo  | Recovery |
|--------|----------|
| 1f~22f | 18f      |

Similar ao pushblock / Advancing Guard da série Marvel vs Capcom. Caso algum ataque do oponente entre em contato com reflects seu oponente é empurrado para longe e você ganha uma quantidade considerável de barra. Durante um reflect você continua na mesma posição, só o oponente é jogado para longe. Reflects são capaz de refletir tanto highs como lows.

### Sparking Blast
`(L+M+H+S, air OK)`
Faz um movimento similar ao burst de Guilty Gear/Blazblue, porém, ao contrário do Burst, Sparking Blast é uma mecânica apenas ofensiva, não pode ser usado para quebrar combos.

Sparking Blast aumenta sua força e suas opções de cancels por um tempo limitado:

**Efeitos do Sparking Blast:**
- Afeta o Time inteiro;
- Quanto mais personagens vivos em seu time, menor é a duração do Sparking Blast;
- A Vida Azul do Personagem ativo é regenerada automaticamente, mesmo durante hitstun, em uma taxa elevada;
- Golpes no chão podem ser cancelados em pulo (inclusive on block);
- Golpes aéreos podem ser cancelados em airdash caso a segunda ação aérea (segundo pulo/airdash) não tenha sido utilizada anteriormente;
- Ganho de barra dobrado;
- 6M (Overhead universal) pode ser cancelado em Special Moves ou Airdash;
- Super Dash ao ser defendido tem menos pushback e pode ser cancelado em ataques instantaneamente;
- Segure M+H ou seu atalho de Vanish para teleportar atrás de seu oponente sem atacar, ascendendo levemente podendo defender ou atacar instantaneamente;
- O Cooldown de seus Assists irá diminuir até mesmo durante blockstun/hitstun de seu oponente.

### Vanish
`(M+H, air OK)`
Custa 1 barra. Teleporta atrás do seu oponente e ataca. Se feito durante o hitstun de algum golpe, cancelando-o, causa wallbounce. Se for feito no neutro apenas lança o oponente para longe. Durante o Sparking Blast segure M+H para teleportar atrás do seu oponente sem atacar e recuperar instantâneamente.

### Guard Cancel Change
`(6+A1/A2 durante blockstun)`
Gasta 1 barra. Troca de personagem. Ao usar o guard cancel change você não pode chamar assists por um tempo. Se você não tiver outros personagens vivos, o guard cancel funcionará como um vanish.

### Ultimate Z Change
`(A1/A2 ou 4+A1/A2 durante um super ou 41236+A1/A2 ou 63214+A1/A2)`
Similar ao DHC da série Marvel vs Capcom. Chama outro personagem do seu time para dar um Super. Pode ser feito durante um super do seu personagem ativo ou, se feito com 41236+A1/A2 ou 63214+A1/A2, Simplesmente chama outro personagem seu para fazer um super.

Personagens saindo ficarão em cooldown, um personagem pode entrar independente do cooldown. Gasta 1 ou 3 barras dependendo de qual super você fez.

# Dicas Gerais (Macetes Incríveis)
## Melhor forma de dar Anti-Air

## Como se defender
### Defendendo Dragon Rush
Para evitar de ser agarrado, basta aperta algum botão de ataque quando estiver prestes a levar o agarrão.
Qualquer dos botões L/M/H/S servem, mas a própria combinações de botões do Dragon Rush `L+M` tem uma janela bem maior para parar o Dragon Rush do adversário.

Lembre-se de que Dragon Rush no ar não pega no personagem que está no chão.
E os frames de início de um pulo tem invulnerabilidade contra agarrão também.

## Como extender sua blockstring

## A melhor forma de fazer seu time