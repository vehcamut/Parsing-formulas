# Parsing-formulas

This is a tutorial project. The program is a simple calculator. It is designed to calculate simple formulas. There is support for the operations: "+", "-", "*", "/", as well as parentheses: "(", ")". Both whole numbers and decimal fractions can be used as operands.

While working on the project, I mastered the basics of C++ syntax, such as:
* classes
* constructors
* cycles
* destructors
* exceptions and their handling
* functions
* inheritance
* logical operations
* pointers
* templates
* working with the command line
* and so on

Data structures were also implemented:
* binary tree
* stack

For parsing the formula, an algorithm was used to translate the formula into a reverse Polish notation, followed by its entry into a binary tree.
For instance, let we have formula: (2 \+ 3) \* 4 \- 5\.

First, we translate it to the reverse Polish notation: 23\+4\*5\-\.

Then we build the tree recursively:

	      -
	     / \
	    *   5
	   / \
	  +   4
	 / \
	2   3

After then we calculate formula.
