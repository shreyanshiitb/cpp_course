## Get the intermediate code (after preprocessing)
gcc -E main.cpp -o main.i
## Get the object code (unreadable binary)
gcc -c main.cpp -o main.o
## Get the assembly code
gcc -S main.cpp -o main.s
## Get the binary executable
gcc main.cpp