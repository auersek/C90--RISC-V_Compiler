## PROJECT 5: C Compiler (C++):

This project implements a C90 compiler that translates C source code into RISC-V assembly instructions, written entirely in C++. The compiler follows a modular design built around an Abstract Syntax Tree (AST), where each node corresponds to a distinct syntactic construct such as arithmetic, logical, relational, and bitwise operations. Each node includes logic for semantic evaluation and instruction emission, enabling precise translation of high-level C expressions into low-level RISC-V assembly.

The compiler supports a wide range of data types including integers, floating-point numbers, doubles, and characters, as well as pointer operations and type-specific arithmetic. It includes a context-aware register allocation system that manages integer and floating-point registers, ensuring efficient use of processor resources during code generation. Pointer arithmetic and type-specific memory handling are implemented carefully to respect data size semantics defined in the C90 standard.

From a systems perspective, this project demonstrates a comprehensive understanding of compiler construction, including lexical and syntactic analysis, semantic typing, and target code generation. The back end specifically focuses on producing correct and optimized RISC-V instructions that maintain functional equivalence with the source code while adhering to architectural conventions.

Beyond its immediate functionality, the compiler serves as a foundation for exploring advanced topics such as optimization passes, control-flow graph generation, and register spilling strategies. It highlights strong skills in C++ system programming, low-level computer architecture, and language translation design, bridging the gap between high-level programming and hardware execution.

