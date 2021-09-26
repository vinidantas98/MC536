# Modelo para Apresentação do Lab06 - Artigo de Dataset Público

Estrutura de pastas:

~~~
├── README.md  <- arquivo apresentando a tarefa
│
└── images     <- arquivos de imagem usados na tarefa (se houver)
~~~

# Aluno
* `188092`: `Vinicius Alves Mancine Dantas`

# Análise do Artigo Extracting and Composing a Dataset of Competitive Counter-Strike Global Offensive Matches

| campo | valor |
|------------|----------------------------------------|
| referência | `Erick Rocha, Henrique Maio, Daniel S. Menasché, Claudio Miceli: Extracting and Composing a Dataset of Competitive Counter-Strike Global Offensive Matches.` |
| link       | `https://drive.google.com/file/d/106Ps__OM8ryapvP958FAIyhEWkzf_XfS/view` |
| dataset | `https://labnet.nce.ufrj.br/files/CSGO_Dataset/` |
| formato | `Apache Parquet` |

## Resumo

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;O artigo inicialmente discorre sobre como os jogos são parte de nossas vidas a milhares de anos e introduz os e-sports, jogos eletrônicos que vem ganhando espaço na mídia e movimentando bilhões de dólares ao redor do mundo. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;O foco do artigo é em um jogo chamado Counter-Strike, um jogo multiplayer de FPS(First-Person Shooter) que contém um cenário competitivo muito bem desenvolvido. CS, como é chamado popularmente, contém diversas estratégias e, em alto nível competitivo, pequenos detalhes que acontecem durante o jogo são decisivos para a partida.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Todas a informações sobre os jogos e torneios competitivos estão espalhados em diversos sites contendo informações precisas sobre cada momento de cada jogo, o artigo divide esses dados em duas categorias: high level data e low level data. Por mais que esses dados possam ser encontrados facilmente em sites, o artigo diz que não há um dataset público que conecte os dois tipos de dados de forma a ser possível realizar uma análise profunda e detalhada sobre os jogos, estratégias, posicionamento, etc. Por conta disto, o objetivo do artigo é criar um dataset onde tudo isso seja possível.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Para atingir este objetivo, diversas barreiras e desafios tiveram que ser quebrados. Estes desafios juntamente com uma explicação mais detalhada sobre quais ferramentas foram usadas, como é feita a coleta de dados, como estes dados são estruturados, indexados e armazenados são descritos no artigo.

## Perguntas de pesquisa/análises
No própio artigo algumas perguntas que podem ser feitas ao dataset são descritas, sendo elas:
- Qual é o comportamento de movimentação do usuário?
- Quais são as estratégias mais adotadas?
- Quais são as melhores estratégias para se ganhar uma partida?
- Como identificar comportamentos de pessoas usando hack(programas auxiliares proíbidos para ganhar - vantagem nos jogos)?

Lendo o artigo ainda é possível identificar mais algumas perguntas que podem ser feitas ao dataset, como:
- Quais são as armas mais usadas pelos jogadores com maior pontuação no campeonato?
- Qual é a média de utilitários usados em cada rodada?
- Quais são os piores lugares para se ficar dentro do bomb em cada mapa?
- Quantos segundos em média um jogador fica cego por granadas de flash por rodada?  

## Trabalhos relacionados
Algumas outras iniciativas relacionadas ao artigo são citadas, como por exemplo:
- Varvello, M., Picconi, F., Diot, C., and Biersack, E. (2008). Is there life in second life? In Proceedings of the 2008 ACM CoNEXT Conference, pages 1–12.
  - Um dos primeiros papéis publicados envolvendo o uso de crawlers e análise de dados de jogos, que neste caso foi focado no jogo Second Life.
  
- Xenopoulos, P., Doraiswamy, H., and Silva, C. (2020). Valuing player actions in counter-strike: Global offensive. In In Proceedings of the 2020 IEEE International Conference on Big Data.
  - Plataforma open-source para coleta de dados do CS:GO.
  
- Bednarek, D., Zavoral, F., and Yaghob, J. (2017). Data preprocessing of esport game records - counter-strike: Global offensive. In In Proceedings of the 6th International Conference on Data Science, Technology and Applications - DATA, 269-276, 2017, Madrid, Spain.
  - Análise de dados do site HLTV, com o objetivo de avaliar e prever performance de jogadores.
 
Outras referências encontradas no artigo estão listadas abaixo:
- El-Harami, J. (2015). Entertainment and recreation in the classical world—tourism products. In Journal of Management and Sustainability; Vol. 5, No. 1; 2015.
- SuperData (2021). 2020 year in review digital games and interactive media. Technical report, SuperData, a Nielsen company.
- Varvello, M. and Voelker, G. M. (2010). Second life: a social network of humans and bots. In Proceedings of the 20th international workshop on network and operating systems support for digital audio and video, pages 9–14.
