---
layout: page
title: "ARIA — Multimodal Preference Learning for LLM Post-Training"
description: "DPO from implicit multimodal feedback (face, voice) with cross-modal consensus and uncertainty filtering. Findings of EMNLP 2026."
importance: 2
category: agents
---

**Problem.** Users rarely give explicit ratings in emotional-support conversations, but their faces and voices say a lot. Can we post-train LLM policies on that implicit signal?

**Approach.** ARIA models implicit user preferences from **multimodal behavioral feedback** — facial expressions and vocal cues. It uses **cross-modal consensus** and **uncertainty-aware filtering** to build reliable preference pairs, then optimizes the LLM policy with **DPO**.

📄 [Findings of EMNLP 2026 paper](https://aclanthology.org/2026.findings-emnlp.814)
