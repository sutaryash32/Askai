# AskAI 🏏💬

AskAI is a full‑stack conversational chatbot project built with **Spring Boot (Java)** on the backend and **Angular** on the frontend.  
It integrates with **Spring AI** and **Ollama** to provide real‑time streaming chat responses, with a special focus on **cricket‑related queries**.

---

## 🚀 Features
- **General Chat**: Streamed responses from AI models.
- **Cricket Chat**: Strictly filters queries to cricket topics, with playful fallback responses for out‑of‑syllabus prompts.
- **Server‑Sent Events (SSE)**: Real‑time streaming from backend to Angular frontend.
- **Dual Model Support**: Configurable integration with Ollama and OpenAI models.
- **Reactive Backend**: Built with Spring WebFlux for non‑blocking streaming.
- **Modern Frontend**: Angular components with live chat UI.

---

## 🛠️ Tech Stack
- **Backend**: Spring Boot, Spring WebFlux, Spring AI, Ollama API
- **Frontend**: Angular, RxJS, EventSource
- **Database**: MySQL (for persistence if needed)
- **Build Tools**: Maven
- **Version Control**: Git + GitHub

---

## ⚙️ Setup Instructions

### Backend (Spring Boot)
1. Clone the repo:
   ```bash
   git clone https://github.com/sutaryash32/Askai.git
   cd Askai
