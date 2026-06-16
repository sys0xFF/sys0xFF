# Anthony Sforzin

Offensive security researcher — kernel & driver vulnerability research, reverse
engineering, fuzzing, and coordinated disclosure.

Software Engineering @ FIAP (São Paulo) · Teaching assistant (Monitor) @ FIAP

I run **[Caustic](https://github.com/causticsec)** — an independent security research
lab focused on vulnerability research and coordinated disclosure across OSS,
drivers/kernel, and firmware.

### Selected work

- **CVE-2025-61155** — co-credited researcher (with Gabriel Maciel Ramos and Gabriel
  Gomes). Access-control flaw in a signed Windows kernel-mode driver (Hotta Studio,
  `GameDriverX64.sys`): an unprivileged IOCTL reaches `ZwTerminateProcess` in kernel
  context, allowing termination of arbitrary processes including protected security
  services (BYOVD / EDR-killer class). NVD: CWE-400 / CVSS 5.5. Subsequently weaponized
  in the wild by Interlock ransomware and documented by FortiGuard Labs and CyberPress.

### Credentials

- CRTA — Certified Red Team Analyst (CyberWarFare Labs)
- NPP — Novo Pentest Profissional (Desec Security)
- FIAP NEXT 2025 — 1st place · FIAP Monitoria Hackathon — 1st place

### Elsewhere

- Caustic — https://github.com/causticsec
- LinkedIn — https://www.linkedin.com/in/anthony-sforzin/
