Системне програмування, Лабораторна робота номер 5 
``` bash
lex lexer.l
yacc -d -v parser.y
gcc -ll -w y.tab.c
./a.out<input1.c
```