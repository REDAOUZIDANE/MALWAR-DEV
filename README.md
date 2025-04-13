<p align="center">
  <img src="https://media.giphy.com/media/3o7aCVpH7k5zdykl6c/giphy.gif" width="80%" alt="Banner">
</p>

<h1 align="center">💀 MALWAR-DEV 💀</h1>
<p align="center"><strong>Learn. Evade. Survive.</strong></p>

<p align="center">
  <img src="https://img.shields.io/badge/RedTeam-Approved-red?style=flat-square" />
  <img src="https://img.shields.io/badge/MalwareDev-Advanced-black?style=flat-square" />
  <img src="https://img.shields.io/badge/EDR-Bypass-blueviolet?style=flat-square" />
</p>

---

## 🧠 Welcome

Welcome to **MALWAR-DEV** — a place for **serious malware devs**, **red teamers**, and **offensive security researchers**.

> ⚠️ This is not script kiddie land.

Here, we explore 🔍:
- Advanced **malware techniques**
- **Anti-debugging**
- **API hooking & unhooking**
- **Stealth & evasion**
- **EDR/AV bypassing**
- Native Windows internals

---

## 🧩 Techniques Covered

- Direct Syscalls (Win64)
- Shellcode Injection (local & remote)
- DLL Injection (Manual Mapping / Reflective)
- Hook Bypass (IAT, EAT, Inline)
- Native API (Zw/Nt) Obfuscation
- TEB/PEB Tampering
- Syscall Spoofing
- MSR Trickery (`IA32_LSTAR`, `RDMSR`)
- Self-deletion and stealth
- Anti-debugging and patch detection

---

## ⚙️ Example Snippet

```cpp
// Manual syscall with inline assembly
__asm {
    mov eax, 0x50        // Syscall ID
    lea edx, [esp+4]     // Pointer to arguments
    int 0x2e             // Trigger syscall (legacy method)
}

