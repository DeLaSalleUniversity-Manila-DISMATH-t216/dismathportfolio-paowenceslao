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

|          Name          |   Rule of Inference       |            Tautology           |
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

## Week 5
- The sixth method was introduced which is **Proof by Equivalence** (Biconditionals).
  - (P ↔ Q) ↔ [(P → Q) ∧ (Q → P)]
  - Show that P → Q and Q → P are both true.
- A new lesson was introduced which is **Mathematical Induction**.
  - There are two steps in applying Mathematical Induction.
    - Basis
      - Show that P(1) or P(0) to be true
    - Direct Proof
      - Asumme P(k) ≡ T
      - Show P(k+1) ≡ T
