# How to Use

Open [Google Colab](https://colab.research.google.com/)

1. **File (Súbor)**
2. **Open notebook (Otvoriť zápisník)**
3. Select **GitHub**
4. Enter a link like:  
   ```
   https://github.com/andylucny/book/blob/master/01-1-single-neuron/single_neuron_training.ipynb
   ```
5. Open the found `single_neuron_training.ipynb`
6. Go to **Runtime → Change runtime type (Zmeniť typ prostredia) → T4 GPU**
7. Press **Ctrl+Enter** to run cells

or

1. click on "Run on Colab"
2. Go to **Runtime → Change runtime type (Zmeniť typ prostredia) → T4 GPU**
3. Press **Ctrl+Enter** to run cells

---

# How to stop

1. Runtime / Manage sessions (Spravovať relácie) / Stop (Ukončit)

---

# How to Convert

### Jupyter → Python
```bash
jupytext --to py notebook.ipynb
```

### Python → Jupyter
```bash
jupytext --to notebook python.py
```

