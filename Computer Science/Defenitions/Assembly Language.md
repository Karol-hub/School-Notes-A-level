- A low-level code 
- Converted by an [[Assembler]]
- Just above machine code in terms of simplicity
- Platform specific (unique to device architecture)

Mnemonic | Instruction | Function
---|---|---
ADD| Add| Adds value at given [[Main Memory\|memory]] address to value in [[Registers\|Accumulator]]
SUB| Subtract| Subtracts value at given [[Main Memory\|memory]] address to value in [[Registers\|Accumulator]]
STA| Store| Stores value in [[Registers\|Accumulator]] at given [[Main Memory\|memory]] address
LDA| Load| Loads value at [[Main Memory\|memory]] address to [[Registers\|Accumulator]]
INP| Input| Allows user to input value which will be stored in the [[Registers\|Accumulator]]
OUT| Output| Prints the value currently held in [[Registers\|Accumulator]]
HLT| Halt| End the program
DAT| Data| Creates a flag with a label at which data is stored
BRZ| Branch if zero| Branches to a given address if the value in the [[Registers\|Accumulator]] is zero. This is a [[Selection\|conditional branch]]
BRP| Branch if positive| Branches to a given address if the value in the [[Registers\|Accumulator]] is positive. This is a [[Selection\|conditional branch]]
BRA| Branch always| Branches to a given address no matter the value in the [[Registers\|Accumulator]]. This is an unconditional branch

- [[Modes of Addressing Memory]] 