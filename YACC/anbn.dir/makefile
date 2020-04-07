anbn: y.tab.c lex.yy.c
	gcc -o anbn y.tab.c
y.tab.c: anbn.y lex.yy.c
	yacc anbn.y
lex.yy.c: anbn.l
	lex anbn.l
clean:
	rm -f lex.yy.c y.tab.c anbn
