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


## Chapter 0.3

### About C++
1. C++ adds many new features to the C language, and is perhaps **best thought of as a superset of C**, though this is not strictly true (as C99 introduced a few features that do not exist in C++)
2. 