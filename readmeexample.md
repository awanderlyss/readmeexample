Alyssa Felix
Anusone Nanthavongsa
Dara Hoy

  Objectives:
1) Describe destructuring
2) Why would we use this?
3) Write an example


Description: Is a convenient way of extracting data stored in (possibly nested) objects and arrays.


WHY?
A more concise way of manipulating and editing data.


Examples:

var foo = ["one", "two", "three"];

var[one, two, three] = foo;
console.log(one); // 'one'
console.log(two); // 'two'
console.log(three); // 'three'



var o = {p: 42, q: true};
var {p, q} = o;

console.log(p); // 42
console.log(q); // true;





Block Scope:
OBJECTIVES:
1) DESCRIBE A BLOCK SCOPE
2) RULES FOR A BLOCK SCOPE
3) DIFFERENCE BETWEEN BLOCK VS FUNCTION SCOPE
4) GIVE AN EXAMPLE OF BLOCK SCOPE


DESCRIPTION OF A BLOCK SCOPE:

A block scope is a local level scope that has a variable that is declared only within a block of code and not outside of that.  Examples of that would include if statements, for loops, while loops. etc


RULES:

1) Has to be within {} aka Moustaches
2) It has a block scope if a variable is declared inside a block of code and is only visible within  that block of code.


Differentiate between BLOCK vs FUNCTION Scope:

$$$function(){
	function(){
		function(){***
		for (i = 0; i > 100; i++)***
	   }
   }
}$$$

$$$ = function scope
*** = Block scope

MORE EXAMPLES:

https://www.sitepoint.com/joys-block-scoping-es6/
