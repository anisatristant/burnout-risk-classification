# 🧠 Employee Burnout Risk Prediction System

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=microsoftpowerbi&logoColor=black)

## 📌 Deskripsi Proyek
Proyek ini bertujuan untuk mendeteksi risiko **Burnout** (kelelahan kerja) pada karyawan secara otomatis menggunakan algoritma **Machine Learning**. Sistem ini mengklasifikasikan karyawan ke dalam tiga tingkat risiko: **Low**, **Medium**, atau **High** berdasarkan pola jam kerja, tingkat stres, dan kualitas tidur.

Analisis ini membantu perusahaan melakukan deteksi dini agar kesejahteraan mental karyawan tetap terjaga sebelum produktivitas menurun.

---

## 📊 Visualisasi Data (Power BI Dashboard)
Selain pemodelan prediktif, proyek ini mencakup analisis visual interaktif untuk memahami korelasi antar faktor kesehatan mental karyawan.

### 1. Mental Health Overview
Dashboard ini memberikan gambaran umum mengenai tingkat stres, produktivitas, dan risiko burnout berdasarkan mode kerja karyawan.
![Mental Health Overview](dashboard/mental%20health%20overview.png)

### 2. Physical Health & Lifestyle Analysis
Dashboard ini menganalisis bagaimana faktor gaya hidup seperti durasi tidur dan aktivitas fisik berdampak langsung pada tingkat stres karyawan.
![Physical Health Analysis](dashboard/physical%20health%20analysis.png)

---

## 📉 Temuan Utama (Insights)
Berdasarkan hasil visualisasi dan pemodelan menggunakan **Random Forest**:
*   **Korelasi Stres & Produktivitas:** Terdapat ambang batas stres tertentu di mana produktivitas mulai menurun secara signifikan saat risiko burnout meningkat ke level "High".
*   **Pola Tidur:** Karyawan dengan rata-rata tidur yang rendah memiliki kecenderungan tingkat stres yang lebih tinggi secara konsisten.
*   **Beban Kerja:** Karyawan dengan kategori *Overworked* (>50 jam/minggu) mendominasi kategori risiko burnout tinggi.
*   **Faktor Pendukung:** Akses ke dukungan kesehatan mental memiliki korelasi positif terhadap stabilitas performa karyawan.

---

## 🚀 Cara Menjalankan Proyek
Untuk mencoba analisis ini, Anda bisa mengikuti langkah berikut:

1.  **Siapkan Dataset:**
    Gunakan file `mental_health_productivity.csv` yang tersedia di repository ini.
2.  **Jalankan Notebook:**
    Buka file `Klasifikasi_Burnout_Risk.ipynb` menggunakan Jupyter Notebook atau Google Colab.
3.  **Instal Library:**
    Jika menjalankan secara lokal, pastikan sudah menginstal library yang diperlukan:
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn
    ```

---

### 👨‍💻 Disusun Oleh:
**Annisa Tristanti**

🔗 **Mari Terkoneksi di LinkedIn:**
[Klik di Sini untuk Profil LinkedIn Saya](https://www.linkedin.com/in/annisatristanti/)

---
*Proyek ini dikembangkan sebagai bagian dari portofolio Analisis Data dan Machine Learning.*
