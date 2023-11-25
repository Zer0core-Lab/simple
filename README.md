Hello World in C for Basic Assembly Learning.
 
This repository contains a simple "Hello, World!" C program designed to help you learn basic assembly language.

Compilation with GCC:

Prerequisites:

Make sure you have GCC (GNU Compiler Collection) installed on your system.

Steps:

1. Open a terminal.

2. Navigate to the directory containing the C program file.
   - eg: cd path/to/your/repo
   
3.Compile the C program using GCC
- eg: gcc -o hello hello.c
- Replace hello with the  name the you want the out to be.

Disassembly with GDB:

Prerequisites:

Make sure you have GDB (GNU Debugger) installed on your system.

Steps:
1. Open a terminal 

2. Navigate to the directory containing the compiled executable.

3. Start GDB: eg: gdb ./hello

4. Inside GDB, disassemble the main function:
   - eg: disassemble main
   - This will show the assembly code corresponding to the main function.
   
Feel free to edit, experiment and explore further! If you have any questions or run into issues, don't hesitate to reach out.

Happy coding and learning! 🚀
