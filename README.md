# Context-Free-Grammars-Epsilon-Unit-Rules-Elimination
For this task you will implement the algorithms for eliminating epsilon and unit rules from a given context-free grammar (CFG). Recall that a CFG is a quadruple (V, Σ, R, S) where V and Σ are disjoint alphabets (respectively, containing variables and terminals), R ⊆ V × (V ∪ Σ)∗ is a set of rules, and S ∈ V is the start variable.

Requirements:I should implement a class constructor CfgEpsUnitElim,and three methods;toString,
eliminateEpsilonRules, and eliminateUnitRules.

1. CfgEpsUnitElim, a class constructor, takes one parameter which is a string description of a CFG and constructs a CFG instance. A string encoding a CFG is of the form V #T #R.

2. toString returns a string representation of a CFG. This string representation is the same as the one used for the input to the constructor.

3. eliminateUnitRules eliminates unit rules from the constructed CFG using the classical algorithm.
