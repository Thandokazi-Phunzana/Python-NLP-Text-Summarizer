# NLP Text Summarizer

**NLP Text Summarizer** is a Python-based NLP project that automatically generates concise summaries of text documents.  
It uses a **graph-based extractive summarization approach** combining TF-IDF and PageRank (TextRank) to identify the most important sentences.

## Features

- Preprocesses text with **NLTK** (tokenization, stopword removal, lemmatization)  
- Uses **TF-IDF** to calculate sentence importance  
- Applies **PageRank** to rank sentences in a similarity graph  
- Generates **extractive summaries** of any input text  
- Outputs:
  - `output.txt` – the summary  
  - `graph.png` – visual graph of sentence similarity  

## Installation

1. Clone the repository:

```bash
git clone https://github.com/Thandokazi-Phunzana/NLP-Text-Summarizer.git
cd NLP-Text-Summarizer
