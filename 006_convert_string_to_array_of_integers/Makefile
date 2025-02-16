task6: task6.o
	ld -melf_i386 -o task6 task6.o

task6.o: task6.S my-macro
	as --32 -gstabs+ -o task6.o task6.S