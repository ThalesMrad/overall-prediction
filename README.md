Aplicar o conceito de regressão linear em uma base de dados, onde que dado um conjunto de dados de entrada, tentar predizer a saída através da modelagem de um polinômio. 

O objetivo deste trabalho foi prever uma saída coerente aos dados de entrada. Então, dada a base de dados, pretendíamos prever o atributo overall dos jogadores baseado em outros atributos.
Apenas a fim de contextualização, no FIFA 19, overall é uma pontuação geral que se dá a um jogador.
Para a elaboração do trabalho, foi utilizado uma base de dados intitulada “FIFA 19 complete player dataset”, que uma base do jogo eletrônico de futebol FIFA 19 que lista todos os jogadores, bem como todos os seus atributos. Ela contém 18206 linhas referentes a todos os jogadores e 89 colunas referentes a todos os atributos de cada jogador.
A princípio, o intuito era predizer o overall de todos os 18206 jogadores, porém estudando um pouco a respeito do FIFA 19, um mesmo atributo pode ser muito significativo para algumas posições e pouco para outras (por exemplo, um atacante deve ter uma boa finalização, mas para um zagueiro isso não é tão importante). Por este fato, a fim de simplificação optamos por restringir a amostra à apenas jogadores com o ofício de goleiro.
Foram considerados seis atributos relevantes para a predição do overall de um goleiro, são eles: 
habilidade com as mãos (GKHandling), chute (GKKicking), elasticidade (GKDiving), posicionamento (GKPositioning), reflexos (GKReflexes) e reputação internacional (InternationalReputation).
