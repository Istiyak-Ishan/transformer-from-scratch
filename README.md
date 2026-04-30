#  Transformer From Scratch → Mini GPT

A complete implementation of a Transformer-based language model built from scratch.
Covers math, NumPy attention, PyTorch model, and GPT-style text generation.

##  Features

* Self-Attention (NumPy)
* Transformer Blocks (PyTorch)
* Mini GPT (decoder-only)
* Causal Masking (GPT logic)
* Text Generation (temperature + top-k sampling)


## 📂 Structure

```id="y6n0k1"
transformer-from-scratch/
├── transformer_notebook.ipynb
├── data/train.csv
├── data/validation.csv
├── data/test.csv
├── README.md
└── requirements.txt
```


##  Quickstart

```bash id="1u0q6l"
pip install -r requirements.txt
jupyter notebook
```

Open:

```id="9uxm8d"
transformer_notebook.ipynb
```

---

##  What It Shows

* How attention works mathematically
* How Transformers are built step-by-step
* How GPT models are trained
* How text is generated from scratch

---

##  Results

Model learns:

* character patterns
* word formation
* basic sentence structure

Example:

```id="z1m5x7"
TUS:
And for his fair, I am it, but in the world of lame,
His way speed in his death and made on thou hast thou wilt be conspect.

DUCHESS OF YORK:
I do the stop of thy suit was my country.

KING RICHARD III:
Why, is a humour with the fix'd;
And thou desperain pack who was a dare to ask
If the world
```


## Stack

Python · NumPy · PyTorch · Pandas · Matplotlib



## Next Steps

* Better tokenization (BPE)
* Larger dataset
* Streamlit UI (chatbot)


