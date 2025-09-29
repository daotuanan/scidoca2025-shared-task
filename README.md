# SCIDOCA 2025 Shared Task Dataset
**Citation Prediction, Discovery, and Placement**

This repository provides the official dataset for the **SCIDOCA 2025 Shared Task**, which addresses citation modeling in scientific documents. The dataset supports three subtasks designed to evaluate citation discovery, prediction, and placement, encouraging progress in scholarly document understanding.

---

## 📌 Subtasks
The dataset includes three subtasks:

1. **Citation Discovery**  
   Identify relevant references for a given paragraph from a list of candidate papers.  

2. **Masked Citation Prediction**  
   Predict the correct citation for masked citation slots within a paragraph.  

3. **Citation Sentence Prediction**  
   Determine the correct reference(s) for each sentence that requires a citation.  

---

## 📂 Dataset Overview
- **Source**: Derived from the [Semantic Scholar Open Research Corpus (S2ORC)](https://allenai.org/data/s2orc).  
- **Training Set**:
  - 10,000 scientific papers  
  - 61,556 annotated paragraphs  
  - Avg. 2.11 gold citations and 18.04 candidate references per paragraph  
- **Test Set**:
  - 1,000 paragraphs from distinct papers  
  - Each annotated with gold citations and distractor candidates  

---

## ⚖️ Data Usage Rules
- No external citation-specific datasets or services (e.g., CrossRef, PubMed).  
- General-purpose pretrained models (e.g., BERT, RoBERTa) are allowed.  
- Citation-specific pretrained models (e.g., SPECTER, Galactica) are prohibited.  

---

## 📊 Evaluation
- **Citation Discovery**: Precision, Recall, F1  
- **Masked Citation Prediction**: Macro-averaged F1 across masked slots  
- **Citation Sentence Prediction**: Sentence-level F1 + no-citation accuracy  

Details are available in the *SCIDOCA 2025 overview paper*.  

---

## 🔗 Reference
If you use this dataset, please cite: 
