CS 2210 Project 2
David Ayodele 
03/18/2019

This implements project 2 - syntax analysis.

This may be compiled as follows:
1)$	make
Executes a makefile that performs the following:
	flex lex.l (generates lex.yy.c)
	yacc -v grammar.y (generates y.tab.c)
	gcc -g -o parser y.tab.c proj2.c -lfl

2) $ ./parser < file
Runs the parser on a file

This was compiled and tested on elements.cs.pitt.edu and germanium.cs.pitt.edu 

This was based on project 1 - lexical analysis, which contained some errors. 
These were not able to be fully corrected in time for the deadline.
 

