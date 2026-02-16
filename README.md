# kitaOS

## Copyright

© 2026 [Kitamyra]. All rights reserved.

This project is the intellectual property of the author.  
Any copying, distribution or modification without the written permission of the author is prohibited.

## About project

A minimal x86 kernel with a simple filesystem and command-line interface.  
Built from scratch as a learning project and for portfolio.

## Features (so far)
- [x] Bootloader (Multiboot-compliant)
- [x] VGA text output
- [ ] Keyboard input
- [ ] Basic shell
- [ ] Simple filesystem (initramfs)
- [ ] ISO image generation

## Build & run
```bash
make
qemu-system-i386 -cdrom kitaos.iso
```

## Goals
   To understand how operating systems work from the ground up,
   and to create a solid foundation for future low-level projects.
