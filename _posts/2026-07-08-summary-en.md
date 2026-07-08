---
layout: default
title: "Horizon Summary: 2026-07-08 (EN)"
date: 2026-07-08
lang: en
---

> From 40 items, 10 important content pieces were selected

---

1. [Januscape KVM Vulnerability Allows 16-Year-Old VM Escape on Intel/AMD](#item-1) ⭐️ 9.0/10
2. [EU's Chat Control Proposals Spark Privacy and Surveillance Debates](#item-2) ⭐️ 8.0/10
3. [Ph.D. Thesis Integrates Differentiable Ray Tracing for Radio Propagation](#item-3) ⭐️ 8.0/10
4. [MIRA: 5B Parameter Multiplayer Interactive World Model for Rocket League](#item-4) ⭐️ 8.0/10
5. [Mozilla CTO Hosts AMA on State of Open Source AI Report](#item-5) ⭐️ 8.0/10
6. [LLM 'know-say gap' linked to routing, not knowledge, study suggests](#item-6) ⭐️ 8.0/10
7. [ICML Position Paper Proposes Credit System for Better ML Conference Reviews](#item-7) ⭐️ 8.0/10
8. [Anthropic Releases Claude Sonnet 5 with Enhanced Agent Capabilities](#item-8) ⭐️ 8.0/10
9. [DeepSeek Develops Own AI Chips to Reduce Nvidia, Huawei Reliance](#item-9) ⭐️ 8.0/10
10. [China Considers Export Curbs on Advanced AI Models, Foreign Investment](#item-10) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [Januscape KVM Vulnerability Allows 16-Year-Old VM Escape on Intel/AMD](https://github.com/V4bel/Januscape) ⭐️ 9.0/10

Security researchers have disclosed Januscape (CVE-2026-53359), a critical KVM/x86 virtual machine escape vulnerability affecting both Intel and AMD platforms, which has existed for approximately 16 years. A proof-of-concept (PoC) has been released, demonstrating the ability to crash the host kernel from a guest and potentially escalate privileges. This vulnerability poses a significant risk to cloud environments and multi-tenant KVM hosts, as it undermines the isolation boundary between virtual machines and the host. Its long existence and potential for privilege escalation make it a critical concern for system security. The flaw stems from a use-after-free defect in the shadow MMU emulation within KVM, allowing a guest VM to corrupt the host's shadow page table. It was reportedly used as a 0-day exploit in a Google CTF competition, and patches have been released in recent Linux kernel updates.

telegram · zaihuapd · Jul 7, 10:14

**Background**: Kernel-based Virtual Machine (KVM) is a virtualization module in the Linux kernel that allows Linux to function as a hypervisor, enabling the creation and management of virtual machines. It requires processors with virtualization extensions like Intel VT or AMD-V. Virtual machine escape vulnerabilities allow code running inside a VM to break out and affect the host system.

<details><summary>References</summary>
<ul>
<li><a href="https://www.bleepingcomputer.com/news/linux/new-januscape-linux-kernel-flaw-allows-vm-escape-on-intel-amd-devices/">New Linux kernel flaw allows VM escape on Intel, AMD devices</a></li>
<li><a href="https://cybernews.com/security/januscape-linux-kvm-vulnerability-exposes-cloud/">Critical Linux KVM vulnerability exposes cloud servers to ...</a></li>
<li><a href="https://cybersixt.com/incidents/16-year-old-kvm-flaw-lets-guest-vms-escape-and-hijack-host-f66a5205">Januscape KVM hypervisor flaw (CVE-2026-53359) enables VM escape</a></li>

</ul>
</details>

**Discussion**: The community has expressed significant concern over the long-standing nature of this vulnerability and its implications for cloud security. There is a general consensus that prompt patching is crucial, especially given the availability of a PoC and its past use in CTF competitions.

**Tags**: `#security`, `#virtualization`, `#KVM`, `#vulnerability`, `#CVE`

---

<a id="item-2"></a>
## [EU's Chat Control Proposals Spark Privacy and Surveillance Debates](https://fightchatcontrol.eu/chat-control-overview) ⭐️ 8.0/10

The EU Council has revived the 'Chat Control 1.0' proposal, which was previously rejected by the European Parliament, and 'Chat Control 2.0' is still under discussion, both aiming to detect child sexual abuse material by scanning digital communications. These proposals raise significant concerns about mass surveillance and the erosion of privacy and end-to-end encryption, potentially impacting all digital communications within the EU. Chat Control 1.0 was narrowly rejected by the European Parliament but later revived by the EU Council, while Chat Control 2.0 continues to be debated, with critics arguing that current technology cannot effectively detect illicit material without high false positive rates.

hackernews · gasull · Jul 7, 14:23 · [Discussion](https://news.ycombinator.com/item?id=48818311)

**Background**: Chat Control, officially the Regulation to Prevent and Combat Child Sexual Abuse (CSAR), is an EU legislative proposal introduced in May 2022. Its stated goal is to combat online child sexual abuse by requiring digital platforms to detect and report child pornography. However, critics argue it mandates mass scanning of private communications, undermining encryption and privacy rights.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Chat_Control">Chat Control - Wikipedia</a></li>
<li><a href="https://fightchatcontrol.eu/chat-control-overview">Chat Control 1.0 vs 2.0 - Fight Chat Control</a></li>
<li><a href="https://byteiota.com/eu-council-chat-control-1-revival-2026/">EU Council Revives Chat Control 1.0 After Parliament Killed It</a></li>

</ul>
</details>

**Discussion**: Community members express strong opposition, viewing Chat Control as a 'dictatorial powers' play that enables mass surveillance rather than targeting offenders specifically, and raise concerns about its impact on encrypted messages and democratic opposition.

**Tags**: `#privacy`, `#surveillance`, `#legislation`, `#AI`, `#policy`

---

<a id="item-3"></a>
## [Ph.D. Thesis Integrates Differentiable Ray Tracing for Radio Propagation](https://www.reddit.com/r/MachineLearning/comments/1upvkp5/phd_thesis_on_differentiable_ray_tracing_for/) ⭐️ 8.0/10

A Ph.D. thesis has been published, presenting a novel approach to radio propagation modeling by integrating automatic differentiation into ray tracing techniques. The work aims to serve as an accessible textbook on the subject. This research bridges the gap between physics-based simulation and machine learning by enabling exact gradient computation through complex environments, which is crucial for next-generation wireless design, inverse problems, and ML model training. The thesis details the integration of automatic differentiation into a GPU-accelerated ray tracing pipeline, focusing on techniques for stable and accurate gradient computation in physical environments for applications like channel modeling and localization.

reddit · r/MachineLearning · /u/jeertmans · Jul 7, 13:45

**Background**: Radio propagation modeling predicts how radio waves travel, essential for designing wireless communication systems. Ray tracing is a rendering technique that simulates light paths, and its adaptation for radio waves allows for detailed environmental interaction analysis. Automatic differentiation (AD) is a technique that computes exact derivatives of computer programs, enabling gradient-based optimization and machine learning.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Radio_propagation">Radio propagation - Wikipedia</a></li>
<li><a href="https://www.emergentmind.com/topics/differentiable-simulation-and-automatic-differentiation">Differentiable Simulation & Automatic Differentiation</a></li>

</ul>
</details>

**Discussion**: The Reddit community expressed strong interest, highlighting the thesis's accessibility as a textbook and its innovative application of automatic differentiation in ray tracing for wireless communications. Users also noted the importance of open-source contributions and the reliance on JAX ecosystem libraries.

**Tags**: `#Machine Learning`, `#Automatic Differentiation`, `#Ray Tracing`, `#Wireless Communications`, `#Physics Simulation`

---

<a id="item-4"></a>
## [MIRA: 5B Parameter Multiplayer Interactive World Model for Rocket League](https://www.reddit.com/r/MachineLearning/comments/1upofuw/mira_multiplayer_interactive_world_models_trained/) ⭐️ 8.0/10

A new 5 billion parameter multiplayer interactive world model named MIRA has been released, trained on 10,000 hours of synthetic Rocket League data. The release includes a playable online demo, a technical report, and a dataset of 1,000 hours of 4-player gameplay. MIRA represents a significant advancement in large-scale interactive world models, demonstrating the potential for complex AI agents to learn and interact within simulated environments. This release could accelerate research in areas like reinforcement learning, game AI, and potentially robotics by providing a powerful tool and valuable dataset. The MIRA model has 5 billion parameters and can run for 4 players at 20 frames per second on a single B200 GPU. The project is a collaboration between General Intuition, Kyutai, and Epic Games.

reddit · r/MachineLearning · /u/MasterScrat · Jul 7, 07:59

**Background**: World models in AI are systems that build internal representations of an environment to predict future states based on actions. This allows AI agents to plan and act more effectively, often leading to sample-efficient reinforcement learning. The concept of mental models, which AI world models are inspired by, suggests that minds construct internal representations of reality to reason and anticipate events.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/World_model_(artificial_intelligence)">World model (artificial intelligence) - Wikipedia</a></li>
<li><a href="https://grokipedia.com/page/World_model">World models</a></li>
<li><a href="https://en.wikipedia.org/wiki/World_models">World models</a></li>

</ul>
</details>

**Discussion**: The community expressed strong interest in MIRA, highlighting its impressive scale (5B parameters) and the valuable resources provided, including a demo and dataset. Discussions touched upon the potential applications and the significance of training on complex, multi-agent environments like Rocket League.

**Tags**: `#Reinforcement Learning`, `#World Models`, `#Game AI`, `#Deep Learning`, `#Robotics`

---

<a id="item-5"></a>
## [Mozilla CTO Hosts AMA on State of Open Source AI Report](https://www.reddit.com/r/MachineLearning/comments/1upxdvc/raffi_krikorian_cto_mozilla_ama_on_the_state_of/) ⭐️ 8.0/10

Raffi Krikorian, CTO of Mozilla, hosted an Ask Me Anything (AMA) session on Reddit on July 14th to discuss the company's first 'State of Open Source AI' report, which examines real-world adoption and trends. This discussion is significant as it provides insights into the practical challenges and realities of open-source AI adoption beyond marketing hype, potentially influencing future development and investment in the field. The AMA delved into topics such as the 'hidden tax' of running AI on proprietary systems, the realities of enterprise adoption, the impact of capable Chinese AI models, developer trust in various tools, and the emerging 'agentic harness' infrastructure layer.

reddit · r/MachineLearning · /u/raffikrikorian · Jul 7, 14:51

**Background**: An 'agentic harness' refers to the software infrastructure that surrounds a large language model (LLM), enabling it to perform tasks rather than just respond to prompts, acting as an operating substrate for autonomous behavior. The 'hidden tax' on 'free' AI models refers to the often-unseen costs associated with using seemingly free AI tools, such as data usage for training, infrastructure expenses, and potential vendor lock-in.

<details><summary>References</summary>
<ul>
<li><a href="https://www.databricks.com/blog/ai-harness">What is an AI Agent Harness? | Databricks Blog</a></li>
<li><a href="https://medium.com/@balajibal/agentic-harnesses-the-new-infrastructure-layer-for-ai-systems-3939c6fac1a6">Agentic Harnesses: The New Infrastructure Layer for AI Systems? | by balaji bal | Medium</a></li>
<li><a href="https://www.cio.com/article/4140634/the-hidden-tax-on-every-ai-initiative-and-how-to-stop-paying-it.html">The hidden tax on every AI initiative (and how to stop paying ...</a></li>

</ul>
</details>

**Discussion**: The community expressed strong interest in the report's findings, particularly regarding the practical costs of open-source AI, developer trust, and the implications of the 'agentic harness' as a new infrastructure layer.

**Tags**: `#Open Source AI`, `#Mozilla`, `#AI Adoption`, `#Developer Trust`, `#AMA`

---

<a id="item-6"></a>
## [LLM 'know-say gap' linked to routing, not knowledge, study suggests](https://www.reddit.com/r/MachineLearning/comments/1uqg3g1/the_llm_knowsay_gap_looks_like_a_routing_problem/) ⭐️ 8.0/10

A new analysis proposes that the 'know-say gap' in Large Language Models (LLMs) is a routing problem, not a lack of internal knowledge. Experiments show that mid-layer hidden states contain confidence signals that are not present in the model's output, and a simple 'bridge' can help the model verbalize this confidence. This finding could significantly impact how we understand and improve LLM reliability and calibration, potentially leading to more trustworthy AI systems that can accurately express their confidence in their outputs. A linear probe on hidden states achieved a type-2 AUROC of ~0.83-0.88 for discriminating correct from incorrect answers, while the model's own confidence output was near chance (~0.57-0.58). A minimal 'bridge' controller, requiring only ~200 labeled examples and 10 trainable parameters, improved verbalized confidence discrimination to ~0.765 type-2 AUROC without altering base weights or the model's answer.

reddit · r/MachineLearning · /u/Synthium- · Jul 8, 02:40

**Background**: The 'know-say gap' refers to the discrepancy between what a language model 'knows' internally and what it can accurately 'say' or express, particularly regarding its confidence. Hidden states in LLMs are intermediate representations of the input data as it passes through the model's layers. Linear probes are simple classifiers trained to predict a specific property from these hidden states, used here to assess if confidence information is encoded internally.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2407.11421">[2407.11421] States Hidden in Hidden States: LLMs Emerge ... States Hidden in Hidden States: LLMs Emerge Discrete State ... Are the Hidden States Hiding Something? Testing the Limits of ... Bleeding Pathways: Vanishing Discriminability in LLM Hidden ... How Alignment and Jailbreak Work: Explain LLM Safety through ...</a></li>
<li><a href="https://carpentries-incubator.github.io/fair-explainable-ml/5c-probes.html">Trustworthy AI: Validity, Fairness, Explainability, and Uncertainty Assessments: Explainability methods: Linear Probes</a></li>

</ul>
</details>

**Discussion**: The community expressed interest in the novel hypothesis and the experimental methodology, with some users seeking clarification on the implications for model alignment and the generality of the findings across different model architectures and scales.

**Tags**: `#LLM`, `#Machine Learning`, `#AI`, `#Natural Language Processing`, `#Research`

---

<a id="item-7"></a>
## [ICML Position Paper Proposes Credit System for Better ML Conference Reviews](https://www.reddit.com/r/MachineLearning/comments/1upjftu/icml_position_track_want_better_ml_reviews_stop/) ⭐️ 8.0/10

A position paper submitted to the ICML 2026 Position Paper Track proposes a novel credit system to incentivize better behavior and accountability among reviewers, authors, and chairs in the machine learning conference review process. This system would award points for positive contributions, which could then be redeemed for perks like free registration or requesting additional reviewers. This proposal addresses a long-standing issue of inconsistent review quality and lack of accountability in academic conferences, potentially improving the fairness and efficiency of the peer-review process. If adopted, such a system could foster a more constructive and rewarding environment for all participants in the machine learning community. The proposed credit system allows community members to earn points for 'doing good,' such as reviewing papers (+1 point) or being outstanding (+3 points), and spend these points on perks. It also explores ideas like refundable submission fees tied to review quality and mobilizing non-author reviewers to mitigate bandwidth issues.

reddit · r/MachineLearning · /u/choHZ · Jul 7, 03:32

**Background**: The International Conference on Machine Learning (ICML) is a premier academic conference for machine learning research. The Position Paper Track at ICML provides a platform for researchers to present arguments and perspectives on future directions or systemic issues, distinct from papers reporting completed research. Artificial General Intelligence (AGI) refers to hypothetical AI with human-like cognitive abilities across a wide range of tasks.

<details><summary>References</summary>
<ul>
<li><a href="https://icml.cc/Conferences/2026/CallForPositionPapers">ICML 2026 Call For Position Papers</a></li>
<li><a href="https://en.wikipedia.org/wiki/Artificial_general_intelligence">Artificial general intelligence - Wikipedia</a></li>

</ul>
</details>

**Discussion**: The community generally views the proposal positively, recognizing the widespread problem of poor review quality and accountability in ML conferences. Discussions highlight the potential benefits of incentivizing good behavior and express interest in the practical implementation and fairness of such a credit system.

**Tags**: `#machine learning`, `#conferences`, `#review process`, `#incentives`, `#accountability`

---

<a id="item-8"></a>
## [Anthropic Releases Claude Sonnet 5 with Enhanced Agent Capabilities](https://t.me/zaihuapd/42404) ⭐️ 8.0/10

Anthropic has launched Claude Sonnet 5, its most capable Sonnet model to date, which offers improved planning and tool usage abilities, performing comparably to Opus models but at a lower cost. This new model is available across all plans starting today and is the default for Free and Pro users. The release of Claude Sonnet 5 signifies a significant advancement in making powerful AI models more accessible and cost-effective, potentially impacting the development of AI agents and applications that require sophisticated reasoning and tool interaction. Its performance parity with higher-tier models at a lower price point could accelerate adoption across various industries. Claude Sonnet 5 demonstrates superior performance over Sonnet 4.6 in reasoning, tool use, coding, and knowledge work, and is the first Sonnet model with real-time cybersecurity safeguards, though it has a lower ability for cybersecurity tasks compared to Opus models. Pricing for Claude Platform is set at $2 per million input tokens and output tokens until August 31, 2026.

telegram · zaihuapd · Jul 7, 09:02

**Background**: Claude is a series of large language models developed by Anthropic, trained using 'constitutional AI' for ethical compliance. The Claude 3 generation, including Haiku, Sonnet, and Opus, offers models of varying capabilities. LLM agents are AI systems designed to perform complex tasks by planning, reasoning, and interacting with external tools and information sources.

<details><summary>References</summary>
<ul>
<li><a href="https://www.anthropic.com/news/claude-sonnet-5">Introducing Claude Sonnet 5 \ Anthropic</a></li>
<li><a href="https://platform.claude.com/docs/en/about-claude/models/whats-new-sonnet-5">What's new in Claude Sonnet 5 - Claude Platform Docs</a></li>
<li><a href="https://en.wikipedia.org/wiki/Claude_Sonnet">Claude Sonnet</a></li>

</ul>
</details>

**Discussion**: Early community reactions highlight the significance of Sonnet 5 achieving near-Opus performance at a lower cost, especially for agentic tasks. Some users are noting its improved tool usage and planning capabilities, while others are observing its limitations in specific cybersecurity tasks compared to Opus.

**Tags**: `#AI`, `#LLM`, `#Anthropic`, `#Claude`, `#Model Release`

---

<a id="item-9"></a>
## [DeepSeek Develops Own AI Chips to Reduce Nvidia, Huawei Reliance](https://www.reuters.com/world/china/chinas-deepseek-developing-its-own-ai-chip-sources-say-2026-07-07/) ⭐️ 8.0/10

Chinese AI company DeepSeek is developing its own AI chips, focusing on the inference stage of AI models, according to three sources familiar with the matter. This initiative began about a year ago and is currently in its early stages, with DeepSeek actively recruiting chip design engineers. This development is significant as it aims to mitigate supply chain risks and reduce dependence on dominant chip providers like Nvidia and Huawei, particularly in light of US export controls impacting access to advanced AI hardware. The chips are specifically designed for AI inference, the process where trained models generate responses, rather than for model training. DeepSeek's previous models relied on Nvidia H800 and Huawei Ascend chips, and the company's founder has acknowledged chip restrictions as a challenge.

telegram · zaihuapd · Jul 7, 11:08

**Background**: AI inference chips are specialized hardware designed to efficiently run pre-trained AI models, a crucial step for deploying AI applications. This contrasts with AI training chips, which require immense computational power to develop models. Companies are increasingly pursuing custom silicon to optimize performance, reduce costs, and secure their supply chains against geopolitical pressures.

<details><summary>References</summary>
<ul>
<li><a href="https://www.naddod.com/ai-insights/inference-chip-guide-the-foundation-of-scalable-ai-applications">Inference Chip Guide: The Foundation of Scalable AI ...</a></li>
<li><a href="https://www.huaweicentral.com/huawei-reveals-3-year-ascend-ai-chip-roadmap-950-coming-in-2026/">Huawei reveals 3-year Ascend AI chip roadmap, 950 coming in ...</a></li>

</ul>
</details>

**Discussion**: The community views this as a strategic and necessary move for Chinese AI companies facing export restrictions, highlighting the growing trend of in-house chip development to ensure self-sufficiency and competitive advantage in the AI hardware market.

**Tags**: `#AI Hardware`, `#Semiconductors`, `#Supply Chain`, `#China`, `#DeepSeek`

---

<a id="item-10"></a>
## [China Considers Export Curbs on Advanced AI Models, Foreign Investment](https://www.reuters.com/world/beijing-is-looking-curbing-overseas-access-chinas-top-ai-models-sources-say-2026-07-07/) ⭐️ 8.0/10

China's Ministry of Commerce has reportedly met with major tech companies like Alibaba and ByteDance to discuss potential restrictions on exporting advanced domestic AI models, including unreleased ones, and limiting foreign investment in AI startups. These proposed restrictions could significantly impact the global AI landscape by limiting access to China's cutting-edge AI technology and potentially escalating geopolitical tensions surrounding AI development and national security. Discussions include potentially classifying the leak or theft of core AI technologies under national security laws and the scope of restrictions is still under deliberation, possibly applying only to future models.

telegram · zaihuapd · Jul 7, 11:42

**Background**: Zhipu AI is a high-tech enterprise in China that develops large language models for artificial intelligence, with its open platform offering various LLM and multimodal vision model products. The US has also been implementing export controls on advanced computing items and AI model weights, indicating a global trend of nations seeking to regulate AI technology for security reasons.

<details><summary>References</summary>
<ul>
<li><a href="https://zh.wikipedia.org/wiki/智谱">智谱 - 维基百科，自由的百科全书</a></li>
<li><a href="https://www.zhipuai.cn/">Z.ai - Inspiring AGI to Benefit Humanity</a></li>
<li><a href="https://www.sidley.com/en/insights/newsupdates/2025/01/new-us-export-controls-on-advanced-computing-items-and-artificial-intelligence-model-weights">New U.S. Export Controls on Advanced Computing Items and Artificial Intelligence Model Weights: Seven Key Takeaways | Insights | Sidley Austin LLP</a></li>

</ul>
</details>

**Discussion**: The community views this as a significant geopolitical move, with some expressing concern over potential impacts on global AI collaboration and innovation, while others see it as a necessary measure for national security.

**Tags**: `#AI Policy`, `#Geopolitics`, `#Export Controls`, `#National Security`, `#China`

---