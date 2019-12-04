# programming-languages-2020

This course has been developed by Alexander Kurz and Samuel Balco and will be taught by Alexander Kurz.

The course is divided in a practical and theoretical component. 

Students will learn the basics of how to

- build a parser and interpreter for simple functional and imperative programming language. 

Moreover, students will learn the fundamental ideas of

- lambda calculus
- operational and denotational semantics    
- term rewriting   
- invariants and well-founded orders     
- program verification and Hoare logic    
- structural induction, universal algebra, and category theory    

On the way, students will encounter different programming languages such as Dafny and Haskell, theorem provers such as Isabelle, dependently typed programming languages such as Idris as well as programming concepts such as algebraic data types, recursion, variable binding, polymorphism, and more.

A special feature of the course is to pay attention to compositionality. In software engineering we see compositionality in the division between syntax and semantics, or, parsing and interpretation. The programming technique of recursion over abstract syntax tree is another incarnation. In program verification, we will separate termination from partial correctness. 

Assessment is divided accordingly in programming assignments, presentations, and written examinations, currently planned as follows.

- Assignment 1: Recursive programming over lists and trees in LambdaNat. (10%)   
- Assignment 2: Installing the Haskell Platform. (5%)   
- Assignment 3: Writing an interpreter for LambdaNat. (10%)    
- Assignment 4: Programming with pointers in LambdaFun. (10%)   
- Assignment 5: Writing an interpreter for LambdaFun. (10%)   
- Test 1: Term rewriting. (5%)   
- Test 2: Program verification. (5%)   
- [Project](presentation.md) on a programming language of your choice. (15%)   
- Final Exam. (30%)   

#### Acknowledgements

The specific way we intertwine theory and practice may be original, but we build on a long tradition of teaching courses on  principles of programming languages. The idea that the best way to understand how programming languages work under the hood is to learn how to build your own, goes back at least to the MIT course and the "Wizard Book" by Abelson and Sussman, [Structure and Interpretation of Computer Programs](https://mitpress.mit.edu/sites/default/files/sicp/index.html), which is still worth reading today. Our use of the parser generator BNFC for the language `LambdaNat` follows Aarne Ranta's book [Implementing Programming Langugages](http://www.grammaticalframework.org/ipl-book), which forms the basis for the [Programming Language Technology](http://www.cse.chalmers.se/edu/course/DAT151/) course at Chalmers University. We will hear more about this in our course on Compiler Construction next semester. `LambdaNat` itself is a lambda calculus with just enough additional syntactic sugar so that writing programs in `LambdaNat` feels is similar enough to mainstream functional programming. The way we then extend `LambdaNat` to our second language, `LambdaFun`, by adding while loops, memory allocation, assignment, and pointers follows Michael Spivey's course on [Programming Languages](https://spivey.oriel.ox.ac.uk/corner/Welcome_to_Spivey%27s_Corner) at Oxford University.

We are also grateful to our friends and colleagues from the [Midlands Graduate School in the Foundations of Computing Science](http://www.cs.nott.ac.uk/MGS/) who have influenced with their graduate level courses from 2002 onwards the choice of material. In fact, it is one of the aims of this course to provide at the undergraduate level the foundations that will equip interested students with the knowledge needed to study advanced topics in programming languages. Many of the paragraphs labelled "Further Study'' are meant to provide bridges to such graduate level courses.

Many thanks to all with whom we had the opportunity to discuss the contents of the course, including (but not limited to) Roy Crole,  Peter Jipsen, Drew Moshier, Paula Sever, and Fer-Jan de Vries for many helpful comments and discussions; to the students of 2018/19 for continuing challenge and feedback; to all the colleagues from whom we have been learning over the years.

