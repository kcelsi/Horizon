---
layout: default
title: "Horizon Summary: 2026-07-16 (EN)"
date: 2026-07-16
lang: en
---

> From 33 items, 9 important content pieces were selected

---

1. [X Platform to Unconditionally Open-Source Entire Codebase After Security Audit](#item-1) ⭐️ 9.0/10
2. [Thinking Machines Releases Inkling: A New Open-Weights Multimodal AI Model](#item-2) ⭐️ 8.0/10
3. [Gemma 4 26B LLM Runs on Old Xeon CPU Without GPU](#item-3) ⭐️ 8.0/10
4. [xAI Open-Sources Grok Build CLI After Privacy Concerns](#item-4) ⭐️ 8.0/10
5. [Claude's web_fetch tool exploited for data exfiltration](#item-5) ⭐️ 8.0/10
6. [PyTorch model 170x slower on T4 vs A100 GPU, user seeks bottleneck cause](#item-6) ⭐️ 8.0/10
7. [DeepSeek Secures Over $7.4 Billion in Landmark First Funding Round](#item-7) ⭐️ 8.0/10
8. [Telegram Launches Serverless Platform for Bots and Mini Apps](#item-8) ⭐️ 8.0/10
9. [xAI Sues User for Generating Child Abuse Material and Deepfakes](#item-9) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [X Platform to Unconditionally Open-Source Entire Codebase After Security Audit](https://x.com/elonmusk/status/2077361679034118271) ⭐️ 9.0/10

Elon Musk announced that X will unconditionally open-source its entire codebase following a security audit. Additionally, X will permit third-party reviewers to inspect its running systems to verify that the open-source code matches the live version. This move significantly increases transparency for a major social media platform, potentially fostering greater trust and allowing external developers to better understand and contribute to its infrastructure. The open-sourcing is contingent on a security audit, and the platform will allow third-party verification of its live systems to ensure the integrity of the released code.

telegram · zaihuapd · Jul 15, 13:32

**Background**: Open-sourcing involves making source code publicly available, allowing anyone to view, modify, and distribute it. Security audits are crucial for identifying vulnerabilities in software, especially for open-source projects where external scrutiny is vital for maintaining trust and safety.

<details><summary>References</summary>
<ul>
<li><a href="https://www.sentinelone.com/cybersecurity-101/cybersecurity/open-source-security-audit/">Open Source Security Audit: An Easy Guide - SentinelOne</a></li>
<li><a href="https://orca.security/resources/blog/open-source-application-security-tools/">Best 16 Open Source AppSec Tools for 2026 | Orca Security</a></li>
<li><a href="https://www.helpnetsecurity.com/2026/04/27/25-open-source-security-tools/">25 open-source cybersecurity tools that don’t care about your ...</a></li>

</ul>
</details>

**Discussion**: The announcement has generated excitement about increased transparency and potential for innovation from the developer community, though some may express concerns about the practicalities of such a large-scale open-sourcing effort.

**Tags**: `#open source`, `#X platform`, `#Elon Musk`, `#transparency`, `#social media`

---

<a id="item-2"></a>
## [Thinking Machines Releases Inkling: A New Open-Weights Multimodal AI Model](https://thinkingmachines.ai/news/introducing-inkling/) ⭐️ 8.0/10

Thinking Machines has introduced Inkling, a new open-weights multimodal model that notably supports audio processing and is positioned as a customizable base for enterprises. This release makes Inkling potentially the largest open-weight model with audio capabilities available to the public. Inkling's release is significant as it provides the AI community with a powerful, open-weights multimodal foundation that can be fine-tuned for specific enterprise needs, potentially lowering costs and enabling localized deployments. This aligns with the growing trend of open-source AI development and the demand for adaptable models. While not the strongest overall model, Inkling's strengths lie in its multimodal capabilities, efficient processing, and availability on platforms like Tinker for fine-tuning, making it an attractive base for customization. Community discussions highlight its potential to outperform existing models in specific tasks and its compatibility with local deployment tools like llama.cpp.

hackernews · vimarsh6739 · Jul 15, 18:12 · [Discussion](https://news.ycombinator.com/item?id=48924912)

**Background**: An open-weights model is an AI model where the trained parameters, known as weights, are publicly released, allowing anyone to download and use them. Multimodal models are capable of processing and integrating information from multiple data types, such as text, audio, and images, enabling a more holistic understanding of complex data.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Multimodal_model">Multimodal model</a></li>
<li><a href="https://hai.stanford.edu/ai-definitions/what-is-an-open-weight-model">What is an Open-Weight Model? - Stanford HAI</a></li>

</ul>
</details>

**Discussion**: Community members expressed excitement about Inkling being the largest open-weight model supporting audio and its potential for local deployment. There's also a sentiment that Thinking Machines could become a significant player in providing open models, especially for those seeking alternatives to existing options.

**Tags**: `#AI`, `#Open-Weights Models`, `#Multimodal AI`, `#Machine Learning`

---

<a id="item-3"></a>
## [Gemma 4 26B LLM Runs on Old Xeon CPU Without GPU](https://www.neomindlabs.com/2026/06/08/running-gemma-4-26b-at-5-tokens-sec-on-a-13-year-old-xeon-with-no-gpu/) ⭐️ 8.0/10

A user successfully ran Google's Gemma 4 26B language model on a 13-year-old Xeon CPU, achieving an inference speed of 5 tokens per second without any GPU acceleration. This demonstration highlights the potential for running sophisticated AI models on less powerful, older hardware. This achievement is significant as it lowers the barrier to entry for local LLM inference, making advanced AI more accessible and potentially reducing reliance on expensive cloud-based solutions. It sparks crucial discussions about the economics and feasibility of running large models on consumer-grade or legacy hardware. The model in question is Gemma 4 26B, a Mixture-of-Experts (MoE) variant, which is known for its efficiency. The user achieved 5 tokens/sec on a 13-year-old Xeon CPU, though other users reported similar or slightly faster speeds on comparable hardware, indicating variability based on specific configurations and optimizations.

hackernews · neomindryan · Jul 15, 15:34 · [Discussion](https://news.ycombinator.com/item?id=48922434)

**Background**: LLM inference is the process of using a trained large language model to generate output for new inputs, without further training. Gemma 4 is a family of open models developed by Google AI, with the 26B MoE variant being designed for high-throughput reasoning. Running these models typically requires significant computational resources, often relying on powerful GPUs.

<details><summary>References</summary>
<ul>
<li><a href="https://huggingface.co/google/gemma-4-26B-A4B">google/gemma-4-26B-A4B · Hugging Face</a></li>
<li><a href="https://ai.google.dev/gemma/docs/core">Gemma 4 model overview | Google AI for Developers</a></li>
<li><a href="https://www.ibm.com/think/topics/llm-inference">What is LLM inference? - IBM</a></li>

</ul>
</details>

**Discussion**: Community members are discussing the surprising feasibility of running large models on older hardware, with some predicting even more powerful models on consumer hardware soon. There's also a debate about the cost-effectiveness, with some arguing that cloud inference might still be cheaper than local electricity costs for equivalent token generation.

**Tags**: `#LLM`, `#AI`, `#Hardware`, `#Optimization`, `#Gemma`

---

<a id="item-4"></a>
## [xAI Open-Sources Grok Build CLI After Privacy Concerns](https://simonwillison.net/2026/Jul/15/grok-build/#atom-everything) ⭐️ 8.0/10

xAI has open-sourced its Grok Build command-line interface (CLI) tool under the Apache 2.0 license, following community backlash over a reported privacy issue where the tool uploaded entire directories. The company has also disabled the feature and deleted previously uploaded user data. This move aims to rebuild user trust and foster community contributions by making the tool's codebase transparent and allowing for local execution, potentially influencing how other AI development tools handle user data and privacy. The Grok Build codebase is substantial, comprising over 844,000 lines of Rust code, with only a small percentage appearing to be vendored. The repository currently has a single commit, offering limited insight into its development history.

rss · Simon Willison · Jul 15, 23:59

**Background**: A command-line interface (CLI) is a text-based way to interact with software. Google Cloud buckets are fundamental containers for storing data in Google Cloud Storage. The Apache 2.0 license is a permissive open-source license that allows broad usage, modification, and distribution of software.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Command-line_interface">Command-line interface - Wikipedia</a></li>
<li><a href="https://docs.cloud.google.com/storage/docs/buckets">About Cloud Storage buckets | Google Cloud Documentation</a></li>
<li><a href="https://en.wikipedia.org/wiki/Apache_License">Apache License</a></li>

</ul>
</details>

**Discussion**: The community expressed significant concern over the initial directory upload behavior, with reactions ranging from shock to demands for immediate action. The subsequent open-sourcing and data deletion are seen as positive steps towards regaining trust, though some may remain cautious.

**Tags**: `#open source`, `#AI`, `#privacy`, `#developer tools`, `#xAI`

---

<a id="item-5"></a>
## [Claude's web_fetch tool exploited for data exfiltration](https://simonwillison.net/2026/Jul/15/claude-web-fetch-exfiltration/#atom-everything) ⭐️ 8.0/10

Security researcher Ayush Paul discovered a vulnerability in Claude's web_fetch tool that allowed data exfiltration by tricking the AI into navigating a sequence of nested, generated links on a honeypot website. This vulnerability highlights a significant security risk in LLM tools that interact with the web, potentially exposing sensitive user data and requiring developers to implement more robust safeguards against prompt injection and data exfiltration. The exploit leveraged the web_fetch tool's ability to navigate embedded links within fetched pages, bypassing Anthropic's original protection that only allowed fetching exact user-provided or search-retrieved URLs.

rss · Simon Willison · Jul 15, 14:21

**Background**: The 'lethal trifecta' refers to a combination of an AI agent having access to private data, a tool for accessing external content, and a mechanism for exfiltrating data. Claude's web_fetch tool is designed to prevent data exfiltration by restricting URL access, but this exploit found a way around those restrictions.

<details><summary>References</summary>
<ul>
<li><a href="https://simonwillison.net/2025/Jun/16/the-lethal-trifecta/">The lethal trifecta for AI agents: private data, untrusted ...</a></li>
<li><a href="https://www.hiddenlayer.com/research/the-lethal-trifecta-and-how-to-defend-against-it">How the Lethal Trifecta Expose Agentic AI - hiddenlayer.com</a></li>

</ul>
</details>

**Discussion**: The community noted that Anthropic has since patched this vulnerability by removing the ability for web_fetch to navigate to additional links within fetched content, and that the company did not issue a bug bounty as they had already identified the issue internally.

**Tags**: `#AI Security`, `#LLM Vulnerabilities`, `#Data Exfiltration`, `#Claude AI`

---

<a id="item-6"></a>
## [PyTorch model 170x slower on T4 vs A100 GPU, user seeks bottleneck cause](https://www.reddit.com/r/MachineLearning/comments/1ux6a9x/pytorch_model_running_170x_slower_on_t4_vs_a100/) ⭐️ 8.0/10

A user reported a PyTorch model, which processes a 47-frame, 256x256 video at batch size 1, runs approximately 170 times slower on an NVIDIA T4 GPU (85 seconds) compared to an A100 GPU (0.5 seconds). The user has already confirmed the model is on the GPU, ruled out driver issues, and found no performance impact from enabling `torch.backends.cudnn.benchmark = True`. This extreme performance discrepancy highlights potential architectural or hardware utilization issues that could affect many machine learning practitioners, especially those working with complex models or comparing performance across different NVIDIA GPU generations. Understanding the root cause is crucial for optimizing model deployment and resource allocation. The model employs local 4D correlation volumes followed by transformer layers for temporal context, running in pure FP32 precision. The user observed 99% GPU utilization on the T4 during the slow inference, suggesting the bottleneck is not due to underutilization but rather an inherent inefficiency in the computation on that specific hardware.

reddit · r/MachineLearning · /u/Future-Structure-296 · Jul 15, 13:44

**Background**: 4D correlation volumes are a technique used in computer vision and deep learning, often for tasks like optical flow estimation or video understanding, where relationships across space and time are analyzed. Transformer layers, originally developed for natural language processing, are now widely used in vision tasks for their ability to capture long-range dependencies, including temporal context in videos.

**Discussion**: Community members are suggesting potential causes such as memory bandwidth limitations, inefficient kernel implementations for the specific operations on the T4, or issues with how PyTorch or CUDA are interacting with the T4's architecture. Profiling tools like NVIDIA Nsight Systems are recommended to pinpoint the exact bottleneck.

**Tags**: `#PyTorch`, `#GPU Performance`, `#Machine Learning`, `#Optimization`, `#NVIDIA`

---

<a id="item-7"></a>
## [DeepSeek Secures Over $7.4 Billion in Landmark First Funding Round](https://t.me/zaihuapd/42589) ⭐️ 8.0/10

AI company DeepSeek has successfully closed its inaugural funding round, raising over 50 billion RMB (approximately $7.4 billion) and achieving a valuation exceeding $50 billion. The funding round involved a unique structure where investors channeled funds through a limited partnership managed by CEO Liang Wenfeng. This substantial funding signifies major investor confidence in DeepSeek's AI technology and potential, positioning it as a significant player in the competitive AI landscape. The unconventional structure also highlights innovative approaches to maintaining founder control amidst large-scale investment. Investors in this round face a five-year lock-up period and will not have voting rights, with CEO Liang Wenfeng personally investing 20 billion RMB. Tencent and CATL are reportedly considering investments of 10 billion RMB and 5 billion RMB, respectively.

telegram · zaihuapd · Jul 15, 12:56

**Background**: A limited partnership (LP) is a common structure in venture capital, comprising General Partners (GPs) who manage the fund and Limited Partners (LPs) who provide capital. Founder control refers to the degree to which a startup's founders retain decision-making power, often a key negotiation point with investors.

<details><summary>References</summary>
<ul>
<li><a href="https://carta.com/learn/private-funds/structures/">The Anatomy of a Modern Fund Structure: LPs, GPs, & LLCs - Carta</a></li>
<li><a href="https://www.goingvc.com/post/the-anatomy-of-a-venture-capital-firm-understanding-structure-and-operations">The Anatomy of a Venture Capital Firm: Understanding ...</a></li>
<li><a href="https://fundingstack.com/blog/posts/how-venture-capital-funds-are-structured-a-simple-guide-for-emerging-managers">How Venture Capital Funds Are Structured: A Simple Guide for ...</a></li>

</ul>
</details>

**Discussion**: The community has expressed significant interest in DeepSeek's massive funding round and its unique structure. Discussions highlight the founder's substantial personal investment and the implications of investors foregoing voting rights and accepting lock-up periods.

**Tags**: `#AI`, `#Funding`, `#Venture Capital`, `#DeepSeek`

---

<a id="item-8"></a>
## [Telegram Launches Serverless Platform for Bots and Mini Apps](https://core.telegram.org/bots/serverless) ⭐️ 8.0/10

Telegram has officially launched a serverless platform, enabling developers to deploy bot and Mini App backends directly onto Telegram's infrastructure without needing to manage servers, containers, or scaling. This move significantly simplifies bot and Mini App development on Telegram by abstracting away infrastructure concerns, potentially leading to a surge in new applications and features built on the platform. Developers can deploy code by writing JavaScript modules and using the 'npx tgcloud push' command, with code running in an isolated V8 sandbox and including a built-in SQLite database.

telegram · zaihuapd · Jul 15, 16:00

**Background**: Serverless computing allows developers to build and run applications without managing servers, with major cloud providers offering Function-as-a-Service (FaaS) solutions. V8 is a high-performance JavaScript and WebAssembly engine developed by Google, often used in sandboxed environments for security. SQLite is a lightweight, embedded relational database engine that stores data in a single file.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Serverless_computing">Serverless computing - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/SQLite">SQLite</a></li>

</ul>
</details>

**Discussion**: The announcement has been met with excitement from developers looking for simplified deployment options. Key discussion points include the potential for easier development cycles and the implications of using a built-in SQLite database for state management.

**Tags**: `#serverless`, `#telegram`, `#bots`, `#developer tools`, `#cloud`

---

<a id="item-9"></a>
## [xAI Sues User for Generating Child Abuse Material and Deepfakes](https://www.reuters.com/legal/litigation/musks-xai-sues-grok-user-over-sexualized-deepfakes-2026-07-15/) ⭐️ 8.0/10

Elon Musk's AI company xAI has filed a lawsuit against a user named Terry Harwood, alleging he misused the Grok chatbot to create child sexual abuse material and non-consensual adult deepfakes. This marks one of the first instances of an AI firm taking legal action against a user for generating such content. This lawsuit sets a significant legal precedent for AI companies addressing the misuse of their technology for illegal and harmful purposes. It highlights the growing challenges in content moderation and the ethical responsibilities of AI developers in preventing the creation of abusive material. xAI is seeking damages and a permanent injunction against Harwood, who was previously arrested on charges of child exploitation. The lawsuit states Harwood uploaded non-sexual images and requested explicit content, violating the chatbot's terms of service. xAI also reported that it suspended over 52,000 accounts and facilitated numerous arrests in the past year.

telegram · zaihuapd · Jul 16, 01:45

**Background**: Grok is a generative artificial intelligence chatbot developed by xAI, founded by Elon Musk. Deepfakes are synthetic media, such as images or videos, created or altered using AI techniques like deep learning, often to depict people in fabricated scenarios. These technologies raise significant ethical concerns, particularly regarding the creation of harmful content like child sexual abuse material and non-consensual pornography.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Grok_(chatbot)">Grok (chatbot)</a></li>
<li><a href="https://en.wikipedia.org/wiki/Deepfake">Deepfake</a></li>

</ul>
</details>

**Discussion**: The community views this lawsuit as a necessary step for AI companies to take responsibility for their technology's misuse. There is agreement on the severity of generating child abuse material, though some discussions might touch upon the broader implications for AI censorship and user freedom.

**Tags**: `#AI ethics`, `#legal precedent`, `#deepfakes`, `#content moderation`, `#xAI`

---