## Chapter 0.2

### Terms
1. Portable - same code can be run any where
2. Platform - set of compatible hardware and software
3. ISA - instruction set architecture - like RISC, MIPS, ARM etc.
4. Machine language -> Assembly language -> High level language
5. Issues with low level language:  
    Not portable, tough to understand, tough to read and extend
6. C++ compilers generally generate assembly language.
    
    *Interpreters tend to be more flexible than compilers, but are less efficient.*  
    when running programs because the interpreting process needs to be done every time the program is run.

### Compiled vs Interpreted languages
1. compiled code benefits   
    more optimized, lower memory usage (generate low-level code that performs the equivalent of a high-level ideas like "dynamic dispatch" or "inheritance" in terms of memory lookups inside of tables.), faster as we don't have to execute interpreted steps
2. compiled code losses:  
    dynamic typing is tough to implement.  
    long compile and load times.  

### Code portability
1. Platform specific optimizations maybe missed
2. Third party libraries are often present only for 1 platform.
3. C++ does not have abstractions to the level of more modern languages like python, JS


## Chapter 0.3 - 0.5

### About C++
1. C++ adds many new features to the C language, and is perhaps **best thought of as a superset of C**, though this is not strictly true (as C99 introduced a few features that do not exist in C++)
2. After the compiler has successfully finished, another program called the linker kicks in. The linker’s job is to combine all of the object files and produce the desired output file (such as an executable file that you can run). This process is called linking. If any step in the linking process fails, the linker will generate an error message describing the issue and then abort.
3. Build automation tools (such as make or build2) are often used to help automate the process of building programs and running automated tests.

## Chapter 0.6 - 0.7

### Installing IDE

## Chapter 0.8 - 0.9

### Starter problems for C++ and IDEs
### Compiler build configurations
1. More details here: https://gcc.gnu.org/onlinedocs/gcc/Optimize-Options.html
2. Configuraing compiler warnings: In rare cases, it may be necessary to explicitly tell the compiler to not generate a particular warning for the line of code in question. C++ does not support an official way to do this, but many individual compilers (including Visual Studio and GCC) offer solutions (via non-portable #pragma directives)
## 
