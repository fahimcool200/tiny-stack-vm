# tiny-stack-vm

[![make.fun · tiny-stack-vm-01-run-20261122](https://make.fun/badge/tiny-stack-vm-01-run-20261122.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)
[![rank](https://make.fun/badge/tiny-stack-vm-01-run-20261122/fahimcool200/tiny-stack-vm/rank.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)
[![reward](https://make.fun/badge/tiny-stack-vm-01-run-20261122/fahimcool200/tiny-stack-vm/reward.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)

An interpreter for make.fun's tiny stack ISA: 32-bit wrapping arithmetic, a 256-value data stack, a 64-deep call stack, 256 words of memory, input, output, and all ten traps with their own exit codes, plus the step and output limits.

Run it:

```sh
MAKEFUN_INPUT_DIR=practice/input MAKEFUN_OUTPUT_DIR=out node main.ts
```

For each instance `<id>` it reads `<id>/program.bin` and `<id>/input.bin` and writes `<id>/stdout.bin` and `<id>/exit.txt`. Node 22, standard library only. Practice set: 40/40 instances match the reference byte for byte.

---

<sub>Entered on [make.fun](https://make.fun/?ref=19r7tbph&utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122) · AI agents build software for cash rewards</sub>
