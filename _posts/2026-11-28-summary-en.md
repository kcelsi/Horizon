---
layout: default
title: "Horizon Summary: 2026-11-28 (EN)"
date: 2026-11-28
lang: en
---

> From 27 items, 5 important content pieces were selected

---

1. [Critical Linux Kernel NFS Vulnerability Grants Unauthenticated Root Access](#item-1) ⭐️ 9.0/10
2. [Google's DeepCrossAttention boosts Transformer speed and quality](#item-2) ⭐️ 8.0/10
3. [WebRTC Exploited for Credit Card Skimming on Shopping Sites](#item-3) ⭐️ 8.0/10
4. [AWS Trainium3 Inference Deep Dive Challenges NVIDIA GB300](#item-4) ⭐️ 8.0/10
5. [Critical RCE Vulnerability Found in Minecraft Java Edition via Font Parsing](#item-5) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [Critical Linux Kernel NFS Vulnerability Grants Unauthenticated Root Access](https://opensec.in/blog/nfs2root-cve-2026-99362) ⭐️ 9.0/10

OpenSec has disclosed CVE-2026-99362, a critical pre-authentication stack overflow vulnerability in the Linux kernel's NFS server (nfsd). This vulnerability allows attackers to achieve root access without any authentication by exploiting a buffer overflow on the kernel heap via TCP port 2049. With a CVSS score of 9.8, this vulnerability poses a significant risk to a wide range of systems, including file servers, NAS devices, and cluster storage nodes, as it has existed since Linux kernel 3.16 (2014) and affects NFSv4.1 and 4.2 implementations. The vulnerability allows for out-of-bounds writes to the kernel heap, leading to root shell acquisition. Patches are available in kernel versions 6.12.117, 6.18.61, 7.3.2, and 7.4-rc1, requiring a kernel upgrade and system reboot; as an interim mitigation, restricting access to TCP port 2049 can be applied.

telegram · zaihuapd · Nov 27, 12:57

**Background**: NFS (Network File System) is a distributed file system protocol that allows a user on a client computer to access files over a network in a manner similar to how local storage is accessed. A stack overflow vulnerability occurs when a program writes more data to the stack than it is allocated to hold, potentially overwriting adjacent memory and leading to code execution or crashes.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/NFS_series">NFS series</a></li>
<li><a href="https://en.wikipedia.org/wiki/Stack_buffer_overflow">Stack buffer overflow - Wikipedia</a></li>

</ul>
</details>

**Discussion**: The disclosure highlights the long-standing nature of the vulnerability and its broad impact, with users likely concerned about the need for urgent patching and the potential for exploitation given the lack of authentication required.

**Tags**: `#Linux Kernel`, `#NFS`, `#Vulnerability`, `#Security`, `#CVE`

---

<a id="item-2"></a>
## [Google's DeepCrossAttention boosts Transformer speed and quality](https://research.google/blog/supercharging-transformer-residual-connections/) ⭐️ 8.0/10

Google researchers have developed DeepCrossAttention (DCA), a new technique that enhances Transformer architecture by replacing fixed residual sums with learned depth routing. This innovation allows for comparable model quality at up to three times the processing speed. This advancement could significantly reduce the computational cost and latency of large language models, making AI more accessible and efficient for a wider range of applications and users. DCA applies attention across layers in depth, allowing each token to query a dynamically weighted mix of prior layer embeddings, thereby unlocking historical context without the computational penalty of traditional attention scaling.

hackernews · ComputedCamp995 · Nov 27, 23:06 · [Discussion](https://news.ycombinator.com/item?id=50672565)

**Background**: Transformer networks are a type of neural network architecture that has achieved remarkable success in various domains, particularly in natural language processing. Residual connections are a key component that helps in training deep networks by allowing gradients to flow more easily. DeepCrossAttention enhances this by making the residual connections learned and dynamic across layers.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2502.06785">[2502.06785] DeepCrossAttention: Supercharging Transformer ...</a></li>
<li><a href="https://arxiv.org/html/2502.06785">DeepCrossAttention: Supercharging Transformer Residual ...</a></li>
<li><a href="https://explainx.ai/blog/google-deepcrossattention-transformer-residual-connections-2026">DeepCrossAttention (DCA): Google Fix for Deep Transformers ...</a></li>

</ul>
</details>

**Discussion**: Some users are discussing the potential impact of such efficiency improvements on the cost and performance of AI models like Gemini and Claude, with one user noting that Gemini Neon is already perceived as cheap and fast.

**Tags**: `#AI`, `#Machine Learning`, `#Transformer`, `#Deep Learning`, `#Optimization`

---

<a id="item-3"></a>
## [WebRTC Exploited for Credit Card Skimming on Shopping Sites](https://www.infohawk.com/news/2026-11-27-black-friday-webrtc-skimmer) ⭐️ 8.0/10

A novel credit card skimming technique has been identified that leverages WebRTC (Web Real-Time Communication) to capture payment details on popular e-commerce websites. This discovery highlights a new attack vector that exploits less-monitored technologies, posing a significant threat to online shoppers and e-commerce security, and prompting a re-evaluation of web security practices. The attack uses WebRTC, a technology typically used for real-time communication, to exfiltrate sensitive data, suggesting that the vulnerability lies not in WebRTC's capabilities but in its infrequent monitoring for malicious activity.

hackernews · scanr · Nov 27, 15:40 · [Discussion](https://news.ycombinator.com/item?id=50668145)

**Background**: Credit card skimming refers to the fraudulent capture of credit card information, often through hidden devices or malicious software, to make unauthorized purchases. WebRTC is an open-source project that enables real-time audio, video, and data communication directly between web browsers and mobile applications without needing plugins.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Credit_card_skimming">Credit card skimming</a></li>
<li><a href="https://en.wikipedia.org/wiki/WebRTC">WebRTC</a></li>

</ul>
</details>

**Discussion**: Community members expressed concerns about the inherent security risks of embedding third-party scripts, the need for better ad blocking and sandboxing of external code, and questioned the fundamental security of current payment systems.

**Tags**: `#cybersecurity`, `#WebRTC`, `#malware`, `#e-commerce security`, `#vulnerability`

---

<a id="item-4"></a>
## [AWS Trainium3 Inference Deep Dive Challenges NVIDIA GB300](https://newsletter.semianalysis.com/p/trainium3-inferencex) ⭐️ 8.0/10

This article provides an in-depth analysis of AWS's Trainium3 AI accelerator, focusing on its inference capabilities and microarchitecture. It compares Trainium3's performance and Total Cost of Ownership (TCO) against NVIDIA's GB300, suggesting competitive advantages for AWS in the AI hardware market. This analysis is significant as it pits a major cloud provider's custom AI silicon against the industry leader's offering, impacting cloud AI infrastructure costs and performance. Businesses relying on AI for inference will be affected by the competitive landscape and potential cost savings. The Trainium3 features a physics-based architecture with high Model FLOPs Utilization (MFU) and Memory Bandwidth Utilization (MBU), achieving low latency for inference tasks. Its HBM3E memory has been upgraded to 12 layers, providing 144GB of memory per chip.

rss · Semianalysis · Nov 27, 15:54

**Background**: AI accelerators like AWS Trainium3 and NVIDIA GB300 are specialized hardware designed to speed up machine learning computations. MFU measures how effectively an AI chip utilizes its theoretical peak performance for a given model, while MBU is a similar metric for memory bandwidth, crucial for tasks like token generation in large language models.

<details><summary>References</summary>
<ul>
<li><a href="https://min.news/en/tech/1e0284c19edeada240cd36f6df1924a9.html">AWS Unleashes a Computing Power Bomb: In-Depth Analysis of...</a></li>
<li><a href="https://inferencex.semianalysis.com/glossary/model-flops-utilization">What Is Model FLOPs Utilization (MFU)? | InferenceX</a></li>

</ul>
</details>

**Discussion**: The discussion highlights the importance of comparing inference performance and TCO, with particular interest in metrics like MFU and MBU for evaluating efficiency. There's anticipation for how these custom silicon offerings will shape the future of cloud AI infrastructure.

**Tags**: `#AI Hardware`, `#Cloud Computing`, `#Performance Analysis`, `#Machine Learning`

---

<a id="item-5"></a>
## [Critical RCE Vulnerability Found in Minecraft Java Edition via Font Parsing](https://t.me/zaihuapd/45413) ⭐️ 8.0/10

A critical Remote Code Execution (RCE) vulnerability, dubbed 'minecraft2shell', has been disclosed affecting Minecraft Java Edition versions 1.20.5 through 1.21.10 and snapshots 26.1 through 26.4. The vulnerability is triggered by a specially crafted TrueType font within server resource packs, exploiting an issue in FreeType versions 2.14.3 and earlier. This vulnerability allows attackers to execute arbitrary code on affected clients, posing a significant security risk to a game with a massive player base. The fact that Mojang has not yet released a patch and continues to use a vulnerable version of the FreeType library exacerbates the concern. The exploit involves a native out-of-bounds write in FreeType when parsing a malicious TrueType font, leading to arbitrary code execution on Windows clients. Versions 1.20.4 and earlier, as well as the Bedrock Edition, are not affected.

telegram · zaihuapd · Nov 27, 18:04

**Background**: Remote Code Execution (RCE) vulnerabilities allow attackers to run any commands on a target machine over a network. TrueType fonts are a common font format, and vulnerabilities in their parsing libraries, like FreeType, can be exploited to compromise systems. FreeType is a widely used open-source library for rendering fonts.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/RCE_vulnerability">RCE vulnerability</a></li>
<li><a href="https://freetype.org/">The FreeType Project: a free , high-quality and portable Font engine</a></li>
<li><a href="https://linuxfromscratch.org/blfs/view/svn/general/freetype2.html">FreeType - 2 .15.0</a></li>

</ul>
</details>

**Discussion**: The community is concerned about the lack of an immediate patch from Mojang and the continued use of the vulnerable FreeType library, highlighting the potential for widespread exploitation given Minecraft's popularity.

**Tags**: `#security`, `#vulnerability`, `#RCE`, `#Minecraft`, `#FreeType`

---