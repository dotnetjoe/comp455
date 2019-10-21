1. Consider the deterministic finite automaton (K, Σ, δ, s, F) where K = {p, q, r}, Σ = {a, b, c}, s = p, F = {q} and δ is given by the following chart: 

	| x 	| y 	| δ(x,y) 	|
	|---	|---	|:------:	|
	| p 	| a 	| q      		|
	| p 	| b 	| q      		|
	| p 	| c 	| r      		|
	| q 	| a 	| r      		|
	| q 	| b 	| p      		|
	| q 	| c 	| p      		|
	| r 	| a 	| r      		|
	| r 	| b 	| r      		|
	| r 	| c 	| r      		|

	Find a regular expression for the language recognized by this automaton.
