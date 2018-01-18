# Evolutionary Computing
## Introduction

Evolutionary computation is a family of algorithms for global optimisation inspired by biological evolution, and the subfield of artificial intelligence and soft computing studying these algorithms. In technical terms, they are a family of population-based trial and error problem solvers with a meta-heuristic or stochastic optimisation character.

Evolutionary Algorithms (EA) consist of several heuristics, which are able to solve optimisation tasks by imitating some aspects of natural evolution. They may use different levels of abstraction, but they are always working on whole populations of possible solutions for a given task. EAs are an approved set of heuristics, which are flexible to use and postulate only neglectible requirements on the
optimisation task.

In real world applications you will most likely encounter problems that are hard to solve. Some examples for these kind of problems are the travelling salesman or the knapsack problem, but also financial applications like the constrained portfolio selection, time series prediction, trading rules for asset and bond markets [DM98], bankruptcy prediction [KF95], credit scoring [DL94], data mining and
many more.

Algorithms to solve these kind of problems are either so specialised, that they only can be applied to a small range of problems, or they are more general but rather inefficient. Some general search heuristics like simple enumeration require vast amounts of computation time and will effectively fail if the problem dimension increases. On the other hand Hill-Climbing algorithms are easily deceived in
multimodal problem spaces and will most likely get stuck in some sub optima.

One of the major advantages of EA methods compared to other methods is, that they only need little problem specific knowledge and that they can be applied on a broad range of problems. EA methods only need the target (fitness) function for a given problem, which is to be optimised. Additional problem specific knowledge can easily be brought into the EA heuristic to improve performance. EA methods do have neglectible demands on the nature of the problem space, they even can be applied on complex problems with discontinuous, non-differentiable and possibly noisy target functions. Additionally they react robust to external EA process parameters and therefore are easy to use on very different problems without the need of special tuning or expert knowledge. Because of the diversity of EA methods it is easy to select an EA method that is especially well suited for a given problem, regarding the data types that are to be processed, the representation of the solution and the search space topology

## Fundamentals of Evolutionary Algorithms

EA are stochastic search and optimisation heuristics derived from the classic evolution theory, which are implemented on computers in the majority of cases. The basic idea is that if only those individuals of a population reproduce, which meet a certain selection criteria, and the other individuals of the population die, the population will converge to those individuals that best meet the selection criteria. If imperfect reproduction is added the population can begin to explore the search space and will move to individuals that have an increased selection probability and that inherit this property to their descendants. These population dynamics follow the basic rule of the Darwinistic evolution theory, which can be described in short as the “survival of the fittest”

To solve optimisation problems with an evolutionary heuristic the individuals of a population have to represent a possible solution of a given problem and the selection probability is set proportional to the quality of the represented solution.

## Applications

### Technical Trading
As a practical application, technical trading rules found by the use of EA will be presented.
