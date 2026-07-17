---
layout: default
title: "Horizon Summary: 2026-07-17 (EN)"
date: 2026-07-17
lang: en
---

> From 43 items, 9 important content pieces were selected

---

1. [Firefox Browser Compiled to WebAssembly Runs Inside Another Browser](#item-1) ⭐️ 8.0/10
2. [Moonshot AI releases Kimi K3, a 2.8T parameter model, challenging top LLMs.](#item-2) ⭐️ 8.0/10
3. [Thinking Machines Lab Releases Inkling: A 975B Parameter Open-Weights Multimodal Model](#item-3) ⭐️ 8.0/10
4. [Linus Torvalds: Linux is not an anti-AI project](#item-4) ⭐️ 8.0/10
5. [AI Memory Architectures: Optimizing for Facts vs. Inferential Patterns?](#item-5) ⭐️ 8.0/10
6. [QLoRA Default Learning Rate of 2e-4 May Cause Overfitting on Small Datasets](#item-6) ⭐️ 8.0/10
7. [ExTernD: Ternary LLM Quantization Achieves High Accuracy with Low VRAM Increase](#item-7) ⭐️ 8.0/10
8. [Japan Buys NVIDIA Rubin Chips for Sovereign AI in Robotics](#item-8) ⭐️ 8.0/10
9. [TSMC Pledges $100 Billion More for US Factories, Reports Record Profits](#item-9) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [Firefox Browser Compiled to WebAssembly Runs Inside Another Browser](https://simonwillison.net/2026/Jul/16/firefox-in-webassembly/#atom-everything) ⭐️ 8.0/10

Puter has successfully compiled the entire Firefox browser to WebAssembly, allowing it to run within another browser, such as Chrome. This demonstration showcases a complex application operating entirely within a web environment. This technical feat highlights the growing capabilities of WebAssembly for running sophisticated software outside traditional environments, potentially enabling new forms of sandboxing, remote computing, and cross-platform application delivery. The project utilized Firefox/Gecko due to its strong single-process support and leveraged AI models like Claude Opus for compilation, with all network traffic funneled through the Wisp protocol over a WebSocket for security and to overcome browser network limitations.

rss · Simon Willison · Jul 16, 23:34

**Background**: WebAssembly (Wasm) is a portable binary code format designed as a compilation target for programming languages, enabling high-performance applications on the web and in non-web environments. Gecko is the open-source layout engine developed by Mozilla, powering Firefox. The Wisp protocol is designed for proxying multiple network sockets over a single WebSocket connection.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/WebAssembly">WebAssembly</a></li>
<li><a href="https://en.wikipedia.org/wiki/Gecko_(software)">Gecko (software) - Wikipedia</a></li>
<li><a href="https://github.com/MercuryWorkshop/wisp-protocol">GitHub - MercuryWorkshop/wisp-protocol: Wisp is a low-overhead, easy to implement protocol for proxying multiple TCP/UDP sockets over a single websocket. · GitHub</a></li>

</ul>
</details>

**Discussion**: The community expressed significant enthusiasm for the technical achievement, marveling at the complexity of running a full browser within another via WebAssembly. Some discussion also touched upon the potential costs and scalability challenges associated with proxying traffic.

**Tags**: `#WebAssembly`, `#Browser Technology`, `#Software Engineering`, `#Demonstration`

---

<a id="item-2"></a>
## [Moonshot AI releases Kimi K3, a 2.8T parameter model, challenging top LLMs.](https://simonwillison.net/2026/Jul/16/kimi-k3/#atom-everything) ⭐️ 8.0/10

Chinese AI lab Moonshot AI has launched Kimi K3, a 2.8 trillion parameter model described as the first 'open 3T-class model', with self-reported benchmarks showing it competitive with leading models like Claude Opus and GPT-5.5. The release of Kimi K3 signifies a significant advancement in the scale and capability of open-weight AI models, particularly from Chinese labs, potentially intensifying competition and driving innovation in the global LLM landscape. Kimi K3 boasts 2.8 trillion parameters and features Kimi Delta Attention and Attention Residuals, with a promised open-weight release by July 27, 2026; its pricing is set at $3/million input tokens and $15/million output tokens, making it the most expensive model from a Chinese AI lab to date.

rss · Simon Willison · Jul 16, 20:19

**Background**: Moonshot AI is a Beijing-based artificial intelligence company founded in March 2023, aiming to compete with leading American AI labs. Their Kimi series of large language models (LLMs) are known for supporting large context windows, with Kimi K2 previously showing strong performance on coding benchmarks.

<details><summary>References</summary>
<ul>
<li><a href="https://www.kimi.com/blog/kimi-k3">Kimi K3 Tech Blog: Open Frontier Intelligence</a></li>
<li><a href="https://en.wikipedia.org/wiki/Kimi_K3">Kimi K3</a></li>
<li><a href="https://apidog.com/blog/what-is-kimi-k3/">What Is Kimi K3? Moonshot's 2.8T Open Flagship</a></li>

</ul>
</details>

**Discussion**: The community is impressed by the scale of Kimi K3 and its competitive benchmarks, though some note its high price point compared to other open-weight models and question the 'open' nature given the delayed release of weights.

**Tags**: `#AI`, `#LLM`, `#Open Source`, `#Benchmarks`

---

<a id="item-3"></a>
## [Thinking Machines Lab Releases Inkling: A 975B Parameter Open-Weights Multimodal Model](https://simonwillison.net/2026/Jul/16/inkling/#atom-everything) ⭐️ 8.0/10

Thinking Machines Lab has released Inkling, a 975 billion parameter multimodal Mixture-of-Experts transformer model. This model is licensed under Apache-2.0 and was trained on 45 trillion tokens of text, images, audio, and video. The release of Inkling contributes a powerful new open-weights model to the AI ecosystem, fostering competition and providing a strong base for customization and fine-tuning. Its multimodal capabilities and permissive license make it a valuable resource for researchers and developers. Inkling features 975 billion total parameters with 41 billion active parameters, making it an efficient Mixture-of-Experts model. While not positioned as a frontier model, it is intended as a strong base for fine-tuning on Thinking Machines' Tinker platform.

rss · Simon Willison · Jul 16, 15:35

**Background**: An open-weights model is a large language model (LLM) whose parameters are publicly accessible and can be used or modified without restriction. A multimodal model integrates and processes multiple types of data, such as text, audio, images, or video, for a more holistic understanding. Mixture-of-Experts (MoE) is an architecture that uses multiple 'expert' models and a 'gate' mechanism to select the most suitable expert for a given task, allowing for efficient learning of complex data distributions.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Mixture_of_experts">Mixture of experts - Wikipedia</a></li>
<li><a href="https://machinelearningmastery.com/mixture-of-experts-architecture-in-transformer-models/">Mixture of Experts Architecture in Transformer Models - MachineLearningMastery.com</a></li>
<li><a href="https://www.ibm.com/think/topics/multimodal-ai">What is Multimodal AI? | IBM</a></li>

</ul>
</details>

**Discussion**: The community views this release positively, appreciating the addition of a competitive open-weights multimodal model to the US AI landscape. Its Apache-2.0 license is highlighted as a significant benefit for broader adoption and customization.

**Tags**: `#AI`, `#Machine Learning`, `#Open Source`, `#Multimodal Models`, `#LLMs`

---

<a id="item-4"></a>
## [Linus Torvalds: Linux is not an anti-AI project](https://simonwillison.net/2026/Jul/16/linus-torvalds/#atom-everything) ⭐️ 8.0/10

Linus Torvalds, the lead maintainer of Linux, has stated that Linux is not an anti-AI project and views AI as a clearly useful tool. He indicated that developers who disagree with this stance are free to fork the project or leave. This statement from a highly influential figure in open-source software development clarifies the direction for AI integration within the Linux ecosystem. It signals that AI tools are expected to be incorporated, potentially impacting future kernel development and related projects. Torvalds emphasized that the usefulness of AI is no longer in question, stating that anyone who doubts it has likely not used it. He drew a parallel between AI and other tools used in software development, asserting his firm stance as the top-level maintainer.

rss · Simon Willison · Jul 16, 13:26

**Background**: Linux is a free and open-source operating system kernel that forms the basis of many operating systems, including Android and numerous server distributions. Linus Torvalds is the original creator and principal developer of Linux. AI, or Artificial Intelligence, refers to the simulation of human intelligence in machines that are programmed to think like humans and mimic their actions.

**Discussion**: The provided content does not include community discussion, so this field is empty.

**Tags**: `#Linux`, `#AI`, `#Software Development`, `#Open Source`

---

<a id="item-5"></a>
## [AI Memory Architectures: Optimizing for Facts vs. Inferential Patterns?](https://www.reddit.com/r/MachineLearning/comments/1uy6yht/are_current_ai_memory_architectures_optimizing/) ⭐️ 8.0/10

A discussion post questions whether current AI memory architectures are optimized for storing descriptive facts rather than inferring higher-level patterns and reasoning styles from user interactions. This perspective shift could fundamentally alter how AI systems learn and adapt, moving from simple recall to a deeper understanding of user cognition and problem-solving approaches. The proposed alternative involves persistent context evolving into a model of the user's understanding, focusing on recurring explanatory frameworks and reasoning styles, rather than just remembering facts like 'user is interested in economics'.

reddit · r/MachineLearning · /u/Boris_Ljevar · Jul 16, 16:00

**Background**: Current AI memory architectures aim to provide continuity of reasoning by encoding, storing, and retrieving data, often balancing semantic understanding, relationship reasoning, and scalability. This includes short-term memory for current sessions and long-term memory for persistent knowledge, bridging fast computation with lasting understanding.

<details><summary>References</summary>
<ul>
<li><a href="https://redis.io/blog/ai-agent-memory-stateful-systems/">AI agent memory: types, architecture & implementation</a></li>
<li><a href="https://memverge.ai/memory-talk/ai-memory-architecture/">How AI Memory Architecture Bridges Compute And Cognition - MemVerge</a></li>
<li><a href="https://www.cognee.ai/academy/chapter-1/what-is-ai-memory">What is AI Memory? | Cognee Academy</a></li>

</ul>
</details>

**Discussion**: Commenters largely agreed with the premise, suggesting that current systems are indeed too focused on factual recall. Some proposed that inferential pattern recognition could emerge naturally from advanced AI, while others noted the need for new architectures beyond current retrieval and summarization methods.

**Tags**: `#AI Memory`, `#Machine Learning`, `#AI Architecture`, `#Pattern Recognition`

---

<a id="item-6"></a>
## [QLoRA Default Learning Rate of 2e-4 May Cause Overfitting on Small Datasets](https://www.reddit.com/r/MachineLearning/comments/1uy1z8b/the_qlora_2e4_default_is_wrong_under_10k_samples/) ⭐️ 8.0/10

A user on Reddit argues that the default QLoRA learning rate of 2e-4, commonly cited in tutorials and documentation, is suboptimal for datasets under 10,000 samples and often leads to overfitting. They propose that a lower learning rate, such as 1e-4, with more epochs, is more effective for smaller datasets. This observation challenges a widely adopted default hyperparameter in a popular fine-tuning technique, potentially saving researchers and developers significant time and resources wasted on ineffective training runs. It highlights the importance of dataset size in hyperparameter selection for LLM fine-tuning. The user found that with datasets around 7,200 samples, the 2e-4 learning rate caused evaluation loss to stagnate or increase within the first epoch, while reducing the learning rate to 1e-4 and increasing epochs from 3 to 5 significantly improved evaluation metrics. They suggest 2e-4 is suitable for datasets above 30k samples, while datasets between 10k and 30k require actual tuning.

reddit · r/MachineLearning · /u/Pretty-Ad774 · Jul 16, 12:50

**Background**: QLoRA (Quantized Low-Rank Adaptation) is a parameter-efficient fine-tuning technique for large language models (LLMs) that reduces memory requirements by integrating 4-bit quantization with Low-Rank Adaptation (LoRA). Overfitting occurs when a model learns the training data too well, including its noise, and fails to generalize to new, unseen data. The learning rate is a crucial hyperparameter that controls how much the model's weights are updated during training.

<details><summary>References</summary>
<ul>
<li><a href="https://grokipedia.com/page/QLoRA">QLoRA</a></li>
<li><a href="https://en.wikipedia.org/wiki/Overfitting_(machine_learning)">Overfitting (machine learning)</a></li>
<li><a href="https://www.mygreatlearning.com/blog/understanding-learning-rate-in-machine-learning/">Understanding Learning Rate in Machine Learning</a></li>

</ul>
</details>

**Discussion**: The community generally agrees with the user's findings, sharing similar experiences where lower learning rates improved performance on smaller datasets. Some users noted that the original QLoRA paper used a larger dataset, and the 2e-4 default might have been derived from that context, leading to its widespread adoption without sufficient validation for smaller scales.

**Tags**: `#QLoRA`, `#Hyperparameter Tuning`, `#Machine Learning`, `#Fine-tuning`, `#LLMs`

---

<a id="item-7"></a>
## [ExTernD: Ternary LLM Quantization Achieves High Accuracy with Low VRAM Increase](https://www.reddit.com/r/MachineLearning/comments/1uy2zb3/externd_expandedrank_ternary_decomposition/) ⭐️ 8.0/10

ExTernD introduces an expanded-rank ternary decomposition method for Large Language Models (LLMs) that decomposes a weight matrix into two ternary matrices and an inner diagonal scaling matrix, enabling arbitrary rank for improved accuracy. This novel quantization technique addresses limitations of fixed-rank ternary methods, potentially allowing LLMs to achieve near-original accuracy with significantly reduced memory footprint, making them more accessible for deployment. The method allows the inner rank to be arbitrarily large, which directly correlates with accuracy, while only requiring a slight increase in VRAM compared to existing quantization methods.

reddit · r/MachineLearning · /u/LMTLS5 · Jul 16, 13:31

**Background**: LLM quantization is a technique to reduce the memory and computational requirements of large language models by representing their weights and activations with lower precision data types. Ternary quantization, a form of extreme quantization, represents weights using only three values (e.g., -1, 0, 1), offering significant compression but often at the cost of accuracy. VRAM (Video Random-Access Memory) is dedicated memory used by GPUs for graphics and AI computations.

<details><summary>References</summary>
<ul>
<li><a href="https://michielh.medium.com/llm-quantization-techniques-balancing-performance-and-efficiency-bc348eed3816">LLM Quantization Techniques: Balancing Performance and... | Medium</a></li>
<li><a href="https://en.wikipedia.org/wiki/VRAM">VRAM</a></li>
<li><a href="https://symbl.ai/developers/blog/a-guide-to-quantization-in-llms/">A Guide to Quantization in LLMs | Symbl.ai</a></li>

</ul>
</details>

**Discussion**: The community expressed interest in the approach, particularly noting the potential for improved accuracy with only a marginal increase in VRAM, which is a significant advantage over previous ternary quantization methods.

**Tags**: `#LLM`, `#Quantization`, `#AI`, `#Deep Learning`, `#Model Compression`

---

<a id="item-8"></a>
## [Japan Buys NVIDIA Rubin Chips for Sovereign AI in Robotics](https://www.bloomberg.com/news/articles/2026-07-16/japan-to-buy-nvidia-rubin-chips-to-build-sovereign-ai-for-robots) ⭐️ 8.0/10

Japan plans to acquire 27,500 NVIDIA Rubin chips through the newly established company Noetra to build a foundational AI for robots. This initiative is backed by a significant government grant of 387.3 billion yen (approximately $2.4 billion) and involves major corporations like SoftBank and Toyota-backed Preferred Networks. This move positions Japan as a potential 'third option' in AI development, aiming to reduce reliance on foreign technology and secure a substantial share of the global robotics market by 2040. It signifies a strategic national effort to achieve technological sovereignty in a critical emerging field. Noetra aims to release its first AI model by March of next year, with a robot-specific version planned for release within several years. The project's goal is to capture over 30% of the global robot market share by 2040.

telegram · zaihuapd · Jul 16, 10:59

**Background**: Sovereign AI refers to national or regional efforts to gain greater control over AI capabilities and reduce dependence on foreign providers, encompassing infrastructure, data, models, and skills. NVIDIA's Rubin chips are part of their next-generation AI platform, succeeding the Blackwell architecture, designed for accelerating advanced AI models.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Sovereign_AI">Sovereign AI</a></li>

</ul>
</details>

**Discussion**: The community views this as a significant strategic move by Japan to foster domestic AI and robotics capabilities, potentially challenging the dominance of US and Chinese tech giants. There is interest in how Noetra will differentiate itself and the feasibility of achieving such ambitious market share goals.

**Tags**: `#AI`, `#Robotics`, `#Semiconductors`, `#Japan`, `#Sovereignty`

---

<a id="item-9"></a>
## [TSMC Pledges $100 Billion More for US Factories, Reports Record Profits](https://www.reuters.com/world/asia-pacific/tsmcs-second-quarter-profit-seen-hitting-record-ai-boom-2026-07-15/) ⭐️ 8.0/10

TSMC announced an additional $100 billion investment in its Arizona facilities, bringing its total US investment to $265 billion, and reported a record second-quarter net profit of $22 billion, a 77% year-over-year increase. The company also raised its 2026 capital expenditure forecast to between $60 billion and $64 billion. This significant expansion underscores TSMC's commitment to bolstering US semiconductor manufacturing capacity amidst soaring AI demand, potentially impacting global supply chains and geopolitical dynamics. The record profits highlight the company's strong market position and the immense profitability of the AI chip sector. The new investment in Arizona could lead to the construction of up to four additional fabrication plants, expanding the total planned facilities to eight. TSMC anticipates its full-year revenue to grow slightly over 40% in USD.

telegram · zaihuapd · Jul 16, 12:29

**Background**: TSMC, or Taiwan Semiconductor Manufacturing Company, is the world's largest contract chip manufacturer, producing chips for many major technology companies. The company's advanced manufacturing processes are crucial for high-performance computing, including the AI processors driving demand.

<details><summary>References</summary>
<ul>
<li><a href="https://wccftech.com/tsmc-stacks-its-us-pledge-to-265-billion-amidst-ai-chip-demand-to-build-four-new-arizona-plants/">TSMC Stacks its US Pledge to $265 Billion Amidst AI Chip Demand to...</a></li>
<li><a href="https://finance.yahoo.com/markets/stocks/articles/tsmc-q2-profit-jumps-77-053602551.html">TSMC Q2 profit jumps 77% to record, far surpasses expectations</a></li>
<li><a href="https://finance.yahoo.com/markets/article/tsmc-raises-capex-and-revenue-forecast-highlighting-growing-ai-chip-demand-113101950.html">TSMC raises capex and revenue forecast, highlighting growing AI chip demand</a></li>

</ul>
</details>

**Discussion**: The announcement has been met with positive sentiment, with discussions focusing on the strategic importance of TSMC's US investments for supply chain resilience and national security, as well as the continued dominance of AI in driving semiconductor growth.

**Tags**: `#semiconductors`, `#AI`, `#investment`, `#manufacturing`, `#TSMC`

---