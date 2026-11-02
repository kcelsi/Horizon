---
layout: default
title: "Horizon Summary: 2026-11-02 (EN)"
date: 2026-11-02
lang: en
---

> From 26 items, 6 important content pieces were selected

---

1. [OmniDiff: A Fast, Open-Source Diff Tool for Diverse File Types](#item-1) ⭐️ 8.0/10
2. [AI is Reshaping Mathematics: From Proof Generation to Problem Selection](#item-2) ⭐️ 8.0/10
3. [Lenovo's 'Encrypted' USB Drive Found to Contain Unencrypted SD Card](#item-3) ⭐️ 8.0/10
4. [GDPx Benchmark Evaluates Frontier AI Models Across Key Economic Domains](#item-4) ⭐️ 8.0/10
5. [Animated Explainer: How GPT-4o's Tokenizer Processes 'strawberry'](#item-5) ⭐️ 8.0/10
6. [LongCat-2.5 Released: A 1.6 Trillion Parameter Native Multimodal Model](#item-6) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [OmniDiff: A Fast, Open-Source Diff Tool for Diverse File Types](https://github.com/ivankovic/omnidiff) ⭐️ 8.0/10

OmniDiff, a new open-source diff tool written in Rust, has been released. It boasts super-fast performance, capable of diffing tens of thousands of lines of C++ code in under 100ms, and supports a wide array of file types including code, images, PDFs, and archives. This tool significantly expands the capabilities of standard Git diffing, offering a unified and efficient solution for comparing diverse file formats. Its speed and broad file type support could improve developer workflows and code review processes across various domains. OmniDiff is licensed under AGPLv3, indicating a strong copyleft stance, and is built upon manual analysis of 2000 diffs from Gentoo repositories to ensure practical utility. The project is currently at version 0.3.0 but has been used daily by the developer for months.

hackernews · FabCH · Nov 1, 13:02 · [Discussion](https://news.ycombinator.com/item?id=50325253)

**Background**: Git difftool is a command provided by Git that allows users to use external diff programs to compare changes between different versions of files. The GNU Affero General Public License (AGPLv3) is a free, copyleft license intended for software run over a network, requiring that the source code of modified versions be made available to users interacting with the software over a network.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/GNU_Affero_General_Public_License">GNU Affero General Public License - Wikipedia</a></li>
<li><a href="https://git-scm.com/docs/git-difftool">Git - git - difftool Documentation</a></li>

</ul>
</details>

**Discussion**: Community members expressed interest in OmniDiff's broad file type support and speed, but also raised concerns about its handling of edge cases (0.05% of changes) and its integration with existing Git workflows, such as rebasing and non-global configuration. There was also positive feedback regarding its AGPLv3 license.

**Tags**: `#software-development`, `#developer-tools`, `#rust`, `#open-source`, `#AI/ML`

---

<a id="item-2"></a>
## [AI is Reshaping Mathematics: From Proof Generation to Problem Selection](https://terrytao.wordpress.com/2026/11/01/mathematics-has-changed-lets-act-like-it/) ⭐️ 8.0/10

The article "Mathematics has changed. Let's act like it" by Terry Tao argues that the advent of AI is fundamentally altering the practice of mathematics. It suggests a shift in focus from generating proofs to selecting problems, understanding results, and exploring applications. This paradigm shift is significant as it redefines the role of mathematicians in an AI-augmented future, potentially impacting research methodologies, educational priorities, and the very definition of mathematical contribution. The discussion highlights that while AI excels at proof generation, human mathematicians may increasingly focus on 'digestion'—understanding, contextualizing, and extending mathematical results, as well as identifying novel problems.

hackernews · smilelamp · Nov 1, 18:28 · [Discussion](https://news.ycombinator.com/item?id=50328251)

**Background**: The integration of AI into mathematics research represents a significant paradigm shift, akin to the advent of computer algebra systems. AI tools are becoming powerful aids in mathematical discovery, prompting a re-evaluation of traditional skills and contributions in the field.

<details><summary>References</summary>
<ul>
<li><a href="https://benjaminhan.net/posts/20260422-proof-generation-vs-digestion/index.html">Proof Generation vs Digestion – synesis</a></li>
<li><a href="https://arxiv.org/pdf/2608.16753">Mathematics in the age of AI</a></li>

</ul>
</details>

**Discussion**: Community members largely agree that AI is changing mathematics, with some comparing it to an industrial revolution in the field. There's a consensus that skills like problem selection and understanding AI-generated proofs will become more crucial.

**Tags**: `#AI`, `#mathematics`, `#research`, `#future of work`, `#computer science`

---

<a id="item-3"></a>
## [Lenovo's 'Encrypted' USB Drive Found to Contain Unencrypted SD Card](https://www.reddit.com/r/technology/comments/1xl2pr3/lenovos_encrypted_fingerprint_usb_drive_is_just/) ⭐️ 8.0/10

A Lenovo branded USB drive, marketed as having encrypted fingerprint security, was discovered to simply contain an unencrypted SD card inside a casing. This finding bypasses any intended security features and raises questions about the product's advertised functionality. This incident significantly undermines user trust in Lenovo's hardware security practices and highlights potential misrepresentation of product capabilities. It suggests a failure in Lenovo's quality control and security review processes, impacting consumers who rely on such devices for data protection. The USB drive, identified by the model name 'FU100', was found to have its internal storage replaced with a standard, unencrypted SD card. This means any data stored on it would not have been protected by the advertised fingerprint encryption.

hackernews · entryleveljobsc · Nov 1, 14:34 · [Discussion](https://news.ycombinator.com/item?id=50326099)

**Background**: Encrypted USB drives typically use hardware-based encryption to protect sensitive data, often featuring fingerprint scanners or password protection. SD cards are a common type of flash memory card used in portable electronics for storing data, but they do not inherently provide encryption.

**Discussion**: Community members expressed disbelief and concern, questioning how such a product could pass security reviews and criticizing Lenovo's trustworthiness for hardware security. Some suggested that users should always rely on software-based encryption over hardware promises.

**Tags**: `#cybersecurity`, `#hardware security`, `#vulnerability`, `#Lenovo`

---

<a id="item-4"></a>
## [GDPx Benchmark Evaluates Frontier AI Models Across Key Economic Domains](https://newsletter.semianalysis.com/p/gdpx-measuring-frontier-model-capabilities) ⭐️ 8.0/10

A new benchmark called GDPx has been introduced to measure the capabilities of frontier AI models across 11 economically valuable domains, including science, engineering, finance, and software development. It aims to serve as the world's best benchmark for general agentic capabilities. This benchmark is significant because it addresses the critical need for comprehensive evaluation of advanced AI models in high-ROI sectors, which are expected to drive the first trillion dollars of AI revenue. GDPx will help identify and compare the most capable AI systems for real-world, high-value applications. GDPx covers domains such as RSI, hardware design, cyber, bio, finance, legal, quant trading, chip design, software engineering, materials science, and alignment, with domain-specialist partners involved in its creation. It provides a live leaderboard, per-domain results, and cost-per-task metrics for frontier models.

rss · Semianalysis · Nov 2, 01:51

**Background**: Frontier AI models, also known as foundation models, are large-scale machine learning models trained on vast datasets, enabling them to be applied across a wide range of use cases. Developing these models is extremely resource-intensive, often costing hundreds of millions of dollars. Examples include OpenAI's GPT series and image models like DALL-E.

<details><summary>References</summary>
<ul>
<li><a href="https://newsletter.semianalysis.com/p/gdpx-measuring-frontier-model-capabilities">GDPx: Measuring Frontier Model Capabilities Across the Most ...</a></li>
<li><a href="https://gdpx.semianalysis.com/domains">GDPx is the best benchmark for measuring general agentic ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Frontier_models">Frontier models</a></li>

</ul>
</details>

**Discussion**: The introduction of GDPx has been met with interest, highlighting its potential to provide a more nuanced understanding of AI capabilities beyond general benchmarks. Discussions may focus on the specific domains chosen and the methodology for evaluating agentic behavior.

**Tags**: `#AI`, `#benchmarking`, `#frontier models`, `#evaluation`, `#domains`

---

<a id="item-5"></a>
## [Animated Explainer: How GPT-4o's Tokenizer Processes 'strawberry'](https://www.reddit.com/r/MachineLearning/comments/1xl9sv7/i_animated_what_gpt4os_tokenizer_does_to/) ⭐️ 8.0/10

A new animated video visually demonstrates how GPT-4o's tokenizer, specifically the o200k_base model, breaks down the word 'strawberry' into tokens. It shows that ' strawberry' (with a leading space) is a single token (ID 101830), and explains the Byte Pair Encoding (BPE) process by merging subwords like 'st', 'raw', and 'berry'. Understanding tokenization is crucial for comprehending how Large Language Models (LLMs) process text and can impact costs and performance, especially across different languages. This visual explanation makes a complex NLP concept accessible to a wider audience. The video highlights that leading spaces significantly affect tokenization, with 'strawberry' and ' strawberry' yielding different token sequences. It also notes that GPT-4o's tokenizer is more efficient for some languages, using 5 tokens for a Hindi sentence compared to GPT-4's 21 tokens.

reddit · r/MachineLearning · /u/Rajucg · Nov 1, 18:01

**Background**: Tokenization is the process of breaking down text into smaller units called tokens, which are then processed by language models. Byte Pair Encoding (BPE) is a common tokenization algorithm that merges frequent character sequences to create subword tokens, balancing vocabulary size and the ability to represent novel words. Token IDs are numerical representations of these tokens used by the model.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Byte-pair_encoding">Byte-pair encoding - Wikipedia</a></li>
<li><a href="https://huggingface.co/learn/llm-course/chapter6/5">Byte-Pair Encoding tokenization - Hugging Face</a></li>
<li><a href="https://auth0.com/blog/id-token-access-token-what-is-the-difference/">ID Token and Access Token: What Is the Difference? | Auth0 What Is an ID Token (and How Does It Work)? - Descope Track and investigate identity activities with linkable ... ID token claims reference - Microsoft identity platform Boost payment security with Token ID | Visa NLP: Understanding Token IDs - Stack Overflow Tokenizer - OpenAI API</a></li>

</ul>
</details>

**Discussion**: The community expressed appreciation for the clear, visual explanation of tokenization, finding it helpful for understanding LLM internals. Some users shared their own experiences and observations about tokenization differences across models and languages.

**Tags**: `#LLM`, `#Tokenization`, `#GPT-4o`, `#NLP`, `#Machine Learning`

---

<a id="item-6"></a>
## [LongCat-2.5 Released: A 1.6 Trillion Parameter Native Multimodal Model](https://longcat.ai/blog/longcat-2.5/) ⭐️ 8.0/10

The LongCat team has released LongCat-2.5, a native multimodal model with 1.6 trillion parameters, featuring approximately 48 billion active parameters per token. This new version enhances visual understanding and agentic coding capabilities for long-range agent tasks compared to its predecessor, LongCat-2.0. This release signifies a major advancement in large-scale multimodal AI, particularly for complex agentic tasks that require deep integration of visual and textual information. It could significantly impact the development of more sophisticated AI agents capable of understanding and interacting with the visual world. LongCat-2.5 encodes visual signals into multi-level discrete tokens, enabling unified processing with text for tasks like visual programming. While the model is available for trial on the official website and via API, GitHub and HuggingFace versions are not yet released.

telegram · zaihuapd · Nov 2, 03:08

**Background**: Native multimodal models (NMMs) are designed with the intrinsic integration of different modalities, such as vision and language, within a unified architecture, moving beyond traditional late-fusion approaches. Agentic coding refers to the use of AI agents to assist in software development tasks, aiming to improve productivity but potentially introducing quality risks.

<details><summary>References</summary>
<ul>
<li><a href="https://www.emergentmind.com/topics/native-multimodal-models-nmms">Native Multimodal Models (NMMs) - emergentmind.com</a></li>
<li><a href="https://en.wikipedia.org/wiki/Agentic_coding">Agentic coding</a></li>

</ul>
</details>

**Discussion**: The community is excited about the scale and native multimodal capabilities of LongCat-2.5, particularly its potential for advanced agent tasks. Some users are eagerly awaiting the public release of the model on platforms like GitHub and HuggingFace.

**Tags**: `#AI`, `#Multimodal Models`, `#Large Language Models`, `#Agent Tasks`

---