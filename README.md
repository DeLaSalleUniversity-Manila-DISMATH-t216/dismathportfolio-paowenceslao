# dismathportfolio-paowenceslao
dismathportfolio-paowenceslao created by Classroom for GitHub

## Week 1:
- I was introduced to a new and interesting subject called **Discrete Mathematics** or **DISMATH**.
  - A subject that involves logic and proofs.
- I've learned that a proposition is a statement that can either be TRUE (1) or FALSE (0).
- I also learned about **Logical Connectives**. 

  Below is a table about Logical Connectives:

| Logical Symbol  |  Logical Operator     | Shorthand | Formula                                       | Logical Expression            |
| :-------------: |:---------------------:|:---------:|:---------------------------------------------:|:-----------------------------:|
| ¬               | Negation              | not       | val(¬p) = 1 - val(p)                          | ¬p                            |
| ∧               | Conjunction           | and       | val(p ∧ q) = min(val(p), val(q))              | p ∧ q                         |
| v               | Disjunction           | or        | val(p v q) = max(val(p), val(q))              | p v q                         |
| ⊕               | Exclusive disjunction | xor       | if val(p) not equal val(q) = 1, otherwise 0   | p ⊕ q  ≡ (¬p ∧ q) v (p ∧ ¬q)  |
| →               | Conditional           | if, then  | if val(p) ≤ val(q) = 1, otherwise 0           | p → q ≡  ¬p v q               |
| ↔               | Biconditional         | iff       | if val(p) equals val(q) = 1, otherwise 0      | p ↔ q ≡ (p → q) ∧ (q → p)     |

## Week 2:
- I learned about a new topic in DISMATH called **Logical Equivalences**.
- The different kinds of laws used in Logical Equivalences were introduced.
- These laws are: 

|         Name        |                           Equivalence                                 |
|:-------------------:|:--------------------------------------------------------------------: |
|    Identity laws    |                      p ∧ T ≡ p <br> p v F ≡ p                         |
|   Domination laws   |                       p v T ≡ T <br> p ∧ F ≡ F                        |
|    Negation laws    |                     p v ¬p ≡ T <br> p ∧ ¬p ≡ F                        |
| Double negation law |                            ¬(¬p) ≡ p                                  |
|   Idempotent laws   |                       p v p ≡ p <br> p ∧ p ≡ p                        |
|   Commutative laws  |                   p v q ≡ q v p <br> p ∧ q ≡ q ∧ p                    |
|   Associative laws  |       (p v q) v r ≡ p v (q v r) <br> (p ∧ q) ∧ r ≡ p ∧ (q ∧ r)        |
|  Distributive laws  | p v (q ∧ r) ≡ (p v q) ∧ (p v r) <br>  p ∧(q v r) ≡ (p ∧ q) v (p ∧ r)  |
|   De Morgan's laws  |              ¬(p ∧ q) ≡ ¬p v ¬q <br> ¬(p v q) ≡ ¬p ∧ ¬q               |
|   Absorption laws   |                 p v (p ∧ q) ≡ p <br> p ∧ (p v q) ≡ p                  |

- I've also learned about **Propositional Logic** and **Quantifiers**. 
- Propositional Logic deals with proposition as a whole. (Subject + Predicate).
- Quantifiers indicates the generality of an open sentence in which a variable occurs.
- Quantifiers have two classifications, one being Existential Quantifiers (∃x) which means "There exist" and the other being Universal Quantifiers (∀x) which means "For all".

## Week 3:
- During this week, I was introduced to a topic called **Rules of Inference**.
- The Rules of Inferences are:

|          Name          |   Rules of Inference       |            Tautology           |
|:---------------------: |:-------------------------:|:-----------------------------:|
|      Modus Ponens      |       p<br>p→q<br>∴q      |        (p ∧ (p → q)) → q       |
|      Modus Tollens     |     ¬q<br>p→q<br>∴ ¬p     |       (¬q ∧ (p → q)) → ¬p      |
| Hypothetical Syllogism |     p→q<br>q→r<br>∴p→r    |  ((p → q) ∧ (q → r)) → (p → r) |
|  Disjunctive Syllogism |      p∨q<br>¬p<br>∴q      |       ((p ∨ q) ∧ ¬p) → q       |
|        Addition        |       p<br>∴p ∨ q         |           p → (p ∨ q)          |
|      Simplication      |       p ∧ q<br>∴p         |           (p ∧ q) → p          |
|       Conjunction      |      p<br>q<br>∴p ∧ q     |      ((p) ∧ (q)) → (p ∧ q)     |
|       Resolution       | p ∨ q<br>¬p ∨ r<br>∴q ∨ r | ((p ∨ q) ∧ (¬p ∨ r)) → (q ∨ r) |

- We used the different rules of inferences to solve problems such as our homework wherein we have to prove "*Superman doesn't exist!*".
- Our professor also discussed about the different **Methods of Proof** starting with **Direct Proof**.
  - To use this method, first assume that P is true then show that Q is also true.
  - P → Q

## Week 4:
- The second method of proof is **Contraposition** or the **Indirect Proof**.
    - First assume ¬Q is true then show that ¬P must also be true.
    - ¬Q → ¬P
- The third method of proof is **Vacuous Proof**.
  - Show that P is false, because P → Q must be true when p is false.
  - ¬P → (P → Q)
- The fourth method is **Trivial Proof**.
  - Show that Q is true, it follows that P → Q must also be true.
  - Q → (P → Q)
- The fifth method is **Proof by Contradiction**.
  - Assume that the premise is not true, then show that the premise will end up in a contradiction.
- I learned about the definition of a rational number which is {a/b | a, b ∈ ℤ, b≠0, a & b have no common factors other than ±1}.

## Week 5:
- The sixth method was introduced which is **Proof by Equivalence** (Biconditionals).
  - (P ↔ Q) ↔ [(P → Q) ∧ (Q → P)]
  - Show that P → Q and Q → P are both true.
- A new lesson was introduced which is **Mathematical Induction**.
  - There are two steps in applying Mathematical Induction.
    - Basis
      - Show that P(1) or P(0) to be true.
    - Direct Proof
      - Asumme P(k) ≡ T
      - Show P(k+1) ≡ T

## Week 6:
- **Summation** (Σ “sigma”) - notation for sum of _a<sub>m</sub>, a<sub>m+1</sub>, ..., a<sub>n</sub>_ is _∑<sup>a</sup><sub>i=m </sub>a<sub>i</sub>_ where _i_ is the index of summation.
- **Recursive/Inductive Definition**
  - Basis step: specify the value of the function at zero.
  - Recursive step: Find a rule for finding its value at an integer number from the values at smaller integers.
- **Recursive Algorithm** - solves a problem by reducing it to an instance with smaller input.
  - *Algorithm* - finite set of precise instructions for performing a computation/solving a problem.
- **Program Correctness** - to ensure that the program always gives the correct output.
  - *Program Verification* - The program is said to be correct if it produces the correct output for every possible input:
    - Show that the correct answer is obtained if the program terminates (Partial Correctness).
    - Show that the program always terminates.
  - *Partial Correctness* - Two propositions are used to specify what it means for a program to produce the correct output:
    - Initial Assertion - p - gives the properties that the input values must have.
    - Final Assertion - q - gives the properties that the output of the program should have, if the program did what it was told.
- **Hoare Triple** p{S}q
  - S is said to be partially correct with respect to the initial assertion p and the final assertion q if whenever p is true for the input values of S and S terminates, then q is true for the output values of S.
- **Rules of Inference**
 - *Composition Rule* </br>
  p{S1}q </br>
  q{S2}r </br>
  ______________ </br>
   ∴ p{S1;S2)r <br>
  - *Conditional Statements* </br>
  (p ∧ _condition_) {S} q </br>
  (p ∧ _¬condition_) → q </br>
  ________________________________________</br>
    ∴ p {**if** _condition_ **then** _S_} q
  - *If-Else Statement* </br>
  (p ∧ _condition_) {S<sub>1</sub>} q </br>
  (p ∧ _¬condition_) {S<sub>2</sub>} q </br>
  _____________________________________ </br>
    ∴ p {*if* _condition_ *then* _S<sub>1</sub>_ *else* _S<sub>2</sub>_} q
- **Power Series**
  - ∑<sup>∞</sup><sub>n = 0</sub> a<sub>n</sub>x<sup>n</sup> where _a<sub>0</sub>, a<sub>1</sub>, a<sub>2</sub>, ..., a<sub>n</sub>_ is a given sequence of constants, and _x_ is a real variable.
 
  
## Week 7:
- **Introduction to Set Theory** - a set is an unordered collection of distinct objects, which may be anything.
    - {a, b, d, c, f, e}
  - Empty Set { } = ∅ means no elements
    - {∅} not an empty set
  - Set Builder Notation 
    - {x | some property that x satisfies}
  - Membership
    - 1 ∈ {1, 3, 5, 7}
- **Venn Diagram**
- **Set Identities**

|  **Laws**  |  **Identity**  |
| :------: | :-----------------------------: |
|  Identity Laws  |  A ⋂ U ≡ A  <br>  A ⋃ ∅ ≡ A  |
|  Domination Laws  |  A ⋃ U ≡ U  <br>  A ⋂ ∅ ≡ ∅  |
|  Idempotent Laws  |  A ⋃ A ≡ A  <br>  A ⋂ A ≡ A  |
|  Complementation Law  |  (A¯)‾ ≡ A  |
|  Commutative Laws  |  A ⋃ B ≡ B ⋃ A  <br>  A ⋂ B ≡ B ⋂ A  |
|  Associative Laws  |  A ⋃ (B ⋃ C) ≡ (A ⋃ B) ⋃ C  <br>  A ⋂ (B ⋂ C) ≡ (A ⋂ B) ⋂ C  |
|  Distributive Laws  |  A ⋃ (B ⋂ C) ≡ (A ⋃ B) ⋂ (A ⋃ C) <br>  A ⋂ (B ⋃ C) ≡ (A ⋂ B) ⋃ (A ⋂ C)  |
|  De Morgan's Laws  |  (A ⋂ B)‾ ≡ A‾ ⋃ B‾  <br>  (A ⋃ B)‾ ≡ A‾ ⋂ B‾  |
|  Absorption Laws  |  A ⋃ (A ⋂ B) ≡ A  <br>  A ⋂ (A ⋃ B) ≡ A  |
|  Complement Laws  |  A ⋃ A‾ ≡ U  <br>  A ⋂ A‾ ≡ ∅  |

- **Subsets** (⊆) - A set S is a subset of a set T (denotes S ⊆ T) if all elements of S are also elements of T.
- **Power Set** P(S) = {T|T ⊆ S}
- **Cardinality** - the cardinality of a set is the number of element it contains.
- **Functions**
  - Let A and B be sets. A function f from A to B is an assignment of exactly one element of B to each element of A.
  - also called *mappings* or *transformations*.
- **Types of Functions**
    - One - to - one Function (Injection) - functions that never assign the same value to two different domain elements.
    - Onto Function (Surjective) - functions have equal range & co-domain.
    - One - to - one Correspondence (Bijection) - function is both one - to - one and onto.

## Week 8:
- **Algorithms** - A finite set of precise instructions for performing a computation or for solving a problem.
  - *Properties of Algorithms*
    - Input
    - Output
    - Definiteness
    - Correctness
    - Finiteness
    - Generality
- **Pseudocode** 
  - high-level desciption of an algorithm that uses the structural conventions of a programming language.
  - intended for human reading
  - Preconditions - statements that describe valid input.
  - Postconditions - conditions that the output should satisfy when the program has run.

## Week 9:
- **Searching Algorithms** - the problem of locating an element in an ordered list.
  - *Linear Search* -  finding a particular value in a list that checks each element in sequence until the desired element is found.
  - *Binary Search* - comparing the middle values of a list then repeated until the desired output is found.
- **Sorting Algorithms** - the problem of assorting elements into increasing order.
  - *Bubble Sort* - compares the first two elements then interchanging them if they are in the incorrect order.
  - *Insertion Sort* - compares the second element with the first and inserts it before the first element if it is less. Otherwise, it is inserted after the first element.
- **Greedy Algorithms** - algorithms that make what seems to be the "best" choice at each step. Selects the best choice at each step, instead of considering all sequences of steps that may lead to optimal solution.
- We started discussing *Growth of Functions*
 
## Week 10:
- **Growth of Functions**
  - *Big-O Notation*
    - Let f and g be functions from R-R; _f(x)_ is _O(g(x))_ if there are constants C and k such that: *"|f(x)| ≤ C|g(x)|"* whenever x > k.
    - Constants _C_ and _k_ are called witnesses.
  - *Big-Omega and Big-Theta Notation*
    - Big-O Notation does not provide a lowerbound for the size of f(x). 
      - Big-Omega (Big-Ω) - lower bound
      - Big-Theta (Big-Θ) - both upper and lower bound
- **Algorithm Time Complexity** - can be expressed in terms of the number of operations used by the algorithm when the input has a particular size.
- **Division and Modulo Operator**
  - let a be an integer and d positive integer. Then there is a unique Q and r with 0 ≤ r < d such that a = dQ + r.
  - Q = a div d
  - r = a mod d

## Week 11:
-No classes because of Holy Week

## Week 12:
- **Graph Theory**
  - Graph - discrete structures consisting of vertices and edges that connect these vertices.
  - A graph G = (V,E) consists of V, a nonempty set of *vertices* (or nodes) and E, a set of *edges*. Each edge has either one or two vertices associated with it, called its *endpoints**.
  - Applications
    - Networks (LAN, MAN, Social Networks, etc.)
    - Job assignments
    - Representing computational models
    - Developing a bot to retrieve info off www

- **Hand shaking theory**
    2e = ∑deg(v)

  - *Path* - sequence of edges that begins at a vertex of a graph and travels from vertex to vertex along edges of the graph.
  - *Euler Circuit* - a simple circuit containing every edge of a graph. (All vertices have an even number of degree)
  - *Euler Path* - simple path containing every edge of a graph. (Exactly 2 vertices have an odd number of degree)
  - *Hamilton Path* - a simple path that passes through every vertex exactly once.
  - *Hamilton Circuit* - a simple circuit that passes through every vertex exactly once which ends up in the same place in which it began.

- **Matrices of Graphs** 
  - 1 for adjacent; 0 for non-adjacent
- **Incidence of Matrices** 
  - a matrix between the vertices and the edges.

- **Isomorphism of Graphs** 
  - a simple graph is isomorphic if it has a one-to-one and onto function.
  - i.e. vertices change positions and still have the same connection as before.

- **Planar Graph**
  - Graphs that can be drawn in the plane without edges having to cross.
  - Euler's Formula: r = e - v + 2
    - r - regions
    - e - edges
    - v - vertices
  - Euler's Characteristic: ℵ = r - |e| + |v| where ℵ = 2

- **Homeomorphic Graphs**
  - Graphs are called homeomorphic if they can be obtained from the same graph by a sequence of elementary subdivisions.
  - *Elementary Subdivision* - If a graph is planar, so will be any graph obtained by removing an edge and adding a new vertex together with edges.
  - *Kuratowski's Theorem* - a graph is nonplanar if and only if it contains a subgraph homeophobic to K3,3 and K5.

## Week 13:
- **Graph Coloring** - assignment of a color to each vertex of the graph so that no two adjacent vertices are assigned the same color.
  - *Four Color Theorem* - the chromatic number of a planar graph is no greater than four.

- **Trees**
  - A connected undirected graph with no simple circuits.
  - A data structure that emulates a heirarchical tree structure with a set of linked nodes.
  - Used to construct efficient algorithms for locating an item in a list.
  - Multiple *Trees* are called **Forest**.
  - *Rooted Tree* - a tree in which one vertex has been designated as the root and every edge is directed away from the root.
    - Root - the beginning of a tree
    - Internal vertices - every vertex before the leaves
    - Leaves - vertices with no descendants
  - *M-ary tree*
    - A rooted tree is called an m-ary tree if every internal vertex has no more than m children.
    - An m-ary tree with m = 2 is called a *binary tree*

- **Modeling Computations**
  - *Language and Grammars*
    - Grammars - used to generate the words of a language and to determine whether a word is in a language
    - Compiler - reads a program written in a source language and translate it into an equivalent program in a target language.
      - Formal Language - automatic translation of one language to another
        - well defined set of rules

- **Alphabet & String**
    - common way to talk about words, numbers, etc.

- **Automata Theory**
    - Studies the law of computation
    - Finite Automata - simplest model of automata
      - initial state
      - final state
      - dead/stuck state
      - transition state

- **Lexical Analysis**
    - process where the stream of characters making up the source program into a sequence of "words" that make up the source code.

- **Finite State Machine**
  - S: Finite set of states
  - I: Finite input alphabet
  - O: Finite output alphabet
  - f: Transition function
  - g: Output function
  - s<sub>0</sub>: Initial state

- **Turing Machine**
    - Alan Turing, the father of computer science.
    - "Imitation Game" movie based on his life.
