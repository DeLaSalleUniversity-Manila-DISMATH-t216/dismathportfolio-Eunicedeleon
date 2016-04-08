# dismathportfolio-Eunicedeleon
dismathportfolio-Eunicedeleon created by Classroom for GitHub
##WEEK 1

- I was introduced to Discrete Mathematics: what it is and what it is used for.
- I was introduced to all the topics that will be discussed during the whole term.
- Learned about propositions and the use of logical deduction.
- Learned how to determine truth values and make a truth table.
- Learned different symbols used in logic:

| Logical Symbol  |  Logical Operator | Usage | For Truth Tables |
| :-----: |:-------:|:-----:|:-----:|
| ¬ |Negation | not | subtract 1|
| ∧ | Conjunction | and | min, multiplication |
| ∨ | Disjunction | or | max, addition |
| ⊕ | Exclusive disjunction | xor | 
| → | Conditional | if, then |
| ↔ | Biconditional | iff |


##WEEK 2

- Learned about **Logical Equivalences** and how to use them to prove propositions.
  
  ![12696464_10204392522173537_1769547281_o](https://cloud.githubusercontent.com/assets/16644615/12865814/852d56c8-ccf2-11e5-9c35-30a761e1a0a1.jpg)

- Learned about **Quantifiers**

  ![12665826_10204392522213538_1479020879_n](https://cloud.githubusercontent.com/assets/16644615/12865813/84f9c812-ccf2-11e5-97e6-2b09a6ec637a.jpg)
  
- Learned about the **Rules of Inference**:
  
  ![12647903_10204392522733551_941197840_n1](https://cloud.githubusercontent.com/assets/16644615/12865855/ce9dc666-ccf3-11e5-89a4-980c634408c9.jpg)

- Learned how to use the Rules of Inference to prove a set of arguments.
- Learned that it is easier to use Rules of Inference than using Truth Tables when dealing with many variables.

##WEEK 3

- Learned about the different types of proofs:
 - **Direct Proof** (p→q) 
   - Step 1: Assume p is true
    - Step 2: Show q is true
 - **Proof by Contraposition** (¬q→¬p)
   - Step 1: Assume ¬q is true
    - Step 2: Show ¬p is true
 - **Vacuous Proof** (¬p→(p→q)) 
   - Step 1: Show that p is false
 - **Trivial Proof** (q→(p→q))
   - Step 1: Show that q is true
 - **Proof by Contradiction** (p) 
   - Step 1: Show that assuming ¬p(whole premise) is true leads to a contradiction 
 - **Proof by Equivalence** (p↔q)
   - Step 1: Show that p→q and q→p are both true
 - **Mathematical Induction**
   - Step 1: Substitution (Basis) 
    - Step 2: Direct Proof (Inductive) 

##WEEK 4

- I got reminded of Summation
- Learned more about proofs through the excercises we did
- Learned about **Recursive Proofs**
  - Step 1: Basis (specify value) 
  - Step 2: Recursive

##WEEK 5
- Learned about Partial Correctness
- Learned how to use the Hoare Triple: p{S}q
- Learned about the functions as Power Series
- Learned about sets and sets theory
  - Membership
  - Set Builder Notation
  - Venn Diagrams
  - Power Set

##WEEK 6
- Learned more about sets
  - Cardinality
  - Functions
    - Domain
    - Co-domain
    - Range

##WEEK 7
- Learned about algorithms
  - how to make pseudocodes
  - Iteration tables 
- Properties of Algorithms 
  - precondition
  - postcondition
  - input
  - output
  - definiteness
  - correctness
  - finiteness
  - generality
- Learned how linear search works and its pseudocode
- Learned how binary search works and its pseudocode

##WEEK 8
- Learned about sorting algorithms
  - insert sort and its pseudocode
  - bubble sort and its pseudocode
  - greedy algorithm

##WEEK 9
- Learned about growth of functions:
  - Big-O which is the upper bound
  - Big-Omega which is the lower bound 
  - Big-Theta which is both lower and upper bound
- Learned about Algorithm Time Complexity
- Caesar Cipher

##WEEK 10
- Learned about graph theory
  -  **Graphs** - Discrete structures consisting of vertices and edges that connect the vertices
  -  **Vertex** 
  -  **Degree of a vertex** - number of edges incident with the vertex
  -  **Handshaking theorem**
  -  **Simple graphs** Kn - one edge between each pair of vertices
  -  **Cycles** Cn
  -  **Wheels** Wn
  -  **Subgraphs**
  -  **Union of graphs**
  -  **Intersection of graphs**
  -  **Path** - sequence of edges and travels from vertex to vertex
  -  **Euler Circuit and Path** - simple circuit containing every edge
      - if the graphs vertices have even degrees, it has an Euler cricuit
      - 2 vertices of odd degree = Euler path
  -  **Hamilton Circuit and Path** - passes through every vertex once
      -3 pendants = no path or circuit 
  -  **Matrices of graphs**
      -  Adjacency Matrix
      -  Incidence Matrix
  -  **Isomorphism of graphs** - graphs are isomorphic iff there is a one-to-one and onto function f from V1 to V2
  -  **Planar Graphs** - graphs that can be drawn in the plane without edges having to cross
  -  **Euler's formula**
  -  **Homeomorphic Graphs**
      - **Elementary Subdivision** - if a graph is planar, so will be any graph obtained by removing an edge and adding a new vertex
      - **Homeomorphic** - graphs can be obtained from the same graph using elementary subdivision
  -  **Kuratowski's Theorem** - a graph is non-planar iff it contains a subgraph homeomorphic to:
