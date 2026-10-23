---
layout: default
title: "Horizon Summary: 2026-10-23 (EN)"
date: 2026-10-23
lang: en
---

> From 44 items, 18 important content pieces were selected

---

1. [eMudhra Certificate Keys Weak, Browsers Blocked Trust](#item-1) ⭐️ 9.0/10
2. [Docker's Unique Design Choices Sparked Debate Among Engineers](#item-2) ⭐️ 8.0/10
3. [LLMs Enhance Formal Software Verification at Scale](#item-3) ⭐️ 8.0/10
4. [Quad9 DNS Resolver Exits France Due to Legal Orders](#item-4) ⭐️ 8.0/10
5. [OpenShell: A Secure Runtime for Autonomous AI Agents](#item-5) ⭐️ 8.0/10
6. [iOS 16.5 Firmware Successfully Emulated on Android Devices](#item-6) ⭐️ 8.0/10
7. [Earstrip library triangulates map polygons significantly faster using WASM](#item-7) ⭐️ 8.0/10
8. [Potential Switch 2 Jailbreak Detailed, Sparking Emulation and Research Discussions](#item-8) ⭐️ 8.0/10
9. [Anthropic Donates Agent Skills Standard to Agentic AI Foundation](#item-9) ⭐️ 8.0/10
10. [Carbon-X: Open 14.8B Model Trained on DNA and Text](#item-10) ⭐️ 8.0/10
11. [Open-XTTS-Trainer Simplifies XTTS v2 Model Training and Adaptation](#item-11) ⭐️ 8.0/10
12. [Tesla Launches Cybercab Production in North America for Driverless Rides](#item-12) ⭐️ 8.0/10
13. [Smart TVs Report Content Data Even When Identification is Disabled, Study Finds](#item-13) ⭐️ 8.0/10
14. [miHoYo and Tsinghua University Open-Source Game Operation Model](#item-14) ⭐️ 8.0/10
15. [Oracle Issues Critical Security Alert for Java SE Vulnerability CVE-2026-91403](#item-15) ⭐️ 8.0/10
16. [333 Compromised Tor Exit Nodes with Ebury Backdoor Taken Down](#item-16) ⭐️ 8.0/10
17. [China State-Backed Firm Buys Banned Nvidia B300 AI Chips, Redacts Details](#item-17) ⭐️ 8.0/10
18. [SpaceX in Talks to Lease 80,000 Cell Sites for Fourth US Wireless Carrier](#item-18) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [eMudhra Certificate Keys Weak, Browsers Blocked Trust](https://t.me/zaihuapd/44627) ⭐️ 9.0/10

Eight intermediate certificate authority private keys from Indian CA eMudhra were found to have extremely weak randomness, with only 256 possible values, allowing for quick brute-force recovery. This led major browsers like Firefox and Chrome to immediately distrust certificates issued by these keys. This vulnerability could allow attackers to impersonate eMudhra, issue fraudulent HTTPS certificates for any website, and potentially steal user data or conduct phishing attacks, undermining trust in the digital certificate ecosystem. Six of the compromised keys could sign website certificates, while two could sign code-signing certificates. Mozilla acted within three hours of receiving the report, while Google also took swift action to block the affected public keys.

telegram · zaihuapd · Oct 23, 01:04

**Background**: eMudhra is an Indian Public Key Infrastructure (PKI) company licensed to issue digital signature certificates. HTTPS certificates are crucial for securing web communications, ensuring both the identity of the website and the privacy of data exchanged. Private keys are secret cryptographic keys used to sign certificates, and their strength relies on high randomness to prevent brute-force attacks.

<details><summary>References</summary>
<ul>
<li><a href="https://cybersecuritynews.com/emudhra-security-compromise/">eMudhra Certificate Authority Compromise Triggers Emergency ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/EMudhra">eMudhra - Wikipedia</a></li>
<li><a href="https://emudhra.com/en/faq/emudhra-ca-certifying-authority">eMudhra as Certifying & Certificate Authority | eMudhra - Global</a></li>

</ul>
</details>

**Discussion**: Community members expressed concern over the severity of the vulnerability and the potential for impersonation. There was also discussion regarding the proportionality of social media amplification versus the technical complexity, and a critique of eMudhra's apparent lack of transparency regarding the cause of the failure.

**Tags**: `#security`, `#cryptography`, `#PKI`, `#vulnerability`, `#browsers`

---

<a id="item-2"></a>
## [Docker's Unique Design Choices Sparked Debate Among Engineers](https://codeandcake.dev/posts/2026-10-22-docker-is-weird) ⭐️ 8.0/10

A blog post critically examines Docker's design choices and underlying technologies, highlighting what makes it unique. The discussion gained traction with contributions from Docker's creator and other experienced engineers. Understanding Docker's design is crucial for developers and system architects as it impacts how applications are built, deployed, and managed, influencing the broader containerization ecosystem. The post suggests Docker's uniqueness stems less from core container technologies like namespaces and more from features like the Dockerfile, layer caching, and its registry, which significantly improved developer experience and CI/CD efficiency.

hackernews · psxuaw · Oct 22, 23:45 · [Discussion](https://news.ycombinator.com/item?id=50202681)

**Background**: Docker is a popular platform for building, shipping, and running applications using containers. Containers package an application and its dependencies together, ensuring consistency across different environments. Docker leverages various Linux kernel features, such as namespaces and cgroups, to isolate processes and manage resources.

<details><summary>References</summary>
<ul>
<li><a href="https://www.docker.com/products/docker-desktop/">Docker Desktop: The #1 Containerization Tool for Developers | Docker</a></li>

</ul>
</details>

**Discussion**: The creator of Docker acknowledged the post, finding it interesting to see discussions about the system's design. Other engineers debated whether Docker's innovation lay in the core container tech or in its developer-friendly abstractions like Dockerfiles and caching, with some preferring alternatives like Podman.

**Tags**: `#docker`, `#containerization`, `#software-architecture`, `#developer-experience`

---

<a id="item-3"></a>
## [LLMs Enhance Formal Software Verification at Scale](https://www.anthropic.com/research/formal-verification) ⭐️ 8.0/10

Researchers are leveraging Large Language Models (LLMs) to significantly improve the feasibility and scale of formal software verification, a process traditionally limited by complexity and time. This advancement promises to make formal verification more accessible for ensuring software correctness. This development could revolutionize software engineering by enabling more robust and reliable software development, especially for critical systems where bugs can have severe consequences. It democratizes a powerful but previously inaccessible technique for a wider range of developers and projects. LLMs can assist in generating proofs and specifications, tasks that were previously manual and labor-intensive, thereby reducing the human effort required. While promising, scaling these LLM-assisted proofs to highly complex programs remains an open question, with potential limitations in handling verbose proof styles.

hackernews · johnbender · Oct 22, 22:54 · [Discussion](https://news.ycombinator.com/item?id=50202217)

**Background**: Formal verification is a rigorous method used to prove that software or hardware meets its specified requirements. It involves using mathematical techniques and tools to ensure correctness, unlike traditional testing which can only find existing bugs. Large Language Models (LLMs) are advanced AI models trained on vast amounts of text data, capable of understanding and generating human-like text, and increasingly, code and logical reasoning.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Formal_verification">Formal verification - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Large_language_model">Large language model</a></li>
<li><a href="https://www.anthropic.com/research/formal-verification">LLMs are making formal software verification feasible at a ...</a></li>

</ul>
</details>

**Discussion**: Community members express optimism about LLMs aiding formal verification but also raise concerns about scalability and the potential shift away from imperative programming languages towards more declarative ones. Some users shared personal experiences of using LLMs for verification tasks, highlighting both successes and limitations.

**Tags**: `#LLM`, `#Formal Verification`, `#Software Engineering`, `#AI`

---

<a id="item-4"></a>
## [Quad9 DNS Resolver Exits France Due to Legal Orders](https://quad9.net/news/blog/au-revoir-france/) ⭐️ 8.0/10

Quad9, a public DNS resolver, has announced it will cease operating in France by November 24th following a court order mandating it to block access to infringing content. This decision highlights the significant legal and operational challenges faced by internet infrastructure providers in complying with content blocking mandates, potentially impacting internet freedom and the neutrality of core internet services. Quad9 was fined for contempt of court after a plaintiff used a VPN to circumvent geoIP blocking, demonstrating the difficulties in enforcing such restrictions effectively against determined users.

hackernews · farrokhi · Oct 22, 14:32 · [Discussion](https://news.ycombinator.com/item?id=50195959)

**Background**: Quad9 is a free, public DNS resolver that aims to improve internet security and privacy by blocking malicious domains. DNS (Domain Name System) acts like a phonebook for the internet, translating human-readable domain names into numerical IP addresses that computers use to connect to services.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/DNS_resolver">DNS resolver</a></li>
<li><a href="https://grokipedia.com/page/Azure_DNS_Private_Resolver">Azure DNS Private Resolver</a></li>

</ul>
</details>

**Discussion**: Community members expressed concern over punishing DNS resolvers, comparing it to punishing a phonebook company for listing a criminal's number. Some suggested retaliatory measures against suing companies, while others noted similar exits by Cisco and Cloudflare due to French legal actions.

**Tags**: `#DNS`, `#copyright`, `#legal`, `#internet infrastructure`, `#France`

---

<a id="item-5"></a>
## [OpenShell: A Secure Runtime for Autonomous AI Agents](https://github.com/NVIDIA/OpenShell) ⭐️ 8.0/10

OpenShell has been introduced as a secure runtime environment designed to provide autonomous AI agents with necessary capabilities while maintaining data and network security. It aims to balance agent functionality with robust security measures. This development is significant as it addresses a critical challenge in deploying autonomous AI agents: granting them the power to act without compromising sensitive information or network integrity. It could enable wider adoption of AI agents in enterprise environments. OpenShell allows agents to read files, install packages, call APIs, and use credentials, but restricts their access to prevent unrestricted data exfiltration or network access. It aims to strike a balance, preventing the 'you can't have your cake and eat it too' paradox.

hackernews · niemandhier · Oct 22, 17:44 · [Discussion](https://news.ycombinator.com/item?id=50198675)

**Background**: Autonomous AI agents are AI systems capable of performing complex tasks independently, learning, and making decisions without human input. A runtime environment provides the context and necessary services for programs to execute, managing aspects like memory, OS interaction, and dynamic features.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Runtime_environment">Runtime environment</a></li>
<li><a href="https://en.wikipedia.org/wiki/Autonomous_agent">Autonomous agent</a></li>
<li><a href="https://www.microsoft.com/en-us/copilot/ai-knowledge/autonomous-ai-agents">Introduction to Autonomous AI Agents | Microsoft Copilot</a></li>

</ul>
</details>

**Discussion**: Community members expressed interest in OpenShell's security approach, with some questioning the feasibility of granting capabilities without full access and others sharing alternative tools like Iron proxy. Concerns were raised about preventing data exfiltration, with suggestions to run agents in containers and manage access policies.

**Tags**: `#AI`, `#Security`, `#Runtime`, `#Autonomous Agents`, `#Software Engineering`

---

<a id="item-6"></a>
## [iOS 16.5 Firmware Successfully Emulated on Android Devices](https://github.com/oosexgang/hackios-xnu-kernel) ⭐️ 8.0/10

Researchers have successfully demonstrated running iOS 16.5 firmware on Android devices, specifically on certain Xiaomi models and within the QEMU emulator, through the 'hackios-xnu-kernel' project. This achievement challenges traditional mobile OS market segmentation and opens new avenues for device emulation research, potentially impacting how mobile operating systems are developed and tested. The project boots Apple's XNU kernel and runs unmodified iOS user space, but it functions as a research bench with limited session times and does not include Apple files or support features like cellular connectivity.

hackernews · aghuang · Oct 22, 15:26 · [Discussion](https://news.ycombinator.com/item?id=50196718)

**Background**: QEMU is a free and open-source machine emulator and virtualizer capable of emulating various instruction set architectures and full systems. The XNU kernel is the core of Apple's operating systems, including iOS and macOS.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/oosexgang/hackios-xnu-kernel">GitHub - oosexgang/hackios-xnu-kernel</a></li>
<li><a href="https://singularitymoments.com/content/inside-hackios-booting-apples-xnu-kernel-and-springboard-on-snapdragon-silicon/">Inside HackiOS: Booting Apple's XNU Kernel and SpringBoard on ...</a></li>
<li><a href="https://www.vibeleaderboard.ai/app/204f5a88-73c5-4aab-90c3-aa14abc9c8bc">HackiOS: iOS 16.5 XNU Kernel on Android Phone Hardware</a></li>

</ul>
</details>

**Discussion**: Community members expressed excitement about the technical feat and its implications for device emulation and market segmentation, with some noting the project's limitations as a research tool rather than a deployable ROM.

**Tags**: `#iOS`, `#Android`, `#Emulation`, `#Reverse Engineering`, `#Mobile OS`

---

<a id="item-7"></a>
## [Earstrip library triangulates map polygons significantly faster using WASM](https://globus.software/blog/2026/10/16/cutting-map-polygons/) ⭐️ 8.0/10

A new library named Earstrip has been developed, achieving polygon triangulation for 3.7 million map polygons in just 489 milliseconds. This performance is substantially faster than existing methods like Earcut, leveraging WebAssembly (WASM) and optimized algorithms. This breakthrough offers a significant performance improvement for map rendering and geospatial data processing, which are critical in applications like web mapping and GIS. Faster triangulation means more responsive map interactions and the ability to handle more complex datasets efficiently. Earstrip utilizes WASM for its core triangulation logic, enabling near-native performance in the browser. The library was benchmarked against Earcut, demonstrating a substantial speedup on a large dataset of map polygons.

hackernews · molind · Oct 22, 09:31 · [Discussion](https://news.ycombinator.com/item?id=50193170)

**Background**: Polygon triangulation is the process of decomposing a polygon into a set of triangles. This is a fundamental operation in computer graphics and computational geometry, used for rendering shapes, meshing, and spatial analysis. Earcut is a popular JavaScript library for 2D polygon triangulation, known for its speed and small size.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/mapbox/earcut">GitHub - mapbox/ earcut : The fastest and smallest JavaScript polygon...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Polygon_triangulation">Polygon triangulation</a></li>

</ul>
</details>

**Discussion**: Community members praised the impressive performance gains and noted the potential for borrowing optimizations. Discussions touched upon trade-offs between performance, bundle size, alternative algorithms like Seidel's trapezoidal method, and the implications of thin triangles for GPU rasterization.

**Tags**: `#computer graphics`, `#algorithms`, `#performance optimization`, `#GIS`, `#WASM`

---

<a id="item-8"></a>
## [Potential Switch 2 Jailbreak Detailed, Sparking Emulation and Research Discussions](https://pepsipu.com/blog/2026-10-switch2-jailbreak-ns2jb/) ⭐️ 8.0/10

A technical blog post has detailed a potential method for jailbreaking the Nintendo Switch 2, outlining the hardware and software techniques involved in achieving read/write access to the file system. This development could significantly impact game preservation, emulation, and the homebrew scene, potentially allowing for console exclusives to be played on other hardware and enabling deeper hardware research. The post describes using tools like JetKVMs for controller input and video output, and a SwitchBot Bot for power button automation, highlighting the sophisticated setup required for this research.

hackernews · ledoge · Oct 22, 08:01 · [Discussion](https://news.ycombinator.com/item?id=50192536)

**Background**: Jailbreaking a console typically involves exploiting vulnerabilities to bypass security restrictions, allowing users to run unauthorized software. This can enable game emulation, where software mimics original console hardware to play games on different devices, and the creation of homebrew applications.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/IOS_jailbreaking">iOS jailbreaking - Wikipedia</a></li>
<li><a href="https://lifehacker.com/is-it-legal-to-jailbreak-a-video-game-console-1848558154">Is It Legal to Jailbreak a Video Game Console? - Lifehacker A new PS5 jailbreak works on almost every firmware version ... How do jailbreaked consoles work? : r/PiratedGames - Reddit The PS5 hacking scene just took a big leap forward Is Jailbreaking Illegal? The Ultimate Guide to Your Digital ... Which Consoles Can Be Jailbroken in 2025? - ExpertBeacon</a></li>

</ul>
</details>

**Discussion**: Community members expressed excitement about the potential for decrypted file system access, leading to rapid game dumping and emulation on arbitrary hardware. They also noted the impressive automation achieved through modern tooling like KVMs and Bluetooth-controlled devices for research purposes.

**Tags**: `#reverse-engineering`, `#console-hacking`, `#emulation`, `#security-research`, `#nintendo-switch`

---

<a id="item-9"></a>
## [Anthropic Donates Agent Skills Standard to Agentic AI Foundation](https://simonwillison.net/2026/Oct/22/donating-agent-skills/) ⭐️ 8.0/10

Anthropic has donated its Agent Skills standard to the Agentic AI Foundation (AAIF), which is hosted under the Linux Foundation. This move aims to foster an open, community-driven, and vendor-neutral approach to developing AI agent capabilities. This donation promotes standardization and interoperability for AI agents, allowing skills to be portable across different AI systems. It signifies a commitment to open-source development in the rapidly evolving field of agentic AI. Agent Skills are a lightweight, open format for extending AI agent capabilities, packaged as portable SKILL .md folders. The AAIF was co-founded by Anthropic, Block, and OpenAI last year and is dedicated to uniting open-source projects advancing agentic AI.

rss · Simon Willison · Oct 22, 18:09

**Background**: Agent Skills provide a standardized way to give AI agents new capabilities and expertise, enabling them to discover and load task-specific knowledge on demand. The Agentic AI Foundation (AAIF), hosted by the Linux Foundation, aims to unite open-source projects in the agentic AI space through neutral governance.

<details><summary>References</summary>
<ul>
<li><a href="https://agentskills.io/home">A standardized way to give AI agents new capabilities and expertise.</a></li>
<li><a href="https://grokipedia.com/page/Agentic_AI_Foundation">Agentic AI Foundation</a></li>
<li><a href="https://en.wikipedia.org/wiki/Model_Context_Protocol">Model Context Protocol</a></li>

</ul>
</details>

**Discussion**: The announcement aligns with previous predictions about Anthropic donating its standards to the AAIF, reinforcing the trend towards open standards in AI development. This move is seen as positive for fostering a collaborative and interoperable AI ecosystem.

**Tags**: `#AI`, `#Agentic AI`, `#Open Source`, `#Standardization`, `#Foundation`

---

<a id="item-10"></a>
## [Carbon-X: Open 14.8B Model Trained on DNA and Text](https://www.reddit.com/r/MachineLearning/comments/1xchayq/carbonx_is_an_open_148b_model_trained_jointly_on/) ⭐️ 8.0/10

Hugging Face has released Carbon-X, an open-source 14.8 billion parameter decoder-only language model trained jointly on DNA and text data. The model uses a shared token stream with 6-mer tokens for both modalities and was mid-trained on 302 billion tokens. This model demonstrates competitive performance on DNA benchmarks, approaching proprietary models, and its open-source nature allows for local analysis of sensitive genomic datasets. This could significantly accelerate bioinformatics research and applications by enabling privacy-preserving analysis. Carbon-X achieves a 66.7% average across five DNA benchmarks and fits on a single 80 GB GPU using bfloat16 precision, with an Apache 2.0 license. It has not undergone clinical validation, and complex sequence operations should still be handled by code.

reddit · r/MachineLearning · /u/jatingargiitk · Oct 22, 12:32

**Background**: Decoder-only models, like Carbon-X, are a common architecture for modern LLMs, designed primarily for generating new text or sequences. 6-mer tokenization represents DNA sequences by grouping six nucleotides into a single token, which can be more efficient for genomic data than standard tokenization methods. Bfloat16 is a 16-bit floating-point format that balances dynamic range and precision, accelerating machine learning computations while reducing memory usage.

<details><summary>References</summary>
<ul>
<li><a href="https://muted-color.github.io/research/2026/05/23/carbon-6mer-phase-sensitivity/">Carbon-3B: Measuring 6-mer Token Phase Sensitivity</a></li>

</ul>
</details>

**Discussion**: Community members are interested in the practical applications of Carbon-X, particularly its potential for analyzing sensitive datasets locally. There is curiosity about whether the benchmark gains observed will hold true for private variant datasets.

**Tags**: `#LLM`, `#Bioinformatics`, `#Open Source`, `#AI/ML`

---

<a id="item-11"></a>
## [Open-XTTS-Trainer Simplifies XTTS v2 Model Training and Adaptation](https://www.reddit.com/r/MachineLearning/comments/1xcurgj/i_built_openxttstrainer_now_you_can_add_new/) ⭐️ 8.0/10

A new open-source tool called Open-XTTS-Trainer has been released, providing a one-click solution to train all three components of the XTTS v2 text-to-speech model, including the DVAE audio tokenizer and Latent HiFi-GAN vocoder. This tool addresses a critical gap left after Coqui AI shut down, making it significantly easier for developers to adapt the powerful XTTS v2 model to new languages and scripts, thereby democratizing advanced TTS capabilities. The suite includes modular training pipelines for the DVAE tokenizer, GPT text model, and Latent HiFi-GAN vocoder, supports adding new Unicode scripts, and is verified to run on modern PyTorch versions without dependency issues.

reddit · r/MachineLearning · /u/yashubhakt · Oct 22, 21:03

**Background**: XTTS v2 is a state-of-the-art multilingual text-to-speech (TTS) model known for its zero-shot capabilities, supporting 17 languages out-of-the-box. The model consists of three main components: an audio tokenizer (DVAE), a text and vocabulary extender (GPT), and a neural vocoder (Latent HiFi-GAN). Training or fine-tuning these components, especially for new languages, was complex and lacked official support after Coqui AI's closure.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/jik876/hifi-gan">GitHub - jik876/ hifi - gan : HiFi - GAN : Generative Adversarial Networks...</a></li>

</ul>
</details>

**Discussion**: Users expressed strong interest in the tool, particularly its ability to enable training for components previously lacking official support and its potential for adapting XTTS v2 to new languages. Some users inquired about specific implementation details and performance benchmarks.

**Tags**: `#TTS`, `#Machine Learning`, `#Open Source`, `#AI Tools`, `#Speech Synthesis`

---

<a id="item-12"></a>
## [Tesla Launches Cybercab Production in North America for Driverless Rides](https://t.me/zaihuapd/44614) ⭐️ 8.0/10

Tesla has announced the commencement of mass production for its Cybercab, a fully autonomous electric vehicle, in North America. This driverless vehicle is designed without a steering wheel, pedals, or side mirrors, relying entirely on its onboard AI for control. The initiation of Cybercab production marks a significant milestone for Tesla's Robotaxi ambitions, potentially reshaping the future of ride-hailing services. This move could accelerate the adoption of autonomous vehicles in urban environments and impact the transportation industry. The Cybercab is specifically engineered for autonomous operation, with its entire architecture and user interface tailored for driverless scenarios. It represents Tesla's dedicated approach to developing a purpose-built autonomous vehicle for its ride-hailing service.

telegram · zaihuapd · Oct 22, 07:54

**Background**: A robotaxi is an autonomous vehicle operated by a ridesharing company for on-demand passenger services, typically at SAE automation levels 4 or 5. These vehicles aim to reduce operating costs by eliminating the need for a human driver and could potentially decrease congestion and pollution. However, challenges remain regarding safety, regulatory approval, and public trust, with some services still operating at a financial loss.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Cybercab">Cybercab</a></li>
<li><a href="https://en.wikipedia.org/wiki/Robotaxi">Robotaxi</a></li>

</ul>
</details>

**Discussion**: No community discussion was provided for this news item.

**Tags**: `#autonomous vehicles`, `#AI`, `#robotaxi`, `#electric vehicles`, `#Tesla`

---

<a id="item-13"></a>
## [Smart TVs Report Content Data Even When Identification is Disabled, Study Finds](https://watchingthewatchers.github.io/watchingthewatchers/index.html) ⭐️ 8.0/10

A study tested 12 smart TVs from 10 manufacturers and found that some models continue to report content identification data even after the Automatic Content Recognition (ACR) feature is disabled in settings. Furthermore, viewing information from two platforms was transmitted unencrypted. This research highlights a significant privacy concern, indicating that users may not have full control over their viewing data even when they believe they have disabled tracking features. The unencrypted transmission of sensitive information poses a risk to user privacy and data security. VIDAA OS transmits data, including a non-resettable device ID and audio fingerprint, via unencrypted MQTT, while Vizio's WatchFree+ includes program names in unencrypted domain queries, and this specific feature cannot be turned off by the user.

telegram · zaihuapd · Oct 22, 09:50

**Background**: Automatic Content Recognition (ACR) is a technology in smart TVs that identifies what is playing on the screen, often to track viewing habits for advertising or content recommendations. MQTT is a lightweight messaging protocol designed for IoT devices with limited bandwidth, typically running over TCP/IP. Audio fingerprinting creates a unique digital summary of an audio signal to identify content.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Automatic_content_recognition">Automatic content recognition - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/MQTT">MQTT</a></li>
<li><a href="https://en.wikipedia.org/wiki/Audio_fingerprinting">Audio fingerprinting</a></li>

</ul>
</details>

**Discussion**: The community expressed significant concern over the findings, with many users feeling their privacy is being violated despite efforts to control settings. There's a call for greater transparency and stronger user controls from manufacturers.

**Tags**: `#smart TV`, `#privacy`, `#data security`, `#ACR`, `#IoT`

---

<a id="item-14"></a>
## [miHoYo and Tsinghua University Open-Source Game Operation Model](https://arxiv.org/abs/2610.28698v1) ⭐️ 8.0/10

miHoYo's AI team, in collaboration with Tsinghua University and others, has open-sourced GameScaling, a game operation model built upon Qwen3.5. This model is designed for continued pre-training on keyboard and mouse actions, with scales ranging from 0.8B to 27B parameters, and it predicts future actions within a 200ms window. The release of GameScaling, with its varying model scales and open-sourced checkpoints under the Apache-2.0 license, is significant for the AI and gaming research community. It allows researchers and developers to explore advanced AI-driven game interaction and potentially develop more sophisticated game automation or assistive technologies. The research investigated the impact of data quantity and diversity on model performance, finding that more data improves same-source performance, while diversity aids transfer to similar games but offers limited gains for vastly different ones. The release includes eight checkpoints and an inference client, but not the training code.

telegram · zaihuapd · Oct 22, 11:32

**Background**: Qwen3.5 is a family of open-source multimodal large language models developed by Alibaba Cloud, known for their capabilities in reasoning, coding, and multimodal understanding. The Apache-2.0 license is a permissive free-software license that allows users to use, distribute, and modify the software freely without royalties, making it suitable for commercial deployments.

<details><summary>References</summary>
<ul>
<li><a href="https://grokipedia.com/page/Qwen35">Qwen3.5</a></li>
<li><a href="https://www.apache.org/licenses/LICENSE-2.0">Apache License , Version 2 . 0 | Apache Software Foundation</a></li>

</ul>
</details>

**Discussion**: The community has shown interest in the open-sourcing of GameScaling, particularly its potential applications in AI-driven gaming. Discussions may focus on the model's performance across different game genres and its utility for creating more interactive or automated gaming experiences.

**Tags**: `#AI`, `#Gaming`, `#Open Source`, `#LLM`, `#Computer Vision`

---

<a id="item-15"></a>
## [Oracle Issues Critical Security Alert for Java SE Vulnerability CVE-2026-91403](https://www.oracle.com/security-alerts/alert-cve-2026-91403.html) ⭐️ 8.0/10

Oracle has released a critical security alert for a high-severity vulnerability, identified as CVE-2026-91403, in its Java SE product. This vulnerability allows for remote, unauthenticated exploitation. With a CVSS score of 9.1, this vulnerability poses a significant risk to data confidentiality and integrity for a widely used technology. Prompt patching is crucial to prevent potential cyberattacks. The vulnerability resides in the JSSE component and can be exploited over the network without authentication, impacting multiple versions including Java SE 8u511, 11.0.33, 17.0.21, and others. Oracle has released patches and urges users to upgrade.

telegram · zaihuapd · Oct 22, 12:30

**Background**: Java SE (Standard Edition) is a widely used platform for developing and deploying Java applications. JSSE (Java Secure Socket Extension) is a security component within Java SE that provides an API for secure network communications, implementing protocols like SSL/TLS. CVSS (Common Vulnerability Scoring System) is a framework used to rate the severity of computer system vulnerabilities.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Java_Secure_Socket_Extension">Java Secure Socket Extension - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Common_Vulnerability_Scoring_System">Common Vulnerability Scoring System - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#Java SE`, `#Security Vulnerability`, `#CVE`, `#Oracle`, `#Patch`

---

<a id="item-16"></a>
## [333 Compromised Tor Exit Nodes with Ebury Backdoor Taken Down](https://kaba.cx/posts/20261020_Tor/) ⭐️ 8.0/10

A Tor operator discovered 333 Tor exit nodes compromised with the Ebury backdoor, representing about 10% of scanned nodes, and subsequently took them offline after flagging them as 'BadExit'. These compromised nodes were found to be hijacking SSH connections and potentially intercepting unencrypted email traffic. This incident highlights a significant security breach within the Tor network, which is crucial for online anonymity and privacy. The compromise of exit nodes could have exposed sensitive user data and undermined trust in the network's ability to protect users. The Ebury backdoor was used to redirect SSH connections on port 22 to 12 intercepting servers for credential theft, and attackers had been compromising these servers since August, blocking some ports to collect unencrypted email traffic.

telegram · zaihuapd · Oct 22, 14:52

**Background**: Tor is a free and open-source network that enables anonymous communication by routing internet traffic through a series of volunteer-operated relays. Tor exit nodes are the final relays in the path, connecting to the public internet, making them potential targets for monitoring or interception.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Tor_exit_node">Tor exit node</a></li>
<li><a href="https://attack.mitre.org/software/S0377/">Ebury, Software S0377 | MITRE ATT&CK®</a></li>
<li><a href="https://salivity.github.io/tor/article/understanding-the-tor-bad-exit-flag">Understanding the Tor BadExit Flag - tor</a></li>

</ul>
</details>

**Discussion**: The discovery and swift action to take down the compromised nodes have been met with appreciation for the operator's vigilance. Concerns have been raised about the methods used by attackers and the ongoing challenge of maintaining the security of the Tor network.

**Tags**: `#security`, `#Tor`, `#networking`, `#malware`

---

<a id="item-17"></a>
## [China State-Backed Firm Buys Banned Nvidia B300 AI Chips, Redacts Details](https://theinference.org/article/china-s-state-money-bought-banned-nvidia-b300-servers-then-redacted-the-receipts) ⭐️ 8.0/10

A Chinese state-backed leasing group financed the purchase of 32 servers equipped with Nvidia's banned B300 AI chips for AI company Glory View Technology. This acquisition was part of a larger deal for over 700 servers totaling more than 3 billion yuan, intended for deployment at China Mobile's Ningxia hub. This incident highlights potential circumvention of US export controls on advanced AI hardware by Chinese entities, impacting the global AI supply chain and geopolitical technology competition. It raises concerns about the effectiveness of US sanctions in restricting China's access to cutting-edge AI technology. The B300 chips are subject to the highest tier of US export controls, effectively banning their sale to China. After regulatory scrutiny, the leasing group resubmitted documents with hardware descriptions redacted. Nvidia stated it is investigating the matter with its partners, and Asus confirmed compliance with export controls.

telegram · zaihuapd · Oct 22, 15:22

**Background**: Nvidia's B300, part of the Blackwell Ultra architecture, is designed for high-performance AI inference and training, featuring advanced GPUs with substantial memory. US export controls aim to limit China's access to advanced semiconductor technology that could be used for military or advanced AI applications.

<details><summary>References</summary>
<ul>
<li><a href="https://www.nvidia.com/en-us/data-center/dgx-b300/">An AI Factory for AI Reasoning NVIDIA DGX B300 Introduction to NVIDIA DGX B300 System NVIDIA B300: Detailed Specifications and Benchmark Ratings ... NVIDIA B300 Specs: 288GB Blackwell Ultra & DGX B300 Price ... NVIDIA DGX B300 Datasheet NVIDIA B300 Specs, Pricing & AI Inference Benchmarks ... Inside NVIDIA Blackwell Ultra: The Chip Powering the AI ...</a></li>
<li><a href="https://docs.nvidia.com/dgx/dgxb300-user-guide/introduction-to-dgxb300.html">Introduction to NVIDIA DGX B300 System NVIDIA B300: Detailed Specifications and Benchmark Ratings ... NVIDIA B300 Specs: 288GB Blackwell Ultra & DGX B300 Price ... NVIDIA DGX B300 Datasheet NVIDIA B300 Specs, Pricing & AI Inference Benchmarks ... Inside NVIDIA Blackwell Ultra: The Chip Powering the AI ...</a></li>
<li><a href="https://cputronic.com/en/gpu/nvidia-b300">NVIDIA B300: Detailed Specifications and Benchmark Ratings ...</a></li>

</ul>
</details>

**Discussion**: The community expressed concern over the potential violation of US export controls and the implications for Nvidia's supply chain integrity. Some noted the sophistication of state-backed entities in navigating such restrictions.

**Tags**: `#AI chips`, `#export controls`, `#Nvidia`, `#China`, `#geopolitics`

---

<a id="item-18"></a>
## [SpaceX in Talks to Lease 80,000 Cell Sites for Fourth US Wireless Carrier](https://www.bloomberg.com/news/articles/2026-10-22/spacex-in-talks-to-access-80-000-cell-sites-for-wireless-network) ⭐️ 8.0/10

SpaceX is reportedly in negotiations to lease approximately 80,000 cell sites from infrastructure providers like Crown Castle, aiming to establish itself as a fourth national wireless carrier in the United States. This move follows SpaceX's recent acquisition of low-frequency spectrum and approval to launch 15,000 direct-to-cell satellites. This strategic initiative by SpaceX could significantly disrupt the U.S. telecommunications market, potentially impacting incumbent carriers like AT&T, Verizon, and T-Mobile, as evidenced by their stock price reactions. The development signals a major push into the mobile network operator space by a company already prominent in satellite internet. The potential deal is valued in the billions of dollars, and SpaceX has also acquired low-band spectrum, which is crucial for wide-area coverage. The company has also received approval for 15,000 satellites capable of direct-to-cell communication.

telegram · zaihuapd · Oct 23, 03:30

**Background**: Cell sites, also known as cell towers or base stations, are the physical locations where wireless carriers house their equipment to provide mobile network coverage. Leasing these sites is a common practice for expanding network reach. Low-band spectrum offers excellent coverage over large geographical areas, making it ideal for nationwide services, while direct-to-cell technology allows standard mobile phones to connect directly to satellites without needing traditional cell towers.

<details><summary>References</summary>
<ul>
<li><a href="https://www.celltowerleaseexperts.com/cell-tower-lease/">Cell Tower Lease Rates 2026: Data From 300,000+ Cell Sites</a></li>
<li><a href="https://eu.westbase.io/what-is-low-mid-and-high-band-the-5g-spectrum-layers-explained/">What Is Low , Mid, and High- Band ? The 5G Spectrum ... | Westbase</a></li>
<li><a href="https://orbitalradar.com/glossary/direct-to-cell">Direct-to-Cell (D2C): Satellite-to-Phone Tech Explained</a></li>

</ul>
</details>

**Discussion**: The news has generated significant discussion regarding the potential impact on existing mobile carriers and the feasibility of SpaceX's ambitious plan. Some express excitement about increased competition and innovation, while others raise concerns about regulatory hurdles and the technical challenges of building a nationwide network.

**Tags**: `#telecommunications`, `#SpaceX`, `#wireless network`, `#business strategy`

---