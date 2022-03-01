- # Big O
	- gives an approximation of time complexity
	- worst case scenario of an algorithm
	- fuzzy, drop all constants and coefficients
-
- Determining complexity type
	- Ignore leading constants
		- For a large n the order of the function has a bigger effect than coefficients
		- O(n)
			- 2n
			- 5n
			- n
		- O(n^2)
			- 3n^2
			- 6n^2
	- Complexity is determined by the highest order function
		- Highest order = fastest growing function
- | Name | Constant | Logarithmic | Linear | Quadratic | Exponential |
  | ---------------------------------------------------- |
  | Notation      | O(1)  | O(log n) | O(n) | O(n^2) | O(c^n) |