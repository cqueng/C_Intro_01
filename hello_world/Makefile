all: run

run: main.c
	gcc -o hello main.c
	./hello

test: test.c main.c
	gcc -o test_hello test.c main.c

clean:
	rm -f hello test_hello
