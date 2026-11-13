---
layout: default
title: "Horizon Summary: 2026-11-13 (EN)"
date: 2026-11-13
lang: en
---

> From 44 items, 14 important content pieces were selected

---

1. [Rust 1.100.0 Stabilizes Never Type, Custom Allocators, and Dependency Cooldowns](#item-1) ⭐️ 9.0/10
2. [PostgreSQL Type Confusion Vulnerability Leads to Remote Code Execution](#item-2) ⭐️ 9.0/10
3. [Anthropic Eyes Massive IPO with Ambitious Financial Projections](#item-3) ⭐️ 9.0/10
4. [Moderna & Merck's mRNA Cancer Vaccine Shows Success in Melanoma Trial](#item-4) ⭐️ 9.0/10
5. [NVIDIA CEO Jensen Huang Resigns; CFO Colette Kress Appointed Interim CEO](#item-5) ⭐️ 9.0/10
6. [Nvidia CEO Jensen Huang Reportedly Resigning Amidst Allegations](#item-6) ⭐️ 8.0/10
7. [Microsoft 365 Suffers Widespread Service Degradation Affecting Core Services](#item-7) ⭐️ 8.0/10
8. [Open-Source Project Enables LLMs on Low-Memory, Older Devices](#item-8) ⭐️ 8.0/10
9. [AMD Zen 6 Architecture Features Surprising Core Design Shifts](#item-9) ⭐️ 8.0/10
10. [Google Launches Gemini 4 Hydrogen for Agentic Workflows](#item-10) ⭐️ 8.0/10
11. [Jane Street Reevaluating Software Engineering Interviews Amidst LLM Advancements](#item-11) ⭐️ 8.0/10
12. [UMAP 0.6 Enhances Performance and Quality for Large Datasets](#item-12) ⭐️ 8.0/10
13. [Meta's TRIBE v2 Model Fails to Replicate Brain Topographic Maps, Except for Motion](#item-13) ⭐️ 8.0/10
14. [Eli Lilly's oral weight-loss drug approved in China](#item-14) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [Rust 1.100.0 Stabilizes Never Type, Custom Allocators, and Dependency Cooldowns](https://blog.rust-lang.org/2026/11/12/Rust-1.100.0/) ⭐️ 9.0/10

Rust 1.100.0 has been released, introducing the stabilization of the 'never' type (!), support for custom allocators, and a new 'dependency cooldown' feature in Cargo to mitigate supply chain risks. This release significantly enhances Rust's type system and memory management capabilities, while Cargo's new security feature helps protect against malicious package updates, impacting all Rust developers and the broader software ecosystem. The 'never' type represents computations that never complete, and expressions of type '!' can be coerced into any other type; custom allocators allow for more control over memory allocation; dependency cooldowns delay the use of newly published versions to allow for auditing.

hackernews · mbStavola · Nov 12, 18:39 · [Discussion](https://news.ycombinator.com/item?id=50472038)

**Background**: The 'never' type, denoted by '!', is a special type in Rust representing functions that never return, such as those that panic or exit. Custom allocators allow developers to provide their own memory allocation strategies instead of relying on the system's default. Dependency cooldowns are a security measure in package managers to prevent the immediate adoption of potentially compromised new versions of libraries.

<details><summary>References</summary>
<ul>
<li><a href="https://doc.rust-lang.org/std/primitive.never.html">never - Rust</a></li>
<li><a href="https://cybersecuritynews.com/rust-1-100-introduces-cargo-security/">Rust 1.100 Introduces Cargo Security Cooldowns to Prevent ...</a></li>

</ul>
</details>

**Discussion**: Community members expressed excitement for the stabilized 'never' type and custom allocators. Some users noted other useful stabilized APIs not mentioned in the blog post, while others debated the effectiveness of dependency cooldowns as a security measure, with concerns about potential workarounds.

**Tags**: `#Rust`, `#Programming Languages`, `#Software Engineering`, `#Compiler`

---

<a id="item-2"></a>
## [PostgreSQL Type Confusion Vulnerability Leads to Remote Code Execution](https://mehmetince.net/part-3-6-how-i-ended-up-turning-a-22-year-old-postgresql-type-confusion-primitive-into-rce-cve-2026-6460/) ⭐️ 9.0/10

A 22-year-old type confusion primitive in PostgreSQL has been exploited to achieve Remote Code Execution (RCE), identified as CVE-2026-6460. This vulnerability allows an object creator to execute arbitrary code as the operating system user running the database, primarily through ALTER commands. This discovery is significant as it demonstrates a critical security flaw in a widely-used database system, potentially impacting numerous applications and services. It highlights the persistent risks associated with long-standing codebases and the importance of thorough security audits. The exploit leverages a type confusion in PostgreSQL's handling of its internal 'Datum' type, where a type identifier might not be correctly bound to the data, enabling arbitrary code execution. While primarily triggered by ALTER TABLE commands, other DDL operations like ADD COLUMN followed by ROLLBACK can also be attack vectors.

hackernews · ozirus · Nov 12, 18:22 · [Discussion](https://news.ycombinator.com/item?id=50471761)

**Background**: PostgreSQL is a powerful, open-source object-relational database system known for its reliability and feature set. Remote Code Execution (RCE) is a severe security vulnerability that allows an attacker to execute arbitrary commands on a target system remotely, often leading to full system compromise. Type confusion occurs when a program incorrectly interprets the data type of a variable, potentially leading to security flaws.

<details><summary>References</summary>
<ul>
<li><a href="https://www.postgresql.org/support/security/CVE-2026-6460/">PostgreSQL: CVE-2026-6460: PostgreSQL type confusion after ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Arbitrary_code_execution">Arbitrary code execution - Wikipedia</a></li>
<li><a href="https://grokipedia.com/page/rce_remote_code_execution">RCE - Remote Code Execution</a></li>

</ul>
</details>

**Discussion**: Some community members debated whether this vulnerability should be classified as RCE or privilege escalation, arguing that it requires authenticated access and might be more relevant for multi-tenant environments. Others praised the detailed write-up and the insight into database internals.

**Tags**: `#PostgreSQL`, `#Security`, `#Vulnerability`, `#RCE`, `#Database Internals`

---

<a id="item-3"></a>
## [Anthropic Eyes Massive IPO with Ambitious Financial Projections](https://ipo.anthropic.com/us/) ⭐️ 9.0/10

Anthropic's potential IPO filing indicates ambitious financial projections, including a target IPO price range of $70–$78 per share, a gross deal size of $85.3 billion (including a $26 billion private placement), and an implied market cap of approximately $968 billion. The company also reported significant compute commitments totaling $900.9 billion through 2045 and Q3'26 revenue projections of $17.0 billion. This potential IPO signifies a major milestone for Anthropic and the AI industry, reflecting immense investor confidence in the company's growth trajectory and the broader generative AI market. The valuation and financial commitments highlight the capital-intensive nature of developing cutting-edge AI models and the competitive landscape for AI dominance. Key details from the filing include a projected Q3'26 revenue of $17.0 billion with a run-rate revenue of approximately $81 billion as of October 2026, alongside 11,900+ customers spending over $100K annually. The company also has substantial compute commitments of $900.9 billion through 2045.

hackernews · josephljohnston · Nov 12, 11:46 · [Discussion](https://news.ycombinator.com/item?id=50465829)

**Background**: Anthropic is an AI safety and research company founded by former OpenAI members, known for its Claude family of large language models (LLMs). LLMs are AI models trained on vast amounts of text data to understand and generate human-like language, powering applications like chatbots and content generation tools. The company is committed to developing artificial general intelligence (AGI) and superintelligence responsibly.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Anthropic">Anthropic</a></li>
<li><a href="https://grokipedia.com/page/Anthropic">Anthropic</a></li>

</ul>
</details>

**Discussion**: Community discussion highlights concerns about the high valuation and the sustainability of such aggressive growth projections, especially with the rise of powerful local models and potential commoditization of LLM services. Some users question the timing of the IPO and the need for immediate capital versus organic growth.

**Tags**: `#AI`, `#IPO`, `#Venture Capital`, `#LLM`, `#Technology`

---

<a id="item-4"></a>
## [Moderna & Merck's mRNA Cancer Vaccine Shows Success in Melanoma Trial](https://t.me/zaihuapd/45084) ⭐️ 9.0/10

Moderna and Merck announced on August 19, 2026, that their personalized mRNA cancer vaccine combined with Keytruda met primary and key secondary endpoints in a Phase 3 trial for post-operative melanoma patients, significantly reducing the risk of recurrence and distant metastasis. This successful Phase 3 trial validates the personalized mRNA cancer vaccine approach for melanoma, potentially offering a new, more effective treatment option for patients and marking a significant advancement in cancer immunotherapy. While specific improvement figures were not disclosed, the trial met its primary endpoint, and the companies will continue to evaluate overall survival; Moderna's stock surged over 150% following the announcement.

telegram · zaihuapd · Nov 12, 07:26

**Background**: Personalized mRNA cancer vaccines are a form of precision immunotherapy that uses synthetic mRNA molecules tailored to encode neoantigens unique to a patient's tumor, aiming to elicit a potent, tumor-specific immune response. Keytruda (pembrolizumab) is a humanized antibody that blocks the PD-1 receptor on lymphocytes, preventing it from interacting with PD-L1 and PD-L2, thereby restoring the immune system's ability to attack cancer cells.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Personalized_mRNA_cancer_vaccine_therapy">Personalized mRNA cancer vaccine therapy</a></li>
<li><a href="https://www.keytrudahcp.com/resources/mechanism-of-action/">Mechanism of Action for KEYTRUDA® (pembrolizumab) and ...</a></li>
<li><a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC10656145/">Patterns of Recurrence of Cutaneous Melanoma: A Literature ...</a></li>

</ul>
</details>

**Discussion**: The announcement has generated significant excitement, with many in the oncology and biotech communities viewing this as a major validation for personalized mRNA cancer therapies and a promising step forward in the fight against melanoma.

**Tags**: `#mRNA vaccine`, `#cancer immunotherapy`, `#melanoma`, `#clinical trial`, `#Moderna`, `#Merck`

---

<a id="item-5"></a>
## [NVIDIA CEO Jensen Huang Resigns; CFO Colette Kress Appointed Interim CEO](https://nvidianews.nvidia.com/news/nvidia-announces-ceo-transition) ⭐️ 9.0/10

NVIDIA announced that Jensen Huang has resigned from his positions as President, CEO, and board member, effective immediately. Colette Kress, currently Executive Vice President and CFO, has been appointed interim CEO while the board initiates a search for a permanent successor. This leadership change at NVIDIA, a dominant player in AI and graphics processing units (GPUs), could significantly impact the semiconductor industry and the trajectory of AI development. Investors and industry observers will be closely watching the transition and the company's future strategic direction. Harvey C. Jones has been appointed as the first Chairman of the Board. NVIDIA has stated that company operations, customer commitments, and product roadmaps will not be interrupted, and the Q3 earnings report will be released as scheduled on November 17th.

telegram · zaihuapd · Nov 12, 13:52

**Background**: NVIDIA is a leading technology company renowned for its graphics processing units (GPUs), which are crucial for gaming, professional visualization, data centers, and artificial intelligence. Jensen Huang co-founded NVIDIA in 1993 and has served as its CEO since then, playing a pivotal role in the company's growth and its dominance in the AI hardware market.

**Discussion**: The news has generated surprise within the tech community, with some users expressing concern about the suddenness of the announcement. There was also a notable, albeit likely speculative, comment from Donald Trump suggesting Apple CEO Tim Cook should take over as NVIDIA's CEO.

**Tags**: `#NVIDIA`, `#CEO Transition`, `#Leadership Change`, `#Semiconductors`, `#AI`

---

<a id="item-6"></a>
## [Nvidia CEO Jensen Huang Reportedly Resigning Amidst Allegations](https://apnews.com/article/nvidia-megaspeed-china-singapore-huang-5403f152a601cf82ce939f1d24fffa0f) ⭐️ 8.0/10

Nvidia CEO Jensen Huang is reportedly stepping down from his position, with speculation mounting around allegations of affairs and potential violations of export control regulations to China. As a pivotal figure in the AI revolution and CEO of a company central to AI hardware, Huang's departure, if confirmed, could significantly impact Nvidia's leadership, strategy, and the broader AI industry's trajectory. The reports suggest that the timing of the resignation is linked to recent allegations, with some community discussions pointing to potential export ban circumvention as a primary driver rather than personal misconduct.

hackernews · lldb · Nov 12, 13:52 · [Discussion](https://news.ycombinator.com/item?id=50467087)

**Background**: Nvidia is a leading technology company renowned for its high-performance graphics processing units (GPUs), which are essential for artificial intelligence, machine learning, and high-performance computing. Jensen Huang has been the CEO and a co-founder of Nvidia since its inception in 1993, guiding the company to become a dominant force in the semiconductor industry, particularly critical for the current AI boom.

**Discussion**: Community members are debating the true reasons for Huang's potential departure, with some focusing on the alleged personal affairs and their impact on corporate perception, while others emphasize potential violations of US export bans to China as a more significant factor, questioning the timing of the revelations.

**Tags**: `#Nvidia`, `#AI`, `#Leadership`, `#Geopolitics`, `#Corporate Governance`

---

<a id="item-7"></a>
## [Microsoft 365 Suffers Widespread Service Degradation Affecting Core Services](https://status.cloud.microsoft/) ⭐️ 8.0/10

Microsoft 365 experienced a significant and prolonged service degradation on November 13, 2026, impacting email, Teams, and other essential productivity tools for users globally. The issue was attributed to an infrastructure problem that required an alternative health check method for recovery. This widespread outage highlights the critical reliance on cloud-based productivity suites and the significant business impact when these services fail. It underscores the need for robust disaster recovery and communication strategies from major cloud providers. The degradation lasted for at least 8 hours for some users, with Teams chat and meetings being the only services reported to be functioning for some. Microsoft implemented an alternative health check method to restore services and prepared an automated recovery process.

hackernews · dkpk · Nov 12, 18:20 · [Discussion](https://news.ycombinator.com/item?id=50471731)

**Background**: Microsoft 365 is a subscription-based suite of productivity and collaboration tools offered by Microsoft, including applications like Outlook, Teams, Word, and Excel, delivered via the cloud. Service degradation means that users experience reduced performance, intermittent availability, or complete unavailability of these services.

**Discussion**: Users expressed significant frustration over the outage's duration and severity, comparing it unfavorably to other major cloud incidents. Some noted that while core services were down, Teams chat and meetings remained operational, and questioned the investment in Microsoft's cloud infrastructure.

**Tags**: `#cloud computing`, `#service outage`, `#Microsoft 365`, `#systems administration`

---

<a id="item-8"></a>
## [Open-Source Project Enables LLMs on Low-Memory, Older Devices](https://github.com/hyperionaidev/smolmaxxing/) ⭐️ 8.0/10

The open-source project 'smolmaxxing' by hyperionaidev is demonstrating the feasibility of running large language models (LLMs) on devices with less than 1GB of usable memory, such as an iPad Air 1st gen and a Xiaomi TV box, achieving decent speeds for the hardware. The project openly shares developed kernels, modified models on Hugging Face, and results for reproducibility. This effort democratizes access to advanced AI capabilities by making LLMs usable on ubiquitous, low-spec hardware, potentially enabling a new wave of edge AI applications and reducing reliance on cloud infrastructure. The project focuses on optimizing kernels and models to fit within severe memory constraints, with reported success in running 16B parameter models on devices with less than 1GB RAM. The community discussion highlights that core LLM inference relies heavily on multiplication operations, suggesting that hardware with basic compute capabilities can be leveraged.

hackernews · mrashad74 · Nov 12, 15:23 · [Discussion](https://news.ycombinator.com/item?id=50468888)

**Background**: Large Language Models (LLMs) are complex AI systems trained on vast amounts of text data, capable of understanding and generating human-like text. Edge AI refers to running AI computations directly on local hardware devices rather than in a centralized cloud, offering benefits like lower latency and enhanced privacy. Kernel optimization involves improving the efficiency of fundamental computational routines (kernels) used in AI models, especially for hardware acceleration.

<details><summary>References</summary>
<ul>
<li><a href="https://www.linkedin.com/pulse/edge-ai-constraint-problem-santhosh-thiruchendru-mba-pmp-9ffce">Edge AI is a constraint problem</a></li>

</ul>
</details>

**Discussion**: Community members express enthusiasm for the trend of optimizing small models and share their own experiences running LLMs on very old or constrained hardware, including a Dreamcast. Some users question the practical utility of these highly optimized small models, while others note that LLM inference is primarily compute-bound and relies on multiplication.

**Tags**: `#LLM`, `#Edge AI`, `#Optimization`, `#Open Source`

---

<a id="item-9"></a>
## [AMD Zen 6 Architecture Features Surprising Core Design Shifts](https://chipsandcheese.com/p/talking-zen-6-with-mike-clark-at) ⭐️ 8.0/10

AMD's upcoming Zen 6 CPU architecture, discussed with designer Mike Clark, will feature a denser core design (Zen 6c) optimized for Instructions Per Cycle (IPC) and a separate high-frequency core, while maintaining software compatibility. This architectural shift in Zen 6 could lead to significant performance gains by optimizing different core types for distinct workloads, potentially impacting the competitive landscape in high-performance computing and gaming. The Zen 6c cores will feature a full 4MB of L3 cache per core, a departure from previous designs where the denser core was not the primary IPC driver. AMD aimed to minimize software-visible gaps between core types to ensure optimizations remain effective.

hackernews · dverlaeckt80 · Nov 12, 14:12 · [Discussion](https://news.ycombinator.com/item?id=50467460)

**Background**: Zen is AMD's CPU microarchitecture, known for its hybrid, multi-chip design that allows for innovation and scalability across various processor types. Instructions Per Cycle (IPC) is a measure of processor performance, indicating how many instructions a CPU can execute on average per clock cycle.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Zen_6">Zen 6 - Wikipedia</a></li>
<li><a href="https://www.techpowerup.com/review/amd-zen-6-technical-deep-dive/">AMD Zen 6 Technical Deep Dive - TechPowerUp</a></li>

</ul>
</details>

**Discussion**: Community members expressed surprise at the inversion of roles, where the denser Zen 6c core is now the primary IPC core, and noted AMD's effort to maintain software compatibility across different core types. The depth of the technical discussion was also praised.

**Tags**: `#CPU architecture`, `#AMD Zen 6`, `#microarchitecture`, `#computer engineering`

---

<a id="item-10"></a>
## [Google Launches Gemini 4 Hydrogen for Agentic Workflows](https://blog.google/innovation-and-ai/models-and-research/gemini-models/introducing-gemini-4-hydrogen/) ⭐️ 8.0/10

Google has introduced Gemini 4 Hydrogen, a new model in its Gemini series, designed for speed and efficiency in agentic workflows and everyday tasks. This model is being rolled out to users, replacing previous versions like Gemini 3.8 Flash. Gemini 4 Hydrogen's release signifies Google's continued push for more specialized and efficient AI models, potentially impacting the cost and performance of AI-powered applications and services. Users are evaluating its performance and pricing against competitors and earlier versions. While frontier models like Gemini 4 Carbon and Argon focus on deep reasoning, Hydrogen is optimized for rapid execution. It is priced similarly to the non-discounted Gemini 3.8 Flash, which is perceived as higher than previous entry-level models.

hackernews · dvaplima · Nov 12, 18:01 · [Discussion](https://news.ycombinator.com/item?id=50471431)

**Background**: Large Language Models (LLMs) often have complex naming conventions that can indicate version, size, or intended purpose, which can be confusing for users. Google's Gemini series represents a family of advanced AI models developed by Google DeepMind, with different versions tailored for various applications.

<details><summary>References</summary>
<ul>
<li><a href="https://blog.google/innovation-and-ai/models-and-research/gemini-models/introducing-gemini-4-hydrogen/">Introducing Gemini 4 Hydrogen for Agentic Workflows</a></li>
<li><a href="https://docs.cloud.google.com/gemini-enterprise-agent-platform/models/gemini/4-hydrogen">Gemini 4 Hydrogen | Gemini Enterprise Agent Platform | Google ...</a></li>
<li><a href="https://deepmind.google/models/model-cards/gemini-4-hydrogen/">Gemini 4 Hydrogen - Model Card — Google DeepMind</a></li>

</ul>
</details>

**Discussion**: Users express confusion and concern over the new naming convention, finding it unhelpful for comparing models. There are also discussions regarding the perceived increase in pricing for the new model compared to previous versions, and some users report issues with app stability and account suspensions.

**Tags**: `#AI`, `#LLM`, `#Google`, `#Gemini`, `#Machine Learning`

---

<a id="item-11"></a>
## [Jane Street Reevaluating Software Engineering Interviews Amidst LLM Advancements](https://blog.janestreet.com/software-engineering-interviews-are-changing-a-little/) ⭐️ 8.0/10

Jane Street is considering changes to its software engineering interview process due to the increasing capabilities of Large Language Models (LLMs). The company is exploring how to adapt its assessment methods to remain effective in evaluating candidates. This shift is significant as it reflects a broader industry challenge in maintaining the integrity and effectiveness of technical assessments when AI tools can potentially automate or assist in solving complex problems. It impacts how companies identify and hire skilled software engineers. The discussion highlights concerns that traditional coding challenges, like those found on LeetCode, may become less effective signals of a candidate's fundamental understanding of data structures, algorithms, and problem-solving abilities. Alternative approaches are being considered to better gauge practical skills and business requirement translation.

hackernews · maitland · Nov 12, 14:05 · [Discussion](https://news.ycombinator.com/item?id=50467297)

**Background**: Large Language Models (LLMs) are advanced AI systems capable of understanding and generating human-like text, and increasingly, code. Their growing capabilities, such as predictive text and automated responses, are impacting various professional fields. Software engineering interviews traditionally involve assessing a candidate's technical skills through coding tests, problem-solving exercises, and system design questions.

**Discussion**: Community members express skepticism about the continued relevance of LeetCode-style problems, arguing they were already flawed and are now less useful with LLMs. Some propose alternative interview strategies, such as live coding without LLM assistance for junior developers or requiring senior developers using LLMs to thoroughly explain the generated code.

**Tags**: `#software engineering`, `#interviews`, `#LLMs`, `#hiring`, `#technical assessment`

---

<a id="item-12"></a>
## [UMAP 0.6 Enhances Performance and Quality for Large Datasets](https://www.reddit.com/r/MachineLearning/comments/1xudaah/umap_06_new_initialization_new_optimizers_and/) ⭐️ 8.0/10

UMAP version 0.6 has been released, featuring a new initialization method, updated optimizers, and significantly faster nearest neighbor search, resulting in much-improved performance and quality for large-scale datasets. This release makes UMAP more practical and efficient for handling massive datasets, a common challenge in machine learning and data visualization, potentially enabling deeper insights from complex data. The new version achieves approximately 4x faster neighbor search using PyNNDescent, introduces a recursive initialization scheme that improves layout accuracy, and employs new optimizers with hard-negative mining for better fidelity on large datasets, with these new features currently opt-in.

reddit · r/MachineLearning · /u/lmcinnes · Nov 12, 13:51

**Background**: UMAP (Uniform Manifold Approximation and Projection) is a dimensionality reduction technique used for visualizing high-dimensional data by preserving its topological structure. It maps data into a lower-dimensional space, typically 2D or 3D, revealing underlying patterns that linear methods like PCA might miss. PyNNDescent is a Python library for approximate nearest neighbor search, crucial for UMAP's performance.

<details><summary>References</summary>
<ul>
<li><a href="https://umap-learn.readthedocs.io/en/latest/">UMAP: Uniform Manifold Approximation and Projection for ...</a></li>
<li><a href="https://github.com/lmcinnes/pynndescent">GitHub - lmcinnes/pynndescent: A Python nearest neighbor ...</a></li>

</ul>
</details>

**Discussion**: The community expressed excitement about the significant performance gains, particularly the speed improvements on large datasets, and noted the potential for UMAP to become even more dominant in the dimensionality reduction space.

**Tags**: `#dimensionality reduction`, `#UMAP`, `#machine learning`, `#performance`, `#algorithms`

---

<a id="item-13"></a>
## [Meta's TRIBE v2 Model Fails to Replicate Brain Topographic Maps, Except for Motion](https://www.reddit.com/r/MachineLearning/comments/1xuillf/does_metas_brainresponse_model_tribe_v2_actually/) ⭐️ 8.0/10

An independent audit of Meta's TRIBE v2 model, which predicts fMRI responses from video and audio, found it failed to recover retinotopic and tonotopic maps. However, it successfully predicted motion selectivity in the MT+ region. This analysis questions the ability of large-scale brain-response models to capture fundamental organizational principles of the brain, like retinotopy and tonotopy. It suggests that spatial averaging in model processing might obscure these crucial topographic representations, impacting the interpretation of AI models in neuroscience. The study found no significant retinotopic (d=0.05) or tonotopic (ρ=-0.07) maps, but a strong motion selectivity map (d=4.31) in the expected MT+ area. It also identified that retinotopy appeared significant only after applying stimulus-geometry controls, suggesting a potential confound rather than a true positional code.

reddit · r/MachineLearning · /u/Own_Tank1283 · Nov 12, 17:16

**Background**: Retinotopy refers to the mapping of visual input from the retina to neurons in the brain, preserving spatial relationships. Tonotopy is the spatial arrangement of neurons in the auditory system that are tuned to specific sound frequencies. TRIBE v2 is a self-supervised vision transformer model developed by Meta AI that aims to predict brain responses to various stimuli.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Retinotopy">Retinotopy</a></li>
<li><a href="https://en.wikipedia.org/wiki/Tonotopy">Tonotopy</a></li>

</ul>
</details>

**Discussion**: Commenters expressed interest in the findings, particularly the identification of stimulus-geometry as a potential confound for retinotopy. There was agreement that this type of independent auditing is crucial for validating AI models in neuroscience research, and discussion arose about the implications for other encoding models.

**Tags**: `#AI`, `#Neuroscience`, `#Machine Learning`, `#fMRI`

---

<a id="item-14"></a>
## [Eli Lilly's oral weight-loss drug approved in China](https://www.reuters.com/business/healthcare-pharmaceuticals/china-approves-eli-lillys-weight-loss-pill-orforglipron-2026-11-12/) ⭐️ 8.0/10

Eli Lilly's oral GLP-1 weight-loss drug, Orforglipron (brand name Muyouda), received approval in China on November 12th as a Class 1 new drug for adults with obesity or overweight conditions. This approval marks the first oral GLP-1 drug for weight loss available in China, introducing a new treatment option and potentially impacting the market currently dominated by injectable GLP-1 medications. Orforglipron is a once-daily oral medication that can be taken without regard to meals and will compete with weekly injectable weight-loss drugs from Novo Nordisk, Pfizer, and Sinopharm.

telegram · zaihuapd · Nov 12, 10:09

**Background**: GLP-1 receptor agonists are a class of medications that mimic the GLP-1 hormone, helping to reduce blood sugar, appetite, and energy intake. Originally developed for type 2 diabetes, some GLP-1 agonists are now approved for weight management.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/GLP-1_drug">GLP-1 drug</a></li>
<li><a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC12898445/">Orforglipron: A Comprehensive Review of an Oral Small ...</a></li>

</ul>
</details>

**Discussion**: The community is discussing the significance of this oral option compared to existing injectables and anticipating its market impact and pricing.

**Tags**: `#pharmaceuticals`, `#healthcare`, `#weight loss`, `#GLP-1`, `#China`

---