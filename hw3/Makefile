# Adrian's Makefile for CSE 508 project 3

all: clean pbproxy test_ssl

pbproxy: pbproxy.c
	gcc -g pbproxy.c -o pbproxy.o -lcrypto -lpthread

test_ssl: test_ssl.c
	gcc -g test_ssl.c -o test_ssl.o -lcrypto

clean:
	rm -f *~ *.o *.out
