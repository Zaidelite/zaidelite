# Hi, I'm Md Zaid Akhtar

Final-year Mechanical Engineering undergraduate at **IIT Kharagpur**, building at the intersection of **GenAI systems** and **mechanical / thermo-fluid engineering**.

I like projects where an LLM is grounded in real engineering content (equations, textbooks, sensor data) rather than just answering from memory.

---

## What I Work On

- **GenAI & LLM applications:** RAG pipelines, multi-agent workflows, and multimodal assistants built with LangChain and Gemini.
- **Mechanical AI:** Applying ML to engineering problems, including AI-based condition monitoring of industrial chain drives during my internship at **Tata Steel, Jamshedpur**.
- **CFD & thermal systems:** Fluid and heat-transfer modelling (ANSYS Fluent, OpenFOAM) alongside my AI work.

---

## Featured Projects

### [MechRAG](https://github.com/Zaidelite/MechRAG) · [Live demo](https://mech-rag-frontend.vercel.app)
A Retrieval-Augmented Generation platform built for mechanical engineering textbooks, lecture notes and formula sheets.
- Preserves equations as LaTeX when parsing PDFs (PyMuPDF), rendered with KaTeX in the UI
- Hybrid retrieval: BM25 + dense embeddings (`BAAI/bge-small-en-v1.5`) fused with Reciprocal Rank Fusion
- Async ingestion with SHA256 deduplication and document state tracking (FastAPI + SQLite + ChromaDB)
- Answers from Gemini 2.5 Flash with traceable citations (book, chapter, page)
- Next.js 14 frontend, Docker Compose setup, tests and CI workflow

`Python` `FastAPI` `ChromaDB` `LangChain` `Gemini` `Next.js` `Docker`

### [Deep Research Agent](https://github.com/Zaidelite/DEEP_RESEARCH_AGENT)
An autonomous two-agent research tool: a Research Agent gathers and cites sources via Firecrawl, then an Elaboration Agent expands the draft into a fuller report, exportable as Markdown.
- Automatic fallback across multiple Gemini models
- Streamlit interface with progress tracking

`Python` `LangChain` `Gemini` `Firecrawl` `Streamlit`

### [Multimodal Voice & Vision AI Assistant](https://github.com/Zaidelite/multimodal_ai_assistant)
A modular assistant that takes voice and image input and replies in text and speech.
- Whisper for speech-to-text, gTTS for text-to-speech
- LangChain LCEL engine with Gemini for multimodal reasoning
- Gradio UI with conversation history and a clean service-per-module layout

`Python` `LangChain (LCEL)` `Whisper` `Gemini` `Gradio`

### [YouTube Multimodal Video Summarizer](https://github.com/Zaidelite/Youtube-Multimodal-Video-Summarizer-Gemini)
Summarizes videos from both audio and visuals, so on-screen code, slides and diagrams are captured, not just speech.
- Replaced an earlier Whisper + Llama 2 audio-only pipeline with native multimodal video understanding in Gemini
- `yt-dlp` ingestion with resolution control, Gemini Files API handling for large uploads
- Prompt presets (comprehensive, technical, executive brief) and Markdown export

`Python` `Gemini` `yt-dlp` `Streamlit`

### [Multi-Turn Conversation App](https://github.com/Zaidelite/Multiturn_Conversation_App)
A stateful, streaming chat application with LangChain message memory and Gemini, with session commands and graceful error handling.

`Python` `LangChain` `Gemini` `Jupyter`

---

## Tech Stack

| Area | Tools |
|---|---|
| **GenAI / LLM** | LangChain, LCEL, RAG, hybrid search (BM25 + vectors), ChromaDB, Gemini API, Whisper, prompt engineering |
| **Backend & Apps** | Python, FastAPI, SQLite, Streamlit, Gradio, Next.js, Tailwind CSS |
| **Engineering & Physics** | CFD, thermal systems analysis, ANSYS Fluent, OpenFOAM, MATLAB, SolidWorks |
| **Dev & Deployment** | Git, Docker, Docker Compose, GitHub Actions, Vercel, Render |
| **Languages** | Python, C++, TypeScript / JavaScript |

---

## Currently

- Looking for **internships and roles** in GenAI/ML, CFD/thermal and EV/automotive engineering
- Building more tools that combine LLMs with engineering workflows

---

## Let's Connect

- **LinkedIn:** [md-zaid-akhtar](https://www.linkedin.com/in/md-zaid-akhtar-2b19b0337)
- **Email:** [zaidakhtarkgpian@gmail.com](mailto:zaidakhtarkgpian@gmail.com)
