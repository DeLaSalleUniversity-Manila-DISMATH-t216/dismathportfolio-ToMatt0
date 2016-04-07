# dismathportfolio-ToMatt0
dismathportfolio-ToMatt0 created by Classroom for GitHub

Author: Matthew Gonzales
ID: 11402725
(FEEL FREE TO BROWSE AND/OR COPY)
(?) - Signifies an unanswered question

#Week 1


####user log
I'm a bit intimidated by this type of subject, but excited by what kind of logical "puzzles" 
we'll be encountering next. I hope that my morning grogginess wont get in the way of my
focus, either. It seems I will require to gather my attention for these lectures.


####learning log 
- importance of order of symbols in creating conditions and propositions.
- combination of symbols having different meanings.

- a mathematical proof is an argument that is proved with theorems and principles that have already been established.
- a proposition is "a chain of logical deductions leading to the proposition from a base set of axioms."

- logical connectives can be described as symbols that unite propositions.
- truth tables is a tool that can use to understand logical connectives.

![img](http://image.slidesharecdn.com/lecture1dsiwarislogic-150919223941-lva1-app6891/95/discrete-structure-lecture-no-1-20-638.jpg?cb=1442702579)

#Week 2

####user log
We're finally picking up momentum as we go deeper into the DISMATH concepts. 
We have a lot of catching up to do, though... 


####learning log 
- a lot of what we learn will be similar to that in logic circuits
- YOU NEED to take notes in this class

- logical equivalences, along, with truth tables are tools in mathematical logic that allow us to analyze statements.

- Existential Quantifiers are true if "there exist of value for which the proposition it is attached to is true."
- Universal Quantifiers are true if "the proposition is true for every value."

- Existential Quantifiers are false if "there is no value for which the proposition it is attached to is true."
- Universal Quantifiers are false if "the proposition is false for every value".

- A fallacy leads to invalid arguments. 
- Valid arguments are not necessarily true.

![img](http://www.csitschools.com/wp-content/uploads/2015/08/Capture39.jpg)
![img](http://lh3.ggpht.com/-NfwPPequ40g/Td_EbcwizXI/AAAAAAAAAGA/ECeOpZBBPnw/image_thumb%25255B67%25255D.png?imgmax=800)

#Week 3

####user log

This week, we learned the rules of inference and continued our discussion about arguments.

####learning log
- we create atomic propositions by assigning symbols and letters to propositional statements.
- a tautology is a rule of replacement that is used to replace redundant expressions (?)
- we learned the various rules of inference

![img](http://images.slideplayer.com/11/3241425/slides/slide_2.jpg)

- Statements in the English language are difficult to analyze logically in some cases, because the definition may be ambiguous.
- we "proved" that Superman does not exist using atomic propositions and rules of inference.

[HELPFUL LINK]: http://www.philosophypages.com/lg/e11a.htm


#Week 4

| Methods of Proving ||
| :-----: |:-------:|
| Direct Proof | Assume **P** to be **true**, then prove **Q** |
| Contraposition | Assume **¬Q** to be **true**, then prove **¬P**|
| Vacuous or Trivial Proof | Proven by implications of truth |                                    

- We have seen that Proof by Contraposition is a result of the logical equivalence of P → Q, which is ¬Q → ¬P.
- A trivial proof is such that is proven by an implication of the antecedent's truth value.
- A vacuous proof is such that is proven by an implication of the precedent's truth value.


#Week 5
| Methods of Proving ||
| :-----: |:-------:|
| Proof of Equivalence | For P ↔ Q,  prove **P → Q**, and **Q → P** |
| Contradiction | Assume **P** to be **false** and then seek a contradiciton |
| Mathematical Induction | Example: Start with a Basis, then show that P(k+1) is equivalent to P(k)+P(1)|

- Learned that to prove a proof by equivalence "p ↔ q" , you must prove that p implies q AND q implies p.
- Learned Recursive/Inductive Definition.
- (Inductive Definition) The Basis Step of Inductive Definition is "find the value of the function at **0**."
- (Inductive Definition) The Recursive Step of Inductive Definition is "give a general rule for finding the result of the function."


#Week 6

- Discussed sets, which was also the first topic in our ENGSTAT course.
- Cardinality is the number of members of a set


| Methods of Proving ||
| :-----: |:-------:|
| Union of Sets | ∨ |
| Intersection of Sets | ∧ |
| Set Differnece A/B  | Members of A that are not in B |
| Symmetric Difference AΔB | (Members of A that are not in B) ∨ (Members of B not in A) |


![img](http://cat4mba.com/Notes/Maths/settheroy/ven.gif)


#Week 7

- a function describes a relationship between elements of two sets
- an image is a subset of a function's codomain and a preimage is the set of elements that are assigned to elements of the codomain
- a codomain describes all possible output, BUT the range is the set of occuring elements.
- the range is a subset of the codomain


| Types of Functions ||
| :-----: | :-------: |
| Injective | One-to-One |
| Surjective | Onto |
| Bijective  | One-to-one correspondence |

![img](http://www.cs.odu.edu/~cs381/cs381content/relation/figures/function3.gif)



#Week 8
- Existing knowledge in programming will help you better understand how to make pseudocode
- Algorithms receive input, perform a procedure, and generate an output
- Any algorithm should be designed to be **definite, finite and general**
- Most of the algorithms we are discussing aim to solve simple problems by providing a definite procedure.
- In the words of Sir Mallari "Computers are "dumb". You have to tell them **exactly** what to do." 


#Week 9
- We learned about **linear search and binary search**
- We have implemented linear search in the past during our C programming classes
- Also learned about **insertion and bubble sort**
- A bubble sort is called that way because larger values "bubble up" or float to the top.
- A greedy algorithm is one that selects the most favorable selection at each "stage."

| Search Algorithms ||
| :-----: | :-------: |
| Linear | Algorithms searches for the first occurance |
| Binary | Algorithm compares the input to the median value and repeats this until it is found |

| Sorting Algorithms ||
| :-----: | :-------: |
| Insertion | Inserts the value in the correct position after making comparison with elements in the list |
| Bubble | Large values "float" to the top, while small values "sink" to the bottom of the list |


#Week 10

- We discussed growth of functions
- The efficiency of an algorithm can drastically change for larger inputs.
- We defined each program or algorithm to have a complexity determind by the number of operations it executes given a certain number of input.

- A less complex algorithm is **often** favored over more complex algorithm.

- If f is of order at least g, then f(x) is Ω(g(x)) iff C|g(x)| <= |f(x)| for all x > k
- If f is of order at most g, then f(x) is O(g(x)) iff C|g(x)| >= |f(x)| for all x > k
- If f is of order g, then f(x) is O(g(x)) iff A|g(x)| <= |f(x)| <= B|g(x)| for all x > k
- C and k are called "witnesses."

![img](http://i.stack.imgur.com/5eFMU.png)

#Week 11

- A degree of a vertex in an undirected graph is the number of edges incident with it.
- Two points in a graph are adjacent if they are endpoints of an edge in the graph
- A subgraph of graph G=(V, E) is a graph that contains vertices and edges that are subsets of the sets of vertices and edges of the graph.
- The union of two graphs contains the vertices and edges of both graphs.


| Some types of graphs ||
| :-----: | :-------: |
| Complete | |
| Cycle |  |
| Wheel | |


| Euler ||
| :-----: | :-------: |
| Path | path containing every edge |
| Circuit | circuit containing every edge |

| Hamiltonian ||
| :-----: | :-------: |
| Path | Passess every vertex exactly once |
| Circuit | Passes every vertex exactly once and returns to the starting point |

- A Petersen graph has a hamilton path but not a circuit.
