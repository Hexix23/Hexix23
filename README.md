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

I'm Carlos Gómez Quintana, aka `0xh3l1x`, Senior Security Consultant and Red Team Leader within IOActive's Global Threat Group (GTG). I write about what I can share at [cgomezsec.com](https://cgomezsec.com/).

### IOActive / Global Threat Group

I lead the team's technical work and develop the tools we use on engagements. I also work on the team's structure and technical workflows.

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
<td width="33%">

<p align="center"><b><a href="https://github.com/Maldev-Academy/GitHubDeviceCodePhishing">GitHubDeviceCodePhishing</a></b></p>
<p align="center"><img src="https://img.shields.io/github/stars/Maldev-Academy/GitHubDeviceCodePhishing?style=flat-square&color=ff0000&labelColor=0d1117" alt="GitHubDeviceCodePhishing stars" /> <img src="https://img.shields.io/github/forks/Maldev-Academy/GitHubDeviceCodePhishing?style=flat-square&color=444444&labelColor=0d1117" alt="GitHubDeviceCodePhishing forks" /></p>

GitHub OAuth device code phishing. Minimal setup.

</td>
<td width="33%">

<p align="center"><b><a href="https://github.com/Maldev-Academy/GitLabDeviceCodePhishing">GitLabDeviceCodePhishing</a></b></p>
<p align="center"><img src="https://img.shields.io/github/stars/Maldev-Academy/GitLabDeviceCodePhishing?style=flat-square&color=ff0000&labelColor=0d1117" alt="GitLabDeviceCodePhishing stars" /> <img src="https://img.shields.io/github/forks/Maldev-Academy/GitLabDeviceCodePhishing?style=flat-square&color=444444&labelColor=0d1117" alt="GitLabDeviceCodePhishing forks" /></p>

Device code phishing for GitLab cloud and self-managed instances.

</td>
<td width="33%">

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

### Internal R&D

Things I work on that aren't public.

<table>
<tr>
<td width="33%" align="center">
<img src="https://img.shields.io/badge/-EDR%20Evasion-cc0000?style=for-the-badge&logoColor=white" alt="EDR Evasion" /><br><br>
Implants in C/C++ and C#/.NET, DLL sideloading, signed binary abuse, BOFs, custom UDRLs, payload staging, and testing against production EDR products.
</td>
<td width="33%" align="center">
<img src="https://img.shields.io/badge/-AD%20/%20Azure%20AD-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" alt="AD / Azure AD" /><br><br>
Active Directory and Microsoft Entra ID attack paths, privilege escalation, lateral movement, token manipulation, conditional access bypasses, and cross-tenant scenarios.
</td>
<td width="33%" align="center">
<img src="https://img.shields.io/badge/-APT--992-4B275F?style=for-the-badge&logoColor=white" alt="APT-992" /><br><br>
For <code>APT-992</code>, I'm training specialist models for offensive security. The RL pipeline uses feedback from live security products.

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
