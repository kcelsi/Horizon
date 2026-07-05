---
layout: default
title: "Horizon Summary: 2026-07-05 (EN)"
date: 2026-07-05
lang: en
---

> From 48 items, 9 important content pieces were selected

---

1. [Huawei's 'Tao Law' Proposes Time Scaling to Revolutionize Semiconductors](#item-1) ⭐️ 9.0/10
2. [Codex Performance Degradation Linked to Reasoning-Token Clustering](#item-2) ⭐️ 8.0/10
3. [YouTube AI Comment Suggestions Vulnerability Leaks Private Videos](#item-3) ⭐️ 8.0/10
4. [Potential session/cache leakage between workspace instances or consumer accounts](#item-4) ⭐️ 8.0/10
5. [BaryGraph: Knowledge Graph Embeds Relationships as Documents](#item-5) ⭐️ 8.0/10
6. [Google Research releases TabFM, a zero-shot foundation model for tabular data](#item-6) ⭐️ 8.0/10
7. [llama.cpp DeepSeek V4 Branch Merges Quantized KV Cache Fixes](#item-7) ⭐️ 8.0/10
8. [South Korea to Invest 800 Trillion Won in Semiconductor Cluster, Doubling DRAM Output](#item-8) ⭐️ 8.0/10
9. [F-Droid labels Google's ADV system process as malware](#item-9) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [Huawei's 'Tao Law' Proposes Time Scaling to Revolutionize Semiconductors](https://t.me/zaihuapd/42346) ⭐️ 9.0/10

At the 2026 International Conference on Circuits and Systems, Huawei introduced the 'Tao Law,' a new semiconductor evolution principle that replaces traditional geometric scaling with 'time scaling.' Huawei has already designed and mass-produced 381 chips based on this principle over the past six years and plans to launch new Kirin chips using logic folding technology this autumn. This announcement signifies a potential paradigm shift in semiconductor development, offering a new path beyond the limitations of Moore's Law and geometric scaling. If successful, the Tao Law could lead to more advanced and efficient chips, impacting the entire electronics industry and potentially extending the pace of technological advancement. The Tao Law aims to achieve multi-level optimization across devices, circuits, chips, and systems by reducing the time constant, rather than solely relying on shrinking physical dimensions. Huawei projects that by 2031, chips based on this law could achieve transistor densities equivalent to 1.4nm process nodes.

telegram · zaihuapd · Jul 4, 04:56

**Background**: For decades, the semiconductor industry has relied on geometric scaling, as described by Moore's Law and Dennard scaling, where transistors are shrunk to increase density, performance, and energy efficiency. However, these approaches are facing physical and economic limits, making it increasingly difficult to achieve traditional scaling benefits.

<details><summary>References</summary>
<ul>
<li><a href="https://www.yicaiglobal.com/news/huawei-presents-tau-law-to-replace-geometric-scaling-with-time-scaling-in-semiconductor-industry">Huawei Proposes Tau Scaling Law to Replace Moore’s Law in Chip Industry</a></li>
<li><a href="https://www.globaltimes.cn/page/202605/1361841.shtml">Huawei unveils new semiconductor law, charting fresh path for industry development - Global Times</a></li>
<li><a href="https://carnewschina.com/2026/05/26/huawei-unveils-tau-scaling-law-a-new-semiconductor-roadmap-to-succeed-moores-law/">Huawei unveils Tau Scaling Law: a new semiconductor roadmap to succeed Moore’s Law</a></li>

</ul>
</details>

**Tags**: `#semiconductors`, `#Huawei`, `#Moore's Law`, `#VLSI`, `#materials science`

---

<a id="item-2"></a>
## [Codex Performance Degradation Linked to Reasoning-Token Clustering](https://github.com/openai/codex/issues/30364) ⭐️ 8.0/10

Users are reporting reproducible performance degradation in OpenAI's Codex model, specifically noting that reasoning tasks sometimes result in incorrect outputs when the model appears to 'short circuit' and use a fixed number of tokens (around 516), as opposed to the expected 6000-8000 tokens for correct results. This issue could significantly impact developers relying on Codex for code generation and complex reasoning tasks, potentially leading to widespread errors and a loss of trust in the model's reliability. The degradation is observed when the model uses approximately 516 tokens for reasoning, while successful reasoning appears to require a much larger token count (6000-8000). This suggests a potential issue with adaptive reasoning or how the model handles complex problem-solving steps.

hackernews · maille · Jul 4, 21:51 · [Discussion](https://news.ycombinator.com/item?id=48789428)

**Background**: OpenAI's Codex is a large language model announced in 2021, derived from GPT-3 and fine-tuned on source code to translate natural language prompts into code. It has been a foundational model for many coding assistants and tools. Reasoning-token clustering refers to a phenomenon where output tokens related to reasoning group together at specific, often fixed, intervals.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/OpenAI_Codex_(language_model)">OpenAI Codex (language model) - Wikipedia</a></li>
<li><a href="https://news.ycombinator.com/item?id=48789428">GPT-5.5 Codex reasoning - token clustering may be... | Hacker News</a></li>
<li><a href="https://arxiv.org/pdf/2506.22638">Layer Importance for Mathematical Reasoning is Forged in...</a></li>

</ul>
</details>

**Discussion**: Community members confirm experiencing similar quality drops and express frustration, with some noting it's a recurring issue that hasn't been addressed. There's a sentiment that open-sourcing allows these issues to surface, and some users are considering alternative models like Claude or local models.

**Tags**: `#AI`, `#LLM`, `#OpenAI`, `#Codex`, `#Performance`

---

<a id="item-3"></a>
## [YouTube AI Comment Suggestions Vulnerability Leaks Private Videos](https://javoriuski.com/post/youtube) ⭐️ 8.0/10

A security researcher discovered a vulnerability in YouTube's AI-powered comment suggestions feature that could allow private videos to be accessed. The exploit involves an attacker leaving a malicious comment, which, when processed by the creator through YouTube Studio's AI-suggested prompts, could reveal unintended content. This vulnerability highlights significant security risks associated with AI features in content platforms, potentially impacting user privacy and trust. It raises concerns about how AI-generated suggestions are handled and secured, especially when interacting with sensitive creator data. The exploit relies on prompt injection, where specially crafted comments trick the AI into executing unintended commands when the creator interacts with suggested replies in YouTube Studio. While the researcher detailed the method, some users attempting to replicate it found it did not work, suggesting potential mitigations or specific conditions required.

hackernews · javxfps · Jul 4, 16:45 · [Discussion](https://news.ycombinator.com/item?id=48786781)

**Background**: Prompt injection is a cybersecurity exploit where malicious inputs trick AI models, particularly Large Language Models (LLMs), into unintended behavior. This can happen when the AI cannot distinguish between developer-defined instructions and user-provided input, leading to bypassed safeguards. Indirect prompt injection can occur when adversarial prompts are embedded in external content, like websites, that the AI retrieves and processes.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Prompt_injection">Prompt injection</a></li>

</ul>
</details>

**Discussion**: The community largely applauded the researcher's clear and factual reporting style, contrasting it with typical clickbait. There was significant discussion on whether YouTube's handling of prompt injection as a non-bug is appropriate, with some suggesting it's a nuanced issue related to feature implementation and performance metrics.

**Tags**: `#security`, `#vulnerability`, `#AI`, `#YouTube`, `#prompt injection`

---

<a id="item-4"></a>
## [Potential session/cache leakage between workspace instances or consumer accounts](https://github.com/anthropics/claude-code/issues/74066) ⭐️ 8.0/10

Users are reporting potential session or cache leakage issues across different LLM providers, where responses seem to contain data from other users' interactions.

hackernews · chatmasta · Jul 4, 14:03 · [Discussion](https://news.ycombinator.com/item?id=48785485)

**Tags**: `#LLM`, `#Security`, `#Privacy`, `#AI`

---

<a id="item-5"></a>
## [BaryGraph: Knowledge Graph Embeds Relationships as Documents](https://www.reddit.com/r/MachineLearning/comments/1un3lsf/barygraph_knowledge_graph_where_every/) ⭐️ 8.0/10

BaryGraph introduces a novel knowledge graph architecture where relationships are treated as first-class embedded documents, termed BaryEdges, instead of traditional edges. This approach allows for recursive stacking of BaryEdges into MetaBary triads to uncover deeper structural connections between concepts. This innovation moves beyond standard vector search limitations by embedding relationships, enabling the discovery of cross-domain conceptual bridges that might be missed by proximity in embedding space alone. It offers a more nuanced way to represent and query complex semantic networks. BaryGraph uses a formula for BaryEdge embedding that incorporates connection quality and the contextual embedding of the relationship type, and recursively builds MetaBary triads without additional embedding calls. It is implemented locally using MongoDB Community Edition and nomic-embed-text, processing 6.6 million documents from English Wiktionary.

reddit · r/MachineLearning · /u/adseipsum · Jul 4, 08:24

**Background**: Traditional knowledge graphs represent concepts as nodes and their connections as edges. Vector embeddings represent words or concepts as numerical vectors in a high-dimensional space, where proximity indicates semantic similarity. Standard approaches often treat relationships as implicit properties of connected nodes, potentially losing information about the nature of the connection itself.

<details><summary>References</summary>
<ul>
<li><a href="https://www.reddit.com/r/mongodb/">r/mongodb</a></li>

</ul>
</details>

**Discussion**: The community expressed interest in the novel approach, with key questions focusing on the scalability of embedding relationships as documents and the practical applications for cross-domain bridging. There's a general sentiment that this offers a promising direction beyond current limitations of vector search.

**Tags**: `#knowledge graphs`, `#vector embeddings`, `#natural language processing`, `#machine learning`

---

<a id="item-6"></a>
## [Google Research releases TabFM, a zero-shot foundation model for tabular data](https://www.reddit.com/r/LocalLLaMA/comments/1un5hyi/googletabfm100/) ⭐️ 8.0/10

Google Research has introduced TabFM, a novel foundation model designed for tabular data. This model operates in a zero-shot manner, capable of performing classification and regression tasks without requiring any fine-tuning. TabFM's ability to handle tabular data without fine-tuning could significantly streamline machine learning workflows for structured datasets. This advancement may democratize the use of powerful ML models for a wider range of applications and users. The model supports both numerical and categorical columns within the tabular data and makes predictions in a single forward pass by treating training examples as context. It eliminates the need for hyperparameter searches.

reddit · r/LocalLLaMA · /u/Balance- · Jul 4, 10:20

**Background**: Foundation models are large-scale machine learning models trained on vast datasets, enabling them to be adapted for a wide range of downstream tasks. Zero-shot learning is a machine learning paradigm where a model can perform tasks on categories or instances it has not encountered during training, often by leveraging auxiliary information. Tabular data refers to information organized in rows and columns, similar to a spreadsheet.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Zero-shot_learning">Zero-shot learning</a></li>
<li><a href="https://en.wikipedia.org/wiki/Foundation_model">Foundation model</a></li>
<li><a href="https://en.wikipedia.org/wiki/Tabular_data">Tabular data</a></li>

</ul>
</details>

**Discussion**: Users are inquiring about the model's performance benchmarks compared to existing methods and its potential for handling complex, real-world tabular datasets. There's also interest in understanding its underlying architecture and limitations.

**Tags**: `#tabular data`, `#foundation models`, `#machine learning`, `#Google Research`, `#zero-shot learning`

---

<a id="item-7"></a>
## [llama.cpp DeepSeek V4 Branch Merges Quantized KV Cache Fixes](https://www.reddit.com/r/LocalLLaMA/comments/1une2il/i_merged_fixes_for_quantized_kv_cache_into_my/) ⭐️ 8.0/10

The author has merged fixes for quantized KV cache into their DeepSeek V4 branch of llama.cpp, specifically addressing PRs #25247, #25303, and parts of #25202. This enables models like DeepSeek V4 with a 1 million token context to run on a single RTX PRO 6000 GPU. This advancement significantly enhances the ability to run large language models with extremely long context windows on consumer-grade hardware. It democratizes access to powerful AI capabilities by reducing the memory and computational requirements. The implementation allows for a 1 million context window using q8_0 quantization for the KV cache, demonstrated by running the antirez IQ2XXS model on an RTX PRO 6000. Benchmarks show performance metrics for various context lengths up to 1 million tokens.

reddit · r/LocalLLaMA · /u/fairydreaming · Jul 4, 16:57

**Background**: llama.cpp is a popular open-source library for running large language models (LLMs) efficiently on various hardware, often serving as the backbone for local AI inference tools. Quantized KV cache is a technique that reduces the memory footprint of the key-value cache used in transformer models by employing lower-precision data types, such as FP8 or FP4, instead of higher-precision formats like BF16.

<details><summary>References</summary>
<ul>
<li><a href="https://docs.vllm.ai/en/latest/features/quantization/quantized_kvcache/">Quantized KV Cache - vLLM</a></li>
<li><a href="https://docs.sglang.io/docs/advanced_features/quantized_kv_cache">Quantized KV Cache - SGLang Documentation</a></li>
<li><a href="https://en.wikipedia.org/wiki/Llama.cpp">Llama.cpp</a></li>

</ul>
</details>

**Discussion**: The community expressed excitement about the potential for running larger context models on consumer hardware. Users are actively seeking clarification on specific configurations and sharing their own results, indicating strong interest and validation of the improvements.

**Tags**: `#LLM`, `#Quantization`, `#llama.cpp`, `#Optimization`, `#AI`

---

<a id="item-8"></a>
## [South Korea to Invest 800 Trillion Won in Semiconductor Cluster, Doubling DRAM Output](https://t.me/zaihuapd/42357) ⭐️ 8.0/10

South Korea's Minister of Trade, Industry and Energy, Ahn Duk-geun, announced a national semiconductor cluster plan to build a second production base in the southwest region. This initiative aims to attract 800 trillion won in corporate investment to construct four memory wafer fabrication plants, with a goal to double DRAM production within five years. This substantial government-backed investment signals South Korea's commitment to strengthening its position in the global semiconductor market, particularly in memory chips like DRAM. The planned expansion could significantly impact global supply and pricing, especially given the projected fourfold growth in the memory market over the next five years. The plan includes constructing four new memory wafer fabrication plants in the southwest region, with a total corporate investment target of 800 trillion won (approximately 3.52 trillion RMB). Minister Ahn emphasized the need for South Korea to lead in speed and innovation to maintain its competitive edge in the rapidly growing global memory market.

telegram · zaihuapd · Jul 4, 15:15

**Background**: DRAM (Dynamic Random-Access Memory) is a type of semiconductor memory that stores each bit of data in a separate microscopic capacitor and transistor. It is volatile memory, meaning it loses data when power is removed, and requires periodic refreshing to maintain data integrity. DRAM is widely used as the main memory in computers and graphics cards due to its high capacity and relatively low cost compared to SRAM.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/DRAM">DRAM</a></li>

</ul>
</details>

**Discussion**: The announcement has been met with optimism regarding South Korea's ambition to lead in the semiconductor sector. Some discussions highlight the significant financial commitment and the strategic importance of securing domestic production capacity amidst global supply chain uncertainties.

**Tags**: `#semiconductors`, `#investment`, `#South Korea`, `#DRAM`, `#manufacturing`

---

<a id="item-9"></a>
## [F-Droid labels Google's ADV system process as malware](https://f-droid.org/2026/07/01/adv-malware.html) ⭐️ 8.0/10

F-Droid has officially classified Google's Android Developer Verifier (ADV) as malware, a pre-installed system process with root access that will prevent users from running unapproved software. This process, disguised as 'Android Developer Verifier,' is already pre-installed on approximately 4 billion Android devices and is scheduled for activation in select countries starting September 30th, with a global rollout planned for 2027 and beyond. This development signifies a major conflict between Google's control over the Android ecosystem and user freedom, potentially impacting how users can install and run applications. The widespread opposition from privacy advocates and open-source organizations highlights concerns about centralized control and censorship within the Android platform. ADV possesses root access and cannot be removed, and Google has intentionally not defined 'malware' in its developer terms of service, allowing them to arbitrarily classify and block unwanted software. Despite significant opposition, including a petition signed by hundreds of thousands and public letters from over 70 organizations like the EFF and FSF, Google is proceeding with the rollout.

telegram · zaihuapd · Jul 5, 00:41

**Background**: F-Droid is a well-known open-source app store and repository for Android, similar to the Google Play Store but exclusively hosting free and open-source software (FOSS). Google Play Protect is a suite of security features built into Android that scans apps for malware and harmful behavior. Android Developer Verification (ADV) is a new initiative by Google aimed at verifying app developers and ensuring apps meet certain requirements before they can be run on certified Android devices.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/F-Droid">F-Droid</a></li>
<li><a href="https://developer.android.com/developer-verification/guides">Android developer verification | Android Developers</a></li>

</ul>
</details>

**Discussion**: The community sentiment, as indicated by the news item's high score and mention of widespread opposition, is largely critical of Google's ADV initiative. Concerns focus on the potential for censorship, the lack of user control, and the broad implications of a system process with root access that cannot be removed.

**Tags**: `#Android`, `#Security`, `#Privacy`, `#Malware`, `#Open Source`

---