<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=28&duration=3000&pause=1000&color=FF0000&center=true&vCenter=true&width=435&lines=0xh3l1x;Red+Team+%7C+OST+Dev;Offensive+Security+R%26D" alt="Typing SVG" />
</h1>

<p align="center">
  <a href="https://cgomezsec.com/"><img src="https://img.shields.io/badge/-cgomezsec.com-FF5722?style=for-the-badge&logo=firefox&logoColor=white" alt="Blog"></a>
  <a href="https://github.com/Maldev-Academy"><img src="https://img.shields.io/badge/-Maldev%20Academy-cc0000?style=for-the-badge&logo=hackthebox&logoColor=white" alt="Maldev Academy"></a>
  <a href="https://www.ioactive.com/authentication-downgrade-attacks-deep-dive-into-mfa-bypass/"><img src="https://img.shields.io/badge/-Published%20Research-4B275F?style=for-the-badge&logo=read-the-docs&logoColor=white" alt="Research"></a>
</p>

---

Red team operator and offensive tool developer. Most of my work lives under [@Maldev-Academy](https://github.com/Maldev-Academy) and private repos. I write about what I can share at [cgomezsec.com](https://cgomezsec.com/).

Author of [Authentication Downgrade Attacks: Deep Dive Into MFA Bypass](https://www.ioactive.com/authentication-downgrade-attacks-deep-dive-into-mfa-bypass/).

---

### What I'm working on

AiTM phishing against hardened targets like Google using real browser instances via CDP instead of reverse proxies, sidestepping TLS fingerprinting, BotGuard, and anti-bot systems. Also doing FIDO2/WebAuthn research, looking at where passkey implementations break in practice.

---

### [`Maldev Academy`](https://github.com/Maldev-Academy)

Modules on phishing, auth attacks, and cloud identity exploitation. Protocol internals, working implementations, OPSEC. All MFA bypass modules include FIDO downgrade vectors.

#### Published Modules

| # | Module | Target | Technique |
|---|--------|--------|-----------|
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

#### In Development

| # | Module | Target | Technique |
|---|--------|--------|-----------|
| 12 | Google AiTM | Google | Real-time credential relay via nodriver + CDP |
| 13 | Phishing Passkeys | FIDO2/WebAuthn | Passkey theft, CDP virtual authenticators |

---

### Tools

#### Open Source

<table>
<tr>
<td width="50%">

**[GitHubDeviceCodePhishing](https://github.com/Maldev-Academy/GitHubDeviceCodePhishing)**

GitHub device code phishing. Minimal setup.

</td>
<td width="50%">

**[GitLabDeviceCodePhishing](https://github.com/Maldev-Academy/GitLabDeviceCodePhishing)**

Same approach for GitLab. Cloud and self-managed.

</td>
</tr>
</table>

#### Internal (Maldev Academy)

**Real-time Phishing Framework** - Multi-provider credential relay with live error feedback. Real Chrome per target via nodriver/CDP. Google, GitHub, Bitwarden providers built in, new target = new folder.

```
Victim Browser <-> Flask <-> Chrome (nodriver/CDP) <-> Real Login Page
                                    |
                         Chrome Sync / Passkeys / Vault
```

**Cloudflare Workers AiTM Proxy** - Invisible reverse proxy running entirely on CF Workers. Rewrites requests/responses on the edge, captures credentials and session tokens in transit. No traditional server infrastructure.

**Azure AiTM Proxy** - AiTM phishing proxy deployed on Azure Functions with Azure Front Door. Legitimate Microsoft infrastructure proxying authentication flows.

**Evilginx M365 Phishlet** - Custom phishlet with MFA downgrade capabilities. Forces FIDO-capable accounts to fall back to weaker authentication methods.

**Client Fingerprinting Worker** - Cloudflare Worker that profiles incoming clients before serving phishing content. Anti-bot checks, sandbox detection, browser fingerprinting, geolocation filtering.

---

### Internal R&D

Things I work on that aren't public.

**EDR Evasion & Implant Development** - Loader/implant development in C/C++ and C#/.NET. Userland and kernel-level evasion techniques against production EDR (Elastic, CrowdStrike, Defender). Syscall unhooking, ETW patching, AMSI bypass, process injection, reflective loading. Testing against live deployments, not default configs.

**Active Directory & Azure AD** - AD attack paths, privilege escalation, lateral movement. Azure AD token manipulation, conditional access bypass, cross-tenant abuse. Internal tooling for engagements.

**APT-992** - Training specialist models for offensive security tasks. The pipeline uses reinforcement learning with feedback from live security products instead of static datasets.

---

### Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=c,cpp,cs,dotnet,rust,python,go,js,bash&theme=dark&perline=9" alt="Languages" />
</p>
<p align="center">
  <img src="https://skillicons.dev/icons?i=docker,azure,cloudflare,nginx,linux,github&theme=dark&perline=6" alt="Infra" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/-C/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white" />
  <img src="https://img.shields.io/badge/-C%23/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white" />
  <img src="https://img.shields.io/badge/-Rust-000000?style=flat-square&logo=rust&logoColor=white" />
  <img src="https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/-Go-00ADD8?style=flat-square&logo=go&logoColor=white" />
  <img src="https://img.shields.io/badge/-x86/x64%20ASM-6E4C13?style=flat-square&logo=assemblyscript&logoColor=white" />
  <img src="https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/-PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white" />
  <img src="https://img.shields.io/badge/-Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white" />
</p>


---

### GitHub Stats

> Most of my work is under [@Maldev-Academy](https://github.com/Maldev-Academy) and private repos.

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Hexix23&show_icons=true&theme=radical&hide_border=true&bg_color=0d1117&title_color=ff0000&icon_color=ff0000&text_color=c9d1d9&include_all_commits=true&count_private=true" height="165" alt="GitHub Stats" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Hexix23&theme=radical&hide_border=true&background=0d1117&ring=ff0000&fire=ff0000&currStreakLabel=ff0000" height="165" alt="GitHub Streak" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Hexix23&theme=redical&hide_border=true&bg_color=0d1117&color=ff0000&line=ff0000&point=ffffff" width="95%" alt="Activity Graph" />
</p>

---

<p align="center"><code>0xh3l1x</code></p>
