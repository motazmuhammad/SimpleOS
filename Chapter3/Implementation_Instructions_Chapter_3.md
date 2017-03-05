For some unclear reason when I name the label loop I get errors when I name it otherwise, the compilation happens successfully
This .asm file is compiled on mac osc using the following command
nasm boot_sect.asm -f bin -o boot_sect_assembled.bin
I have only tried it using qemu, however there is no reason it won't work in bochs too.