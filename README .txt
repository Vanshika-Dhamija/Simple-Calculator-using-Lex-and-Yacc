there are two files we have to run the following commands
lex SimpleCalculator.l
yacc -d SimpleCalculator.y
cc lex.yy.c y.tab.c -o out
./out
after that enter the values
