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
```

### 2. Environment Setup
```bash
cp sample.env .env
# Fill in your API keys and configurations in the .env file
```

### 3. Run the Frontend
```bash
cd frontend
streamlit run frontend.py
```

### 4. Start the Backend
```bash
cd backend
python app.py
```

---

## 🧑‍💻 How to Use

1. **Describe Your Trip**  
   - Use natural language like:  
     _"I want to travel to Bangkok from New York from July 1st to July 10th."_

2. **Explore the Results**  
   - View flight options and pricing  
   - Browse hotel recommendations  
   - Discover top local restaurants

3. **Get Local Insights**  
   - Chat with the Research Assistant  
   - Learn about customs, tips, attractions, and more

---

## 🧩 Future Enhancements
- Multi-language support  
- Advanced itinerary optimization  
- Multi-user trip collaboration  
- Offline PDF itinerary export  

---

## 🤝 Contributing
Contributions are welcome! Please open an issue or pull request.

---

## 📄 License
This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.

---

## 🌐 Connect
- [GitHub](https://github.com/RomitDeokar/Travel_Planner)
- [Portfolio](https://resumechatbot1-y8jjvwn7gof79bc6euvwch.streamlit.app/)
