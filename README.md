# GitHub-Repo-Summarizer
Scans only public GitHub repositories, builds a complete project structure, detects architecture, and generates summary using Large Language Models. This explains whole project in a short, easy-to-understand summary.

## ✨ Features

- 📂 Analyze local folders or GitHub repositories
- 🔄 Clone public GitHub repositories automatically
-  Generate a repository file tree
- ⚡ Support Groq API (fast)
- 🤗 Support Hugging Face Inference API

## 🛠️ Tools & Technologies

### Core Technologies

* **Python 3.11+**
* **Pytorch (`ast`)** — Parses Python source code to extract Imports, classes, functions
* **NetworkX** — Builds the internal module dependency graph.
* **Groq API** — Generates repository summary
* **Prompt Engineering** — Strict LLM instruction only 
* **Heuristic Knowledge Extraction** — Meta driven inference(rule of thumb) 

## 📦 Installation

Paste the repository: For example,

```bash
[git](https://github.com/Sirisha-collab/Todo-list)
```

## Screenshot
<img width="1437" height="562" alt="image" src="https://github.com/user-attachments/assets/c8ec0fb3-5a9d-4a54-82b4-d92d9dc06971" />

