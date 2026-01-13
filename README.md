**Genetic Algorithms**

Genetic Algorithms are optimization techniques inspired by natural selection. They evolve a population of candidate solutions using selection, crossover, and mutation to gradually improve solution quality. GAs are effective for large, complex search spaces where traditional methods struggle.

**Vehicle Routing Problem**

The Vehicle Routing Problem focuses on finding efficient routes for vehicles delivering goods to multiple locations. It is widely used in logistics and supply chain optimization to reduce cost and improve operational efficiency.

**Implementation**

Implemented using Python and the DEAP library.

Individuals represent delivery routes and are evolved through selection, crossover, and mutation.

A custom fitness function evaluates total route distance and feasibility.

Matplotlib is used to visualize fitness trends and final routing paths.

**Results & Learnings**

The algorithm shows steady improvement in route quality across generations. Experimentation with genetic operators helped identify configurations that improved convergence and solution stability. The project strengthened understanding of evolutionary optimization and practical modeling.
