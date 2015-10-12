### Ekaterina Martakova
### CS178
### Make_ Build_And_Run

test: countThrees threesData.bin
	./countThrees

countThrees: countThrees.o readInt32BitLE.o
	gcc -o countThrees countThrees.o readInt32BitLE.o

countThrees.o: countThrees.c readInt32BitLE.h
	gcc -c countThrees.c

readInt32BitLE.o: readInt32BitLE.c readInt32BitLE.h
	gcc -c readInt32BitLE.c



clean:
	rm -f countThrees countThrees.o readInt32BitLE.o

