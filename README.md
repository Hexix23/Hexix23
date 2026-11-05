<h1 align="center">
  <img src="assets/header.svg" width="100%" alt="Carlos Gómez Quintana · 0xh3l1x · Red Team, Security Research and Offensive Development" />
</h1>

<table align="center">
<tr>
<td width="50%" align="center" valign="top">
<p><a href="https://www.ioactive.com/"><img src="assets/ioactive.svg" width="146" height="64" alt="IOActive" /></a></p>
<p><strong>IOActive</strong><br>Global Threat Group (GTG)</p>
<p>Senior Security Consultant<br><strong>Red Team Leader</strong></p>
</td>
<td width="50%" align="center" valign="top">
<p><a href="https://github.com/Maldev-Academy"><img src="assets/maldev-academy.png" width="64" height="64" alt="Maldev Academy" /></a></p>
<p><strong>Maldev Academy</strong></p>
<p><strong>Security Researcher &amp; Developer</strong></p>
</td>
</tr>
</table>

<p align="center">
  <a href="https://cgomezsec.com/"><img src="https://img.shields.io/badge/-cgomezsec.com-FF5722?style=for-the-badge&logo=firefox&logoColor=white" alt="Blog"></a>
  <a href="https://www.ioactive.com/"><img src="https://img.shields.io/badge/-Red%20Team%20Leader%20%C2%B7%20GTG%20%C2%B7%20IOActive-cc0000?style=for-the-badge" alt="Red Team Leader · GTG · IOActive"></a>
  <a href="https://github.com/Maldev-Academy"><img src="https://img.shields.io/badge/-Security%20Researcher%20%26%20Developer%20%C2%B7%20Maldev%20Academy-cc0000?style=for-the-badge&logo=hackthebox&logoColor=white" alt="Security Researcher &amp; Developer · Maldev Academy"></a>
  <a href="#publications-and-talks"><img src="https://img.shields.io/badge/-Published%20Research-4B275F?style=for-the-badge&logo=read-the-docs&logoColor=white" alt="Publications and talks"></a>
</p>

<p align="center">
  <a href="#internal-red-team-work">Internal Work</a> ·
  <a href="#vulnerability-research">CVEs</a> ·
  <a href="#publications-and-talks">Publications &amp; Talks</a> ·
  <a href="#maldev-academy">Maldev Academy</a> ·
  <a href="#tools">Tools</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/-C/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white" alt="C/C++" />
  <img src="https://img.shields.io/badge/-C%23/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white" alt="C#/.NET" />
  <img src="https://img.shields.io/badge/-Rust-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust" />
  <img src="https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/-Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go" />
  <img src="https://img.shields.io/badge/-x86/x64%20ASM-6E4C13?style=flat-square&logo=assemblyscript&logoColor=white" alt="x86/x64 ASM" />
  <img src="https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/-PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white" alt="PowerShell" />
  <img src="https://img.shields.io/badge/-Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white" alt="Bash" />
</p>

---

I'm Carlos Gómez Quintana, aka `0xh3l1x`, Senior Security Consultant and Red Team Leader within IOActive's Global Threat Group (GTG). I'm also a Security Researcher and Developer at [Maldev Academy](https://github.com/Maldev-Academy). I write about what I can share at [cgomezsec.com](https://cgomezsec.com/).

### Internal Red Team Work

<table>
<tr>
<td width="50%" valign="top">
<p align="center"><img src="https://img.shields.io/badge/-Operations%20%26%20Tooling-ef4444?style=for-the-badge&labelColor=0d1117" alt="Operations and tooling" /></p>

I lead technical development and build the tools we use on engagements. I also help define the team's structure and technical workflows.

</td>
<td width="50%" valign="top">
<p align="center"><img src="https://img.shields.io/badge/-Identity%20%26%20Cloud-0078D4?style=for-the-badge&labelColor=0d1117" alt="Identity and cloud" /></p>

Active Directory and Microsoft Entra ID attack paths, privilege escalation, and lateral movement. OAuth device-code and consent flows, token manipulation, conditional access, and cross-tenant scenarios.

</td>
</tr>
<tr>
<td width="50%" valign="top">
<p align="center"><img src="https://img.shields.io/badge/-Browser%20Operations-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white&labelColor=0d1117" alt="Browser operations" /></p>

CDP-driven AiTM, BotGuard behavior, Chrome Sync, and session handling. FIDO2/WebAuthn research focuses on downgrade paths in real implementations.

</td>
<td width="50%" valign="top">
<p align="center"><img src="https://img.shields.io/badge/-Infrastructure%20%26%20OPSEC-F38020?style=for-the-badge&logo=cloudflare&logoColor=white&labelColor=0d1117" alt="Infrastructure and OPSEC" /></p>

Cloudflare Workers and Azure Functions / Front Door for engagement infrastructure. Request and response rewriting, client profiling, anti-bot checks, and sandbox detection.

</td>
</tr>
<tr>
<td width="50%" valign="top">
<p align="center"><img src="https://img.shields.io/badge/-Offensive%20Development-ef4444?style=for-the-badge&labelColor=0d1117" alt="Offensive development" /></p>

Implants in C/C++ and C#/.NET, BOFs, custom UDRLs, payload staging, DLL sideloading, and signed binary abuse. Tested against production EDR products.

</td>
<td width="50%" valign="top">
<p align="center"><img src="https://img.shields.io/badge/-AI--Assisted%20Research-7C3AED?style=for-the-badge&labelColor=0d1117" alt="AI-assisted research" /></p>

LLM-assisted code review, runtime checks, and patch validation. For <code>APT-992</code>, I'm training specialist models for offensive security with RL feedback from live security products.

</td>
</tr>
</table>

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

<table>
<tr>
<td width="50%" valign="top">
<p><img src="https://img.shields.io/badge/IOActive-2026-ef4444?style=flat-square&labelColor=0d1117" alt="IOActive · 2026" /></p>

**[LLM-Assisted Vulnerability Research: Finding Real Bugs with Code-Reasoning Models](https://www.ioactive.com/llm-assisted-vulnerability-research-finding-real-bugs-with-code-reasoning-models/)**

A workflow for turning code-review candidates into confirmed bugs, with runtime tests and patch comparisons.

</td>
<td width="50%" valign="top">
<p><img src="https://img.shields.io/badge/IOActive-2026-ef4444?style=flat-square&labelColor=0d1117" alt="IOActive · 2026" /></p>

**[Authentication Downgrade Attacks: Deep Dive into MFA Bypass](https://www.ioactive.com/authentication-downgrade-attacks-deep-dive-into-mfa-bypass/)**

How weaker fallback methods let authentication flows be downgraded, even when FIDO2/WebAuthn is available.

</td>
</tr>
</table>

#### Talks

<table>
<tr>
<td width="50%" valign="top">
<p><img src="https://img.shields.io/badge/-Authentication%20Research-4285F4?style=flat-square&labelColor=0d1117" alt="Authentication research" /></p>

**Cloud Edge Phishing: Breaking the Future of Auth**

Out of the Box · Bangkok · 2025

Cloudflare Workers and Azure infrastructure for AiTM operations.

[Abstract](https://www.ioactive.com/event/out-of-the-box-carlos-gomez-quintana-cloud-edge-phishing-bangkok-thailand/)

</td>
<td width="50%" valign="top">
<p><img src="https://img.shields.io/badge/-Automotive%20%26%20RF-ef4444?style=flat-square&labelColor=0d1117" alt="Automotive and RF research" /></p>

**Upgrading Rollback-Agnostic Replay Attacks**

<p>Hack In The Box · Amsterdam · 2023<br>HACK::SOHO · 2023<br>ESCAR USA · Detroit</p>

[Slides](https://conference.hitb.org/hitbsecconf2023ams/materials/D1%20COMMSEC%20-%20Upgrading%20Rollback%20Agnostic%20Replay%20Attacks%20-%20Carlos%20Gomez.pdf)

</td>
</tr>
</table>

---

### Current Research

I'm researching browser-based AiTM phishing through CDP, including BotGuard behavior and Chrome Sync. My FIDO2/WebAuthn work looks at downgrade paths and session handling in real implementations.

---

### [`Maldev Academy`](https://github.com/Maldev-Academy)

I write modules and build companion tooling for [Maldev Academy](https://github.com/Maldev-Academy) on phishing, authentication attacks, and cloud identity exploitation. Protocol internals, working implementations, OPSEC. Topics include MFA downgrade paths where weaker fallback methods remain available.

<table>
<tr>
<td>

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

</td>
</tr>
</table>

---

### Tools

#### Open Source

<table>
<tr>
<td width="33%" valign="top">

<p align="center"><b><a href="https://github.com/Maldev-Academy/GitHubDeviceCodePhishing">GitHubDeviceCodePhishing</a></b></p>
<p align="center"><img src="https://img.shields.io/github/stars/Maldev-Academy/GitHubDeviceCodePhishing?style=flat-square&color=ff0000&labelColor=0d1117" alt="GitHubDeviceCodePhishing stars" /> <img src="https://img.shields.io/github/forks/Maldev-Academy/GitHubDeviceCodePhishing?style=flat-square&color=444444&labelColor=0d1117" alt="GitHubDeviceCodePhishing forks" /></p>

GitHub OAuth device code phishing. Minimal setup.

</td>
<td width="33%" valign="top">

<p align="center"><b><a href="https://github.com/Maldev-Academy/GitLabDeviceCodePhishing">GitLabDeviceCodePhishing</a></b></p>
<p align="center"><img src="https://img.shields.io/github/stars/Maldev-Academy/GitLabDeviceCodePhishing?style=flat-square&color=ff0000&labelColor=0d1117" alt="GitLabDeviceCodePhishing stars" /> <img src="https://img.shields.io/github/forks/Maldev-Academy/GitLabDeviceCodePhishing?style=flat-square&color=444444&labelColor=0d1117" alt="GitLabDeviceCodePhishing forks" /></p>

Device code phishing for GitLab cloud and self-managed instances.

</td>
<td width="33%" valign="top">

<p align="center"><b><a href="https://github.com/Hexix23/shodan-mcp">shodan-mcp</a></b></p>
<p align="center"><img src="https://img.shields.io/github/stars/Hexix23/shodan-mcp?style=flat-square&color=ff0000&labelColor=0d1117" alt="shodan-mcp stars" /> <img src="https://img.shields.io/github/forks/Hexix23/shodan-mcp?style=flat-square&color=444444&labelColor=0d1117" alt="shodan-mcp forks" /></p>

Shodan MCP server. Query Shodan from AI assistants.

</td>
</tr>
</table>

#### Internal Tooling — Maldev Academy

<p align="center">
  <a href="https://github.com/Maldev-Academy"><img src="https://img.shields.io/badge/-Maldev%20Academy-cc0000?style=for-the-badge&logo=hackthebox&logoColor=white" alt="Maldev Academy" /></a>
  <img src="https://img.shields.io/badge/-Members%20Only-0d1117?style=for-the-badge&labelColor=0d1117" alt="Members Only" />
  <img src="https://img.shields.io/badge/-Private-444444?style=for-the-badge" alt="Private" />
</p>

<p align="center"><i>These private tools come with the Maldev Academy modules and are available to members.</i></p>

<table>
<tr>
<td width="50%" valign="top">

<p align="center"><b>Real-time Phishing Framework</b></p>
<p align="center"><img src="https://img.shields.io/badge/-AiTM-cc0000?style=flat-square" alt="AiTM" /> <img src="https://img.shields.io/badge/-CDP-4285F4?style=flat-square&logo=googlechrome&logoColor=white" alt="CDP" /> <img src="https://img.shields.io/badge/-Multi--provider-444444?style=flat-square" alt="Multi-provider" /></p>

Credential relay with live feedback. Real Chrome per target via nodriver/CDP; Google, GitHub, and Bitwarden support.

</td>
<td width="50%" valign="top">

<p align="center"><b>Cloudflare Workers AiTM Proxy</b></p>
<p align="center"><img src="https://img.shields.io/badge/-AiTM-cc0000?style=flat-square" alt="AiTM" /> <img src="https://img.shields.io/badge/-Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white" alt="Cloudflare" /> <img src="https://img.shields.io/badge/-Serverless-444444?style=flat-square" alt="Serverless" /></p>

Serverless reverse proxy for request/response rewriting and credential/session capture.

</td>
</tr>
<tr>
<td width="50%" valign="top">

<p align="center"><b>Azure AiTM Proxy</b></p>
<p align="center"><img src="https://img.shields.io/badge/-AiTM-cc0000?style=flat-square" alt="AiTM" /> <img src="https://img.shields.io/badge/-Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" alt="Azure" /> <img src="https://img.shields.io/badge/-Front%20Door-444444?style=flat-square" alt="Front Door" /></p>

AiTM proxy on Azure Functions and Azure Front Door.

</td>
<td width="50%" valign="top">

<p align="center"><b>Evilginx M365 Phishlet</b></p>
<p align="center"><img src="https://img.shields.io/badge/-Phishlet-cc0000?style=flat-square" alt="Phishlet" /> <img src="https://img.shields.io/badge/-M365-0078D4?style=flat-square&logo=microsoft&logoColor=white" alt="M365" /> <img src="https://img.shields.io/badge/-MFA%20Downgrade-444444?style=flat-square" alt="MFA Downgrade" /></p>

MFA downgrade paths where weaker authentication methods remain enabled.

</td>
</tr>
<tr>
<td width="50%" valign="top">

<p align="center"><b>Google MFA Bypass Framework</b></p>
<p align="center"><img src="https://img.shields.io/badge/-Module%2012-cc0000?style=flat-square" alt="Module 12" /> <img src="https://img.shields.io/badge/-Google-4285F4?style=flat-square&logo=google&logoColor=white" alt="Google" /> <img src="https://img.shields.io/badge/-BotGuard-444444?style=flat-square" alt="BotGuard" /></p>

BotGuard analysis, browser-driven authentication via nodriver/CDP, and Chrome Sync research.

</td>
<td width="50%" valign="top">

<p align="center"><b>Passkey Phisher</b></p>
<p align="center"><img src="https://img.shields.io/badge/-Module%2013-cc0000?style=flat-square" alt="Module 13" /> <img src="https://img.shields.io/badge/-FIDO2-0d1117?style=flat-square&logo=fidoalliance&logoColor=white" alt="FIDO2" /> <img src="https://img.shields.io/badge/-WebAuthn-444444?style=flat-square" alt="WebAuthn" /></p>

Synced passkeys and hardware-key authentication flows, CDP virtual authenticators, downgrade paths, and session capture.

</td>
</tr>
<tr>
<td width="50%" valign="top">

<p align="center"><b>ConsentFix Tool</b></p>
<p align="center"><img src="https://img.shields.io/badge/-Module%2014-cc0000?style=flat-square" alt="Module 14" /> <img src="https://img.shields.io/badge/-OAuth-EB5424?style=flat-square&logo=oauth&logoColor=white" alt="OAuth" /> <img src="https://img.shields.io/badge/-M365-0078D4?style=flat-square&logo=microsoft&logoColor=white" alt="M365" /></p>

OAuth consent abuse with the ConsentFix lure flow, packaged for engagements.

</td>
<td width="50%" valign="top">

<p align="center"><b>Client Fingerprinting Worker</b></p>
<p align="center"><img src="https://img.shields.io/badge/-Anti--bot-cc0000?style=flat-square" alt="Anti-bot" /> <img src="https://img.shields.io/badge/-Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white" alt="Cloudflare" /> <img src="https://img.shields.io/badge/-Recon-444444?style=flat-square" alt="Recon" /></p>

Client profiling on Cloudflare Workers: anti-bot checks, sandbox detection, browser fingerprinting, and geo filtering.

</td>
</tr>
</table>

---

### Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=c,cpp,cs,dotnet,rust,python,go,js,bash&theme=dark&perline=9" alt="Languages" />
</p>
<p align="center">
  <img src="https://skillicons.dev/icons?i=docker,azure,cloudflare,nginx,linux,github&theme=dark&perline=6" alt="Infra" />
</p>


---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=ff0000&height=80&section=footer" width="100%" alt="" />
</p>

<p align="center"><code>0xh3l1x</code></p>
