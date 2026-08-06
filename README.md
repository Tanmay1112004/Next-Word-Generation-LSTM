# 🎬 Next Word Generation using LSTM

Language models power everything from **autocomplete to AI assistants**.
This project builds a **Next Word Prediction system** using **Long Short-Term Memory** trained on the **TMDB 5000 Movies Dataset**.

The model learns patterns from movie titles and predicts the **most likely next word in a sequence**.
An interactive **Gradio** interface allows users to test predictions in real time.

---

# Demo Images

![demo](https://github.com/Tanmay1112004/Next-Word-Generation-LSTM/blob/main/Next-Word-Generation-LSTM/screenshots/Screenshot%202025-09-17%20205339.png)

![demo](https://github.com/Tanmay1112004/Next-Word-Generation-LSTM/blob/main/Next-Word-Generation-LSTM/screenshots/Screenshot%202025-09-17%20205339.png)

---

# 🚀 Key Features

* Text preprocessing and tokenization
* LSTM-based sequence prediction model
* Training visualization using loss & accuracy curves
* Saved trained model (`.h5`)
* Interactive Gradio UI
* Adjustable **Top-K predictions**
* Clean dark-themed demo interface

This project demonstrates the **end-to-end workflow of a deep learning NLP system**.

---

# 📂 Project Structure

```bash
Next-Word-Generation-LSTM/
 ├── Next_Word_Prediction.ipynb
 ├── nwp.h5
 ├── tmdb_5000_movies.csv
 └── README.md
```

Each component serves a specific role:

* Notebook → training & experimentation
* `.h5` → serialized trained model
* dataset → training corpus
* README → project documentation

Minimal structure. Clear workflow.

---

# 🧠 Model Architecture

The model uses **LSTM layers** designed for sequential text data.

Pipeline:

1. Text cleaning
2. Tokenization
3. Sequence generation
4. Padding sequences
5. LSTM model training
6. Prediction generation

Why LSTM?

Because it captures **long-term dependencies in sequences**, making it ideal for **language modeling tasks**.

---

# 🛠 Technology Stack

* Python
* TensorFlow / Keras
* Pandas
* NumPy
* Matplotlib
* Gradio

This stack enables **deep learning training + interactive ML deployment**.

---

# ⚡ Quick Start

### Clone the repository

```bash
git clone https://github.com/Tanmay1112004/Next-Word-Generation-LSTM.git
cd Next-Word-Generation-LSTM
```

### Install dependencies

```bash
pip install tensorflow gradio matplotlib pandas numpy
```

### Run the notebook

```bash
jupyter notebook Next_Word_Prediction.ipynb
```

Launch the interactive app:

```python
demo.launch(share=True)
```

---

# 🎯 Example Prediction

**Seed Input**

```
The Lord
```

**Generated Output**

```
The Lord of the Rings
```

The model predicts the next word by selecting from the **top probability candidates**.

---

# 📊 Training Visualization

The notebook includes:

* Training accuracy curve
* Loss curve
* Model convergence analysis

These visualizations help evaluate model learning behavior.

---

# 🤝 Acknowledgements

Dataset source:
**TMDB 5000 Movies Dataset**

---

# ⭐ Support the Project

If you found this useful:

⭐ Star the repository
🍴 Fork it
🚀 Build something on top of it

---
