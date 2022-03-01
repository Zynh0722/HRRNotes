alias:: Hoisting, Variable Hoisting

- > var message = 'I <3 javascript';
  > 
  > var f = function() {
  > 
  >     console.log(message);
  >     var message = 'this is a cool message';
  > };
  > 
  > f();
	- Prints 'undefined'
- ## This is due to Variable Hoisting
	- In the JS interpreter, the code looks more like
- > var message, f;
  > 
  > message = 'I <3 javascript';
  > 
  > f = function() {
  >     var message;
  >     console.log(message);
  >     message = 'this is a cool message';
  > };
  > 
  > f();
-
- id:: 6216783a-8b6d-4948-9097-c6c9541d96ba
  #+BEGIN_CENTER
  variables initialized with the var keyword, are always initialized at the top of **local** scope. 
  #+END_CENTER