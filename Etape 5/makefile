CC=gcc
CFLAGS= -Wall -g

all : show

show : $(patsubst %.c, %.o, $(wildcard *.c) )
	$(CC) -o $@ $^
	
clean:
	rm -rf *.o
