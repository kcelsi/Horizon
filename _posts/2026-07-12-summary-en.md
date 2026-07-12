---
layout: default
title: "Horizon Summary: 2026-07-12 (EN)"
date: 2026-07-12
lang: en
---

> From 25 items, 8 important content pieces were selected

---

1. [vLLM v0.25.0: Model Runner V2 Default, PagedAttention Removed, Transformers Backend Accelerated](#item-1) ⭐️ 9.0/10
2. [OpenAI Launches GPT-5.6 Series with Sol, Terra, and Luna Models](#item-2) ⭐️ 9.0/10
3. [Nvidia, CoreWeave, and Nebius: Analyzing GPU Boom's Circular Financing](#item-3) ⭐️ 8.0/10
4. [VultronRetriever Models Achieve Top MTEB Rankings with Edge AI Efficiency](#item-4) ⭐️ 8.0/10
5. [Six U-Boot Bootloader Vulnerabilities Allow Stealthy Firmware Attacks](#item-5) ⭐️ 8.0/10
6. [Zhipu AI Founder Launches 'Touch High Plan' for AGI Research](#item-6) ⭐️ 8.0/10
7. [Shanghai Targets High-Quality Brain Control by 2027 with BCI Advancements](#item-7) ⭐️ 8.0/10
8. [Apple Sues OpenAI for Alleged Trade Secret Theft in Hardware Development](#item-8) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [vLLM v0.25.0: Model Runner V2 Default, PagedAttention Removed, Transformers Backend Accelerated](https://github.com/vllm-project/vllm/releases/tag/v0.25.0) ⭐️ 9.0/10

vLLM has released version 0.25.0, making Model Runner V2 the default for all dense models, removing the legacy PagedAttention implementation, and achieving native vLLM speeds with the Transformers backend. This release significantly enhances LLM inference performance and flexibility by defaulting to the more advanced Model Runner V2 and optimizing the Transformers backend, making vLLM a more powerful and efficient tool for serving large language models. Model Runner V2 now supports EVS, realtime embeddings, and dynamic speculative decoding, while the removal of PagedAttention simplifies the codebase; the Transformers backend now includes FP8 MoE support and has been optimized for speed.

github · khluu · Jul 11, 20:06

**Background**: vLLM is an open-source library designed for fast and efficient inference of large language models (LLMs). PagedAttention was a core technology in vLLM that optimized memory management for attention key-value caches. Model Runner V2 is a newer execution engine within vLLM that aims to further improve performance and support for various model architectures and features.

<details><summary>References</summary>
<ul>
<li><a href="https://docs.vllm.ai/en/latest/design/paged_attention/">Paged Attention - vLLM</a></li>
<li><a href="https://vllm.ai/blog/2023-06-20-vllm">vLLM: Easy, Fast, and Cheap LLM Serving with PagedAttention</a></li>

</ul>
</details>

**Discussion**: The community is likely to view this release positively due to the performance improvements and the consolidation of Model Runner V2 as the default, although the removal of PagedAttention might require users to adapt their configurations if they relied on specific aspects of the legacy implementation.

**Tags**: `#LLM`, `#Inference`, `#Performance`, `#vLLM`

---

<a id="item-2"></a>
## [OpenAI Launches GPT-5.6 Series with Sol, Terra, and Luna Models](https://t.me/zaihuapd/42497) ⭐️ 9.0/10

OpenAI has officially released the GPT-5.6 series, introducing three distinct models: 'Sol' for peak performance, 'Terra' for a balance of performance and cost, and 'Luna' for high-concurrency, low-cost scenarios, with 'Sol' being the default for most uses. This release signifies a major advancement in AI model development, offering specialized capabilities and improved efficiency that could significantly impact fields like coding, knowledge work, design, research, and cybersecurity by enabling more complex tasks with fewer resources. The GPT-5.6 series introduces 'max/ultra inference' for enhanced processing, 'multi-agent collaboration' for coordinated AI tasks, and 'Programmatic Tool Calling' for more efficient tool integration, all aimed at reducing token usage and costs for complex operations.

telegram · zaihuapd · Jul 11, 13:34

**Background**: OpenAI is a leading artificial intelligence research laboratory known for developing advanced AI models. GPT (Generative Pre-trained Transformer) models are a series of large language models that have demonstrated remarkable capabilities in understanding and generating human-like text. The introduction of specialized models like Sol, Terra, and Luna suggests a move towards more tailored AI solutions for different use cases.

<details><summary>References</summary>
<ul>
<li><a href="https://platform.claude.com/docs/en/agents-and-tools/tool-use/programmatic-tool-calling">Programmatic tool calling - Claude Platform Docs</a></li>
<li><a href="https://www.anthropic.com/engineering/advanced-tool-use">Introducing advanced tool use on the Claude Developer Platform \ Anthropic</a></li>
<li><a href="https://arxiv.org/abs/2501.06322">Multi - Agent Collaboration Mechanisms: A Survey of LLMs</a></li>

</ul>
</details>

**Discussion**: The community is largely impressed by the new series, particularly the focus on cost-efficiency and specialized models like Sol and Terra. There is excitement about the potential for improved performance in complex tasks and a keen interest in how 'Programmatic Tool Calling' will streamline workflows.

**Tags**: `#AI`, `#Large Language Models`, `#OpenAI`, `#GPT-5.6`, `#Machine Learning`

---

<a id="item-3"></a>
## [Nvidia, CoreWeave, and Nebius: Analyzing GPU Boom's Circular Financing](https://io-fund.com/ai-stocks/nvidia-coreweave-nebius-circular-financing-gpu-boom) ⭐️ 8.0/10

The article examines the intricate financing structures supporting the current GPU boom, specifically highlighting Nvidia's substantial investment in CoreWeave and questioning the validity of the 'circular financing' model in this context. This analysis is significant as it scrutinizes the financial underpinnings of the AI hardware market, potentially impacting investment strategies and revealing the true economic drivers behind the demand for advanced GPUs. Nvidia invested $2 billion for a 9% stake in CoreWeave, which plans $35 billion in capital expenditures for 2026, with Nvidia's investment representing only a fraction of that year's planned spending.

hackernews · adletbalzhanov · Jul 11, 17:21 · [Discussion](https://news.ycombinator.com/item?id=48873836)

**Background**: Circular financing, in one interpretation, occurs when an investor funds a company, and that company then spends the money on the investor's products or services, creating a closed loop. Vendor finance is a related concept where a vendor lends money for the purchase of their own products, often taking equity. The GPU boom is driven by the immense computational needs of artificial intelligence, leading to unprecedented demand for high-performance graphics processing units (GPUs).

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Circular_financing">Circular financing</a></li>
<li><a href="https://completeaitraining.com/news/ais-money-go-round-circular-financing-fuels-growth-and/">AI's Money-Go-Round: Circular Financing Fuels Growth-and Bubble...</a></li>
<li><a href="https://americas.societegenerale.com/en/news-north-america/news/news/financing-the-rise-of-neoclouds-to-power-the-ai-boom/">Financing the Rise of Neoclouds to Power the AI Boom - Societe Generale North America</a></li>

</ul>
</details>

**Discussion**: Commenters largely dismiss the concept of 'circular financing' in this scenario, arguing Nvidia's investment is a hedge against hyperscalers and not a true circular loop. Others question the long-term profitability and economic viability of these large-scale GPU build-outs, suggesting metrics like ROI per token are more relevant.

**Tags**: `#AI`, `#GPU`, `#Venture Capital`, `#Semiconductors`, `#Financing`

---

<a id="item-4"></a>
## [VultronRetriever Models Achieve Top MTEB Rankings with Edge AI Efficiency](https://www.reddit.com/r/MachineLearning/comments/1utmxq8/vultronretriever_family_of_models_released_on/) ⭐️ 8.0/10

The VultronRetriever family of models, including Prime, Core, and Flash variants, has been released on HuggingFace, with VultronRetrieverPrime-8B achieving the global #1 rank on the MTEB Leaderboard. These models demonstrate significant improvements in efficiency, storage footprint, and offline performance, even running Q&A and document embedding on an iPhone. This release marks a significant advancement in retrieval models, offering state-of-the-art performance with drastically reduced resource requirements. The focus on efficiency and offline capabilities on edge devices makes powerful AI more accessible for real-world applications, particularly in resource-constrained environments. VultronRetrieverPrime-8B offers up to 16x smaller index storage and 12x higher throughput than previous leaders, while VultronRetrieverFlash-0.8B can index up to 60 images per minute offline. The models were trained on meticulously curated datasets with no cross-dataset duplication or evaluation contamination, ensuring robust performance.

reddit · r/MachineLearning · /u/madkimchi · Jul 11, 15:22

**Background**: The MTEB (Massive Text Embedding Benchmark) Leaderboard is a standard benchmark for evaluating the performance of text embedding models across various natural language processing tasks, including retrieval. HuggingFace is a popular platform for sharing and deploying machine learning models. Edge AI refers to running AI algorithms directly on local devices, such as smartphones or IoT devices, rather than relying on cloud servers.

<details><summary>References</summary>
<ul>
<li><a href="https://huggingface.co/spaces/mteb/leaderboard">MTEB Leaderboard - a Hugging Face Space by mteb</a></li>
<li><a href="https://embeddings-benchmark.github.io/mteb/get_started/usage/leaderboard/">Run the Leaderboard - Massive Text Embedding Benchmark</a></li>

</ul>
</details>

**Discussion**: The community expressed excitement about the models' performance and efficiency gains, particularly their offline capabilities on edge devices like iPhones. There is interest in how these models will perform in real-world applications and their potential to reduce computational costs.

**Tags**: `#Machine Learning`, `#NLP`, `#Retrieval Models`, `#Edge AI`, `#HuggingFace`

---

<a id="item-5"></a>
## [Six U-Boot Bootloader Vulnerabilities Allow Stealthy Firmware Attacks](https://www.bleepingcomputer.com/news/security/new-u-boot-flaws-could-enable-stealthy-firmware-attacks/) ⭐️ 8.0/10

Six vulnerabilities have been discovered in U-Boot's FIT signature verification code, with two allowing arbitrary code execution and four causing device crashes. These flaws, dating back to U-Boot 2013.07, affect numerous stable versions and vendor branches. These vulnerabilities are critical because they allow attackers to execute malicious code before the operating system or security software loads, potentially disabling security features or implanting persistent malware. This could lead to widespread compromise of embedded systems, including those with remote update capabilities like BMCs. The vulnerabilities reside within the FIT signature verification process, enabling attackers to bypass authentication and execute unauthorized code during the boot sequence. Patches have been accepted by U-Boot maintainers, but widespread remediation depends on hardware vendors integrating these fixes into firmware updates, leaving older, unsupported devices vulnerable indefinitely.

telegram · zaihuapd · Jul 11, 08:32

**Background**: U-Boot, or Das U-Boot, is a widely used open-source bootloader for embedded systems across various architectures like ARM and RISC-V. It plays a crucial role in initializing hardware and loading the operating system. FIT (Flattened Device Tree) is a format used by U-Boot to describe hardware, and its signature verification is a security mechanism to ensure the integrity of the loaded firmware.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Das_U-Boot">Das U - Boot - Wikipedia</a></li>
<li><a href="https://u-boot.org/">Das U - Boot : The Universal Boot Loader</a></li>

</ul>
</details>

**Discussion**: The discovery highlights the persistent challenges in securing the firmware supply chain for embedded devices. Concerns are raised about the long-term security of older devices that may never receive patches, emphasizing the need for proactive security measures and vendor accountability.

**Tags**: `#firmware security`, `#vulnerability`, `#U-Boot`, `#bootloader`, `#embedded systems`

---

<a id="item-6"></a>
## [Zhipu AI Founder Launches 'Touch High Plan' for AGI Research](https://mp.weixin.qq.com/s/3CQSkf_kBnXiCDgS4L-Cgg) ⭐️ 8.0/10

Zhipu AI founder Tang Jie has announced the 'Touch High Plan,' an initiative dedicated to Artificial General Intelligence (AGI) research, shifting focus away from short-term commercialization. The plan outlines four key areas: long-term tasks, autonomous agent systems, complete self-training, and extreme safety governance. This strategic pivot by Zhipu AI signals a significant commitment to advancing AGI, a field with the potential to revolutionize technology and society. The emphasis on explainable AI and safety governance addresses critical concerns in AI development, potentially influencing the direction of future AI research and deployment. The 'Touch High Plan' includes a substantial investment of billions in resources for mechanical explainability to make black-box models more transparent. Zhipu AI's GLM-5.2 model is noted as approaching the capabilities of frontier models and is appreciated for its open-source nature.

telegram · zaihuapd · Jul 11, 13:59

**Background**: Artificial General Intelligence (AGI) refers to a hypothetical AI that can understand, learn, and apply knowledge across a wide range of tasks at a human level or beyond. Autonomous agents are AI systems capable of performing complex tasks independently with minimal human supervision. Explainable AI (XAI) is a field focused on developing AI methods that allow humans to understand the reasoning behind AI decisions, countering the 'black box' problem.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Artificial_general_intelligence">Artificial general intelligence - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Autonomous_agent">Autonomous agent</a></li>
<li><a href="https://en.wikipedia.org/wiki/Explainable_AI">Explainable AI</a></li>

</ul>
</details>

**Discussion**: The announcement has generated interest within the technical community, particularly due to Zhipu AI's GLM-5.2 model being open-source and approaching frontier capabilities. Discussions likely revolve around the feasibility of achieving AGI, the challenges of extreme safety governance, and the impact of explainable AI.

**Tags**: `#AI`, `#AGI`, `#Explainable AI`, `#Zhipu AI`

---

<a id="item-7"></a>
## [Shanghai Targets High-Quality Brain Control by 2027 with BCI Advancements](https://t.me/zaihuapd/42501) ⭐️ 8.0/10

Shanghai has released an action plan aiming for high-quality brain control by 2027, with semi-invasive brain-computer interface (BCI) products achieving clinical application and breakthroughs in invasive BCI research. This initiative signifies Shanghai's commitment to advancing neurotechnology and could lead to significant improvements in assistive devices for patients with conditions like paralysis and aphasia, potentially impacting the global BCI market. The plan aims to have over five types of invasive and semi-invasive BCI products complete type testing and clinical trials, targeting functional recovery for patients with speech and motor impairments.

telegram · zaihuapd · Jul 11, 15:49

**Background**: Brain-Computer Interfaces (BCIs) connect the brain directly to external devices, bypassing the body's natural pathways. They can be invasive (surgically implanted), non-invasive (external sensors), or semi-invasive (partially penetrating the skull or dura mater), each offering different trade-offs in signal quality and risk.

<details><summary>References</summary>
<ul>
<li><a href="https://www.linkedin.com/pulse/minds-interface-bridging-thought-technology-bci-neuranet-ai-otbae">The Mind's Interface : Bridging Thought and Technology with BCI</a></li>
<li><a href="https://manasikkm.medium.com/it-doesnt-take-a-brainiac-to-learn-about-brain-computer-interfaces-24be96645df8">It Doesn’t Take A Brainiac to Learn About Brain - Computer Interfaces</a></li>
<li><a href="https://www.business-standard.com/technology/tech-news/what-makes-brain-implants-more-than-just-a-sci-fi-fantasy-as-ai-era-unfolds-126051100098_1.html">What makes brain implants more than just a sci-fi... - Business Standard</a></li>

</ul>
</details>

**Tags**: `#Brain-Computer Interface`, `#Neurotechnology`, `#Medical Technology`, `#AI Applications`, `#Shanghai Policy`

---

<a id="item-8"></a>
## [Apple Sues OpenAI for Alleged Trade Secret Theft in Hardware Development](https://t.me/zaihuapd/42502) ⭐️ 8.0/10

Apple filed a lawsuit on July 10th in the U.S. District Court for the Northern District of California against OpenAI, two former employees, and io Products. The lawsuit accuses OpenAI of systematically stealing Apple's trade secrets related to product design, manufacturing processes, and supply chain information to accelerate its consumer hardware research and development. This legal action highlights escalating tensions in the competitive AI and hardware sectors, potentially impacting intellectual property rights and future innovation for both companies. The outcome could set precedents for how trade secrets are protected in the fast-paced tech industry. The lawsuit alleges that former Apple employee Chang Liu accessed internal networks and downloaded numerous hardware files after leaving, while another former employee, Tang Yew Tan, is accused of emailing supplier information to a personal account before his departure. OpenAI's hardware lead allegedly asked candidates to bring Apple components to interviews.

telegram · zaihuapd · Jul 11, 16:29

**Background**: OpenAI is reportedly developing a new family of AI-native consumer hardware devices, potentially in partnership with former Apple design chief Jony Ive. This venture into hardware signifies a strategic expansion beyond its core AI model development. Apple, a long-standing leader in consumer electronics, has a history of stringent protection of its product designs and manufacturing processes.

<details><summary>References</summary>
<ul>
<li><a href="https://www.macrumors.com/2026/07/10/apple-sues-openai/">Apple Sues OpenAI for Stealing Trade Secrets to Build AI Hardware</a></li>
<li><a href="https://abc7chicago.com/post/cupertino-based-apple-files-lawsuit-accusing-chatgpt-maker-openai-stealing-trade-secrets-hardware-development/19482823/">Cupertino-based Apple files lawsuit accusing... - ABC7 Chicago</a></li>
<li><a href="https://www.ghacks.net/2026/07/11/apple-sues-openai-alleging-former-employees-stole-trade-secrets-for-ai-hardware-development/">Apple Sues OpenAI Alleging Former Employees Stole Trade Secrets ...</a></li>

</ul>
</details>

**Discussion**: The community is expressing surprise and concern over the severity of the allegations, with some questioning the extent to which former employees can be restricted from using their knowledge. Others are speculating on the potential impact on OpenAI's hardware projects and the broader implications for tech talent mobility.

**Tags**: `#Legal`, `#Intellectual Property`, `#AI`, `#Hardware`, `#Trade Secrets`

---