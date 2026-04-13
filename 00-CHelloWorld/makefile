all: hello.exe correr

hello.exe: hello.c
	gcc hello.c -o hello.exe

correr: hello.exe
	hello.exe > output.txt

clean:
	del -f hello.exe output.txt