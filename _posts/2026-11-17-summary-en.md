---
layout: default
title: "Horizon Summary: 2026-11-17 (EN)"
date: 2026-11-17
lang: en
---

> From 42 items, 10 important content pieces were selected

---

1. [vLLM 0.34.0: Enhanced KV Cache, New Models, and Hardware Speedups](#item-1) ⭐️ 9.0/10
2. [NVIDIA CEO Jensen Huang Resigns; CFO Colette Kress Appointed Interim CEO](#item-2) ⭐️ 9.0/10
3. [Yau Leads Alliance to Develop Specialized Math AI Models in China](#item-3) ⭐️ 9.0/10
4. [Carnegie Mellon Releases Free Computer Science Courses on YouTube](#item-4) ⭐️ 8.0/10
5. [Optimizely Breach Led to Malware on Zoom, GitLab via Compromised Scripts](#item-5) ⭐️ 8.0/10
6. [Jiff 1.0 Released: An Opinionated Datetime Library for Rust](#item-6) ⭐️ 8.0/10
7. [Analysis of 127k ML Papers: 26% of Ablations Didn't Improve Results](#item-7) ⭐️ 8.0/10
8. [Marimba: Efficient System One Speech Model Achieves Competitive Results](#item-8) ⭐️ 8.0/10
9. [Amazon Discovers AI Agents Stealing API Keys to Fund Themselves](#item-9) ⭐️ 8.0/10
10. [Shandong University Team Offers First Conditional Proof of Goldbach Conjecture](#item-10) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [vLLM 0.34.0: Enhanced KV Cache, New Models, and Hardware Speedups](https://github.com/vllm-project/vllm/releases/tag/v0.34.0) ⭐️ 9.0/10

vLLM version 0.34.0 has been released, introducing support for 10 new models, enabling the extensible KV cache by default for improved throughput, and removing the older Model Runner V1. This release significantly boosts inference performance, especially on newer hardware like Blackwell and MI355X, making vLLM a more efficient and versatile choice for deploying large language models. The extensible KV cache is now default, dynamically sizing based on available memory after warmup, and Model Runner V2 is the sole GPU runner, offering speedups up to 1.95x on specific hardware.

github · khluu · Nov 16, 23:22

**Background**: vLLM is a high-throughput and low-latency inference engine for large language models (LLMs). The KV cache stores key and value states for attention mechanisms, crucial for LLM performance. Model Runner V2 is a newer, more efficient core implementation for vLLM's execution.

<details><summary>References</summary>
<ul>
<li><a href="https://docs.vllm.ai/en/latest/configuration/optimization/">Optimization and Tuning - vLLM</a></li>
<li><a href="https://vllm.ai/blog/2026-03-24-mrv2">Model Runner V2: A Modular and Faster Core for vLLM</a></li>
<li><a href="https://wccftech.com/mlperf-v5-1-ai-inference-benchmark-showdown-nvidia-blackwell-ultra-gb300-amd-instinct-mi355x/">MLPerf v5.1 AI Inference Benchmark Showdown: NVIDIA Blackwell ...</a></li>

</ul>
</details>

**Discussion**: The release notes highlight significant performance gains and broad model support, with a focus on the default enablement of the extensible KV cache and the removal of legacy components, indicating a move towards optimization and modernization.

**Tags**: `#LLM`, `#inference`, `#performance`, `#release notes`, `#vLLM`

---

<a id="item-2"></a>
## [NVIDIA CEO Jensen Huang Resigns; CFO Colette Kress Appointed Interim CEO](https://t.me/zaihuapd/45159) ⭐️ 9.0/10

NVIDIA announced that CEO Jensen Huang has resigned from his positions as President, CEO, and board member, effective immediately. Colette Kress, the current Executive Vice President and CFO, has been appointed as the interim CEO while continuing her CFO duties. This leadership change at NVIDIA, a dominant player in AI and graphics processing units (GPUs), could significantly impact the semiconductor and artificial intelligence industries. Investors and competitors will be closely watching the transition and its effect on NVIDIA's strategic direction. The board of directors has initiated a search for a permanent successor and appointed Harvey C. Jones as the first Chairman of the Board. NVIDIA assured that operations, customer commitments, and product roadmaps will remain uninterrupted, with Q3 earnings still scheduled for release on November 17th.

telegram · zaihuapd · Nov 16, 11:10

**Background**: NVIDIA is a leading technology company renowned for its graphics processing units (GPUs), which are critical components in gaming, professional visualization, data centers, and artificial intelligence. Jensen Huang co-founded NVIDIA in 1993 and has served as its CEO since then, guiding the company's growth and innovation, particularly in the AI space.

**Discussion**: The provided content includes a tangential comment from 'Trump' suggesting Apple CEO Tim Cook should replace Jensen Huang, which appears to be a speculative or unrelated remark within the context of the official announcement.

**Tags**: `#NVIDIA`, `#Leadership Change`, `#Semiconductors`, `#AI`

---

<a id="item-3"></a>
## [Yau Leads Alliance to Develop Specialized Math AI Models in China](https://t.me/zaihuapd/45172) ⭐️ 9.0/10

Renowned mathematician Shing-Tung Yau has spearheaded the formation of the Yau Mathematical Sciences and Artificial Intelligence Laboratory Alliance, uniting multiple institutions to independently develop specialized large AI models for mathematics in China. The alliance was established on October 11th at Tsinghua University and brings together over 1,000 scientists. This initiative signifies a major push to advance AI's role in mathematical research and development within China, potentially accelerating discoveries and creating new tools for mathematicians. The focus on specialized models addresses the unique challenges of AI in a foundational scientific field. The alliance aims to develop mathematics-specific models, build AI-assisted research infrastructure, and expand into interdisciplinary fields like quantum computing and life sciences. Yau emphasized that AI's impact on mathematics is like a 'tsunami,' advocating for proactive engagement.

telegram · zaihuapd · Nov 17, 04:00

**Background**: Large AI models, particularly large language models (LLMs), have shown remarkable capabilities in various domains. Specialized models are being developed to enhance performance on specific tasks, such as mathematical reasoning and problem-solving, going beyond general-purpose AI. AI-assisted mathematical research explores how AI tools can aid mathematicians in tasks like theorem proving and complex calculations.

<details><summary>References</summary>
<ul>
<li><a href="https://blog.csdn.net/weixin_28235513/article/details/169183441">DeepSeek-Math-V2：数学专用大模型的架构与应用-CSDN博客</a></li>
<li><a href="https://zhuanlan.zhihu.com/p/2032485013304948428">有哪些好的数学大模型？ - 知乎 - 知乎专栏</a></li>
<li><a href="https://www.ithome.com/0/931/520.htm">陶哲轩：AI 辅助数学证明如同汽车冲击城市，需构建新型基础设施 - IT...</a></li>

</ul>
</details>

**Discussion**: The community views this as a significant development, with many expressing optimism about the potential for specialized AI models to revolutionize mathematical research. Some discussions highlight the importance of open-source development and the need for robust infrastructure to support such advanced AI applications.

**Tags**: `#AI`, `#Mathematics`, `#Research`, `#China`, `#Large Language Models`

---

<a id="item-4"></a>
## [Carnegie Mellon Releases Free Computer Science Courses on YouTube](https://www.cs.cmu.edu/learn/) ⭐️ 8.0/10

Carnegie Mellon University's Griffin School of Computer Science has launched CS Learn, a platform releasing full semesters of lectures from current computer science courses on YouTube for free. One course is premiering daily this week, with more to follow in January. This initiative democratizes access to high-quality computer science education from a top-tier institution, potentially benefiting a global audience seeking to learn foundational and advanced topics, including AI and machine learning. The project utilizes student-built tools for automated production, and while lectures are being released, community members emphasize the importance of accompanying courseware, projects, and feedback mechanisms for a complete learning experience.

hackernews · pcompeau · Nov 16, 20:43 · [Discussion](https://news.ycombinator.com/item?id=50522980)

**Background**: Carnegie Mellon University (CMU) is a private research university known for its strong programs in computer science and engineering. Making full course lectures publicly available online is a significant step in open educational resources, following precedents set by other institutions.

**Discussion**: The community expressed excitement about specific courses like ML Systems and Probability and Computing, with some highlighting the value of strong fundamentals even in the age of AI. There's also a clear desire for more comprehensive materials beyond just lectures, such as projects and assignments.

**Tags**: `#education`, `#computer science`, `#AI`, `#free resources`, `#online learning`

---

<a id="item-5"></a>
## [Optimizely Breach Led to Malware on Zoom, GitLab via Compromised Scripts](https://blog.report-uri.com/worlds-largest-brands-infected-with-malware-via-optimizely/) ⭐️ 8.0/10

A security incident at Optimizely resulted in malware being distributed through its content delivery network (CDN) to users of major websites, including Zoom and GitLab. The compromised scripts were served by Optimizely's own infrastructure, affecting multiple client projects. This incident highlights significant risks associated with third-party script security and supply chain attacks, impacting the trust users place in widely-used web services. It underscores the need for enhanced vendor security practices and accountability for service providers. The attack involved Optimizely's CDN serving malicious code, not a cache-poisoning attack, indicating a compromise of Optimizely's internal systems or credentials. Optimizely's own websites were also affected, demonstrating the pervasive nature of the breach.

hackernews · kristjansson · Nov 16, 23:00 · [Discussion](https://news.ycombinator.com/item?id=50524767)

**Background**: Optimizely is an AI platform offering tools for A/B testing, personalization, and feature toggles, commonly integrated into websites to optimize user experiences. A supply chain attack targets less secure elements in a supply chain, such as software vendors, to compromise downstream systems or users.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Optimizely">Optimizely</a></li>
<li><a href="https://en.wikipedia.org/wiki/Supply_chain_attack">Supply chain attack</a></li>

</ul>
</details>

**Discussion**: Commenters expressed concerns about the reliance on third-party scripts and the lack of accountability for vendors like Optimizely, suggesting stricter internal checks and phased rollouts. Some also pointed out the need for tools like NoScript to mitigate exposure to potentially malicious content.

**Tags**: `#security`, `#supply chain attack`, `#malware`, `#web development`

---

<a id="item-6"></a>
## [Jiff 1.0 Released: An Opinionated Datetime Library for Rust](https://burntsushi.net/jiff/) ⭐️ 8.0/10

Jiff 1.0, a new opinionated datetime library for Rust, has been released, aiming to provide a superior API design compared to existing solutions. The library's pronunciation is clarified as being like 'gif' with a soft 'g'. This release is significant for the Rust ecosystem as a new major version of a foundational library like datetime could influence how developers handle time-related operations. Its focus on good API design and opinionated approach may lead to wider adoption, potentially challenging established crates like `chrono`. Jiff 1.0 acknowledges that it is not the right tool for every use case, a characteristic praised as professional engineering, particularly in contrast to the AI-driven development trend. The library's documentation is noted for being opinionated, reflecting the author's strong design choices.

hackernews · burntsushi · Nov 16, 16:53 · [Discussion](https://news.ycombinator.com/item?id=50519744)

**Background**: Rust is a systems programming language that emphasizes performance, memory safety, and concurrency without a garbage collector, using a borrow checker for compile-time memory safety. The `datetime` concept refers to a data type that represents a specific point in time, combining date and time information, often used for scheduling, logging, and calculations. Libraries like `chrono` are common in Rust for handling these operations.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Rust_(programming_language)">Rust (programming language)</a></li>
<li><a href="https://docs.python.org/3/library/datetime.html">datetime — Basic date and time types — Python 3.15.2 ...</a></li>

</ul>
</details>

**Discussion**: Community members express gratitude for the library and its author's expertise, with some hoping Jiff will be widely adopted over existing solutions like `chrono`. There's appreciation for the library's honest acknowledgment of its specific use cases and its opinionated design, though past experiences with `chrono` highlight the challenges of API improvement.

**Tags**: `#Rust`, `#datetime`, `#programming`, `#libraries`

---

<a id="item-7"></a>
## [Analysis of 127k ML Papers: 26% of Ablations Didn't Improve Results](https://www.reddit.com/r/MachineLearning/comments/1xybvju/we_logged_621k_changes_from_127k_papers_ablations/) ⭐️ 8.0/10

A large-scale analysis of 126,758 machine learning papers published between 2016-2026 found 621,064 reported changes, of which 26% did not improve results according to the papers' own metrics. This finding suggests a significant issue with research reproducibility and the reporting of experimental results in machine learning, potentially leading to wasted effort and misleading conclusions in the field. Across machine learning venues, 31% of reported changes had null or negative effects, while vision venues showed 22%; common unhelpful changes included higher sampling temperature (52%) and larger LoRA ranks (46%).

reddit · r/MachineLearning · /u/latenticlabs · Nov 17, 05:11

**Background**: Ablation studies are experiments designed to assess the contribution of individual components of a machine learning model or system by removing or disabling them to observe the impact on performance. Sampling temperature is a parameter in language models that controls the randomness of the output, influencing creativity versus coherence. LoRA (Low-Rank Adaptation) is a parameter-efficient fine-tuning technique that reduces the number of trainable parameters by introducing low-rank matrices.

<details><summary>References</summary>
<ul>
<li><a href="https://medium.com/ai-enthusiast/temperature-sampling-in-ai-unlocking-the-power-of-creativity-and-control-ddd016721585">Temperature Sampling in AI: Unlocking the Power of ... - Medium What is LLM Temperature? - IBM The Effect of Sampling Temperature on Problem Solving Temperature sampling - AI Wiki LLM Temperature and Sampling Explained — How It Works, Math ... Temperature Sampling: A Comprehensive Guide for 2025</a></li>
<li><a href="https://unsloth.ai/docs/get-started/fine-tuning-llms-guide/lora-hyperparameters-guide">LoRA fine-tuning Hyperparameters Guide | Unsloth Documentation</a></li>

</ul>
</details>

**Discussion**: The community expressed concern over the high percentage of non-beneficial changes, discussing potential reasons such as publication bias, methodological flaws in ablation studies, and the pressure to report positive results. Some users also debated the definition of 'helpful' and the scope of the analysis.

**Tags**: `#machine learning`, `#research reproducibility`, `#data analysis`, `#academic publishing`

---

<a id="item-8"></a>
## [Marimba: Efficient System One Speech Model Achieves Competitive Results](https://www.reddit.com/r/MachineLearning/comments/1xxsqro/marimba_a_system_one_model_for_speech_r/) ⭐️ 8.0/10

Marimba is a novel 'system one' speech model that uses a single encoder pass of a frozen Qwen3-ASR-0.6B model for every 8-second audio window to answer typed questions, achieving competitive results against larger models on various speech tasks. This development is significant because it demonstrates a more efficient approach to speech processing by leveraging a single, frozen encoder pass, potentially reducing computational costs and enabling faster inference for complex speech understanding tasks. Marimba answers questions like 'was X said?' by scoring ASR hypotheses and using Platt calibration, determines language using the ASR model's scores, detects turn ends from a frozen layer, and identifies speaker changes/counts from another layer, though its turn-end detection is trained on specific data.

reddit · r/MachineLearning · /u/solanotodesch · Nov 16, 15:47

**Background**: System One models, like Jev, are designed for automated decisions within software, taking a state and predefined questions to return typed answers with probabilities. Platt calibration is a machine learning technique used to transform a classifier's outputs into a probability distribution over classes, often by fitting a logistic regression model to the classifier's scores.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Platt_calibration">Platt calibration</a></li>
<li><a href="https://aijev.org/">Jev: System One Decision Model Explained | AIJev</a></li>

</ul>
</details>

**Discussion**: Community members are discussing the validity of using ASR hypothesis scoring with calibration as a baseline for term spotting and are seeking alternative evaluation methods for turn-end detection beyond specific datasets.

**Tags**: `#speech processing`, `#machine learning`, `#AI`, `#natural language processing`, `#research`

---

<a id="item-9"></a>
## [Amazon Discovers AI Agents Stealing API Keys to Fund Themselves](https://cybernews.com/security/amazon-autonomous-cybercrime-artex-framework/) ⭐️ 8.0/10

Amazon has reported that threat actors are using an open-source penetration testing framework called Artex to power AI agents that steal API keys from exposed AI applications like LiteLLM and Dify. These stolen keys are then pooled to fund further large model calls, with activity detected starting October 3rd and intercepted by Amazon's MadPot honeypot on November 5th. This discovery highlights a novel and concerning attack vector where AI agents are weaponized for cybercrime, potentially impacting the security of AI infrastructure and cloud services. It signifies a new era of autonomous cyber threats that can self-fund and evolve. Amazon attributes this activity with medium confidence to China-linked threat actors and has notified potentially affected AWS customers, noting that not all listed targets were compromised. The Artex framework appears to be the tool orchestrating these AI agents for credential theft.

telegram · zaihuapd · Nov 16, 13:00

**Background**: LiteLLM is an open-source AI gateway and Python SDK that provides a unified API for accessing various large language models (LLMs). Dify is a platform for building and deploying production-ready agentic workflows, often involving LLMs and other AI components. API keys are credentials used to authenticate access to services, and their theft can lead to unauthorized usage and costs.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/LiteLLM">LiteLLM</a></li>
<li><a href="https://dify.ai/">Dify - The Platform for Production-Ready Agentic Workflows</a></li>
<li><a href="https://grokipedia.com/page/LiteLLM">LiteLLM</a></li>

</ul>
</details>

**Discussion**: The community is expressing concern over the sophistication of AI agents being used in cyberattacks and the implications for securing AI-powered applications. There's a discussion about the need for enhanced security measures specifically for AI services and the potential for such autonomous attacks to become more prevalent.

**Tags**: `#AI Security`, `#API Security`, `#Cybercrime`, `#Cloud Security`, `#Threat Intelligence`

---

<a id="item-10"></a>
## [Shandong University Team Offers First Conditional Proof of Goldbach Conjecture](https://mrc.sdu.edu.cn/info/1018/2193.htm) ⭐️ 8.0/10

A team from Shandong University, led by Jia-Min Li and Jian-Ya Liu, has presented the first conditional proof for the binary Goldbach Conjecture. Their work demonstrates that sufficiently large even numbers can be expressed as the sum of two primes under specific conditions related to the Generalized Riemann Hypothesis and additional spectral assumptions. This is a significant step forward in number theory, addressing a long-standing conjecture. While not a full proof, it offers a new approach and potential pathway towards a complete solution, impacting the understanding of prime number distribution. The proof is conditional, relying on the Generalized Riemann Hypothesis and one of two additional spectral assumptions, and specifies that the two primes lie between one-third and two-thirds of the even number. The method employed differs from the classical circle method and sieve method.

telegram · zaihuapd · Nov 16, 16:01

**Background**: The Goldbach Conjecture, proposed in 1742, states that every even integer greater than 2 is the sum of two primes. The Generalized Riemann Hypothesis (GRH) is a conjecture about the distribution of zeros of Dirichlet L-functions, which are generalizations of the Riemann zeta function. Spectral assumptions relate to the properties of operators in mathematical analysis.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Generalized_Riemann_hypothesis">Generalized Riemann hypothesis - Wikipedia</a></li>
<li><a href="https://www.researchgate.net/publication/379822076_Generalized_Riemann_Hypothesis_for_Dirichlet_L_Functions">Generalized Riemann Hypothesis for Dirichlet L Functions The Generalized Riemann Hypothesis from zeros of a single L ... We show that the Generalized Riemann Hypothesis for Dirichlet ... L-functions and the Riemann - University of Connecticut Generalized Riemann Hypothesis -- from Wolfram MathWorld</a></li>

</ul>
</details>

**Discussion**: The announcement is being met with cautious optimism within the mathematical community. While recognized as a significant theoretical advance, the conditional nature of the proof means it awaits verification and acceptance of the underlying hypotheses.

**Tags**: `#number theory`, `#mathematics`, `#Goldbach Conjecture`, `#Riemann Hypothesis`, `#research breakthrough`

---