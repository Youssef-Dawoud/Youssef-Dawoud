### Hi, I'm Youssef 👋

Cybersecurity Engineering M.Sc. candidate at **Politecnico di Torino** (graduating November 2026). I work where applied cryptography meets systems security.

#### What I'm working on
**Master's thesis:** *An OpenSSL Engine for Offloading Cryptography to Trusted Hardware on Industrial Gateways*

I extended an existing OpenSSL engine that moves an application's cryptography into a Trusted Execution Environment with no changes to the application, and moved it onto real OP-TEE (Arm TrustZone) on an NXP i.MX7 board backed by its CAAM crypto engine. I wrote five new Trusted Applications, so TLS 1.2 and 1.3 handshakes (including X25519) run end to end in the secure world, with ECDSA/RSA keys generated and kept inside the TEE. Validated with 129 automated checks on OP-TEE 4.8 and benchmarked against plain OpenSSL and Linux's CAAM driver.

**Upstream:** found a bug in OP-TEE's CAAM RSA driver that stopped it using CRT keys since 2020 (RSA-2048 signing 131 → 36 ms once fixed). Fix submitted as [OP-TEE PR #8140](https://github.com/OP-TEE/optee_os/pull/8140), with [issue #8139](https://github.com/OP-TEE/optee_os/issues/8139) reporting a related hang with CAAM black keys.

#### Offensive security
- [polito-ctf-writeups](https://github.com/Youssef-Dawoud/polito-ctf-writeups): write-ups from my master's CTF coursework (binary exploitation, web, reverse engineering)
- [Hacker101CTF](https://github.com/Youssef-Dawoud/Hacker101CTF): web exploitation write-ups (SQLi, XSS, IDOR, broken access control), with the reasoning behind each solve

#### Other projects
- [stream-safe](https://github.com/Youssef-Dawoud/stream-safe) + [stream-safe-backend](https://github.com/Youssef-Dawoud/stream-safe-backend): encrypted, channel-based chat with symmetric encryption and key exchange

#### Background
- Teaching Assistant for Hardware & Wireless Security and Web Applications at Polito
- Thales CipherTrust Data Security Platform (CDSP) Core Engineer
- One year as a full-stack engineer (Node.js, React, AWS) before my master's

**Tools:** OpenSSL, OP-TEE, QEMU, radare2, pwntools, Burp Suite  
**Languages:** C/C++, Python, Go, TypeScript

Open to security engineering roles in Italy, across Europe or remote. Authorized to work in Italy.

[Portfolio](https://youssef-dawoud.github.io/youssef-portfolio/) · [LinkedIn](https://www.linkedin.com/in/youssef-dawoud25/)
