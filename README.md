# x86_64 Assembly.sudo apt update && sudo apt upgrade -y Just for fun ;)

Need a assembler:
````
sudo apt install nasm
````
Compile:
````
nasm -f elf64 -o hello.o hello.asm
````
Link to make it exe:
````
ld hello.o -o hello
````
