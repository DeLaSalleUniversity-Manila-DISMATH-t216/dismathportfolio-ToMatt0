# dismathportfolio-ToMatt0
dismathportfolio-ToMatt0 created by Classroom for GitHub

Author: Matthew Gonzales
ID: 11402725

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


#Week 3

####user log
This week, we finally had a glimpse of what problems in the exam would be like.
It is imperative that we learn to hone our analysis skills and be more observant of the
tiny details in statements. 

####learning log 
-  Quantifiers are true if "there exist."
- Universal Quantifiers are true if "all exist."

- Existential Quantifiers are false if "none exist."
- Universal Quantifiers are false if a single value is false.

- A fallacy leads to invalid are=guments. 
- Valid arguments are not necessarily true.
