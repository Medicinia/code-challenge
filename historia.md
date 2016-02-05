## A lenda de Spotippos

No século passado, no planeta de Spotippos da galáxia Goopple, o reinado de Zillia estava em questionamento. Com seus 66 anos de idade e 33 anos no governo, o rei apresentava cansaço e parte do povo demandava mais energia e mudanças mais rápidas. 

Trullow, um idealista de 33 anos, iniciou então uma revolução que culminou no sesafio de sparzsek - uma famosa arma em Spotippos. O povo estava dividido. Parte apoiava Zillia, parte apoiava Trullow. O reinado, com seus ministros, delegados, juízes e soldados, também estava dividido. Foi então que o desafio foi aceito pelo rei Zillia, para lutar uma batalha de sparzsek até a morte. Quem vencesse seria então o rei absoluto de Spotippos. 

![Zillia](public/images/zillia.png)
> Zillia

Como a História é sempre cheia de surpresas, a batalha entre Zillia e Trullow acabou tragicamente em um incidente onde, por um milésimo de segundo, uma pequena fração de tempo, Zillia e Trullow desferiram simultaneamente o golpe monashark, onde o combatente usa as duas mãos e fica sem defesa durante aproximadamente 2 segundos, o que resultou na morte dos dois.

![Trullow](public/images/trullow.png)
> Trullow
 
O reinado se construiu novamente com outra estrutura e até hoje ambos são lembrados como ídolos em Spotippos. As batalhas de sparzsek foram banidas para sempre, trazendo paz e harmonia para o povo e para o reinado.

Um legado interessante deste período é que as duas moedas vigentes na época permanecem como moedas oficiais até hoje em Spotippos. Você pode usar tanto Zillis Z$ como Trullis T$ para efetuar seus pagamentos. O interessante é que a taxa de câmbio entre Z$ e T$ é calculada todos os dias a meia noite em ponto. A taxa de hoje é para cada 1 Z$ = 2 T$.

Agora, neste novo momento de Spotippos, o maior desafio dos bytes - ah, esqueci de mencionar que lá não vivem pessoas, a raça predominante lá são os bytes - é encontrar a casa dos seus sonhos. Além de ser complicado encontrar a casa ideal, alguns proprietários anunciam seus imóveis em Z$ e outros em T$, criando ainda mais dificuldade para encontrar a tão idealizada casa dos sonhos. 

O seu desafio é montar a unidade VivaReal em Spotippos! Para isso, iremos disponibilizar dois feeds de imóveis, um com preços em Zillis e outro com preços em Trullis.

Você deve construir então uma API que seja capaz de encontrar imóveis nas provincias Gode, Ruja, Jaby, Scavy, Groola e Nova.

![Spotippos](public/images/spotippos.png)


De acordo com imóveis de Spotippos fornecidos no feed [properties.json](properties.json), crie uma API com os seguintes métodos:

1. Dado 2 pontos (x,y) de coordenadas em Spotippos, devolva todos os imóveis pertencentes aquele retangulo.
2. Crie uma método que devolva todos os imóveis de uma provincia. Note que no mapa Gode e Ruja possuem uma sobreposição.
