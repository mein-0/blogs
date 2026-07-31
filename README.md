# blogs

CyberAZE community üzvləri tərəfindən yazılmış bloqların indeksi

## Mündəricat

- [Kernel & Exploit Development](#kernel--exploit-development)
- [Malware Analysis & Reverse Engineering](#malware-analysis--reverse-engineering)
- [OSINT](#osint)
- [Video & Talks](#video--talks)

## Kernel & Exploit Development

- [Kod execute dövrü bitdi?](https://medium.com/@1dont/kod-execute-dövrü-bitdi-a59aefadd228) - Windows kernel mitigationlar seriyası (1/3). DEP, SMEP, HVCI və exploit development-in təkamülü.
- [Kernel bizə inanır? (!)](https://medium.com/@1dont/kernel-bizə-inanır-c39af8f5869d) - HEVD Stack Overflow zəifliyi ilə kernelə shellcode injection. Token stealing-in avtomatlaşdırılması.
- [Windows Kernel Data-Only Attack](https://medium.com/@1dont/windows-kernel-data-only-attack-5ac958b71345) - Kod execute etmədən privilege escalation. `_SEP_TOKEN_PRIVILEGES` manipulyasiyası, PPL bypass.
- [BYOVD: 2 Driver, 2 Primitiv, 1 Attack Chain](https://medium.com/@1dont/byovd-2-driver-2-primitiv-1-attack-chain-e7450ba7e8cf) - CVE-2026-0828 (kill primitivi) və CVE-2025-7771 (arbitrary R/W) ilə SYSTEM-ə qədər tam attack chain.
- [Fortinet is dead?](https://medium.com/@1dont/fortinet-is-dead-45780b6b008b) - FortiClient-in "anti-exploit" driverində zəiflik. 8 baytlıq mesajla PPL bypass və Defender/LSASS kill.
- [CVE-2021–30807 IOMobileFrameBuffer Out-of-Bounds Write](https://medium.com/@1dont/cve-2021-30807-iomobileframebuffer-out-of-bounds-write-34ee5ca60f6e) - iOS kernel analizi. OOB write-dan heap feng shui və tfp0-a qədər jailbreak zənciri.

## Malware Analysis & Reverse Engineering

- [Wanna Cry reverse engineering](https://medium.com/@1dont/wanna-cry-reverse-engineering-c24063419892) - WannaCry ransomware-in Ghidra/IDA/x64dbg ilə analizi. CryptoAPI sui-istifadəsi, persistence mexanizmi, kill-switch.

## OSINT

- [OSINT № 5](https://medium.com/@nuranabdulhamidov/nuran-abdulhamidov-osint-5-f5eb2432cb99) - TikTok videosunun geolocation tədqiqi. Vizual ipucları ilə hadisə yerinin müəyyən edilməsi.
- [Epstein, Profumo Affair & OSINT](https://www.linkedin.com/posts/mahammad-hamzayev_epstein-profumoaffair-osint-ugcPost-7431850408798576641-u8qL) - Tarixi casusluq skandallarından müasir OSINT/OPSEC dərsləri. Zəif məlumat yox, yanlış əminlik problemi.

## Video & Talks

- [Praktiki AI Part1: Agentic Sistemlərin Arxitekturası](https://www.youtube.com/watch?v=Y3BaTG-ctvU) - Agentic AI sistemlərin arxitekturası. Model/agent/context/harness anlayışları, prompt engineering-dən context engineering-ə, tool calling, agent loop və skills.
