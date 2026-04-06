
build: 
	nasm -f elf p5.asm
	ld -m elf_i386 p5.o -o ../../bin/practica5.exe ../../lib/libpc_io.a

builda: 
	nasm -f elf p5a.asm
	ld -m elf_i386 p5a.o -o ../../bin/practica5a.exe ../../lib/libpc_io.a

buildb: 
	nasm -f elf p5b.asm
	ld -m elf_i386 p5b.o -o ../../bin/practica5b.exe ../../lib/libpc_io.a
buildc: 
	nasm -f elf p5c.asm
	ld -m elf_i386 p5c.o -o ../../bin/practica5c.exe ../../lib/libpc_io.a
run:
	./../../bin/practica5.exe
runa:
	./../../bin/practica5a.exe
runb:
	./../../bin/practica5b.exe
runc:
	./../../bin/practica5c.exe