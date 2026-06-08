# Introduction to Generative AI with HuggingFace

This repository contains my learning progress and hands-on exercises with Generative AI, utilizing the powerful **HuggingFace Transformers** library.

The main artifact in this repository is a Jupyter Notebook (`HuggingFace_demo.ipynb`) demonstrating various GenAI capabilities.

## 🚀 Skills & Concepts Demonstrated

Through this notebook, I've practically explored and implemented:

- **HuggingFace Pipelines:** Utilizing pre-built pipelines for out-of-the-box machine learning tasks.
- **Model Loading:** Downloading and caching pre-trained models from the HuggingFace Hub.
- **Tokenization:** Converting text into a format understandable by Transformer models.
- **Text Generation & NLP:** Applying Large Language Models (LLMs) to perform tasks such as text completion, sentiment analysis, and summarization.
- **PyTorch/TensorFlow Integration:** Running models using deep learning frameworks as backends.

## 🛠️ Mini-Projects Included

### 1. Academic Paper Summarizer (ArXiv API + BART)
At the end of the notebook, I built a practical mini-project that:
- Automatically fetches recent AI and Machine Learning research papers using the **ArXiv API**.
- Extracts the complex, dense abstracts of these papers.
- Uses a Hugging Face text summarization model (`facebook/bart-large-cnn`) to automatically condense the academic text into short, easy-to-read summaries.
- **Expected Output:** A 2-3 sentence plain-English summary of a highly technical research paper.

## 💻 How to Run Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/abdullah763/HuggingFace-NLP-Basics.git
   cd HuggingFace-NLP-Basics
   ```

2. **Install the dependencies:**
   It is recommended to use a virtual environment.
   ```bash
   pip install -r requirements.txt
   ```

3. **Open the Notebook:**
   Start Jupyter Notebook or Jupyter Lab:
   ```bash
   jupyter notebook HuggingFace_demo.ipynb
   ```
   *Alternatively, you can upload this notebook directly to [Google Colab](https://colab.research.google.com/) for easy execution with free GPU support.*

## 📚 Credits & Acknowledgements

This project was built following the comprehensive **Generative AI** tutorial provided by **freeCodeCamp.org**, taught by the excellent instructor **dswithbuppy**. 

* Tutorial Source: freeCodeCamp.org YouTube Channel
* Instructor: dswithbuppy
