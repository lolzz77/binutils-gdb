Intro
1. This is unofficial copy of GNU source code
2. The original is https://sourceware.org/git/?p=binutils-gdb.git;a=summary
3. Seems like it wasn't using github

-------------

Setup
Pre-requisite reference : https://sourceware.org/gdb/current/onlinedocs/gdb.html/Requirements.html
Other people's build : https://docs.rtems.org/releases/rtems-4.10.2/html/started/started00051.html
1. apt-get update
- Required, else you might fail install the `texinfo`
2. apt-get install libmpc-dev texinfo bison flex -y
- they are pre-requisite of GDB
3. mkdir /workspace/objdir
4. cd /workspace/objdir
5. ./../binutils-gdb/configure
6. make -j3
7. make install
