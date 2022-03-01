- Functions bind to the context in which they are called, not where they are passed
- ```
  window.name = 'window';
  
  var alice = {
  	name = 'alice',
      speak = function () {
      	console.log(this.name);
      }
  }
  
  alice.speak(); // prints 'alice'
  setTimeout(alice.speak, 1000); // prints 'window' after 1 second
  ```
-
- Ways to bind a this context
	- `function.bind(thing to bind to, ...args)``
	- `function.call(thing to bind to, ...args)`
	- `function.apply(thing to bind to, arguments)`