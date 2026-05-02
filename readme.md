AI Workstation Project: "NativeAI"
Target: Dell Precision 7520 (Pop!_OS)
Objective: Subscription-free, 100% local AI-driven software development.

1. Hardware State
Current RAM: 16GB (2x8GB).  

Pending Upgrade: 32GB (2x16GB) arriving to reach 48GB total.  

GPU: Quadro M-series (NVIDIA/CUDA support active on Pop!_OS).  

Optimization: System swappiness set to 10 to prioritize physical memory for LLM weights.  

2. Software Stack (Active)
Inference Engine: Ollama (Local).  

Active Model: qwen2.5-coder:7b (Temporary until RAM upgrade).  

Agentic CLI: Aider (Installed via pipx for environment isolation).  

Terminal Environment: Ghostty (GPU accelerated) + Zellij (Session management).  

IDE Integration: VS Code + Continue.dev (Configured for local RAG and Autocomplete).  

3. Workflow Configuration
Agent Mode: Aider is used in --architect mode to handle all coding tasks autonomously.  

User Role: Purely supervisory; the LLM is the sole code generator.

Local RAG: Prepared for codebase indexing via nomic-embed-text.  

4. Pending Milestones (Chronological)
[ ] RAM Installation: Physical upgrade to 48GB.

[ ] Model Promotion: Replace 7b with qwen2.5-coder:32b or deepseek-coder-v2:16b.

[ ] Terminal Automation: Finalize a Zellij .kdl layout that auto-starts Aider and btop monitoring.  

[ ] Headless Orchestration: Configure scripts to manage Ollama context windows up to 32k for larger codebases.