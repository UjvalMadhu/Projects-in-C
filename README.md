# Projects-in-C
 This repo contains various programs built using the C programming language.


## Intro to C


*C*  was orginally created by Dennis M. Ritchie for moving the kernal code from assembly language to a high level language and other applications in the UNIX operating system at Bell Labs in 1972. C succeeded the programming Language B (derived from BCPL systems programming Language) developed by Ken Thompson and Dennis Ritchie. A large number of the modern programming languages are influenced by C in terms of syntax formation.

* C is widely used for systems programming in building operating systems and applications software for various computer architectures that range from Supercomputers and PLCs to   embedded systems. 
* C is a very good mid level programming language, meaning it has sufficient features of a high level language and can also be easily complied to low level assembly language for almost all the architectures present. The ease of compiling makes C very portable and ideal for cross-platform programming, this also allows C to be used for making compilers , libraries and interpreters of other languages. 
* C is also very stable, efficient and faster than most high level languages as it does not have similar overheads during processing. This makes it apt for resource constrained real-time systems. 

### Tools Needed:

To build and run C prgrams you need:
 1. Text Editor: Any available text editor to write your code. You have to then save it as a `.c `file.
 2. Compiler: A compiler is a software that converts the your code into machine language your CPU understands so as to execute it. I use the GNU C/C++ compiler which is open source and widely used. You can download the GNU compiler for various OS from the below links:
 > * For Linux OS (It is usually preloaded, Check before downloading) :  https://gcc.gnu.org/install/  
 > * For Windows OS you need to install MinGW ( Minimalist GNU for Windows) which is an open source software development platform which has the compilers for C,C++ and Fortan with associated tools for windows, download from: https://www.mingw.org  
 > * For Mac OS you need to download and setup X code development environment which has the GNU C/C++ compiler,from Apple's website:  https://developer.apple.com/technologies/tools/ 
3. Command-Prompt interface: you can run the C program on the command line after compiling it, I use the GCC compiler on the Linux Terminal to run the following code.

       $ gcc [File_Name].c
       $ ./a.out 
The first line compiles the code and the second line produces the output.
If you are using a different compiler, make sure to read the documentation regarding compiling and running the code.


Motivation: This contains various C programs that are done for the purpose of learning the language especially for use in embedded systems programming. The code will be explained in a beginner friendly manner so that anyone can implement and learn them.
