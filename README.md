# Papers 03 — Reasoning & Test-Time Compute

A single-page presentation deck indexing the five publications that taught language models to think before answering and turned reasoning into a knob you can spend compute on at inference time. It traces the arc from **Chain-of-Thought Prompting** (Wei et al., 2022), which unlocked emergent multi-step reasoning through worked exemplars, to **Self-Consistency** (Wang et al., 2022) and its sample-many-paths-then-majority-vote decoding, through **Tree of Thoughts** (Yao et al., 2023), which recasts reasoning as deliberate BFS/DFS search with generation, state evaluation, lookahead and backtracking, then **Let's Verify Step by Step** (Lightman et al., 2023), which shows step-level process supervision trains better verifiers than outcome supervision and releases the PRM800K labels, and finally **DeepSeek-R1** (DeepSeek-AI, 2025), where large-scale RL (GRPO) grows long chain-of-thought, self-verification and "aha" moments directly from a base model and ships o1-class reasoning as open weights. Each paper gets the problem, the contribution, an engineer's-eye view of why it matters, a tailored diagram, and a callout on the practical trade-offs.

**Live site:** https://brendanjameslynskey.github.io/Papers_03_Reasoning/

Part of the [Key LLM Publications sub-hub](https://github.com/BrendanJamesLynskey/LLM_Hub_Key_Publications)
