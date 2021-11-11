# InstructionDecoder
A simple processor based on the simplified 2-step instruction cycle.

This assignment is to design a simple processor based on the simplified 2-step instruction cycle 
shown in Figure 3.3 of our textbook. You will be creating two functions in software, one to 
simulate the fetch next instruction cycle, fetchNextInstruction(), and one to simulate the 
execute instruction cycle, executeInstruction(). Neither of these functions will have parameters 
nor will they return values. They will operation on global data meant to simulate the registers 
and memory of the processor. 
 
 
This simulated machine consists of four registers that will be represented in your software with 
four global variables. 
• PC -- Program counter (16 bit) used to hold the address of the next instruction to execute. It is 
initialized to zero. 
• IR -- Instruction register (8 bit) used to hold the current instruction being executed 
• MAR -- Memory Address Register (16 bit) used to hold an address being used as a pointer, i.e., 
an indirect reference to data in memory 
• ACC -- Accumulator (8 bit) used to operate on data 
 
 Memory will be simulated with an array memory[65536]. 
