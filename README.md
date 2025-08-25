# ai-pbl-app
🧠 AI-powered assistant for project-based learning in Probability &amp; Statistics. Helps instructors generate assignments and students explore statistical methods with real datasets.
# 📊 AI-PBL App for Teaching Probability and Statistics

This application supports **project-based learning** using **AI Agent** to guide students in statistical data analysis. Built with Streamlit.

## 💻 Features

- Instructor uploads a CSV dataset and receives project assignment suggestions.
- Student enters natural-language questions and receives:
  - Matching statistical methods
  - Explanations and Python code examples
- Group assessment via custom data literacy rubric

## 📂 Files

| File                            | Description                                 |
|---------------------------------|---------------------------------------------|
| `app_en.py`                     | Streamlit application                       |
| `ai_agent_prompt_library_full.csv` | Prompt library for AI agent              |
| `requirements.txt`              | Python dependencies                         |
| `README_VI.txt`                 | Vietnamese user guide                       |

## 🚀 How to Run Locally

```bash
pip install -r requirements.txt
streamlit run app_en.py
