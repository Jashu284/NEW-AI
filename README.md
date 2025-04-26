# 🧠 Generative AI Assistant

Welcome to the **Generative AI Assistant** project!
This Streamlit-based app allows you to ask questions related to **Generative AI** topics such as **transformers**, **embeddings**, **GANs**, **RAG**, and more.
It uses **OpenAI GPT** models and **Pinecone** vector database for retrieval-augmented generation (RAG)!

---

## 🌐 Live Demo
[![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](YOUR_STREAMLIT_APP_LINK)

---

## 🔗 Technologies Used
- **Streamlit** for UI
- **OpenAI** for embeddings and chat completion
- **Pinecone** for semantic vector search
- **Python-dotenv** for environment variable management

---

## 🚀 Features
- Upload your own **knowledge base** (.txt or .md)
- Get **embedding-based semantic search**
- Uses **RAG** (Retrieval Augmented Generation) pipeline
- Light / Dark **theme switcher**
- Clean and **conversational UI**

---

## 🔧 Installation

```bash
# Clone the repository
git clone https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME.git
cd YOUR_REPO_NAME

# Create a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run app.py
```

---

## 📂 Environment Variables
Create a **.env** file in the project root and add:

```
OPENAI_API_KEY=your-openai-api-key
PINECONE_API_KEY=your-pinecone-api-key
PINECONE_ENV=your-pinecone-environment
PINECONE_INDEX=your-pinecone-index-name
```

**Important**: When deploying on Streamlit Cloud, configure these in the `Secrets` section.

---

## 🔥 Screenshots

| Light Mode | Dark Mode |
|:---:|:---:|
| ![light](path/to/light_mode_screenshot.png) | ![dark](path/to/dark_mode_screenshot.png) |

---

## 🚀 Future Improvements
- Multiple file uploads
- Caching frequent queries
- Admin dashboard for analytics
- Voice-based input option

---

## 📅 License
This project is licensed under the MIT License. See `LICENSE` file for more details.

---

## 📢 Connect

- GitHub: [YOUR_GITHUB_PROFILE_LINK]
- LinkedIn: [YOUR_LINKEDIN_PROFILE_LINK]

> **Made with ❤️ by [Your Name]!**

