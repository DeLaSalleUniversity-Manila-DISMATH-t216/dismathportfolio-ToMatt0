# dismathportfolio-ToMatt0
dismathportfolio-ToMatt0 created by Classroom for GitHub

Author: Matthew Gonzales
ID: 11402725
(FEEL FREE TO BROWSE AND/OR COPY)
(?) - Signifies an unanswered question

#Week 1


####user log
I'm a bit intimidated by this type of syntax, but excited by what kind of logical "puzzles" 
we'll be encountering next. I hope that my morning grogginess wont get in the way of my
focus, either. It seems I will require to gather my attention for these lectures.


####learning log 
- importance of order of symbols in creating conditions and propositions.
- combination of symbols having different meanings.

| Logical Symbol  |  Logical Operator | Shorthand | Formula | Logical Expression |
| :-----: |:-------:|:-----:| :-------: | :-------: |
| ¬ |Negation | not | val(¬p) = 1 - val(p) | ¬p |
| ∧ | Conjunction | and | val(p ∧ q) = min(val(p), val(q)) | p ∧ q |
| ∨ | Disjunction | or | val(p v q) = max(val(p), val(q)) | p v q |
| ⊕ | Exclusive disjunction | xor | if val(p)  not equal val(q) = 1 , otherwise  0|  p ⊕ q  ≡ (¬p ∧ q) v (p ∧ ¬q) |
| → | Conditional | if, then | if val(p)  ≤ val(q) = 1 , otherwise  0  | p → q ≡  ¬p v q |
| ↔ | Biconditional | iff | if val(p) equals val(q) = 1 , otherwise  0 |  p ↔ q ≡ (p → q) ∧ (q → p) |
###(taken from biancacamille)

#Week 2

####user log
We're finally picking up momentum as we go deeper into the DISMATH concepts. 
We have a lot of catching up to do, though... This much is certain


####learning log 
- truth tables
- logical connectives
- a lot of what we learn will be similar to that in logic circuits
- YOU NEED to take notes in this class
- logical equivalences are laws that are similar to basic arithmetic.

-  Quantifiers are true if "there exist."
- Universal Quantifiers are true if "all exist."

- Existential Quantifiers are false if "none exist."
- Universal Quantifiers are false if a single value is false.

- A fallacy leads to invalid arguments. 
- Valid arguments are not necessarily true.
- 
| Name |||
| :-----: |:-------:|:-----:|
| Identity Laws | p ∨ F ≡ p | p ∧ T ≡ p |
| Domination Laws| p ∨ T ≡ T | p ∧ F ≡ F |
| Negation Laws| p ∧ ¬p ≡ F | p ∨ ¬p ≡ T |                                            
| Double Negation Laws | (¬(¬p) ≡ p) |                                                           
| Idempotent Laws| p ∨ p ≡ p | p ∧ p ≡ p |                                              
| Commutative Laws | p ∨ q ≡ q ∨ p | p ∧ q ≡ q ∧ p |                                       
| Associative Laws | (p ∨ q) ∨ r ≡ p ∨ (q ∨ r) | (p ∧ q) ∧ r ≡ p ∧ (q ∧ r) |            
| Distributive Laws | p ∨ (q ∧ r) ≡ (p ∨ q) ∧ (p ∨ r) | p ∧ (q ∨ r) ≡ (p ∧ q) ∨ (p ∧ r) |  
| De Morgan's Laws| ¬(p ∧ q) ≡ ¬p ∨ ¬q | ¬(p ∨ q) ≡ ¬p ∧ ¬q |                        
| Absorption Laws | p ∨ (p ∧ q) ≡ p | p ∧ (p ∨ q) ≡ p |          
###(taken from biancacamille)

#Week 3

####user log

This week, we learned the rules of inference and continued our discussion about arguments.

####learning log
- atomic propositions, or assigning symbols and letters to propositional statements allows us to simplify tasks.
- a tautology is a rule of replacement that is used to replace redundant expressions (?)


| Rules of Inference (My way of remembering) ||
| :-----: |:-------:|
| Modus ponens | Is, therefore |
| Modus tollens | Is not, so |
| Hypothetical Syllogism | Your front is my back |                                    
| Disjunctive Syllogism | Not this, so this |                                                    
| Addition |  Out of the blue |                                           
| Simplification |  The truth's in the p |                                   
| Conjunction | Put em' together | 
| Resolution |  If you're not taking it, I will |


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
| Mathematical Induction | Start with a Basis, then show that P(k+1) is equivalent to P(k)+P(1)|

- Learned that to prove a proof by equivalence "p ↔ q" , you must prove that p implies q AND q implies p.
- Learned Recursive/Inductive Definition.
- (Inductive Definition) The Basis Step of Inductive Definition is "find the value of the function at **0**."
- (Inductive Definition) The Recursive Step of Inductive Definition is "give a general rule for finding the result of the function."


#Week 6

- Discussed sets, which was also the first topic in our ENGSTAT course.


| Methods of Proving ||
| :-----: |:-------:|
| Union of Sets | ∨ |
| Intersection of Sets | ∧ |
| Set Differnece A/B  | Members of A that are not in B |
| Symmetric Difference AΔB | (Members of A that are not in B) ∨ (Members of B not in A) |


![img](http://cat4mba.com/Notes/Maths/settheroy/ven.gif)


#Week 7


