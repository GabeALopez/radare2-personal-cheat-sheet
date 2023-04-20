# Personal Cheat Sheet

## Debugging

### When Opening Binary

r2 -d ./[nameOfFile]

### Break, Start, run, and then run again

1. db main
2. dc
3. ood
4. ood (To start again)

### Stepping through binary

- F7 - step
- F8 - step over
- . - gets back to the instruction pointer

## Some Usage

### Renaming functions

1. pdf ( or pdr if in debug mode) @ [address of function]
2. afn [function_name]

### Renaming variables

1. pdf - show function
2. afvn [var name in asm] [personal var name]

### List all functions

- afl

### Print what is inside register

pf z @[register name]

### Show a pseudocode version of code in a c-like syntx

- pdc

### Saving and Loading Projects

#### Saving

Ps [fileName]

#### Loading

Po [fileName]

#### Listing Projects

P

#### Delete Projects

Pd [fileName]


