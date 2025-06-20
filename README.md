# WholeLearnerBot

**WholeLearnerBot** is a lightweight, interpretable AI tutor that uses emotion recognition, Bloom’s taxonomy classification, and SEF scoring to evaluate learner inputs. Designed for educators and researchers, it runs entirely in Python and is fully Colab-compatible. It is NLP Project.

---

## 🎯 Key Benefits

- **Emotion-Aware Feedback** – Detects learner emotions (e.g., joy, frustration) using logistic regression on TF-IDF.
- **Cognitive Tier Detection** – Classifies input into Bloom’s levels (1–6) to gauge depth of understanding.
- **SEF Scoring** – Computes semantic similarity between learner input and expected objectives.
- **SBERT SEF Option** – Supports cosine similarity with `all-MiniLM-L6-v2` for richer embeddings.
- **Structured Logging** – Captures inputs, predictions, responses, and scores in `logs/logs.csv`.
- **Easy to Extend** – Swap models, integrate LLMs, or update objectives without retraining everything.

---
