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



![aes](https://github.com/user-attachments/assets/765cde80-acc1-4001-996a-1f6f3c5be156)

![bc58de28-b187-43bc-9243-b90d870e220d](https://github.com/user-attachments/assets/dbcb50d8-be7b-483b-9ed0-7edb96aa94e4)

![5abaa173-7740-4b4a-acad-453e28706ad5](https://github.com/user-attachments/assets/004c7af0-6505-41d3-b167-124885426045)



![69f9ea12-c3b8-46c3-8ba9-192112254e52](https://github.com/user-attachments/assets/56a6533f-d0be-44bf-a143-c5bae15931a6)




<img width="846" height="470" alt="roberta rmse vs mse" src="https://github.com/user-attachments/assets/ef0e6363-cb8e-4937-85dc-f7f69294d61d" />


