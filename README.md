CMMInterpreter
==============

An interpreter for CMM, a subset of C language. It's written in C, based on GNU Flex &amp; Bison.

It supports following types:
* int
* real(float)
* bool
* array

loops:
* while

and standard I/O:
* read(var)
* write(var)

You don't need to write **main** function, actually it doesn't support function. It also supports comments, both /*comment*/ and //comment .
You can use **-t** to let the interpreter print the **syntax tree**, but you may put the sign at the last position of line like this: **./interpreter test2.cmm -s**

That's all.  Have fun. ;-D

Notice: It does not support variable definition with declaration, which means you have to do this: **int var; var = 3;** instead of **int var = 3;** Same for arrays.