# micro16-compiler
Compiles micro16 assembly into elf64

## EXAMPLES

**Hello World**
```asm
main:
    SETA 'H'
    OUTA 0x10
    SETA 'e'
    OUTA 0x10
    SETA 'l'
    OUTA 0x10
    SETA 'l'
    OUTA 0x10
    SETA 'o'
    OUTA 0x10
    SETA ' '
    OUTA 0x10
    SETA 'W'
    OUTA 0x10
    SETA 'o'
    OUTA 0x10
    SETA 'r'
    OUTA 0x10
    SETA 'l'
    OUTA 0x10
    SETA 'd'
    OUTA 0x10
    SETA '!'
    OUTA 0x10
    SETA 10
    OUTA 0x10
    HLT
```

## DEPENDENCIES

Youll need `nasm`, `ld`, and a Linux system. Tested on Arch Linux.
