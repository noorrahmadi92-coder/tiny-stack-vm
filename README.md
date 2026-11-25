# Tiny Stack VM

A correct interpreter for make.fun's tiny stack ISA (v1): 32-bit wrapping
arithmetic, 256-value stack, 64-deep calls, 256 words of memory, all 10
traps with their exact exit codes, step and output limits.

Run: `node main.ts` — reads `/input/<id>/`, writes `/output/<id>/`.
