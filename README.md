# 🧠 Auto Tagging Support Tickets using LLM

## 📌 Objective of the Task

The objective of this project is to automatically classify customer support tickets into relevant categories using a Large Language Model (LLM).

---

## 📊 Dataset Used

Customer Support Ticket Dataset containing free-text support queries and their corresponding categories.

---

## ⚙ Methodology / Approach

- Loaded real-world support ticket dataset
- Applied zero-shot classification using pre-trained LLM
- Used few-shot prompt engineering to improve predictions
- Generated top 3 predicted tags for each ticket
- Compared zero-shot vs few-shot performance using accuracy

---

## 📈 Key Results / Observations

- Zero-shot learning provides a good baseline without training
- Few-shot learning improves classification accuracy
- LLM effectively handles free-text ticket categorization
- Prompt engineering significantly enhances model performance
