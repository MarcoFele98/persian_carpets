# persian_carpets
In here is the replication of Nowak, Martin &amp; May, Robert. (1992). Evolutionary Games and Spatial Chaos. Nature. 359. 826-829. 10.1038/359826a0. 

## Background
The evolution of cooperation is one of the biggest problems in evolutionary theory. The condition that allows for the seeminlgy paradoxical evolution of altruism is positive assortement: when altrusim are more likely to interact compared to other stategies. There are mulitple mechanisms that allow positve assortment: kin, behavioural bookeeping (reciprocity), and spatial structure. This model shows how spatial structure can lead to consexistance of altrusist and defection through a cellular automaton which runs a spatially explicit prisoner-dilemma game on a square lattice. 

## Code
Not great Mathematica code but very pretty nonetheless. The first function is used to find the fitenss of every cell based on the stategy of the focus cell and its neighbours with period boundary condition. It is possible to change the parameters of the two-strategies payoff matrix and in this way spatially simulate other types of games. The second function updates the state of the cell based on its fitness and the fitness of its neighbours (the state chcnage sto the best performing strategy). For the default parameter values, seeminlgy self-similar fractal growth obtained by seeding a defector in a world of cooperation is interrupted by dynamic and chaotic spatial patterns.
