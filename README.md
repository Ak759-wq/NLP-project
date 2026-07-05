# NLP-project
# 📚 AI Research Paper Search Engine

Finding relevant research papers can be frustrating when traditional keyword searches miss papers that mean the same thing but use different wording.

I built this project to make research paper discovery smarter using Natural Language Processing (NLP) and semantic search. Instead of relying only on keywords, it understands the meaning behind a query and returns the most relevant papers. Along with search, it can summarize papers, extract important keywords, identify named entities, and recommend similar research papers.

---

## ✨ Features

- 🔍 Semantic search using Sentence Transformers and FAISS
- 📄 Automatic research paper summarization with BART
- 🏷️ Keyword extraction using KeyBERT
- 🧠 Named Entity Recognition (NER) using spaCy
- 🤝 Similar research paper recommendations based on semantic similarity
- ⚡ Fast similarity search using FAISS indexing
- 📊 Search performance benchmarking
- 💾 Export extracted named entities to a CSV file

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Sentence Transformers
- FAISS
- Hugging Face Transformers
- BART
- KeyBERT
- spaCy
- Scikit-learn

---

## 📂 Dataset

The project uses a dataset of approximately **15,000 research papers** containing paper titles and abstracts. These abstracts are converted into embeddings, allowing the system to perform semantic similarity search instead of simple keyword matching.

---

## 🚀 How It Works

1. Load the research paper dataset.
2. Clean and preprocess the abstracts.
3. Generate embeddings using Sentence Transformers.
4. Store embeddings in a FAISS index.
5. Search papers using semantic similarity.
6. Generate a concise summary of the selected paper.
7. Extract important keywords.
8. Detect named entities such as organizations, locations, and people.
9. Recommend similar research papers based on embedding similarity.

---

## 📌 Example

### Search Query

```
Transformer models for medical image segmentation
```

### Output

- Top relevant research papers
- AI-generated summary
- Extracted keywords
- Named entities
- Similar research paper recommendations

---

## 📁 Project Structure

```
AI-Research-Paper-Search/
│
├── research_paper_search.ipynb
├── research_papers.csv
├── extracted_entities.csv
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/your-username/AI-Research-Paper-Search.git
```

Move into the project folder

```bash
cd AI-Research-Paper-Search
```

Install the required libraries

```bash
pip install -r requirements.txt
```

Download the spaCy English model

```bash
python -m spacy download en_core_web_sm
```

Run the notebook and start searching for research papers.

---

## 🎯 Future Improvements

- Streamlit web application
- PDF report generation
- Research trend visualization
- Paper filtering by research domain
- Citation analysis
- Interactive dashboard

---

## 📸 Demo

> Add screenshots or a short GIF here showing:
>
> - Semantic search results
> - Paper summary
> - Extracted keywords
> - Named entities
> - Similar paper recommendations

---

## 👨‍💻 Author

**Aditya Kumar**

If you found this project useful, feel free to ⭐ the repository.
