---
layout: default
title: "Horizon Summary: 2026-09-16 (EN)"
date: 2026-09-16
lang: en
---

> From 33 items, 6 important content pieces were selected

---

1. [Typesafe AI Launches Jev for Fast, Structured AI Inference](#item-1) ⭐️ 8.0/10
2. [Internet Archive's Wayback Machine faces access issues due to AI scraping](#item-2) ⭐️ 8.0/10
3. [Google Launches Gemini 3.8 Live with Enhanced Real-Time Conversational AI](#item-3) ⭐️ 8.0/10
4. [Security firm claims 25-minute admin access to Baseten's GitHub via leaked token](#item-4) ⭐️ 8.0/10
5. [Tiny 44M LLM Trained from Scratch Achieves 19.8MB Size, Runs Fast on CPU](#item-5) ⭐️ 8.0/10
6. [TabPFN-3.5 released, setting new state-of-the-art for tabular foundation models.](#item-6) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [Typesafe AI Launches Jev for Fast, Structured AI Inference](https://typesafe.ai/blog/introducing-system-one-models-and-jev) ⭐️ 8.0/10

Typesafe AI has introduced System One Models and Jev, a new approach to AI inference that prioritizes speed and cost-effectiveness by generating structured outputs instead of general-purpose text. This system aims to enable new applications in areas like classification and data processing. Jev represents a paradigm shift in AI inference, moving away from the broad capabilities of large language models towards specialized, efficient processing for specific tasks. This could significantly lower the cost and increase the speed of AI applications that require structured data extraction or classification. The system is designed for millisecond-level inference and costs approximately $0.042 per million tokens, offering a cost-effective alternative to traditional LLM inference for tasks requiring structured responses like yes/no, multiple-choice, or scoring.

hackernews · albelfio · Sep 15, 19:25 · [Discussion](https://news.ycombinator.com/item?id=49717558)

**Background**: AI inference is the process where a trained AI model uses its learned patterns to make predictions on new data. Structured output learning, or structured prediction, involves machine learning techniques that predict complex, structured objects rather than simple values. This contrasts with general-purpose generation found in many large language models (LLMs).

<details><summary>References</summary>
<ul>
<li><a href="https://grokipedia.com/page/Inference_artificial_intelligence">Inference (artificial intelligence)</a></li>
<li><a href="https://en.wikipedia.org/wiki/Structured_output_learning">Structured output learning</a></li>
<li><a href="https://openai.com/index/introducing-structured-outputs-in-the-api/">Introducing Structured Outputs in the API - OpenAI</a></li>

</ul>
</details>

**Discussion**: Community members expressed excitement about the novelty of Jev, with some suggesting alternative titles that better reflect its focus on typed inference. Discussions also touched upon the potential for misleading speed comparisons and the integration of Jev with concepts like design-by-contract for enhanced functionality.

**Tags**: `#AI`, `#Machine Learning`, `#Inference`, `#Structured Output`, `#LLM`

---

<a id="item-2"></a>
## [Internet Archive's Wayback Machine faces access issues due to AI scraping](https://blog.archive.org/2026/09/15/an-update-on-wayback-machine-access/) ⭐️ 8.0/10

The Internet Archive's Wayback Machine is experiencing high-volume automated traffic, prompting the implementation of access protections to maintain service availability. This surge is suspected to be from AI scrapers attempting to bypass restrictions on accessing original websites. This situation highlights the strain that AI-driven data collection can place on critical internet infrastructure, potentially impacting historical web preservation and access for legitimate users. It underscores a growing conflict between AI development's data needs and the sustainability of open web resources. The automated traffic is causing service degradation, leading some websites to opt out of being archived. Access issues have been noted even when using VPNs, suggesting broad blocking measures are in effect.

hackernews · ChrisArchitect · Sep 15, 17:52 · [Discussion](https://news.ycombinator.com/item?id=49716176)

**Background**: The Wayback Machine, operated by the Internet Archive, is a digital archive of the World Wide Web that allows users to view archived versions of websites. AI scrapers are tools that use artificial intelligence to automatically extract data from websites, often for training AI models or feeding large language models. These AI scrapers are designed to adapt to website changes and anti-bot measures, making them persistent.

<details><summary>References</summary>
<ul>
<li><a href="https://apify.com/store/categories/ai">AI web scrapers · Apify</a></li>
<li><a href="https://scraperdirectory.pages.dev/scrapers/ai/">Harnessing the Power of AI Scrapers : A Guide to Data Collection and...</a></li>

</ul>
</details>

**Discussion**: Community members express strong support for the Internet Archive, viewing it as a vital resource under attack. There's a consensus that AI companies are likely responsible for the traffic, with some users sharing personal positive experiences with the Wayback Machine and others noting broader access difficulties.

**Tags**: `#internet archive`, `#wayback machine`, `#web scraping`, `#ai`, `#infrastructure`

---

<a id="item-3"></a>
## [Google Launches Gemini 3.8 Live with Enhanced Real-Time Conversational AI](https://blog.google/innovation-and-ai/models-and-research/gemini-models/gemini-3-8-live-gemini-3-8-live-extended-thinking/) ⭐️ 8.0/10

Google has released Gemini 3.8 Live and Gemini 3.8 Live Extended Thinking, new speech-to-speech models designed for more natural and fluid voice interactions, supporting complex reasoning and real-time visual context. This release signifies a leap in conversational AI, potentially impacting how users interact with AI assistants and services through voice, especially for niche language support and complex tasks. These models support 97 languages, offer low latency, pleasant voices, and are capable of background tool calling, with Extended Thinking built for high-complexity tasks and multi-step reasoning.

hackernews · leumon · Sep 15, 17:38 · [Discussion](https://news.ycombinator.com/item?id=49715947)

**Background**: Conversational AI integrates speech recognition, language models, and text-to-speech to enable real-time voice interactions. Gemini models are Google's flagship large language models, competing in the rapidly evolving AI landscape.

<details><summary>References</summary>
<ul>
<li><a href="https://blog.google/innovation-and-ai/models-and-research/gemini-models/gemini-3-8-live-gemini-3-8-live-extended-thinking/">Introducing Gemini 3.8 Live and 3.8 Live Extended Thinking</a></li>
<li><a href="https://www.marktechpost.com/2026/09/15/google-releases-gemini-3-8-live-and-3-8-live-extended-thinking-for-production-grade-voice-agents/">Google Releases Gemini 3.8 Live and 3.8 Live Extended Thinking for Production Grade Voice Agents - MarkTechPost</a></li>

</ul>
</details>

**Discussion**: Users are impressed with Gemini 3.8 Live's performance, particularly its proficiency in niche languages like Afrikaans and its ability to handle accents and low latency. Some users are comparing its progress to competitors and anticipating future versions.

**Tags**: `#AI`, `#LLM`, `#Gemini`, `#Google`, `#Natural Language Processing`

---

<a id="item-4"></a>
## [Security firm claims 25-minute admin access to Baseten's GitHub via leaked token](https://www.strix.ai/blog/baseten-harbor-github-pat-takeover) ⭐️ 8.0/10

The security firm Strix AI announced they gained administrative access to Baseten's production GitHub repositories within 25 minutes by exploiting a leaked personal access token found in a Docker build history. This incident highlights a critical vulnerability in AI infrastructure security, demonstrating how easily sensitive production systems can be compromised through leaked credentials, impacting trust and potentially exposing customer data. The leaked token, belonging to 'basetenbot', had admin and push access to Baseten's main product repository, its GitOps repository, and other private repositories, including customer-specific ones.

hackernews · bearsyankees · Sep 15, 18:11 · [Discussion](https://news.ycombinator.com/item?id=49716476)

**Background**: Baseten is an AI inference platform offering cloud pricing for AI model deployment. GitHub is a widely used platform for software development and version control, where access tokens are used for authentication and authorization. Leaked tokens can grant unauthorized access to code and infrastructure.

<details><summary>References</summary>
<ul>
<li><a href="https://grokipedia.com/page/Baseten">Baseten</a></li>
<li><a href="https://dailysecurityreview.com/security-spotlight/github-supply-chain-attack-traced-to-leaked-spotbugs-token/">GitHub Supply Chain Attack Traced to Leaked SpotBugs Token</a></li>

</ul>
</details>

**Discussion**: Community members noted Baseten's prompt response in securing their systems after the disclosure, while also raising questions about the ethics of security testing against vendors without explicit prior negotiation.

**Tags**: `#security`, `#vulnerability`, `#github`, `#disclosure`, `#ai`

---

<a id="item-5"></a>
## [Tiny 44M LLM Trained from Scratch Achieves 19.8MB Size, Runs Fast on CPU](https://www.reddit.com/r/MachineLearning/comments/1wgzpli/i_trained_a_44m_parameter_quantized_llm_from/) ⭐️ 8.0/10

A new 44 million parameter Large Language Model (LLM) named SHADOW-50M has been trained from scratch on 45 billion tokens, resulting in a remarkably small 19.8 MB model size and achieving approximately 1,900 tokens/second on a laptop CPU. This development is significant for enabling powerful AI capabilities on resource-constrained devices, potentially democratizing access to LLMs for offline and edge applications without requiring high-end hardware. The model utilizes ternary {-1,0,+1} weights, a 73,880-token vocabulary with fixed 512-bit fingerprints instead of embeddings, and a compiled kernel that runs at ~500 tok/s in WebAssembly, demonstrating novel approaches to model compression and computation.

reddit · r/MachineLearning · /u/Final-Data-1410 · Sep 15, 12:59

**Background**: Quantization in LLMs refers to reducing the precision of the model's weights and activations, typically from floating-point numbers to lower-bit integers, to decrease model size and computational requirements. Ternary weights are an extreme form of quantization where weights are restricted to only three values: -1, 0, and +1, significantly reducing memory footprint and potentially speeding up computation. WebAssembly (Wasm) is a binary instruction format for a stack-based virtual machine, designed as a portable compilation target for languages, enabling high-performance applications on the web and in non-web environments.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/WebAssembly">WebAssembly</a></li>
<li><a href="https://en.wikipedia.org/wiki/1.58-bit_large_language_model">1.58-bit large language model - Wikipedia</a></li>
<li><a href="https://developers.redhat.com/articles/2024/10/17/we-ran-over-half-million-evaluations-quantized-llms">We ran over half a million evaluations on quantized LLMs—here's what we found | Red Hat Developer</a></li>

</ul>
</details>

**Discussion**: The community expressed strong interest in the model's efficiency and novel techniques, with many users inquiring about its performance on specific tasks, potential applications in embedded systems, and the specifics of its quantization and indexing methods.

**Tags**: `#LLM`, `#Quantization`, `#Edge AI`, `#Model Compression`, `#Machine Learning`

---

<a id="item-6"></a>
## [TabPFN-3.5 released, setting new state-of-the-art for tabular foundation models.](https://www.reddit.com/r/MachineLearning/comments/1wh4xhy/tabpfn35_is_released_as_the_next_sota_tabular/) ⭐️ 8.0/10

Prior Labs has released TabPFN-3.5, a new tabular foundation model that has achieved state-of-the-art performance on both TabArena and BeyondArena benchmarks, excelling on large and high-dimensional datasets. This release signifies a major advancement in tabular data modeling, potentially impacting various industries that rely on tabular data for critical machine learning applications by offering improved accuracy and efficiency. TabPFN-3.5-Fast offers a 6x speed improvement, while TabPFN-3.5-Thinking provides enhanced accuracy at the cost of compute, and TabPFN-3.5-Plus is also available; the model leads BeyondArena by +250 Elo points on text-rich, high-cardinality, and high-dimensional data.

reddit · r/MachineLearning · /u/tuanacelik · Sep 15, 16:18

**Background**: Tabular foundation models are pre-trained models designed to generalize across a wide range of tabular datasets, similar to how large language models work for text. TabArena and BeyondArena are continuously maintained benchmarking systems designed to evaluate the performance of machine learning models on tabular data under various conditions.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2506.16791">[2506.16791] TabArena: A Living Benchmark for Machine Learning on Tabular Data</a></li>
<li><a href="https://www.linkedin.com/posts/probabl_theres-a-new-tabular-ai-benchmark-in-town-activity-7481346525374271488-KtqC">There’s a new tabular AI benchmark in town: BeyondArena Our...</a></li>

</ul>
</details>

**Discussion**: The community expressed excitement about the release, noting its strong performance on challenging benchmarks and discussing the potential implications of faster and more accurate variants for practical applications.

**Tags**: `#machine learning`, `#tabular data`, `#foundation models`, `#AI`, `#deep learning`

---