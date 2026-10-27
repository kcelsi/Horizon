---
layout: default
title: "Horizon Summary: 2026-10-27 (EN)"
date: 2026-10-27
lang: en
---

> From 43 items, 7 important content pieces were selected

---

1. [OpenAI Claims Exponential Time Hypothesis is False](#item-1) ⭐️ 9.0/10
2. [Anthropic Files S-1, Revealing Major Financial Commitments and IPO Plans](#item-2) ⭐️ 9.0/10
3. [Sebastian Raschka Launches 'From Scratch' LLM Reasoning Model Video Course](#item-3) ⭐️ 8.0/10
4. [Deepity: Optimized C++/CUDA Predictive Coding Library Challenges JAX on MNIST](#item-4) ⭐️ 8.0/10
5. [China Proposes Mandatory National Standard for Intelligent Vehicle Driving Assistance Systems](#item-5) ⭐️ 8.0/10
6. [ByteDance Releases Seedance 2.5 Video Model with 30-Second Generation](#item-6) ⭐️ 8.0/10
7. [Chinese Team Sets Optical Fiber Real-Time Speed Record at 3.2 Pb/s](#item-7) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [OpenAI Claims Exponential Time Hypothesis is False](https://github.com/openai/math/blob/main/preprints/The-Exponential-Time-Hypothesis-is-False-October-25-2026/paper.pdf) ⭐️ 9.0/10

A new paper released by OpenAI claims to have disproven the Exponential Time Hypothesis (ETH), a fundamental assumption in computational complexity theory. The paper, dated October 26, 2026, asserts that certain NP-hard problems, specifically 3-SAT, can be solved in sub-exponential time. If validated, this result would fundamentally challenge our understanding of computational limits, potentially impacting algorithm design and the perceived difficulty of solving complex problems. It could have profound implications across various fields that rely on computational complexity, from cryptography to artificial intelligence. The paper notes that its runtime bounds of the form 2^o(n) do not transfer under general polynomial-time reductions, meaning it does not directly imply that all NP problems admit subexponential time algorithms. OpenAI is seeking academic review of the proof.

hackernews · vok · Oct 26, 21:59 · [Discussion](https://news.ycombinator.com/item?id=50251661)

**Background**: The Exponential Time Hypothesis (ETH) posits that NP-complete problems, such as 3-SAT, cannot be solved in sub-exponential time (2^o(n)). It is a stronger assumption than P ≠ NP and implies that many known algorithms have near-optimal time complexity. Sub-exponential time refers to algorithms whose running time grows faster than any polynomial but slower than any exponential function.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Exponential_time_hypothesis">Exponential time hypothesis</a></li>
<li><a href="https://en.wikipedia.org/wiki/NP_problem">NP problem</a></li>
<li><a href="https://en.wikipedia.org/wiki/Sub-exponential_time">Sub-exponential time</a></li>

</ul>
</details>

**Discussion**: Commenters expressed surprise and noted that the result does not directly imply all NP problems are solvable in subexponential time, as stated in the paper. There is also discussion about potential implications for advanced LLMs and whether this theoretical result has immediate practical applications in areas like SAT solving.

**Tags**: `#computational complexity`, `#algorithms`, `#theoretical computer science`, `#P vs NP`

---

<a id="item-2"></a>
## [Anthropic Files S-1, Revealing Major Financial Commitments and IPO Plans](https://www.sec.gov/Archives/edgar/data/2130357/000162828026067168/anthropicpbc-sx1.htm) ⭐️ 9.0/10

Anthropic PBC has officially filed a registration statement on Form S-1 with the U.S. Securities and Exchange Commission for its proposed initial public offering (IPO) of Class A common stock, intending to list on the Nasdaq Global Select Market under the symbol "ANRO". The filing provides a detailed look into the company's financial health, strategic partnerships, and operational risks. This S-1 filing marks a significant step towards Anthropic's public debut, offering unprecedented insight into the financial underpinnings and strategic direction of a leading AI company. The details revealed will be crucial for investors and competitors alike, impacting the valuation and competitive landscape of the rapidly evolving AI industry. The filing highlights substantial financial commitments, including $114 billion to Google, $110 billion to AWS, $161 billion to Broadcom, and $120 billion to SpaceX, alongside a notable improvement in revenue per compute dollar, reaching $2.08 from $0.40 in Q1 2025. It also acknowledges risks related to open-source models and potential harm from AI misuse.

hackernews · SiNTEx · Oct 26, 13:04 · [Discussion](https://news.ycombinator.com/item?id=50242939)

**Background**: An S-1 filing is a registration statement filed with the U.S. Securities and Exchange Commission (SEC) by companies planning to go public. It provides comprehensive financial and business information to potential investors. Anthropic is a prominent artificial intelligence company known for developing advanced AI models like Claude.

<details><summary>References</summary>
<ul>
<li><a href="https://www.anthropic.com/news/s1-sec">Anthropic files S-1 with the SEC for proposed initial public ...</a></li>
<li><a href="https://www.businessinsider.com/anthropic-s-1-filing-public-finances-compute-deals-2026-10">Anthropic's Public S-1 Sets Stage for Massive IPO Debut ...</a></li>

</ul>
</details>

**Discussion**: Community members are discussing the massive financial commitments Anthropic has secured, with some expressing concern about the potential downside if demand doesn't meet projections. Others highlight AI coding as a key revenue driver and a potential competitive advantage, while also noting the potential risk posed by open-source AI models.

**Tags**: `#AI`, `#IPO`, `#Venture Capital`, `#Cloud Computing`, `#Machine Learning`

---

<a id="item-3"></a>
## [Sebastian Raschka Launches 'From Scratch' LLM Reasoning Model Video Course](https://magazine.sebastianraschka.com/p/building-reasoning-models) ⭐️ 8.0/10

Sebastian Raschka has released a new video course that teaches how to build Large Language Model (LLM) reasoning models from the ground up. The course offers a deep dive into LLM architecture and the intricacies of training these models. This course is significant because it provides a rare, in-depth educational resource for understanding LLM internals, catering to developers and researchers seeking to move beyond using pre-trained models. It addresses a gap in practical, hands-on learning for complex AI systems. The course focuses on building models 'from scratch,' which involves understanding foundational concepts and implementation details rather than just fine-tuning existing models. It aims to demystify the process and highlight practical learning value, even if training a full-scale LLM from scratch is computationally prohibitive for individuals.

hackernews · sgiannopoulos · Oct 26, 15:11 · [Discussion](https://news.ycombinator.com/item?id=50245138)

**Background**: Large Language Models (LLMs) are advanced AI models trained on vast amounts of text data, capable of understanding and generating human-like text. Reasoning models are a type of LLM enhanced with techniques like reinforcement learning and verifiable rewards to improve their ability to solve complex problems requiring multiple steps of thought or logic. Building these models from scratch involves defining their architecture, preparing datasets, and implementing training algorithms.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Reasoning_model">Reasoning model</a></li>
<li><a href="https://www.thoughtworks.com/insights/decoder/r/reasoning-models">All a business exec needs to know about reasoning models .</a></li>

</ul>
</details>

**Discussion**: Community members discuss the practical value and potential misconceptions surrounding 'from scratch' LLM courses, with some highlighting the immense computational resources required for real-world training. Others praise the instructor's ability to explain complex topics intuitively and recommend his previous book on the subject.

**Tags**: `#AI`, `#Machine Learning`, `#LLMs`, `#Deep Learning`, `#Education`

---

<a id="item-4"></a>
## [Deepity: Optimized C++/CUDA Predictive Coding Library Challenges JAX on MNIST](https://www.reddit.com/r/MachineLearning/comments/1xg6sqa/deepity_a_handtuned_ccuda_predictive_coding/) ⭐️ 8.0/10

A new predictive coding library called Deepity has been released, featuring a C++20 core with hand-tuned AVX2/AVX-512 SIMD kernels, OpenBLAS/MKL integration, and a CUDA backend. It demonstrates competitive performance on MNIST benchmarks, outperforming JAX and ngc-learn in training time while achieving higher accuracy. Deepity offers a from-scratch, highly optimized implementation of predictive coding, a biologically inspired alternative to backpropagation. Its competitive performance suggests that specialized, low-level optimizations can yield significant gains, potentially influencing future deep learning framework development and research into alternative learning paradigms. The library uses nanobind for Python bindings and offers several PCN variants, including Direct Kolen-Pollack feedback and a 'kitchen sink' network with various toggles. The CPU benchmark achieved ~675 GFLOPS/s, and the software is currently in alpha (0.1.0a3) with solo maintenance, focusing on CPU performance while CUDA optimizations are ongoing.

reddit · r/MachineLearning · /u/Important-Home4431 · Oct 26, 19:34

**Background**: Predictive coding is a theory in neuroscience and cognitive science suggesting the brain constantly predicts sensory input and updates its internal model based on prediction errors. Unlike backpropagation, which uses a global error signal, predictive coding involves local computations where each layer predicts and corrects its own state. CUDA is a parallel computing platform and API developed by Nvidia for GPU acceleration, while AVX2/AVX-512 are SIMD instruction set extensions for CPUs that allow parallel processing of data.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/CUDA">CUDA</a></li>
<li><a href="https://en.wikipedia.org/wiki/Advanced_Vector_Extensions">Advanced Vector Extensions - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Predictive_coding">Predictive coding</a></li>

</ul>
</details>

**Discussion**: The community expressed strong interest in Deepity's performance claims and its novel approach to predictive coding. Users inquired about specific implementation details, potential applications beyond MNIST, and comparisons to other frameworks, with general sentiment leaning towards optimism about its potential for optimized deep learning.

**Tags**: `#machine learning`, `#deep learning`, `#optimization`, `#C++`, `#CUDA`

---

<a id="item-5"></a>
## [China Proposes Mandatory National Standard for Intelligent Vehicle Driving Assistance Systems](https://t.me/zaihuapd/44711) ⭐️ 8.0/10

China's National Standard Information Public Service Platform has announced a proposal to establish a mandatory national standard for the safety requirements of combined driving assistance systems in intelligent connected vehicles. This standard, proposed by the Ministry of Industry and Information Technology, is being drafted by entities including the China Automotive Technology and Research Center, Dongfeng Motor Group, and Huawei Technologies. This proposed mandatory standard is significant as it aims to enhance the safety and regulate the performance of advanced driver-assistance systems (ADAS) in China's rapidly growing intelligent connected vehicle market. It will provide crucial technical support for industry management, product upgrades, and testing development, potentially impacting all manufacturers and consumers in this sector. The standard is planned for a development cycle of 22 months and intends to standardize the functional performance of combined driving assistance systems to reduce safety accidents. Key stakeholders like Huawei are involved in its drafting, indicating a focus on integrating advanced technological capabilities.

telegram · zaihuapd · Oct 26, 08:24

**Background**: Intelligent connected vehicles (ICVs) integrate advanced sensing, communication, and autonomous technologies. Combined driving assistance systems, often referred to as ADAS, are a suite of technologies designed to help drivers with tasks like adaptive cruise control, lane centering, and parking, thereby enhancing safety and comfort.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Connected_car">Connected car - Wikipedia</a></li>
<li><a href="https://www.nhtsa.gov/vehicle-safety/driver-assistance-technologies">Driver Assistance Technologies - NHTSA</a></li>

</ul>
</details>

**Tags**: `#Automotive`, `#Standards`, `#AI`, `#Safety`, `#Regulation`

---

<a id="item-6"></a>
## [ByteDance Releases Seedance 2.5 Video Model with 30-Second Generation](https://t.me/zaihuapd/44714) ⭐️ 8.0/10

ByteDance officially launched its next-generation video creation model, Seedance 2.5, on July 31st, significantly increasing its single generation length from 15 to 30 seconds. The new version enhances long narrative capabilities and multimodal referencing, supporting up to 30 images, 10 video clips, and 10 audio clips as reference materials. This advancement in video generation length and multimodal input capabilities from a major player like ByteDance signifies progress in AI's ability to create more complex and coherent video content. It could impact creative industries by providing more powerful tools for content creation and potentially raise new discussions around AI-generated media. Seedance 2.5 supports multi-round extensions for generating continuous videos potentially lasting several minutes, with precise control over timing via timestamps. The model is being integrated into ByteDance's platforms like Jiemeng AI and Doubao Pro, with API services coming soon to Volcengine.

telegram · zaihuapd · Oct 26, 10:16

**Background**: Seedance is an AI text-to-video model developed by ByteDance. Multimodal learning in AI involves integrating and processing multiple types of data, such as text, audio, and images, to achieve a more comprehensive understanding and generation capability, mimicking human sensory input.

<details><summary>References</summary>
<ul>
<li><a href="https://seed.bytedance.com/en/seedance2_5">Seedance 2.5 - seed.bytedance.com</a></li>
<li><a href="https://www.seedance.tv/seedance-2-5">Seedance 2.5 AI Video Generator — Up to 30s Video With Audio</a></li>
<li><a href="https://en.wikipedia.org/wiki/Seedance_2.0">Seedance 2.0</a></li>

</ul>
</details>

**Discussion**: The announcement has generated interest in the extended generation length and improved reference capabilities, with users anticipating its integration into creative workflows. Some discussion points revolve around the potential for longer, more coherent AI-generated narratives and the technical challenges of maintaining consistency.

**Tags**: `#AI`, `#Video Generation`, `#Machine Learning`, `#ByteDance`

---

<a id="item-7"></a>
## [Chinese Team Sets Optical Fiber Real-Time Speed Record at 3.2 Pb/s](https://www.tomshardware.com/networking/3-2-pb-s-real-time-optical-fiber-transfer-speed-world-record-claimed-by-chinese-team-speed-fast-enough-to-download-more-than-20-000-4k-movies-in-one-second) ⭐️ 8.0/10

A Chinese research team has achieved a new world record for real-time optical fiber transmission speed, reaching 3.2 petabits per second (Pb/s) using a 24-core fiber. This new record surpasses their previous achievement of 2.5 Pb/s by nearly 30%. This breakthrough significantly pushes the boundaries of data transmission capacity over optical fibers, potentially paving the way for next-generation high-speed internet and advanced communication networks. The increased speed could enable faster data transfer for everything from cloud computing to scientific research. The team utilized a commercial compatible hardware architecture and employed space-division multiplexing (SDM) along with S+C+L band transmission techniques. While laboratory records have reached higher speeds, this achievement is notable for its real-time application and use of commercially compatible hardware.

telegram · zaihuapd · Oct 27, 03:45

**Background**: Space-division multiplexing (SDM) is a technique that increases data capacity by transmitting independent channels through different spatial paths within an optical fiber. The S, C, and L bands refer to specific wavelength ranges within the optical spectrum used for communication, and transmitting across these multiple bands (S+C+L) further expands the total bandwidth and capacity.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Space-division_multiplexing">Space-division multiplexing</a></li>
<li><a href="https://www.emergentmind.com/topics/scl-band-long-haul-transmission">SCL - Band Long-Haul Transmission</a></li>
<li><a href="https://www.fiberlabs.com/glossary/optical-communication-band/">Optical Communication Band - FiberLabs Inc.</a></li>

</ul>
</details>

**Discussion**: The community is impressed by the record-breaking speed, with many highlighting the practical implications for future internet speeds and data-intensive applications. Some discussions also touch upon the challenges of scaling such technology to widespread commercial use and the ongoing advancements in optical communication.

**Tags**: `#networking`, `#optical fiber`, `#data transmission`, `#world record`, `#telecommunications`

---