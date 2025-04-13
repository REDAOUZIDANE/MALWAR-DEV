<p align="center">
  <img src="https://media.giphy.com/media/3o7aCVpH7k5zdykl6c/giphy.gif" alt="Malware Dev Banner" width="80%" />
</p>

<h1 align="center">💀 MALWAR-DEV 💀</h1>
<p align="center">
  <i>Advanced Malware Development & Evasion Research Lab</i>  
  <br><br>
  <img src="https://img.shields.io/badge/EDR-Bypass-blueviolet?style=flat-square&logo=windows" />
  <img src="https://img.shields.io/badge/Windows%20Internals-Deep%20Dive-red?style=flat-square&logo=microsoft" />
  <img src="https://img.shields.io/badge/API%20Hooking-Advanced-yellow?style=flat-square" />
  <img src="https://img.shields.io/badge/POC-Ready-green?style=flat-square&logo=github" />
</p>

---

## 🧠 About This Repo

Welcome to **MALWAR-DEV** — a place for **serious malware devs, red teamers**, and **offensive security researchers**.  
This is **not** script kiddie land. Here, we explore **advanced malware techniques**, **anti-debugging**, **API hooking**, **stealth**, and **bypassing EDR/AV**.

---

<details>
  <summary>🧩 <strong>Techniques Covered</strong></summary>

- ✅ Native API Evasion (`Zw`, `Nt`)
- ✅ API Hooking & Unhooking
- ✅ Shellcode Injection (Classic + Remote)
- ✅ DLL Injection Techniques
- ✅ Inline Hook Bypass
- ✅ Syscall Spoofing & Direct Syscalls
- ✅ Debugger Detection & Anti-Anti-Debug
- ✅ Self-Deletion & Persistence
- ✅ Evasion via TEB/PEB manipulation
- ✅ MSR Register Tricks (`IA32_LSTAR`, `RDMSR`)
</details>

---

// Example: Manual syscall with inline assembly
__asm {
    mov eax, 0x50 // Syscall ID
    lea edx, [esp+4]
    int 0x2e      // Trigger syscall
}

<p align="center"> <img src="https://media.giphy.com/media/26ufnwz3wDUli7GU0/giphy.gif" width="500px" /> <br><br> <i>POC of Shellcode Injection & API Unhooking</i> </p>
💀 MALWAR-DEV
"Learn. Evade. Survive."
import os

pdfs = [f for f in os.listdir() if f.endswith('.pdf')]
with open("README_INDEX.md", "w") as f:
    f.write("# 📄 PDF Index\n\n")
    for pdf in sorted(pdfs):
        f.write(f"- [{pdf}](./{pdf})\n")
REDAOUZIDANE
⚔️ MALWAR-DEV ⚔️

