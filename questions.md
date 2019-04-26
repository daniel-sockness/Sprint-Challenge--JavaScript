1. Describe the biggest difference between `.forEach` & `.map`.
.foreach will execute the provided function once for each element in a array

.map will create a new array with the results of calling the provided function on every element in the array

2. What is the difference between a function and a method?
a method is created within a object is is also used as a property in that object
a function is created without a object

3. What is closure?

Closure makes it where any nested functions have access to the enclosing functions variables.

4. Describe the four rules of the 'this' keyword.

    1. When `this` is called in the global scope its value is the window/console object.
    2. Whenever a function is called by a preceding dot, the object before that dot is this.
    3. Whenever a constructor function is used, this refers to the specific instance of the object that is created and returned by the constructor function.
    4. Whenever JavaScript’s call or apply method is used, this is explicitly defined.

5. Why do we need super() in an extended class?