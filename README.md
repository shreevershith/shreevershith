<p align="center">
  <a href="https://shreevershith.com/">
    <img src="./banner.svg" alt="Pixel-art banner: Shreevershith's avatar running past the Dallas skyline, jumping a bug. Applied AI Engineer · LLM agents · voice AI" width="100%">
  </a>
</p>

# Hey, I'm Shreevershith 👋

I'm an **Applied AI Engineer** in Dallas, building agentic systems, real-time voice agents and LLM products that hold up in production. Right now I'm the sole developer rebuilding **OptionFormulator**, a real-time options analytics platform, at Vernus Technologies. Before that, I built voice-to-action and voice-agent systems at an early-stage startup and at Implify, and enterprise chatbots and .NET systems at Infosys and UT System.

I care about agents that check their own work: grounded answers, human approval where it matters, and evals and tracing so you can see why something happened.

Open to **Applied AI, AI Engineer and Forward Deployed** roles, especially teams shipping agentic systems to real users. Open to relocation.

[![Portfolio](https://img.shields.io/badge/shreevershith.com-play_the_career_game-FFCF3F?style=flat&logo=googlechrome&logoColor=black)](https://shreevershith.com/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shreevershith-k/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/shreevershith)

> 🎮 My [portfolio](https://shreevershith.com/) is a pixel-art career game: walk through four career levels, ask a RAG chatbot about my work, or press Space and play Bug Run.

<p align="center">
  <a href="https://shreevershith.com/">
    <img src="./gameplay.gif" alt="Recording of the portfolio: the home title screen, a Bug Run where the avatar jumps bugs and 500 errors, then the journey auto-walking through Bengaluru" width="600">
  </a>
  <br><sub>Home → Bug Run → the journey. <a href="https://shreevershith.com/">Play it live</a>.</sub>
</p>

---

## 🏆 Highlights

- 🥇 **1st place**, Kaggle emotion-classification challenge
- 🥈 **2nd place**, Open Agents Hackathon 2026 (AkashGuard)
- 📄 **First-author paper**, Springer LNNS Vol. 565 (photometric redshift with deep learning)
- 🏅 **Infosys Insta Award**: a multilingual chatbot that lifted lead qualification 13%

---

## 💼 Recent work

- **Vernus Technologies, Software Engineer (Analytics Platform), Jul 2026 – now:** sole developer rebuilding OptionFormulator from legacy .NET into Python + TypeScript on Azure. The platform runs a **15s options scan cycle** across **22 strategies**, has **230 tests** checked against the legacy system, and uses a grounded LLM to explain each pick while code supplies every number.
- **Stealth Startup, Software Engineer (Forward Deployed), Jun – Jul 2026:** voice-to-action that turns live conversations into reviewable tasks, with human approval gates and idempotent execution.
- **Implify, AI Engineer (Forward Deployed), Oct 2025 – Jun 2026:** an eldercare voice assistant with a **4.5s median time to first audio** and a 6-layer filter against speech-to-text hallucinations.

---

## 🚀 Featured projects

### 🔹 [AkashGuard](https://github.com/shreevershith/akashGuard): *Open Agents Hackathon 2026 · 2nd place 🥈*
A self-healing agent for decentralized cloud. Llama 3.3 70B diagnoses failing deployments, confidence scoring picks the recovery action, and workloads are redeployed across Akash providers with no human in the loop. Decision traces are in Langfuse.
`Python` `FastAPI` `Akash Network` `Llama 3.3 70B` `Langfuse` `Telegram`

### 🔹 [Emotion Detection with Transformers](https://github.com/shreevershith/emotion_detection_using_transformers_kaggle): *Kaggle 1st place 🥇* · [demo](https://huggingface.co/spaces/shreevershith/emotionDetectionUsingQwen3)
Multi-label emotion classification over 1M+ tweets. I benchmarked RoBERTa, DistilBERT and ALBERT, then fine-tuned Qwen3-0.6B with 4-bit QLoRA. Macro-F1 went from **0.74 to 0.81** with per-class thresholds and synonym augmentation.
`PyTorch` `Qwen3` `QLoRA` `Hugging Face` `W&B`

### 🔹 [InferScope](https://inferscope.vercel.app): *live LLM cost and performance dashboard* · [repo](https://github.com/shreevershith/inferscope)
Compares LLM price, ELO and infrastructure across **15 API providers** and **10 GPU setups**. Includes a cost calculator and a Groq-powered advisor grounded in the live dashboard data, with rate limiting and prompt-injection defenses.
`React` `Vite` `Zustand` `Tailwind` `Recharts` `Groq` `Vercel`

### 🔹 [DealGraph](https://github.com/shreevershith/dealgraph): *AWS × Anthropic × Datadog GenAI Hackathon 2026*
Pitch deck in, confidence-scored deal memo out. Every claim is routed to graph, web or LLM verifiers, with OpenTelemetry tracing end to end.
`Python` `FastAPI` `Strands Agents` `Next.js` `Memgraph` `OpenTelemetry`

### 🔹 [Sidewalk](https://github.com/shreevershith/sidewalk): *YC hackathon* · [demo](https://vibeapps.dev/s/sidewalk)
Paste a local business link and get a week of growth moves: rivals, offers, posts, events and leads, from **6 agents** plus a grounded chat.
`Multi-agent` `LLM APIs` `Next.js`

### 🔹 [Cactus Voice](https://github.com/shreevershith/CactusWebApp): *on-device voice to actions*
Voice commands turned into actions **fully on-device** with local Whisper and FunctionGemma. No cloud round-trip.
`Whisper` `FunctionGemma` `On-device AI`

*More on GitHub: [Legal Strategy Council](https://github.com/shreevershith/LegalStrategyCouncil) (4 debating agents), [NutriGuard](https://github.com/shreevershith/nutriguard-api) (guarded RAG), [GlassesToReels](https://github.com/shreevershith/GlassesToReels) and more.*

---

## 🛠 Tech stack

**AI & agents**
![LLM APIs](https://img.shields.io/badge/LLM_APIs-OpenAI_·_Anthropic_·_Groq-412991?style=flat)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat&logo=langchain&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-embeddings-6B4FBB?style=flat)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat)
![Voice](https://img.shields.io/badge/Voice-Deepgram_·_Whisper-13EF93?style=flat&logoColor=black)
![Langfuse](https://img.shields.io/badge/Evals_&_tracing-Langfuse_·_OpenTelemetry-425CC7?style=flat&logo=opentelemetry&logoColor=white)

**ML & MLOps**
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat&logo=mlflow&logoColor=white)
![W&B](https://img.shields.io/badge/W%26B-FFBE00?style=flat&logo=weightsandbiases&logoColor=black)

**Languages & backend**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![C#](https://img.shields.io/badge/C%23_/_.NET-512BD4?style=flat&logo=dotnet&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js_&_React-000000?style=flat&logo=next.js&logoColor=white)

**Cloud, data & DevOps**
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)

---

## 🎓 Education & certifications

- **MS, Business Analytics & AI**, UT Dallas, with Graduate Certificates in Applied Machine Learning and in Business Analytics & Data Mining
- **BE, Computer Science & Engineering**, Visvesvaraya Technological University

| Certification | Issuer |
|---|---|
| Azure Fundamentals (AZ-900) | Microsoft |
| Azure AI Fundamentals (AI-900) | Microsoft |
| Azure Data Fundamentals (DP-900) | Microsoft |
| Power Platform Fundamentals (PL-900) | Microsoft |

---

## 🐍 My contributions, eaten

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/shreevershith/shreevershith/output/github-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/shreevershith/shreevershith/output/github-snake.svg">
  <img alt="Pixel snake eating my GitHub contribution graph" src="https://raw.githubusercontent.com/shreevershith/shreevershith/output/github-snake.svg">
</picture>

---

## 🤝 Let's connect

Hiring for Applied AI, AI Engineer or Forward Deployed roles? I'd love to talk.

🌐 [Portfolio](https://shreevershith.com/) · 💼 [LinkedIn](https://www.linkedin.com/in/shreevershith-k/)
