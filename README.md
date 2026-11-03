## Hi there 👋
# 💀 Gantosay // Exploit Developer & Reverse Engineer

```assembly
section .text
    global _start

_start:
    ; 9+ Years of CTF & Weaponized Exploit Development
    mov rdi, [target_binary]
    call bypass_mitigations    ; ASLR/PIE, DEP/NX, Canary, CFG, CET
    call get_rip_control       ; Stack/Heap/Format-String primitives
    call pwn_the_world
```

---

### 🛡️ Core Vulnerability & Exploitation Research
Focusing on low-level memory corruption and bypassing modern mitigations across different architectures (**x86/x64, ARM64, MIPS**).

*   **Userland Exploitation:** Advanced Heap Feng Shui (Tcache poisoning, House of Lore/Force/Einherjar), IO_FILE structures, OCG (One Gadget Constraints), and JOP/ROP chain crafting.
*   **Kernel & Hypervisor:** Linux Kernel Pwn (UAF, Race Conditions, SMEP/SMAP/KASLR bypass), VM Escapes, and Browser Exploitation (V8/JavaScriptCore).
*   **Reverse Engineering:** Custom Packer unpacking, Devirtualization (VM-based obfuscation), Cryptographic implementation analysis, and Automated Taint Analysis.

---

### 🧰 The Arsenal (Low-Level Stack)

```text
[Languages]      --> C,C++,  Python, Perl, Javascript, Bash, x86/64 ASM, ARM64 ASM,
[Debug/Dynamic]  --> GDB + GEF/pwndbg, Objdump, rr (Record and Replay), Frida, QEMU
[Static/Reversing]--> IDA Pro, Ghidra (Custom Scripts & Extensions), Rizin, Binary Ninja
[Automation]     --> Pwntools, Angr (Symbolic Execution), Triton, Z3 Theorem Prover
```

---

### 🏆 CTF Pipeline & Write-ups
My automated and manual exploitation walkthroughs are categorized in my repositories:

*   🚀 **[CTF-Writeups](https://github.com/Gantosay/CTF-Writeups/tree/main):** High-quality walkthroughs focused on Heap Exploitation, Kernel Pwn, and complex Reverse Engineering challenges.
*   🛠️ **[Pwn-Tools-Custom](https://github.com/Gantosay/Pwn-Tools-Custom/tree/main):** My personal collection of exploit templates, GDB scripts, and heap visualizers.

---
### 🌐 Connect With Me

* 👾 **Discord:** `Gantosay`
