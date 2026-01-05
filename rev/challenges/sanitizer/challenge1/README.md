# CHALLENGE 1: ELFx86 - 0 Protection

## Table of Content
1. [Overview](#1-overview)
2. [Name of the challenge](#2-name-of-the-challenge)
3. [Write-up](#3-write-up)
4. [Wrap-up](#4-wrap-up)

## 1. Overview

- **Source**: https://www.root-me.org/en/Challenges/Cracking/ELF-x86-0-protection
- **Difficulty**: ⭐🔲🔲🔲🔲
- **Tool**: Varied

## 2. Name of the challenge

- **ELF**: Executable file running on Linux
- **x86**: Compiled on CPU of 32-bit architecture
- **0 Protection**:
  - No striped
  - No anti-debug
  - No obfuscation
  - No packer
  
## 3. Write-up

### Solution 1: strings command


### Solution 2: IDA

**Author**: CodeAndSec  

**Step-by-step solution**:
1. Open the file in IDA
2. You’ll notice first it calls getString with ebp+s1 string as location to store result of getString (user-input)
3. Then you’ll see it calls _strcmp to compare ebp+s1 (user input) with ebp+s2 which is as you can see string 123456789

### Solution 3: Tracer

**Author**: chesteroni  

**Step-by-step solution**:
1. Choosing a tracer, for example, *ltrace*  
`sudo apt-get install ltrace`
2. Simply run the binary through a tracer  
`ltrace ./ch1.bin`
3. Enter any password and observe the dump for strcmp call  
`strcmp("yourpass", "123456789")`  
4. Get flag

## 4. Wrap-up
strcmp: string compare
