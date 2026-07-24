# 4byteredstonecomputer-minecraft-littlebigredstone
Documentation of my first Redstone Computer, made in Minecraft with Little Big Redstone.

Version: Minecraft NeoForge 1.21.1  
Required Mods: Litte Big Redstone, TesseractAPI (NeoForge), GuideMe.

[youtubeShowcase](https://youtu.be/CrhyAOjgtU8)

- 144 microchips used, took me 3 weeks to built it;

- Buttons are there to edit instruction memory, lock/unlock registers, add 1 to the program counter or to start the computer;

- Turing-incomplete: it has no data-dependent repetition, meaning there are no conditional branch instructions (e.g. "If Register 1 = 0, jump to instruction 5");

- 4 bytes of registers: 1 bit per microchip, 1 byte for storing each number;

- Arithmetic Logic Unit (ALU): 8 full adders in series (1 full adder per microchip), also capable of subtraction;

- Program Counter (PC): 1.2 second clock cycle, always jumps to the next instruction memory address, making it Turing-incomplete;

- Instruction Memory: 1 byte per microchip, meaning there are 8 sets of instructions ("lines"). In each set, you are able to input two registers (or numbers from the instruction memory itself, which is called Immediate Adressing Mode) into the ALU, decide the operation (add/sub) you want to perform, and then load the result into 1 or more registers;

