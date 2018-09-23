# compiler
A short Description of this repository:  
It contains all the Code from my "Writing a simple Compiler on my own" series on Steemit (step by step / article by article), where we are implementing a complete Compiler for a simple C-like Language using the C-tools Flex and Bison.

It's worth noting that not all articles contain actual Coding.  
Compiler design in general is mostly about understanding how everything needs to work.  
After understanding the basic principle, the implementation is much easier, which is why some articles are 90% theory!

Until now we covered:  
-Compiler design in general (introduction) -> https://steemit.com/programming/@drifter1/writing-a-simple-compiler-on-my-own-introduction  
-The simple C-like Language -> https://steemit.com/programming/@drifter1/writing-a-simple-compiler-on-my-own-a-simple-c-language  
-Lexical Analysis and the implementation of a simple Lexer using Flex -> https://steemit.com/programming/@drifter1/writing-a-simple-compiler-on-my-own-lexical-analysis-using-flex  
-The basic implementation/structure of a Symbol Table -> https://steemit.com/programming/@drifter1/writing-a-simple-compiler-on-my-own-symbol-table-basic-structure  
-Using the Symbol Table in the Lexer -> https://steemit.com/programming/@drifter1/writing-a-simple-compiler-on-my-own-using-symbol-tables-in-the-lexer  
-Syntax Analysis Theory needed-> https://steemit.com/programming/@drifter1/writing-a-simple-compiler-on-my-own-syntax-analysis-theory  
-Bison tool basics / tutorial -> https://steemit.com/programming/@drifter1/writing-a-simple-compiler-on-my-own-bison-basics  
-Creating a Grammar for the Language by also implementing a first Parser -> https://steemit.com/programming/@drifter1/writing-a-simple-compiler-on-my-own-creating-a-grammar-for-our-language  
-Combining Flex and Bison -> https://steemit.com/utopian-io/@drifter1/writing-a-simple-compiler-on-my-own-combine-flex-and-bison  

What remains now is:  
-Passing information from the Lexer to the Parser and fixing up some stuff  
-Finishing of the grammer/parser by adding more rules  
-Semantic analysis which includes predicates and more things about the Symbol Table  
-Intermediate code generation in form of a Abstract syntax tree  
-Final machine code generation in MIPS Assembly

After doing all that we could also get into Optimizations, Extensions and even more if you like :)
