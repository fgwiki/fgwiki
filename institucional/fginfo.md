<!-- TITLE: Informação geral em jogos de Luta -->

# Termos gerais de jogo de luta 2D
## Notações
Notações normalmente depende de cada jogo, mas sempre há termos mais genéricos que possívelmente todo mundo consegue entender cedo ou tarde.

### Notação Numérica
|  |  |  |
|---|---|---|
| 7 | 8 | 9 |
| 4 | 5 | 6 |
| 1 | 2 | 3 |

O método de referência de direção mais comum entre os jogadores japoneses, pode parecer um tanto confuso no começo mas logo fica facil de reconhecer as direções num piscar de olhos. Ele assume sua posição de Player 1, portanto fica: 4 = Trás, 6 = Frente, 2 = Baixo, 8 = Cima e 5 = Nenhuma direção sendo pressionada. Nisso o movimentoi de Hadouken, por exemplo, fica escrito como 236 + Soco.
Há os golpes que são executados ao segurar o botão pra trás ou baixo, e rapidamente apertar a direção oposta + botão de ataque. Esses são chamados de Charge.
Para referir ao movimento de Charge em notação numérica, é usado os colchetes `[]` para a direção segurada.
No final, a notação deve ficar tipo assim:

|  |  |
|---|---|
| Hadouken | 236+ Soco |
| Sonic Boom | [4]6 + Soco|

Jogos como Street Fighter, que não possui comandos direcionais muito absurdos ou no geral bem comuns, tem siglas como forma mais popular de mostrar como são feitos os movimentos de specials:

| Sigla | Nome | Notação Num. |
|---|---|---|
| qcf | Quarter Circle Foward | 236 |
| qcb | Quarter CIrcle Back | 214 |
| ch bf | Charge Back Foward | [4]6 |
| ch du | Charge Down Up | [2]8 |
| dp | Dragon Punch (Shoryuken) | 623 |
| rdp | Reverse Dragon Punch | 421 |
| tk | Tiger Knee | 12369 |

### Botões de Ataque
Alguns jogos possuem pesos diferentes pra tipos de chute e soco, alguns apresentam apenas pesos, portanto eu vou colocar siglas e algumas das possíveis combinações:

| Sigla | Nome Inglês | Tradução |
|---|---|---|
| L | Light | Fraco |
| M | Medium | Médio |
| H | Heavy | Forte |
| S | Special | Especial |
| LP | Light Punch | Soco Fraco |
| MP | Medium Punch | Soco Médio |
| HP | Heavy Punch | Soco Forte |
| LK | Light Kick | Chute Fraco |
| MK | Medium Kick | Chute Médio |
| HK | Heavy Kick | Chute Forte |
| PPP | 3x Punches | Os 3 botões de Soco |
| KKK | 3x Kick | Os 3 botões de Chute |

Tenha em mente que nem todos os jogos usam os mesmos termos, por exemplo Guilty Gear tem S = Slash e H = Heavy Slash, e outros jogos usam até A, B, C e D para os botões como os jogos da SNK.

## Normals, Specials, Supers, Command Normals, Grab, Command Grab e EX Specials
* **Normals** São os ataques básicos do personagem, como 5L que normalmente é um soco simples;

* **Jumping** Para quem não sabe inglês, significa "pulando";

* **Specials** São os golpes únicos de cada personagem feito ao dar um comando específico (exemplo comum: apertando 236 + soco para dar Hadouken), normalmente consegue ser combinado depois de algum Normal para dar mais dano (o famoso combo);

* **Super** é o "golpe secreto" do personagem. É normalmente executado ao fazer um comando mais complexo que um Special (no caso de Street Fighter, seria 236236 + soco, mas também pode ser relativamente simples que nem no Dragon Ball Fighter Z que é somente 236 + dois botões de ataque). Normalmente possui uma barra dedicada que só possibilita o Super ser executado caso ela esteja cheia;

* **Command Normals** são ataque simples normalmente específicos de cada personagem, como *6 + soco* para dar golpe Overhead;

* **Grab** é o agarrão. Dependendo do jogo pode ser combinação de dois botões ou apenas apertando 6 + botão forte para agarrar o oponente. Ferramenta extremamente útil contra algum oponente que está defendendo tudo que você faz. Para lidar com grab, você pode dar tech, que se refere ao ato de tentar dar grab ao mesmo tempo que seu oponente (ou prever um grab com antecedência). Grabs só funcionam contra oponentes que estão no chão, oponentes *airborne* (no ar) ou durante blockstun estão imunes a grabs. Pulos e backdashes são opções bem comuns para escaparem de throws.
O ato de dar um grab ao mesmo tempo que seu oponente é chamado de **tech**

* **Command Grab** é a versão "Special" do Grab normal, que é feito somente quando vc faz algum comando especifico. Diferente do Grab normal, esse tipo de grab só dá para escapar pulando para fora do alcance. Mas cuidado porque há personagens que tem Command Grabs que só pegam em oponentes no chão ou só em oponentes no ar.

* **EX Specials** são uma versão mais forte dos Specials. Normalmente custando parte da barra de Super como efeito, e tão efetivo quanto usar um Super caso você esteja em dia com os combos do seu personagem.


## High, Low, Overhead e OTG
High e Low são referentes à altura dos golpes: 
* Golpes **High**: Golpes que precisam ser defendidos em pé. Normalmente vem a partir de *jump-ins* (pulos) ou overheads.

* Golpes **Mid**: Golpes que podem ser defendidos tanto em pé quanto agachado.

* Golpes **Low**: Golpes que precisam ser defendidos agachados. Normalmente estes golpes são feitos agachados, com algumas exceções. Em alguns jogos existem golpes low que são feitos com personagem em pé.

* **Overhead** (em sigla: OH) são golpes normalmente bem lentos mas acertam inimigos que estavam bloqueando low;

* Golpes **OTG** (On the Ground) são golpes que acertam oponentes caídos no chão. Não confundir com *okizeme*.

## Framedata e Detalhes
Framedata são informações gerais sobre os golpes em um jogo de luta. Mais especificamente sobre *velocidade* e *duração dos golpes* . O quanto um golpe demora para começar, quanto tempo ele pode acertar o oponente e quanto tempo demora para voltar ao *neutro* . O tempo é denotado em *frames* que se refere aos quadros de animação, maioria dos jogos de luta rodam a 60 quadros por segundo, fazendo com que cada frame seja aproximadamente 16 milissegundos.

Você não precisa decorar framedata, você também não precisa se preocupar com milissegundos. Framedata é para ser consultada durante o seu treino e para poupar o tempo que você gastaria testando coisas. É informação valiosa sintetizada de uma maneira muito rápida de digerir.

Framedata normalmente consiste das seguintes informações:

* **Start-Up**: O tempo que a animação de um ataque leva até chegar no Active frames. É possível que seu ataque tenha sido interrompido aqui se seu oponente conseguiu bater antes que seu golpe saísse;
> Um golpe que começa em 3f é mais rápido do que um que começa em 7f

* **Active**: O momento em que o golpe "bate" no oponente. Os frames ativos sempre conectam no oponente no primeiro possível.
> Meu golpe tem 4f ativo, significa que ele fica ali,na tela, acertando durante 4f.

* **Recovery**: O tempo de animação em que o golpe termina até o personagem volta ao estado neutro.
> Golpes com recovery muito alto podem ser punidos porque meu personagem demora a voltar a defender.

* **on Hit**: Quantidade de tempo em frames de diferença entre você e o oponente caso ele tenha recebido um ataque
> Se um golpe é +7 on hit, você recupera 7 frames antes do seu oponente. Nesse caso posso combar com um golpe de até 7 frames de startup. 

* **on Block**: Quantidade de tempo em frames de diferença entre você e o oponente caso ele tenha defendido um ataque;
> Dei um golpe que é -5 on block na defesa do meu oponente. Eu posso levar qualquer golpe de até 5f de startup. Pois ele recupera o controle do personagem 5f antes de mim.

* **Positivo e Negativo**: Caso seu ataque tenha acertado o seu oponente ou ele tenha bloqueado, há uma diferença de tempo entre vocês dois até que consigam realizar qualquer outra ação. Caso você consiga agir antes que seu oponente, você estava em vantagem de frames positiva (que seria dito como exemplo: +10 on Hit ou +2 on Block), e caso ele consiga agir antes de você, você estaria em Negativo (por exemplo -4 on Block);

* **Hitstun**: Animação que seu personagem está tomando dano;

* **Blockstun**: Animação que seu personagem fica quando defendeu um golpe;

* **Hitbox**: Caixa invisível para detecção de colisão de um golpe. Se a Hitbox colidir com uma Hitbox, o jogo avalia que o golpe acertou o oponente. O tempo que a Hitbox de um golpe fica ativa é o que referimos como *Active Frames* (Frames ativos);

* **Hurtbox**: Caixa invisível de detecção de colisão do seu personagem em estado neutro. Se a hitbox de um golpe conectar na sua Hurtbox, o joga avalia que você levou dano e vai ficar em Hitstun.

* **iFrames**: Também conhecidos como *Invencibility/Invulnerability Frames* (ou frames de invencibilidade). São literalmente golpes que não podem ser atingidos, justamente pela __ausência de hurtbox__.
Alguns golpes como os shoryukens de Street Fighter são imunes a golpes, pois eles não tem hurtbox durante um tempo em suas animações, o que faz com que eles tenham muitos iframes.


## Combo
Combos são uma série de ataques seguidos que o oponente não consegue interromper apenas bloqueando (se ele fez isso é porque vc errou o combo). Há diversos tipos de combos em jogos diferentes:

* **Combo Links**: Realizado quando você conecta golpes um no outro porque a framedata possibilita tal. Tem execução mais restritiva e costuma aparecer em jogos mais velhos;
> Um golpe é +5 on hit, posso encaixar um golpe de até 5f de startup. Isso é um link.

* **Chain Combo**: Combo que tem timing mais leniente que Combo Link e é executado geralmente com uma série de botões genérica (por exemplo: L > L > M > M > 2H do DBFZ) Chain combos cancelam um botão em outro logo após conectar com o oponente. Também conhecidos como **Target Combos**, **Gatlings** e **Magic Series**

* **Cancels**: Quando o recovery de algum ataque é cancelado e outro golpe sai imediatamente;

## Neutro e Pressão
* **Neutral Game**: Jogo neutro se refere a um ponto do jogo onde ambos jogadores não tem nenhuma vantagem sobre o outro estão procurando conseguir qualquer tipo de vantagem.

    **Alguns exemplos de situações vantajosas:**
    - Fazer seu oponente bloquear algo positivo on block
    - Acertar um golpe
    - Conseguir um knockdown
    - Levar seu oponente pro corner são exemplos de situações vantajosas.

* **Mix-up**: Mixup é qualquer situação que você obrigue seu oponente a escolher entre opções.
    - Criar uma dúvida se você vai agarrar ou fazer um overhead
    - Se você vai fazer um crossup ou não
    - Se ele precisa defender high ou low

* **Okizeme**: Refere-se a atacar seu oponente enquanto ele está levantando de um knockdown.

## Defesa
* **Block**: A simples defesa. Grande maioria dos jogos 2D é simplesmente segurar para trás ou trás+baixo.
* **Pushblock**: Alguns jogos possuem mecânicas que permitem que o ataque do oponente seja ainda mais afastado caso você bloqueie e aperte junto uma combinação de botões. Isso se chama Pushblock, mas também pode possuir nomes próprios dependendo do jogo (Advancing Guard no Marvel vs Capcom 3, Faultless Defense no Guilty Gear, Reflect no Dragon Ball Fighter Z)
* **Chicken Block**: Jogos que tem um jogo aéreo mais intenso normalmente te dão a possibilidade de bloquear no ar. Chicken Block é rapidamente pular para trás e bloquear para evitar mix-ups intensivos, já que no ar não há diferença entre high e low, e sair do blockstun mais rápido.

* **Burst**: Alguns jogos que possuem pressão intensa dão a possibilidade do jogador interromper a ofensiva do adversário. Burst é usado para afastar o oponente numa explosão que da pouco dano e manda ele para o outro lado da tela, e assim voltando ao neutral game. Pode ser realizado para interromper um combo do seu oponente ou simplesmente usar para acabar com a pressão.
* **Guard Cancel**:
* **Reversal**:
* **Parry**:

## Option Select

## Fuzzies
Termos de fuzzies ficaram meio que misturados por erro de comunicação na internet, portanto vou organizar da melhor forma que encontrei. (Obrigado Lorem e Ryuzlin pela colaboração).

### Fuzzy Guard
Técnica defensiva e um OS. Quando um ataque do oponente pode ser seguido de um outro ataque low ou overhead, esses provavelmente vão ter startups diferentes. Para defender isso vc pode fazer o **Fuzzy Guard**: Defender agachado até um pouco antes de acaba o start-up frames do OH, defende em pé por alguns instantes, e depois defende agachado de novo.
Exemplo: Se um personagem tem followup de um ataque que é um low 9f start-up e um OH 20f de start-up, vc defende os 18 primeiros frames agachado, levanto por um breve tempo e agacha de novo.

Para vencer esse tipo de defesa, o oponente pode atrasar um pouco o golpe low dele.

### Fuzzy Jump
Similar ao Fuzzy Guard, mas ao inves de High/Low você vai fazer Low/Jump. Você bloqueia os primeiros frames agachado, depois pula e volta rapidamente a defende low. Fuzzy Jump funciona mais contra personagens que tem mix-up low/grab.

### Fuzzy Attack / F-Shiki
Isso daqui é a coisa que confunde muita gente, mais porque muita gente chama isso de Fuzzy Guard ou simplesmente de Fuzzy no ocidente, e no Japão é chamado de F-Shiki ou um dos outros 10 milhões de termos. Vo usar Fuzzy Attack porque, diferente dos outros dois, esse é um técnica ofensiva.
**Fuzzy Attack** consiste em dar um ataque que prende o oponente no blockstun em pé (normalmente um ataque pulando), e logo em seguida dar um ataque Overhead (novamente normalmente outro jumping attack) para acerta o oponente.
Se o ataque OH acertar o oponente que estava preso em blockstun em pé, é porque o Fuzzy Attack funcionou. Isso funciona porque o oponente defendeu agachado depois do primeiro ataque:  Enquanto ele estava no blockstun em pé, ele apertou baixo+trás para bloquear porque achou que você ia dar um ataque low, mas como o blockstun não permitiu que a animação do personagem mudasse de posição, ele leva um OH que possivelmente não poderia levar porque só acertaria no personagem com altura em pé.