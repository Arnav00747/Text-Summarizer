#  Text Summarizer using Transformers 

This project demonstrates how to perform **abstractive text summarization** using the `transformers` library from HuggingFace. It allows you to input long text and generate a short, meaningful summary using pre-trained transformer models like `t5-small` or `bart-large-cnn`.

---

##  Features

- Abstractive Summarization using HuggingFace `pipeline`
- Pre-trained model: `t5-small` (can change to others like `bart-large-cnn`)
- Simple and efficient – works in just a few lines
- Easy to use with Jupyter Notebook (Anaconda)

---

##  Requirements

Install the required packages before running:

pip install transformers
pip install torch
Run summarizer.ipynb in Jupyter or Anaconda.
## How to run:

1. Open `summarizer.ipynb` in Jupyter Notebook.
2. Replace the `text` variable with your own paragraph.
3. Run the cells.
4. The model will print a short summary of the input.

## Example Output

**Input:**
> Natural Language Processing (NLP) is a subfield of artificial intelligence...

**Summary:**
> NLP is a branch of AI that helps computers understand human language.
