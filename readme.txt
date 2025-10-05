# Assembly Game Project 🎮

A graphical DOS game written in **x86 Assembly (Mode 13h)**.  
Built for **DOSBox** — displays graphics and text using BIOS interrupts.

## 🧱 Features
- Runs in 320x200 graphics mode (0x13)
- Custom image/logo display
- "Start Game" screen text in graphics mode
- Uses Python script to convert images to `.asm` arrays

## 🖥️ Run Instructions
1. Assemble and run in DOSBox:
   ```bash
   nasm -f bin game.asm -o game.com
   game.com
