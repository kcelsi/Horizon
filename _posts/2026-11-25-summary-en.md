---
layout: default
title: "Horizon Summary: 2026-11-25 (EN)"
date: 2026-11-25
lang: en
---

> From 27 items, 10 important content pieces were selected

---

1. [OpenAI Research Suggests Matrix Multiplication Exponent is Exactly 9/4](#item-1) ⭐️ 9.0/10
2. [VMware vCenter Suffers Critical 9.8 CVSS Auth Bypass Vulnerability](#item-2) ⭐️ 9.0/10
3. [OpenAI Launches GPT-6 Cyber for Advanced Cybersecurity Research](#item-3) ⭐️ 9.0/10
4. [Ternary Bonsai 2.5 27B: Efficient LLM for Local Agentic Coding](#item-4) ⭐️ 8.0/10
5. [PenGPT: Generative Transformer for Realistic Handwriting and Sketches](#item-5) ⭐️ 8.0/10
6. [Active Intrusion Campaign Exploits PRNG Flaw in Check Point Servers](#item-6) ⭐️ 8.0/10
7. [Three LLM Inflection Points in the Past Year](#item-7) ⭐️ 8.0/10
8. [GPT-6.2 Astra Solves 1808 Sketchbook Mystery in 22 Minutes](#item-8) ⭐️ 8.0/10
9. [Huawei and Qualcomm Sign Broad Multi-Year Patent License Agreement](#item-9) ⭐️ 8.0/10
10. [Anthropic Sets IPO Price at $83 Per Share, Targeting November 2026](#item-10) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [OpenAI Research Suggests Matrix Multiplication Exponent is Exactly 9/4](https://github.com/openai/math/blob/main/preprints/The-matrix-multiplication-exponent-is-nine-fourths-November-24-2026/paper.pdf) ⭐️ 9.0/10

OpenAI has published research indicating that the matrix multiplication exponent is precisely 9/4, refuting previous conjectures about its exact value. This finding was presented in a paper titled 'The matrix multiplication exponent is nine fourths'. This result has significant implications for computational complexity theory, potentially impacting the efficiency of algorithms that rely on matrix multiplication, which are fundamental to many areas of computer science and AI. The research establishes the exponent as exactly 9/4 (or 2.25) over any field, correcting the notation from a potential O(n^2.25) to the more precise Theta(n^2.25). The paper also reportedly addresses other problems in computational mathematics.

hackernews · E-Reverance · Nov 25, 01:19 · [Discussion](https://news.ycombinator.com/item?id=50637220)

**Background**: Matrix multiplication is a fundamental operation in linear algebra. The matrix multiplication exponent, denoted by omega (ω), is the smallest real number such that any n x n matrices can be multiplied using O(n^(ω+ε)) operations for any ε > 0. Finding the exact value of ω is a long-standing problem in computer science and mathematics.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Matrix_multiplication_algorithm">Matrix multiplication algorithm - Wikipedia</a></li>
<li><a href="https://mathworld.wolfram.com/MatrixMultiplicationExponent.html">Matrix Multiplication Exponent -- from Wolfram MathWorld</a></li>

</ul>
</details>

**Discussion**: Community members noted that the title initially contained an incorrect notation (O(n^2.25) instead of Θ(n^2.25)) and that the research was conducted using an undisclosed model. Some also drew parallels between OpenAI's recent output and historical breakthroughs from Bell Labs.

**Tags**: `#matrix multiplication`, `#computational complexity`, `#algorithms`, `#AI research`, `#mathematics`

---

<a id="item-2"></a>
## [VMware vCenter Suffers Critical 9.8 CVSS Auth Bypass Vulnerability](https://thehackernews.com/2026/11/vmware-vcenter-hit-by-another-critical.html) ⭐️ 9.0/10

Broadcom has released patches for 23 vulnerabilities in VMware products, including a critical authentication bypass vulnerability (CVE-2026-123903) in vCenter's directory service (vmdir) with a CVSS score of 9.8. This flaw allows unauthenticated access to the system if vCenter is reachable. This critical vulnerability in VMware vCenter, a widely used enterprise management tool, poses a significant risk to organizations. Its exploitation as a zero-day means attackers could have already compromised systems before a fix was available, potentially leading to widespread data breaches or system control. The vulnerability, CVE-2026-123903, specifically targets the vCenter directory service (vmdir) and allows attackers to bypass authentication. The high CVSS score of 9.8 indicates a severe security risk, and the fact that it was exploited as a zero-day highlights the urgency for patching.

telegram · zaihuapd · Nov 24, 14:50

**Background**: VMware vCenter Server Appliance (VCSA) is a centralized management platform for VMware virtual environments, used to manage ESXi hosts and virtual machines. A zero-day vulnerability is a security flaw unknown to the software vendor, allowing attackers to exploit it before a patch is developed. The Common Vulnerability Scoring System (CVSS) is a framework used to rate the severity of vulnerabilities, with scores ranging from 0 (minor) to 10 (severe).

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/VMware_vCenter">VMware vCenter</a></li>
<li><a href="https://en.wikipedia.org/wiki/Zero-day_vulnerability">Zero-day vulnerability</a></li>

</ul>
</details>

**Discussion**: The community is expressing concern over the recurring critical vulnerabilities in VMware products and the implications of zero-day exploits. There's a strong emphasis on the need for prompt patching and improved security practices within organizations managing these critical infrastructure components.

**Tags**: `#vulnerability`, `#VMware`, `#vCenter`, `#cybersecurity`, `#zero-day`

---

<a id="item-3"></a>
## [OpenAI Launches GPT-6 Cyber for Advanced Cybersecurity Research](https://t.me/zaihuapd/45356) ⭐️ 9.0/10

OpenAI has released GPT-6 Cyber, a new AI model specifically designed for cybersecurity research, which demonstrates enhanced capabilities and improved model alignment. This model has already been utilized in research on the Linux kernel and is being adopted by security teams at major companies like Mozilla, Palo Alto Networks, and Cisco. The introduction of GPT-6 Cyber signifies a major advancement in AI's application to cybersecurity, potentially accelerating vulnerability discovery and defense strategies. Its adoption by leading security firms suggests a significant impact on how the industry approaches cyber threats. Currently, GPT-6 Cyber is available only to select Daybreak Red customers, with OpenAI planning a gradual expansion of access. The model reportedly achieved 40.3% recall in black-box web penetration testing, surpassing its predecessor GPT-6 Astra's 32.0%.

telegram · zaihuapd · Nov 25, 04:51

**Background**: AI alignment refers to the process of ensuring that AI systems operate in accordance with human values, goals, and ethical principles to achieve intended objectives safely and reliably. Large Language Models (LLMs) like GPT-6 Cyber are trained on vast amounts of text data and can perform a wide range of tasks, including coding, research, and analysis.

<details><summary>References</summary>
<ul>
<li><a href="https://developers.openai.com/api/docs/models/gpt-6-cyber">GPT - 6 Cyber Model | OpenAI API</a></li>
<li><a href="https://www.aixploria.com/en/gpt-6-cyber-openai/">GPT - 6 Cyber : Reviews, Price, Info & 41 Alternatives AI Tools | AIxploria</a></li>
<li><a href="https://en.wikipedia.org/wiki/GPT-5.6-Cyber">GPT-5.6-Cyber</a></li>

</ul>
</details>

**Discussion**: Community members are discussing the potential of LLMs like GPT-6 Cyber to act as a 'glue layer' between specialized AI models and to outperform them in certain tasks, particularly in complex research workflows. There's also a mention of comparing its performance against other models, including open-weight alternatives.

**Tags**: `#AI`, `#Cybersecurity`, `#OpenAI`, `#Machine Learning`, `#Research`

---

<a id="item-4"></a>
## [Ternary Bonsai 2.5 27B: Efficient LLM for Local Agentic Coding](https://prismml.com/news/bonsai-2-5-27b) ⭐️ 8.0/10

Ternary Bonsai 2.5 27B, a 27-billion parameter language model derived from Qwen3.8-27B, has been released with all weights being ternary ({−1, 0, +1}) and an FP16 scale. It offers improved performance for agentic tasks, multi-turn tool use, and multi-step execution within a 5.9 GB footprint. This model demonstrates significant advancements in local LLM efficiency, achieving high token generation speeds and supporting large context windows, making powerful AI capabilities accessible on consumer hardware for complex tasks like agentic coding. Users report token generation speeds of around 22-25 tokens/s on M5 Pro Macs with 24GB RAM and the ability to handle up to 128k context. Its performance on benchmarks like SWE-bench is noted to be competitive with future models, though potential benchmark gaming is a consideration.

hackernews · b0m · Nov 24, 20:08 · [Discussion](https://news.ycombinator.com/item?id=50633922)

**Background**: Agentic coding involves using AI agents, powered by LLMs and tools, to assist in software development tasks like writing, debugging, and testing code. These agents go beyond simple chat interfaces, operating across multiple layers of the development stack to act as collaborative partners for developers.

<details><summary>References</summary>
<ul>
<li><a href="https://docs.prismml.com/models/bonsai-2-5-27b">Ternary Bonsai 2.5 27B - Bonsai - docs.prismml.com</a></li>
<li><a href="https://prismml.com/news/bonsai-2-5-27b">PrismML — Introducing Ternary Bonsai 2.5 27B: Powering ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Agentic_coding">Agentic coding</a></li>

</ul>
</details>

**Discussion**: Community members are impressed by the model's performance on local hardware, particularly its speed and large context window support, finding it useful for agentic tasks. Some discussions revolve around comparing its benchmark scores to other models and the potential reasons for its strong performance.

**Tags**: `#LLM`, `#AI`, `#Machine Learning`, `#Open Source`, `#Performance`

---

<a id="item-5"></a>
## [PenGPT: Generative Transformer for Realistic Handwriting and Sketches](https://greydanus.github.io/2026/11/12/pengpt/) ⭐️ 8.0/10

Researchers have developed PenGPT, a generative Transformer model capable of producing realistic handwriting and sketches. The project highlights that significant effort was dedicated to creating large, clean datasets rather than novel architectural innovations. This work demonstrates the effectiveness of focusing on data quality in generative AI, suggesting that high-quality datasets can be more critical than complex model architectures for achieving impressive results in tasks like handwriting and sketch generation. The author emphasizes that approximately 80% of the effort was invested in building and quality-controlling the datasets, with the model itself being a straightforward application of existing Transformer principles.

hackernews · smusamashah · Nov 25, 00:54 · [Discussion](https://news.ycombinator.com/item?id=50637056)

**Background**: Generative Pre-trained Transformers (GPT) are a type of large language model (LLM) based on the Transformer deep learning architecture, widely used for generative AI tasks. Creating high-quality datasets is a crucial step in developing AI systems, as curated and standardized datasets are essential for effective model training and research.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/List_of_datasets_for_machine-learning_research">List of datasets for machine-learning research - Wikipedia</a></li>
<li><a href="https://aimultiple.com/datasets-for-ml">+100 Datasets for ML & AI Models</a></li>

</ul>
</details>

**Discussion**: Community members found the emphasis on data quality over architectural complexity particularly insightful, referencing the 'Bitter Lesson' concept. There is also strong interest in applying this research to areas like real-time graphical presentations.

**Tags**: `#AI`, `#Generative Models`, `#Computer Vision`, `#NLP`, `#Research`

---

<a id="item-6"></a>
## [Active Intrusion Campaign Exploits PRNG Flaw in Check Point Servers](https://www.greynoise.io/blog/check-point-security-management-servers-intrusion-campaign) ⭐️ 8.0/10

An active intrusion campaign has been identified targeting Check Point Security Management Servers by exploiting a flaw in the pseudorandom number generator (PRNG) algorithm used to sign session cookies. Attackers were able to reconstruct the PRNG's internal state to forge administrative session cookies and gain unauthorized access. This sophisticated attack highlights a critical vulnerability in how session management is secured, potentially impacting numerous organizations relying on Check Point products. It underscores the need for robust PRNG implementations and vigilant monitoring for unusual access patterns in network security infrastructure. The attackers exploited the JavaScript `Math.random()` function's PRNG within the Node.js V8 engine by observing successive login attempts and collecting enough output to deduce the signing key. This allowed them to forge administrative session cookies, bypassing standard authentication mechanisms.

hackernews · louiereederson · Nov 24, 16:32 · [Discussion](https://news.ycombinator.com/item?id=50630594)

**Background**: A pseudorandom number generator (PRNG) is an algorithm that produces a sequence of numbers that approximate the properties of random numbers, often used in cryptography and session management. Session cookies are small pieces of data stored by a web server on a user's device to maintain state, such as login status, between requests.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Pseudorandom_number_generator">Pseudorandom number generator - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Session_cookies">Session cookies</a></li>

</ul>
</details>

**Discussion**: Community members expressed concern over the exploitation of a fundamental PRNG function like `Math.random()`, with some questioning why such generators aren't inherently more secure. There's also discussion about the potential for AI to be used in future sophisticated cyberattacks.

**Tags**: `#cybersecurity`, `#vulnerability`, `#intrusion detection`, `#network security`, `#AI`

---

<a id="item-7"></a>
## [Three LLM Inflection Points in the Past Year](https://simonwillison.net/2026/Nov/24/llm-inflection-points/) ⭐️ 8.0/10

This post identifies three significant inflection points in LLM and coding agent capabilities over the last twelve months, using the anniversary of Claude Opus 4.5's release as a key marker. The first inflection point, around November 2025, saw models like Claude Opus 4.5 and OpenAI's GPT-5.1 series become reliably useful for daily coding tasks. These inflection points signify a rapid acceleration in AI's ability to assist with complex tasks, particularly in software development. This evolution impacts developers by potentially increasing productivity and changing how coding problems are approached. The second inflection point, in June/July 2026, was marked by 'Fable class models' like Claude Fable 5, which demonstrated proactive problem-solving and brute-force capability, though Fable 5 was briefly subject to export controls. The third inflection point is described as the arrival of models capable of 'thinking' and performing actions, moving beyond mere inference.

rss · Simon Willison · Nov 24, 23:02

**Background**: Large Language Models (LLMs) are advanced AI systems trained on vast amounts of text data, enabling them to understand and generate human-like text. Coding agents are specialized AI tools designed to assist with software development tasks, such as writing code, debugging, and testing. Claude Opus 4.5 and GPT-5.1 are specific versions of LLMs developed by Anthropic and OpenAI, respectively, known for their advanced capabilities.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Claude_(AI)">Claude (AI) - Wikipedia</a></li>
<li><a href="https://grokipedia.com/page/Comparison_of_Claude_Opus_45_and_Grok_Code_Fast_1">Comparison of Claude Opus 4.5 and Grok Code Fast 1</a></li>

</ul>
</details>

**Discussion**: The discussion highlights the rapid pace of LLM development, with users noting how quickly these tools have become indispensable for many coding tasks. There's an ongoing conversation about the definition and impact of these 'inflection points' on the AI and software engineering landscape.

**Tags**: `#LLM`, `#AI`, `#Coding Agents`, `#Machine Learning`, `#Analysis`

---

<a id="item-8"></a>
## [GPT-6.2 Astra Solves 1808 Sketchbook Mystery in 22 Minutes](https://simonwillison.net/2026/Nov/24/astra-historical-mystery/) ⭐️ 8.0/10

History professor Mark Humphries used GPT-6.2 Astra to autonomously identify the creator of an anonymous 1808 sketchbook from Yale's Beinecke Library in just 22 minutes by analyzing publicly available sources. This case study demonstrates a significant advancement in AI's capability for autonomous research and discovery, potentially transforming historical research by rapidly uncovering new insights from vast amounts of data. GPT-6.2 Astra discovered a little-known paper archive source, predicted its relevance, and used it to confirm the sketchbook belonged to the vicomte de Chabot, whose travel journal was later identified as a key piece of evidence.

rss · Simon Willison · Nov 24, 16:53

**Background**: GPT-6.2 Astra is a family of large language models released by OpenAI on November 17, 2026, available to paid users. While some early testers criticized its performance, this application highlights its potential for complex analytical tasks beyond typical generative AI uses.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/GPT-6.2_Astra">GPT-6.2 Astra</a></li>
<li><a href="https://simonwillison.net/2026/Nov/17/gpt62-astra-and-sol/">GPT ‑ 6 . 2 Astra and GPT ‑ 6 . 2 Sol | Simon Willison’s Weblog</a></li>

</ul>
</details>

**Discussion**: Some community members expressed awe at the AI's speed and autonomous research capabilities, while others raised concerns about the potential 'crisis of confidence' for historians, akin to the impact of AI in mathematics, though acknowledging the unique interpretive nature of historical work.

**Tags**: `#AI`, `#Historical Research`, `#Case Study`, `#GPT`, `#Discovery`

---

<a id="item-9"></a>
## [Huawei and Qualcomm Sign Broad Multi-Year Patent License Agreement](https://t.me/zaihuapd/45344) ⭐️ 8.0/10

Huawei and Qualcomm have announced a multi-year, broad patent license agreement covering technologies like 5G, computing, AI, and networking, effective from 2021. As part of the deal, Qualcomm will also license Huawei's patented logic folding chip manufacturing technology. This agreement resolves significant patent disputes between two major telecommunications players, impacting the global 5G and AI patent landscape. The deal is expected to generate over $6.9 billion in cumulative patent licensing revenue for Huawei, bolstering its intellectual property business. The agreement includes cross-licensing of patent portfolios and Qualcomm's purchase of certain Huawei patents in the US. Huawei anticipates its patent licensing business will achieve positive revenue from 2021 onwards, with cumulative expected contract value exceeding $6.9 billion post-agreement.

telegram · zaihuapd · Nov 24, 11:38

**Background**: Cross-licensing is a form of licensing agreement where two or more patent holders grant each other permission to use their respective patents, often to avoid litigation or facilitate product development. Huawei's 'logic folding' technology is an advanced chip manufacturing technique that optimizes circuit layout to improve transistor density and system performance, representing a significant innovation in chip design.

<details><summary>References</summary>
<ul>
<li><a href="https://www.thepaper.cn/newsDetail_forward_34242762">华为麒麟9050系列实现逻辑折叠技术量产，2027年芯片已进入测试阶段_10...</a></li>
<li><a href="https://baike.baidu.com/item/交叉许可/1000643">交叉许可_百度百科</a></li>
<li><a href="https://wiki.mbalib.com/wiki/交叉许可">交叉许可 - MBA智库百科 - wiki.mbalib.com</a></li>

</ul>
</details>

**Discussion**: The community views this as a significant business development, highlighting the importance of Huawei's intellectual property and its ability to monetize its innovations, especially in advanced areas like AI and chip manufacturing.

**Tags**: `#5G`, `#AI`, `#Patents`, `#Licensing`, `#Telecommunications`

---

<a id="item-10"></a>
## [Anthropic Sets IPO Price at $83 Per Share, Targeting November 2026](https://t.me/zaihuapd/45347) ⭐️ 8.0/10

AI company Anthropic has announced its Initial Public Offering (IPO) pricing at $83 per share for its Class A common stock. The company plans to offer approximately 9.8 billion shares, with trading expected to commence on the Nasdaq Global Select Market under the ticker ANT on November 19, 2026. This IPO pricing marks a significant milestone for Anthropic, a key player in the AI industry, and provides a valuation benchmark for the rapidly evolving AI sector. The successful listing could influence future AI company valuations and investment strategies. The offering includes approximately 9.56 billion shares sold by the company and about 23.65 million shares sold by certain shareholders, with underwriters having an option to purchase up to an additional 147 million shares. The offering is expected to close on November 20, 2026.

telegram · zaihuapd · Nov 24, 13:52

**Background**: An Initial Public Offering (IPO) is the process by which a private company becomes public by selling shares to investors on a stock exchange. Class A common stock is a type of stock that may have different voting rights or privileges compared to other classes. The Nasdaq Global Select Market is the highest tier of the Nasdaq stock market, known for its stringent listing requirements.

<details><summary>References</summary>
<ul>
<li><a href="https://baike.baidu.com/item/A类普通股/67544291">A类普通股_百度百科</a></li>
<li><a href="https://baike.baidu.com/item/纳斯达克全球精选市场/68858569">纳斯达克全球精选市场 - 百度百科</a></li>

</ul>
</details>

**Tags**: `#AI`, `#IPO`, `#Finance`, `#Anthropic`

---