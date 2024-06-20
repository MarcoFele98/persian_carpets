# persian_carpets
In here is the replication of Nowak, Martin &amp; May, Robert. (1992). Evolutionary Games and Spatial Chaos. Nature. 359. 826-829. 10.1038/359826a0. 

## Background
The evolution of cooperation/altruism is one of the biggest problems in evolutionary theory. The condition that allows for the seeminlgy paradoxical evolution of altruism is a sufficently strong "positive assortement": when altruists are more likely to interact compared to other stategies. There are multiple mechanisms that allow positive assortment e.g., kin (disclaimer: it is possible to argue that kin is not a "mechanism" but rather an alternative mathematical framework to describe positive assortment), behavioural bookkeeping (also known as reciprocity), and spatial structure. This model shows how spatial structure can lead to coexistence of altruism and defection through a cellular automaton which runs a spatially explicit prisoner-dilemma game on a square lattice. 

## Code
The first function is used to find the fitenss of every cell based on the stategy of the focus cell and its neighbours with periodic boundary condition. It is possible to change the parameters of the two-strategies payoff matrix and in this way simulate other types of games. The second function updates the state of the cell based on its fitness and the fitness of its neighbours (the focus stategy is set to the best performing one). For the default parameter values, seeminlgy self-similar fractal growth obtained by seeding a defector in a world of cooperation is interrupted by dynamic and chaotic spatial patterns.
![carpet](https://github.com/MarcoFele98/persian_carpets/assets/122376407/927f3148-5961-4a3a-b69b-411c2c21f15b)

