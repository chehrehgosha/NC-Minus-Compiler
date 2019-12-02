# NC-Minus-Compiler
Compiler for NC-Minus Programming Language
In this project:
* The main objective is to implement a compiler for NC-Minus programming language.
* This compier is a one-pass compiler.
* This project is implemented in python.
* At first step I designed an implemented the Lexical Analyzer for this compiler which tries to scan the code, extract the proper token and pass it to the parser.
* In this part (Scanner) compiler reads the code character by character and recognize the proper token like (Token Type, Token String). The DFA for this scanner is designed by scratch on paper.
* The next step is to implement the parser for this compiler. For the convenient we had to transform our grammar to a LL(1) grammar. For this purpose I used the website [The Context Free Grammar Checker](http://smlweb.cpsc.ucalgary.ca/start.html) it had some very useful tools. The final LL(1) grammar is coded in a JSON-like code at the first part of code.
