# ROOT ME CRACKING CHALLENGES
**Website**: [Root Me Cracking](https://www.root-me.org/en/Challenges/Cracking/)  

**Overview**: Reverse binaries and crack executables.  

**Description**: This series of challenges will help you understand the inner workings of compiled languages. Disassemble the binaries provided to solve the crackmes at the assembly level.  

**Prerequisites**:
- Advanced understanding of assembly languages on various architectures (x86, ARM, MIPS ...).
- Understanding of the different executable formats (ELF, PE, etc.).
- Mastery in the use disassemblers and debuggers.

# STRUCTURE OF CHALLENGES
This will be organized by the difficulty and techniques having been used.

## 💦 Sanitizer
<ins>Description</ins>: This category focuses on the basic file structure and fundamental knowledge of Assembly.

<ins>Challenges</ins>: **8 units**  
 - [x] 1. ELF x86 - 0 protection (5)  
 - [ ] 2. ELF x86 - Basic (5)  
 - [ ] 3. PE x86 - 0 protection (5)  
 - [ ] 4. ELF C++ - 0 protection (10)  
 - [ ] 5. Godot - 0 protection (10)  
 - [ ] 6. PE DotNet - 0 protection (10)  
 - [ ] 22. Basic ? crackme (25)  
 - [ ] 50. PE x86 - AutoPE (45)  

<ins>Skills</ins>:  
  - Computer architecture (Registers, Stack, Heap)
  - Basic Assembly (x86, x64): MOV, CMP, JMP, TEST, CALL
  - Executable format: PE Header (Windows), ELF Header (Linux)
  - Binary patching

<ins>Tools</ins>:
  - Disassembler: IDA Free, Ghidra, Binary Ninja (Cloud)
  - Hex Editor: HxD, ImHex
  - Command Line: file, strings, objdump

## 🤡 Baby 
<ins>Description</ins>: This category focuses on the algorithm in order to understand keygen process.

<ins>Challenges</ins>: **18 units**  
   - [ ] 9. ELF x64 - Golang basic (15)  
   - [ ] 10. ELF x86 - Fake Instructions (15)  
   - [ ] 16. ELF x64 - Basic KeygenMe (20)  
   - [ ] 27. ELF x86 - CrackPass (30)  
   - [ ] 28. ELF x86 - ExploitMe (30)  
   - [ ] 29. ELF x86 - Random Crackme (30)  
   - [ ] 32. PE x86 - Xor Madness (30)  
   - [ ] 35. ELF x64 - Crackme automating (35)  
   - [ ] 42. ELF x64 - Rust backdoor (40)  
   - [ ] 43. ELF x64 - Rust Crackme (40)  
   - [ ] 48. PE DotNet - KeygenMe (45)  
   - [ ] 53. ELF x86 - KeygenMe (50)  
   - [ ] 54. HackerMan (50)  
   - [ ] 59. ELF x64 - KeyGenMe (60)  
   - [ ] 60. ELF x64 - Anti-debug and equations (65)  
   - [ ] 65. PE32+ - KeygenMe (85)  
   - [ ] 68. Ringgit (110)  
   - [ ] 70. White-Box Cryptography #2 (130)  

<ins>Skills</ins>:
  - Reverse logic
  - Basic crypto analysis
  - Scripting
  - Compiler

<ins>Tools</ins>:
  - Debugger: x64dbg (Windows), GDB/GEF (Linux)
  - Crypto Indentifiers: PEiD (Krypto ANALyzer plugin FindCrypt)

## 😰 Easy Crazy
<ins>Description</ins>: This category focuses on the programming languages not being compiled but assembled or running on virtual machine.

<ins>Challenges</ins>: **20 units**  

*DotNet*: 
  - [ ] 20. PE DotNet - Basic Crackme (20)  
  - [ ] 19. PE DotNet - Basic Anti-Debug (20)  
  - [ ] 57. PE DotNet - Memory Protect (55)

*Android (APK)*:
  - [ ] 7. APK - Introduction (15)  
  - [ ] 14. APK - Flutter Debug (20)  
  - [ ] 40. APK - Anti-Debug (40)  
  - [ ] 41. APK - Insomni'Droid (40)  
  - [ ] 45. APK - Root My Droid (45)

*Python*: 
  - [ ] 21. PYC - ByteCode (20)  
  - [ ] 51. PYC - Self Modifying (Byte)Code (45)  
  - [ ] 52. PYC - Snakeygen (45)

*Game Engine*: 
  - [ ] 12. Godot - Bytecode (15)  
  - [ ] 18. Godot - Mono (20)  
  - [ ] 55. Unity - Mono - Basic Game Hacking (50)  
  - [ ] 61. Unity - IL2CPP - Basic Game Hacking (65)  
  - [ ] 17. Unity3D Save handling (20)  
  - [ ] 24. Lua - Bytecode (25)  
  - [ ] 37. Godot - 3D model (35)

*Web/Script*: 
  - [ ] 31. PDF - Javascript (30)  
  - [ ] 33. Powershell DeObfuscation (30)  

<ins>Skills</ins>:
  - Understanding Bytecode and Intermediate Language (IL/MSIL, Smali, P-code)
  - Decompilation
  - Compiled file (pyc, Lua)
  - APK file structure

<ins>Tools</ins>:
  - .NET: dnSpy, dnSpyEx, ILSpy
  - Java/APK: Jadx-gui, APKTool, Bytecode Viewer
  - Python: uncompyle6, pycdc
  - Game: Godot RE Tools, Unity Assets Bundle Extractor

## 😩 Medium
<ins>Description</ins>: This category focuses on de-obsfucation

<ins>Challenges</ins>: **11 units**  
  - [ ] 11. ELF x86 - Ptrace (15)  
  - [ ] 23. ELF x86 - No software breakpoints (25)  
  - [ ] 39. PE x86 - SEHVEH (35)
  - [ ] 46. ELF x64 - Nanomites - Introduction (45)  
  - [ ] 47. ELF x86 - Anti-debug (45)  
  - [ ] 49. PE x64 - Tables in shambles (45)  
  - [ ] 62. ELF x64 - Nanomites (70)  
  - [ ] 63. ELF x86 - Packed (70)  
  - [ ] 64. PE x86 - RunPE (75)  
  - [ ] 67. ELF x64 - Hidden Control Flow (100)  
  - [ ] 69. Voracious Nanomites (110)  

<ins>Skills</ins>:
  - Unpacking: Original Entry Point OEP, dump process
  - Anti-Debug Bypassing: RDTSC, ptrace, IsDebggerPresent
  - De-obfuscation
  - Nanomites: Exception Handler

<ins>Tools</ins>:
  - Unpacker: UPX (-d), CFF Explorer
  - Anti-Anti-Debug: ScyllaHide, TitanHide
  - Memory Dumping: Process Hacker, Scylla

## 😈 Exotic 
<ins>Description</ins>: This category focuses on the Instruction Set other than classic x86.

<ins>Challenges</ins>: **11 units**  
*MIPS*: 
  - [ ] 8. ELF MIPS - Basic Crackme (15)

*ARM*: 
  - [ ] 15. ELF ARM - Basic Crackme (20)  
  - [ ] 26. ELF ARM - crackme 1337 (30)  
  - [ ] 34. ELF ARM - Crypted (35)  
  - [ ] 25. MachO x64 - keygenme or not (25)

*WebAssembly*:
  - [ ] 13. WASM - Introduction (15)  
  - [ ] 56. WASM - Find the NPC (50)

*Console/Firmware*: 
  - [ ] 30. GB - Basic GameBoy crackme (30)  
  - [ ] 38. NRO ARM - Switch homebrew (35)  
  - [ ] 44. PE x64 - UEFI Secure Boot (40)

*Blockchain*: 
  - [ ] 36. EVM - Bytecode (35)  

<ins>Skills</ins>:
  - RISC (ARM, MIPS). Noting the Link Register
  - WebAssembly (Stack Machine)
  - Emulation
  - Smart Contract

<ins>Tools</ins>:
  - Emulators: QEMU, Emu8051
  - WASM: The WebAssembly Binary Toolkit wabt, Chrome Developer Tools
  - Disassembler: Ghidra

## 💀 Out-of-control
<ins>Description</ins>: This category focuses on the virtual machines, weird CPU with specific instruction sets.

<ins>Challenges</ins>: **2 units**  
  - [ ] 58. Bash - VM (60)  
  - [ ] 66. ELF x86 - VM (90)  

<ins>Skills</ins>:
  - Virtual machine structure: V-IP, V-SP, Dispatcher/Handler Table
  - Disassembler Specifying
  - Trace Analysis
  - Automation

<ins>Tools</ins>:
  - Graphing: Graphviz
