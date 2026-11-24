---
layout: default
title: "Horizon Summary: 2026-11-24 (EN)"
date: 2026-11-24
lang: en
---

> From 34 items, 10 important content pieces were selected

---

1. [Formal Proof of Riemann Hypothesis Verified in Lean](#item-1) ⭐️ 9.0/10
2. [Anthropic's Claude AI Discovers Proof for VP ≠ VNP Conjecture](#item-2) ⭐️ 9.0/10
3. [Ladybird Browser Reaches Alpha Stage with Impressive Rendering Capabilities](#item-3) ⭐️ 8.0/10
4. [NariQ Quantizes Qwen3.8-27B to 10GB with Near-BF16 Quality](#item-4) ⭐️ 8.0/10
5. [Zhipu AI's GLM-5.4 Introduces Loop Transformer for Enhanced Coding LLMs](#item-5) ⭐️ 8.0/10
6. [Codex2api Project Compromised by Supply Chain Attack](#item-6) ⭐️ 8.0/10
7. [Meta AI Chief Warns of Imminent Superintelligence and Control Risks](#item-7) ⭐️ 8.0/10
8. [Jensen Huang Reinstated as NVIDIA CEO After Board Review](#item-8) ⭐️ 8.0/10
9. [ChatGPT rolls out GPT-6.2 Sol for paid users, enhancing complex requests and web searches.](#item-9) ⭐️ 8.0/10
10. [Musk's SpaceX Leases AI Compute Power, Earning Billions Amidst Own AI Lag](#item-10) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [Formal Proof of Riemann Hypothesis Verified in Lean](https://t.me/zaihuapd/45324) ⭐️ 9.0/10

On November 20, 2026, Levent Alpöge released a formal proof of the Riemann Hypothesis in Lean, comprising approximately 17 million lines of code. The Lean FRO and Mathlib Initiative jointly certified the proposition and proof as correct on November 21, 2026. This marks a significant milestone in the formal verification of complex mathematical theorems, demonstrating the power of proof assistants like Lean for ensuring mathematical rigor. It could pave the way for more complex mathematical conjectures to be formally verified, increasing confidence in their correctness. The verification process involved confirming the proposition's consistency with Mathlib's RiemannHypothesis, successful compilation of the codebase, and validation by multiple independent proof checkers. The proof was developed with assistance from the AI model Claude.

telegram · zaihuapd · Nov 24, 01:29

**Background**: Lean is an open-source proof assistant and functional programming language developed since 2013, used for formal verification of software and mathematical proofs. The Riemann Hypothesis, first posed in 1859, is a conjecture about the distribution of prime numbers, considered one of the most important unsolved problems in mathematics.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Lean_(proof_assistant)">Lean (proof assistant)</a></li>
<li><a href="https://en.wikipedia.org/wiki/Formal_verification">Formal verification - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Riemann_hypothesis">Riemann hypothesis</a></li>

</ul>
</details>

**Discussion**: The community's validation by the Lean FRO and Mathlib Initiative, including multiple independent checkers, lends significant weight to the announcement. This event highlights the growing capability and importance of formal verification in mathematics.

**Tags**: `#formal verification`, `#mathematics`, `#AI`, `#computer science`, `#proof assistant`

---

<a id="item-2"></a>
## [Anthropic's Claude AI Discovers Proof for VP ≠ VNP Conjecture](https://github.com/anthropics/formal-math/blob/main/vp-vnp/README.md) ⭐️ 9.0/10

Anthropic announced on November 24th that an internal Claude model discovered a proof for the VP ≠ VNP conjecture in algebraic complexity theory. The company has released the formal Lean 4 proof and a paper detailing the findings, both reportedly authored by AI. This development signifies a potential breakthrough in AI's capability for advanced mathematical discovery, potentially accelerating research in theoretical computer science. It also highlights the growing role of formal verification tools like Lean 4 in validating complex mathematical arguments. The proof, which focuses on the lower bounds of Hamiltonian circuit polynomials under arithmetic circuits, has passed an audit by three standard axioms and a review by the nanoda kernel, with no 'sorry' declarations in the released code. However, human verification is still pending, and the formal statement's consistency with the claimed proposition needs independent review.

telegram · zaihuapd · Nov 24, 06:02

**Background**: The VP vs. VNP problem is an algebraic analog to the famous P vs. NP problem in computational complexity theory, proposed by Valiant in 1979. VP represents polynomial-time computable functions by arithmetic circuits, while VNP represents functions verifiable in polynomial time. Proving VP ≠ VNP would imply that not all problems verifiable in polynomial time can be computed in polynomial time using arithmetic circuits.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Arithmetic_circuit_complexity">Arithmetic circuit complexity - Wikipedia</a></li>
<li><a href="https://arxiv.org/abs/1605.02815">[1605.02815] Boundaries of VP and VNP - arXiv.org</a></li>

</ul>
</details>

**Discussion**: The community is cautiously optimistic, acknowledging the potential significance of an AI-generated proof while emphasizing the critical need for rigorous human verification. Concerns have been raised about the scope of the proof (arithmetic circuits only) and the AI's potential for generating incorrect but convincing arguments.

**Tags**: `#AI`, `#Theoretical Computer Science`, `#Complexity Theory`, `#Formal Verification`, `#Mathematical Discovery`

---

<a id="item-3"></a>
## [Ladybird Browser Reaches Alpha Stage with Impressive Rendering Capabilities](https://ladybird.org/posts/alpha/) ⭐️ 8.0/10

Ladybird, an open-source web browser developed from scratch, has officially reached its alpha stage. This milestone signifies a functional implementation capable of rendering various websites. The successful alpha release of Ladybird is significant as it demonstrates the viability of building a new, independent browser engine. This offers a potential alternative to existing browser ecosystems and could foster greater web diversity and innovation. The browser has shown impressive rendering accuracy across a wide range of websites, including complex ones like ProxMox with its NoVNC interface, performing comparably to established browsers like Firefox. Some minor issues like jerky scrolling and specific rendering failures (e.g., XSLT stylesheets) have been noted.

hackernews · janvdberg · Nov 23, 16:13 · [Discussion](https://news.ycombinator.com/item?id=50614249)

**Background**: Ladybird is an open-source web browser developed by the Ladybird Browser Initiative, a nonprofit organization. It was initially a component of SerenityOS but has been a standalone project since 2022. Ladybird utilizes its own unique rendering engine and JavaScript interpreter, differentiating it from browsers based on Chromium, Gecko, or WebKit.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Ladybird_browser">Ladybird browser</a></li>

</ul>
</details>

**Discussion**: Community feedback is largely positive, with users expressing amazement at the browser's rendering capabilities and functional implementation from scratch. Some users highlighted minor issues like scrolling performance and suggested future improvements in privacy features, such as non-compliant JavaScript modes and more granular permissions.

**Tags**: `#web browser`, `#rendering engine`, `#software development`, `#open source`

---

<a id="item-4"></a>
## [NariQ Quantizes Qwen3.8-27B to 10GB with Near-BF16 Quality](https://huggingface.co/nari-labs/Qwen3.8-27B-NariQ-GGUF) ⭐️ 8.0/10

Nari Labs has released NariQ, a new quantization method for the Qwen3.8-27B large language model, achieving 3-bit or lower precision that retains near-BF16 quality across various complex tasks. These quantized models are available in GGUF format and are significantly smaller, with the 3-bit version fitting into a 10GB file. This breakthrough makes powerful LLMs like Qwen3.8-27B more accessible by drastically reducing their file size and memory requirements, enabling deployment on a wider range of hardware. The preservation of near-BF16 quality at such low bitrates is crucial for maintaining performance in demanding applications. NariQ utilizes a trellis-coded post-training quantization technique calibrated on agent sessions, demonstrating strong performance on benchmarks like DeepSWE, Terminal-Bench, and AIME, even at 2.5 bits. The project requires a specific llama.cpp fork for execution and shows competitive decode speeds on NVIDIA GPUs, though performance on Apple's M-series chips is slower.

hackernews · toebee · Nov 23, 13:42 · [Discussion](https://news.ycombinator.com/item?id=50611402)

**Background**: Quantization is a technique used to reduce the size and computational cost of AI models by representing their weights with lower precision numbers, such as 3-bit integers instead of 16-bit floating-point numbers (BF16). BF16 (Brain Floating Point) is a 16-bit format designed for machine learning that balances dynamic range with reduced precision, offering a good trade-off between performance and memory usage compared to 32-bit formats. Qwen3.8-27B is a large language model known for its capabilities in coding, professional tasks, and long-horizon agentic applications.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2611.26157">[2611.26157] NariQ: Sub-3-Bit Quantization for Long-Horizon ...</a></li>
<li><a href="https://aiweekly.co/alerts/nari-labs-nariq-quant-compresses-qwen38-27b-to-10gb-while-matching-bf16-on">Nari Labs' NariQ Quant Compresses Qwen3.8-27B to 10GB While ...</a></li>

</ul>
</details>

**Discussion**: Community members expressed skepticism about quantization methods over-optimizing on benchmarks but appreciated NariQ's validation on diverse long-horizon tasks. Concerns were raised about information loss during quantization, performance on Apple Silicon, and compatibility with older hardware like Volta GPUs.

**Tags**: `#LLM`, `#Quantization`, `#AI`, `#Model Compression`

---

<a id="item-5"></a>
## [Zhipu AI's GLM-5.4 Introduces Loop Transformer for Enhanced Coding LLMs](https://z.ai/blog/glm-5.4) ⭐️ 8.0/10

Zhipu AI has released GLM-5.4, a new iteration of their language model, which notably features a novel 'loop transformer' architecture designed to improve generalized coding capabilities. This development is significant as it introduces a new architectural approach to LLMs, potentially leading to more efficient and capable AI models for complex tasks like coding, and highlights Zhipu AI's contributions to open research. The loop transformer architecture reuses a shared block of transformer layers multiple times instead of running a token through a tall stack of unique layers, which optimizes memory bandwidth and inference efficiency.

hackernews · foohis · Nov 23, 10:06 · [Discussion](https://news.ycombinator.com/item?id=50609685)

**Background**: Traditional transformers process tokens through a series of distinct layers. A loop transformer, also known as recurrent depth or looped depth sharing, applies the same transformer block repeatedly, mimicking deeper networks with fewer unique parameters. This approach aims to address the memory bandwidth bottleneck in LLM inference.

<details><summary>References</summary>
<ul>
<li><a href="https://sebastianraschka.com/llm-architecture-gallery/looped-depth-sharing/">Looped Transformer | Sebastian Raschka, PhD</a></li>
<li><a href="https://www.emergentmind.com/topics/looped-transformer-architecture">Looped Transformer Architecture - emergentmind.com</a></li>
<li><a href="https://techstackups.com/articles/loop-architecture-explained/">Loop Architecture Explained: Why Looped Transformers Are ...</a></li>

</ul>
</details>

**Discussion**: Community members appreciate Zhipu AI's transparency in sharing technical details, contrasting it with more closed approaches from Western companies. While some note access challenges and performance nuances like 'marathon thinking' sessions, the loop transformer concept is seen as a promising direction.

**Tags**: `#LLM`, `#AI`, `#Transformer`, `#Coding`, `#Research`

---

<a id="item-6"></a>
## [Codex2api Project Compromised by Supply Chain Attack](https://github.com/WormW/codex2api-incident-2026-11) ⭐️ 8.0/10

The Codex2api project has been compromised via a supply chain attack, where a malicious version (v3.1.11) was pushed by an attacker who gained control of the author's account. This compromised version removes authentication and leaks 16 GitHub Actions secrets across at least 21 repositories. This incident highlights the severe risks of supply chain attacks in software development, potentially exposing sensitive credentials and enabling remote command execution for users who updated to the malicious version. It underscores the need for robust security practices throughout the software development lifecycle. The attacker bypassed the main branch to push a tag, enabling the build of a backdoor version. Version 3.1.11 disables authentication, effectively allowing remote command execution, and exfiltrates 16 Actions secrets.

telegram · zaihuapd · Nov 23, 11:21

**Background**: A supply chain attack targets less secure elements in a supply chain, such as software components, to compromise downstream users. GitHub Actions secrets are sensitive variables stored in GitHub repositories that are used to authenticate with external services or access sensitive information within workflows.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Supply_chain_attack">Supply chain attack</a></li>
<li><a href="https://docs.github.com/en/actions/how-tos/write-workflows/choose-what-workflows-do/use-secrets">Using secrets in GitHub Actions</a></li>

</ul>
</details>

**Discussion**: Users are advised to immediately stop using and revert to version 3.1.9, and to rotate all affected GitHub tokens, SSH keys, and database credentials.

**Tags**: `#security`, `#supply chain attack`, `#vulnerability`, `#software development`

---

<a id="item-7"></a>
## [Meta AI Chief Warns of Imminent Superintelligence and Control Risks](https://thenextweb.com/news/metas-ai-chief-says-superintelligence-is-arriving-and-control-is-at-risk) ⭐️ 8.0/10

Meta's AI Chief, Alexandr Wang, stated that superintelligence is no longer a distant prospect, citing an AI-assisted proof of the Riemann Hypothesis as evidence of AI's rapid advancement. This statement highlights growing concerns within leading AI research labs about the accelerating pace of AI development and the potential loss of human control over increasingly powerful systems. Wang pointed to the AI-assisted Riemann Hypothesis proof, completed with Anthropic's Claude and verified by the Lean and Mathlib communities, as a sign that AI is closing the gap with top human experts, with only specific knowledge, engineering integration, and experimentation remaining as distinctions.

telegram · zaihuapd · Nov 23, 12:49

**Background**: The Riemann Hypothesis is a major unsolved problem in mathematics concerning the distribution of prime numbers. Lean is an open-source proof assistant and functional programming language, while Mathlib is a community-driven library of formalized mathematics for Lean. Anthropic's Claude is a series of large language models known for their focus on AI safety.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Lean_(proof_assistant)">Lean (proof assistant) - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Anthropic_Claude">Anthropic Claude</a></li>
<li><a href="https://en.wikipedia.org/wiki/Riemann_hypothesis">Riemann hypothesis</a></li>

</ul>
</details>

**Discussion**: The community discussion highlights the significance of AI assisting in complex mathematical proofs, with some expressing awe at the rapid progress and others echoing Wang's concerns about the potential risks and the need for urgent safety research.

**Tags**: `#AI Safety`, `#Superintelligence`, `#Artificial Intelligence`, `#Meta AI`

---

<a id="item-8"></a>
## [Jensen Huang Reinstated as NVIDIA CEO After Board Review](https://nvidianews.nvidia.com/news/nvidia-board-reinstates-jensen-huang-as-president-ceo-and-board-director) ⭐️ 8.0/10

NVIDIA's board of directors has unanimously reinstated Jensen Huang as President and CEO, effective immediately, following a review that concluded his return poses no national security risk after consulting senior U.S. government officials. Colette Kress, who served as interim CEO, will continue as CFO. This decision reaffirms Jensen Huang's leadership at a critical juncture for NVIDIA, a key player in the AI hardware market, ensuring continuity and stability amidst potential geopolitical concerns. His continued leadership is vital for the company's strategic direction in the rapidly evolving technology industry. The board's decision followed a review prompted by reports that Huang was a target of foreign intelligence activities, leading to the formation of an independent investigation committee. NVIDIA also established a National Security and Export Controls Committee and is recruiting for a Chief Compliance Officer.

telegram · zaihuapd · Nov 23, 14:02

**Background**: Jensen Huang is the co-founder, president, and CEO of NVIDIA, a leading technology company renowned for its graphics processing units (GPUs), which are crucial for artificial intelligence and gaming. His leadership has been instrumental in NVIDIA's growth and its current dominant position in the AI chip market.

**Discussion**: The community expressed relief and confidence in Jensen Huang's return, acknowledging the thorough review process and the importance of his leadership for NVIDIA's future, particularly in the AI sector.

**Tags**: `#NVIDIA`, `#CEO`, `#Jensen Huang`, `#Leadership`, `#Technology Industry`

---

<a id="item-9"></a>
## [ChatGPT rolls out GPT-6.2 Sol for paid users, enhancing complex requests and web searches.](https://x.com/ChatGPT/status/2124942186425069836) ⭐️ 8.0/10

ChatGPT announced the launch of GPT-6.2 Sol on November 23rd, a new version available to Plus, Pro, Business, and Enterprise users, designed to better handle complex instructions and online information retrieval. This upgrade signifies an advancement in AI's ability to understand and execute intricate user requests, potentially improving productivity and user experience for professionals and power users relying on ChatGPT for detailed tasks and research. GPT-6.2 Sol shows improvements in recognizing photo details, narrowing online options by criteria like price or location, and proactively offering follow-up suggestions, though these capabilities are based on official statements and not yet independently verified.

telegram · zaihuapd · Nov 24, 00:44

**Background**: ChatGPT is a generative AI chatbot developed by OpenAI, known for popularizing conversational AI and accelerating the AI boom. It operates on a freemium model, with paid tiers like ChatGPT Plus offering advanced features. GPT models are large language models (LLMs) that generate text based on user prompts.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/GPT-6.2_Sol">GPT-6.2 Sol</a></li>
<li><a href="https://chatgpt.com/plans/plus/">ChatGPT Plan | Plus</a></li>
<li><a href="https://en.wikipedia.org/wiki/ChatGPT_Plus">ChatGPT Plus</a></li>

</ul>
</details>

**Discussion**: The announcement has generated interest among paid users eager to test the new capabilities, with some expressing optimism about improved complex task handling and web search integration.

**Tags**: `#AI`, `#ChatGPT`, `#LLM`, `#Product Update`

---

<a id="item-10"></a>
## [Musk's SpaceX Leases AI Compute Power, Earning Billions Amidst Own AI Lag](https://www.nytimes.com/2026/11/23/business/elon-musk-ai-anthropic-google.html) ⭐️ 8.0/10

SpaceX, under Elon Musk's direction, has been generating billions of dollars monthly since May by leasing significant computing power from its data centers to AI companies like Anthropic and Google. Musk reportedly acknowledged SpaceX's lag in AI development, leading to this strategic pivot. This move highlights the immense demand and value of AI infrastructure, signaling a potential shift in how AI development is resourced. It also underscores the competitive pressures within the AI industry, where even established players may prioritize lucrative external contracts over internal development. Musk allegedly renamed a departmental chat group to 'Sell compute because we can't compete' and warned employees against GPU waste. The revenue generated is substantial, reportedly reaching billions monthly, indicating a high demand for GPU resources.

telegram · zaihuapd · Nov 24, 02:06

**Background**: GPUs (Graphics Processing Units) are specialized electronic circuits initially designed for digital image processing but are now extensively used for AI processing and model training due to their ability to accelerate linear algebra calculations. SpaceX is known for its aerospace ventures, but this news reveals its significant investment in data centers and computing infrastructure.

<details><summary>References</summary>
<ul>
<li><a href="https://www.nytimes.com/2026/11/23/business/elon-musk-ai-anthropic-google.html">Elon Musk Faces an A.I. Dilemma at SpaceX - The New York Times</a></li>
<li><a href="https://en.wikipedia.org/wiki/GPU">GPU</a></li>

</ul>
</details>

**Discussion**: The community expressed surprise at Musk's candid admission of AI lag and the significant revenue generated from compute leasing. Some users questioned the long-term implications for SpaceX's own AI ambitions, while others noted the profitability and strategic sense of leveraging existing infrastructure.

**Tags**: `#AI`, `#SpaceX`, `#Cloud Computing`, `#Business Strategy`

---