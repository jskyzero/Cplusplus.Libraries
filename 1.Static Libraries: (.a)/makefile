all: 
	cc -Wall -c ctest1.c ctest2.c
	ar -cvq libctest.a ctest1.o ctest2.o
	ar -t libctest.a
	cc -o main.1.out prog.c libctest.a
	cc -o main.2.out prog.c -L./ -lctest