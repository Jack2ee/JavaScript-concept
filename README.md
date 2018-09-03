# JavaScript-concept

#### Promise
0 FROM MDN:
A Promise is a proxy for a value not necessarily known when the promise is created. It allows you to associate handlers with an asynchronous action's eventual success value or failure reason. This lets asynchronous methods return values like synchronous methods: instead of immediately returning the final value, the asynchronous method returns a promise to supply the value at some point in the future.

A Promise is in one of these states:

pending: initial state, neither fulfilled nor rejected.
fulfilled: meaning that the operation completed successfully.
rejected: meaning that the operation failed.
A pending promise can either be fulfilled with a value, or rejected with a reason (error). When either of these options happens, the associated handlers queued up by a promise's then method are called. (If the promise has already been fulfilled or rejected when a corresponding handler is attached, the handler will be called, so there is no race condition between an asynchronous operation completing and its handlers being attached.)

As the Promise.prototype.then() and Promise.prototype.catch() methods return promises, they can be chained.
https://mdn.mozillademos.org/files/15911/promises.png

1 한글:
https://jdub7138.blog.me/221064769867


#### Const
a JavaScript keyword that creates a new variable with a value that CANNOT change;
#### Let
a JavaScript keyword that creates a new variable with a value that CAN change;
#### Undefined
a space for variables that are not assigned a value;
#### Arrow Functions
the syntax indicating the variable stores a function;
#### Parameters
variables in a function definition that represent data we can input into the function;

#### Array Methods
0. forEach(): will execute the same code on each element of an array;
1. map(): returns a new array with elemnets that have been modified by the code in its block(forEach() does not return a new array) --> So, new variable needed against a new array;
2. reduce(): applies a function against an accumulator and each element in the array(from left to right) to reduce it to a single value;
3. filter(): creates a new array with all elements that pass the test implemented by the provided function(returns a new array, returning certain elements from the original array that evaluate to truthy based on conditions written in the block of the method);
4. slice(): returns a shallow copy of aportion of an array into a new array object selected from begin to end(end not included);
5. splice(): changes the contents of an array by removing existing elements and/or adding new elements;
6. shift(): removes the first element from an array and returns that removed element;
7. unshift(): adds one or more elements to the beginning of an array and returns the new length of the array;
8. join(): joins all elements of an array into a string and returns this string;
9. some(): returns TRUE when at least one element in an array is true;
10. every(): tests whether all elements in the array pass the test implemented by the provided function, and if all elements pass the test , return true;

#### Object Methods
0. Object.entries(): method returns an array of a given object's own enumerable property [key, value] pairs, in the same order as that provided by a for...in loop (the difference being that a for-in loop enumerates properties in the prototype chain as well);
1. Object.assign(): method is used to copy the values of all enumerable own properties from one or more source objects to a target object. It will return the target object

#### Spread Operator (Array/Object Spread)
Spread syntax allows an iterable such as an array expression or string to be expanded in places where zero or more arguments (for function calls) or elements (for array literals) are expected, or an object expression to be expanded in places where zero or more key-value pairs (for object literals) are expected.
https://seongbeom.github.io/2017/02/08/uses-of-spread-operator.html

#### Export/Import
0. Export: defining a module in one file and making the module available for use in another file(export default/ named export);
1. Import: To make use of the exported module and the behavior we define within it(import/ named import);

