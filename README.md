# Introduction to Generative AI with HuggingFace 🤗

This repository contains my learning progress and hands-on projects with **Generative AI**, built using the powerful **HuggingFace Transformers** library.

All notebooks are beginner-friendly, fully commented, and follow the comprehensive **Generative AI** tutorial by **dswithbuppy** on freeCodeCamp.org.

---

## 📂 Notebooks

| Notebook | Description |
|---|---|
| [`HuggingFace_demo.ipynb`](./HuggingFace_demo.ipynb) | Core HuggingFace concepts: pipelines, tokenization, NLP tasks, and an ArXiv paper summarizer mini-project |
| [`Project Text Summarizer.ipynb`](./Project%20Text%20Summarizer.ipynb) | Full fine-tuning project: train PEGASUS on the SAMSum dataset for dialogue summarization |

---

## 🚀 Skills & Concepts Demonstrated

- **HuggingFace Pipelines:** Using pre-built pipelines for NLP tasks out of the box.
- **Model Loading:** Downloading and caching pre-trained models from the HuggingFace Hub.
- **Tokenization:** Converting text into token IDs that Transformer models understand.
- **NLP Tasks:** Sentiment analysis, text generation, question answering, and summarization.
- **Seq2Seq Fine-Tuning:** Training an encoder-decoder model (PEGASUS) on a custom dataset.
- **ROUGE Evaluation:** Measuring summarization quality with industry-standard metrics.
- **Dataset Handling:** Loading and preprocessing datasets with the HuggingFace `datasets` library.

---

## 🛠️ Mini-Projects Included

### 1. 📄 Academic Paper Summarizer (ArXiv API + BART)
*Inside `HuggingFace_demo.ipynb`*

- Fetches recent AI/ML research papers using the **ArXiv API**.
- Extracts dense academic abstracts from the papers.
- Summarizes them into plain English using `facebook/bart-large-cnn`.
- **Expected Output:** A 2-3 sentence easy-to-read summary of a highly technical paper.

---

### 2. 💬 Dialogue Summarizer — Fine-tuned PEGASUS
*Inside `Project Text Summarizer.ipynb`*

A full end-to-end fine-tuning project based on the **dswithbuppy / freeCodeCamp** tutorial:

- Loads the **SAMSum** dataset — a collection of messenger-style dialogues with human-written summaries.
- Fine-tunes Google's **PEGASUS** model (`google/pegasus-cnn_dailymail`) for dialogue summarization.
- Evaluates performance using **ROUGE-1, ROUGE-2, ROUGE-L** metrics.
- Saves the fine-tuned model and runs inference on real test samples.
- **Expected Output:** A clean, concise summary of a multi-turn conversation.

> 💡 **Note:** This project requires a GPU (T4 or better). Use **Google Colab** with a free GPU runtime for best results.

---

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

3. **Open a Notebook:**
   ```bash
   jupyter notebook
   ```
   *Alternatively, upload any notebook directly to [Google Colab](https://colab.research.google.com/) for free GPU access.*

> ⚠️ **Avoid 429 Rate-Limit Errors:** The notebooks include a Hugging Face login cell. Run it with your free token from [huggingface.co/settings/tokens](https://huggingface.co/settings/tokens) before downloading any models.

---

## 📚 Credits & Acknowledgements

This repository follows the **Generative AI** tutorial series by **dswithbuppy** on freeCodeCamp.org.

* **Tutorial Source:** [freeCodeCamp.org YouTube Channel](https://www.youtube.com/@freecodecamp)
* **Instructor:** dswithbuppy
