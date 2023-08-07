- Aims to allow more [[Fetch Decode Execute cycle (FDE Cycle)|FDE cycles]] to be executed to happen at once
- Aims to minimise the idle time of the [[CPU]]
- Only works with [[RISC Processor|RISC processors]] as each instruction is exactly one [[Fetch Decode Execute cycle (FDE Cycle)|FRE cycle]]

Without Pipelining :

Cycle | Fetch | Decode | Execute
:--|:--:|:--:|:--:
1| Instruction 1 |  | 
2|  | Instruction 1 | 
3|  |  | Instruction 1
4| Instruction 2 |  | 
5|  | Instruction 2 | 
6|  |  | Instruction 2

With Pipelining :

Cycle | Fetch | Decode | Execute
:--|:--:|:--:|:--:
1| Instruction 1 |  | 
2| Instruction 2 | Instruction 1 | 
3| Instruction 3 | Instruction 2 | Instruction 1
4| Instruction 4 | Instruction 3 | Instruction 2
5| Instruction 5 | Instruction 4 | Instruction 3
6| Instruction 6 | Instruction 5 | Instruction 4

