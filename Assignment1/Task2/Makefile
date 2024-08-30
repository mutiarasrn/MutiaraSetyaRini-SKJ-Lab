all: multiplicationtask2


multiplicationtask2: multiplicationtask2.cpp
	g++ -o multiplicationtask2 multiplicationtask2.cpp


dump: multiplicationtask2
	objdump -d multiplicationtask2.exe > multiplicationtask2.asm


clean:
	del multiplicationtask2.exe multiplicationtask2.asm


run: multiplicationtask2
	./multiplicationtask2.exe