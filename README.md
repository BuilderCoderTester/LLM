# Building an LLM From Scratch 🧠 (Word Embedding Project)

This repository documents my personal journey to build a basic **Large Language Model (LLM) from the ground up** using pure Python and fundamental libraries (like NumPy or PyTorch, if used). The goal is to deeply understand the core Transformer architecture without relying on high-level, pre-packaged frameworks.

This is an **active, ongoing project**. New commits reflect progress, challenges, and core learnings in deep learning and NLP.

---

## 🚀 Current Focus & Progress

The main focus right now is establishing the foundational components of the model.

### Key Milestones Completed:

* **Custom Tokenization:** Implemented a basic tokenizer to preprocess the raw text data.
* **Word Embeddings:** Created the initial word embedding layer to convert tokens into vector representations.
* **Positional Encoding (Current Focus):** Successfully implemented the **sine and cosine Positional Encoding** functions. This critical step teaches the model about the sequence and order of words in the input.

### Next Steps:

* [ ] Implement the **Multi-Head Self-Attention** block.
* [ ] Construct the full **Transformer Decoder Block**.
* [ ] Set up the core **training loop** for the model's first run.

---

## 📂 Repository Structure

The core logic and sequential development can be followed in the Jupyter Notebook:

* **`wordembed.ipynb`**: This is the main development notebook. It contains all the code, step-by-step explanations (in markdown cells), implementation logic, and initial test runs.

---

## 🛠️ Technologies & Dependencies

* **Language:** Python
* **Core Libraries:** [List the main libraries you are using, e.g., PyTorch, NumPy, Pandas]
    * `numpy` (for mathematical operations)
    * `[pytorch , pandas ,tiktoken ......]`
* **Environment:** This notebook was initially developed on Kaggle.

---

## 📚 Learning Resources & Credit

This project is a learning endeavor guided by the excellent work of experts in the field.

I am currently following the **[Build an LLM from Scratch]** by **[Sebastian Raschka]**. The detailed instruction has been invaluable for grasping the complex mathematical foundations.

---


This is primarily a learning project, but any constructive feedback, bug reports, or suggestions on improving the efficiency or clarity of the implementation are welcome!

If you'd like to reach out, connect with me on E-mail: **[sarkaranurag556@gmail.com]**
