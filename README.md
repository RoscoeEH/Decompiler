# Decompiler
## Overview
This program works to decompile to ANSI C based on an LLVM compilation. I am interested in reverse engineering and at one point took a class on language design which gave me some familiarity with parsing. Given that I thought this would be a fun project. 

## Status
This contains a checklist for what exists in the current iteration. This list is subject to change as I learn more about decompilation. The current version is based on course notes from Maxime Serrano at CMU.
1. [ ] Disassembly - transformation from machine code to the assembly equivalent.
2. [ ] Lifting and Dataflow Analysis - transforming the resulting assembly code into a higher-level internal representation.
3. [ ] Control Flow Analysis - recovering control flow structure information, such as if and while statements, as well as their nesting level.
4. [ ] Type Analysis -  recovering types of variables, functions, and other pieces of data.

## Updates on Specific Portions



## Resources
- https://www.cs.cmu.edu/~fp/courses/15411-f13/lectures/20-decompilation.pdf