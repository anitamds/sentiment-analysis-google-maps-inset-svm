# Sentiment Analysis of Google Maps Reviews Using SVM

This repository contains the implementation and documentation of an undergraduate thesis entitled:

**"ANALISIS SENTIMEN ULASAN GOOGLE MAPS DENGAN PENDEKATAN LABELLING LEXICON INSET DAN METODE SUPPORT VECTOR MACHINE UNTUK PERUMUSAN STRATEGI SWOT (STUDI KASUS: TIGA PUTRA KAWI MALANG)"**

---

## 📌 Research Overview

The rapid growth of online review platforms such as *Google Maps* allows customers to express opinions and experiences regarding a business. These reviews provide valuable insights that can be utilized for business decision-making and strategy formulation.

This research aims to analyze customer sentiment toward **Toko Tiga Putra Kawi Malang** based on *Google Maps* reviews and to utilize the results for business strategy formulation using **SWOT analysis**.

---

## 📊 Dataset

- **Source**: Google Maps Reviews  
- **Collection Method**: Web scraping using *Apify*
- **Time Period**: September 2017 – October 2025  
- **Total Reviews**: 1,657 valid reviews

---

## ⚙️ Methodology

The research workflow consists of the following stages:

1. **Text Preprocessing**
   - Cleaning
   - Tokenizing
   - Normalization
   - Stopword Removal
   - Stemming

2. **Sentiment Labeling**
   - Automatic labeling using **Lexicon InSet**

3. **Feature Extraction**
   - Term Frequency–Inverse Document Frequency (*TF-IDF*)

4. **Data Splitting**
   - Stratified Sampling (Training & Testing Data)

5. **Class Imbalance Handling**
   - Random Oversampling (applied only to training data)

6. **Classification**
   - Support Vector Machine (*SVM*)
   - Kernel: Radial Basis Function (*RBF*)
   - Hyperparameter tuning using GridSearchCV

7. **Evaluation**
   - Accuracy
   - Classification Report
   - Confusion Matrix

8. **Business Strategy Analysis**
   - Mapping sentiment results into **SWOT matrix**
   - Strategy recommendation formulation

---

## 📈 Results

- **Test Accuracy**: **90.45%**
- The SVM model demonstrates stable performance without significant overfitting.
- Sentiment analysis results were successfully utilized to generate SWOT-based business strategies.

---

## 🛠 Tools & Libraries

- Python
- Scikit-learn
- Imbalanced-learn
- Pandas
- NumPy
- NLTK / Sastrawi
- Apify

---

## 📁 Repository Structure
├── dataset/
│ └── dataset.csv
├── tiga_putra_final.ipynb
├── model_hasil/
│ ├── svm_sentiment_model.pkl
│ └── tfidf_vectorizer.pkl
├── kamus/
│ ├── kamus_eksternal.txt
│ └── kamus_internal.txt
├── analisis_swot/
│ ├── analisis_swot_final.xlsx
├── README.md


---

## 👩‍🎓 Author

**Anita Silalahi**  
Undergraduate Student  
Informatics / Computer Science  

---

## 📄 License

This project is intended for academic and research purposes.


