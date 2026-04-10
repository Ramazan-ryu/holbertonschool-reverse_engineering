Resources
Read or watch:
A Beginner's Guide to Reverse Engineering
https://0xinfection.xyz/reversing/
GDB Tutorial Series
https://www.cs.cmu.edu/~gilpin/tutorial/
x64dbg Official Documentation
https://x64dbg.com/#documentation
Malware Analysis Tutorials
https://youtu.be/qA0YcYMRWyI?si=6vJZLSt0a08t5KPb
Introduction to SAT Solving with Z3
https://ericpony.github.io/z3py-tutorial/guide-examples.htm
Understanding SAT Solvers

Practical Reverse Engineering with Z3
https://de-engineer.github.io/SMT-Solvers/
SAT/SMT
https://youtu.be/s1zLmn30xuE?si=2sAl9HMbTLpa21oy
Symbolic Execution
https://srg.doc.ic.ac.uk/klee22/talks/David-Reverse-Engineering.pdf
Anti-Debugging Techniques in Malware
https://www.astesj.com/publications/ASTESJ_0506142.pdf
Understanding and Bypassing Anti-Debugging Techniques
https://repo.zenk-security.com/Reversing%20.%20cracking/CodeBreakers%202006%20-%20AntiDebugging%20techniques.pdf
GDB Tutorial: Bypassing Anti-Debugging
https://jaybailey216.com/debugging-stripped-binaries/
Introduction to Reverse Engineering with GDB
https://azeria-labs.com/debugging-with-gdb-introduction/
Understanding Self-Modifying Code
https://malwaremusings.com/2012/10/13/self-modifying-code-changing-memory-protection/


Tools
GDB (GNU Debugger)
https://www.sourceware.org/gdb/
OllyDbg
https://www.ollydbg.de/
x64dbg
https://x64dbg.com/
Cuckoo Sandbox
https://cuckoosandbox.org/
Intel Pin
https://www.intel.com/content/www/us/en/developer/articles/tool/pin-a-dynamic-binary-instrumentation-tool.html
Wireshark
https://www.wireshark.org/
Sysinternals Suite
https://learn.microsoft.com/en-us/sysinternals/
Z3 Solver
https://github.com/Z3Prover/z3
MiniSat
http://minisat.se/MiniSat.html
Binary Ninja
https://binary.ninja/
IDA Pro
https://hex-rays.com/ida-free
Immunity Debugger
https://letsdefend.io/blog/how-to-install-immunity-debugger-on-windows
Valgrind
https://valgrind.org/


Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

What are the key differences between static and dynamic analysis, and why is dynamic analysis important in reverse engineering?

What techniques can be employed in dynamic analysis, such as setting breakpoints, performing memory dumping, and tracing program execution?

How can debugging tools like GDB, x64dbg, and OllyDbg be effectively utilized to analyze binary files and track their execution?

What methods can be used to monitor system behavior during program execution, particularly using tools like Process Monitor and Wireshark?

How does a program interact with the operating system, including its file system access, API calls, and network communications?

What best practices should be followed for documenting findings from dynamic analysis, including observed behaviors and potential vulnerabilities?

In what real-world scenarios can dynamic analysis skills be applied, such as in malware analysis, security testing, and software debugging?

Requirements
General
Here are the requirements for the dynamic analysis project in the same format:

Allowed tools: GDB,x64dbg, OllyDbg, Cuckoo Sandbox, Wireshark, ProcMon, Intel Pin, Valgrind, Sysinternals Suite.
All analyses should be conducted in a controlled environment, such as a virtual machine or sandbox.
Ensure that all files and data are backed up regularly during the analysis process.
All your scripts and tools must be executable and runnable on Kali Linux.
Avoid using hardcoded values for paths; utilize relative paths instead for all file references.
Validate the integrity of the binaries and scripts before analyzing them to prevent potential issues.
Ensure that all monitoring tools are configured correctly before starting the analysis.
All findings and documentation should be organized and clearly formatted for easy reference and reporting.
Focus your analysis on the target binary provided for the project.
You are not allowed to use online tools or services for your analysis; all work must be done locally within your controlled environment.

