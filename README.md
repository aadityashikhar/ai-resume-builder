# ✦ CareerForge — AI Resume & Portfolio Builder
### MVP v0.1 · Streamlit · HuggingFace · Mistral-7B · sklearn

---

## 🚀 Features (MVP)
| Feature | AI Technique | Model |
|---|---|---|
| **Resume Generator** | Gen AI · Prompt Engineering | Mistral-7B-Instruct (HF) |
| **Cover Letter** | Gen AI · In-Context Learning | Mistral-7B-Instruct (HF) |
| **Portfolio Builder** | Gen AI · Content Generation | Mistral-7B-Instruct (HF) |
| **Job Match Scorer** | ML · TF-IDF Cosine Similarity | sklearn |

---

## ⚡ Quick Start

```bash
# 1. Install
pip install -r requirements.txt

# 2. Add HuggingFace token (free at huggingface.co/settings/tokens)
echo 'HF_TOKEN = "hf_your_token"' > .streamlit/secrets.toml

# 3. Run
streamlit run app.py
```

## ☁️ Deploy Free
- **Streamlit Cloud**: share.streamlit.io → Connect GitHub repo → Add HF_TOKEN secret
- **HuggingFace Spaces**: Create a Streamlit Space, push code
- **Google Colab**: Use pyngrok tunnel

## 🗺️ Roadmap
- **v0.2** — BERT skill extractor, LoRA fine-tuning, PDF export
- **v0.3** — LangChain job scraper agent, semantic embeddings (FAISS)
- **v0.4** — RAG interview coach, resume classifier, user auth
- **v1.0** — React frontend, FastAPI backend, auto-apply agent

## 📁 Structure
```
ai-resume-builder/
├── app.py                 # Main Streamlit app
├── requirements.txt
├── .streamlit/
│   └── secrets.toml       # HF_TOKEN
└── architecture_roadmap.html
```

## 🤝 Contributing
Pull requests welcome! See the roadmap for what's coming next.
