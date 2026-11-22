---
layout: default
title: "Horizon Summary: 2026-11-22 (EN)"
date: 2026-11-22
lang: en
---

> From 24 items, 6 important content pieces were selected

---

1. [Formal Proof of Riemann Hypothesis Achieved with AI Assistance in Lean](#item-1) ⭐️ 9.0/10
2. [Zhejiang University Achieves First Real-Machine QRAM on Superconducting Chip](#item-2) ⭐️ 9.0/10
3. [GnuPG's GPGME Library Vulnerable, Affecting Numerous Applications](#item-3) ⭐️ 8.0/10
4. [Microsoft Enables Distributed AI on Windows via USB4 RDMA](#item-4) ⭐️ 8.0/10
5. [OpenRouter Warns of Potential Third-Party Access to MiniMax Model Prompts](#item-5) ⭐️ 8.0/10
6. [Tesla Rolls Out FSD v15 with Major Safety and Visualization Upgrades](#item-6) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [Formal Proof of Riemann Hypothesis Achieved with AI Assistance in Lean](https://leanprover-community.github.io/blog/posts/riemann-hypothesis/) ⭐️ 9.0/10

Mathematician Levent Alpöge, with assistance from Anthropic's AI model Claude, has announced a formal proof of the Riemann Hypothesis and its generalization. The proof has been encoded in the Lean theorem prover, resulting in a formalization exceeding 250,000 pages. This achievement represents a significant breakthrough in formal verification, potentially revolutionizing how complex mathematical proofs are validated and opening new avenues for foundational mathematics research. It demonstrates the growing capability of AI in assisting with highly complex scientific endeavors. The proof has been accepted by the independent Lean and Mathlib mathematical communities as verified, though an informal, human-readable proof has yet to be published. The formalization involved formalizing a substantial portion of modern mathematics.

hackernews · g-b-r · Nov 21, 14:36 · [Discussion](https://news.ycombinator.com/item?id=50589618)

**Background**: The Riemann Hypothesis, proposed by Bernhard Riemann in 1859, is a conjecture about the distribution of prime numbers. It states that all non-trivial zeros of the Riemann zeta function lie on the critical line with real part 1/2. Lean is an open-source proof assistant and functional programming language used for formal verification of mathematical theorems.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Riemann_hypothesis">Riemann hypothesis</a></li>
<li><a href="https://en.wikipedia.org/wiki/Lean_theorem_prover">Lean theorem prover</a></li>

</ul>
</details>

**Discussion**: Community members express excitement about the potential paradigm shift in formalizing complex proofs and acknowledge the rigorous nature of the verification process. There's also discussion about the implications for math foundations and the possibility of AI 'hacking' the system, though the human expert involvement mitigates this concern.

**Tags**: `#formal verification`, `#mathematics`, `#AI`, `#theorem proving`, `#Riemann Hypothesis`

---

<a id="item-2"></a>
## [Zhejiang University Achieves First Real-Machine QRAM on Superconducting Chip](https://finance.sina.com.cn/stock/2026-11-21/doc-iniznhsk3530826.shtml) ⭐️ 9.0/10

Zhejiang University researchers have successfully implemented the world's first real-machine Quantum Random Access Memory (QRAM) on their self-developed superconducting quantum chip, 'Tianmu 2.0'. This breakthrough, published in Nature Physics, demonstrated prototype operation for retrieving 4-bit and 8-bit data with 80.9% and 60.4% accuracy, respectively. This achievement is a significant step towards building more efficient quantum computers, as QRAM acts as high-speed memory for them. It could accelerate the development of quantum computing hardware and its applications in fields like AI and complex simulations. The implementation on 'Tianmu 2.0' reduced circuit depth by over 30% compared to unoptimized solutions and demonstrated initial local noise resistance. The team plans to focus on scaling up QRAM research next.

telegram · zaihuapd · Nov 21, 08:31

**Background**: Quantum Random Access Memory (QRAM) is a proposed essential component for quantum computers, analogous to RAM in classical computers, enabling efficient access to large datasets in superposition. Superconducting quantum chips utilize superconducting electronic circuits, including Josephson junctions, as qubits, forming the core of a quantum processor (QPU). This architecture is a dominant method in the industry for developing quantum processing units.

<details><summary>References</summary>
<ul>
<li><a href="https://grokipedia.com/page/Quantum_random-access_memory">Quantum random-access memory</a></li>
<li><a href="https://en.wikipedia.org/wiki/Superconducting_quantum_computing">Superconducting quantum computing</a></li>

</ul>
</details>

**Discussion**: The community is likely to view this as a major advancement in quantum computing hardware, particularly for its practical implementation on real hardware. The publication in Nature Physics lends significant credibility to the findings.

**Tags**: `#Quantum Computing`, `#QRAM`, `#Superconducting Qubits`, `#AI/ML Hardware`, `#Research Breakthrough`

---

<a id="item-3"></a>
## [GnuPG's GPGME Library Vulnerable, Affecting Numerous Applications](https://lists.gnupg.org/pipermail/gnupg-announce/2026q4/000517.html) ⭐️ 8.0/10

A security advisory has been released for GnuPG's GPGME library, detailing a double-free vulnerability. The first fixed version is GPGME 2.3.1, with earlier versions like 2.3.0 also mentioned as potentially affected. This vulnerability impacts a wide range of software that relies on GPGME, including email clients, Samba, and Flatpak, potentially compromising the security of digital signatures and encrypted communications for many users. The vulnerability is a double-free bug, and all software using GPGME versions prior to 2.3.0, whether as a shared library, DLL, or statically linked, is affected.

hackernews · gdgghhhhh · Nov 21, 08:32 · [Discussion](https://news.ycombinator.com/item?id=50587208)

**Background**: GnuPG (GNU Privacy Guard) is a free software replacement for PGP, providing cryptographic functionality. GPGME (GnuPG Made Easy) is a library that simplifies the use of GnuPG for developers, making it easier to integrate GPG functionalities into other applications.

<details><summary>References</summary>
<ul>
<li><a href="https://www.phoronix.com/news/GnuPG-GPGME-Critical">GnuPG's GPGME Affected By Critical Security Bug In Turn... - Phoronix</a></li>
<li><a href="https://en.wikipedia.org/wiki/GPGME">GPGME</a></li>

</ul>
</details>

**Discussion**: Community members debated the severity of the bug, with some questioning if it was overstated as an RCE chain and others lamenting the inherent risks of C/C++ development, suggesting Rust-level tooling as a solution.

**Tags**: `#security`, `#vulnerability`, `#GPGME`, `#software engineering`

---

<a id="item-4"></a>
## [Microsoft Enables Distributed AI on Windows via USB4 RDMA](https://videocardz.com/newz/microsoft-brings-rdma-over-usb4-to-windows-allowing-multiple-pcs-to-run-one-local-ai-model) ⭐️ 8.0/10

Microsoft has released a developer preview of RDMA over USB4 for Windows, allowing multiple PCs connected via standard USB4 cables to pool their memory and GPU compute resources for running a single, large local AI model. This innovation democratizes access to powerful local AI by eliminating the need for specialized, expensive networking hardware, potentially lowering the barrier to entry for complex AI tasks and enabling more users to run large models on consumer-grade hardware. A demonstration showed three AMD Ryzen AI Max+ 395 PCs running a 4-bit quantized Qwen3-235B-A22B model at approximately 18.5 tokens/second, with the feature slated for release via Windows Insider.

telegram · zaihuapd · Nov 21, 06:13

**Background**: RDMA (Remote Direct Memory Access) allows computers to access the memory of other devices directly without involving the CPU, significantly speeding up data transfer. USB4 is a high-speed connection standard that can now leverage RDMA for more efficient inter-PC communication. 4-bit quantization is a technique used to reduce the memory footprint and computational requirements of AI models by representing model weights with fewer bits, enabling them to run on less powerful hardware.

<details><summary>References</summary>
<ul>
<li><a href="https://habr.com/ru/articles/1110636/">Microsoft представила решение на базе USB 4 и RDMA для... / Хабр</a></li>
<li><a href="https://gagadget.com/ru/artificial-intelligence/735249-resursyi-neskolkih-pk-dlya-zapuska-tyazhelogo-ii-nauchilas-obedinyat-microsoft-cherez-usb4/">Microsoft реализовала RDMA через USB 4 для ИИ-кластеров</a></li>

</ul>
</details>

**Discussion**: The community is excited about the potential for distributed local AI inference using standard hardware, though some express curiosity about latency and the practical performance gains compared to dedicated hardware or cloud solutions.

**Tags**: `#AI`, `#Systems Research`, `#USB4`, `#Distributed Computing`, `#Microsoft`

---

<a id="item-5"></a>
## [OpenRouter Warns of Potential Third-Party Access to MiniMax Model Prompts](https://news.ycombinator.com/item?id=50585962) ⭐️ 8.0/10

OpenRouter has issued a warning that user prompts sent to MiniMax AI models may have been accessed by a third party. Security researchers observed third parties accessing test URLs embedded in prompts sent to MiniMax models between July and October 2026, with delays ranging from 40 to 130 hours. This incident highlights a significant security vulnerability in the AI model supply chain, potentially exposing sensitive user data and eroding trust in AI service providers. It underscores the need for robust security measures and transparency from both API providers and model developers. OpenRouter attributes the issue to MiniMax and its forwarders (AtlasCloud, Novita, StreamLake), and has removed the 'zero data retention' tag from relevant endpoints, advising users to change API keys and passwords if sensitive credentials were used.

telegram · zaihuapd · Nov 21, 06:53

**Background**: MiniMax Group is an AI company based in Shanghai, China, known for developing multimodal AI models. OpenRouter provides a unified API gateway to access a wide range of AI models from various providers, simplifying integration for developers.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/MiniMax_Group">MiniMax Group - Wikipedia</a></li>
<li><a href="https://www.minimax.io/">MiniMax</a></li>
<li><a href="https://openrouter.ai/openrouter">OpenRouter API and Models | OpenRouter</a></li>

</ul>
</details>

**Discussion**: The discussion on Hacker News likely focuses on the technical implications of prompt injection or data leakage through third-party forwarding services, the responsibility of API aggregators like OpenRouter, and the broader security risks in the AI ecosystem.

**Tags**: `#AI Security`, `#Data Privacy`, `#LLM Vulnerability`, `#OpenRouter`, `#MiniMax`

---

<a id="item-6"></a>
## [Tesla Rolls Out FSD v15 with Major Safety and Visualization Upgrades](https://x.com/Tesla/status/2124222447855743019) ⭐️ 8.0/10

Tesla has begun rolling out its Full Self-Driving (FSD) v15 software update, which significantly enhances safety-critical scenario processing by 25 times and introduces a new 'Tesla Reality View' visualization interface. This update represents a substantial leap in Tesla's autonomous driving capabilities, directly addressing key weaknesses and aiming to improve driver confidence and system reliability. FSD v15 features 'Tesla Reality View' which overlays FSD driving plans onto camera feeds, offering full-screen, map, or split-screen views, and includes optimizations for road imperfections, school zones, and adverse weather conditions.

telegram · zaihuapd · Nov 22, 00:03

**Background**: Tesla's Full Self-Driving (FSD) is an advanced driver-assistance system that aims to enable autonomous driving, though it currently requires active driver supervision. 'Tesla Reality View' is a new visualization feature designed to provide a more intuitive understanding of the system's perception and planned actions.

<details><summary>References</summary>
<ul>
<li><a href="https://electrek.co/2026/11/21/tesla-fsd-v15-rollout-25x-safety-reality-view/">Tesla launches FSD v15, targets its biggest weaknesses, from ......</a></li>
<li><a href="https://driveteslacanada.ca/news/tesla-reality-view/">Tesla Reality View takes FSD visualizations to an entirely new...</a></li>
<li><a href="https://gizmodo.com/its-like-gta-musk-touts-video-game-like-update-to-tesla-fsd-2000843584">Tesla Adds GTA-Like Update to FSD - Gizmodo</a></li>

</ul>
</details>

**Discussion**: Early reports highlight the impressive 'Tesla Reality View' and the focus on addressing long-standing weaknesses like sign reading and pothole handling, suggesting a positive reception to the update's practical improvements.

**Tags**: `#AI`, `#Autonomous Driving`, `#Software Update`, `#Automotive Technology`

---