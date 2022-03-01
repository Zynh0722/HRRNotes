- Linked lists are similar to Arrays.
	- However the data is stored **non-contiguously**
	- Values are stored in nodes
		- A node is a value, with a reference to the next node
-
- Based on [[Complexity Analysis]]:
	- For a Linked List, what is the time complexity of retrieving a value at a given position? #card
	  card-last-score:: 5
	  card-repeats:: 1
	  card-next-schedule:: 2022-03-01T17:48:27.728Z
	  card-last-interval:: 4
	  card-ease-factor:: 2.6
	  card-last-reviewed:: 2022-02-25T17:48:27.730Z
		- O(n)
	- For a Linked List, what is the time complexity of assigning a value at a given position? #card
		- O(n)
	- For a Linked List, what is the time complexity of inserting a value at a given position? (insert)  #card
		- O(1)? but also O(n)?
			- most often when inserting a value you already have a reference to the position you are inserting at, making it O(1), although with no prior information it will be O(n)
	- For a Linked List, what is the time complexity of removing a value at a given position? (splice) #card
		- Head: O(1)
		- Middle: O(n)
	- For a Linked List, what is the time complexity of finding a value in an Array by its value? #card
		- O(n)