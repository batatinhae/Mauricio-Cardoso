# Mauricio-Cardoso

Aluno : Mauricio Cardoso da Silva

Faculdade: Area 1 

Data:23/11/2019

Trabalho simula o jogo do Pacman em um laberinto onde ele precisa encontrar o unico ponto de comida. 
O objetivo do trabalho é implementar tipos de buscas para fazer com que o Pacman chegue ao seu objetivo de forma autonoma e da melhor maneira possivel. Foi usado a estrutura de dados Stack (pilha), Queue (fila) e PriorityQueue (fila com prioridade) na implimentação de cada codigo na ordem sucessiva. 

Busca em profundidade (depth-first search = DFS)

Usamos o seguinte comandos para executar o programa: 

python pacman.py -l tinyMaze -p SearchAgent

python pacman.py -l mediumMaze -p SearchAgent

python pacman.py -l bigMaze -z .5 -p SearchAgent

Video - Link: https://drive.google.com/open?id=1fNdGktNccbSsPI2ysiI89k2iTVTb0Z9D

Busca em Largura (breadthFirstSearch = BFS)

Usamos o seguinte comandos para executar o programa:

python pacman.py -l mediumMaze -p SearchAgent -a fn=bfs

python pacman.py -l bigMaze -p SearchAgent -a fn=bfs -z .5

Video - Link: https://drive.google.com/open?id=1YxB-osrrRiuJl9uzEScjsE45iIDRnn1E

Busca de Custo Uniforme (uniformCostSearch = UCS)

Usamos o seguinte comandos para executar o programa:

python pacman.py -l mediumMaze -p SearchAgent -a fn=ucs

python pacman.py -l mediumDottedMaze -p StayEastSearchAgent

python pacman.py -l mediumScaryMaze -p StayWestSearchAgent

Video - Link: https://drive.google.com/open?id=1aI2BBwIVHA7uz6NYTUN_pm9epTsgyUtG

Busca A* (StarSearch = AaStarSearch )

Usamos o seguinte comandos para executar o programa:

python pacman.py -l bigMaze -z .5 -p SearchAgent -a fn=astar,heuristic=manhattanHeuristi

python pacman.py -l trickySearch -p AStarFoodSearchAgent

Video

Link: https://drive.google.com/open?id=1R3l2UomMrvLjqLNWP6Aum9Mvp-BwsBJX

Link: https://drive.google.com/open?id=1u36itmHUpGWNUBHOGRAKvlqZNpTD44kI
