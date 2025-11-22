# Anton Smirnov

**Computational Linguist | NLP Engineer | Corpus Architect**  
Based in Berlin. Working at the intersection of language, data, and meaning.

---

## Profile

Master’s student at Freie Universität Berlin in *Interdisciplinary Studies of the Middle East*, specializing in **computational linguistics**, **historical corpora**, and **vector-based language analysis**.  
Focus areas include the processing of Arabic, Persian, and Chinese texts through NLP pipelines, OCR, embeddings, and dimensionality reduction for **semantic retrieval**, **cluster analysis**, and **language change modeling**.

I design tools that:
- Extract structure from large, unstructured textual data  
- Visualize and interpret high-dimensional semantic spaces  
- Enable efficient retrieval and analysis of classical texts  

---

## Selected Projects

### [AskSunna](https://github.com/Quchluk/AskSunna)
A semantic retrieval system for classical Islamic texts with intelligent filtering and vector-based search.  
Implements a multilingual hadith database with **embedding-based retrieval**, **contextual filtering**, and **structured citation mapping**.

---

### [JLProj](https://github.com/Quchluk/jlproj)
**Johnson–Lindenstrauss Projection Toolkit** for dimensionality reduction in NLP and corpus linguistics.  
Provides fast, scalable embeddings projection with FAISS integration and evaluation utilities.  
Applied in temporal clustering of Arabic corpora and high-dimensional text analysis.

---

### [Research Paper Filter – LLM-Powered Document Relevance Analyzer](https://github.com/Quchluk/Research-Paper-Filter---Document-Relevance-Analyzer)
An intelligent document filtering system that uses **OCR** and **large language models** to identify relevant academic papers.  
Automates the process of reviewing and filtering PDF documents based on customizable research criteria.

**Features**
- OCR via Google Cloud Vision API  
- Relevance evaluation via DeepSeek V3.2 (OpenRouter)  
- CSV output with scoring and detailed logging  
- Batch processing with progress tracking  
- Environment-driven configuration and retry logic  

**Architecture**
1. `ocr_vision.py` — PDF text extraction  
2. `document_filter.py` — LLM-based filtering  
3. `prompt.py` — user-defined research criteria  

---

### [Arabic Quranic Text Lemmatizer](https://github.com/Quchluk/arabic-quran-lemmatizer)
An AI-based **lemmatization tool for Arabic text analysis**, focusing on the Quranic corpus.  
Processes 19,494 unique Arabic word forms and maps them to root lemmas using OpenRouter models.

**Core Functions**
- Lemmatization of Arabic words with frequency analysis  
- CSV outputs for lemma frequency and form analysis  
- Checkpoint/resume processing for long datasets  
- Structured corpus pipeline for linguistic research  

**Corpus Stats**
- 82,456 total words, 19,494 unique forms  
- Source: [semarketir/quranjson](https://github.com/semarketir/quranjson)  
- Top lemmas: من (4049), الله (2816), إن (2288)

---

## Technical Skills

**Languages:** Python, Bash, SQL, HTML  
**NLP:** BERT, Word2Vec, TF–DF, ChromaDB, LangChain, SpaCy, Farasa  
**Machine Learning:** PCA, TDA, KMeans, HDBSCAN, UMAP, FAISS  
**Infrastructure:** Git, Jupyter, Docker, Hugging Face, Streamlit  

---

## Languages

Russian (native), English (C2), Chinese (fluent), Arabic (fluent), German (B2)

---

## Contact

GitHub: [@Quchluk](https://github.com/Quchluk)  
Website: [antonsmirnov.de](https://www.antonsmirnov.de)  
Email: AntonSmirnovM@protonmail.com
