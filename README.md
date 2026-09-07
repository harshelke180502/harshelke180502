<div align="center">
  <img src="assets/profile.png" width="160" alt="Harsh Shelke" />

# Harsh Shelke

**ML Research Engineer @ Gmango AI Health**  
Real-Time Voice Infrastructure · Latency Profiling · LLM Systems  
📍 Bellevue, WA

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/harsh-shelke)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:hpshelke2002@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/harshelke180502)

</div>

---

## Overview

**Who I am.** ML research engineer focused on low-latency voice (WebSocket STT/TTS, semantic VAD) and measurable LLM systems (Langfuse, OpenTelemetry, Python).

**Building now.** The voice stack at [Gmango](https://gmango.ai) in Python, Langfuse, and OpenAI Realtime, so consults stay fast on weak networks.

### Focus Areas

| Vector | Stack I use | Why it matters |
| :--- | :--- | :--- |
| **Real-Time Voice Infrastructure** | WebSocket TTS · semantic VAD · adaptive-bitrate audio · OpenAI Realtime | Turns stay natural on weak networks, with fewer cutoffs |
| **Observability & Latency Profiling** | Langfuse · OpenTelemetry · Python replay harnesses · p50/p95/p99 | Shows which hop is slow, not just end-to-end time |
| **LLM Alignment & Fairness** | PyTorch · Transformers · LoRA / PEFT · RABBI | Same eval protocol, clearer cost / speed / fairness tradeoffs |

---

## Key Impact @ Gmango AI Health

Python · Langfuse · OpenTelemetry · WebSocket TTS · Bellevue, WA · Jul 2026 – Present

<table>
  <tr>
    <td align="center"><strong>5</strong><br/>Langfuse stage timers</td>
    <td align="center"><strong>~9×</strong><br/>TTS cost reduction</td>
    <td align="center"><strong>4</strong><br/>replay recordings</td>
    <td align="center"><strong>4</strong><br/>voice-quality bugs closed</td>
  </tr>
</table>

- Slashed voice session cost as measured by **~$0.018/session, ~9x cheaper** than ~$0.16, by switching the stack to Deepgram STT, OpenAI LLM, and OpenAI TTS.
- Exposed the slowest reply hop as measured by **5 Langfuse timers** (speech-end, first-token, TTS-dispatch, first-audio, transport), by adding OpenTelemetry spans in Python.
- Automated comparable latency tests as measured by a **4-recording replay harness**, by replaying the same clips with Python, OpenTelemetry, and LangWatch.
- Stabilized playback on weak networks as measured by live **adaptive-bitrate TTS** on a hotspot, by shrinking the Python WebSocket buffer when the link drops.
- Replaced mid-thought cutoffs as measured by **semantic VAD** (fewer cuts on "um" pauses), by swapping fixed-silence detection for pause logic in Python.
- Resolved recurring voice glitches as measured by **4 production bugs** closed, by rebuilding Python audio buffering and pause detection.
- Shipped a native Indonesian voice as measured by consults using **Indonesian TTS priming**, by passing session language into OpenAI Realtime TTS.
- Localized leftover English copy as measured by **4 English-only strings** (0 remaining), by translating diagnosis and prescription text.
- Recovered frozen-audio sessions as measured by a **10s auto-recovery** with no app restart, by restarting the TTS thread in Python.
- Hardened those voice fixes as measured by **1,162 passing / 0 failing** tests, by adding Python regression coverage for language fallback and TTS.

---

## Education

| Degree | School | Timeline |
| :--- | :--- | :--- |
| **M.S. Computer Science** | University of Illinois at Chicago (UIC) | Aug 2024 – May 2026 |
| **B.Tech Computer Science & Engineering** | MIT World Peace University, Pune, India | Aug 2020 – Jun 2024 |

---

## Featured Projects

| Project | Stack | Impact |
| :--- | :--- | :--- |
| [**Travel-Safe**](https://github.com/harshelke180502/Travel-Safe) | Python · MCP · Anthropic Claude · FastAPI · React · Pydantic | Chicago travel-safety agent with **5** safety and transit tools; risk scoring over **3** live sources (crime, CTA, incidents) |
| [**M&A Intelligence Platform**](https://github.com/harshelke180502/ma-intelligence-platform) | Python · GPT-4o-mini · FastAPI · React · PostgreSQL · Vercel · Render | **7-stage** deal-sourcing pipeline; fine-tuned GPT-4o-mini on **100** labeled profiles to score **4,400+** acquisition targets 0–100% |
| [**LLM Allocation Harms**](https://github.com/harshelke180502/Allocation-Harms-in-LLMs) | Python · PyTorch · Transformers · PEFT/LoRA | LoRA on Llama-2 and Phi-3; **+0.12** demographic parity; **25%** better cross-group fairness (RABBI) across **7** demographic groups |
| [**Prompt2Pixel**](https://github.com/harshelke180502/Prompt2Pixel) | Python · FastAPI · HF Inference · SDXL · Ollama · Jinja2 | Multi-size / multi-image generation; local **gemma3:1b** prompt enhancement and validation before SDXL |
| [**Misinformation Detection**](https://github.com/harshelke180502/Misinformation-Analysis) | BERTopic · langdetect · Sentence Transformers | Multilingual RU/UA/EN pipeline over **5.9M+** YouTube comments; tracked **10** evolving narratives with cached translation batching |
| [**SAR Visualization**](https://github.com/harshelke180502/SAR-VISUALIZATION) | React · D3.js · Vite · Tailwind · Python · RDKit | Linked-view SAR explorer for **95** β-carboline antimalarial compounds; **15** scatter pairings plus a Tanimoto heatmap from Morgan fingerprints |

---

## Technical Stack

| Layer | Tools |
| :--- | :--- |
| **Languages** | Python · JavaScript · SQL · Java · C/C++ |
| **ML & LLMs** | PyTorch · TensorFlow · Transformers · LoRA / PEFT · Fine-tuning · Sentence Transformers · XGBoost · TabNet · LangChain |
| **Voice & Real-Time Systems** | Deepgram STT · OpenAI TTS · OpenAI Realtime · ElevenLabs · Semantic VAD · WebSocket audio · Adaptive-bitrate TTS |
| **Systems & Tooling** | FastAPI · Flask · React · Docker · Git · PostgreSQL · FAISS · D3.js · Hugging Face Spaces · Langfuse · OpenTelemetry |
| **Evaluation & Metrics** | LangWatch replay harnesses · Latency profiling (p50 / p95 / p99) · TTFT / TTFA · Fairness (RABBI, demographic parity) · Precision / Recall · Cost-per-session |

---

## GitHub Analytics

<div align="center">

  <img src="https://github-readme-stats.vercel.app/api?username=harshelke180502&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&show=reviews,discussions_started,discussions_answered,prs_merged,prs_merged_percentage" alt="GitHub stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=harshelke180502&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top languages" />

  <br/>

  <img src="https://streak-stats.demolab.com/?user=harshelke180502&theme=tokyonight&hide_border=true" alt="GitHub streak" />

  <br/>

  <img src="https://github-profile-trophy.vercel.app/?username=harshelke180502&theme=tokyonight&no-frame=true&column=7&margin-w=8&margin-h=8" alt="GitHub trophies" />

  <br/>

  <img src="https://github-readme-activity-graph.vercel.app/graph?username=harshelke180502&theme=tokyo-night&hide_border=true&area=true" alt="Contribution graph" />

</div>

---

<div align="center">

`hpshelke2002@gmail.com` · [linkedin.com/in/harsh-shelke](https://linkedin.com/in/harsh-shelke) · [github.com/harshelke180502](https://github.com/harshelke180502)

</div>
