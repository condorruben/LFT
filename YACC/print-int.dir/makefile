print-int: y.tab.c lex.yy.c
	gcc -o print-int y.tab.c
y.tab.c: print-int.y lex.yy.c
	yacc print-int.y
lex.yy.c: print-int.l
	lex print-int.l
clean:
	rm -f lex.yy.c y.tab.c print-int
