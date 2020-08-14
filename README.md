# AssemblyLanguageFindings
What you are viewing is my findings in x86 Tutorial Assembly Languge on Linux.
### Requirements
- Linux, WSL2 , or  VM Linux
- Nasm
- GCC (if C program functions is used)
## Running Codes
- Install Nasm on your WSL or Linux
```shell
$ sudo apt-get install nasm
```
- Create Executables Though Below Command:
```shell
$ nasm -f elf32 xxx.asm -o ex1.o
$ Ld -m elf_i386 ex1.o -o ex1
```

- Run Executables.
```shell
./ex1
echo $? 
```

## Credit
- ShiroKlein
