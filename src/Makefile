# Makefile for Biro lang

all: main.o chunk.o debug.o memory.o value.o vm.o scanner.o \
	compiler.o object.o table.o
	$(CC) -Wall -Wextra -Wconversion -pedantic -std=gnu17 -o biro \
	main.o chunk.o debug.o memory.o value.o vm.o scanner.o compiler.o \
	object.o table.o

main.o: main.c common.h
	$(CC) -c main.c

chunk.o: chunk.c chunk.h
	$(CC) -c chunk.c

debug.o: debug.c debug.h
	$(CC) -c debug.c

memory.o: memory.c memory.h
	$(CC) -c memory.c

value.o: value.c value.h
	$(CC) -c value.c

vm.o: vm.c vm.h
	$(CC) -c vm.c

scanner.o: scanner.c scanner.h
	$(CC) -c scanner.c

compiler.o: compiler.c compiler.h
	$(CC) -c compiler.c

object.o: object.c object.h
	$(CC) -c object.c

table.o: table.c table.h
	$(CC) -c table.c

clean:
	rm *.o

clean-all:
	rm *.o biro

