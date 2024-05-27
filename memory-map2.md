| Linear Address Range | Real-Mode Address Range | Memory Type | Use |
|---------------------|-------------------------|-------------|-----|
| 0x00000 - 0x003FF    | 0x0000:0000 - 0x0000:03FF| RAM         | Real-mode interrupt vector table (IVT) |
| 0x00400 - 0x004FF    | 0x0040:0000 - 0x0040:00FF| BIOS Data   | BIOS data area (BDA) |
| 0x00500 - 0x09FBFF   | 0x0050:0000 - 0x9000:FBFF| RAM         | Free conventional memory (below 1 meg) |
| 0x09FC00 - 0x09FFFF  | 0x9000:FC00 - 0x9000:FFFF| BIOS Data   | Extended BIOS data area (EBDA) |
| 0x0A0000 - 0x0BFFFF  | 0xA000:0000 - 0xB000:FFFF| Video RAM   | VGA framebuffers |
| 0x0C0000 - 0x0C7FFF  | 0xC000:0000 - 0xC000:7FFF| ROM         | Video BIOS (32K is typical size) |
| 0x0C8000 - 0x0EFFFF  | 0xC800:0000 - 0xE000:FFFF| NOTHING     | - |
| 0x0F0000 - 0x0FFFFF  | 0xF000:0000 - 0xF000:FFFF| ROM         | Motherboard BIOS (64K is typical size) |
| 0x100000 - 0xFEBFFFF | RAM                     | Free extended memory (1 meg and above) |
| 0xFEC00000 - 0xFFFFFFFF | Various               | Motherboard BIOS, PnP NVRAM, ACPI, etc. |
