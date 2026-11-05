<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=28&duration=3000&pause=1000&color=FF0000&center=true&vCenter=true&width=435&lines=0xh3l1x;Red+Team+Leader;Offensive+Security+R%26D" alt="0xh3l1x | Red Team Leader | Offensive Security R&amp;D" />
</h1>

<p align="center">
  <strong>Senior Security Consultant &amp; Red Team Leader</strong><br>
  Global Threat Group (GTG) · IOActive
</p>

<p align="center">
  <a href="https://cgomezsec.com/"><img src="https://img.shields.io/badge/-cgomezsec.com-FF5722?style=for-the-badge&logo=firefox&logoColor=white" alt="Blog"></a>
  <a href="https://www.ioactive.com/"><img src="https://img.shields.io/badge/-Red%20Team%20Leader%20%C2%B7%20GTG%20%C2%B7%20IOActive-cc0000?style=for-the-badge" alt="Red Team Leader · GTG · IOActive"></a>
  <a href="https://github.com/Maldev-Academy"><img src="https://img.shields.io/badge/-Maldev%20Academy-cc0000?style=for-the-badge&logo=hackthebox&logoColor=white" alt="Maldev Academy"></a>
  <a href="#publications-and-talks"><img src="https://img.shields.io/badge/-Published%20Research-4B275F?style=for-the-badge&logo=read-the-docs&logoColor=white" alt="Publications and talks"></a>
</p>

---

I'm Carlos Gómez Quintana, aka `0xh3l1x`, Senior Security Consultant and Red Team Leader within IOActive's Global Threat Group (GTG). I write about what I can share at [cgomezsec.com](https://cgomezsec.com/).

### IOActive / Global Threat Group

I lead the team's technical work and develop the tools we use on engagements. I also work on the team's structure and technical workflows.

- **Offensive development:** implants in C/C++ and C#/.NET, DLL sideloading, signed binary abuse, BOFs, custom UDRLs, payload staging, and testing against production EDR products.
- **Identity security:** Active Directory and Microsoft Entra ID attack paths, privilege escalation, lateral movement, token manipulation, conditional access bypasses, and cross-tenant scenarios.

---

### Vulnerability Research

I use LLMs to review code, then test suspected bugs against real builds. My [IOActive article](https://www.ioactive.com/llm-assisted-vulnerability-research-finding-real-bugs-with-code-reasoning-models/) follows that process through two Angular findings and their fixes, from threat modeling to checking the patched versions.

| CVE | Product | Vulnerability | Contribution |
|---|---|---|---|
| [CVE-2026-68945](https://github.com/advisories/GHSA-jhpw-976m-542j) | Angular | Different request parameters could produce the same `HttpTransferCache` key, causing the wrong cached response to be reused. | Research and patch development. |
| [CVE-2026-69151](https://github.com/advisories/GHSA-jj27-h5hq-8x99) | Angular | A translation file could inject JavaScript through event-handler attributes marked for i18n. | Research and patch development. |
| [CVE-2026-105803](https://github.com/git-lfs/git-lfs/releases/tag/v3.8.1) | Git LFS | A malicious repository's `.lfsconfig` could make Git LFS run an arbitrary program as a custom transfer adapter. | Additional responsible reporter, acknowledged in the release notes. |

---

### Publications and Talks

#### Publications

| Year | Research | Publisher |
|---|---|---|
| 2026 | [LLM-Assisted Vulnerability Research: Finding Real Bugs with Code-Reasoning Models](https://www.ioactive.com/llm-assisted-vulnerability-research-finding-real-bugs-with-code-reasoning-models/) | IOActive |
| 2026 | [Authentication Downgrade Attacks: Deep Dive into MFA Bypass](https://www.ioactive.com/authentication-downgrade-attacks-deep-dive-into-mfa-bypass/) | IOActive |

#### Talks

| Year | Talk | Event |
|---|---|---|
| 2025 | [Cloud Edge Phishing: Breaking the Future of Auth](https://www.ioactive.com/event/out-of-the-box-carlos-gomez-quintana-cloud-edge-phishing-bangkok-thailand/) | Out of the Box, Bangkok |
| 2023 | [Upgrading Rollback-Agnostic Replay Attacks](https://conference.hitb.org/hitbsecconf2023ams/materials/D1%20COMMSEC%20-%20Upgrading%20Rollback%20Agnostic%20Replay%20Attacks%20-%20Carlos%20Gomez.pdf) | Hack In The Box, Amsterdam |

---

### Open Source Tools

| Tool | Purpose |
|---|---|
| [GitHubDeviceCodePhishing](https://github.com/Maldev-Academy/GitHubDeviceCodePhishing) | GitHub OAuth device code phishing. Minimal setup. |
| [GitLabDeviceCodePhishing](https://github.com/Maldev-Academy/GitLabDeviceCodePhishing) | Device code phishing for GitLab cloud and self-managed instances. |
| [shodan-mcp](https://github.com/Hexix23/shodan-mcp) | Shodan MCP server. Query Shodan from AI assistants. |

---

### Maldev Academy

I write modules and build companion tooling for [Maldev Academy](https://github.com/Maldev-Academy) on phishing, authentication attacks, and cloud identity exploitation. Protocol internals, working implementations, OPSEC. Topics include MFA downgrade paths where weaker fallback methods remain available.

<details>
<summary>Training modules and companion tooling</summary>

#### Training modules

| # | Module | Target | Technique |
|---|---|---|---|
| 01 | Microsoft Device Code Phishing | M365 | OAuth 2.0 device code flow abuse |
| 02 | GitHub Device Code Phishing | GitHub | Device code phishing against GitHub OAuth |
| 03 | Illicit Consent Grant Attack | M365 | OAuth consent phishing for persistent access |
| 04 | MFA Bypass: Invisible Proxy | M365 | AiTM proxy via Cloudflare Workers |
| 05 | Invisible Proxy: OPSEC | — | Detection evasion and infrastructure hardening |
| 06 | Evilginx Phishlet Development | M365 | Custom phishlet with MFA downgrade capabilities |
| 07 | Evilginx URL Rewriting | Evilginx | Modifying Evilginx URLs to avoid signature detection |
| 08 | GitLab Device Code Phishing | GitLab | Cloud + self-managed instance support |
| 09 | Client Analysis Via Cloudflare Workers | — | Anti-bot, anti-analysis, client fingerprinting |
| 10 | Dynamic Device Code Phishing | Microsoft | Flask app for runtime device code generation |
| 11 | MFA Bypass Via Azure AiTM | Azure AD | AiTM via Azure Functions + Azure Front Door |
| 12 | Google Phishing: BotGuard, Browser Automation, Chrome Sync | Google | BotGuard analysis, CDP browser automation, and Chrome Sync research |
| 13 | Phishing Passkeys | FIDO2/WebAuthn | Synced passkeys and hardware-key authentication flows, downgrade paths, and session capture |
| 14 | ConsentFix Attack | M365 / OAuth | ConsentFix attack chain with custom tooling for engagements |

#### Companion tooling

These private tools come with the Maldev Academy modules and are available to members.

| Tool | Focus |
|---|---|
| Real-time Phishing Framework | Credential relay with live feedback. Real Chrome per target via nodriver/CDP; Google, GitHub, and Bitwarden support. |
| Cloudflare Workers AiTM Proxy | Serverless reverse proxy for request/response rewriting and credential/session capture. |
| Azure AiTM Proxy | AiTM proxy on Azure Functions and Azure Front Door. |
| Evilginx M365 Phishlet | MFA downgrade paths where weaker authentication methods remain enabled. |
| Google MFA Bypass Framework | BotGuard analysis, browser-driven authentication via nodriver/CDP, and Chrome Sync research. |
| Passkey Phisher | Synced passkeys and hardware-key authentication flows, CDP virtual authenticators, downgrade paths, and session capture. |
| ConsentFix Tool | OAuth consent abuse with the ConsentFix lure flow, packaged for engagements. |
| Client Fingerprinting Worker | Client profiling on Cloudflare Workers: anti-bot checks, sandbox detection, browser fingerprinting, and geo filtering. |

</details>

---

### Current Research

I'm researching browser-based AiTM phishing through CDP, including BotGuard behavior and Chrome Sync. My FIDO2/WebAuthn work looks at downgrade paths and session handling in real implementations.

For `APT-992`, I'm training specialist models for offensive security. The RL pipeline uses feedback from live security products.

---

### Stack

**Languages:** C/C++, C#/.NET, Rust, Python, Go, x86/x64 assembly, JavaScript, PowerShell, Bash.

**Infrastructure:** Docker, Azure, Cloudflare, Nginx, Linux, GitHub.

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=ff0000&height=80&section=footer" width="100%" alt="" />
</p>

<p align="center"><code>0xh3l1x</code></p>
