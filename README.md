# 🌍 AI Travel Planner ✈️  
**Your Smart Companion for Effortless Travel Planning**

> Plan trips, explore destinations, and get real-time recommendations — all powered by AI.

---

## 🚀 Features

### 🧠 AI-Driven Planning
- Natural language input for travel details  
- Smart parsing of **locations**, **dates**, and **preferences**  
- Real-time **flight** and **hotel** search  
- Progress tracking and intelligent fallback handling

### 🧳 AI Assistants
- **Travel Assistant** – Personalized itinerary builder  
- **Research Assistant** – Insights on culture, tips, and attractions  
- Context-aware responses with saved history  
- Suggested prompts to guide users

### 🍽️ Local Discovery
- Restaurant search (currently optimized for **Thailand**)  
- Vector-based restaurant recommendations using ChromaDB  
- Details include:
  - Ratings & Reviews  
  - Hours, Location, Services  
  - Contact info & Pricing

### 💬 Interactive Interface
- Built with **Streamlit**  
- Chat UI with Markdown support  
- Human-like conversations powered by **Ollama** or **Claude**  
- Easily customizable and extendable

---

## 🛠 Tech Stack

| Layer          | Tools Used                                                              |
|----------------|-------------------------------------------------------------------------|
| **Frontend**   | `Streamlit`                                                             |
| **Backend**    | `Python`, `app.py` logic                                                |
| **LLMs**       | `Ollama`, `Claude`                                                      |
| **Embeddings** | `nomic-embed-text`                                                      |
| **Vector DB**  | `ChromaDB`                                                              |
| **Search API** | `DuckDuckGo`                                                            |
| **Data Sources** | `BrightData`, scraped datasets, and public APIs                        |
| **Storage**    | `JSON` + Vector database                                                |

---

## 📦 Getting Started

### 1. Install Dependencies
```bash
pip install -r requirements.txt
