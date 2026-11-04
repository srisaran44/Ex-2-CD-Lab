# Ex-2-GENERATION OF LEXICAL TOKENS LEX FLEX TOOL
## Date:04/11/2026
## Register Number:212225240159
# AIM
## To write a lex program to implement lexical analyzer to recognize a few patterns.
# ALGORITHM

1.	Start the program.

2.	Lex program consists of three parts.

     a.	Declaration %%

     b.	Translation rules %%

     c.	Auxilary procedure.

3.	The declaration section includes declaration of variables, maintest, constants and regular definitions.
4.	Translation rule of lex program are statements of the form

    a.	P1 {action}

    b.	P2 {action}

    c.	…

    d.	…

    e.	Pn {action}

5.	Write a program in the vi editor and save it with .l extension.

6.	Compile the lex program with lex compiler to produce output file as lex.yy.c. eg $ lex filename.l $ cc lex.yy.c
7.	Compile that file with C compiler and verify the output.

# INPUT
(a+b*c)*$
# OUTPUT
<img width="1472" height="795" alt="image" src="https://github.com/user-attachments/assets/eb2118e0-b6c8-486f-8f0d-e719f355d2dc" />

# RESULT
## The lexical analyzer is implemented using lex and the output is verified.
