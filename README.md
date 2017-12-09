# Curtain-Compiler
The Curtain Compiler - Compiles Curtain Syntax into C, and then ASM using GCC. Designed with a versatile syntax and featureset that maintains full control and executes swiftly.
<br>
<br>
The Current iteration is written in Java. But, the beta iteration will be utilizing bootstrapping.
<br>
<h2>Program Structure</h2>
Arguments are verified, if valid, program continues, else throws reasonable error<br>
reads each line, assembles it into string array<br>
Parses each line, tokenizes it<br>
Replaces keywords, begins translation<br>
Pulls other imported files, parses them, and assembles syntax tree<br>
After translation is complete, writes C code to output<br>
