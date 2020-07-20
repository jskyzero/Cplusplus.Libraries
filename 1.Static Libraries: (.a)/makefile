all: 
	cc -Wall -c ctest1.c ctest2.c
	ar -cvq libctest.a ctest1.o ctest2.o
	ar -t libctest.a
	cc -o main prog.c libctest.a
	# cc -o executable-name prog.c -L/path/to/library-directory -lctest