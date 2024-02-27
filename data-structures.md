# Data Structures

## Sets

A set is an unordered collection of distinguishable elements.

### Equality

Two sets are equal if they contain the same elements.

### Empty Set

An empty set contains no elements and is denoted by the symbol ∅.

### Subset

If all the elements of a set A are contained in set B, then A is a subset of B. This relationship is denoted by: $` A \subseteq B `$

### Proper Subset

Set A is a proper subset of B if A and B are not equal. A proper subset relationship is denoted as: $` A \subset B `$

### Cardinality

The cardinality of a set is the number of elements within a set, for a set S this is denoted by: $` |S| `$

#### Finite Set

A set is finite if its cardinality is a natural number. (Some may quibble regarding whether zero is a natural number.)

#### Infinite Set

A set is infinite if its cardinality is not a natural number.

##### Countably Infinite

An infintie set is countably infinite if its elements can be put into a one-to-one mapping to the natural numbers.

##### Uncountable

An infinite set is uncountable if its elements cannot be put into a one-tp-one mapping to the natural number.

### Cartesian Product

The Cartesian product of two sets A and B, denoted by $` A \times B `$, is the set of all ordered pairs such that the first element of the pair is an element of A and the second element of the pair is an element of B.

$` A \times B = {(a, b): a \in  A  \space and \space b \in B} `$

### Binary Relation

A binary relation is a subset of the Cartesian product of two sets. For a binary relation R where $` (a, b) \in R `$, the binary relation can be denoted as: $` aRb `$

## Sequences

A sequence is an ordered collection of elements.

## Graphs

Graphs are collections of related vertices and edges. Theses collections are known as the vertex set and edge set.

### Directed Graph

A directed graph is a collection of vertices and edges where the vertex set is a finite set and the edge set is a binary relation on the vertex set. Which is to say that, the edges specify an source vertex and target vertex. 

Self-loops, an edge from one vertex to the same vertex, are permissable.

### Undirected Graph

An undirected graph is a graph wherein the edges have no concept of source and target vertex. Two verticies have are connected or not with no directionality.

### Incident Edges

In directed graphs, we can say that an edge is _incident from_ the source vertex and and _incident to_ the target vertex. It can alternative be said, an edge leaves the source vertex and enters the target vertex. In an undirected graph, an edge can be said to be _incident on_ a pair of vertices.

### Neighbors

A neighbor of a vertex is any other vertex connected by an edge. In a directed graph neighbor status is irrespective of directionality of the edge.

### Adjacency

In an undirected graph two vertices are adjacent if they are neighbors and the adjacency relationship is symmetric.

In a directed graph the adjacency relationship need not be symmetric. A vertex A is adjacent to vertex B if there is an edge incident from vertex B that is incident to vertex A.

### In-Degree

In a directed graph the in-degree is the number of edges incident on it.

### Out-Degree

In a directed graph the out-degree is the number of edges incident from it.

### Degree

In an undirected graph the degree of a vertex is the number of edges incident on it.

The degree of a directed graph is the sum of its in-degree and out-degree.

### Path

A path is a sequence of vertices for which there exist incident edges that allow traversal from the first vertex in the sequence to the last.

#### Path Length

The length of a path is the number of incident edges required to traverse the path.

#### Reachable

Vertex B is reachable from vertex A if there is a path from A to B.

#### Simple

A path is simple if all of the verticies in the path are distinct.

#### Subpath

A subpath of a path is a contiguous subsequence of the vertices in the path.

