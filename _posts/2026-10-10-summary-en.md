---
layout: default
title: "Horizon Summary: 2026-10-10 (EN)"
date: 2026-10-10
lang: en
---

> From 38 items, 4 important content pieces were selected

---

1. [Cloudflare Acquires Deno, Sparking Concerns Over Runtime's Future](#item-1) ⭐️ 9.0/10
2. [FAST Telescope Discovers Unique Evolving Triple Pulsar System](#item-2) ⭐️ 8.0/10
3. [JetBrains Releases Open-Source Coding Model Mellum2.1](#item-3) ⭐️ 8.0/10
4. [Telegram Desktop Vulnerability Allows Arbitrary File Theft via tg:// Links](#item-4) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [Cloudflare Acquires Deno, Sparking Concerns Over Runtime's Future](https://deno.com/blog/cloudflare) ⭐️ 9.0/10

Cloudflare has announced its acquisition of Deno, the secure JavaScript and TypeScript runtime. While Cloudflare will continue to support Deno for another year with bug fixes and security updates, they will cease active development thereafter, welcoming external contributions to continue its evolution. This acquisition significantly impacts the JavaScript runtime landscape, potentially altering the trajectory of Deno's development and its role as an alternative to Node.js. Developers who have invested in the Deno ecosystem may face uncertainty regarding future innovation and long-term support. Cloudflare's stated intention is to support Deno for one year post-acquisition, after which development will be community-driven. Some community members view this as an "acquihire" that effectively ends Deno's independent development, while others hope Cloudflare's work on `workerd` might adopt Deno's security features.

hackernews · ilreb · Oct 9, 13:03 · [Discussion](https://news.ycombinator.com/item?id=50019911)

**Background**: Deno is a secure-by-default JavaScript and TypeScript runtime built on V8 and Rust, designed as a modern alternative to Node.js. It emphasizes security through explicit permission granting and adheres to web standards. JavaScript runtimes allow developers to execute JavaScript code outside of a web browser, enabling server-side applications and command-line tools.

<details><summary>References</summary>
<ul>
<li><a href="https://www.educative.io/courses/deno-web-development/deno-runtime">Deno Runtime</a></li>
<li><a href="https://www.infoq.com/articles/deno-introduction-practical-examples/">Deno Introduction with Practical Examples - InfoQ</a></li>

</ul>
</details>

**Discussion**: Community sentiment is largely one of sadness and disappointment, with many expressing that Deno's independent development is effectively over, despite it remaining open source. Some lament the loss of innovation and the shift away from Deno's original first-principles approach, while others hope for potential integration of Deno's security concepts into Cloudflare's `workerd`.

**Tags**: `#JavaScript`, `#runtime`, `#Cloudflare`, `#Deno`, `#acquisition`

---

<a id="item-2"></a>
## [FAST Telescope Discovers Unique Evolving Triple Pulsar System](https://nao.cas.cn/news/gd/202610/t20261009_8289939.html) ⭐️ 8.0/10

China's FAST telescope has discovered a unique triple pulsar system, designated PSR J0435+3233, which is still in its evolutionary phase. This system consists of a pulsar, a white dwarf, and a sun-like star, with orbital periods of 8 days and 73.5 years for the inner and outer orbits, respectively. This discovery is significant as it represents the first confirmed triple pulsar system observed while still undergoing evolution, offering a rare opportunity to study stellar evolution in complex gravitational environments. The finding, independently verified by European scientists, highlights the advanced capabilities of the FAST telescope in astronomical research. The system's components include a pulsar, a white dwarf, and a sun-like star, with distinct orbital periods of 8 days (inner) and 73.5 years (outer). The research was published in The Astrophysical Journal Letters on October 9, 2026.

telegram · zaihuapd · Oct 9, 05:14

**Background**: A pulsar is a highly magnetized rotating neutron star that emits beams of electromagnetic radiation, appearing as pulses. White dwarfs are dense stellar remnants, the end-stage of evolution for low- to intermediate-mass stars like our Sun, radiating residual heat. Triple pulsar systems are rare configurations where three pulsars or a pulsar and other stars orbit each other.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Pulsar">Pulsar</a></li>
<li><a href="https://en.wikipedia.org/wiki/White_dwarf">White dwarf</a></li>
<li><a href="https://aasnova.org/2026/10/09/a-pulsar-in-a-rare-triple-system/">A Pulsar in a Rare Triple System - AAS Nova</a></li>

</ul>
</details>

**Discussion**: The community has expressed excitement over this rare astronomical discovery, particularly noting the significance of observing a triple pulsar system in an evolutionary phase. The independent verification and publication in a reputable journal have bolstered confidence in the findings.

**Tags**: `#astronomy`, `#pulsar`, `#FAST telescope`, `#astrophysics`, `#scientific discovery`

---

<a id="item-3"></a>
## [JetBrains Releases Open-Source Coding Model Mellum2.1](https://blog.jetbrains.com/ai/2026/10/mellum2-1-gets-to-work-a-fast-open-model-for-coding-agents/) ⭐️ 8.0/10

JetBrains has released Mellum2.1, an open-source 12 billion parameter coding model utilizing a Mixture-of-Experts (MoE) architecture with 2.5 billion active parameters. The model is trained for real-world coding agent tasks and is available under the Apache 2.0 license. This release provides a powerful, open-source tool for developing AI coding agents, potentially accelerating innovation in automated software development. Its availability under a permissive license encourages broader adoption and customization by the developer community. Mellum2.1 features a Mixture-of-Experts architecture, enabling efficient processing by activating only a subset of its parameters for each task. It is designed to perform complex coding agent functions like exploring codebases and editing files, with weights available on Hugging Face.

telegram · zaihuapd · Oct 9, 07:30

**Background**: A Mixture-of-Experts (MoE) architecture in AI involves using multiple specialized sub-models, or 'experts,' that work together to process complex inputs, activating only relevant experts for a given task. Coding agents are AI systems designed to autonomously perform tasks related to software development, such as writing, reviewing, and editing code.

<details><summary>References</summary>
<ul>
<li><a href="https://www.kdnuggets.com/why-the-newest-llms-use-a-moe-mixture-of-experts-architecture">Why the Newest LLMs use a MoE ( Mixture of Experts ) Architecture</a></li>
<li><a href="https://grokipedia.com/page/Coding_agent">Coding agent</a></li>

</ul>
</details>

**Discussion**: The release has been met with positive reception, with users noting the significance of an open-source MoE model from JetBrains for coding agents and appreciating its practical applications and permissive license.

**Tags**: `#AI`, `#Machine Learning`, `#Open Source`, `#Programming Models`, `#Coding Agents`

---

<a id="item-4"></a>
## [Telegram Desktop Vulnerability Allows Arbitrary File Theft via tg:// Links](https://t.me/zaihuapd/44307) ⭐️ 8.0/10

Telegram Desktop versions prior to 7.2.9 contain a critical vulnerability (CVE-2026-107181) where specially crafted tg:// links can steal arbitrary files from a user's system without confirmation. This vulnerability poses a significant security risk to millions of Telegram Desktop users, potentially leading to the exposure of sensitive personal data like documents, credentials, and cryptocurrency wallet information. The exploit leverages an unescaped semicolon in the tg:// link, which is misinterpreted as a separate Inter-Process Communication (IPC) command, allowing the 'interpret:' processor to access and exfiltrate files.

telegram · zaihuapd · Oct 9, 09:51

**Background**: Telegram Desktop is a popular cross-platform application for the Telegram messaging service. Inter-Process Communication (IPC) refers to methods that allow different processes on a computer to communicate with each other. A tg:// link is a custom URL scheme used by Telegram to launch the application and perform specific actions.

<details><summary>References</summary>
<ul>
<li><a href="https://www.cve.org/CVERecord?id=CVE-2026-107181">CVE Record: CVE - 2026 - 107181</a></li>
<li><a href="https://securityvulnerability.io/vulnerability/CVE-2026-107181">CVE - 2026 - 107181 : IPC Record-Separation Injection Vulnerability in...</a></li>
<li><a href="https://cybernews.com/security/one-click-telegram-desktop-exploit-hijacks-accounts/">Telegram Desktop vulnerability lets hackers hijack accounts ...</a></li>

</ul>
</details>

**Discussion**: Users are advised to update to the latest version of Telegram Desktop immediately and remain vigilant about clicking on suspicious tg:// links, with some also recommending enabling a local password for added security.

**Tags**: `#security`, `#vulnerability`, `#telegram`, `#exploit`, `#CVE`

---