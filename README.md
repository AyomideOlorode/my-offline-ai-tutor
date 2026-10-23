# 🧠 Air-Gapped AI Learning System

A distraction-free, offline learning framework running lightweight open-weight LLMs locally via LM Studio. Designed for active recall, Feynman-style testing, and Socratic instruction without internet dependency.

## 🚀 Key Features
- **100% Offline & Private:** Runs locally on device hardware—zero data transmitted off-machine.
- **Distraction-Free:** Eliminates browser context-switching and recommendation rabbit holes.
- **Active Pedagogy:** Pre-configured system prompts that enforce active recall rather than text generation dumps.

## 🛠️ Stack & Hardware
- **Inference Engine:** LM Studio (Local OpenAI-compatible endpoint)
- **Model Recommendation:** Llama 3.2 3B Instruct (Q4_K_M quantization) / Phi-4-mini
- **Host Specs:** 8GB – 16GB RAM

## 📦 Quickstart
1. Clone this repo: `git clone https://github.com/[your-username]/offline-ai-tutor-system.git`
2. Download LM Studio from [lmstudio.ai](https://lmstudio.ai/).
3. Pull `Llama-3.2-3B-Instruct-GGUF` inside the app.
4. Copy the prompts from `/system-prompts` into your LM Studio System Prompt settings.
5. Turn off Wi-Fi and start learning.
