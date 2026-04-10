For this project, we expect you to look at these concepts:

Static Analysis
Resources
Read or watch:
Ghidra Beginner’s Guide:
https://github.com/NationalSecurityAgency/ghidra
System Security
https://opensecuritytraining.info/System%20Security.html
Exponentiation by Squaring
https://en.wikipedia.org/wiki/Exponentiation_by_squaring
Modular Arithmetic
https://en.wikipedia.org/wiki/Modular_arithmetic
Introduction to Cryptography
https://www.crypto101.io/i
Introduction to Assembly Language for Reverse Engineering
https://www.youtube.com/watch?v=LdWU8JEfPhg&t=10sGDB 
Tutorial: Stepping Through Assembly
https://www.cs.cmu.edu/~gilpin/tutorial/
Reversinghttps://www.youtube.com/watch?v=oTD_ki86c9I
Understanding x86/x64 Assembly
https://cs.brown.edu/courses/cs033/docs/guides/x64_cheatsheet.pdf
Tools

Ghidra
https://github.com/NationalSecurityAgency/ghidra
Radare2
https://rada.re/n/
IDA Pro
https://hex-rays.com/ida-free
GDB (GNU Debugger)
https://www.sourceware.org/gdb/
Objdump
https://sourceware.org/binutils/docs/binutils/objdump.html


Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

What is static analysis in reverse engineering?
Why is static analysis important for malware analysis, security auditing, and software debugging?
How does disassembly and decompilation aid in understanding a program’s code?
What are the key differences between executable formats like PE (Windows), ELF (Linux), and Mach-O (macOS)?
What tools are commonly used for static analysis, such as IDA Pro, Ghidra, and Radare2?
How do control flow graphs (CFGs) assist in mapping out the execution flow of a program?
What techniques are used to identify vulnerabilities and bugs in binary code through pattern recognition and signature matching?
How does header analysis contribute to understanding the structure of binary files?
What role does cross-referencing play in identifying critical functions and code paths?
What are the steps in a typical static analysis workflow, from initial inspection to documentation?
Requirements
General
Allowed tools: IDA Pro, Ghidra, Radare2,Hex-Rays Decompiler, Binwalk, Strings, Binary Ninja, Cutter.
All analyses should be conducted in a controlled environment, like a VM or sandbox.
Ensure that all files are backed up regularly during the analysis process.
All your scripts must be executable and runnable on Kali Linux.
You should avoid using hardcoded values for paths; utilize relative paths instead.
Make sure to validate the integrity of the binaries before analyzing them.
All analysis findings should be organized and clearly formatted for easy reference.
For this project, your focus will be on the target target_binary
You are not allowed to use online tools or services for your analysis; everything must be done locally.
