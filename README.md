📘 TDS Virtual TA
TDS Virtual TA is a smart assistant designed for the Tools in Data Science (TDS) course offered by IIT Madras. It can answer student questions using both markdown course content and Discourse forum discussions. It supports image-based questions and returns reliable answers with citation links.

🚀 Features
Accepts student questions and screenshots (base64 image)
Returns:
A concise answer
Relevant Discourse links with context
Uses local embeddings from markdown and forum data
Powered by FastAPI, OpenAI/Gemini, and FAISS
Deployable on Render, Vercel, or local
📂 Project Structure
. ├── api/ │ └── app.py # Main FastAPI app ├── knowledge_base.db # FAISS DB of embedded content ├── preprocess.py # Builds embedding DB ├── requirements.txt # Python dependencies ├── .env # Environment variables ├── render.yaml # Render deployment config └── README.md
