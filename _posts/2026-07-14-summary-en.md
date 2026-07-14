---
layout: default
title: "Horizon Summary: 2026-07-14 (EN)"
date: 2026-07-14
lang: en
---

> From 15 items, 2 important content pieces were selected

---

1. [DOOMQL: A Retro FPS Game Engine Powered by SQLite](#item-1) ⭐️ 8.0/10
2. [GPUHedge cuts serverless GPU cold start latency from 117s to 30s](#item-2) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [DOOMQL: A Retro FPS Game Engine Powered by SQLite](https://simonwillison.net/2026/Jul/13/doomql/#atom-everything) ⭐️ 8.0/10

Peter Gostev has developed DOOMQL, a retro Doom-like game implemented as a Python terminal script where the SQLite database engine controls all game logic, including movement, combat, and rendering via SQL queries. A particularly impressive SQL query implements a full ray tracer within SQLite using a recursive CTE. This project creatively repurposes SQLite, a ubiquitous database, as a game engine, demonstrating a novel application of existing technology. It challenges conventional game development paradigms and highlights the potential for databases to drive complex interactive experiences. The game runs in a terminal using text-mode pixel art and leverages a recursive CTE in SQL for its ray tracing rendering. The game state is stored in a SQLite database, which can be explored with Datasette, enabling custom HTML+JavaScript apps to interact with the game.

rss · Simon Willison · Jul 13, 22:34

**Background**: SQLite is a self-contained, serverless, zero-configuration, transactional SQL database engine that is the most widely deployed database engine in the world. It is embedded directly into applications, making it highly reliable and efficient for local data storage. Text-mode pixel art refers to graphics created using characters and symbols within a text-based terminal environment, mimicking pixel art aesthetics.

<details><summary>References</summary>
<ul>
<li><a href="https://www.sqlite.org/">SQLite Home Page</a></li>

</ul>
</details>

**Discussion**: The project has generated excitement for its unconventional use of SQL as a game engine, with many appreciating the technical ingenuity and the retro aesthetic. Some discussions revolve around the performance implications and the broader possibilities of using databases for game logic.

**Tags**: `#SQL`, `#Game Development`, `#Python`, `#Creative Coding`, `#Databases`

---

<a id="item-2"></a>
## [GPUHedge cuts serverless GPU cold start latency from 117s to 30s](https://www.reddit.com/r/MachineLearning/comments/1uvlb6h/gpuhedge_hedging_serverless_gpu_providers/) ⭐️ 8.0/10

GPUHedge, an open-source alpha tool, has been developed to significantly reduce serverless GPU cold start latency by speculatively hedging requests across multiple providers, improving p95 latency from 117 seconds to 30 seconds in initial benchmarks. This innovation addresses a critical bottleneck in serverless GPU computing, which is essential for efficient AI and ML model deployment, potentially lowering operational costs and improving user experience for latency-sensitive applications. GPUHedge works by initiating a request on a primary provider and, if a cold start is detected, conditionally launching or switching to a backup provider, with the first valid result winning and the losing job being cancelled; it also reduced active-compute cost and requests exceeding 60 seconds.

reddit · r/MachineLearning · /u/Putrid_Construction3 · Jul 13, 19:20

**Background**: Serverless GPU providers allow users to access GPU power on demand without managing infrastructure, which is beneficial for ML workloads. Cold start latency refers to the delay experienced when a serverless function is invoked after a period of inactivity, requiring the allocation and initialization of resources. P95 latency indicates the response time below which 95% of requests are completed, representing a common metric for tail latency.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Speculative_execution">Speculative execution</a></li>
<li><a href="https://redis.io/blog/p95-latency/">P95 Latency: What It Is & Why It Matters</a></li>

</ul>
</details>

**Discussion**: The community expressed interest in the novel approach to mitigating cold start latency, with users sharing their own experiences and suggesting additional providers to integrate. There's a general sentiment that this could be a valuable tool for MLOps practitioners dealing with serverless GPU costs and performance.

**Tags**: `#serverless`, `#GPU`, `#latency`, `#AI`, `#MLOps`

---