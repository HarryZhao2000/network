# CS224w -1 Structure of graph

## Two types of network

- Networks(AKA Natural Graphs)
- Information Graphs

## Why networks? Why now?

- Universal language for describing complex data
  - The underlying data representation is the same
  - 通用性
- Shared vocabulary between fields
  - 跨学科研究
- Data availabity and computational challenge 
- Impacts
  - people start to realize the impact of networks

## Ways to analyze networks

- Predict the type/color of a given node ( node classification )
- Predict whether two node are linked ( link prediction )
- Identify densely linked clusters of nodes ( community cluster )
- Measure similarity of two nodes/networks ( Network similarity )

### Application

- Social networks

  - Social Circle detection ( Discover circle and why exist )

- Infrastructure

- Knowledge( Encoding into graphs )

  #### Embedding Node

  Take the graph and try to map every nodes of the graph in some d-dimensional space. So the nodes related in the graph are also close in the space.

  Goal: Map nodes to d-dimensional embeddings so that nodes with similar network neighborhoods are embedded colse together.

- Online media

- Misinformation/fake news

  - Use articles links to detect whether an article is a hoax. 
  - Hoax intend to refer to an **incoherent** set of entities.
  - Tring to capture relationships

- Predictiing Virality

  - How information cascade
    - how they spread and how peoplr get adopted and how perople get exposed to it and so on.
  - Product Adoption

- Biomedicine

  - 蛋白质网络 protein-protein
  - Side effects
    - Given a pair of drugs, predict adverse side effects.
  - How?
    - Build a heterogeneous graph
    - Predict links

## Structure of graph

- A network is a collection of objects where some pairs of objects are connected by links.
- Components of a Network
  - Objects: nodes, vertices.  N
  - Interactions: link, edge.     E
  - System: network, graph.   G(N,E)
- Network or Graph
  - Network often refer to real systems.
    - Language: Network, node, link
  - Graph is a mathematical representation of a network
    - Language: Graph, vertex, edge
- How to define a network?
  - How to build a graph:
    - What are nodes?
    - What are edges?
  - Choice of proper network representation of a given domain/problem deternmines our ability to use networks successfully:
    - In some cases there is a unique, unambiguous representation
    - In other cases, the representation is by no means unique
    - The way you assign links will determine the nature of the question you can study

## Representation

- Directed vs Undirected
- Node degrees
- Complete graph E=N(N-1)/2
- Bipartite Graph
  - Bipartite Graph is a graph whose nodes can be divided into 2 disjoint sets U and V such that every link connects a node in U to one in V; that is, U and V are independent sets.
  - Folded Graph

- Adjacency Matrix
- Edge list
- Adjacency lisy
- 



