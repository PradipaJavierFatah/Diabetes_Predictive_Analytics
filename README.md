# Diabetes Predictive Analytics

![Project Status](https://img.shields.io/badge/Status-Completed-green)

## 📜 Deskripsi Proyek

Proyek ini bertujuan untuk membuat model prediktif yang dapat membantu menganalisis potensi diabetes pada pasien di Indonesia. Menggunakan data dari Kaggle dan generate Chat GPT, proyek ini mengeksplorasi tiga algoritma machine learning utama: **XGBoost Classifier**, **Random Forest Classifier**, dan **Decision Tree Classifier** untuk menganalisis dataset yang berisi 1879 data dengan 50 atribut.

**Catatan:** Diabetes merupakan kondisi kronis dengan tingkat prevalensi tinggi di Indonesia, sehingga analisis ini diharapkan dapat memberikan insight penting bagi dunia kesehatan.

---

## 🛠️ Teknologi yang Digunakan

- Python (Scikit-learn, XGBoost, Pandas, Matplotlib, Seaborn)
- Google Colab
- Data Cleaning, Normalization, dan Encoding
- Data Visualization
- Machine Learning Models

---

## 📋 Langkah-Langkah Analisis

1. **Data Understanding & Integration**
   - Menggabungkan dataset dari berbagai sumber.
   - Membersihkan data dari atribut yang tidak relevan, outlier, dan duplikasi.

2. **Data Preprocessing**
   - One-Hot Encoding dan Normalization.
   - Splitting data menjadi 80% training dan 20% testing.

3. **Modeling**
   - Membangun dan mengevaluasi tiga model: XGBoost, Random Forest, dan Decision Tree.

4. **Evaluasi Model**
   - Menggunakan metrik ROC AUC, KS Score, precision, recall, F1-score, dan akurasi.

---

## 📊 Hasil dan Insight

### **XGBoost Classifier**
- **ROC AUC:** 0.9551
- **Akurasi:** 93%
- **Kelebihan:** Performa terbaik dengan keseimbangan precision dan recall.
- **Kekurangan:** Recall untuk kelas positif perlu ditingkatkan.

### **Random Forest Classifier**
- **ROC AUC:** 0.9444
- **Akurasi:** 91%
- **Kelebihan:** Keseimbangan precision tinggi.
- **Kekurangan:** Recall kelas positif lebih rendah dibanding XGBoost.

### **Decision Tree Classifier**
- **Akurasi:** 89%
- **Kelebihan:** Model sederhana dan mudah dimengerti.
- **Kekurangan:** Precision dan recall lebih rendah dibanding model lain.

---

## 🔗 Link Pendukung
- **Dataset:** [Drive Dataset](https://drive.google.com/drive/folders/1-mhy-K5X9TceVMpxsG2-NJPJpINjOPAv?usp=sharing)
- **Dataset Penjelasan:** [Notion Dataset Details](https://steadfast-beard-007.notion.site/Penjelasan-Dataset-152e97aa4e8a803caa43ff7cc05e8672?pvs=4)
- **Repository GitHub:** [Diabetes Predictive Analytics](https://github.com/PradipaJavierFatah/Diabetes_Predictive_Analytics)

---

## 🤝 Kontributor

- **Pradipa Javier Fatah** (2602158815)
- **Muhammad Alvin** (2602135603)
- **Nathanael Sanliago Suhardjo** (2602190772)
- **Nixen Jenio** (2602159982)
- **Ngui Su Ying** (2602141051)
