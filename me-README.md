Intro
1. This is unofficial copy of GNU source code
2. The original is https://sourceware.org/git/?p=binutils-gdb.git;a=summary
3. Seems like it wasn't using github

-------------

Setup
Pre-requisite reference : https://sourceware.org/gdb/current/onlinedocs/gdb.html/Requirements.html
1. apt-get update
- Required, else you might fail install the `texinfo`
2. apt-get install libmpc-dev texinfo bison flex -y
- they are pre-requisite of GDB
3. ./configure
4. make -j3 (still doesnt work, try read doc from gdb/README.md)
