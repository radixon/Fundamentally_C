CFLAGS = -Wno-implicit-function-declaration

all: hi

hi: main.o hello.o
	@echo "Linking and producting the executable\n"
	gcc $(CFLAGS) main.o hello.o -o hi

main.o: main.c
	@echo "Compiling the main file\n"
	gcc $(CFLAGS) -c main.c

hello.o: hello.c 
	@echo "Compiling the hello file\n"
	gcc $(CFLAGS) -c hello.c

clean:
	@echo "Reducing folder to source files\n"
	rm main.o hello.o hi 