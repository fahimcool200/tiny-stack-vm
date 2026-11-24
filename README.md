# tiny-stack-vm

An interpreter for make.fun's tiny stack ISA: 32-bit wrapping arithmetic, a 256-value data stack, a 64-deep call stack, 256 words of memory, input, output, and all ten traps with their own exit codes, plus the step and output limits.

Run it:

```sh
MAKEFUN_INPUT_DIR=practice/input MAKEFUN_OUTPUT_DIR=out node main.ts
```

For each instance `<id>` it reads `<id>/program.bin` and `<id>/input.bin` and writes `<id>/stdout.bin` and `<id>/exit.txt`. Node 22, standard library only. Practice set: 40/40 match the reference.
