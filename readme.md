Your `Documents/nativeAI/readme.md` has been structured to serve as the definitive "source of truth" for your AI Native transformation[cite: 1].

### Plan and Current Progress
*   **Hardware Transformation:** The plan focuses on upgrading the Dell Precision 7520 from 16GB to 48GB of RAM to enable local hosting of high-reasoning models[cite: 1].
*   **Operating System:** Pop!_OS is being utilized for its native NVIDIA and CUDA support, essential for AI workloads[cite: 1].
*   **Memory Management:** The system swappiness has been adjusted to `10` to prioritize keeping large LLMs in physical memory rather than swapping to disk[cite: 1].

### Terminal and Workspace Setup
*   **Ghostty:** You have installed this GPU-accelerated terminal emulator to handle high-speed AI text streaming with minimal latency[cite: 1].
*   **Zellij:** A custom `ai-workstation` layout has been designed to provide a multi-pane dashboard including your code editor, local AI chat, and a GPU monitor[cite: 1].
*   **Ollama:** This serves as the local inference engine, currently hosting `qwen2.5-coder:7b` for speed and prepared for the `32b` version once RAM is installed[cite: 1].

### IDE Integration
*   **Continue.dev:** VS Code has been configured to connect directly to your local Ollama instance, ensuring your coding assistance remains subscription-free[cite: 1].
*   **Local RAG:** The system is prepared for codebase indexing using the `nomic-embed-text` model[cite: 1].

For a full view of the implementation details, you can refer directly to the file: `Documents/nativeAI/readme.md`[cite: 1].