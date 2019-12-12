# Mauricio-Cardoso

Aluno : Mauricio Cardoso da Silva

Faculdade: Area 1 

Data:23/11/2019

Trabalho simula o jogo do Pacman em um labirinto onde ele precisa encontrar o unico ponto de comida. 
O objetivo do trabalho é implementar tipos de buscas para fazer com que o Pacman chegue ao seu objetivo de forma autonoma e da melhor maneira possivel. Foi usado a estrutura de dados Stack (pilha), Queue (fila) e PriorityQueue (fila com prioridade) na implimentação de cada codigo na ordem sucessiva. 

O processo de tentar encontrar uma sequencia de ações que leva de um estado até um estado objetivo é chamado de busca.

• Uma vez encontrada a solução, o agente pode executar a sequencia de ações para chegar no objetivo.

O ambiente é estático, observável e determínistico.

Busca em profundidade (depth-first search = DFS)

Busca começar no nó raiz e adiciona na pilha nó raiz e explora os ramos desses nós, colando o nó a ser explorado no stack(Pilha). Depois você volta para o nó raiz, marcando os nós já visitados

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
