all: 
	gcc -Wall -fPIC -c *.c
	# gcc -shared -Wl,-soname,libctest.so.1 -o libctest.so.1.0   *.o
	gcc -shared -o libctest.so  *.o
	gcc -Wall -I./ -L./ prog.c -lctest -o main.1.out


	# mv libctest.so /opt/lib
	# ln -sf /opt/lib/libctest.so.1.0 /opt/lib/libctest.so.1
	# ln -sf /opt/lib/libctest.so.1.0 /opt/lib/libctest.so
	# gcc -Wall -L/opt/lib prog.c -lctest -o main.2.out