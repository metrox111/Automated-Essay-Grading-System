---


# 📝 Automated Essay Grader (BERT + Gradio)

An end-to-end deep learning app that scores essays using a fine-tuned BERT model and provides a simple web UI via Gradio.

---

## 🚀 Overview

This project trains and deploys a transformer-based model (BERT) to evaluate and grade student essays. The model understands context, coherence, and semantic quality to predict a score. A Gradio interface wraps the backend, making it accessible via browser.

---

## 🔧 Features

- Fine-tuned BERT model for essay scoring
- Optional experiments with LSTM and RoBERTa (included)
- Clean, interactive UI using Gradio
- Handles raw text input and outputs score prediction in real time

---

## 🧠 Model Details

- **Backbone:** BERT (`bert-base-uncased`)
- **Training Data:** Essay datasets (Kaggle / ASAP)
- **Loss Function:** MSE (for regression)
- **Other Models Tried:** LSTM, RoBERTa

> 📁 Check notebooks:
> - `bert-train-val.ipynb` — BERT training + validation
> - `roberta-train.ipynb` — RoBERTa training experiment
> - `LSTM.ipynb` — LSTM-based baseline
> - `gradio_proto1axe.ipynb` — Gradio app implementation

---

## 🖥 Gradio UI

The Gradio interface lets you:

- Paste or type an essay
- Get an instant predicted score
- (Optional) Visualize model confidence or intermediate outputs

## 📊 Example Output

**Input Essay:**

> “Technology is shaping education by improving access...”

**Predicted Score:** `8.5 / 10`

---

## 🗂 File Structure

```
/
├── bert-train-val.ipynb     # BERT training notebook
├── roberta-train.ipynb      # RoBERTa experiment
├── LSTM.ipynb               # Baseline LSTM model
├── gradio_proto1axe.ipynb   # Gradio app frontend
├── Classic_Models.ipynb     # Traditional baselines
├── README.md
```

---

## 📄 License

MIT License — use it, modify it, build your own grading AI.

---

## 📬 Contact

Built by [@metrox111](https://github.com/metrox111).
DM or open an issue for feedback, collabs, or feature requests.

```

---


