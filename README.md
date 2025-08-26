<h1 align="center">Robust Prompting Notebooks</h1>

A collection of Jupyter tutorial notebooks on **Prompt Engineering for Hallucination Prevention**,  
developed as supplemental materials for the Hanbit Media book.  
This repository demonstrates practical techniques such as Chain-of-Thought, Self-Consistency, RAG, Reflection, and Agentic workflows to build more robust and trustworthy AI systems.

---

## Repository Structure

```plaintext
robust-prompting-notebooks/
├── LICENSE
├── README.md
├── part1/ # Introduction and basics
├── part2/ # Hallucination prevention techniques
├── part3/ # Advanced prompting & agent patterns
├── part4/ # RAG (Retrieval-Augmented Generation)
└── part5/ # Applications & case studies
```

Each notebook corresponds to a chapter in the book and can be run independently.

---

## Setup

### 1. Clone the repository

```bash
git clone https://github.com/your-username/robust-prompting-notebooks.git
cd robust-prompting-notebooks
```

### 2. Create a virtual environment

```bash
python3 -m venv venv
source venv/bin/activate
# Windows: venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

## Usage

1. Launch Jupyter Lab:

```bash
jupyter lab
```

2. Navigate to the desired part/chapter notebook (e.g., `part2/Chapter 2-5-1. Self-Consistency_ 산술 연산 구현.ipynb`)

3. Follow the step-by-step instructions inside each notebook.

> ⚠️ Note: Some examples require API keys (e.g., OpenAI, Google Gemini).
> Please set your keys as environment variables before running

```bash
export OPENAI_API_KEY=your_key_here
export GEMINI_API_KEY=your_key_here
```

## License

This repository and all included notebooks are © 2025 Hanbit Media, Inc. and Sungmin Han.
All rights reserved.

- Free for personal study, education, and non-commercial research
- Commercial use, modification, or redistribution without permission is prohibited

For commercial inquiries, please contact Hanbit Media, Inc. and Sungmin Han.
