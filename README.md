# 🇮🇳 Padhlo.ai – Free AI Study Assistant for Indian Students

> "Padho, likho, jeeto!"  
> Your handwritten AI study assistant that understands Indian syllabi and exam formats.

---

## 🎯 What is Padhlo.ai?

**Padhlo.ai** is a 100% free, AI-powered tool that helps Indian students prepare for exams. It generates *handwritten-style* answers from your **syllabus, question papers, or queries** using ChatGPT and outputs them in a clean PDF, image, or PPT format.

No ads. No payment. No distractions. Just study.

---

## ✨ Features

✅ Upload your syllabus or past papers (PDF)  
✅ Ask custom questions or unit names  
✅ AI-generated answers with diagrams  
✅ Handwritten-style rendering (looks like you wrote it!)  
✅ Export to PDF / Image / PPT / Word  
✅ Built for SPPU, CBSE, UPSC, and other Indian exam systems

---

## 🛠️ Built With

- [Streamlit](https://streamlit.io/) – for the UI
- [OpenAI GPT-3.5](https://openai.com/) – for answer generation
- [Pillow (PIL)](https://python-pillow.org/) – for handwritten text rendering
- [FPDF / ReportLab](https://pypi.org/project/fpdf/) – for PDF export
- [Python](https://python.org/) – backend logic

---

## 💻 Local Setup

### 🧰 Requirements
- Python 3.8+
- OpenAI API key

### 🚀 Install & Run

```bash
git clone https://github.com/yourusername/padhlo-ai.git
cd padhlo-ai

# Install packages
pip install -r requirements.txt

# Add your OpenAI API Key
echo "OPENAI_API_KEY=your_key_here" > .env

# Launch Streamlit app
streamlit run app.py
