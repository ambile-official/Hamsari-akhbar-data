# 📰 Hamsari Akhbar – Preprocessed Sindhi Text Dataset

### 🏛️ Source: Hamsari Akhbar (Sindhi Newspaper & Articles Collection)  
### 📤 Uploaded & Curated by: *Abdul Majid Bhurgiri, Institute of Language Engineering*  
### 📅 Release: 2025  
### 🌍 Language: Sindhi (سنڌي)  
### 📦 Dataset Type: Preprocessed Newspaper & Article Corpus

---

## 📖 Overview

The **Hamsari Akhbar Dataset** is a high-quality, **Sindhi news and article corpus**, carefully collected and preprocessed from the *Hamsari Akhbar* publication archives.  

This dataset is designed for **Natural Language Processing (NLP)** applications and research, providing a clean, ready-to-use text corpus ideal for **language modeling**, **classification**, **summarization**, and **translation** tasks in Sindhi.

---

## 🧹 Data Cleaning & Preprocessing

The dataset has undergone extensive preprocessing to ensure textual quality and consistency for model training.  
The following cleaning steps were applied:

- ✅ Removed all **email addresses**  
- ✅ Removed **URLs and links**  
- ✅ Removed **special characters**, **punctuation noise**, and **emojis**  
- ✅ Removed **non-Sindhi words** and **foreign language segments**  
- ✅ Normalized Sindhi **Unicode characters**  
- ✅ Removed unnecessary line breaks and extra spaces  
- ✅ Ensured **UTF-8** encoding for compatibility  

The result is a **clean and standardized Sindhi corpus** suitable for direct input to modern NLP models.

---

## 📂 Dataset Contents

| File Name | Description | Format | Encoding |
|------------|-------------|---------|-----------|
| `Hamsari_Akhbar_Preprocessed.txt` | Clean Sindhi newspaper and article corpus | `.txt` | UTF-8 |

Each line represents a cleaned segment of text extracted from *Hamsari Akhbar* articles.

---

## 🧠 Research Applications

This dataset can be used for a variety of **Sindhi NLP research and AI applications**, including:

- 🗣️ **Language Modeling** – Train or fine-tune LLMs and GPT-style models  
- 💬 **Chatbots** – Build Sindhi conversational systems and news assistants  
- 🧩 **Embedding Training** – Create or enhance Sindhi text embeddings  
- 📊 **Sentiment Analysis** – Develop classifiers for news opinions or tone  
- 📰 **Summarization Models** – Generate automatic Sindhi news summaries  
- 🌐 **Translation Models** – Train Sindhi ↔ English or Sindhi ↔ Urdu translation systems  

---

## ⚙️ Technical Details

- **Data Source:** Hamsari Akhbar (News Articles)  
- **Data Type:** News, opinion, and editorial content in Sindhi  
- **File Format:** Plain text (`.txt`)  
- **Encoding:** UTF-8  
- **Preprocessing:** Complete cleaning pipeline (no manual post-processing required)  

### Example (Python)

```python
with open("Hamsari_Akhbar_Preprocessed.txt", "r", encoding="utf-8") as f:
    text = f.read()

print(text[:500])  # Preview first 500 characters
