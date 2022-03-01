alias:: Variable Hoisting

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