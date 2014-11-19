Web Developer Interview Questions
=======================

General questions for LAMP based web developer. Beginner to advanced.

### PHP

1. Difference between == and ===?
2. What is the keyword that tells PHP that a class definition subclasses another class?
3. Name some PHP superglobals.
4. Describe a use case for an anonymous function.
5. Why should you not use register_globals?
6. How would you deal with SQL injection in PHP?
7. What is MVC? Why is it useful?
8. What is the difference between an abstract class and an interface?
9. What are the 3 major principles of Object Oriented Programming?
  * Encapsulation
  * Polymorphism
  * Inheritance
10. What is the difference between _public_, _protected_, and _private_?
11. What are some of the newer features in PHP?
  * Constant scalar expressions
  * Variadic functions (... operator)
  * Argument unpacking (... opertator)
  * Generators
  * finally keyword
  * Opcode caching via OpCaching
  * Traits
12. What is Composer?

### Javascript

1. What type of inheritance does Javascript use?
2. How do you create a new object in Javascript?
  * Literal {} or via _new_
3. How does prototype inheritance work?
4. How do you organize your Javascript code?
5. How does _this_ work in Javascript?
  * Global == window
  * Function == window ("use strict" == undefined)
  * Object == object
  * Constructor == the new object (unless constructor returns object, in which case this object is discarded)
6. What is a closure?
7. What is an Immediately Invoked Function Expression? Why would you use it?
8. What is hoisting? 

### CSS

1. What is the box model? What are the 4 parts to the box model?
2. What is the difference between an inline element and a block element?
3. Explain the difference in _visibility: hidden_ and _display: none_.
4. What is a CSS preprocessor and how are they useful?

### MySQL

1. What is the difference between an inner join and a left join?
2. Describe what steps you take, or what things you look for, when you need to optimize queries.
3. Explain advantages of InnoDB over MyISAM?
  * Row-level locking
  * Transactions
  * Foreign key constraints
  * Crash recovery.
