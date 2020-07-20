all: 
	gcc -Wall -fPIC -c *.c
	gcc -shared -o libctest.so  *.o
	gcc -rdynamic -o main.out prog.c -ldl