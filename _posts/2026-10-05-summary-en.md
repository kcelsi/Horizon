---
layout: default
title: "Horizon Summary: 2026-10-05 (EN)"
date: 2026-10-05
lang: en
---

> From 24 items, 6 important content pieces were selected

---

1. [Qwen 3.8 Flash Next 125B Runs on Consumer RTX 4090 at High Speed](#item-1) ⭐️ 8.0/10
2. [ARC-AGI Benchmark Sees AI Scores Jump from 7% to 56%](#item-2) ⭐️ 8.0/10
3. [Stockfish Value Function Distilled into Neural Networks with Large Dataset Release](#item-3) ⭐️ 8.0/10
4. [DynaBase: Minimal Interpretable Architecture for Zero-Shot Dynamical System Reconstruction](#item-4) ⭐️ 8.0/10
5. [New dataset challenges CV and depth estimation with mirror suit reflections.](#item-5) ⭐️ 8.0/10
6. [Google Releases VeriHarness for Long-Range Task Verification](#item-6) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [Qwen 3.8 Flash Next 125B Runs on Consumer RTX 4090 at High Speed](https://github.com/Niko1221/Strata) ⭐️ 8.0/10

A method has been shared to run the large language model Qwen 3.8 Flash Next 125B on consumer-grade hardware, specifically an Nvidia RTX 4090, achieving token generation speeds of up to 100 tokens per second (100T/s). This was demonstrated by users achieving speeds of 124 tokens/sec and 60 tokens/sec on their respective hardware setups. This development significantly lowers the barrier to entry for utilizing powerful large language models, making advanced AI capabilities more accessible to individuals and smaller organizations. It enables users with high-end consumer GPUs to experiment with and deploy state-of-the-art models without requiring expensive enterprise hardware. The method involves running a quantized version of the 125B parameter Qwen 3.8 Flash Next model, with users reporting successful operation on systems with 128GB DDR5 RAM and Ryzen 7950x3d CPUs, as well as on older hardware with PCIe Gen3 limitations. Concerns were raised about potential quality degradation with lower bit quantizations, though 4-bit quantizations were deemed sufficient for specific coding tasks.

hackernews · snehesht · Oct 4, 12:51 · [Discussion](https://news.ycombinator.com/item?id=49953495)

**Background**: Qwen 3.8 Flash Next is a large, multimodal, open-weight model developed by Qwen, featuring a 125 billion parameter main model and supporting a large context window. Running such large models typically requires significant computational resources, often found only in specialized data centers or high-end enterprise hardware. Quantization is a technique used to reduce the memory footprint and computational cost of AI models by using lower-precision numerical formats.

<details><summary>References</summary>
<ul>
<li><a href="https://huggingface.co/Qwen/Qwen3.8-Flash-Next">Qwen / Qwen 3 . 8 - Flash - Next · Hugging Face</a></li>
<li><a href="https://github.com/qwenlm/qwen3.8-flash-next">GitHub - QwenLM/ Qwen 3 . 8 - Flash - Next : Qwen 3 . 8 - Flash - Next is the...</a></li>
<li><a href="https://unsloth.ai/docs/models/qwen3.8-next">Qwen 3 . 8 - Flash - Next : How to Run Locally | Unsloth Documentation</a></li>

</ul>
</details>

**Discussion**: Community members expressed excitement about the accessibility gains, with some sharing their own successful implementations and performance metrics. However, concerns were raised regarding potential quality degradation at lower quantization levels, and comparative benchmarks showed that other inference stacks like llama.cpp sometimes offer better accuracy for specific tasks.

**Tags**: `#LLM`, `#AI`, `#Hardware`, `#Optimization`, `#Inference`

---

<a id="item-2"></a>
## [ARC-AGI Benchmark Sees AI Scores Jump from 7% to 56%](https://www.reddit.com/r/MachineLearning/comments/1wxcd4k/top_arc%CE%B1gi3_scores_on_kaggle_just_went_from_7_to/) ⭐️ 8.0/10

Top scores on the ARC-AGI benchmark on Kaggle have dramatically increased from 7% to 56% within the last month, achieved by smaller, locally run AI models. This rapid improvement challenges the ARC-AGI benchmark's original design, which aimed to highlight human superiority in general reasoning, and suggests that current AI models are quickly approaching or surpassing human-level capabilities on specific reasoning tasks. The models achieving these scores are described as 'smallish local models,' implying they are not massive, cloud-based systems but rather more accessible, potentially resource-efficient AI.

reddit · r/MachineLearning · /u/we_are_mammals · Oct 4, 10:24 · [Discussion](https://www.reddit.com/r/MachineLearning/comments/1wxcd4k/top_arcαgi3_scores_on_kaggle_just_went_from_7_to/)

**Background**: The ARC-AGI benchmark was designed with the principle of 'Easy for Humans, Hard for AI,' intended to measure progress towards Artificial General Intelligence (AGI) by focusing on tasks that require abstract reasoning and problem-solving skills, which are considered hallmarks of human intelligence. The recent surge in AI performance suggests a potential shift in this dynamic.

<details><summary>References</summary>
<ul>
<li><a href="https://arcprize.org/arc-agi">ARC Prize - The only AI benchmark that measures AGI progress.</a></li>
<li><a href="https://arcprize.org/">ARC Prize Foundation is a nonprofit advancing open-source AGI ...</a></li>
<li><a href="https://github.com/arcprize/arc-agi-benchmarking">GitHub - arcprize/ arc - agi - benchmarking : Testing baseline LLMs...</a></li>

</ul>
</details>

**Discussion**: Community members expressed surprise and debated the implications of these results, with some questioning the benchmark's validity or the interpretation of 'human superiority' in this context, while others acknowledged the significant progress of smaller AI models.

**Tags**: `#AI`, `#Machine Learning`, `#AGI`, `#Benchmark`, `#Reasoning`

---

<a id="item-3"></a>
## [Stockfish Value Function Distilled into Neural Networks with Large Dataset Release](https://www.reddit.com/r/MachineLearning/comments/1wxz5qq/distilling_stockfish_on_a_billion_positions_full/) ⭐️ 8.0/10

A project has successfully distilled the Stockfish chess engine's value function into ResNet and Vision Transformer (ViT) models by training on one billion chess positions. A comprehensive dataset of 3.9 billion positions, derived from Lichess games, has been made publicly available on Hugging Face for research purposes. This work demonstrates a practical method for approximating complex chess engine evaluations with neural networks, potentially leading to faster and more efficient AI opponents. The release of the large dataset will empower further research in game AI and deep learning model compression. The project aimed to create a faster approximation of Stockfish's depth-limited search value function, comparing CNNs and ViTs, and found that while ViTs were initially slow, a hybrid approach yielded the best results. The constant depth during distillation was crucial for approximating the full search tree.

reddit · r/MachineLearning · /u/microscope1024 · Oct 5, 04:11

**Background**: Stockfish is a powerful open-source chess engine known for its sophisticated evaluation function, which assigns a score to different board positions. NNUE (Efficiently Updatable Neural Network) is a specialized neural network architecture used in some chess engines to replace traditional evaluation functions, offering improved performance. ResNet and ViT are types of deep learning models; ResNet (Residual Network) is a convolutional neural network (CNN) architecture, while ViT (Vision Transformer) is a model that applies the transformer architecture, originally developed for natural language processing, to image recognition tasks.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/NNUE">NNUE</a></li>

</ul>
</details>

**Discussion**: The community expressed strong interest in the practical application of distilling a top-tier chess engine and the availability of the large dataset. Discussions touched upon the technical challenges of training neural networks for chess, the performance trade-offs between different architectures like CNNs and ViTs, and the potential for this approach to compete with existing methods like NNUE.

**Tags**: `#machine learning`, `#chess AI`, `#deep learning`, `#computer vision`, `#dataset`

---

<a id="item-4"></a>
## [DynaBase: Minimal Interpretable Architecture for Zero-Shot Dynamical System Reconstruction](https://www.reddit.com/r/MachineLearning/comments/1wxex8n/a_minimal_interpretable_architecture_for_zeroshot/) ⭐️ 8.0/10

Researchers have introduced DynaBase, a novel minimal and interpretable architecture for zero-shot reconstruction of dynamical systems, capable of reproducing various dynamical regimes using only a piecewise affine map with a single parameter and a context selector. This architecture, detailed in a NeurIPS 2026 paper, surprisingly outperforms many existing foundation models in both long-term statistics and short-term predictions. DynaBase's simplicity and interpretability offer a tractable mathematical handle for understanding and improving time series and dynamical system foundation models, potentially leading to more efficient and robust AI systems. Its strong zero-shot performance suggests a significant step towards more generalizable and data-efficient machine learning. The architecture comprises a piecewise affine map controlled by a single parameter 'α' for local divergence rates and a context selector that picks the closest data point from the context signal. DynaBase can reproduce fixed points (α<1), limit cycles (α=1), and chaotic attractors (α>1), and its training can be done analytically or via a simple grid search.

reddit · r/MachineLearning · /u/DangerousFunny1371 · Oct 4, 12:49

**Background**: Dynamical systems describe how a system evolves over time, with applications in physics, engineering, and economics. Zero-shot reconstruction in machine learning refers to a model's ability to perform a task on unseen data or categories without explicit training for them. Piecewise affine maps are functions that are composed of multiple affine (linear) transformations over different regions of their domain.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Dynamical_system">Dynamical system</a></li>
<li><a href="https://www.emergentmind.com/topics/zero-shot-scene-reconstruction">Zero - Shot Scene Reconstruction</a></li>
<li><a href="https://www.emergentmind.com/topics/piecewise-affine-regularization-par">Piecewise - Affine Regularization (PAR)</a></li>

</ul>
</details>

**Discussion**: The community is impressed by the minimal nature of the architecture and its strong performance, particularly its ability to reproduce various dynamical regimes with just two core mechanisms. There is interest in its potential for interpretability and its implications for understanding complex systems.

**Tags**: `#Machine Learning`, `#Dynamical Systems`, `#Interpretability`, `#NeurIPS`, `#Research`

---

<a id="item-5"></a>
## [New dataset challenges CV and depth estimation with mirror suit reflections.](https://www.reddit.com/r/MachineLearning/comments/1wx7jg6/here_are_some_pictures_of_a_robot_costume_wearing/) ⭐️ 8.0/10

A new dataset of 425 RAW/JPEG images, featuring a robot in a custom mirror suit, has been released to benchmark computer vision and depth-estimation algorithms against extreme specular reflections. This dataset addresses a significant challenge in computer vision, where specular reflections can cause bounding-box dropouts and segmentation failures, potentially improving the robustness of AI systems in real-world scenarios. The dataset includes proprietary uncompressed Camera-Master RAWs, high-resolution JPEGs, and SHA-256 forensic manifests for data integrity, captured in high-contrast outdoor environments to specifically trigger failures in current algorithms.

reddit · r/MachineLearning · /u/5500kelvin · Oct 4, 05:21

**Background**: Specular reflections occur when light reflects off a surface in a single, mirror-like direction, posing challenges for computer vision algorithms that rely on diffuse reflection. Depth estimation algorithms process sensor data to compute depth information, which can be significantly disrupted by the unpredictable nature of specularities. SHA-256 manifests are cryptographic hashes used to verify the integrity and authenticity of digital data, crucial in forensic applications.

<details><summary>References</summary>
<ul>
<li><a href="https://cave.cs.columbia.edu/old/publications/pdfs/Nayar_IJCV97.pdf">International Journal of Computer Vision 21(3), 163-186 (199</a></li>
<li><a href="https://fiveable.me/autonomous-vehicle-systems/unit-3/depth-estimation/study-guide/qSiUyDsiHPsyod2g">Depth estimation | Autonomous Vehicle Systems Class... | Fiveable</a></li>

</ul>
</details>

**Discussion**: The community views this as a valuable contribution for testing AI systems against challenging visual conditions, with discussions likely focusing on its utility for specific applications like robotics and autonomous driving.

**Tags**: `#computer vision`, `#dataset`, `#AI/ML`, `#depth estimation`, `#benchmarking`

---

<a id="item-6"></a>
## [Google Releases VeriHarness for Long-Range Task Verification](https://arxiv.org/abs/2610.00972v1) ⭐️ 8.0/10

Google Research has introduced VeriHarness, a novel framework designed for long-range task verification. This framework uniquely employs the same model for both generating candidate results and validating them, achieving state-of-the-art performance on several benchmarks. VeriHarness addresses the critical challenge of ensuring reliability in complex, multi-step AI tasks, which is crucial for deploying AI agents in real-world applications. Its approach of using self-verification can lead to more robust and trustworthy AI systems. The framework achieves top scores on five long-horizon task benchmarks across two models, including Gemini 3.5 Flash and Claude Opus. Evidence-driven revisions show significant performance improvements, with Gemini 3.5 Flash scoring 6.2 points higher and Claude Opus 4.8 points higher on average after revision.

telegram · zaihuapd · Oct 4, 13:32

**Background**: Long-range task verification is essential for AI agents that need to perform complex sequences of actions over extended periods. Traditional methods often struggle with maintaining accuracy and coherence in such tasks. VeriHarness aims to improve this by having the AI model itself critically evaluate its own outputs.

**Discussion**: The release has been met with interest from the AI community, particularly regarding the novel self-verification approach and its performance gains on challenging benchmarks. The availability of the code and paper is seen as a positive step for reproducibility and further research.

**Tags**: `#AI`, `#Machine Learning`, `#Framework`, `#Verification`, `#Google`

---