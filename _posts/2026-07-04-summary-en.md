---
layout: default
title: "Horizon Summary: 2026-07-04 (EN)"
date: 2026-07-04
lang: en
---

> From 47 items, 7 important content pieces were selected

---

1. [MEP Investigating Spyware Targeted with Pegasus](#item-1) ⭐️ 8.0/10
2. [PostgreSQL Stability: Why Strict Memory Overcommit is Crucial](#item-2) ⭐️ 8.0/10
3. [New Method Recovers Finetuning Data from LLMs Using Only Logit Access](#item-3) ⭐️ 8.0/10
4. [Anthropic Accuses Alibaba of Massive AI 'Distillation Attack' to Steal Claude Capabilities](#item-4) ⭐️ 8.0/10
5. [Huawei Launches Atlas 350 AI Accelerator with Ascend 950PR, Outperforming NVIDIA H20](#item-5) ⭐️ 8.0/10
6. [Huawei Mate 80 Pro's Kirin 9030 Achieves Superior Gaming Efficiency with HarmonyOS](#item-6) ⭐️ 8.0/10
7. [Tencent's Atuin AI Outperforms Anthropic's Mythos in Cybersecurity Benchmark](#item-7) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [MEP Investigating Spyware Targeted with Pegasus](https://citizenlab.ca/research/member-of-committee-investigating-spyware-hacked-with-pegasus/) ⭐️ 8.0/10

A member of the European Parliament's committee tasked with investigating spyware was himself infected with Pegasus spyware on multiple occasions between October 2022 and March 2023. The forensic analysis was conducted by Citizen Lab. This incident raises serious concerns about state-sponsored espionage within the EU and the potential for sophisticated actors to target lawmakers. It highlights the ongoing threat posed by advanced spyware to democratic institutions and personal privacy. The infections occurred around October 21, 2022, and again on March 6 and 7, 2023, using what is likely a zero-click exploit. There is an overlap with a previous Pegasus campaign targeting Russian and Belarusian exiles, suggesting the actor has authorization to operate across multiple European countries.

hackernews · ledoge · Jul 3, 20:38 · [Discussion](https://news.ycombinator.com/item?id=48779683)

**Background**: Pegasus is a sophisticated spyware developed by the Israeli NSO Group, capable of covertly accessing and extracting data from mobile devices. It is designed for use against national security threats but has been widely misused by governments to target journalists, activists, and political dissidents. The sale of Pegasus requires approval from the Israeli Ministry of Defense.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Pegasus_(spyware)">Pegasus (spyware)</a></li>
<li><a href="https://grokipedia.com/page/Zero-click_exploit">Zero-click exploit</a></li>

</ul>
</details>

**Discussion**: Community members expressed concern over the potential for internal EU member states to be involved, given the overlap with previous campaigns and the implication of authorization across multiple countries. Some users debated the separation of personal and work devices and the broader implications for politicians and journalists.

**Tags**: `#cybersecurity`, `#espionage`, `#Pegasus spyware`, `#European Parliament`, `#privacy`

---

<a id="item-2"></a>
## [PostgreSQL Stability: Why Strict Memory Overcommit is Crucial](https://www.ubicloud.com/blog/postgresql-and-the-oom-killer-why-we-use-strict-memory-overcommit) ⭐️ 8.0/10

This article explains that for PostgreSQL, disabling memory overcommit (setting vm.overcommit_memory to 1 or 2) is preferred to prevent the Linux OOM killer from terminating PostgreSQL processes unexpectedly. It contrasts this with Linux's default overcommit behavior, which can lead to instability. This is significant because unexpected termination of PostgreSQL by the OOM killer can lead to data corruption and significant downtime, impacting applications relying on the database. Adopting strict memory overcommit improves database reliability and availability for critical workloads. The article highlights that setting vm.overcommit_memory to 2 (or 1) prevents the kernel from overcommitting memory, ensuring that allocations are backed by actual available memory. While this avoids OOM kills, it may lead to applications failing to allocate memory if the system is truly out of resources.

hackernews · furkansahin · Jul 3, 13:00 · [Discussion](https://news.ycombinator.com/item?id=48774509)

**Background**: Memory overcommit is a Linux kernel feature where the system allows processes to allocate more memory than is physically available, assuming not all allocated memory will be used simultaneously. The Out-of-Memory (OOM) killer is a Linux kernel process that terminates processes when the system runs out of memory to prevent a complete system crash. PostgreSQL, a popular relational database, requires stable memory management to operate correctly.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/OOM_killer">OOM killer</a></li>
<li><a href="https://en.wikipedia.org/wiki/Memory_overcommitment">Memory overcommitment</a></li>
<li><a href="https://practicaldev-herokuapp-com.freetls.fastly.net/shafikshaon/understanding-overcommit-memory-in-linux-kernel-2ek6">Understanding Overcommit Memory in Linux Kernel - DEV Community</a></li>

</ul>
</details>

**Discussion**: Community members noted that Linux's default memory management can be problematic, leading to system instability or unexpected process kills. Some users shared experiences of encountering issues with overcommit settings, emphasizing the need for careful testing in QA/Perf environments before production deployment.

**Tags**: `#PostgreSQL`, `#Linux`, `#Memory Management`, `#System Administration`, `#OOM Killer`

---

<a id="item-3"></a>
## [New Method Recovers Finetuning Data from LLMs Using Only Logit Access](https://www.reddit.com/r/MachineLearning/comments/1umn2dk/contrastive_decoding_diffing_cdd_recovering/) ⭐️ 8.0/10

Contrastive Decoding Diffing (CDD) is a novel grey-box method that can recover verbatim finetuning data from large language models (LLMs) by analyzing only their logits, without needing access to model weights or activations. This method outperforms previous white-box techniques like Activation Difference Lens (ADL) in recovering specific training data. CDD offers a significant advancement in understanding how LLMs are finetuned, enabling the recovery of sensitive or proprietary training data without requiring full model access. This has implications for AI security, data privacy, and auditing the training process of LLMs. CDD directly contrasts the logits of the base and finetuned models, achieving a 4+/5 verbatim recovery score on the SDF benchmark across various model families and sizes. Notably, CDD recovered a recurring fictional persona, 'Dr. Elena Rodriguez,' which was disproportionately favored by Claude Sonnet 3.6 when generating synthetic data.

reddit · r/MachineLearning · /u/CebulkaZapiekana · Jul 3, 19:01

**Background**: Logits are the raw, unnormalized output scores from a machine learning model before they are converted into probabilities. Contrastive Decoding is a technique that uses the difference between the outputs of a large language model and a smaller, simpler model to improve text generation quality. Grey-box testing is a software testing method that combines aspects of both black-box and white-box testing, where testers have partial knowledge of the internal structure of the system.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2210.15097">Contrastive Decoding: Open-ended Text Generation as Optimization</a></li>
<li><a href="https://en.wikipedia.org/wiki/Logit">Logit - Wikipedia</a></li>

</ul>
</details>

**Discussion**: The community expressed strong interest in CDD's ability to recover verbatim data with only logit access, highlighting its potential for auditing and security applications. Some users noted the surprising finding about 'Dr. Elena Rodriguez' and discussed the broader implications of LLM-generated data influencing finetuning.

**Tags**: `#LLM`, `#Finetuning`, `#Model Diffs`, `#AI Security`, `#Machine Learning`

---

<a id="item-4"></a>
## [Anthropic Accuses Alibaba of Massive AI 'Distillation Attack' to Steal Claude Capabilities](https://t.me/zaihuapd/42327) ⭐️ 8.0/10

AI company Anthropic has formally accused Alibaba of conducting a large-scale 'distillation attack' to illegally extract capabilities from its Claude large language model. The accusation, detailed in a letter to the US Senate Banking Committee, claims Alibaba used nearly 25,000 fraudulent accounts to interact with Claude over 28.8 million times between April 22 and June 5, 2026. This accusation highlights a significant escalation in competitive and potentially illicit practices within the AI industry, representing a direct threat to intellectual property and the substantial R&D investments made by leading AI firms. The scale of the alleged attack could have major implications for AI development costs, security protocols, and international regulatory scrutiny. Anthropic described this as the 'largest distillation attack known to date' against their company, involving Alibaba and its AI lab Qwen. Distillation attacks involve using a weaker model to learn from a stronger model's outputs to replicate its capabilities, often at a fraction of the original development cost.

telegram · zaihuapd · Jul 3, 06:21

**Background**: Anthropic is an American AI company known for developing the Claude family of large language models. Alibaba, a Chinese technology conglomerate, has developed its own AI models, including the Qwen series, which are based on Meta AI's Llama architecture. Model distillation is a technique where a smaller, more efficient AI model is trained to mimic the performance of a larger, more complex model by learning from its outputs.

<details><summary>References</summary>
<ul>
<li><a href="https://www.anthropic.com/news/detecting-and-preventing-distillation-attacks">Detecting and preventing distillation attacks \ Anthropic</a></li>
<li><a href="https://medium.com/@tahirbalarabe2/understanding-llm-distillation-attacks-929306ca38cd">Understanding LLM Distillation Attacks | by Tahir | Medium</a></li>
<li><a href="https://www.mindstudio.ai/blog/ai-model-distillation-attacks-explained">AI Model Distillation Attacks: What They Are and Why They Matter | MindStudio</a></li>

</ul>
</details>

**Discussion**: The community is expressing concern over the implications of such large-scale IP theft in the AI sector, with some noting that distillation attacks are a known but difficult-to-prevent threat. There's also discussion about the potential for retaliatory actions and the need for stronger industry-wide security measures.

**Tags**: `#AI`, `#Intellectual Property`, `#Cybersecurity`, `#Competition`

---

<a id="item-5"></a>
## [Huawei Launches Atlas 350 AI Accelerator with Ascend 950PR, Outperforming NVIDIA H20](https://t.me/zaihuapd/42329) ⭐️ 8.0/10

Huawei has officially launched and released the Atlas 350 AI accelerator card, featuring the new Ascend 950PR processor. This new card offers 2.87 times the computing power of NVIDIA's H20 and is the only domestic accelerator card supporting FP4 low-precision inference. The Atlas 350's significant performance leap and unique FP4 inference support position it as a strong contender in the AI hardware market, potentially offering a more cost-effective solution for large model inference and impacting the competitive landscape for AI accelerators. The Atlas 350 boasts 112 GB of HBM capacity, supports loading 70B parameter models on a single card, and significantly reduces inference latency and investment costs through improvements in vector computing power, interconnect bandwidth, and self-developed HBM.

telegram · zaihuapd · Jul 3, 08:35

**Background**: High Bandwidth Memory (HBM) is a type of high-performance RAM used in graphics cards and AI accelerators, offering greater capacity and bandwidth than traditional DDR memory. FP4 inference is a low-precision format that reduces memory usage and computational requirements for AI models, enabling faster and more efficient inference, especially for large language models.

<details><summary>References</summary>
<ul>
<li><a href="https://www.omniyq.com/en/sys-nd/501.html">Ascend 950 : A Milestone for Domestic AI Compute - Shenzhen Cloud...</a></li>
<li><a href="https://spoonai.me/posts/2026-04-13-huawei-950pr-ai-chip-en">Huawei Ascend 950 PR — 2.8x H20 FP4, and ByteDance... | spoonai</a></li>
<li><a href="https://en.wikipedia.org/wiki/High_Bandwidth_Memory">High Bandwidth Memory - Wikipedia</a></li>

</ul>
</details>

**Discussion**: The community is discussing the implications of Huawei's Ascend 950 PR chip and the Atlas 350 card, particularly its competitive positioning against NVIDIA's offerings and the significance of its FP4 inference capabilities for domestic AI development.

**Tags**: `#AI Hardware`, `#Ascend`, `#Huawei`, `#Deep Learning`, `#Inference`

---

<a id="item-6"></a>
## [Huawei Mate 80 Pro's Kirin 9030 Achieves Superior Gaming Efficiency with HarmonyOS](https://www.bilibili.com/video/BV1F7T46wEyT) ⭐️ 8.0/10

A review of the Huawei Mate 80 Pro series reveals that its new Kirin 9030 and 9030 Pro chips, particularly the Pro version with a 9-core CPU and 6-core Mali G935 GPU, demonstrate superior gaming energy efficiency compared to the Snapdragon 8 Gen 3 when running native HarmonyOS applications. This development is significant as it suggests that Huawei's custom silicon and HarmonyOS ecosystem can overcome theoretical performance deficits through software optimization, potentially challenging established chip leaders and impacting the mobile industry's focus on efficiency alongside raw power. Despite theoretical performance lagging behind contemporary flagships, the Mate 80 Pro Max achieved a whole-device power consumption of only 4.9W running Genshin Impact at 60fps, and around 3W for Honor of Kings at 120fps, showcasing significant real-world efficiency gains due to HarmonyOS native app optimization and system-level coordination.

telegram · zaihuapd · Jul 3, 13:27

**Background**: HarmonyOS is Huawei's proprietary operating system, which has evolved from being Android-based to a fully native version that does not rely on the Android Open Source Project (AOSP) core, aiming for better cross-device integration and performance. The Kirin series chips are designed by Huawei's HiSilicon subsidiary, which has faced US trade restrictions impacting its chip manufacturing capabilities.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/HarmonyOS">HarmonyOS - Wikipedia</a></li>
<li><a href="https://www.harmony-developers.com/p/harmonyos-next-native-apps-installs">HarmonyOS Next native apps installs have exceeded one million</a></li>

</ul>
</details>

**Discussion**: Community reaction highlights excitement over Huawei's resurgence in chip technology and the demonstrated efficiency gains from HarmonyOS native applications, with some users expressing optimism about the OS's future and its potential to compete with established mobile platforms.

**Tags**: `#mobile technology`, `#performance testing`, `#HarmonyOS`, `#chipset`, `#energy efficiency`

---

<a id="item-7"></a>
## [Tencent's Atuin AI Outperforms Anthropic's Mythos in Cybersecurity Benchmark](https://mp.weixin.qq.com/s/BzU7g-2iG7d6h4ViwMhxyg) ⭐️ 8.0/10

Tencent's Xuanwu Lab's Atuin AI achieved an 84.0% score in the CyberGym cybersecurity benchmark, surpassing Anthropic's Claude Mythos Preview. Built on the open-source GLM-5.1 model, Atuin AI discovered critical vulnerabilities missed by Mythos at less than 0.1% of its budget. This demonstrates the growing capability of open-source AI models in specialized, high-stakes fields like cybersecurity, potentially democratizing advanced vulnerability discovery. It signals a competitive shift where cost-effectiveness and performance are key differentiators. Atuin AI identified multiple high-risk logical vulnerabilities in projects like curl, gnark, and OpenSSL, achieving a top score of 9.3 in severity, and ranked first in severe vulnerability severity on the Berkeley BVI real-world vulnerability leaderboard.

telegram · zaihuapd · Jul 3, 16:12

**Background**: CyberGym is a large-scale benchmark developed by UC Berkeley to evaluate AI agents' real-world cybersecurity capabilities, featuring over 1,500 historical vulnerabilities from 188 software projects. GLM-5.1 is an open-source large language model developed by Z.ai, known for its strong coding capabilities and local deployment options. Mythos is an AI model developed by Anthropic as part of Project Glasswing, aimed at finding and fixing software vulnerabilities.

<details><summary>References</summary>
<ul>
<li><a href="https://www.cybergym.io/cybergym/">CyberGym: Evaluating AI Agents' Real-World Cybersecurity Capabilities at Scale</a></li>
<li><a href="https://arxiv.org/abs/2506.02548">[2506.02548] CyberGym: Evaluating AI Agents' Real-World Cybersecurity Capabilities at Scale</a></li>
<li><a href="https://rdi.berkeley.edu/blog/cybergym/">CyberGym: Evaluating AI Agents' Real-World ...</a></li>

</ul>
</details>

**Discussion**: The community is impressed by the performance and cost-effectiveness of the open-source Atuin AI, especially its ability to surpass a commercial model like Mythos. There is excitement about the potential for open-source AI to advance cybersecurity research and practice.

**Tags**: `#AI`, `#Cybersecurity`, `#Vulnerability Discovery`, `#Open Source`

---