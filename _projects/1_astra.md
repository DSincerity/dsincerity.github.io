---
layout: page
title: "ASTRA — Strategic Tool-Augmented LLM Agent"
description: "Stateful negotiation agent with belief tracking, solver-backed tool use, and look-ahead simulation. +17.2% utility. EMNLP 2025."
importance: 1
category: agents
---

**Problem.** LLM agents in strategic, multi-turn settings (e.g., negotiation) act myopically: they don't track what the partner wants, and they can't reason about offers precisely.

**Approach.** ASTRA is an adaptive decision architecture that

- maintains an **online belief state** over partner preferences, fairness, and stance, updated every turn;
- calls **solver-backed tools** (optimization) to compute candidate offers instead of guessing numbers;
- runs **look-ahead simulation** to select the strategic action with the best expected outcome.

**Result.** Agent utility improves from **20.75 → 24.31 (+17.2%)** in agreement cases.

📄 [EMNLP 2025 paper](https://aclanthology.org/2025.emnlp-main.821/) · Related: [Are LLMs Effective Negotiators? (Findings of EMNLP 2024)](https://aclanthology.org/2024.findings-emnlp.310/)
