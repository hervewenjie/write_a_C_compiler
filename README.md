# How to Run the Code

```
gcc -o xc xc.c (you may need the -m32 option on 64bit machines)
./xc hello.c
./xc -s hello.c

./xc c4.c hello.c
./xc c4.c c4.c hello.c
```

# About

This project is inspired by [c4](https://github.com/rswier/c4) and is largely
based on it.

However, I rewrited them all to make it more understable and help myself to
understand it.

Despite the complexity we saw in books about compiler design, writing one is
not that HARD. You don't need that much theory though they will help for
better understanding the logic behind the code.

# Resources

Further Reading:

- [Let's Build a Compiler](http://compilers.iecc.com/crenshaw/): An excellent
    starting material for building compiler.

# Licence

The original code is licenced with GPL2, so this code will use the same
licence.