# AI Workstation Project: "NativeAI"
**Target:** Dell Precision 7520 (Pop!_OS)[cite: 1]
**Objective:** Subscription-free, 100% local AI-driven software development[cite: 1].

---

## 1. Hardware State
*   **Current RAM:** 16GB (2x8GB)[cite: 1].
*   **Pending Upgrade:** 32GB (2x16GB) arriving to reach 48GB total[cite: 1].
*   **GPU:** Quadro M-series (NVIDIA/CUDA support active on Pop!_OS)[cite: 1].
*   **Optimization:** System swappiness set to `10` to prioritize physical memory for LLM weights[cite: 1].

## 2. Software Stack (Active)
*   **Inference Engine:** Ollama (Local)[cite: 1].
*   **Active Model:** `qwen2.5-coder:7b` (Temporary until RAM upgrade)[cite: 1].
*   **Agentic CLI:** Aider (Installed via `pipx` for environment isolation)[cite: 1].
*   **Terminal Environment:** Ghostty (GPU accelerated) + Zellij (Session management)[cite: 1].
*   **IDE Integration:** VS Code + Continue.dev (Configured for local RAG and Autocomplete)[cite: 1].

## 3. Workflow Configuration
*   **Agent Mode:** Aider is used in `--architect` mode to handle all coding tasks autonomously[cite: 1].
*   **User Role:** Purely supervisory; the LLM is the sole code generator[cite: 1].
*   **Local RAG:** Prepared for codebase indexing via `nomic-embed-text`[cite: 1].

## 4. Pending Milestones (Chronological)
1.  **[ ] RAM Installation:** Physical upgrade to 48GB[cite: 1].
2.  **[ ] Model Promotion:** Replace `7b` with `qwen2.5-coder:32b` or `deepseek-coder-v2:16b`[cite: 1].
3.  **[ ] Terminal Automation:** Finalize a Zellij `.kdl` layout that auto-starts Aider and `btop` monitoring[cite: 1].
4.  **[ ] Headless Orchestration:** Configure scripts to manage Ollama context windows up to 32k for larger codebases[cite: 1].

---
**Note for AI Session:** When acting as a collaborator, reference these hardware constraints and tool versions to ensure all generated commands and scripts are compatible with this local environment.