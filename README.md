# 🧠 NeuroCanvas – AI Image Generator

**NeuroCanvas** transforms your imagination into art using **Generative AI**.  
Describe your idea, choose a style, and watch AI paint your vision — all powered by **Qwen-Image-Lightning**.

🌐 **Live App:** [neurocanvas-ai.streamlit.app](https://neurocanvas-ai.streamlit.app/)  
📦 **Repository:** [github.com/raghavramani04/NeuroCanvas-AI-Image-Generator](https://github.com/raghavramani04/NeuroCanvas-AI-Image-Generator)  
📄 **License:** MIT  
🧾 **Version:** 1.0.0  

---

## ✨ Features

- 🎨 **AI text-to-image generation** powered by Qwen-Image-Lightning  
- ⚙️ Choose from multiple **art styles** — Realistic, Cartoon, Cyberpunk, Fantasy, and more  
- 🔑 Supports both **default** and **custom Hugging Face API keys**  
- 💾 **Instant downloads** for generated images  
- 🖼️ **Dark, aesthetic UI** with previous image history  
- ⚡ **Fast and lightweight Streamlit-based deployment**

---

## ⚙️ Tech Stack

- **Frontend:** Streamlit  
- **Backend:** Hugging Face Hub  
- **Language:** Python  
- **Libraries:**
  - huggingface_hub  
  - pillow  
  - python-dotenv  
  - langchain  
  - langchain-openai  
  - langchain-groq  

**Future Expansions**
- Integrating LangChain Suite for more advanced AI reasoning  
- Multi-model support for diverse artistic outputs  
- Enhanced prompt engineering for detailed control  

---

## 🚀 Run Locally

You can easily run **NeuroCanvas** on your local machine to explore or modify it.  
Follow the steps below to get started:

```bash
# Clone the repository
git clone https://github.com/raghavramani04/NeuroCanvas-AI-Image-Generator.git
cd NeuroCanvas-AI-Image-Generator

# Install dependencies
uv pip install -r requirements.txt

# Run the Streamlit app
streamlit run NeuroCanvas.py
