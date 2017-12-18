# Lexical-Analyzer-
Some lexical analyzer for identifying keyword for C programming, counting character, word, line, identifying character. All of those rules written in Flex
#The program charcheter word count multi take multiple file as a input.
So you just have to pass multiple file name as a run time.

#Commnad for running lexical analyzer
1. you have to generate lex.yy : flex -l yourprogramnmae.l
2. gcc lex.yy.c -o outputFilename
3. ./outputFilename < inputfile.in
