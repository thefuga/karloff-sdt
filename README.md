# karloff-sdt
Syntax directed translation using the Karloff grammar for a compilers design assignment.

1. Generate the Java code using javacc: `javacc karloff.jj`
2. Compile all generated code using Java compiler: `javac *.java`
3. Run compiled code (followed by and input file): `java Karloff input.klf`

