# 🔎 MindWeave — Multi-Agent AI Writing System

A multi-agent AI application that automates research, content generation, summarization, and evaluation using large language models. Built with Python and deployed through an interactive Gradio interface.

## 🚀 Features

- 🧠 **Multi-Agent Architecture** — Modular pipeline with specialized agents  
- 🔍 **Automated Research Generation** — Produces structured research with key concepts  
- ✍️ **Content Refinement** — Converts research into a coherent essay  
- 📄 **Smart Summarization** — Generates concise outputs within a word limit  
- 📊 **AI-Based Evaluation** — Provides strengths, weaknesses, and suggestions  
- 🖥️ **Interactive Web Interface** — Built using Gradio  
- 📥 **Document Export** — Outputs content as `.docx` files  


## 🗂️ Project Structure
```bash
MindWeave/
│
├── app.py / notebook.ipynb # Main application logic
├── agents/
│ ├── researcher.py
│ ├── editor.py
│ ├── summarizer.py
│ └── critic.py
├── utils/
│ └── doc_export.py
├── outputs/
│ ├── editor_output.docx
│ └── final_answer.docx
└── requirements.txt
```

## 🛠️ Tech Stack

- Python  
- OpenAI API  
- Gradio  
- python-docx  

---

## ⚙️ How It Works

1. User inputs a topic and desired word limit  
2. Research Agent generates structured content  
3. Editor Agent refines it into an essay  
4. Summarizer Agent produces a concise version  
5. Critic Agent evaluates and scores the output  


## 📦 Installation & Setup

1. **Install dependencies**
```bash
pip install gradio python-docx openai
```
2. **Set API Key**
```bash
export OPENAI_API_KEY=your_api_key_here
```
4. **Run the application**
```bash
python app.py
```

## 📊 Output
- editor_output.docx → Full generated essay
- final_answer.docx → Summarized version


## 🎯 Use Cases
1. AI-assisted research and writing
2. Academic content generation
3. Essay drafting and refinement
4. Automated writing evaluation
5. Productivity tools for students and professionals

## 🔮 Future Improvements
1. Add citation and reference generation
2. Support multiple writing styles (formal, creative, technical)
3. Improve agent coordination with memory/context
4. Deploy as a full-stack web application

## 🧑‍💻Author
**Anand** - https://github.com/ANANDSONI21
