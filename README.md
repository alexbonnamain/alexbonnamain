<h1 align="center">Alexandre Bonnamain</h1>

<p align="center">
  <b>Cybersecurity Specialist · Red Team · Linux & Infrastructure</b><br>
  <em>15+ years building, securing, and breaking real-world systems.</em>
</p>

<p align="center">
  <img src="https://img.shields.io/github/followers/alexbonnamain?label=follow&style=for-the-badge&logo=github&color=222">
</p>

---

### ⚡ Operational Security Loop

```nasm
section .text
global _start

_start:
    call    init_security        ; prepare environment & trust boundaries
    call    analyze_binary       ; reverse engineering & low-level analysis
    call    exploit_surface      ; identify and break attack surfaces
    call    harden_system        ; apply mitigations & defensive controls
    jmp     _start               ; continuous security lifecycle
