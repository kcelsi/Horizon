---
layout: default
title: "Horizon Summary: 2026-11-16 (EN)"
date: 2026-11-16
lang: en
---

> From 37 items, 7 important content pieces were selected

---

1. [Universal XSS Vulnerability Found in uBlock Origin's Element Picker](#item-1) ⭐️ 8.0/10
2. [Nvidia Faces Future Challenges from Customers, Competition, and Leadership](#item-2) ⭐️ 8.0/10
3. [Crows Exhibit Faster Decision-Making Than Humans, New Research Suggests](#item-3) ⭐️ 8.0/10
4. [Unbundling Multimodal Vision Encoding: Pretraining Optional, Vision Parameters Crucial](#item-4) ⭐️ 8.0/10
5. [New Tool Achieves 5x Faster cudaMemcpy on NVIDIA B300](#item-5) ⭐️ 8.0/10
6. [Telegram Widgets Vulnerability Allows Remote Code Execution](#item-6) ⭐️ 8.0/10
7. [Alibaba Previews Qwen4-Max LLM with Enhanced Capabilities](#item-7) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [Universal XSS Vulnerability Found in uBlock Origin's Element Picker](https://iter.ca/post/ubo-uxss/) ⭐️ 8.0/10

A universal cross-site scripting (XSS) vulnerability has been identified in the uBlock Origin browser extension, specifically within its website-driven element picker functionality. This vulnerability could allow malicious scripts to be injected into web pages viewed by users. This is significant because uBlock Origin is a widely-used extension for blocking ads and trackers, and a vulnerability within it could impact a large number of users' security and privacy. It highlights the ongoing challenges in securing complex browser extensions. The vulnerability arises from how the element picker's interface is integrated into the website's DOM, allowing website-driven code to potentially interact with and exploit the extension's functionality. Potential solutions involve moving the element creation logic to the browser's chrome instead of the website's DOM.

hackernews · zaik · Nov 16, 02:04 · [Discussion](https://news.ycombinator.com/item?id=50513160)

**Background**: Cross-site scripting (XSS) is a type of security vulnerability where attackers inject malicious scripts into web pages viewed by other users, potentially bypassing security measures like the same-origin policy. An element picker is a tool, often part of browser extensions, that allows users to visually select specific elements on a web page, typically for testing or customization purposes.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/XSS_vulnerability">XSS vulnerability</a></li>
<li><a href="https://community.owasp.org/attacks/xss/">Cross Site Scripting ( XSS ) | OWASP Foundation</a></li>
<li><a href="https://www.liftextension.com/blog/building-element-picker">How to Build a Browser Element Picker That Actually Works ...</a></li>

</ul>
</details>

**Discussion**: Community members expressed appreciation for the detailed analysis and the use of AI in generating the proof of concept. Concerns were raised about extensions needing to inject interfaces into the website's DOM, and suggestions were made to move such functionality to the browser's chrome for better security. Users also shared version information for affected and fixed versions.

**Tags**: `#security`, `#vulnerability`, `#browser-extensions`, `#javascript`, `#ublock-origin`

---

<a id="item-2"></a>
## [Nvidia Faces Future Challenges from Customers, Competition, and Leadership](https://steveblank.com/2026/11/15/whats-next-for-nvidia/) ⭐️ 8.0/10

This discussion speculates on Nvidia's future, highlighting potential threats from major customers developing their own chips and the decreasing relevance of its CUDA platform, while also considering the impact of leadership changes. These potential shifts could significantly impact the AI hardware market, forcing Nvidia to adapt its strategy to maintain its dominant position against evolving customer needs and technological advancements. The analysis draws parallels to historical tech company strategies, such as Apple's product cannibalization, and notes that the stabilization of the AI problem space enables large buyers to create custom silicon with companies like Broadcom.

hackernews · zdw · Nov 15, 23:55 · [Discussion](https://news.ycombinator.com/item?id=50512235)

**Background**: Nvidia's CUDA (Compute Unified Device Architecture) is a proprietary parallel computing platform and API that enables software to leverage Nvidia GPUs for accelerated processing, crucial for AI and high-performance computing. AI hardware refers to specialized components designed to efficiently execute AI computations, often offering performance and energy advantages over general-purpose hardware.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Nvidia_CUDA">Nvidia CUDA</a></li>
<li><a href="https://en.wikipedia.org/wiki/Hardware_for_artificial_intelligence">Hardware for artificial intelligence - Wikipedia</a></li>
<li><a href="https://www.intel.com/content/www/us/en/learn/ai-hardware.html">Artificial Intelligence (AI) Hardware – Intel</a></li>

</ul>
</details>

**Discussion**: Community members express concern that major customers becoming competitors is the biggest threat, potentially leading to a collapse in Nvidia's margins as CUDA becomes less relevant. There's also discussion about the impact of leadership and whether founder departures inherently doom innovation.

**Tags**: `#Nvidia`, `#AI Hardware`, `#Strategy`, `#Competition`, `#Semiconductors`

---

<a id="item-3"></a>
## [Crows Exhibit Faster Decision-Making Than Humans, New Research Suggests](https://www.nytimes.com/2026/11/15/science/birdbrain-crows-birds-research-decision.html) ⭐️ 8.0/10

Recent research indicates that crows can make decisions more rapidly than humans, challenging long-held assumptions about avian intelligence and the evolution of cognitive abilities. This finding is significant as it suggests convergent evolution of intelligence and could lead to a re-evaluation of brain architecture and processing speeds across different species, potentially impacting fields like comparative psychology and artificial intelligence. The research highlights that crows' cognitive processes, particularly in decision-making, may operate on a different, potentially faster, timeline than those observed in humans, despite lacking a mammalian cerebral cortex.

hackernews · gumby · Nov 15, 17:53 · [Discussion](https://news.ycombinator.com/item?id=50509023)

**Background**: Intelligence has evolved independently in various animal groups, including mammals, corvids (like crows), and octopuses. Unlike mammals, birds possess a different neuron design and brain architecture, lacking a layered cerebral cortex, which is considered the highest integration center in the mammalian brain.

**Discussion**: Community members noted that intelligence has evolved multiple times on Earth with different brain architectures, suggesting that birds' potentially faster decision-making could be due to shorter neural pathways in smaller brains or the demands of complex behaviors like flight. The term 'birdbrain' is also discussed as a misnomer given these findings.

**Tags**: `#AI`, `#Cognitive Science`, `#Neuroscience`, `#Animal Intelligence`

---

<a id="item-4"></a>
## [Unbundling Multimodal Vision Encoding: Pretraining Optional, Vision Parameters Crucial](https://www.reddit.com/r/MachineLearning/comments/1xx1k2o/meta_fair_nyu_unbundling_multimodal_vision/) ⭐️ 8.0/10

Researchers from Meta FAIR and NYU systematically unbundled multimodal vision encoding by training over 200 MLLMs from scratch, finding that while encoder pretraining is optional, dedicated vision-only parameters are essential for performance. This research clarifies the design choices for multimodal large language models (MLLMs), impacting how future models are built and potentially reducing computational costs by showing pretraining is not always necessary. The study found that encoders pretrained with various objectives performed similarly to encoders trained from scratch with the LLM at matched compute, and that dedicated vision-only parameters, even when integrated into the LLM's early layers ('in-fusion'), are critical for performance.

reddit · r/MachineLearning · /u/trungh98 · Nov 15, 17:38

**Background**: Multimodal Large Language Models (MLLMs) combine language understanding with other modalities, most commonly vision. A key component is the vision encoder, which processes image data before it's fed into the language model. How this encoder is trained and integrated has been a subject of debate, with different models employing separate pretraining, training from scratch, or even removing the encoder.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2611.17334">[2611.17334] Unbundling Multimodal Vision Encoding - arXiv.org</a></li>
<li><a href="https://huggingface.co/papers/2611.17334">Paper page - Unbundling Multimodal Vision Encoding</a></li>
<li><a href="https://arxiv.org/abs/2506.23639">Unified Multimodal Understanding via Byte-Pair Visual Encoding NYU and Meta FAIR Unbundle MLLM Vision Encoding — CASRAI Multimodal LLMs Explained: Vision, Text & Audio Models (2026) Brain encoding models based on multimodal transformers can ... An fMRI visual neural encoding method with multimodal large ...</a></li>

</ul>
</details>

**Discussion**: The community expressed strong interest, noting the significance of the findings for current MLLM design debates and appreciating the systematic approach to unbundling different components.

**Tags**: `#Multimodal AI`, `#LLMs`, `#Computer Vision`, `#Research`, `#Machine Learning`

---

<a id="item-5"></a>
## [New Tool Achieves 5x Faster cudaMemcpy on NVIDIA B300](https://www.reddit.com/r/MachineLearning/comments/1xx2n25/making_cudamemcpy_5x_faster_on_a_b300_p/) ⭐️ 8.0/10

A new tool has been developed that significantly accelerates pageable memory transfers for `cudaMemcpy` operations, demonstrating a 5x speedup on NVIDIA's B300 hardware. This optimization was achieved using a tuning approach applied to the `cudamemcpy-tuner`. This breakthrough is crucial for machine learning and GPU computing as `cudaMemcpy` is fundamental for data movement between the CPU and GPU. A 5x improvement in transfer speed directly translates to faster training times and more efficient utilization of powerful hardware like the B300. The tool specifically targets pageable transfers, which are typically slower due to the need for an intermediate copy to pinned memory before DMA to the GPU. The reported benchmark shows a jump from 10.2 GB/s to 51.5 GB/s for a 1 GB tensor transfer on the B300.

reddit · r/MachineLearning · /u/makneeee · Nov 15, 18:20

**Background**: NVIDIA GPUs are essential for modern AI and high-performance computing, and efficient data transfer is a key bottleneck. `cudaMemcpy` is the standard CUDA function for copying data between host (CPU) and device (GPU) memory. Pageable memory, while convenient, requires extra steps for GPU transfers compared to pinned memory, which is directly accessible by the GPU's DMA engine.

<details><summary>References</summary>
<ul>
<li><a href="https://developer.nvidia.com/blog/how-optimize-data-transfers-cuda-cc/">How to Optimize Data Transfers in CUDA C/C++ | NVIDIA Technical...</a></li>
<li><a href="https://www.coddykit.com/courses/learn_cuda/why-pageable-memory-is-slow-12273260">Why Pageable Memory Is Slow — CUDA Academy | CoddyKit</a></li>

</ul>
</details>

**Discussion**: The community expressed excitement about the significant speedup, with some users noting the importance of optimizing data transfers for large models and hardware like the B300. There was also interest in the underlying techniques used by the `cudamemcpy-tuner`.

**Tags**: `#CUDA`, `#GPU Computing`, `#Performance Optimization`, `#Machine Learning`

---

<a id="item-6"></a>
## [Telegram Widgets Vulnerability Allows Remote Code Execution](https://t.me/zaihuapd/45139) ⭐️ 8.0/10

A Remote Code Execution (RCE) vulnerability has been discovered in Telegram Widgets, a feature introduced in Bot API 10.4 on November 9, 2026. The flaw stems from an insecure client-side sandbox implementation that allows embedded JavaScript to run with unintended privileges. This vulnerability poses a significant risk to Telegram users, as it could allow malicious actors to execute arbitrary code on a user's device through compromised bots. The widespread use of Telegram makes this a critical security concern for a large user base. The vulnerability specifically targets the way Telegram Widgets handle HTML, CSS, and JavaScript, enabling native code execution within the chat widget engine via flaws in the QuickJS-ng JavaScript engine's sandbox. Researchers have demonstrated RCE by sending specially crafted widget messages.

telegram · zaihuapd · Nov 15, 10:51

**Background**: Telegram Widgets, introduced in November 2026, allow bots to embed interactive interfaces within chat messages using HTML, CSS, and JavaScript. A client-side sandbox is a security mechanism designed to isolate code execution, preventing it from accessing sensitive system resources or performing malicious actions. Flaws in sandbox implementations can lead to 'sandbox escapes,' where attackers can break out of the isolated environment.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/davtur19/tg-widget-rce">GitHub - davtur19/tg- widget - rce · GitHub</a></li>
<li><a href="https://habr.com/ru/articles/1107586/">В новых HTML‑виджетах Telegram обнаружили RCE ‑уязвимость</a></li>
<li><a href="https://github.com/bikini/telejam">GitHub - bikini/telejam: telegram RCE · GitHub</a></li>

</ul>
</details>

**Discussion**: The community is advised to exercise caution with unknown bots and temporarily avoid updating Telegram, indicating a general concern for user safety and a need for immediate protective measures.

**Tags**: `#security`, `#vulnerability`, `#Telegram`, `#RCE`, `#software`

---

<a id="item-7"></a>
## [Alibaba Previews Qwen4-Max LLM with Enhanced Capabilities](https://t.me/zaihuapd/45147) ⭐️ 8.0/10

Alibaba has released a preview version of its Qwen4-Max large language model, which features improved knowledge comprehension, world perception, coding, and agentic abilities. This new model is now accessible through the Alibaba Token Plan, with early adopters receiving significant discounts. The release of Qwen4-Max signifies a notable advancement in Alibaba's AI offerings, potentially impacting various applications from software development to complex agentic tasks. Its integration into existing products and services suggests a push towards practical, real-world deployment of cutting-edge LLM technology. Qwen4-Max is built on a 2.4-trillion-parameter architecture, boasts native vision capabilities, and supports a one-million-token context window, enabling it to handle long-horizon tasks and professional tools more effectively. It also supports web search, tool calling, and is compatible with OpenAI and Anthropic APIs.

telegram · zaihuapd · Nov 16, 02:52

**Background**: Qwen is a family of large language models developed by Alibaba Cloud. The Alibaba Token Plan is a flexible, credit-based system that provides access to various AI models, including Qwen, for text, image, and video generation, as well as agent support. Agentic abilities refer to AI systems that can interpret context, learn from interactions, and autonomously control actions to achieve goals.

<details><summary>References</summary>
<ul>
<li><a href="https://qwen.ai/blog?id=qwen4-max">Qwen4-Max: Your New Teammate Has Arrived</a></li>
<li><a href="https://www.qianwenai.com/models/qwen4-max">Qwen4-Max - 千问AI平台 - qianwenai.com</a></li>
<li><a href="https://www.alibabacloud.com/help/en/model-studio/qwen4-max-preview">qwen4-max-preview (Latest Model) - Alibaba Cloud</a></li>

</ul>
</details>

**Discussion**: Early access through the Alibaba Token Plan is highlighted, with a focus on the significant discounts available for limited-time trials. The integration into products like Qoder and the Qwen App indicates practical adoption and user accessibility.

**Tags**: `#AI`, `#LLM`, `#Qwen`, `#Alibaba`

---