# 4byteredstonecomputer-minecraft-littlebigredstone
Documentation of my first Redstone Computer, made in Minecraft with Little Big Redstone.

Version: Minecraft NeoForge 1.21.1  
Required Mods: Litte Big Redstone, TesseractAPI (NeoForge), GuideMe.

[youtubeShowcase](https://youtu.be/CrhyAOjgtU8)

- Turing-incomplete: it has no data-dependent repetition, meaning there are no conditional branch instructions (e.g. "If Register 1 = 0, jump to instruction 5");

- 144 microchips used;
- Took me 3 weeks to built it;
- Buttons are there to edit program memory, lock/unlock registers, add 1 to the program counter or to start the computer;
- Able to add/subtract registers and load the result in another register (you can also load numbers directly from the program memory (Immediate Adressing Mode);

- 4 bytes of registers: 1 bit per microchip, 1 byte for storing each number;

- Instruction Memory: 1 byte per microchip, meaning there are 8 instruction memory adresses ("lines"). ;

- Arithmetic Logic Unit (ALU): 8 full adders in series (1 full adder per microchip), also capable of subtraction;

- Program Counter (PC): 1.2 second clock cycle, always jumps to the next memory address;
