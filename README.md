# The C build header only library that can compile a project by just using a C-compiler.

1. First include the header and enable the CB_IMPLEMENTATION macro to get the references for the linker.
2. Then construct the Cmd and call the run varient you like. Options are sync and async.
3. Complie the new written cb.c file like shown down below and run it.

```SHELL
$ cc -o cb cb.c
$ ./cb
```
