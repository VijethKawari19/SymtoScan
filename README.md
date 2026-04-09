# SymtoScan 

### AI-Driven Precision Diagnosis Assistant for Smart Healthcare Decisions

SymtoScan is an AI-powered medical assistant that analyzes symptoms, predicts possible medical conditions, recommends drugs, suggests alternatives, and warns about side effects — all from a simple conversational interface.

> ⚠️ **Disclaimer:** This tool is for informational purposes only and does not replace professional medical advice.

---

## 📌 Problem Statement
Designing and developing an AI-powered medical diagnosis assistant to provide safe and reliable treatment recommendations — accessible from home, without requiring a doctor's visit for every query.

---
## ✨ Features
- 🔍 **Symptom Analysis** — Select body part and symptoms through an interactive UI
- 🧠 **Disease Prediction** — Predicts likely medical condition using fine-tuned FLAN-T5
- 💊 **Drug Recommendation** — Suggests primary and alternative medicines
- ⚠️ **Side Effect Prediction** — Warns about potential adverse drug reactions
- 🌐 **Web Interface** — Built with Gradio for easy, no-code interaction

---

## 🧠 Model
This project uses **FLAN-T5 (Small)** — a lightweight, open-source instruction-tuned model by Google.

| Why FLAN-T5? |
|---|
| ✅ Free & open-source — no API keys needed |
| ✅ Runs on Google Colab or personal GPU |
| ✅ Privacy-preserving (fully offline capable) |
| ✅ Fine-tuned on custom medical dataset |

---

## 📊 Results

| Task | Accuracy |
|---|---|
| Condition Prediction | 85% |
| Drug Suggestion | 65% |
| Side Effect Prediction | 60% |

---

## 🛠️ Tech Stack
- **Model:** FLAN-T5 (Hugging Face Transformers)
- **UI:** Gradio
- **Data Processing:** Pandas, CSV
- **Backend Logic:** Python, Regex
- **Training:** Google Colab

---
