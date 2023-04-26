## Graph theory subject domains hierarchy

```mermaid
graph LR;
    Graphs([Graphs])
    Graphs --> Simple_Graphs([Simple Graphs])
    Graphs --> Directed_Graphs([Directed Graphs])
    Graphs --> Multigraphs([Multigraphs])
    Graphs --> Trees([Trees])
    Graphs --> Planar_Graphs([Planar Graphs])
    Graphs --> Acyclic_Graphs([Acyclic Graphs])
    Graphs --> Graph_Cuts([Graph Cuts])
    Graphs --> Graph_Sequence([Graph Sequence])
    Graphs --> Graph_Properties([Graph Properties])
    Graphs --> Graph_Representation([Graph Representation])
    Graphs --> Graph_Operations([Graph Operations])
    Graphs --> Graph_Connectivity([Graph Connectivity])
    Graphs --> Graph_Algorithms([Graph Algorithms])

    Directed_Graphs --> Weighted_Directed_Graphs([Weighted Directed Graphs])

    Multigraphs --> Hypergraphs([Hypergraphs])
    
    Trees --> Binary_Trees([Binary Trees])
    Trees --> Quad_Trees([Quad Trees])
    Trees --> Heaps([Heaps])
    
    Planar_Graphs --> Graph_Embeddings([Graph Embeddings])
    Planar_Graphs --> Graph_Coloring([Graph Coloring])
    
    Acyclic_Graphs --> Directed_Acyclic_Graphs([Directed Acyclic Graphs])
    Acyclic_Graphs --> Forests([Forests])

    Graph_Cuts --> Minimum_Graph_Cuts([Minimum Graph Cuts])
    Graph_Cuts --> Maximum_Graph_Cuts([Maximum Graph Cuts])
    Graph_Cuts --> Graph_Cut_Space([Graph Cut Space])
    Graph_Cuts --> Graph_Splits([Graph Splits])

    Graph_Sequence --> Graph_Paths([Graph Paths])
    Graph_Sequence --> Graph_Cycle([Graph Cycle])
    Graph_Sequence --> Graph_Chain([Graph Chain])
    
    Graph_Operations --> Dual_Graphs([Dual Graphs])

    Graph_Algorithms --> Shortest_Paths([Shortest Paths])
    Graph_Algorithms --> Tree_Traversal([Tree Traversal])
    Graph_Algorithms --> Graph_Traversal([Graph Traversal])

    Shortest_Paths --> Dijkstra_Algorithm[Dijkstra Algorithm]
    Shortest_Paths --> Floyd_Warshall_Algorithm[Floyd-Warshall Algorithm]

    Tree_Traversal --> Pre_order_Traversal[Pre-order Traversal]
    Tree_Traversal --> In_order_Traversal[In-order Traversal]
    Tree_Traversal --> Post_order_Traversal[Post-order Traversal]

    Graph_Traversal --> Breadth_First_Search[Breadth-First Search]
    Graph_Traversal --> Depth_First_Search[Depth-First Search]
```


## Key concepts
- __Basic Concepts__ [Базовые понятия (граф, вершина, ребро)]\
`Graphs`

- __Connectivity__ [Связность и компоненты графа]\
`Graphs > Connectivity`

- __Graph Properties__ [Свойства графов]\
`Graphs > Properties`

- __Graph Representation__ [Способы задания графов]\
`Graphs > Graph Representation`

- __Paths__ [Маршруты]\
`Graphs > Paths`

- __Paths__ [Пути]\
`Graphs > Paths`

- __Paths__ [Цепи]\
`Graphs > Paths`

- __Cycles__ [Циклы]\
`Graphs > Paths`

- __Subgraphs__ [Подграфы]\
`Graphs > Simple Graphs > Subgraphs`

- __Directed Graphs__ [Ориентированные графы]\
`Graphs > Directed Graphs`

- __Acyclic Graphs__ [Ациклические графы]\
`Graphs > Directed Graphs > Acyclic Graphs`

- __Trees__ [Деревья]\
`Graphs > Trees`

- __Graph Cuts__ [Сечение деревьев]\
`Graphs > Trees > Graph Cuts`

- __Dual Graphs__ [Двойственные графы]\
`Graphs > Graph Operations > Dual Graphs`

- __Planar Graphs__ [Планарные графы]\
`Graphs > Planar Graphs`

- __Cut Vertices and Bridges__ [Точки сочленения, мосты и блоки]\
`Graphs > Planar Graphs > Cut Vertices and Bridges`

- __Breadth-First Search__ [Поиск в ширину]\
`Graphs > Graph Algorithms > Graph Traversal > Breadth-First Search`

- __Depth-First Search__ [Поиск в глубину]\
`Graphs > Graph Algorithms > Graph Traversal > Depth-First Search`

- __Dijkstra Algorithm__ [Нахождение кратчайшего пути (Алгоритм Дейкстры)]\
`Graphs > Graph Algorithms > Shortest Paths > Dijkstra Algorithm`

- __Pre-order Traversal__ [Прямой левый обход дерева]\
`Graphs > Graph Algorithms > Tree Traversal > Pre-order Traversal`

- __In-order Traversal__ [Центрированный обход дерева]\
`Graphs > Graph Algorithms > Tree Traversal > In-order Traversal`

- __Post-order Traversal__ [Обратный левый обход дерева]\
`Graphs > Graph Algorithms > Tree Traversal > Post-order Traversal`

- __Floyd-Warshall Algorithm__ [Алгоритм Флойда - Уоршелла]\
`Graphs > Graph Algorithms > Shortest Paths > Floyd-Warshall Algorithm`

## Distribution
- Voitkus Stanislav:
  - Subject Domain of Domain of Graphs
  - Subject Domain of Connectivity
  - Subject Domain of Graph Operations
  - Subject Domain of Dual Graphs
- Samokhval Evgeniy:
  - Subject Domain of Shortest Sequence
  - Subject Domain of Graph Paths
  - Subject Domain of Graph Cycle
  - Subject Domain of Graph Chain
  - Subject Domain of Simple Graphs
  - Subject Domain of Subgraphs
- Sharapov Artur:
  - Subject Domain of Acyclic Graphs
  - Subject Domain of Directed Acyclic Graphs
  - Subject Domain of Forests
  - Subject Domain of Trees
  - Subject Domain of Binary Trees
  - Subject Domain of Graph Cuts
  - Subject Domain of Graph Minimum Cuts
  - Subject Domain of Graph Maximum Cuts
  - Subject Domain of Graph Cut Space
  - Subject Domain of Graph Splits
- Shurmel Konstantin:
  - Subject Domain of Planar Graphs
  - Subject Domain of Graph Embeddings
  - Subject Domain of Graph Coloring
  - Subject Domain of Directed Graphs
  - Subject Domain of Weighted Directed Graphs
  - Subject Domain of Graph Representation
  - Subject Domain of Graph Properties
  - Subject Domain of Quad Trees
  - Subject Domain of Heaps
- Yakubovskiy Kirill:
  - Subject Domain of Graph Algorithms
  - Subject Domain of Graph Traversal
  - Subject Domain of Shortest Paths
  - Subject Domain of Tree Traversal
  - Subject Domain of Multigraphs
  - Subject Domain of Hypergraphs
