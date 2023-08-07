- Complex Instruction Set Computer (CISC)
- Has a larger instruction set (than [[RISC Processor|RISC]])
- Instructions are built into hardware
- Aim is to accomplish a task with as few lines of code as possible
- One instruction can take more than one clock cycle
- More common in [[Embedded System|embedded systems]] 

[[RISC Processor]] | [[CISC Processor]]
--|--
Compiler has to do more work to translate code into machine code | Compiler has to do less work to translate code into machine code
More [[Main Memory\|RAM]] is required to store the code | Less [[Main Memory\|RAM]] is required to store code as code is shorter
[[Pipelining]] is possible as each instruction is one line | Many specialised instructions even though only a few are used (lots of bloat)