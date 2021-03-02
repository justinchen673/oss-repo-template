static_library: source/block.c headers/block.h program.c
	gcc -std=c99 -c source/block.c headers/block.h program.c -I.
	ar -rc libstatic.a block.o program.o
	gcc program.c -L. -lstatic -o static_block

shared_library: source/block.c headers/block.h program.c
	gcc -std=c99 -c -fpic source/block.c headers/block.h program.c -I.
	gcc -shared -o libshared.so block.o program.o
	gcc program.c -L. -lshared -o dynamic_block.o
