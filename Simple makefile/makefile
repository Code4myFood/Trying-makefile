run: Myadd.o main.o
        gcc Myadd.o main.o -o run
Myadd.o: Myadd.c
        gcc -c Myadd.c
main.o: main.c
        gcc -c main.c

.PHONY: clean

clean:
        rm -rf *.o
        rm -rf *.gch
