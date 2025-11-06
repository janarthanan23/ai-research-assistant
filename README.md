# 🧠 AI-Driven Multi-Agent System for Literature Review and Report Generation

### 📘 Mini Project (19CS702)  
**Submitted by:** Janarthanan S (212222040058)  
**Batch:** 2022–2026  
**Team No:** 169  
**Guide:** Dr. Anitha Julian, Professor, Department of CSE  
**Institution:** Saveetha Engineering College (Autonomous)

---

## 🚀 Project Overview

This project aims to solve the problem of **information overload** in academic and industry research by building an **AI-powered multi-agent system** that automates the entire literature review process — from searching research papers to generating structured comparative reports.

Using frameworks like **LangGraph** and **Gemini API**, the system coordinates specialized agents to handle searching, summarization, comparison, and report generation efficiently.

---

## 🎯 Problem Statement

Researchers, students, and professionals often face **information overload** when conducting literature reviews.  
Manually finding, reading, and summarizing multiple papers is time-consuming and limits innovation.

This project proposes an automated, intelligent solution that can:
- Retrieve and analyze research papers.
- Generate comprehensive, comparative summaries.
- Produce formatted `.docx` reports automatically.

---

## 🧩 Purpose of the Project

To build a **fully automated AI assistant** for research literature review that:
- Accepts a topic as input.  
- Finds and summarizes relevant academic papers.  
- Compares methodologies and findings.  
- Generates a well-structured report.

This approach significantly reduces manual effort and enhances productivity in research environments.

---

## ⚙️ Proposed Methodology

### 🧠 System Workflow

1. **Topic Input & Search Agent** – Accepts a research topic and retrieves papers via Semantic Scholar and arXiv APIs.  
2. **PDF Parsing & Preprocessing Agent** – Extracts text from papers for analysis.  
3. **Multi-Agent Analysis (LangGraph + Gemini)** – Uses AI agents for summarization and comparative analysis.  
4. **Report Generation** – Creates structured `.docx` reports using `python-docx`.  
5. **Web App & Automation** – Built with **FastAPI**, **React**, and **n8n** for seamless execution.

---

### 🧩 Workflow Diagram

<img width="811" height="609" alt="Screenshot 2025-10-19 121913" src="https://github.com/user-attachments/assets/baff410f-d495-4d6c-a3cb-0d3aa560509a" />


---

## 📊 Expected Results

- A functional web app that automates research paper analysis.  
- High-quality summaries and comparisons.  
- Consistent report generation in `.docx` format.  
- Time savings and improved research productivity.  
- A scalable foundation for advanced academic research tools.

---

## 🧠 Technologies Used

- **Frontend:** HTML  
- **Backend:** FastAPI  
- **Automation:** n8n  
- **AI Models:** LangGraph, Gemini API  
- **Libraries:** Python-docx, Requests, PDFMiner, Pandas  
- **Version Control:** Git & GitHub  

---

## 🧾 References

1. LangChain Team. *LangGraph Documentation.* [https://python.langchain.com/docs/langgraph](https://python.langchain.com/docs/langgraph)  
2. Vaswani, A. et al. (2017). *Attention Is All You Need.* [https://arxiv.org/abs/1706.03762](https://arxiv.org/abs/1706.03762)  
3. Allahyari, M. et al. (2017). *Text Summarization Techniques: A Brief Survey.* [https://arxiv.org/abs/1707.02268](https://arxiv.org/abs/1707.02268)  

---



---

> ✨ *Empowering research through automation — Let AI handle the reading while you focus on discovery.*
