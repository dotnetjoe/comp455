## Assignments

### HW1
1. True or false:
	- {{a, b}} ⊆ {{a, b, c}}
	- {{a, b}, {b, a, c}} = {{b, a}, {c, c, a, b}, {a, a, b}}
	- {a, c} ∈ {{a, b}, c, {a, c}}
2. Compute the result of these operations:
	- ({a, b} ∪ {b, c}) ∩ {a, c, d}
3. Compute the result of this composition of two relations:
	- {(a, b),(b, c),(a, d)} ◦ {(b, c),(c, d),(b, f),(d, f)}

### HW2
1. Give a regular expression for the set of strings over {a, b, c} such that the sum of the number of a’s and the number of b’s is equal to 3.

### HW3
1. Construct a deterministic finite automaton accepting all and only strings in the language represented by the following regular expression: ((aa ∪ bb)c)\*

### HW4
1. Consider the deterministic finite automaton (K, Σ, δ, s, F) where K = {p, q, r}, Σ = {a, b, c}, s = p, F = {q} and δ is given by the following chart: 

	| x 	| y 	| δ(x,y) 	|
	|---	|---	|:------:	|
	| p 	| a 	| q      	|
	| p 	| b 	| q    	|
	| p 	| c 	| r    		|
	| q 	| a 	| r    		|
	| q 	| b 	| p    	|
	| q 	| c 	| p    	|
	| r 	| a 	| r    		|
	| r 	| b 	| r    		|
	| r 	| c 	| r    		|

	Find a regular expression for the language recognized by this automaton.

### HW5
1. Construct a context-free grammar generating all the strings in the following language, and no others: 
	{a<sup>m</sup>b<sup>n</sup>c<sup>p</sup>d<sup>q</sup> : m ≠ n, p ≠ q}
