# ✨ LexiFlow AI – Intelligent Writing Assistant

**LexiFlow AI** is an AI-powered writing assistant developed using Python and Natural Language Processing (NLP). It helps users identify spelling mistakes, analyse grammar and improve their written sentences through intelligent suggestions.

## 🚀 Features

- **Spelling Error Detection:** Identifies incorrectly spelled words.
- **Spelling Suggestions:** Generates alternative words using edit distance and word frequency.
- **Noisy Channel Model:** Ranks spelling correction candidates.
- **Grammar Checking:** Uses LanguageTool to identify grammatical issues.
- **POS Tagging:** Uses NLTK to identify parts of speech, such as nouns, verbs, adjectives and adverbs.
- **Writing Statistics:** Displays word, character and sentence counts.
- **Interactive Dashboard:** Provides a user-friendly interface for analysing written content.

## 🛠️ Technologies Used

- Python
- Natural Language Processing (NLP)
- NLTK
- LanguageTool
- Wordfreq
- Gradio
- Regular Expressions
- Google Colab

## 🧠 NLP Techniques and Algorithms

1. Tokenization
2. Edit Distance Algorithm
3. Noisy Channel Model-based candidate ranking
4. Word Frequency Analysis
5. Grammar Checking
6. Parts of Speech (POS) Tagging

## 📂 Project Structure

```text
lexiflow_NLP/
│
├── LexiFlow_AI.ipynb
├── README.md
├── requirements.txt
├── LexiFlow_AI_PBL_Report.pdf
│
└── screenshots/
    ├── screenshot1.png
    ├── screenshot2.png
    └── screenshot3.png
```

*The filenames and folder structure above are a suggested organisation for the repository.*

## ⚙️ Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/sany-sharma/lexiflow_NLP.git
```

### 2. Open the project

Open the downloaded notebook in Google Colab or Jupyter Notebook.

### 3. Install dependencies

```bash
pip install gradio language-tool-python wordfreq pandas nltk
```

### 4. Download the required NLTK resource

```python
import nltk
nltk.download('averaged_perceptron_tagger_eng')
```

### 5. Run the notebook

Execute the notebook cells in order and launch the Gradio application.

## 🖥️ Application Workflow

1. Enter or paste text into the writing editor.
2. Click **Analyze My Writing**.
3. LexiFlow AI analyses spelling and grammar.
4. View suggested corrections and writing statistics.
5. Improve your sentence using the suggestions.

## 📸 Project Screenshots

Screenshots of the LexiFlow AI dashboard will be available in the `screenshots` folder.

## 🎓 Project Information

- **Project Name:** LexiFlow AI
- **Project Domain:** Natural Language Processing
- **Project Type:** Project Based Learning (PBL)
- **Development Environment:** Google Colab
- **Programming Language:** Python

## 🔮 Future Scope

- Context-aware grammar correction.
- Improved sentence restructuring.
- More accurate tense detection.
- Clickable spelling and grammar suggestions.
- Support for additional languages.
- Advanced NLP-based sentence analysis.

## 📄 Project Documentation

The project report is included in this repository.

---

**LexiFlow AI – Every Word. Perfectly Written.**
