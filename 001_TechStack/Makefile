CFLAGS = -Wno-implicit-function-declaration

all: hi

hi: main.o hello.o
	gcc $(CFLAGS) main.o hello.o -o hi
	@echo "Linking and producting the executable\n"

main.o: main.c
	gcc $(CFLAGS) -c main.c
	@echo "Compiling the main file\n"

hello.o: hello.c 
	gcc $(CFLAGS) -c hello.c
	@echo "Compiling the hello file\n"

clean:
	rm main.o hello.o hi 
	@echo "Reducing folder to source files\n"
