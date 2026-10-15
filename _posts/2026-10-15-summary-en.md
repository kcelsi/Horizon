---
layout: default
title: "Horizon Summary: 2026-10-15 (EN)"
date: 2026-10-15
lang: en
---

> From 43 items, 5 important content pieces were selected

---

1. [Google Reportedly Links Phone Numbers Across All Signed-In Accounts](#item-1) ⭐️ 8.0/10
2. [Mapping Post-Transformer Architectures for Enhanced AI Capabilities](#item-2) ⭐️ 8.0/10
3. [Research Traces LLM 'Slop' Style to Training Stages and Model Activations](#item-3) ⭐️ 8.0/10
4. [Anthropic Launches Free AI-Powered OSS Vulnerability Scanner](#item-4) ⭐️ 8.0/10
5. [Apple Sues OpenAI for Alleged Systematic Theft of Trade Secrets](#item-5) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [Google Reportedly Links Phone Numbers Across All Signed-In Accounts](https://www.androidauthority.com/google-auto-phone-number-verification-android-3723117/) ⭐️ 8.0/10

Google is reportedly implementing a system that links a user's phone number across all their signed-in accounts, even if the number was provided for different purposes or on different accounts. This change aims to enhance account security and verification processes. This development raises significant privacy concerns as it could enable more comprehensive user tracking and data deanonymization by Google, potentially impacting user trust and the perceived privacy of their online activities. The linking of phone numbers is said to be happening silently in the background, without explicit user consent for this specific cross-account linkage. Users are concerned about the potential for this consolidated data to be used for targeted advertising or other purposes beyond basic account security.

hackernews · Brajeshwar · Oct 14, 16:28 · [Discussion](https://news.ycombinator.com/item?id=50090349)

**Background**: Data deanonymization refers to the process of re-identifying individuals from anonymized or pseudonymized data. Account security involves measures taken to protect user accounts from unauthorized access, often through passwords, multi-factor authentication, and verification processes.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Data_anonymization">Data anonymization</a></li>
<li><a href="https://en.wikipedia.org/wiki/Account_Security">Account Security</a></li>

</ul>
</details>

**Discussion**: Community members express strong concerns about Google's aggressive anti-privacy practices and the normalization of phone number requests by websites, viewing the phone number as a de facto internet social security number. There is frustration over Google's integrated services potentially leading to account lockouts and a desire for regulations to prevent single corporate entities from controlling too many essential services.

**Tags**: `#privacy`, `#data security`, `#google`, `#android`, `#surveillance`

---

<a id="item-2"></a>
## [Mapping Post-Transformer Architectures for Enhanced AI Capabilities](https://www.reddit.com/r/MachineLearning/comments/1x5u2wz/mapping_the_posttransformer_architecture/) ⭐️ 8.0/10

A comparative analysis maps various post-Transformer architectures, including Mamba, RWKV, xLSTM, and others, detailing their core mechanisms, attention variants, and memory capabilities. The post highlights a trend towards architectures that improve reasoning, memory, and adaptation within practical compute and energy constraints. This exploration is significant as it suggests the next frontier in AI may shift from pure scaling to achieving greater intelligence with limited resources. These emerging architectures could lead to more efficient and capable AI models, impacting various applications and industries. The analysis includes a comparison table detailing architectures like Mamba-3 (Selective SSM, complex-valued state), RWKV-7 (Parallelizable RNN, constant memory), xLSTM (Exponential gating, matrix memory), and Titans (Neural long-term memory). It also categorizes overlaps in features like linear attention, softmax attention, and test-time fast weights.

reddit · r/MachineLearning · /u/Public-Feedback-6705 · Oct 14, 15:22

**Background**: Transformer architectures have dominated large language models (LLMs) due to their attention mechanisms, but they face challenges with quadratic complexity in sequence length. Post-Transformer architectures aim to overcome these limitations by exploring alternative mechanisms like state space models (SSMs) and recurrent neural networks (RNNs) to achieve linear or near-linear scaling.

<details><summary>References</summary>
<ul>
<li><a href="https://grokipedia.com/page/Mamba_deep_learning_architecture">Mamba (deep learning architecture)</a></li>
<li><a href="https://wiki.rwkv.com/basic/architecture.html">RWKV Architecture History</a></li>
<li><a href="https://www.nx-ai.com/en/core-architecture">xLSTM . The architecture for what comes next.</a></li>

</ul>
</details>

**Discussion**: Community members expressed interest in the comprehensive mapping of post-Transformer architectures, with discussions focusing on the trade-offs between different approaches and their potential for specific tasks. Some users highlighted the importance of efficiency and adaptation alongside raw performance.

**Tags**: `#AI`, `#Machine Learning`, `#Deep Learning`, `#Architecture`, `#LLM`

---

<a id="item-3"></a>
## [Research Traces LLM 'Slop' Style to Training Stages and Model Activations](https://www.reddit.com/r/MachineLearning/comments/1x64lbk/tracing_where_llm_slop_style_comes_from_in_the/) ⭐️ 8.0/10

This research identifies that the characteristic 'slop' style in LLMs, marked by features like em dashes and buzzwords, originates from specific training stages, namely Supervised Fine-Tuning (SFT) and Direct Preference Optimization (DPO). It further pinpoints a 'register axis' within the model's activations that correlates strongly with these stylistic elements. Understanding the origins of LLM 'slop' style is crucial for developing more controlled and precise language generation. This work allows for targeted interventions to mitigate undesirable stylistic artifacts, potentially leading to more reliable and user-friendly AI assistants. The study found that SFT introduces rhetorical structures, while DPO amplifies buzzwords and markdown formatting, effectively doubling the 'slop' score. A register axis was identified, distinguishing abstract vocabulary from common hedges, and this axis showed cross-lingual consistency for certain tropes like 'not X, but Y'. Directional ablation techniques were used to reduce this style, with a rank-16 LoRA achieving an 83% reduction in the slop score.

reddit · r/MachineLearning · /u/Imaginary_Money2285 · Oct 14, 22:08

**Background**: Supervised Fine-Tuning (SFT) is a common post-training step for Large Language Models (LLMs) where the model learns from curated datasets of input-output pairs to improve its ability to follow instructions and adopt a specific style. Direct Preference Optimization (DPO) is another training technique that refines LLM behavior by learning from human preferences between pairs of model outputs, often used to enhance helpfulness and harmlessness.

<details><summary>References</summary>
<ul>
<li><a href="https://www.geeksforgeeks.org/artificial-intelligence/supervised-fine-tuning-sft-for-llms/">Supervised Fine-Tuning (SFT) for LLMs - GeeksforGeeks</a></li>
<li><a href="https://arxiv.org/html/2509.06948v1">Beyond Two-Stage Training: Cooperative SFT and RL</a></li>
<li><a href="https://deepwiki.com/xubuvd/LLMs/2.2-direct-preference-optimization-(dpo)">Direct Preference Optimization ( DPO ) | xubuvd/LLMs | DeepWiki</a></li>

</ul>
</details>

**Discussion**: The Reddit community expressed significant interest, with users highlighting the practical implications for controlling LLM output and appreciating the detailed technical breakdown. Some comments discussed the limitations of the 'slop' scorer and the need for human evaluation, while others shared insights on similar phenomena observed in different models.

**Tags**: `#LLM`, `#AI`, `#Natural Language Processing`, `#Machine Learning`, `#Research`

---

<a id="item-4"></a>
## [Anthropic Launches Free AI-Powered OSS Vulnerability Scanner](https://t.me/zaihuapd/44407) ⭐️ 8.0/10

Anthropic has launched OSS Scanner, a new service that provides free, opt-in vulnerability scanning for qualifying open-source projects. The scanner utilizes AI models like Claude to automatically identify and report potential security flaws, including reproduction steps and patch suggestions. This initiative significantly enhances the security posture of the open-source ecosystem, which underpins much of the modern technology landscape. By offering this free service, Anthropic aims to proactively address security vulnerabilities before they can be exploited, benefiting developers and users alike. The reports generated by OSS Scanner are not human-reviewed and may contain errors; however, Anthropic reported identifying over 29,000 candidate vulnerabilities in the past six months. Projects can apply for scanning by submitting a GitHub Pull Request (PR).

telegram · zaihuapd · Oct 14, 09:25

**Background**: Open-source software (OSS) is software with source code that anyone can inspect, modify, and enhance. Vulnerability scanning is the process of identifying security weaknesses in software. AI assistants like Claude are large language models designed to understand and generate human-like text, and can be applied to tasks like code analysis.

<details><summary>References</summary>
<ul>
<li><a href="https://www.anthropic.com/claude/haiku">Claude Haiku \ Anthropic</a></li>
<li><a href="https://claude.com/">Claude</a></li>
<li><a href="https://aws.amazon.com/bedrock/anthropic/">Claude by Anthropic - Models in Amazon Bedrock – AWS</a></li>

</ul>
</details>

**Discussion**: The community generally views this as a positive step towards improving open-source security, appreciating Anthropic's contribution. Some discussions may revolve around the accuracy of AI-generated reports and the potential for false positives or negatives.

**Tags**: `#AI`, `#Open Source Security`, `#Vulnerability Scanning`, `#Anthropic`

---

<a id="item-5"></a>
## [Apple Sues OpenAI for Alleged Systematic Theft of Trade Secrets](https://t.me/zaihuapd/44415) ⭐️ 8.0/10

Apple filed a lawsuit on July 10th in the U.S. District Court for the Northern District of California against OpenAI, two former employees, and io Products, alleging systematic theft of trade secrets related to hardware development and supply chain information. This lawsuit highlights the intense competition and legal scrutiny in the AI and hardware development sectors, potentially impacting intellectual property protection and future innovation for both Apple and OpenAI. The lawsuit claims former employees downloaded dozens of hardware files and sent supplier information to personal emails, with OpenAI allegedly using this information to accelerate consumer hardware research and development.

telegram · zaihuapd · Oct 15, 00:25

**Background**: OpenAI, a leading AI research company, has been reportedly exploring hardware development, including custom chips and devices, to enhance its AI product performance and reduce reliance on third-party hardware. io Products is an AI hardware company founded by former Apple design chief Jony Ive and others, which was acquired by OpenAI in May 2025.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Io_Products">Io Products</a></li>
<li><a href="https://openai.com/index/openai-broadcom-jalapeno-inference-chip/">OpenAI and Broadcom unveil LLM-optimized inference chip</a></li>
<li><a href="https://builtin.com/articles/openai-device">OpenAI’s New Device: What We Know So Far | Built In</a></li>

</ul>
</details>

**Discussion**: Community discussions express surprise at the lawsuit's timing, given OpenAI's recent hardware initiatives, and raise questions about the definition and protection of trade secrets in the fast-paced AI industry.

**Tags**: `#Legal`, `#Intellectual Property`, `#AI`, `#Hardware Development`, `#Trade Secrets`

---